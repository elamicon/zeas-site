---
title: Intruduction to the GEAS decipherment tool
shorttitle: GEAS Tool & Fonts
toolbox: 1
weight: 10
---

## Tool Introduction

The [decipherment tool](</tool/>) is a web-based application that allows you to browse inscriptions, access the respective photographs and drawings, modify the corpus, conduct a RegEx based search for sign sequences, find an exhaustive literature list, and copy/paste text in these ancient undeciphered scripts. The tool is available online as libre software and works without installing the fonts on your system.

In the toolbox to the upper right of each corpus page, a number of temporary settings can be modified:

* **writing direction:** For writing systems which vary between sinistroverse and dextroverse inscriptions, the direction can be harmonised. This may be useful for rendering sign sequences and transliterations in scientific articles. Note that the signs themselves are not getting mirrored with this function.

* **Sign forms:** By selecting "normalise per the syllabary", each sign token is replaced by its respective sign type, i.e. its priniciple variant as chosen in the Syllabary > Dynamic Syllabary > Grouping of variants/allographs. This allows for i) raising statistics touching the type/token relation problem (i.e. the Exponent-G-based calculation of the logogram/phonogram ratio) in writing systems with not yet established syllabaries, and ii) to render more phonetic transliterations in writing systems which contain a high ratio of variants with not yet established sound values.

* **Signs with assumed sound value:** By selecting "replace with sound value", the user gets a transliteration of the entire corpus. This allows to read them aloud (a method to guess possible linguistic content for partially deciphered scripts on an acoustic level), facilitates any kind of analysis, and accelerates the reproduction of transliterations and transcriptions in scientific articles. Naturally, the writing direction must be harmonised into LtR first.

* **Remove these signs from the corpus:** This function permits to exclude special signs that disturb the corpus search or the raising of statistics, e.g. the rupture sign    or the place holder . Each writing system has its particular problems, e.g. inconsequent use of word dividers, abundant use of phrase-introducing logograms etc.

In the folders beneath the **character picker**, a number of basic settings can be modified:

* **Sandbox:** A helpful Unicode text field for your browser-based work proceeding.

* **Reliterator:** Inside of the sandbox folder we integrated a reliterator. This is a tool that converts existing transliterations (e.g. the ones of the Proto-Elamite tablets in CDLI) into signs of a given text corpus (e.g. the Linear Elamite signs in the OCLEI). It is a tool for specialists only, and any output should be reviewed manually. To reliterate text, 1) Paste a given transliteration into the sandbox, e.g. "M362M102~eM309~aM362+M317M269" (special signs such as ~ or + are ignored by the reliterator, so text passages from articles and corpora can be used without modification) 2) Check the "Replace text" box below to open the "Word pair per line" window. 3) Paste in a simplified line-by-line signlist. 4) Copy the resulting text into a text document on your computer and choose the respective font, e.g. the GEAS ProtoElamite font.

