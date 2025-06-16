<h3 align="center" >SADIYA MD USER BOT</h3>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
   <p align="center">
<a href="https://github.com/sadiya-tech12/SADIYA-MD-V1">
    <img src="https://i.ibb.co/N6Hg4QWN/Sadiya-Md.jpg" width="700px">
  </a>
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

### Visit Website
<a href="https://sadiya-md-official.vercel.app/"><img src="https://img.shields.io/badge/DEPLOY-blue" width="125vm" target="_blank"></a>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

### Workflow Deploy Code 👇

```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```

`🧑‍💻 SADIYA MD 🧑‍💻 - By Sadiya Tech`

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
