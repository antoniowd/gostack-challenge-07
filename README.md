<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" style="width: 100%;"/>

<h3 align="center">
  Challenge 07: GoFinances Wev
</h3>

<blockquote align="center">“Don't expect good results if you have unclear goals!”</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/Rocketseat/bootcamp-gostack-desafios/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rocketseat/bootcamp-gostack-desafios?style=social">
  </a>
</p>

## :rocket: About the challenge

In this challenge, you must continue developing the transaction management application, GoFinances. Now you will practice what you've learned so far on React.js and TypeScript, using routes and sending files by form.

This will be an application that will connect to your [Backend Challenge 06](https://github.com/antoniowd/gostack-challenge-06), to display the created transactions and import an CSV file to generate new records in the database.

### Layout

[Layout in Figma](https://www.figma.com/file/EgOhyj1Inz14dhWGVhRlhr/GoFinances?node-id=1%3A863)

### Application requirements

- **List the transactions**: Your Dashboard page should be able to display a list through a table, with the `title`, `value`, `type` and `category` field of all the transactions that are registered in your API.

- **Display the balance**: In your Dashboard page you must display the balance that is returned from your backend, containing the total, along with the total of incomes and outcomes.

- **Import CSV files**: In your Import page, you must allow the sending of a file in csv format to your backend, which will import the transactions into your database. The csv file must follow the following format.

```csv
title, type, value, category
Loan, income, 1500, Others
Website Hosting, outcome, 50, Others
Ice cream, outcome, 3, Food
```

## Test Specification

Before running the tests, create a database named "gostack_desafio06_tests" so that all the tests can execute correctly

## :memo: Licence

This project is under license from MIT. See the archive [LICENSE](LICENSE) to more details.

---

Made with 💜 by Rocketseat :wave: [Join our community!](https://discordapp.com/invite/gCRAFhc)
