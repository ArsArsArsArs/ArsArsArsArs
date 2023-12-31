```golang
func GenerateNickname(realName string, iq int) string {
  var output string
  for i := 0; i < iq; i++ {
    output += realName
  }
  return output
}
```
