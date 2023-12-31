## Computing Austen’s differences
### ENGL35 2023 Assignment 5
### by Rachel Sagner Buurma and Rich Wicentowski
#### Originally written to pair with CS21 [Lab 8: DH/searching](https://www.cs.swarthmore.edu/courses/CS21Labs/f17/labs/lab08.html) and [Lab 9: DH/sorting](https://www.cs.swarthmore.edu/courses/CS21Labs/f17/labs/lab09.html)

Summary: *This assignment will ask: how specifically are Jane Austen's novels (written and published between approximately 1790 and 1818) different from those of her contemporaries? How different are they from the other eighteenth-century and early-nineteenth-century novels we might read in a class on the history of the novel in English?*

## Background

In ENGL035: The Rise of the Novel we have been studying the history of the novel in English. We’re interested in the history of the novel for many reasons. For a long time, people have written and read novels for entertainment and for instruction; to learn about people unlike themselves, and to see representations of people like themselves circulate in print; to learn about the world, and to learn new ways of thinking and feeling. In this class, we have been especially interested in how the novel developed both as a reflection of social and psychological life and a model for it. The novel is designed to represent the current state of what it is like to think, feel, and live as an everyday and historically unremarkable person, but it is also a form that opens up new possibilities for how a novel reader might think, feel, and live as an everyday person. Depending on who you were or are, the novel might help you learn how you might fall in love, grow up, be (or become, or refuse to become) a woman (or a man), grow old, or mourn the loss of a child. It might also, of course, depending on who you were, fail to acknowledge you as a person worthy of being addressed by the novel. Perhaps most importantly, the novel can help you understand (or believe) that you are (or are potentially) a valuable, interesting, unique person - even in the face of overwhelming evidence that you are actually a very ordinary and replaceable person.

As we have discussed in class, any attempt to survey any literary genre across three centuries is sure to run into difficulties, and the novel poses particular challenges. When we read novels for the purpose of discussing them in a classroom, we read them in part as we read when we read for pleasure - from cover to cover, following the plot, identifying (or not) with characters, enjoying the scenery. But we also read them more discontinuously and intensively - skipping around to search for evidence of a claim or dwelling for twenty minutes on a single word (as on that memorable day in October when we spent that amount of time discussing the final word of *Evelina*, which is, as you will recall, “Evelina”). This kind of reading takes a long time, novels themselves are long (sometimes VERY long), and the semester and our attention spans are short. Therefore in this class we have only been able to read ten novels published over the span of 242 years (1719-1961). During this timespan, hundreds of thousands of novels were published, so naturally we needed to be very selective.

But how do we choose? We choose novels for a syllabus like ours - in which we can only read ten novels - not because they are "average" nor because they are wholly "exceptional," but because they are "exemplary." The are in some (controversial) sense the "best," yes, but they are the best "of their kind." They must somehow represent larger groups of novels, so that we can claim to be learning something about "the novel" or "the Anglophone novel" in the class, not just some things about ten random novels.  Yet our choices must also be be worth reading in themselves; we want them to be compelling and important in their own rights. We implicitly claim, therefore, that each novel on our syllabus is both representative *and* distinctive.

## Comparison: How?

Accordingly, this assignment will ask: how specifically are Austen's novels (which she wrote and published between approximately 1790 and 1818) different from those of her contemporaries? How different are they from the other eighteenth-century and early-nineteenth-century novels we might read in a class like this one?

There are a few ways we have gone about answering this question over the course of the semester, and each has its particular strengths and weaknesses. One way is to draw on the aggregated conclusions many critics have come to in their own readings of novels. For critic Ian Watt, for example, Austen innovates by joining different forms of realism that were previously separate, allowing one novel to be both psychologically realist and yet also true to external life. For critics like D.A. Miller and Frances Ferguson, Austen's narrative style - her impersonal narrator and use of free indirect discourse - is both new and trendsetting. Though it is clear that Austen draws on existing narrative conventions, critics like Miller and Ferguson see her fiction as significantly different from the novels that came before them, while also seeing them exert a strong influence on the novels that came after them. Another approach we have taken is to select a single less-canonical work - in our case, *The Woman of Colour* - and read it in order to compare it to Austen's *Northanger Abbey* on a one-to-one basis.

But what if we want to be able to compare larger groups of novels, more than we can easily eyeball? And what if we want to compare the contents of these novels, rather than their titles or publication information (which might be easier to do just bey reading)? To do this, we can try to examine a smaller number of characteristics (or "features") of each novel across a larger group of novels. In this assignment, we will identify a feature that can be easily extracted from each text or group of texts, and then decide how we might go about representing that feature in a way that lets us easily compare texts to one another. Clearly, the kinds of features or textual characteristics we can extract (or generate) from texts will severely limit the kinds of questions we can ask. On the other hand, the very act of having to isolate a machine-identifiable characteristic or group of characteristics in a big set of novels may very well help us think entirely differently about texts and interpretation.

