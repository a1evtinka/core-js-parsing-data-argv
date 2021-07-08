# Data parsing: filtering, argv

## Introduction

This challenge is the continuation of the previous exercise [parsing data][]. If you have not done it yet - it is time to get to it! You can also postpone this challenge and do any of the today's exercises.

## Releases

### Release 0: Working with JS objects

![animation](readme-assets/pd-name.gif)

_Figure 1_. Filtering js objects, created from CSV file, by "last_name" field.


![animation](readme-assets/pd-code.gif)

_Figure 2_. Filtering js objects, created from CSV file, by "area_code" field.


One of the benefits of loading data from CSV file into js objects is that it becomes easier to 'filter' a collection of people or manipulate their attributes. For instance, you could sort people by name. Or you could update a person' phone number.

Твоя программа должна позволять пользователям «фильтровать» людей из `people.csv`, используя разные команды: фильтрацию людей по определенному региональному коду, по определенной фамилии, адресу электронной почты из определенного домена или по дате рождения. Программа должна работать аналогично примеру на Рисунке 1.
Your program should allow users to 'filer' people from `people.csv` using different commands: filtering people by a specific region code, by a specific last name, an email address from a specific domain or by date of birth. The program should work similarly to the example in Figure 1.

Start by developing a function to find (filter) people by region code. Run the program and follow the error messages. After users can search for people by region code, implement three other functions: search by last name, by email, and by year of birth. Then come up with and add another search parameter.

### Release 1: Collection and storage of information

You already can write data to CSV! Write a script to generate a CSV address book based on user input. You enter people's names, phone numbers, etc right in the command line when you run the script (`runner.js`), and then you save the entered data to a CSV file. An example of starting the program:

```bash
node runner.js '[{"name":"Vasya", "phone":"+79887776634", ...}, ...]'
```

The format in which you transfer data about people at starting the program can be anything. Come up with your own version.
It is necessary that you can add several users to the address book at once in just one start of the program.

## Conclusion
Good job!


[parsing data]: https://github.com/Elbrus-Bootcamp/core-js-parsing-data-fs
