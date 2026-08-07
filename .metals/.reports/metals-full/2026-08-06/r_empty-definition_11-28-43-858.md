error id: file:///C:/Users/rahul/Github/My_Python-codes/Scala%20codes/new.scala:scala/StringContext#f().
file:///C:/Users/rahul/Github/My_Python-codes/Scala%20codes/new.scala
empty definition using pc, found symbol in pc: 
empty definition using semanticdb
empty definition using fallback
non-local guesses:

offset: 301
uri: file:///C:/Users/rahul/Github/My_Python-codes/Scala%20codes/new.scala
text:
```scala
object HelloWorld {
  def main(args: Array[String]): Unit = {

val name = "Rahul"; val age = 28

val a = s"$name is $age"              // s-interpolator: substitutes variables/expressions
val b = s"next year: ${age + 1}"     // braces needed for expressions, not just bare identifiers
val c = f@@"$name%s is $age%03d"        // f-interpolator: printf-style formatting, type-checked
val d = raw"line1\nline2"            // raw: no escape processing — \n stays literal backslash-n

println(a)
println(b)
println(c)
println(d)

// val price = 1234.52345678
// println(price)
// println(price.formatted("%.4f")) // formatted: formats a number to a string with specified decimal places 
  }
}


```


#### Short summary: 

empty definition using pc, found symbol in pc: 