It is important to understand that when we create any representation of a text or group of texts – whether the fairly simple one in this assignment or much more sophisticated models - we are deliberately choosing to create a VERY reductive representation of each text so that we can easily manipulate and compare the representations of a larger number of novels. What we are NOT doing is pretending that this feature in any way stands in for a human reading of the text, or offers any kind of full representation of the text. Rather, are using feature extraction to look closely at and compare one very specific aspect of the text, an aspect that we cannot easily see when we read. Another way to think about what we are doing is not “reduction” of each text to a given feature or set of features, but “transformation” – the creation of a new text that tell us something ABOUT the original texts from which we began. (You may notice, by the way, that this tension between imagining a representation as a reduction as opposed to imagining a representation as a transformation is also a current running through some of the literary-critical treatments of novelistic realism we have been examining.)

### More Distinctive Words

 In this particular assignment, we are going to compare different texts and collections of texts in order to find out what their most distinctive words are. These distinctive words will - for the purposes of this assignment - act as a very reductive representation of the texts from which they are drawn. Because this is such a reductive representation of a text, we won’t be able to answer most questions a literary critic would have about single text. However, reducing the scope of our evidence in this way WILL allow us to answer a few questions about a much larger group of texts.

We will be able to compare a novel we *have* read - Jane Austen's Northanger Abbey (composed 1790, published 1818) - with a series of other groups of novels. First we will compare *Northanger Abbey* with the complete works of the uncanonical (and, in her own time, arguably old-fashioned) novelist Mary Brunton, with the works of generation-earlier novelist Frances Burney, and with Austen's own complete works. We will then move on to compare both *Northanger Abbey* and Austen’s complete works with two larger corpora: a corpus that has been selected to represent "canonical" novels and one that has been selected to represent “the archive.” (More on the meaning and difference between "canon" and "archive" below.)

Comparing a text with a corpus, or a corpus with a corpus, is tricky. We could simply calculate raw frequencies: how many times does the word “shrubbery” appear in Jane Austen’s novels, and how many times in Mary Brunton’s? But of course we have six Austen novels and only two Brunton novels, so this will be unfair. To even things out, we should *divide the count of every word by the total number of words in the corpus*. Then, at least, we can compare similar numbers - the proportion of words in Austen's novels that are "shrubbery" with the proportion in Brunton's.

Let's take an example. What proportion of Austen’s corpus is made up of the word “exceedingly,” and what proportion of Brunton’s is made up of the word “exceedingly”? It turns out that 'everything' occurs just 2 times out of a total of 340,352 words in Brunton, and 101 out of 752,331 words in Austen.

Even eyeballing this probably tells us that "everything" is much more prevalent in Austen than in Brunton, but let's figure out what precise proportion of "everything" is in each author's collected works by dividing the number of occurrances of "everything" by the total number of words in the collected works. So for the word 'everything' in Brunton, dividing 2 by 340,352 (and then multiplying by 100 to make percentages) gives us "everything" as ~ 0.0006% of all words, whereas for "everything" in Austen, dividing 101 by 752,331 and then multiplying by 100 will give us "everything" as ~ 0.0134% of all words.

The ratio (310/752331) / (2/340411) = 0.00041205267	/ 0.00000587525 = 23.3 tells us that ‘everything’ is about 23 times more likely to appear in Austen than in Brunton. If we calculate this ratio for every word in both documents, we can find the set of words for each text or group of texts that are, in a sense, the most important words in that text - if, that is, we can judge importance by relative frequency of use.

This is the measure we are using in the program the CS21 students have written for us. However, there are some limits to what it can tell us, and a number of other methods for comparing texts and corpora exist. In the "Further Reading" and "Extra Credit" sections you will find ideas and examples of how some people have gone about accounting for these shortcomings. The bottom line, however, is that we may be able to build a better way of determining which words to use as a representation or stand-in for our texts, but they will always remain a very specific and partial representation of one particular aspect of the texts. This is a *good* thing.


### Corpus: to what can we compare Austen?

Comparing Austen's novels and complete works to "everything else" sounds great in theory; how will it work in practice? First, we need to determine what groups of novels we might want to compare to Austen's and whether they exist in machine-readable form.  As we learned in Assignment 4, even if we have a digital facsimile of a novel, using OCR on it won't necessarily give us a machine-readable text that is good enough for a purpose like this; almost all computational text analysis work requires that we pre-process or "clean" existing machine-readable texts before we can use them. For this assignment, we will use the texts and corpora described below. All of these corpora (except one) are composed of texts that were either transcribed by a person or people, so they are very accurate. In this case, we have removed metadata and other ancillary text that we don't want to see in our results. The programs we use will also include functions that remove or ignore some words; our program, for example, ignores words that appear < 5 times in both texts or corpora that we are comparing.

