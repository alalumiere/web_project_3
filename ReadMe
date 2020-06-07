# Responsive Webpage - From Portland to Portland USA

Link: https://alalumiere.github.io/web_project_3/

Building this website developed responsive web development skills utilizing media queries and CSS grid. 

The most recent updates include Media Query brakepoints at widths: 320px, 768px, 1024px and 1280px. 

Example:

```css
.photo-grid{
  max-width: calc(100% - 96px);
  padding-left: 48px;
  padding-right: 48px;
  padding-bottom: 92px;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(3, 1fr);
  grid-gap: 16px 16px;
  margin: auto;
}

@media screen and (min-width:1024px) and (max-width:1279px){
  .photo-grid{
    max-width: calc(100% - 96px);
    min-height: 942px;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(4, 1fr);
    grid-gap: 14px 14px;
  }
}

@media screen and (min-width:768px) and (max-width:1023px){
  .photo-grid{
    max-width: calc(100% - 48px);
    padding-left: 24x;
    padding-right: 24px;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(6, 1fr);
    padding-bottom: 88px;
  }
}

@media screen and (min-width:320px) and (max-width:767px){
  .photo-grid{
    display: inline-grid;
    padding-left: 16px;
    padding-right: 16px;
    max-width: calc(100% - 32px);
    max-height: 100%;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr;
    grid-row-gap: 12px;
  }
}
```

The files have been structured according to BEM.