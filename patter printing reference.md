# Pattern Printing

*****
*****
*****
*****
*****

Solution :
To create a square pattern, we need 2 nested loops. The outer loop will print a number of rows and the inner loop will print the star in each row.

Repeat external loop for times equal to the size of the square, inside this loop, repeat inner loop for times equal to the size of the square and print star. At the end of each row, print a new line.

Code :
<?php
    // square pattern
    $size = 5;
    for($i = 0; $i < $size; $i++) {
        // print column
        for($j = 0; $j < $size; $j++) {
          // print row
          echo "*";
        }
        // change line
        echo "<br>";
    }
?>
