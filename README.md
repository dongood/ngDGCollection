#ngDGCollection

A collection of AngularJS Directives.

##ngGravatar
Directive for embedding a gravatar image in your code.

This directive wraps functionality described at <http://en.gravatar.com/site/implement/images/> for creating Gravatar image requests.

```html
<gravatar email="chuckjones@gmail.com" size="100"></gravatar>
<div gravatar email="chuckjones@gmail.com" size="100"></div>
```

The directive takes the following attributes.

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

Attr | Description
---- | -----------
**email** | *Required* Gravatar's email address
** size** | *Optional* (1-1024) Image size. Defaults to 80px.
**d-option** | *Optional* Image to display when no gravatar exists. Default's to Gravatar icon.  See below for info.
**force** | *optional* (true/false) Force the d-option to be displayed regardless.

The **d-option** can be set to one of the following:
* **404**: do not load any image if none is associated with the email hash, instead return an HTTP 404 (File Not Found) response
* **mm**: (mystery-man) a simple, cartoon-style silhouetted outline of a person (does not vary by email hash)
* **identicon**: a geometric pattern based on an email hash
* **monsterid**: a generated 'monster' with different colors, faces, etc
* **wavatar**: generated faces with differing features and backgrounds
* **retro**: awesome generated, 8-bit arcade-style pixelated faces
* **blank**: a transparent PNG image (border added to HTML below for demonstration purposes)

##ngDatepicker
Directive for displaying a bootstrap styled data-picker.
