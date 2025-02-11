### Control your tokens borders. 
Player side configuration of the tokens borders, color and scale. Target HUD color and size can be altered, target HUD can also be rendered inside the token border.

Can prevent borders from showing on player clients for non-owned tokens; no longer hide your mimics behind tiles!

Increased accessability for those with visibility impairments

External border offset changeable.

Color gradient reads actor HP and returns a color between the two provided colors. 
Supported systems for color gradient are :

- DnD5e
- PF1
- PF2
- SWADE
- Symbaroum

Temp HP gradient moves up from the "full hp" color towards a defined color, maxing out at 1/2 hpMax.

This also fixes the current disposition bug: https://gitlab.com/foundrynet/foundryvtt/-/issues/4352

Nameplates are now customizable, change the size, vertical offset and font. You can also make then circular, to fit with POG style tokens
Available fonts are: Arial, Arial Black, Comic Sans MS, Courier New, Georgia, Helvetica, Impact, Tahoma, Times New Roman and Verdana.

A border may be toggled off by using the Token HUD element here

![BorderHUD](https://github.com/kandashi/Border-Control/blob/master/Border_Control_HUD.PNG?raw=true)
