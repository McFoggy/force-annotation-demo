# responsible annotations

Demo project for a blog [post](http://blog.matthieu.brouillard.fr/2016/11/26/ensure-annotation-on-classes/) on how to enforce the definition of annotations on java types using annotation processing.

When building: `mvn clean install`, the build MUST fail with the following error:

```
[INFO] -------------------------------------------------------------
[ERROR] COMPILATION ERROR : 
[INFO] -------------------------------------------------------------
[ERROR] fr.brouillard.oss.app.ServiceTwo must be annotated with @fr.brouillard.oss.annotation.Responsible to declare a ownership
[INFO] 1 error
```