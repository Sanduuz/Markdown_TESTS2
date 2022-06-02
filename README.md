Here are the steps for reproduction:

| ![kitten.png](http://x.nixu.com:1234/kitten.png) |
|:---:|
| This is a working image of a cat |

| ![kitten.png](/etc/passwd"x=1) |
|:---:|
| This is a broken image of a cat because of math symbols $x_n$ |


> The same goes with blockquotes. Here is a working image of a cat:
> ![kitten.png](http://x.nixu.com:1234/kitten.png)
> Renders just fine

> But if I have math symbols in:
> ![kitten.png](http://x.nixu.com:1234/kitten.png)
> The image breaks $x_n$
