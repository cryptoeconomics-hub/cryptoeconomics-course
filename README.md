# Why is this stuff important?

Under every blockchain design there is some cryptoeconomics involved; and under every blockchain projects, there is too. Cryptoeconomics is the **secret ingredient** required in order for open, decentralised, secure, neutral, distributed network to work properly.

This is still early stage for cryptoeconomics as a field but lately, the concept of **token design** has become important, since with the advent of ICOs, many have now realised how important the definition of the purpose of the token is. <a href="https://youtu.be/cM5KYcOm66Y">Note</a> that token design is more about mechanism design combined with economic incentives, as we will see later. Cryptoeconomics is thus about securing networks with the help of economic incentives.

In general, it is fair to say that if the objective is to work out **robust designs** for decentralised economic networks and build working ecosystems around blockchain based infrastructure, then cryptoeconomics is the first set of tools you will want to learn.

Here is a formal definition of cryptoeconomics.

> A formal discipline that studies protocols that govern the production, distribution and consumption of goods and services in a decentralised digital economy. Cryptoeconomics is a practical science that focuses on the design and characterisation of these protocols. <a href="https://twitter.com/VladZamfir" alt="Vlad Zamfir profile">Vlad Zamfir</a> **[Ethereum Foundation]**

The key part is about building an actual **decentralised digital economy**. You need a million of things to achieve that, but only a few fundamental components will be enough to start with.

* Prove things that happened in the past, i.e **cryptography**.
* Incentivise people to participate, i.e **game theory**.

*"Cryptoeconomics makes use of cryptography and game theory to design and characterise protocols"* means that cryptoeconomic protocols are usually **reverse games**: you know the results (what you want to happen in your newly created digital economy –this is also known as desirable outcome) and you look for the right rules of a game that will adequately incentivise people to participate. Whatever the rules of the game, participants will –amongst other things– base their actions on non-arguable events that happened in the past and for that we use **cryptographic proofs**.

For designers, the difficulty of cryptoeconomics lies in two things: the design of the rules of the game and the understanding of the underlying technical components that will make the design a functional reality as intended. In the next sections, you will find directions to make your way through the field of cryptoeconomics.

# Simple example

*Alice wants to send a message to Bob*

In a distributed network where there's no central authority, there's no one to make sure that Alice did send the message nor that Bob did receive it. Put it differently, you can't tell the difference between these 2 statements:

* Alice fails to send a message to Bob
* Bob fails to report Alice's successfully sent message

If this is the game then there are several strategies both players can play: Alice and Bob can respectively tell the truth or lie regarding sending and receiving the message. Therefore to inform the network about the success or failure of Alice sending a message to Bob, there must be an incentive toward telling the truth. This is where cryptoeconomics kicks in.

# What are the goals of cryptoeconomics?
