# assignment2-yeluri
# vengalarao
###### salar jung museum

The Salar Jung Museum is an art museum located at Dar-ul-Shifa, on the southern bank of the Musi River in the city of **Hyderabad**, **Telangana**, India. It is one of the notable National Museums of India.[1] Originally a private art collection of the Salar Jung family, it was endowed to the nation after the death of Salar Jung III. It was inaugurated on 16 December 1951.

Ordered List
***
# Rajiv Gandhi International Airport
1. From Airport take a bus to Mehidpatnam.
2. Mehidpatnam to srnagar.
3. srnagar to kukatpally.
4.kukatpally to salar jung museum.

an unordered list of other locations around the museum that you would recommend for others.
* Charminar.
* Golkanda Fort.
* Birla Mandir.
* Ocean Park

[AboutMe](AboutMe.md)

***
# Tables
 4 cities that you would recommend someone visit

| Name of the city | location to visit | amount of time |
| ---              | ---               | ---            |
| Hyderabad        | Birla Mandir      | 2 hours        |
| Mumbai           | Marine Beach      | 2 hours        |
| Goa              | Baga Beach        | 3 hours        | 
| Vizag            | RK Beach          | 2 hours        |

***
# Pithy Quotes
> A man is but the product of his thoughts -- *Mahatma Gandhi*

> You must not lose faith in humanity -- *Mahatma Gandhi*

***
# Code Fencing

[how to sort in svg](https://stackoverflow.com/questions/17915276/sorting-data-bound-to-svg-elements-using-d3-js)

```
var sortOrder = false;

var sortByPropertyX = function() {
        sortOrder = !sortOrder;
        sortCells = function(x, y) {
    if (sortOrder) {
        return x.someProperty - y.someProperty;
    }
        return y.someProperty - x.someProperty;
        };
        svg.selectAll("rects")
    .sort(sortCells)
    .attr("x", function(d, i) {return d.x})
    .attr("y", function(d, i) {return d.y})

        svg.selectAll("text")
    .sort(sortCells)
    .text(function(d, i) {
        return d.someProperty;
    })
    .attr("text-anchor", "middle")
    .attr("x", function(d, i) {
        return d.x + CELLWIDTH/2;
            })
    .attr("y", function(d, i) {
        return d.y + CELLHEIGHT/2;
    })

    [svg](https://css-tricks.com/snippets/svg/)

