---
disqus: ""
hide:
  - navigation
---

# Contenuti divisi in tab
=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

### There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.


=== "What is Lorem Ipsum?"

    Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
	
	
=== "Why do we use it?"

    Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).

=== "Where does it come from?"

    Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. 

---
	
### Tabbed extension css for @cirospat 😜 😂😂😂
	
```
/*Tabbed extension css*/
.md-typeset .tabbed-labels { box-shadow: none!important;}

.md-typeset .tabbed-labels>label {border-bottom: .2rem solid transparent; font-size: 0.75rem!important; font-weight: 600!important;	background-color: #f5f5f58c; border-radius: 5px 5px 0px 0px;	border-left: .01rem solid #dbdbdb54; border-right: .01rem solid #dbdbdb54;  border-top: .01rem solid #dbdbdb54;}

.md-typeset .tabbed-content { width: 100%; text-align: justify!important; font-family: 'Roboto Mono'!important;	background-color: #f5f5f5; padding-left: 0.5rem;
padding-right: 0.5rem; border: .01rem solid #ff990047; border-radius: 0 5px 5px 5px; box-shadow: 0px 1px 1.2px rgb(0 0 0 / 25%);}

.md-typeset .tabbed-set>input:first-child:checked~.tabbed-labels>:first-child, .md-typeset .tabbed-set>input:nth-child(2):checked~.tabbed-labels>:nth-child(2), .md-typeset .tabbed-set>input:nth-child(3):checked~.tabbed-labels>:nth-child(3), .md-typeset .tabbed-set>input:nth-child(4):checked~.tabbed-labels>:nth-child(4), .md-typeset .tabbed-set>input:nth-child(5):checked~.tabbed-labels>:nth-child(5), .md-typeset .tabbed-set>input:nth-child(6):checked~.tabbed-labels>:nth-child(6), .md-typeset .tabbed-set>input:nth-child(7):checked~.tabbed-labels>:nth-child(7), .md-typeset .tabbed-set>input:nth-child(8):checked~.tabbed-labels>:nth-child(8), .md-typeset .tabbed-set>input:nth-child(9):checked~.tabbed-labels>:nth-child(9), .md-typeset .tabbed-set>input:nth-child(10):checked~.tabbed-labels>:nth-child(10), .md-typeset .tabbed-set>input:nth-child(11):checked~.tabbed-labels>:nth-child(11), .md-typeset .tabbed-set>input:nth-child(12):checked~.tabbed-labels>:nth-child(12), .md-typeset .tabbed-set>input:nth-child(13):checked~.tabbed-labels>:nth-child(13), .md-typeset .tabbed-set>input:nth-child(14):checked~.tabbed-labels>:nth-child(14), .md-typeset .tabbed-set>input:nth-child(15):checked~.tabbed-labels>:nth-child(15), .md-typeset .tabbed-set>input:nth-child(16):checked~.tabbed-labels>:nth-child(16), .md-typeset .tabbed-set>input:nth-child(17):checked~.tabbed-labels>:nth-child(17), .md-typeset .tabbed-set>input:nth-child(18):checked~.tabbed-labels>:nth-child(18), .md-typeset .tabbed-set>input:nth-child(19):checked~.tabbed-labels>:nth-child(19), .md-typeset .tabbed-set>input:nth-child(20):checked~.tabbed-labels>:nth-child(20){border-color: var(--md-accent-fg-color);  color: var(--md-accent-fg-color); background-color: #f5f5f5;    border-radius: 5px 5px 0px 0px; box-shadow: 0px 1px 1.2px rgb(0 0 0 / 65%);	border-left: .01rem solid #ff990047; border-right: .01rem solid #ff990047;  border-top: .01rem solid #ff990047;}

```	
	
### Aggiungere annotazioni nei blocchi di codice


``` yaml
theme: # (1)
  features: # (2)
    - content.code.annotate # (3)
```

1.  :man_raising_hand: I'm a code annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.

2. 	The generated Lorem Ipsum is therefore always free from repetition, injected humour, or non-characteristic words etc.
	
3. Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. 

---

### Where does it come from?
The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.


