# HeroMarkdown
HERO System style specification for BaldarSilveraxe's (AKA Stephen S.) Roll20 [markdown scripts](https://gist.github.com/BaldarSilveraxe/). This example is modeled after Slugnet's excellent example for [Alien RPG](https://github.com/slugnet/roll20/tree/main/AlienRPGMarkdown). 

The [Roll20 forum thread](https://app.roll20.net/forum/post/8028597/script-markdown-handouts-and-bios/?pagenum=1) may be of interest.

# Quickstart Using the HERO System CSS and Markdown in Roll20

## Part 1 - Install the API Scripts on Roll20
You will need to either have an existing game on Roll20, or create a new game.

Install the three mods (aka API scripts) into your game:
- [markdown.js](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/markdown.js) (Updated with fixes for tables.)
- [markdownNotesBio.js](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/markdownNotesBio.js)
- [markdownDocumentation.js](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/markdownDocumentation.js)

For further documentation on installing mods, please visit the [Roll20 Mod (API) help page](https://help.roll20.net/hc/en-us/articles/360037256714-Roll20-Mods-API).

## Part 2 - Using the Markdown in a Roll20 Game
Once you have installed the API scripts, launch the game in Roll20. To prepare a handout for application of markdown code follow the steps below.

### A. Getting Started
Create a new **"Handout"** named **"Style Sheet"**. Scroll down to the **"GM Notes"** section and past the following two lines:
```
[css]
h1 {color: red;}
```
**Save changes.**

In the **"Description & Notes"** section you should see the processed **CSS**
```
[css](-O3fF3GCNgPDgG9m9-4L)
h1 {color: red;}
```

Like so:

![Style Sheet](/images/Style_Sheet_Example.png?raw=true)

> [!NOTE]  
> The unique id "-O3fF3GCNgPDgG9m9-4L"` is the object id for the style sheet.
> ***Copy*** your version of this line.

Create a new handout named **"Markdown Handout"** and in the **"GM Notes"** paste the copied code. Add two additional lines of code like so:
```
[md]
[css](-O3fF3GCNgPDgG9m9-4L)
# This Heading should be red.
```
> **Remember:** The "-O3fF3GCNgPDgG9m9-4L"` part is the object id for your handout. It will not be the same as you see in this example.
> 
**Save changes.**

In the **"Description & Notes"** section you should see the processed **Markdown.**
It should be large red text reading:

```
This Heading should be red.
```
Like so:

![Markdown Handout](/images/Markdown_Handout_Example.png?raw=true)

### B. Switching to HERO System Styling
If all has worked correctly in the previous steps, do the following.

Open the [HERO-CSS-Markdown file](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/HERO-CSS-Markdown.css). At the top of the page replace the object id below
```
[css](-O3fF3GCNgPDgG9m9-4L)
```

with your updated object id.

Now copy everything in *HERO-CSS-Markdown.css* and paste it to the **"GM Notes"** section of the **"Style Sheet"** handout, overwriting the existing contents.

**Save changes.**

In the **"Description & Notes"** section you should see the processed **CSS**
```
[css](-O3fF3GCNgPDgG9m9-4L) <-- will not be this code, was replaced earlier.

bg {
	padding: 30px;
	padding-top: 1px;
	margin: -30px;
	max-width: 800px;
}

etc.
```

Now open the [HERO Example Markdown file](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/HERO-Example.md). At the top of the page find and replace the object id below
```
[css](-O3fF3GCNgPDgG9m9-4L)
```

with your updated object id.

Now copy/paste everything in *HERO-Example.md* to the **"GM Notes"** section of the **"Handout"**  **"Markdown Handout"**. **Delete** or overwrite the text that reads:

```
[md]
[css](-O3fF3GCNgPDgG9m9-4L)
# This Heading should be red.
```

**Save changes.**

In the **"Description & Notes"** section you should see the processed **Markdown** with its content like the image shown below.

> [!TIP]
> Once you are comfortable setting up the Markdown script, you may skip most of Part A. For a new sheet begin with a new handout named "Style Sheet." Paste the contents of *HERO-CSS-Markdown.css* into the **GM Notes section** and save the handout. The script will generate the necessary hash, e.g., **"[css](-O3fF3GCNgPDgG9m9-4L),"** which you may use in Part B.

# Example Handout in Roll20

![Overview of Markdown Available in Roll20](https://github.com/Villain1nGlasses/HeroMarkdown/blob/main/HERO-Example.png)

For reference, the original scripts can be found here:
- [markdown.js](https://gist.github.com/BaldarSilveraxe/0eaaf6fafe8cef89c73fb89c6f37d563)
- [markdownNotesBio.js](https://gist.github.com/BaldarSilveraxe/1002a65dd6e2613c8d38edc1f6005990)
- [markdownDocumentation.js](https://gist.github.com/BaldarSilveraxe/5a1db1db88890ff2de0b94b57557f8c3)


