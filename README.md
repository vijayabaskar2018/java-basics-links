# java-basics-links

Immutable Class

https://javarevisited.blogspot.com/2013/03/how-to-create-immutable-class-object-java-example-tutorial.html#axzz6prTYgrDr

https://www.techiedelight.com/shallow-copy-vs-deep-copy-java/

https://howtodoinjava.com/java/cloning/a-guide-to-object-cloning-in-java/

https://howtodoinjava.com/java/collections/arraylist/arraylist-clone-deep-copy/

(1) Object.clone() does have an implementation. It makes a shallow copy of the object if the object implements Cloneable. 
(2) The .clone() method is not part of any interface. 
(3) Having a .clone() method and implementing the Cloneable interface are completely separate things. 
You only need to implement the Cloneable interface if you intend to make use of Object's clone method; however, 
this is the recommended way to write a clone method for your class -- 
to get its copy from the superclass's clone method, which eventually goes up to Object's clone method.
4) if you call clone() method without implementing Clonable interface will throw CloneNotSupportedException.

Garbage collection

finalize()
https://blog.jamesdbloom.com/JVMInternals.html

https://dzone.com/articles/java-memory-management

https://www.coderstea.com/post/java/get-ready-to-deep-dive-java-memory-management-garbage-collector/

https://titanwolf.org/Network/Articles/Article?AID=b29f7060-8967-4cf3-a109-b982279c3f4e#gsc.tab=0

https://javarevisited.blogspot.com/2011/04/garbage-collection-in-java.html#axzz6prTYgrDr

https://javarevisited.blogspot.com/2014/03/difference-between-weakreference-vs-softreference-phantom-strong-reference-java.html#axzz6prTYgrDr

Java Memory leaks

https://www.baeldung.com/java-memory-leaks

https://stackoverflow.com/questions/6470651/how-can-i-create-a-memory-leak-in-java

https://stackify.com/memory-leaks-java/

Singleton pattern

https://www.callicoder.com/java-singleton-design-pattern-example/

JAXB

https://www.javacodegeeks.com/2014/12/jaxb-tutorial-xml-binding.html

https://dzone.com/articles/jaxb-and-root-elements
