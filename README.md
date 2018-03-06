# Homework 1

This skript allows one to canculate the the area of triangle

## 

You will need this skrip in case you want to calculate the area of a triangle and you know the coordinates of all three points

### Input

As input you should provide coordinates for all the three points of the triangle

```
parser.add_argument("k", type=float,
                   help="coordinate x1")
parser.add_argument("l", type=float,
                   help="coordinate y1")
parser.add_argument("n", type=float,
                   help="coordinate x2")
parser.add_argument("m", type=float,
                   help="coordinate y2")
parser.add_argument("t", type=float,
                   help="coordinate x3")
parser.add_argument("f", type=float,
                   help="coordinate y3")
```

### Output

As output of the skript working you will get the area of triangle calculated using the Gerone formula

```
print ('The square is', answer)
```

## Running the tests

Here some examples of the skript working are shown

### Test 1
If input points have all coordinates are 0

```
'The square is', 0
```

### Test 2
If input points  0 0 1 1 0 1

```
'The square is', 0.49999999999999983
```

### Test 3
If input points  10 5 1 21 17 63

```
'The square is', 316.99999999999983
```


* Hope you liked the skript
* And found it useful
* Good luck!