We are grateful that Yumi D. Shiroma contributed her expertise to the creation and assembly of these corpora.

#### AUSTEN
Our Jane Austen corpus contains the texts of *Emma*, *Lady Susan*, *Mansfield Park*, *Northanger Abbey*, *Persuasion*, *Pride and Prejudice*, and *Sense and Sensibility*.

#### BRUNTON
Our Maria Brunton corpus contains the novels *Discipline* and *Self-Control*.

#### BURNEY
Our Burney corpus contains *Cecelia*, *Evelina*, and *The Wanderer*.

#### CANON
The “canon” collection contains 44 works of eighteenth- and early-nineteenth-century works of fiction in English that are taught frequently in university-level classes on the novel and fiction; we drew them from a survey of 40 recent syllabi for eighteenth-century and history of the novel classs [LINK]. They are *Pamela* (1740), *Tristram Shandy* (1749), *Evelina* (1778), *Robinson Crusoe* (1719), *Tom Jones* (1749), *Joseph Andrews* (1742), *Oroonoko, or The Royal Slave* (1688), *Moll Flanders* (1722), *Northanger Abbey* (1817), *Shamela* (1741), *Clarissa* (1748), *The Castle of Otranto* (1764), *Emma* (1815), *Roxana* (1724), *The Female Quixote* (1752), *The Monk* (1796), *Fantomina: or, Love in a Maze* (1724), *The Man of Feeling* (1771), *A Sicilian Romance* (1790), *A Sentimental Journey* (1768), *Humphry Clinker* (1771), *Gulliver’s Travels* (1726), *Candide* (1759), *Castle Rackrent* (1800),
*Mansfield Park* (1814), *The Fair Jilt* (1688), *Pilgrim's Progress* (1678), *The Mysteries of Udolpho* (1794), *Pride and Prejudice* (1813), *Les Liaisons Dangereuses* (1782), *The Princesse de Clèves* (1678), *Sense and Sensibility* (1811), *A Simple Story* (1791), *The Romance of the Forest* (1791), *Anti-Pamela* (1741), *Don Quixote* (1615), *Jane Eyre* (1847), *The History of Pompey the Little* (1750), *Belinda* (1801), *Roderick Random* (1748), *The History of Rasselas* (1759), *The Italian* (1797), *Waverley* (1814). (*Love in Excess* (1719) is on this list but not included because of the lack of a readily available machine-readable text.) They come primarily from the Project Gutenberg archive; see the note in the repository for more information.

#### Archive
We have two corpora that stand in for the “archive” or - to use the words of Margaret Cohen - “the great unread” (“Narratology in the Archive of Literature,” 61) - all of those books that were published and (possibly) read at one time but which have not been read much since.

