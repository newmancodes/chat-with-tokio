# Creating a Chat Server with async Rust and Tokio

Learning more about [Rust](https://www.rust-lang.org/) and [Tokio](https://tokio.rs) by following along with [Creating a Chat Server with async Rust and Tokio](https://www.youtube.com/watch?v=4DqP57BHaXI) from [Lily Mara](https://twitter.com/TheLily_Mara).

## How to use

Clone the code from the repo and cd into the project root.

> cargo run --release

This will compile and start up the server.

From another terminal session

> telnet localhost 8080

Will create a connection to the server. Typing a message and hitting return will be sent, but you won't see anything, for that you need another client to chat with.

From (yet) another terminal session

> telnet localhost 8080

Now we have two clients connected we can talk between them. Pretty simple stuff and well explained in the linked video. Well worth a watch.