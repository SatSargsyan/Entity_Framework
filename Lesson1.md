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


#### Unem 100000 togh, incpes jnjel entity-ov

Ete remove anem, petq e nakh kardal, vorn optimal che,
dra hamar proc em sarqum 


Ete query-i ardyunqum mets dataset em stanum, entity-n ardyunavet che
st.phone.add
```C#
db.Entry(st).State=EntityDtate.Modified;
```
miayn ayd masn update kani, ev optimal e, qani vor lracucich chenq kardum
#### [DbContext.Entry Method (Object)](https://msdn.microsoft.com/en-us/library/gg696238(v=vs.113).aspx)


```c#
await db.SaveChangesAsync();
```

save-Y ciklic durs enq anum, vor amen angam bazanerin chdimi



