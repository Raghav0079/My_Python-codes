error id: file:///C:/Users/rahul/Github/My_Python-codes/Scala%20codes/Update.scala:scala/StringContext#s().
file:///C:/Users/rahul/Github/My_Python-codes/Scala%20codes/Update.scala
empty definition using pc, found symbol in pc: 
empty definition using semanticdb
empty definition using fallback
non-local guesses:

offset: 222
uri: file:///C:/Users/rahul/Github/My_Python-codes/Scala%20codes/Update.scala
text:
```scala
object Update {
  def main(args: Array[String]): Unit = {
    println("--- Updated File ---")

    val x= 10
    var y = 20

    println(s"Initial values: x = $x, y = $y")

    // x= 11
    y = 25

    println(@@s"Updated values: x = $x, y = $y")

  }
}
```


#### Short summary: 

empty definition using pc, found symbol in pc: 