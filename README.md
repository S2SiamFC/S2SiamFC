# S<sup>2</sup>SiamFC
A temporal repository for S<sup>2</sup>SiamFC.

The results of VOT2016 & VOT2018 are under ./results.

## Analysis about Anti-Clutter weighting in video level on VOT2018
<b>Note: The following results are based on existing experimental results (the first two rows in Table 3 in the paper) but in detail. Therefore, it should obey the rebuttal policy.</b>

`↑ denotes larger is better; ↓ denotes smaller is better`

### 1. Results of Anti-cluttering weighting on VOT2018 in the video level.
There are some some successful cases that can illustrate the contributions of anti-clutter weighting:
<table>
<tr>
<td align="center">  <td colspan=1 align="center"> S<sup>2</sup>SiamFC with AC weighting <td colspan=1 align="center">S<sup>2</sup>SiamFC without AC weighting
<tr>
<td colspan=1 align="center">Video name <td colspan=1 align="center">Lost Number &#8595;<td colspan=1 align="center">Lost Number &#8595;
<tr>
<td colspan=1 align="center">   ball2    <td colspan=1 align="center"> <b>1.000  <td colspan=1 align="center"> 2.000 
 <tr>
<td colspan=1 align="center">   birds1    <td colspan=1 align="center"> <b>3.000  <td colspan=1 align="center"> 4.000 <tr>
<td colspan=1 align="center">   blanket    <td colspan=1 align="center"> <b>1.000  <td colspan=1 align="center"> 2.000 <tr>
<td colspan=1 align="center">   book    <td colspan=1 align="center"> <b>3.000  <td colspan=1 align="center"> 5.000 <tr> 
<td colspan=1 align="center">   butterfly    <td colspan=1 align="center"> <b>1.000  <td colspan=1 align="center"> 3.000 <tr> 
<td colspan=1 align="center">   conduction1    <td colspan=1 align="center"> <b>0.000  <td colspan=1 align="center"> 4.000 <tr> 
  <td colspan=1 align="center">   fish2    <td colspan=1 align="center"> <b>7.000  <td colspan=1 align="center"> 8.000 <tr> 
  <td colspan=1 align="center">   fish3    <td colspan=1 align="center"> <b>2.000  <td colspan=1 align="center"> 3.000 <tr> 
  <td colspan=1 align="center">   flamingo1    <td colspan=1 align="center"> <b>6.000  <td colspan=1 align="center"> 8.000 <tr> 
  <td colspan=1 align="center">   gymnastics1    <td colspan=1 align="center"> <b>7.000  <td colspan=1 align="center"> 9.000 <tr> 
  <td colspan=1 align="center">   gymnastics2    <td colspan=1 align="center"> <b>4.000  <td colspan=1 align="center"> 6.000 <tr> 
  <td colspan=1 align="center">   handball1    <td colspan=1 align="center"> <b>7.000  <td colspan=1 align="center"> 8.000 <tr> 
  <td colspan=1 align="center">   handball2    <td colspan=1 align="center"> <b>5.000  <td colspan=1 align="center"> 6.000 <tr> 
  <td colspan=1 align="center">   iceskater1    <td colspan=1 align="center"> <b>7.000  <td colspan=1 align="center"> 11.000 <tr> 
  <td colspan=1 align="center">   iceskater2    <td colspan=1 align="center"> <b>5.000  <td colspan=1 align="center"> 8.000 <tr> 
  <td colspan=1 align="center">   leaves    <td colspan=1 align="center"> <b>4.000  <td colspan=1 align="center"> 5.000 <tr> 
  <td colspan=1 align="center">   nature    <td colspan=1 align="center"> <b>5.000  <td colspan=1 align="center"> 6.000 <tr> 
  <td colspan=1 align="center">   traffic    <td colspan=1 align="center"> <b>0.000  <td colspan=1 align="center"> 1.000 <tr> 
<td colspan=1 align="center">   zebrafish1    <td colspan=1 align="center"> <b>17.000  <td colspan=1 align="center"> 19.000 <tr>
<td colspan=1 align="center">  iceskater1   <td colspan=1 align="center"> <b>5.000   <td colspan=1 align="center"> 11.000 <tr>
<td colspan=1 align="center">     road   <td colspan=1 align="center"> <b>1.000  <td colspan=1 align="center"> 5.000  
 <tr>
<td colspan=1 align="center">   soccer1    <td colspan=1 align="center"> <b>9.000 <td colspan=1 align="center"> 10.000 <tr>
<tr>
 
</table>
The demo on "conduction1" and "butterfly":

`Green denote GT`
`Red denote S^2SiamFC with AC weighting`
`Blue denote S^2SiamFC without AC weighting`

![image](https://github.com/S2SiamFC/S2SiamFC/blob/master/conduction.gif)
![image](https://github.com/S2SiamFC/S2SiamFC/blob/master/butterfly.gif)

### 2. Overall results of Anti-cluttering weighting on VOT2018.
|   VOT2018   | Accuracy &#8593;   | Robustness &#8595; | EAO &#8593; |
|:---: | :---:  | :---:  | :---:  |
|S<sup>2</sup>SiamFC with AC weighting| <b>0.476</b>  | <b>1.110</b>  | <b>0.136</b> |
|S<sup>2</sup>SiamFC without AC weighting| 0.472  | 1.232  | 0.130 |


