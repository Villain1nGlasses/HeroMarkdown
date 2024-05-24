[md]

[css](-Ny20scsdV4yq_kXEbAi)

# PAGE TITLE

---

## CHAPTER

### SECTION

---

![featured featured name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Karl_Friedrich_Schinkel.png?raw=true)

---

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

___

# Formatting Examples

---

## The easiest way to use this section is to open the GM Notes to view the formatting.

---

___

---

# Heading 1

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

#### Quote Block

> Quote

> Multi-line quote sentence one.
> Multi-line quote sentence two.

> Nested.
> > Quotes.

```
Code Block
```

The part in yellow is ```inline code.```

---

## Line Breaks/Horizontal Rules

### Solid White Line

___

### Thematic Break

***

### Blank Space

---

## Tables

---


|Cell A1 Left Justified| Center Justified Cell B1| Right Justified Cell C1|
|:----|:----:|----:|
|Cell A2|Cell B2|Cell C2|
|Cell A3|Cell B3|Cell C3|
|Cell A4|Cell B4|Cell C4|

```
|Cell A1 Left Justified| Center Justified Cell B1| Right Justified Cell C1|
|:----|:----:|----:|
|Cell A2|Cell B2|Cell C2|
|Cell A3|Cell B3|Cell C3|
|Cell A4|Cell B4|Cell C4|
```

---

## Lists

1. Item # 1
1. Item # 2   
	1. Sub Item # 1 (indented four (4) spaces)        
	1. Sub Item # 2 (indented four (4) spaces)
1. Item # 3

- Item
- Item
	- Sub Item (indented four (4) spaces)
	- Sub Item (indented four (4) spaces)
- Item

```
1. Item # 1
1. Item # 2   
	1. Sub Item # 1 (indented four (4) spaces)        
	1. Sub Item # 2 (indented four (4) spaces)
1. Item # 3

- Item
- Item
	- Sub Item (indented four (4) spaces)
	- Sub Item (indented four (4) spaces)
- Item
```

---

## Floating Right Sidebar

Use the below code directly in your markup to make a floating right sidebar.

<div style="font-family: Open Sans, Museo Sans, Raleway, Tahoma, Nunito, arial; float:right; margin-left: 6px; width: 40%; margin-top: 1em; margin-bottom: 1em; padding: 5px 10px; background-image: linear-gradient(#e5f0f7, #99c6e0); border-top: 4px solid #0072B2; color: black;">

## Content Here

Can be any of the standard markup.

![right20 Right 20 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true) Including images

</div>

```

<div style="font-family: Open Sans, Museo Sans, Raleway, Tahoma, Nunito, arial; float:right; margin-left: 6px; width: 40%; margin-top: 1em; margin-bottom: 1em; padding: 5px 10px; background-image: linear-gradient(#ddf0fa, #88caef); border-top: 2px solid; border-bottom: 2px solid; border-left: 0px solid; border-right: 0px solid;">

## Content Here

Can be any of the standard markup.

![right20 Right 20 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true) Including images

</div>

```

---

---

## Links and Other Formatting


