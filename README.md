<div align="center">

## What is Subclassing in a few words


</div>

### Description

I asked John Galanopoulos to explain sub classing in a few words ... I liked his reply which follows ... I take no credit for this and I'm only posting this as credit to him ...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Trevor Herselman](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/trevor-herselman.md)
**Level**          |Beginner
**User Rating**    |4.5 (18 globes from 4 users)
**Compatibility**  |VB 6\.0
**Category**       |[Windows System Services](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-system-services__1-35.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/trevor-herselman-what-is-subclassing-in-a-few-words__1-34190/archive/master.zip)





### Source Code

```
Windows sends messages to programs, windows, objects etc for notification purposes. For example when power state changes windows sends a signal to all running processes that there's been a change on the power status. The programs who use subclassing change their behaviour according to this signal. For example MS Word, saves all open files, so in case of an unexpected power down, the user won't loose the opened documents. Another example : When memory starts to run out, Windows sends a WM_COMPACTING signal to all windows loaded. If they use subclassing, they start to free as much memory as they can. So in general, subclassing is a method to receive windows messages.
check out this link also.. it might help you out a bit
http://www.1vbstreet.com/vb/scripts/ShowCode.asp?txtCodeId=34112&lngWId=1
```

