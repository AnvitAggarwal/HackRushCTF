# Cyber Security: HackRushCTF'25

### Misc

- __Find me__
I just went to the EII website. Right clicked on the slider and clicked on inspect element. There was a comment.
```html
<!-- flag? SFJDVEZ7IV9MMFYzX0hAQ0tSVSRIfQ== -->
```
The string in the comment is in base64 format. I just decoded it using a website that decodes base64 strings.

```sh
FLAG: HRCTF{!_L0V3_H@CKRU$H}
```
