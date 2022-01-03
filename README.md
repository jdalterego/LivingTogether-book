This is an online book about Hansalim, a food and farming cooperative in South Korea. One of the world's largest organic food cooperatives, Hansalim brings together farmers and consumers into a single federation of cooperatives with over 750,000 members and producers across the country.

## Google Analytics

Google analytics has been set up to track interactions with the book.

This was done by creating a style/ga.html file containing the Global site tag code. Next, the following code was added to the _output.yml file under the `bookdown::bs4_book:` section:

```
  includes:
    in_header: style/ga.html
```

This adds the contents of the style/ga.html file to the header of each webpage when the book is built.
