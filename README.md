<p align=center>
	<img src="https://cdn.statically.io/img/pngimage.net/wp-content/uploads/2018/06/politecnico-milano-logo-png-5.png" alt="Logo Polimi" width="132" />
</p>
<h1 align=center>Master Thesis Template Polimi</h1>
<p align=center>
	LaTeX template for master theses at Politecnico di Milano.
    <br/>
    <br/>
    <a href="https://github.com/marshka/master-thesis-template-polimi/archive/main.zip">
    <img src="https://img.shields.io/badge/download-⬇-blue?style=for-the-badge" alt="Download"/>
    </a>
</p>


<!-- LATEX TIPS -->

## Latex tips

In this section, you can find some tips that can help you in writing texts on LaTeX.

- Put a tilde after a period that is not a full stop.

	> <span style="color: red;"> wrong</span>: Dr. House is a...<br>
	> <span style="color: green;"> correct</span>: Dr.~Dolittle is a...

- Use `\emph{}` only the first time a new term is introduced, and never again.

- Avoid using `\vspace` in figures unless it's absolutely necessary. It usually messes with the space below the caption.

- Avoid defining your own chapters and sections styles. Stick to what the template uses.

- Should you have to cite more than one reference at once, put them together inside the curly brackets.

	> <span style="color: red;"> wrong</span>: \cite{foo}, \cite{bar}<br>
	> <span style="color: green;"> correct</span>: \cite{foo, bar}
	
- Always add a `~` after *et al.* and *vs.* to avoid extra space

	> <span style="color: red;"> wrong</span>: as shown by Doe et al. \cite{foo}, the...<br>
	> <span style="color: green;"> correct</span>:  as shown by Doe et al.~\cite{foo}, the...

- All `\ref` are preceded by a tilde.

	> <span style="color: red;"> wrong</span>: Figure\ref{fig:mae}<br>
	> <span style="color: green;"> correct</span>: Figure~\ref{fig:mae}

- The `\autoref` command provided by the `hyperref` package (included in the template) let you refer to items by automatically adding the inferred prefix. The following examples produce the same output.

	> <span style="color: green;"> correct</span>: As shown in Figure~\ref{fig:mae}<br>
	> <span style="color: green;"> correct</span>: As shown in \autoref{fig:mae}


### Other LaTeX suggestions

- [Labels and Cross-referencing](https://en.wikibooks.org/wiki/LaTeX/Labels_and_Cross-referencing)
- [Bibliography Management](https://en.wikibooks.org/wiki/LaTeX/Bibliography_Management)


<!-- ENGLISH TIPS -->

## English tips

In this section, you can find some tips that can help you not to incur in common mistakes while writing in English.

- Never use a hyphen after an adverb that ends in "ly"

	> <span style="color: red;"> wrong</span>: widely-known paper<br>
	> <span style="color: green;"> correct</span>: widely known paper

- Numbers one to ten should be written as words, greater numbers as digits.

- Write gender-neutral. Avoid using "he/she", use plural or they. If absolutely necessary, use only "she".

- Never use citations in their own as nouns.

	> <span style="color: red;"> wrong</span>: as [22] shows...<br>
	> <span style="color: green;"> correct</span>: as the work of Doe et al. [22] shows...
	
- Avoid using citations in the abstract. The abstract can be used on its own in different context (e.g., on the conference web page) so having a citation number there is pointless.

- Do not forget the period at the end of the captions.

- How to use i.e., e.g., vs., et al., and etc. Know what they mean (id est, exempli gratia, versus, et cetera, et alia). There is always a comma after e.g., and i.e., and they should not be ever used to begin a sentence. Always use a comma before etc.

- Use "or" instead of "/".

- Use a comma before the "and" when the "and" separates two full sentences.

	> <span style="color: red;"> wrong</span>: I like apples and I adore pears.<br>
	> <span style="color: green;"> correct</span>: I like apples, and I adore pears.

- Never put a comma between subject and verb. In lists, use a comma before the last item, even if it starts with "and".

	> <span style="color: red;"> wrong</span>: We will eat meat, vegetables and bread.<br>
	> <span style="color: green;"> correct</span>: We will eat meat, vegetables, and bread.

	> <span style="color: red;"> wrong</span>: I like apples, and pears.<br>
	> <span style="color: green;"> correct</span>: I like apples and pears.
	
- The sounds of the acronym/initialism determines the use of "a" or "an".

- Do not define acronyms if they are not actually used anywhere else in the text.

- Do not use abbreviations such as: don't, isn't, aren't, we're, etc. Instead, use the expanded version: do not, is not, are not, we are, etc.

- Do not be too verbose.

	> <span style="color: orange;">bad</span>: We did this experiment in order to show...<br>
	> <span style="color: green;">better</span>: We did this experiment to show...

- "Section" and "Chapter" are uppercase if they refer to a specific section/chapter, with the relative number. If it is used in a generic fashion, then it is lower case. "In this section"/"In this chapter" senteces are always followed by a comma.

	> <span style="color: green;"> correct</span>: In Section 4, we will show...<br>
	> <span style="color: green;"> correct</span>: In this section, we will show...

- Always make sure that it is absolutely clear what you are referring to when you use "which", "it", "these", etc. The reader will back-track in the sentence and match the pronoun to the closest noun.

- Write in direct form, the passive form confuses the reader because it is not clear who performs the action.

	> <span style="color: orange;">bad</span>: A model that outperforms the state of the art has been built.<br>
	> <span style="color: green;">better</span>: We built a model that outperforms the state of the art.

- Write uniformly and make sure verbal tenses are consistent in periods/sections. It is convenient to stick to the present throughout all the thesis.

- Avoid too many synonyms, as they confuse the reader.

### Other English suggestions 

- [Differences between en (–) and em (—) dashes](https://getitwriteonline.com/articles/en-dashes-em-dashes/)
- [Who vs which vs that](https://www.dailywritingtips.com/when-to-use-that-which-and-who/)
- [How to properly use articles](https://owl.purdue.edu/owl/general_writing/grammar/using_articles.html)


<!-- UTILITIES -->

## Utilities

- [Grammarly](https://app.grammarly.com/): make your writing clear and engaging, eliminating grammar errors.
- [Ludwig Guru](https://ludwig.guru/): helps you understand if your English sentence is correct and makes sense in the academic context.
- [Reverso Context](https://context.reverso.net/): translate sentences in English according to the context relying on verified translation examples.


<!-- LICENSE -->

## License

Distributed under the MIT License. See [`LICENSE`](https://github.com/marshka/master-thesis-template-polimi/blob/main/LICENSE) for more information.


<!-- CONTACT -->

## Contact

Ivan Marisca - [@marshka](https://github.com/marshka)

<a href="https://linkedin.com/in/ivanmarisca">
	<img src="https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555" alt="Linkedin"/>
</a>
