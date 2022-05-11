# Installation

---

This is an elaborate walkthrough on the installation and configuration of Gitchat on your local machine, for development purposes.

## Project Structure

This is the structure of the application. For easier navigation and to prevent an intimmidating looking repository, the folders are named after greek olympian Gods.

|   Folder    |   Description    |
| :---------: | :--------------: |
|  <b>Aries   |    React App     |
| <b>Chronos  |  Elixir Server   |
|  <b>Flask   |   Python Stuff   |
|  <b>Hades   |   Next JS App    |
| <b>Poseidon | Electron Wrapper |
|   <b>Zeus   |   Expo CLI App   |

## Requirements

It is worthy to note that you do not require all these tools, except the ones in red which are necessary for working with all parts of the project currently.

1. <p style="color: red">Node.js</p>
2. <p style="color: red">Expo CLI tools</p>
3. Docker
4. Elixir/Erlang VM
5. <p style="color: red">MySQL</p>
6. Postgres SQL
7. GraphQL
8. <p style="color: red">Python & PIP</p>
9. <p style="color: red">Yarn</p>

## Getting Started

Note this is just an all round installation. Each folder, has it's own specific configuration and requirements.

Install Node.js for your machine by clicking <a href="http://nodejs.org">here.</a> Remember to check and verify the installation.

<strong>STEP 1</strong>
```shell
$ node -v
```
Check your npm version as well. Though we'd be using Yarn instead of NPM.

```shell
$ npm -v
```
<strong>STEP 2</strong>

Install Docker. Not really compulsory, if you do not want to run the application within containers.
Install <a href="http://docker.org">here</a>.

<strong>STEP 3</strong>

Install Python. From <a href="http://python.org">here</a>. 

Install virtualenv

```shell
$ pip install virtualenv
```
Install flask

```shell
$ pip install flask
```

Just so you have the basic environment setup. 

<strong>STEP 3</strong>

Not really compulsory to install Elixir, but see the ```chronos``` folder for an elaborate installation guide.

<strong>STEP 4</strong>

Clone this repository. You would need Gitbash on your local machine to execute this. Install Gitbash.
Now in your git terminal, or VsCode preferrably, navigate to ```source control.```
Click on ``clone repository``
Enter this link: `https://github.com/grayoj/gitchat.git`

OR terminal way: 

```git
$ git clone https://github.com/grayoj/gitchat.git
```

Now ``cd`` into the root directory. Have fun or start contributing!
More detailed guidelines, for specific tasks coming.