<div align="center">

## create a YES or NO msgbox


</div>

### Description

simply pops up an msgbox with a yes or no choice below (very simple)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[sean mckeown](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sean-mckeown.md)
**Level**          |Unknown
**User Rating**    |4.4 (22 globes from 5 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sean-mckeown-create-a-yes-or-no-msgbox__1-4226/archive/master.zip)





### Source Code

```
dim a as integer
a% = msgbox("Message box message ;-)",10+10)
if a% = 6 then '6 indicates a YES
msgbox "yes was choosen"
else
msgbox "no was choosen"
end if
```

