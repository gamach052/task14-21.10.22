###  [Task 8kyu](https://www.codewars.com/kata/5ab6538b379d20ad880000ab/train/javascript)

You are given the length and width of a 4-sided polygon. The polygon can either be a rectangle or a square.
If it is a square, return its area. If it is a rectangle, return its perimeter.




### My solution
```Java
  const areaOrPerimeter = function(l , w) {
        if (l==w){return l*l;}
        else {return 2*(l+w);}
        };
```

### Fav solution
```Java
const areaOrPerimeter = (l , w) => l === w ? l*w : 2*(l+w);

```
I like this solution because I like it