Our first “archive” corpus is CHAWTON,  a collection of 75 novels drawn from the [Chawton House Library’s Novels Online project](https://chawtonhouse.org/the-library/library-collections/womens-writing-in-english/novels-online/). CHAWTON contains little-known novels written (primarily) by women and published during the eighteenth and early nineteenth centuries.

A alternate model for “archive” is [SINGERMENDENHALL](https://github.com/earlynovels/digital-collection). This corpus contains seventy-five rare works of eighteenth-century fiction drawn from the Singer-Mendenhall collection at the University of Pennsylvania. The SINGERMENDENHALL corpus is different from our others because it was created via OCR of scanned novels; we then processed the resulting (very messy) text by removing "non-words" (any words that appear < 200 times in the Google ngram corpus) and uppercase words. The corpus was selected and curated by Dr. Alice McGrath and Dr. Lindsay Van Tine.

Are either of these corpora a perfect representation of the "real" archive of all the late-eighteenth and early-nineteenth-century fiction that was ever published? Nope! Both CHAWTON and SINGERMENDENHALL are assembled not of "average" early novels, but of rare and outlying texts. But there's really no perfect representation of the "archive", and there is a lot we can learn from this one.

### How to run the CS21 "more distinctive words" program

We will be running this program - written in the programming language Python - from the command line via your Terminal (on Mac) or PowerShell (on PC). The command line is simply a tool for viewing and interacting with the files and programs on your computer. In order to understand the basics of running Python programs if you have not worked with Python before, you will complete a tutorial.

### Before beginning: installing Python with the Python Launcher

To run this program, you will need Python 3. To install Python 3,[go here](https://www.python.org/downloads/)and follow the prompts to install it on your hard drive in your Applications folder (or wherever you prefer). Once installed, take a look in your new Python folder; it should include a few files and applications, including the Python Launcher. Once you see this, you can move on to the next step, below.

### Running the "more distinctive words" program

Before we run the program, let's let's take a quick look at it.

1. Download the our corpus and code, [Rise18-Assignment8-master corpus and and code](https://github.com/rbuurma/Rise18-Assignment8), by clicking on the green CODE button, selecting the zip file download, and then expanding the zip file by clicking on it once you've downloaded it. Save it somewhere that makes sense to you.

2. If you haven't already installed the [Visual Studio Code editor](https://code.visualstudio.com/), do so now. 

3. In the "bin" folder within Rise18=Assignment8-master you will see several versions of the code, the textinfo.py version version written by Professor Wicentowski, and other versions written by various students from Professor Wicentowski's Fall 2017 CS21 -  Danielle Rossetti textinfo_dr.py,  Alex Galarraga textinfo_ag.py, Jason Wong textinfo_jw.py, and Rise 2017's own Hannah Kloetzer textinfo_hk.py.

Open textinfo.py with the Visual Studio Code editor so that you can VIEW (not yet run) the code and take at least a brief look. This step is just to give you the sense of how to open the file and what it looks like.

Each version of the code will do more or less the same thing. There are, however, some slight differences. *Therefore we highly recommend running textinfo.py as well as one or more of the other versions; watch for the slightly different outputs, and prepare to consider what has caused the differences.*

4. At long last, let's run the code.  To do that, right-click on textinfo.py (or whichever version you want to run) and select the Python Launcher program from the (probably long) list of options. Selecting it will open your Terminal or PowerShell window. (You may recieve a prompt asking you to allow Python Launch to access your files - allow it.) The program will run, prompting you to choose two corpora to compare. Try comparing AUSTEN and BRUNTON by typing in the corresponding integers just as a start.

5. You will see a few outputs. First, there will be a list of most frequent words in each corpus with a number alongside telling you how many times that word occurs. These can be potentially interesting, but will not be our primary focus. Next comes the two list of "most distinctive" word in each corpus; each word is accompanied by a number that tells you how many times the word appears in (for example) Austen than in BRUNTON.

You will then also be able to select any word from that list and ask the program to display all instances of it in the context of the surrounding words from the text, which will give you a sense of the word's uses. (This is called Keyword in Context, or KWiC.)

### Interpret

1. Once you have the program running, try these comparisons first: The AUSTEN corpus to BRUNTON, CHAWTON, and CANON corpora.

You will see at least one fairly striking result in this comparison. Can you describe it to yourself? Think back to the Gallagher "Rise of Fictionality" article; how does this result speak to Gallagher's argument? Think also about Watt on formal realism and Barthes on the reality effect; how might this result help us interpret Austen vs these corpora in light of Watt or Barthes?

2. Next, map out come other comparisons - between Austen's novels and other groups of novels, and between individual Austen novels and other individual novels - that you would like to make in order to answer some of the questions below.

Note: We cannot using these results answer the question of whether Austen is different from her contemporaries, because we have built difference into our output: our friends in CS21 have constructed a program that will find difference no matter what. That is, what “more distinctive” word comparisons *can’t* do is prove that Austen is generally divergent or distinctive from her contemporaries. But given difference, we can use the lists of "most distinctive" words to look at the *shape difference takes* once we have built in the presence of difference.


### Write

After making a series of comparisons, write 4-5 paragraphs describing your results and speculating on your interpretation of them.

1. The AUSTEN corpus in comparison with BRUNTON, CHAWTON, and CANON corpora in light of Catherine Gallagher's argument in "The Rise of Fictionality"

2. Some other interesting result from a comparison that you have made in the context of another one of our critical or theoretical readings.

3. Some consideration of what it means to make comparisons between texts and corpora in this way along side the way any one of our critics has made - or implied - comparisons between texts or corpora/groups of texts.

4. Add it to your Text Exercise doc.

### Extra credit 1 (for people who have not taken CS21)

Open the script in Atom or a similar code-editing tool and modify the script to try one or both of the following:

Display 20 words instead of 10 and re-run the script.

The number of words that must appear in both corpora for the word to appear at all in the results output is currently 5; set that number to a different number and re-run the script.

### Extra credit 2 (for anyone and everyone)

In his book Nabokov’s *Favorite Word is Mauve*, data journalist Ben Blatt notes that Jane Austen’s “use of words like "very" is off the charts,” and gives an example:

![Blatt quote](https://raw.githubusercontent.com/rbuurma/rise-2018/master/Images/BlattAustenQuote.jpg))

Based on only what you see here, what is potentially wrong with Blatt’s example? Might what is wrong with this example be a symptom of what else might go wrong with the computational text analysis of literature when a literary critic is not involved? Explain the basic literary critical concept(s) Blatt fails to take into account here.


# License

This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/ or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA.

Rachel Sagner Buurma | rbuurma1 at swarthmore dot edu| rachelsagnerbuurma.org
Richard Wicentowski | rwicent1 at swarthmore dot edu |
