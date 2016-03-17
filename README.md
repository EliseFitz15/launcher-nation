## Practice challenge

#### To access this challenge:
  - `git clone https://github.com/EliseFitz15/launcher-nation`
  - `cd launcher-nation`
  - bundle and create your database

This challenge is focused solely on **migrations**, **models**, and the database **schema**. The relevant files that will be checked are:
* Include database constraints and model validations where appropriate.

- All files in the `app/models` directory.
- All files in the `db/migrate` directory.
- The `db/schema.rb` file.

* Draw out the ER Diagram on paper so that you can understand what data you will need to save and the relationships that you will need to create.
* Test your models in `pry` by running `pry -r "./app.rb"`.


Design a schema and create the necessary migrations and models to represent citizens living in a nation:

#### Citizen

* Citizens must have a first name and a last name.
* Citizens can optionally have a email.
* Citizens can belong to multiple nations.

#### Nation

* A nation must have a name.
* A nation can optionally have an official language.
* A nation can have many citizens.
