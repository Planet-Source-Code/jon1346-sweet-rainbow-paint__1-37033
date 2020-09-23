<div align="center">

## Sweet\! Rainbow Paint


</div>

### Description

It's like that ad for "rainbow art" or whatever.
 
### More Info
 
What makes this code so cool? It's simple, and you can tweak it to ANY COLOR IMAGINABLE! All you need to do is change the rgb values!


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jon1346](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jon1346.md)
**Level**          |Beginner
**User Rating**    |4.8 (24 globes from 5 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__1-46.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jon1346-sweet-rainbow-paint__1-37033/archive/master.zip)





### Source Code

```
Private Sub Form_MouseMove(Button As Integer, Shift As Integer, X As Single, Y As Single)
Static r 'r
r = r + 10: If r > 510 Then r = 0 'make it fade
 For i = 0 To 200 '200 is brush tip size
 Circle (X, Y), i, RGB(Abs(r - 250), 0, Abs(r - 6)) 'heart of fading- change the Red, Green, Blue to get different colors!
 Next i 'make another circle
End Sub
```

