#
####  If we want, that in app.config we can use another name not default generated, we must  to create another partial class, where in constructor, we will write:
```C#
 public partial class BetSatSargsyanEntities
    {
        public BetSatSargsyanEntities(string name)
            : base(name)
        {
        }
    }
    
    class program
    {
        static void Main(string[] args)
        {
           var db = new BetSatSargsyanEntities("name=DefaultConnection"); 
        }
     }
 
    


```

And so in the app.config  file we can write ="DefaultConnection" nam-i pokharen
####  If we want, that 







#### publish enq anum

#### ON DELETE CASCADE  GRELOV  KJNJI STUDENTI TVYALNERY PHone table-ic kjnji hamarnery ayn student-i tvyalnery, vorin jnjel enq studentner-i table-ic


update model from database
validate
