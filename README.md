# Rust_client-server_chat

# A simple rust client/server chat program

## Run `cargo run` to run the app, run `cargo build` to build an executable file.

### Check out the Youtube Tutorial for this [Rust Tutorial](https://youtu.be/CIhlfJSvxe4).  Here is our [Youtube Channel](https://www.youtube.com/channel/UCYqCZOwHbnPwyjawKfE21wg) Subscribe for more content.

### Check out our blog at [tensor-programming.com](http://tensor-programming.com/).

### Our [Twitter](https://twitter.com/TensorProgram), our [facebook](https://www.facebook.com/Tensor-Programming-1197847143611799/) and our [Steemit](https://steemit.com/@tensor).

# purplemass updates May 2020

Thanks to Tensor Programming for their excellent chat app in Rust.

A few tweaks were made to this to make it work across different computers. The only requirement for this is to set an environment variable of the server for the client app like this (tested on macOS):

    export BAM_SERVER_IP="xxx.xxx.xxx.xxx"

where `xxx.xxx.xxx.xxx` is the IP address of the server.

The port used can only be set in the source code and is left unchanged as `6000`.