**Link to Handout:** [(Markdown Getting Started)]
**Link to webpage:** [Journal Command Buttons](https://wiki.roll20.net/Journal#Journal_Command_Buttons)
**Link to chat roll:** [Attack Roll](`/roll 11-3d6+5 vs DCV)
**Link to chat inline roll:** [Roll 1d6](`[[1d6]])
**Link to API command:** [API Command](`!apitlinktest)

```
**Link to Handout:** [(Markdown Getting Started)]
**Link to webpage:** [Journal Command Buttons](https://wiki.roll20.net/Journal#Journal_Command_Buttons)
**Link to chat roll:** [Dagger Attack](`/roll 1d20+2 vs AC /roll 1d4 Damage )
**Link to chat inline roll:** [Roll 1d6](`[[1d6]])
**Link to API command:** [API Command](`!apitlinktest)
```

---

## Font Styles

---
*italic*

**bold**

***italic and bold***

~~strike~~

```
*italic*

**bold**

***italic and bold***

~~strike~~
```

---
<div style="text-align: center">

#### Center this section
Using direct HTML
</div>


```
<div style="text-align: center">
#### Center this section
Using direct HTML
</div>
```

---

## Standard CSS items included in stylesheet

```
bg // background
p // standard text
h1, h2, h3, h4, h5, h6 // headers
pre // code block
code // inline code
blockquote, p.blockquote // blockquote
table, tbody // table
tr:first-child, tr:nth-child(even), tr:nth-child(odd), tr:nth-child(last) // table header/even/odd rows
tr:nth-child(last):nth-child(even), tr:nth-child(last):nth-child(odd) // table header/even/odd last rows
td.align-left, td.align-center, td.align-right, // |:---|:----:|---:| // table alignment
ol, ul, li.ordered, li.unordered // ordered and unordered lists

___, ---, *** // horizontal rule

```

___



# Using Images

## In-Line Icons to Use Within Text

![warning_icon Sometimes surprisingly effective element](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Warning.png?raw=true) **Warning Icon** Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.

![stop_icon Campaign altering element](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/STOP.png?raw=true) **Stop Icon** Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

![superhero_icon Superheroic campaign icon](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Bolt.png?raw=true) **Superheroic Icon** Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.

![hero_icon Heroic campaign icon](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Blue.png?raw=true) **Heroic Icon** Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

![grimoire_icon Grimoire spell icon](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Spell_Pentagram.png?raw=true) **Grimoire Icon** Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.

___

---

## HERO Icons (full size)


![ HERO Icon Blue](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Blue.png?raw=true) ![ HERO Icon Light Blue](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Light_Blue.png?raw=true)

![ HERO Icon Light Gray](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Light_Gray.png?raw=true) ![ HERO Icon Yellow](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Yellow.png?raw=true)

___

---

## HERO Dice Faces (quarter size)

![hero_dice HERO Dice 1](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_1.png?raw=true) ![hero_dice HERO Dice 2](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_2.png?raw=true) ![hero_dice HERO Dice 3](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_3.png?raw=true) ![hero_dice HERO Dice 4](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_4.png?raw=true) ![hero_dice HERO Dice 5](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_5.png?raw=true) ![hero_dice HERO Dice 6](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_6.png?raw=true)

___

---

### Right Thumb (140px max height)

![right-thumb right thumb name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Hero_System_Sixth_Edition_Blue.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---

___

---

### Left Thumb (140px max height)

![left-thumb left thumb name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Hero_System_Sixth_Edition_Color.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---

___

---

### Featured Image (80% Width)

![featured featured name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Karl_Friedrich_Schinkel.png?raw=true)

---

---

___

---

### Left Icons (50px max width)

![left-icon Left Icon Chapter 1](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_01.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

![left-icon Left Icon Chapter 2](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_02.png?raw=true) ![left-icon Left Icon Chapter 3](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_03.png?raw=true) ![left-icon Left Icon Chapter 4](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_04.png?raw=true) ![left-icon Left Icon Chapter 5](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_05.png?raw=true) ![left-icon Left Icon Chapter 6](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_06.png?raw=true)

---

---

___

---

### Right Icons (50px max width)

![right-icon Right Icon Chapter 7](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_07.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

![right-icon Right Icon Chapter 8](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_08.png?raw=true) ![right-icon Right Icon Chapter 9](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_09.png?raw=true) ![right-icon Right Icon Chapter 10](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_10.png?raw=true) ![right-icon Right Icon Chapter 11](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_11.png?raw=true) ![right-icon Right Icon Chapter 12](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_12.png?raw=true)

---

---

___

---

### Center (full size)

![center Center Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true)

---

---

### Left 20% Width

![left20 Left 20 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---


### Right 20% Width

![right20 Right 20 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---

### Left 40% Width

![left Left 40 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Willem_van_de_Veld_Calm_Sea.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---

### Right 40% Width

![right Right 40 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Castle_on_the_Rhine.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---

### Left 60% Width

![left60 Left 60 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Giovanni_Maria_Quaglio.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---

### Right 60% Width

![right60 Right 60 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Romolo_Achille_Liverani.png?raw=true) Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

---

---

___

```

![warning_icon Sometimes surprisingly effective element](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Warning.png?raw=true)

![stop_icon Campaign altering element](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/STOP.png?raw=true)

![superhero_icon Superheroic campaign icon](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Bolt.png?raw=true)

![hero_icon Heroic campaign icon](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Blue.png?raw=true)

![grimoire_icon Grimoire spell icon](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Spell_Pentagram.png?raw=true)

---

---

![ HERO Icon Blue](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Blue.png?raw=true) 

![ HERO Icon Light Blue](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Light_Blue.png?raw=true)

![ HERO Icon Light Gray](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Light_Gray.png?raw=true) 

![ HERO Icon Yellow](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Yellow.png?raw=true)

---

---

![hero_dice HERO Dice 1](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_1.png?raw=true) 
![hero_dice HERO Dice 2](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_2.png?raw=true) 
![hero_dice HERO Dice 3](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_3.png?raw=true) 
![hero_dice HERO Dice 4](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_4.png?raw=true) 
![hero_dice HERO Dice 5](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_5.png?raw=true) 
![hero_dice HERO Dice 6](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Dice_Face_6.png?raw=true)

---

---

![right-thumb right thumb name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Hero_System_Sixth_Edition_Blue.png?raw=true) 

![left-thumb left thumb name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Hero_System_Sixth_Edition_Color.png?raw=true)

![featured featured name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Karl_Friedrich_Schinkel.png?raw=true)

---

---

![left-icon Left Icon Chapter 1](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_01.png?raw=true)
![left-icon Left Icon Chapter 2](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_02.png?raw=true)
![left-icon Left Icon Chapter 3](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_03.png?raw=true)
![left-icon Left Icon Chapter 4](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_04.png?raw=true)
![left-icon Left Icon Chapter 5](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_05.png?raw=true)
![left-icon Left Icon Chapter 6](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_06.png?raw=true)

---

---

![right-icon Right Icon Chapter 7](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_07.png?raw=true)
![right-icon Right Icon Chapter 8](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_08.png?raw=true)
![right-icon Right Icon Chapter 9](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_09.png?raw=true)
![right-icon Right Icon Chapter 10](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_10.png?raw=true)
![right-icon Right Icon Chapter 11](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_11.png?raw=true)
![right-icon Right Icon Chapter 12](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/HERO_Chapter_Hexagon_12.png?raw=true)

---

---

![center Center Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true)

![left20 Left 20 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true)

![right20 Right 20 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Rossetti_Joan_of_Arc.png?raw=true)

![left Left 40 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Willem_van_de_Veld_Calm_Sea.png?raw=true)

![right Right 40 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Castle_on_the_Rhine.png?raw=true)

![left60 Left 60 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Giovanni_Maria_Quaglio.png?raw=true)

![right60 Right 60 Name](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/graphics/Romolo_Achille_Liverani.png?raw=true)

```

---

---

---

---

---