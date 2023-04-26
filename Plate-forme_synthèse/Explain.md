ENVIRONNMENT
the main environnment of the blockchain will be based on python, c++, go and javascript languages ​​to run client software and applications.
the environment will thus be a network making it possible to deploy several blockchains and clones of blockchains and to access them via suitable entry points.


Blockchain initialization
This step consists of manually defining a first block by creating a JSON file. This block must contain all the characteristics of the chain. Thus, the random value used by the cryptographic hash, the level of requirement linked to the cryptographic processing and the validation time between two successive blocks are essential parameters to be informed.
Once the file is well populated, it will be up to the client to create the blockchain folder and initialize it. That said, the commands will be replicated as many times as your network has nodes.Choosing a good consensus protocol
Here, it comes down to validating and securing the content of the blocks through a consensus protocol. The latter varies depending on whether your blockchain is public or private. Thus, due to the high number of actors and the multitude of nodes existing in a public blockchain, the concept of proof of work is the most suitable protocol.

On the other hand, in a private configuration, consensus protocols such as proof of stake or proof of authority lend themselves more readily. That said, the protocol chosen as well as the number of nodes are entered in the configuration file which is executed in a command line.
