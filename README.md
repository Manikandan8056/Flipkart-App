# Online Book Shop Portal

## Tables

#### Table1: Text_books
| Books | Price | Stars | New |
| -- | -- | -- | -- |
| Maths | 500 | 3 | old |
| CSS | 1000 | 4 | new |
| JEE | 800 | 2 | old |
| Java | 2000 | 5 | new |
| C++ | 1500 | 3 | old |

#### List All Books
`
select * from Text_books;
`

### Sort By
#### Price Low-High
`
select * from Text_books order by Price ASC;
`
#### Price High-Low
`
select * from Text_books order by Price DESC;
`
#### Sort by stars
`
select * from Text_books where Stars=3 order by Books;
`
#### Sort by with Min-Max
`
select * from Text_books where price<=1500 and price>=800 order by Books;
`
