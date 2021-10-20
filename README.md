# E-Commerce

<a href="https://choosealicense.com/licenses/mit" target="_blank"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" /></a>

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Video](#video)

## Description

E-Commerce project builds the back end for the site, leveraging Express.js API to Sequelize to interact with a MySQL database.

## Installation

First, ensure node.js is installed on your computer. Next, clone this repository. Open the respository in a code editor such as VS Code

## Usage

After cloning the repository to your computer, follow the next steps:

1. Open E-Commerce repository in VS Code

2. Open Terminal

Type the syntax below.
a. Install the dependencies.

```bash
npm install
```

b. Begin MYSQL login.

```bash
mysql -u root -p
```

b. Enter your MYSQL password.

```bash
Password:
```

c. Execute schema.sql query.

```bash
source db/schema.sql
```

d. Exit MySQL

```bash
quit
```

e. Run the application

```bash
node models/index.js
```

```bash
npm run seed
```

```bash
node server.js
```

## Video

Link [E-Commerce Video](https://drive.google.com/file/d/1eDG5jSgNeYe3TqWf77WGbNKmXMz9q6go/view?usp=sharing)
