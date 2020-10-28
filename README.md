# Bubble-Sort
Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order.<br>
The pass through the list is repeated until the list is sorted.<br>
Example:<br>
First Pass:
( 5 1 4 2 8 ) –> ( 1 5 4 2 8 ), Here, algorithm compares the first two elements, and swaps since 5 > 1.<br>
( 1 5 4 2 8 ) –>  ( 1 4 5 2 8 ), Swap since 5 > 4 <br>
( 1 4 5 2 8 ) –>  ( 1 4 2 5 8 ), Swap since 5 > 2 <br>
( 1 4 2 5 8 ) –> ( 1 4 2 5 8 ), Now, since these elements are already in order (8 > 5), algorithm does not swap them. <br>

Second Pass: <br>
( 1 4 2 5 8 ) –> ( 1 4 2 5 8 ) <br>
( 1 4 2 5 8 ) –> ( 1 2 4 5 8 ), Swap since 4 > 2 <br>
( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) <br>
( 1 2 4 5 8 ) –>  ( 1 2 4 5 8 ) <br>
