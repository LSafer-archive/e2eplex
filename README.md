# e2eplex
A project to make TRUE end-to-end encryption possible!



For a true E2E un-spy-able encryption, we need to split the work into multiple pieces.

This is my first thoughts:


Human <--> Codec <--> Human <--> Cleint <--> ((Server)) <--> Client <--> Human <--> Codec <--> Human

- The `((server))` is the center of the conversation. It could be any message service provider. Even SMS or E-Mail (even thought it is discoraged)!
- The `Cleint` (in any side) is the application that talks to the server. It could be any client application.
- The `Human` is the human in that side.
- The `Codec` is our project.

Our project is to not trust the `Server`, the `Client` application nor the `Client` device itself!.
So, the solution (as I think) is to trust nobody, split the work, make everything clear, safe and organized. Then, automate everything.

### Q/A
- Q: When will you start the project?
  - A: I do not know
  
- Q: How could I help?
  - A: open an issue or fork the repo and do a pull-request.

- Q: I do not understand what you are going to do?
  - A: I do not understand ether! I am learning afterall! This is first thoughts that came in my mind and I just wrote it for me to do it later.
