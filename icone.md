## ICONE
### con framework _fontawesome_

###### CDN da integrare

```
<style rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"></style>
```


Esempio di integrazione icone
per mezzo di una **pseudo classe** sull'elemento html (in questo esempio uso il _before_)
```
p::before{
    content:"\f105";
    font-family: "Font Awesome 5 Free";
    margin-right:20;
}
```
