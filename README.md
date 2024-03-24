package main

import "fmt"

type Person struct {
  name string
  username string
  age int
  hobbies []string
  job string
}

func main() {
  var me = new(Person)
  
  me.name     = "KAYES BIN SABITH"
  me.username = "kayes2015"
  me.age      = "28"
  me.job      = "AI developer | Web developer"
  me.hobbies  = []string{"code", "anime", "music"," guiterist"," gaming"}
  
  fmt.Println(me)
}
