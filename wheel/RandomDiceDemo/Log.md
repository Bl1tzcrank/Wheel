# Random-Dice

- The Code is from ↓
- https://www.bilibili.com/video/BV1Po4y1o7by



# Here is some notes

```CSS 
 /* It use @keyframes name to define a animation */
        @keyframes random {
            from {
                background-position: 0% 100%;
            }
            to {
                background-position: 100% 100%;
            }
        }
```



```CSS
/* The animation set */
		animation: .2s steps(5,start) random infinite;
```

```CSS 
/* lets you apply graphical effects such as blurring or color shifting to the area behind an element */
		backdrop-filter: blur(20px);
```

