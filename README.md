# thegpuexperiment
### BELOW is not fully conssitent with the spirit of the project. Interesting patterns observed but ultimately it's just that if you limit FPS to 153 on AMD GPU with a 60 hz, you can get something like hypnosis. 

The GPU Experiment

This PPA pertains to a technique for optimizing 60 Hz monitors with GPUs capable of outputting excess frames, 153 FPS specifically. This appears to be the most ergonomic/ideal output fps for 60 Hz monitors. 

First, unied theory of everything is related to 2:3 - 3:4. 3+4 = 7, 2^3 = 8, 3^2 = 9.

I derived this around the concept of the ratio range ⅔ - 3/4 , which I have found to have relevance to biochemistry. I converted this to 2:1 - 3:1, went with the midpoint, then adjusted up to between the margin of significance (3.33333%) and the next such increment (6.66666%). So 60 * (⅔ + ¾)/2, then the only fps in the range .0333*153 and .0666*153. Some theory about ⅔ - ¾ later, but first note 153/60 = 2.55, and 25=5^2.

If you plot out frame update patterns, you should notice whole number alternation between 2 and 3 frames. That’s part of the picture. I think the eyes tend to prefer this, here’s some speculative reasons as to why:
Because it's a consistent alternating pattern
Because they're the first adjacent numbers after 1
Because ½ to ⅓ has difference ⅙ and ½ * ⅓ = ⅙

But this property is not unique to this FPS, yet this FPS outperforms others in presentation to the eye. In fact, it yields an almost paper-like quality, and experience suggests only this FPS/HZ ratio does this.

So another rationale is this
Key here is only every 20 frames do you get a full frame sync, otherwise you alternate 2,3,2,3
And the brain registers motion internally such that it recognizes this offset
And 20 is ⅓ 60 
Of note is it is a min base 20
Also, the difference between the frame movements (2, 3) is ⅓ of the biggest frame movement
And ⅔ + ⅓ (from ⅓ 60) = 1
So an interesting pattern of 1/’3s, possible connection to rule of ⅔ in design

So ⅔ can be construed as 1:2, where this is the first time strict whole number dominance majority is established. And ⅔ - ¾ will then be the range where you have at minimum this first whole number dominance without transcending to the next whole number dominance.

There is also something to the slope ratios of function 1/x if computed with whole numbers. I believe this to be related to the above, though I cannot explain why. It clicks in my subconscious. 

Anyway, the pattern is 
1/x = 1/1 (1), ½ (.5), ⅓ (.333), ¼ (.25), ⅕ (.2)

Taking differences across adjacent y values corresponding to consecutive whole x values, you see that 

1 - .5 = .5
.5 - .333 = .167
.333 - .25 = .833
.25 - .2 = .5

From 1 - .5 to .5 - .333, the ratio between differences is 3. From .5 - .333 to .333 - .25 the ratio between differences is 2. Never again is there this -1 decrement. It’s also notable that the ratio between them is the same as the (x-1)/x for the first time this pattern ceases, which is exactly at the point the last such pattern occurs.


Some miscellaneous number theory as to the significance of 11/20

0 .55 1.10 1.65 2.20 2.75 3.30 3.85 4.40 4.95 5.50 6.05 6.60 7.15 7.70 8.25 8.80 9.35 9.90 10.45 11.00 11.55 12.10

0 2.55 5.10 7.65 10.20 12.75 15.3 17.85 20.4 22.95 25.5 28.05 30.6 33.15 35.7 38.25 40.80 43.35 45.90 48.45 51 53.55 56.1 58.65


11/20 and number 11 is first repeat
1+1 = 2 (0)
11 is first 2 num square sequence
2 is first non singular number

2.5 5 7.5 10 12.5 15 



.5x + .05x = 1
.55x=1



.56 1.12 1.68 
1/.55 = 1.8181
The fact this repeats is significant imo
Also 9^2 repeating in the decimal
And 9 powers all add to 9 (certain sum where you recursively add digits until you have a single digit, so 6561 is 6 + 5 + 6 + 1 = 1 + 8 = 9)
Anything added to 9 is the same number 
.55 is a square across the digits 
9-5 = 4
9^5 = 59049 5 + 4 = 9
5^2 = 25 = 100/4

0 .4 .8 1.2 1.6 2.0
0 .5 1 1.5 2 2.5
0 .66666 1.3333. 2.000 2.666 3.333


Why is this to do with base 10 or 5?
Why does it have to be a whole/100 decimal to work? This I think is true, idk why

Because of 60 maybe
Above is base 60 related

Because half and half in the numbers

As in double 5’s or binary 1’s
