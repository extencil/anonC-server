# Anon Chat (server)

anonC (Anon Chat) is an simple and open source messenger that secure your conversations with E2E encryption.

Your messages are encrypted using keys stored on your device, the server never got access to your keys.

# Todo
- [ ] MVP
    - **An user needs to connect and talk securely with another user**. I prefer to use [GSRN](https://github.com/hackerschoice/gsocket) because i like the E2E encryption of GSRN, providing an double E2E encryption (eg: GSRN Encrypt the network data and anonC app encrypt conversation data again). In other ways, Tor Project or P2P can be used.
- [ ] Rooms features
    - **An user can connect into a server, join in a room and talk securely with a group**.
- [ ] Segfault's Chat App
    - **Use [segfault](https://www.thc.org/segfault/) to run a new client instance securely**. Maybe, with `udocker`? In other ways, we can use the GSocket tools for running a new instance. My idea is:
        - 1: User open terminal
        - 2: User type something like: `gs-netcat -k secretchatapp -i`
        - 3: User can chat with another users or private chat with some friend.
- [ ] GUI Version
    - **An GUI Version for an user friendly interface**. Why not? I prefer to use `ElectronJS`, but we can look some python libs.