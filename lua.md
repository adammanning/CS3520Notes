# Lua
---
## References

Lua on [*Learn X in Y Minutes*](https://learnxinyminutes.com/docs/lua/)

[*Passing a Language Through the Eye of a Needle*](http://queue.acm.org/detail.cfm?id=1983083)

---
Lua is an embedded language, like javascript
- How do you communicate with the host language?
- In Javascript we interact with the browser by querying the DOM

---

## Language Types
- **Statically Typed:** Variable has a type
- **Dynamically Typed:** Value has a type
- **Strongly Typed:** Cannot use one type as another
- **Weakly Typed:** Can use one type as another

Lua is dynamically typed

---

## Loops
- For
- Repeat-Until

---

[//]: <> (All javascript language types are for syntax highlighting only)

## Assignment
``` javascript
	x, y, z = 1, 2, 3, 4
	-- 4 is thrown away
```

---

## Tables
- The main data structure in Lua
- Square brackets around a key allow for any kind of key
	- Be careful with objects as keys as Lua looks for the same object used to create the key

### Table Declaration
``` javascript
	t = {key1 = 'value1', key2 = false}
```

### Table Iteration
``` javascript
	for key, val in pairs(u) do
		print(key, val)
```

---
