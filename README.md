# Accessing and using the Library System

- In order to access our checkout system you'll have to first load the file into irb using: load './lib/library.rb'<br>

- To open access database use: lib = Library.new <br>

- To see which books are checked out:  lib.checked_out<br>

- To see which books are available: lib.available<br>

- To checkout a book with yaml index: lib.checked_out("index number here")<br>

- To search for a book: lib.select_book("title or keywords here")<br>



************
## Things to be improved upon or implemented:<br>
- A checkout system that uses the data pulled from a title search.<br>
- A return method that modifies yaml file availability.<br>
- A method that returns which books are checked out by a specific person.

*********
Resources used: 
Advanced RSpec demo