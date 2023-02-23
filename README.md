# Bangs Index

Community maintained !Bangs Database.

## What exactly is a `!Bang`?

In case you haven't heard of the term `!Bang`, it is a way to search quickly.
Directly takes you to search results of the specified website or your
pre-defined default one. Let's take a closer look at the example below:

1. Type "!w Banana" in the address bar
2. You've been directly redirected to the Banana Wikipedia page.

### What exactly happened is:

1. Looks through the `bangs.yaml` file to match for `!w`
2. Founds a match, that leads to search results of Wikipedia 
in bangs.yaml file `https://en.wikipedia.org/w/index.php?search={search}`
3. Replaces the `{search}` with the `Banana`
4. Navigates to that URL.


## Contributing

Feel free to contribute. Soon there'll be a `Code of Conduct` and
CONTRIBUTING.md to guide you.
