<p align="center" style="font-size:30px">
<a href="https://mwray.github.io/">Michael Wray</a> and <a href="https://dimadamen.github.io/">Dima Damen</a>
</p>

![Verb Overlaps](intro_fig.jpg)

## Abstract

This work introduces verb-only representations for both recognition and retrieval of visual actions, in video. Current methods neglect legitimate semantic ambiguities between verbs, instead choosing unambiguous subsets of verbs along with objects to disambiguate the actions. We instead propose multiple verb-only labels, which we learn through hard or soft assignment as a regression. This enables learning a much larger vocabulary of verbs, including contextual overlaps of these verbs.

We collect multi-verb annotations for three action video datasets and evaluate the verb-only labelling represen-tations for action recognition and cross-modal retrieval (video-to-text and text-to-video).We demonstrate that multi-label verb-only representations outperform conventional sin-gle verb labels. We also explore other benefits of a multi-verb representation includingcross-dataset retrieval and verb type (manner and result verb types) retrieval.


## Video


<iframe align="center" width="640" height="360" src="https://www.youtube.com/embed/E1CRoOG2eE8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## Paper

[PDF](MVOL.pdf)

[ArXiv](https://arxiv.org/abs/1907.11117)

## Bibtex

```markdown
@InProceedings{wray2019learning,
    author    = {Wray, Michael and Damen, Dima},
    title     = {Learning Visual Actions Using Multiple Verb-Only Labels},
    booktitle = {Proceedings of the IEEE International Conference on Computer Vision (ICCV)},
    year      = {2019}
}
```

## Acknowledgements
This research is supported by [EPSRC LOCATE (EP/N033779/1)](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/N033779/1) and EPSRC Doctoral Training Partnerships (DTP). 
