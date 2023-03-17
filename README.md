# git3
package main
import(
	"fmt"
)
func main(){
	for m:=1;m<100;m++{
		if m%3==0 && m%5==0{
			fmt.Printf("%d foo bar\n",m)
		}else if m%5==0{
			fmt.Printf("%d bar\n",m)
		}
	}
}