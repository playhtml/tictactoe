# Mooncat Design Series



## Original MoonCatRescue Series (~24×24) - 128 Designs

All 128 designs in original pixel size.

Note: The pixel size depends on the pose:
standing (21×17), sleeping (20×14), pouncing (17×22), stalking (20×21)

![](i/original-008.png)
![](i/original-012.png)
![](i/original-009.png)
![](i/original-013.png)
![](i/original-010.png)
![](i/original-014.png)
![](i/original-011.png)
![](i/original-015.png)

![](i/original-008x4.png)
![](i/original-012x4.png)
![](i/original-009x4.png)
![](i/original-013x4.png)
![](i/original-010x4.png)
![](i/original-014x4.png)
![](i/original-011x4.png)
![](i/original-015x4.png)

For more see [**original »**](original)



## V2 Series (~24×24) -  8 Designs

Let's change the nose and mouth to use the outline (color #1).
Let's change color #5 into the (exclusive) eyes color
by adding a pixel each to the eyes
and changing all other color #5 pixels to color #4.
Can you spot the difference?

![](i/v2-008.png)
![](i/v2-012.png)
![](i/v2-009.png)
![](i/v2-013.png)
![](i/v2-010.png)
![](i/v2-014.png)
![](i/v2-011.png)
![](i/v2-015.png)

![](i/v2-008x4.png)
![](i/v2-012x4.png)
![](i/v2-009x4.png)
![](i/v2-013x4.png)
![](i/v2-010x4.png)
![](i/v2-014x4.png)
![](i/v2-011x4.png)
![](i/v2-015x4.png)


What's the point?
It's "L'art pour L'art" or in English "Art for Art's Sake" :-).

Almost. The idea of the new v2 design series is to make
it easier to colorize Mooncats. The new color scheme:

- #1 - outline color
- #2 - pattern 1 (or highlight) color
- #3 - base color
- #4 - pattern 2 (or accent) color
- #5 - eyes color

For more see [**v2 »**](v2)



## Original CryptoCats Series (32×32) - 4 Designs

Let's keep the V2 color scheme
and cross-over to CryptoCats.

Note: The designs in the original MoonCatRescue series
only use 5 colors (plus transparent).
As a new convention lets add two more "hard-coded" always pre-defined / present colors:

- #6 - BLACK (`000000`)
- #7 - WHITE (`ffffff`)

Let's try:

![](i/cryptocats-000.png)
![](i/cryptocats-001.png)
![](i/cryptocats-002.png)
![](i/cryptocats-003.png)

![](i/cryptocats-000x4.png)
![](i/cryptocats-001x4.png)
![](i/cryptocats-002x4.png)
![](i/cryptocats-003x4.png)

For more see [**cryptocats »**](cryptocats)






## Tools

###  Do-It-Yourself (DIY) Corner - The Original Mooncat Pixel Drawing Tool Online

The Mooncat developers (Ponderware) write:

