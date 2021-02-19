# HTML-refresh
Refreshing my memory of the basics of HTML, which is a language I haven't used in a long time


<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Bubble Sort</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <script src="script.js"></script>
    <h1> BUBBLE SORT </h1>
    <p1> 6,1,3,2,7,4,5</p1>
    <br></br>
    <p2> This is the unsorted list</p2>
    <br></br>
    <br></br>
    <p1> 1,6,3,2,7,4,5</p1>
    <br></br>
    <p2> The algorithm checks if the first element is bigger than the second element. If this statement is true, the two elements swap. Here, you can see the 6 and the 1 have swapped  places</p2>
    <br></br>
    <br></br>
    <p1> 1,3,6,2,7,4,5</p1>
    <br></br>
    <p1> 1,3,2,6,7,4,5</p1>
    <br></br>
    <p1> 1,3,2,6,7,4,5</p1>
    <br></br>
    <p2> The 7 is bigger than 6, so they don't swap places</p2>
    <br></br>
    <br></br>
    <p1> 1,3,2,6,4,7,5</p1>
    <br></br>
    <p1> 1,3,2,6,4,5,7</p1>
    <br></br>
    <p2> The 7 then continues on until the end of the list is reached. This means one pass has been completed. After one pass, you know the number at the end of the list is the biggest number</p2>
    <br></br>
    <br></br>
    <p1> 1,2,3,4,5,6 (7)</p1>
    <br></br>
    <p2> Another pass begins, ignoring the 7 to save time</p2>
    <br></br>
    <br></br>
    <p1> 1,2,3,4,5 (6,7)</p1>
    <br></br>
    <p1> 1,2,3,4,5,6,7</p1>
    <br></br>
    <p2> Another pass is completed, and the computer detects that no more numbers have been swapped. This means the list is sorted, so the program ends there</p2>
  </body>
</html>
