This is a general catch-all for User Agent.
This is self executing and added to the window object

Short Example

```
if(Browser.is("ie78")){
	
}
else if(Browser.is("firefox")){ 

}
else{

}
```

Assigning a Click Events
Default is "click". Other "UP,DOWN,OVER,OUT,MOVE"

```
$("#butn_prev_page").bind(Browser.evt(),showPrevPage);
```