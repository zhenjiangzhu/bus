# Bitconch 
A New Distributed Web Protocol for Smart Contracts and DApps. 

This repo is the official implementation of the Bitconch Chain protocol.

## File Structure

```
|___blaze_gpu\
|___build\
|___cdylib\
|___common\
|___core\
|___crypto\
|___docs\
|___gobin\
|___scripts\
|___smart_contract\
|___tokenissue\
|___vendor\
|___whitepaper\
|___deploy.py
|___preset.sh

```

## Build

---

### Ubuntu


1. run preset.sh to install environment

```
preset.sh
```

```
pip3 install colorama
```

2. run the leader node

```
./run1.sh
```

3. open another terminal, and run token bot service
```
./run2.sh

```
4. open another terminal, and run voter node 

```
./run3.sh

```

5. Open another terminal, and run the bench mark service


```
./run4.sh

```

### Windows


*WIP*

**For first time user on windows**
1. Download and install Chcolate https://chocolatey.org/
2. Install mingw, go, rust
3. Download and install Visutal Studio Code https://code.visualstudio.com/
4. Register an account on Github.com
5. Download the Github desktop client from https://desktop.github.com
6. Clone this repo to your own local
7. Modify the code as you wish.
8. Commit the changes to your local repo. And push to your own remote repo.
9. Please make sure your contributions adhere to our coding guidelines:

    * Code must adhere to the official Go [formatting](https://golang.org/doc/effective_go.html#formatting) guidelines (i.e. uses [gofmt](https://golang.org/cmd/gofmt/)).
    * Code must be documented adhering to the official Go [commentary](https://golang.org/doc/effective_go.html#commentary) guidelines.
    * Pull requests need to be based on and opened against the `master` branch.
    * Commit messages should be prefixed with the package(s) they modify.
      * E.g. "consensus: add new pckage buffett for POR consensus"


# How to contribute (Bitconch Improvement Proposal - BUSIP)

---

People wishing to submit BUSIPs, first should propose their idea or document to the caesar@bitconch.io mailing list. After discussion, please open a PR. After copy-editing and acceptance, it will be published here.

We are fairly liberal with approving BIPs, and try not to be too involved in decision making on behalf of the community. The exception is in very rare cases of dispute resolution when a decision is contentious and cannot be agreed upon. In those cases, the conservative option will always be preferred.

Having a BIP here does not make it a formally accepted standard until its status becomes Final or Active.


# Magna Carta of Bitconch
Bitconch is dedicated to build a global community of developers. This part is still in *WIP*, please send your email to caesar@bitconch.io if you have any good ideas.
