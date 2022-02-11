# Learn Markdown
Learn simple Markdown syntaxes in just a second...

## Paragraph
Facere ultrices massa accumsan nascetur veniam in! Officia, sit nisl dis tenetur lectus sagittis? Nostrum sapiente, velit inventore, cursus quo anim nihil corporis rem dolores, urna quis, nunc facilisi? Platea donec nunc senectus illo aenean, eveniet, debitis alias interdum hac! Quis voluptates, unde luctus quos ducimus vestibulum vero? Temporibus gravida mus reiciendis! Metus officiis dolore vero! Taciti gravida anim blandit accusamus ea pretium nesciunt torquent varius! Pellentesque tincidunt aliquam animi, massa est, ab debitis similique dolor euismod deleniti eum cubilia! Duis natus omnis nunc, vulputate, diam vitae fringilla inventore nascetur tincidunt voluptate corrupti turpis quam velit, hic alias natoque mollitia.

## Internal Link
- `[Home](index.md)`
- Go to [Home](index.md)

## Internal Link with anchor
- `[KYC Flowchart](./kyc/index.md#copy-kyc-files-flowchart)`  
- Go to [KYC Flowchart](./kyc/index.md#copy-kyc-files-flowchart)

## External Link
`[External Link](https://thouradev.com/)`  
[External Link](https://thouradev.com/) 

## External Link With Title
`[External Link with Title](https://thouradev.com/  "Title Here")`  
[External Link with Title](https://thouradev.com/  "Title Here") 

## Italic

`_Italic Text_`  
_Italic Text_

## Image
- `![Copy KYC File 1](./img/jerry.png "Jerry Image")`
- ![Copy KYC File 1](./img/jerry.png "Jerry Image")

## H1 - H6
   1. `# This is a H1`
   2. `## This is a  H2`
   3. `### This is a  H3`
   4. `#### This is a  H4`
   5. `##### This is a  H5`
   6. `###### This is a  H6`

## Nested Level
```
> Level 1
>> Level 2
>>> Level 3
>>>>...> Level n
```
> Level 1
>> Level 2
>>> Level 3

> Back to the first level
>
> > > Back to the first level
>
> > > > Back to the first level

## Unordered List

```
+
*
-
```

+   Red
*   Green
-   Blue

## Ordered List
```
1. One
2. Two
3. Three
4. Four
5. Five
```
1. One
2. Two
3. Three
4. Four
5. Five

## Line Separator
`* * *`
* * *

`***`
***

`*****`
*****

`- - -`
- - -

`---------------------------------------`
 ---------------------------------------

## Table

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

**Result:**  

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

***

```
| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |
```

**Result:**  

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |

## Fenced code blocks

`Single Quote`

``Double Quotes``

```
Triple Quotes
```

```
Title:   My Document
Summary: A brief description of my document.
Authors: Waylan Limberg
         Tom Christie
Date:    January 23, 2018
blank-value:
some_url: https://example.com

This is the first paragraph of the document.
```

## Code Snippet

- Python:  
```python
def fn():
    pass
```
- Java
```Java
public static void main(String[] args) {
    //do something
}
```
- Script
```Script
cd first-project
```
- Javascript
```js
function doSomething() {
    //do something
}
```