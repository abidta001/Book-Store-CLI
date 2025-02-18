It is golang command line application to list, add, update and delete books using flag, json, ioutils package

# build
go build

# run

# get books
./bookstore get --all
./bookstore get --id 5

# add a book with id ,title, author, price, image_url
./bookstore add --id 6 --title test-book --author abid --price 200 --image_url http://abid.com/test.png

# update a book with id ,title, author, price, image_url
./bookstore update --id 6 --title test-book-1 --author abid1 --price 2001 --image_url http://abid.com/test.png1

# delete a book by --id
./bookstore delete --id 6
# Book-Store-CLI
