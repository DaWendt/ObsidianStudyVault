Bsp.:
```
func Reverse(s string) string {

	r := []rune(s) 
	
	for i, j := 0, len(r)-1; i < len(r)/2; i,j = i+1, j-1 {
		r[i], r[j] = r[j], r[i]
	}

	return string(r)
}
```

--> Typen stehen generell hinter zeug
--> Arrays werden "Slice" genannt
--> Swap: i,j = j,i
	--> berechnet zuerst rechte Seite und weist es dann auf die linke zu

#Ver-Sys 