<!--HEADING -->
# my title h1
## mytitle h2
### mytitle h3
#### mytitle h4
##### mytitle h5
###### mytitle h6


<!-- STYLES TEXT-->
<!-- italic-->
this is an *italic* text
<!-- strong-->
this is an **strong** text
<!-- strikethrough-->
this is an ~~tached~~ text

<!--UL-->
* apples
  * apple green
  * apple red 
* orange
* lemon

 <!--Order list--> 
 1. apples
     1. apple green
     2. apple red
 2. orange
 3. lemon
   
<!-- create link-->
You can go to link [fastweb.com](https://www.faztweb.com)

[fastweb.com](https://www.faztweb.com "Custom title")

<!-- generate quote o citas-->
> this is a quote

<!-- create HR o linea horizontal-->
---
___

<!--type code-->
`console.log('Hello world');`

```java
package com.devsuperior.dsmovie.entities;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.GenerationType;
import javax.persistence.Id;
import javax.persistence.Table;

@Entity
@Table(name ="tb_user")
public class User {

	@Id
	@GeneratedValue(strategy = GenerationType.IDENTITY)
	private Long id;
	private String email;
	
	
	public User() {
		
	}


	public User(Long id, String email) {
		this.id = id;
		this.email = email;
	}
}
```

```python
print("Hello world)
```
```html
<h1>Hello world</h1>
```

<!--Create table (usar Tab)-->
|Tables    |Are          |Cool  |
|----------|-------------|------|
|col 3 ls  |right-aligned|$1600 |
|col 2 ls  |centred      |  $12 |

<!-- Generate Images-->
**Image logo visual studio code from URL**
![visual studio code logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/512px-Visual_Studio_Code_1.35_icon.svg.png "vscode logo")

**Image logo visual studio code from file**
![visual studio code logo from file](vscode.png "vscode logo")

 <!--   GITHUB MARKDOWN-->
 * [*] Task Completed
 * [] Task Uncomplete
 * [] Task Uncomplete
 * [*] Task Completed





