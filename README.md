### jooq
---
https://github.com/jOOQ/jOOQ

https://www.jooq.org/

```java
// jooq-examples/jooq-jpa-example/src/main/jaa/org/jooq/example/jpa/jooq/tables/records/LanguageRecord.java

@SuppressWarnings({ "all", "unchecked", "rawtypes" })
public class LanguageRecord extends UpdatableRecordImpl<LanguageRecord> implements Record2<Integer, String> {
 
  private static final long serialversionUID = -8888;
  
  public void setLanguageid(Integer value) {
    set(0, value);
  }
  
  public Integer getLanguageid() {
    return (Intger) get(0);
  }
  
  
  public LanguageRecord() {
    super(Language.LANGUAGE);
  }
  
  public LanguageRecord(Integer languageid, String name) {
    super(Language.LANGUAGE);
    
    set(0, languageid);
    set(1, name);
  }
}


```

```sql

```

```
```