* **Sound values (current state of decipherment):** The sound value attributions given in this section determine the rendering of transliterations in the "replace with sound value" mode (see section "signs with assumed sound values" above). The actual sound value pre-sets for each writing system represent the current evidence as accepted by the GEAS consortium. Our contributors try their best to provide literature references to the right of each sound value. (If not so, please check the literature lists in the "Intro and Sources" folder. Scholars of the respective fields are invited to contact GEAS for updates and criticism. Authors who use GEAS sound value lists are invited to mention us as a source, and add the date of access.

* **Dynamic Syllabary (Current state of decipherment):** Analyses of undeciphered or partially deciphered writing systems almost always suffer from the prejudices of the respective scholars as to which sign token (single occurrence of a certain graphical shape / Formvariante) is considered to be a variant of a suggested sign type / grapheme type. But in reality, intuition as to which variant belongs to which line in the syllabary/alphabetary almost always turns out to be erroneous as soon as a writing system is finally deciphered. Accordingly, the number of grapheme types can not be established with certainty during the decipherment process. In order to encouter this inevitable *Zirkelschluss*, the GEAS methodology consortium has established the dynamic syllabary method: For every raising of statistics and for every sign sequence search, the syllabary can be modified by manually changing the content of the syllabary entrances. Just copy and paste the signs you suspect to belong to another grapheme type. The character picker as well as the search results will immediately take into account your personalised syllabary. Do not forget to save your syllabaries on your computer. The less entrances your syllabary contains, the longer is the list of results for each sign sequence search you perform. In partially deciphered writing systems, the dynamic syllabary method has lead to many innovative sound value proposal.

* **Dynamic Syllabary (Each sign separately):** This function basically provides a list of each sign token (i.e. form variant) present in the text corpus. It is also needed for quantitative investigations such as Exponent G determination (Fuls 2019:8-12), Markov chain and co-occurrence calculations, Jaccard Index or Levenshtein Distance calculations, etc. (Naturally, decisions taken by the GEAS consortium concerning the composition of the corpus, i.e. the inclusion of doubtful artefacts, creating or not a separate form variant etc. must be accepted by the users. At least, sub-groups can be excluded from the corpus in the "Corpus Search" folder.) 

* **Frequency Analysis:** This folder provides an automatized frequency count of single graphemes as well as sequences based on the Dynamic Syllabary currently established by the user.

* **Corpus Search:** This tool enables simple searches as well as RegEx searches. As a basic decision the user must determine whether he prefers to eliminate certain sub-groups from the corpus in question. The GEAS consortium does its best to define the sub-groups according to the current archaeological and palaeographical knowledge. For instance, if scholars have determined that geographical or chronological parameters may have influence on the graphical shape of the signs, we will adapt the sub-compartimentation according to the scientific literature adduced in the "Intro & sources" chapter. Accoding to the GEAS methodology, every inscription which might be part of a certain writing system is incorporated. With this, the GEAS corpora usually are more extensive than those in printed works. Especially, and in contrast to traditional research, we also include inscriptions that are susceptible to be modern forgeries, and flag them with the 'fake?' superscript and put them into a separate sub-corpus. Instead of criticising us for this philosophy in your articles or in E-mails, just eliminate them from your personalised corpus.

* **Corpus of inscriptions:** The name of the inscription is given in majuscule or minuscule letters depending on the convention in the respective research field. The superscript denominates the sub-group a certain inscription is grouped in. The line of the inscription (as decided by the GEAS consortium in cases of doubt) is given in Roman numbers and pinned at the beginning of each line. (Please contact GEAS if you have evidence for a different writing direction or a different line order.) If a line is interrupted by a physical rupture of the artefact, this is noted by    . Visible traces of illegible signs are noted by , disregarding the conventions of the respective research fields. In order to reproduce sequences in your dextroverse scientific articles, please use the toolbox to change the direction into LtR. For each inscription we offer either a slide with all photographs and drawings available in the literature including archaeological information and references to the excavation reports, or a link leading to friendly online corpora which meet this task on a scientific standard, and which collaborate with GEAS.



## Fonts

To copy text snippets from the GEAS decipherment tool and use them in your documents, you need to install the fonts on your system. You can choose them in all applications, and generate PDF documents containing the glyphs.

Downlad the [GEAS font collection](/tool/fonts/GEAS-Fonts.zip) and get faster in composing your articles and notes.

We've combined the font glyphs with the Liberation font so that you can write text including GEAS glyphs without having to switch to another font. The Liberation fonts as well as the derivative GEAS-Liberation font is available under the SIL Open Font License (OFL). This allows you to use, modify, and distribute the fonts. The license is available on the [SIL website](https://scripts.sil.org/OFL).

It is possible to combine the GEAS font with other fonts such as Verdana, Times New Roman etc., but due to licensing restrictions, we cannot publish font packages of such combinations. Feel free and ask for a specific combined font according to the requirements of your publishing house.



## Citation
The corpora published to this date can be cited as follows:
* Elamicon = Online Corpus of Linear Elamite inscriptions (OCLEI)
* Byblicon = Online Corpus of Byblos Inscriptions (OCBI)
* Deir Alla = Online Corpus of Deir Alla Inscriptions (OCDAI)
* Raeticon = Collection of Sign Variants in Raetic Inscriptions (linked to [TIR](https://tir.univie.ac.at/wiki/Main_Page) with gratitude to Corinna Salomon)
* Leponticon = Collection of Sign Variants in Lepontic, Camunic, and Brembonic Inscriptions (linked to [LexLep](https://lexlep.univie.ac.at/wiki/Main_Page) with gratitude to David Stifter)
* Etruricon = Collection of Sign Variants in Etruscan Inscriptions (no text corpus published)
* Runicon = Collection of Linguistic Sign Variants in the Elder Futhark (no text corpus published)