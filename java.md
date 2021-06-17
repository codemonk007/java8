--------
java->JVM->OS
cunstructor->overload
-----
method overload
classes, interface,abstract class
---------
OOPS: 
abstarction
    can have public,private,static methods.
inherritance
    upcasting ,downCasting
encapsulation
    private,public,protected.
    getters and setters
polimorphism
    method overriding,
    method overloading.
    ducktyping.
    interface and child implimention through 
______________
Collection :

List : Interface
insertion order mentained 
hetero Objects allowed 
null allowed 
duplicates allowed  
ArrayList : Implementation class
LinkedList
Vector
-----------------------------------------------------
Set 
    Hashset
    linkedhash set
    tree set
    Map
    hashmap
    linkedHashmap
    treemap
Hash Table is common underlying datastructure
Duplicates are not allowed
one null insertion .
order not promised.
with LinkedHashset insertion order is promised
with tree set sorted set is promised.
navigable set brigs up few other implemented methods on navigating the sets.
--------
MAP
    key value pair .
    null key one insertion is allowed
    order is not maintained
    with linkedhashmap-> order is maintained.
    with tree set sorting is allowed
----------
custom sorting 
1) comparable interface-> compareTo(Object Obj) method
2) comparator interface -> compare(Object obj1,Object obj2);

while creting instance invoke this method.
-----------
Thread-->run
runnable->interface->start
    thread states:
        new
        runnable
        running
        blocked
        waiting
        terminated
    sleep
    yeild
    thread.setPriority

    thread.join()-> causs this perticular thread is completed.
    thread.yield() ->   ready to be waiting state.
    using synchronised keyword we can make the method threadsafe.
    transient keyword variables willnot be stored when we do a save.
---------
functional Interface
@functional inteface
library methods
predicate -> test
function -> apply
consumer -> accept
supplyer -> get
------------
Exception Handling 
Hirarchy
------------





