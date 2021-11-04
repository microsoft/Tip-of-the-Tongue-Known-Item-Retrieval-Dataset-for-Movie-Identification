# Tip of the Tongue Known Item Retrieval Dataset for Movie Identification
This repository contains the dataset from the paper [**Tip of the Tongue Known-Item Retrieval: A Case Study in Movie Identification**](https://dl.acm.org/doi/10.1145/3406522.3446021).

If you use this dataset for your research, please cite the paper as follows:
```
@inproceedings{arguello2021tip,
  title={Tip of the tongue known-item retrieval: A case study in movie identification},
  author={Arguello, Jaime and Ferguson, Adam and Fine, Emery and Mitra, Bhaskar and Zamani, Hamed and Diaz, Fernando},
  booktitle={Proceedings of the 2021 Conference on Human Information Interaction and Retrieval},
  pages={5--14},
  year={2021}
}
```

## Dataset

The [Tip of the Tongue (ToT) dataset](https://github.com/microsoft/Tip-of-the-Tongue-Known-Item-Retrieval-Dataset-for-Movie-Identification/blob/main/ToT.txt) is comprised of 1000 question/answer pairs scraped from the website iRememberThisMovie.com between 2013 and 2018.

These question/answer pairs consist of REQUESTS, in which a user of the website describes a movie they have seen but whose title they have forgotten, and ANSWERS, which consist of different solutions to the request from other users of the website. We also attach Wikipedia/IMDB links for the films.  

We annotate the text of the REQUESTS on the sentence level using a handcrafted set of codes. This set of codes is used to identify trends in the data such as mentions of release/viewing dates, characters or locations remembered from the film, circumstances surrounding the viewing of the film, and others. A complete list of these codes (also available in table 1, 2 and 3 in section 4.3 of our paper) is presented below: 

* Movie: Codes touching on the content of the movie
  * Character: Describes a character
  * Scene: Describes a scene
  * Object: Describes a tangible object in a scene
  * Location type: Describes a scene’s location type
  * Plot summary: Describes the overall plot or premise
  * Release date: Describes timeframe of movie release
  * Visual style: Describes visual style (e.g., black and white, colour, CGI animation, etc.)
  * Language: Describes the language spoken
  * Regional Origin: Describes movie’s region of origin
  * Specific location: Describes a scene’s specific location
  * Quote/dialogue: Describes a quote from the movie
  * Real person: Describes real person associated with movie
  * Camera angle: Describes camera action
  * Singular timeframe: Describes timeframe
  * Multiple timeframe: Describes the passage of time in the movie
  * Fictional person: Describes fictional person associated with movie (directly or indirectly)
  * Actor nationality: Describes nationality or ethnicity associated with actor/actress
  * Target audience: Describes movie’s target audience
  * Compares music: Describes movie’s soundtrack
  * Specific music: Describes specific song in the movie. 
* Context: Codes touching on the context in which the movie was seen
  * Temporal context: Describes when the movie was seen, either in absolute terms (e.g., around 2008) or relative terms (e.g., when I was a kid)
  * Physical medium: References the physical medium associated with watching the movie (e.g., TV, theatre, VHS, etc.)
  * Cross media: Describes exposure to movie through different media (e.g., trailer, DVD cover, poster, etc.)
  * Contextual witness: Describes other people involved in the movie watching experience
  * Physical location: Describes physical location where movie was watched
  * Concurrent events: Describes events relevant to time period when movie was watched
* The following categories do not contain sub-codes
  * Previous Search: Indicates that a previous attempt had been made to find the movie title
  * Social: Indicates that the sentence is primarily a social nicety without content relating to the film
  * Uncertainty: Indicates that the sentence contains language revealing uncertainty on the author’s part
  * Opinion: Indicates that the sentence contains language conveying an opinion or judgement of the movie
  * Emotion: Indicates that the sentence contains language conveying an emotion the movie made the author feel
  * Relative Comparison: Indicates that the sentence contains language describing the movie using relative terms (such as comparisons to other movies, actors, locations, etc.) 

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

## Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content
in this repository under the [Creative Commons Attribution-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-sa/4.0/legalcode),
see the [LICENSE](LICENSE) file.

Privacy information can be found at <https://privacy.microsoft.com/en-us/>.

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
