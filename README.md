# rem-responsive-typography
REM Responsive Typography - example /  cheatsheet

Example here http://codepen.io/anon/pen/BWEQgb

```css
/*--------------------------------------------------------------
>>>> LETS HANDLE TYPOGRAPHY BETTER:
>>> USING REM AND MEDIA QUERYS
>> AUTHOR: JEFFREY DUCHARME
> WEBSITE: MODERNLAYOUT.COM
----------------------------------------------------------------*/

/*--------------------------------------------------------------
>>> SETUP:
----------------------------------------------------------------*/
html, body { overflow-x: hidden; }
html { font-size: 16px; }

/*--------------------------------------------------------------
>>> RESPONSIVE TYPOGRAPHY FIXES:
----------------------------------------------------------------*/

h1 { font-size: 4rem; }
h2 { font-size: 3.5rem; }
h3 { font-size: 3rem; }
h4 { font-size: 2.5rem; }
h5 { font-size: 2rem; }
h6 { font-size: 1.5rem; }
p, a { font-size: 1.2rem; }

/* Extra Large Devices, Wide Screens */
@media only screen and (max-width: 1600px) { html { font-size: 14px; } }
/* Large Devices, Wide Screens */
@media only screen and (max-width: 1200px) { html { font-size: 13px; } }
/* Medium Devices, Desktops */
@media only screen and (max-width: 1024px) { html { font-size: 12px; } }
/* Small Devices, Tablets */
@media only screen and (max-width: 768px) { html { font-size: 11px; } }
/* Extra Small Devices, Phones */ 
@media only screen and (max-width: 480px) { html { font-size: 10px; } }
/* Custom, iPhone Retina */ 
@media only screen and (max-width: 320px) { html { font-size: 9px; } }
```

Shout outs to [DevTips](https://www.youtube.com/watch?v=UHf3aQz50jQ) for his awesome explanation
