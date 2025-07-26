this is just tiny modification of this code:

https://github.com/bpetrynski/firefox-shrinking-tabs-css 

I noticed that while it did exactly as advertised and made firefox tabs behave like chrome tabs in the way they became smaller, it didn't allow me to drag the tabs the way chrome does:

![tab on edge vs firefox](https://github.com/user-attachments/assets/12534b68-3120-434d-97ae-e23681e49b8a)


so by trial and error I found the line that was causing that and deleted it

it was this one!:

<img width="824" height="204" alt="Screenshot 2025-07-26 022805" src="https://github.com/user-attachments/assets/09d60428-c128-47fe-a8b1-440c391ae533" />


it does have the side effect of allowing firefox to activate the scroll arrows, but that's only with like 400 tabs open on my 1080p monitor so I don't mind it that much.


