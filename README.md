<div align="center">
  
```cs
using Me;
using Me.Languages;

public class MyLife 
{
  Me me;
  public static void Main() 
  {
    me = new Me("kaankny");
    while (me.alive) 
    {
      me.eat();
      me.doCoding(Languages.CSharp);
      me.sleep();
    }
  }
}
```
</div>
