#### lyolpresentreveal
#####2 exploring reveal
######working with basic HTML
```
<div class="reveal">
  <div class="slides">
    <section>
      <h1>slide1</h1>
    </section>
    <section>
      <h1>slide2</h1>
    </section>
  </div>
</div>
```
press esc to show preview(all slides)

######Create vertical slides
```
<div class="reveal">
  <div class="slides">
    <section>
      <h1>slide1</h1>
    </section>
    <section>
      <h1>slide2</h1>
    </section>
    <section>
      <section>
        <h1>slide1 -vertical1</h1>
      </section>
      <section>
        <h1>slide2 -vertical2</h1>
      </section>
    </section>
  </div>
</div>
```
######Using background
set background image or color
```
<section data-background="#121212">
  <h1>slide2 -vertical2</h1>
</section>
```
Or
```
<section data-background="1.jpg" data-background-size="100px" data-backgeound-repeat="repeat">
  <h1>slide2 -vertical2</h1>
</section>
```
######building up content using fragments
click next, then fragment shows
```
<ul>
  <li class="fragment highlight-blue">1</li>
  <li>2</li>
</ul>
```

#####3
######Touring the default CSS themes
change it manually:
```
index.html?theme=beige
```
