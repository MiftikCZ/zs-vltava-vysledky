# [ZSvltava.cz převody](http://www.zsvltava.cz/fyzika/prevody) solver
Napíše správné odpovědi příkladů do konzole

# kód
```js
$.each($("#tblZadani tbody tr"),function(i,v){        
  var a = RightAnswer($(this).find('input[type="hidden"]').val().trim());
   
  var v = $(this).find("td input").val().trim().split(",");
  var result = v[0];
  console.log(a)
})
```

# postup
> Klikni `F12` a tam napiš kód který máš tady ^