> Here is the tool we wrote and used to generate the MoonCatRescue pixel art.
> There has been some interest in knowing how we drew them, so we figured we might as well release it.
> Prepare to be underwhelmed!  => [**mooncatrescue.com/pixeleditor**](https://mooncatrescue.com/pixeleditor)



A little tip if you try it out online - there are [128 original mooncat pixel drawings / designs](https://github.com/cryptocopycats/awesome-mooncatrescue-bubble/blob/master/DESIGNS.md)
(all encoded in the original source code in a single-line string - see [`designs.rb`](https://raw.githubusercontent.com/cryptocopycats/mooncats/master/mooncats/lib/mooncats/designs.rb) for a "word-wrapped" more readable
source of the original example.

Yes, you can read in the design into the pixel drawing tool online  (reformat required - every pixel row must be on its own line
and all (color) numbers space separated).
Example for [design 0](original/000.txt):

```
0 0 1 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0
0 1 3 1 0 0 0 1 3 1 0 0 0 0 0 0 0 0 0 0 0
0 1 5 3 1 1 1 3 5 1 0 0 0 0 0 0 0 0 0 0 0
1 1 3 3 3 3 3 3 3 1 1 0 0 0 0 0 0 1 1 1 0
1 3 3 3 3 3 3 3 3 3 1 0 0 0 0 0 0 1 3 1 0
1 3 3 1 3 3 3 1 3 3 1 1 1 1 1 1 0 1 1 3 1
1 3 3 3 3 3 3 3 3 3 1 3 3 3 3 1 1 0 1 3 1
1 3 3 4 3 5 3 4 3 3 1 3 3 3 3 3 1 0 1 3 1
1 3 3 3 4 3 4 3 3 3 1 3 3 3 3 3 1 1 1 3 1
0 1 3 3 3 3 3 3 3 1 3 3 3 3 3 3 3 3 3 1 1
0 0 1 1 1 1 1 1 1 3 3 3 3 3 3 3 3 1 1 1 0
0 0 1 3 3 3 3 3 3 3 3 3 3 3 3 3 3 1 0 0 0
0 0 1 3 3 3 3 3 1 4 4 4 1 3 3 3 1 1 0 0 0
0 0 0 1 3 3 1 3 3 1 4 1 3 3 3 1 1 0 0 0 0
0 0 0 0 1 3 1 1 3 1 4 1 3 3 1 1 0 0 0 0 0
0 0 0 0 1 5 1 1 5 1 1 5 3 1 1 0 0 0 0 0 0
0 0 0 0 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0
```

Paste the text into the box below the pixel grid canvas and click on the read button.
Now you should see the mooncat pixel design.


![](https://github.com/cryptocopycats/awesome-mooncatrescue-bubble/raw/master/i/pixel-design-000.png)


And for some more fun here's the [design 3](original/003.txt) reformatted - ready to copy'n'paste:

```
0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 0 0 0 0
0 0 0 0 0 0 0 0 0 0 1 3 3 3 3 1 1 1 0 0
0 0 0 0 0 0 0 0 0 0 1 3 1 1 3 3 3 1 0 0
0 0 0 0 0 0 0 0 0 0 1 1 0 0 1 1 3 1 0 0
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 3 1 1 0
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 3 3 1 0
0 0 1 1 0 0 0 0 1 1 0 0 0 1 1 1 1 1 1 0
0 1 3 1 0 0 0 1 3 1 0 0 1 1 3 3 3 3 1 1
1 3 5 3 1 1 1 3 5 3 1 1 1 3 3 3 3 3 3 1
1 3 3 3 3 3 3 3 3 3 1 1 3 3 3 3 3 3 3 1
1 3 3 3 3 3 3 3 3 3 1 3 3 3 3 3 3 3 3 1
1 3 3 1 3 3 3 1 3 3 1 3 3 3 3 3 3 3 1 1
1 3 3 3 3 3 3 3 3 3 1 3 3 3 3 3 3 3 1 0
1 3 3 4 3 5 3 4 3 3 1 3 3 3 3 4 3 3 1 0
1 3 3 3 4 3 4 3 3 3 1 3 3 4 4 4 3 3 1 0
0 1 3 3 3 3 3 3 3 1 1 3 4 4 4 1 3 3 3 1
0 0 1 1 1 1 1 1 1 3 3 3 1 1 1 1 1 3 3 1
0 1 1 3 3 3 3 3 3 3 1 1 1 3 3 1 1 3 1 1
1 1 3 3 3 1 3 3 1 1 1 1 5 3 1 1 3 3 1 0
1 5 3 1 1 1 5 1 1 0 0 1 1 1 1 5 3 1 1 0
1 1 1 1 0 1 1 1 0 0 0 0 0 0 1 1 1 1 0 0
```

![](https://github.com/cryptocopycats/awesome-mooncatrescue-bubble/raw/master/i/pixel-design-003.png)






## Questions? Comments?

Post them on the [mooncatrescue reddit](https://old.reddit.com/r/mooncatrescue). Thanks.

