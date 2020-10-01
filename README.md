# parallax-slide-website

Parallax scrolling is a web site trend where the background content (i.e. an image) is moved at a different speed than the foreground content while scrolling.

Following css snippet is used to create such effect.

.pimg1, .pimg2, .pimg3 {
  position: relative;
  opacity: 0.70;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;

  /* 
    fixed = parallax
    scroll = normal
  */
  background-attachment: fixed;
}

1)
<img width="1437" alt="Screen Shot 2020-10-01 at 8 46 23 AM" src="https://user-images.githubusercontent.com/72097871/94761905-e32fd180-03c3-11eb-9b97-b6f556fa8ac5.png">

2)
<img width="1439" alt="Screen Shot 2020-10-01 at 8 46 36 AM" src="https://user-images.githubusercontent.com/72097871/94761958-0fe3e900-03c4-11eb-9c99-f5aab51b06ff.png">

3)
<img width="1437" alt="Screen Shot 2020-10-01 at 8 46 53 AM" src="https://user-images.githubusercontent.com/72097871/94761989-212cf580-03c4-11eb-88fa-64ed41b705c6.png">
