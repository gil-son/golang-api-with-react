# golang-api-with-react








<details><summary><h3>Pointers and Memory Allocation</h3></summary>

<div align="center">
  <img src="https://thumbs2.imgbox.com/0e/a1/lpWV1FQv_t.png" width="50%">
</div>
<hr/>
<div align="center">
  <img src="https://thumbs2.imgbox.com/2f/2a/t6aKd0Sc_t.png">
</div>
<hr/>
<div align="center">
  <img src="https://thumbs2.imgbox.com/c3/39/3e06emD8_t.png">
</div>
<hr/>
<div align="center">
  <img src="https://thumbs2.imgbox.com/d3/69/cGhIWOXr_t.png">
</div>
<hr/>
<div align="center">
  <img src="https://thumbs2.imgbox.com/3d/25/admoM99q_t.png">
</div>

<hr/>

```
package main
import "fmt"

func main() {
    var x int = 5 
    
    fmt.Println("x | address:",  &x)
    fmt.Println("x | value:", x)
    
	var p *int = &x 

	fmt.Println("p | address:", &p)
	fmt.Println("p | address -> x:", p)
    fmt.Println("p | value: -> x:",  *p)
}
```

</details>
