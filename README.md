#Scala
Scala combines object-oriented and functional programming in one concise, high-level language. Scala's static types help avoid bugs in complex applications, and its JVM and JavaScript runtimes let you build high-performance systems with easy access to huge ecosystems of libraries.

### Variables:
declarition of varaibles in scala :
`var myName = "dsadsa" (var is similar to js,mutable)`
`val myName = "dsadsa" (val is similar to const in js , it will not change,imutable)`
`var isCheck = if(age >= 18) true else false`

### Conditions:
example :

    if((age >= 5) && (age <= 6)){
    println("good")}else if((age ==0)){
    println("bad")
    } else {
    println("good" + (age - 5))
    }

### Loops:
##### while :
    while(i <= 10){
    println(i)
    i += 1
    }
##### do:
    do {
    println(i)
    i +=1
    }while(i <= 20)
##### for:
    for (i <- 1 to 10)
    	println(i)

    var randomString = "Adasdsadas"
    for(i <- 0 until randomString.length)
    		 println(randomString(i))

    val aList = List(1,2,3,4,5)
    for(i <- aList){
    		 println(i)
    		 }
			 
    for (i <- 1 to 5; j <- 6 to 10){
    println("i="+i)
    println("j="+j)
    }
