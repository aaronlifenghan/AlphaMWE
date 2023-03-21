# AlphaMWE
AlphaMWE: Construction of Multilingual Parallel Corpora with MWE Annotations

In this work, we present the construction of multilingual parallel corpora with annotation of multiword expressions (MWEs). 
The MWEs include the verbal MWEs (vMWEs) defined by the PARSEME shared task that have a verb as the head of the studied terms. 
The annotated vMWEs are also bilingual and multilingual aligned manually. The languages covered include English, Chinese, Polish, German, and two working langauges Arabic (Standard, Egyptian Arabic, Tunisian Arabic) and Italian (Standard and Dialectal). 
The original English corpus is taken from the PARSEME shared task in 2018. 
We performed machine translation of this source corpus followed by human post editing and annotation of target MWEs, some dialectal langauges being translated mannually from scratch becasue current MT systems donot support them at all. 
Strict quality control was applied for error limitation, i.e., each MT output sentence received first person post editing and annotation plus second person quality checking. 
One of our findings during corpora preparation is that accurate translation of MWEs presents challenges to MT systems. 
To facilitate further MT research, we present a categorisation of the error types encountered by MT systems in performing MWE related translations. 
To acquire a broader view of MT issues, we selected four popular and state-of-the-art MT models for comparisons namely Microsoft Bing Translator, GoogleMT, Baidu Fanyi and DeepL MT. Systran MT was added in the Arabic corpus creation.
Because of the noise removal, translation post editing and MWE annotation by human professionals, 
we believe AlphaMWE is an asset for cross-lingual and multilingual research, such as MT and information extraction. Our multilingual corpora are freely available for research community.

The original English source repo (https://gitlab.com/parseme/parseme_corpus_en)

Five portions of the files from ‘aa to ae’: ‘Ab’ portion contain some ‘mature phrase/content’

License: since we use the English PARSEME dataset, we adopt the same license as the original dataset, i.e. CC-BY-SA 4.0

If you are interested in including your native languages into AlphaMWE (currently involved: English/Chinese/German/Polish/ working:Arabic/Italian/Spanish), please get in touch. We do think this is a good contribution to various native language processing in machine / AI era, in addition to lexical studies. 

# Download multilingual parallel corpora (en, de, zh, pl, ar (working), it (working) | English-German-Chinese-Italian-Arabic)

<img
  src="[/path/to/img.jpg](https://github.com/aaronlifenghan/AlphaMWE/blob/main/logo-alphaMWE-Polish.png)"
  alt="Alt text"
  title="alphaMWE-Polish"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

![alt text](https://github.com/aaronlifenghan/AlphaMWE/blob/main/logo-alphaMWE-Polish.png)


https://drive.google.com/drive/folders/1ikZ9nK1t-MlFjQ_PCvX_YCNooujGdyVO?usp=sharing 
[lifeng.han(AT)manchester.ac.uk] (P.S. AlphaMWE corpus under cleaning stage, please contact this email for sample/part of the data if needed)


# paper & presentation
Welcome to read our paper and the presentations
https://arxiv.org/abs/2011.03783 (paper)
https://youtu.be/KiuF5JdOlLw (oral)
https://es.slideshare.net/mobile/AaronHanLiFeng/alphamwe-construction-of-multilingual-parallel-corpora-with-mwe-annotations-ppt4ws (ppt)


# Citation (initial publication in proceedings):

Lifeng Han, Gareth Jones, and Alan Smeaton. 2020. AlphaMWE: Construction of Multilingual Parallel Corpora with MWE Annotations. Forthcoming in Joint Workshop on Multiword Expressions and Electronic Lexicons (MWE-LEX) @COLING-2020, pages 44--57. Barcelona, Spain (Online). Association for Computational Linguistics.

@inproceedings{han-etal-2020-alphamwe,
    title = "{A}lpha{MWE}: Construction of Multilingual Parallel Corpora with {MWE} Annotations",
    author = "Han, Lifeng  and
      Jones, Gareth  and
      Smeaton, Alan",
    booktitle = "Proceedings of the Joint Workshop on Multiword Expressions and Electronic Lexicons",
    month = dec,
    year = "2020",
    address = "online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.mwe-1.6",
    pages = "44--57",
    abstract = "In this work, we present the construction of multilingual parallel corpora with annotation of multiword expressions (MWEs). MWEs include verbal MWEs (vMWEs) defined in the PARSEME shared task that have a verb as the head of the studied terms. The annotated vMWEs are also bilingually and multilingually aligned manually. The languages covered include English, Chinese, Polish, and German. Our original English corpus is taken from the PARSEME shared task in 2018. We performed machine translation of this source corpus followed by human post editing and annotation of target MWEs. Strict quality control was applied for error limitation, i.e., each MT output sentence received first manual post editing and annotation plus second manual quality rechecking. One of our findings during corpora preparation is that accurate translation of MWEs presents challenges to MT systems. To facilitate further MT research, we present a categorisation of the error types encountered by MT systems in performing MWE related translation. To acquire a broader view of MT issues, we selected four popular state-of-the-art MT models for comparisons namely: Microsoft Bing Translator, GoogleMT, Baidu Fanyi and DeepL MT. Because of the noise removal, translation post editing and MWE annotation by human professionals, we believe our AlphaMWE dataset will be an asset for cross-lingual and multilingual research, such as MT and information extraction. Our multilingual corpora are available as open access at github.com/poethan/AlphaMWE.",
}

# Contributors for each language pair
English-Arabic:
Najet Hadj Mohamed (Tunisian and Standard Arabic), University of Tours, France and  Arabic Natural Language Processing Research Group, University of Sfax, Tunisia

Malak Rassem (Egyptian and Standard Arabic), IMS, University of Stuttgart, Germany

Haifa Alrdahi (coming soon for Saudi Arabic), Uni Manchester


English-Chinese:

Lifeng Han, <lifeng.han(a-t)manchester.ac.uk> Uni Manchester, UK

Pan Pan, <panpan(at)m.scnu.edu.cn> School of Foreign Studies, South China Normal University, Guangzhou, China

Qinyuan Li, <liq3(at)tcd.ie> School of Education, Trinity College Dublin (TCD), Ireland

Ning Jiang, <njiang(at)tcd.ie> School of Linguistic, Speech and Communication Sciences, TCD, Ireland




English-Polish:

Teresa Flera, <t.flera(at)uw.edu.pl> Doctoral School of Humanities (Institute of English Studies), University of
Warsaw, Poland

Sonia Ramotowska, <s.ramotowska(at)uva.nl> Institute for Logic, Language and Computation, University of
Amsterdam, Science Park 107, 1098 XG Amsterdam, The Netherlands

English-German:

Gültekin Cakir, <gueltekin.cakir(at)mu.ie> Innovation Value Institute, Maynooth University, Ireland

Daniela Gierschek, <daniela.gierschek(at)uni.lu> Institute of Luxembourgish Linguistics and Literature, Université du
Luxembourg, 2 Avenue de l'Université, 4365 Esch-sur-Alzette, Luxembourg

Vanessa Smolik, <v.smolik(at)uni-bielefeld.de> Bielefeld University, Universitätsstraße 25, 33615 Bielefeld, Germany


English-French (paused): 
Lea Devingt, lea.delvingt(at)gmail.com 
Killian Mace, killian.mace(at)gmail.com 

English-Italian:
Miss Gabriella Guagliardo, gabriellaguagliardo9(at)gmail.com 
Dr. Paolo Bolzoni, paolo.bolzoni.brown(at)gmail.com 


English-Spanish (paused):
Dr. Dexmont Pena, Email: dexmont.pena2(at)mail.dcu.ie / dexmont(at)gmail.com
Miss. Sheila Lavado Muñoz
Dr. Ricardo Bango coming-on-way news


# Acknowledgment
We are especially grateful to all the colleagues who contributed to the creation of this open source corpus from each language pair. We thank the support and discussion we received from Roise McGagh, Paolo Bolzoni, Lorin Sweeney, Eoin Treacy and Yi Lu on the corpus in various ways.


# news:
AlphaMWE was presented in MWE-LEX@COLING2020 on December 13th. Tereska and Sonia were present together with Lifeng during the Online QA session. We thank the co-chairs/orgnizers, and got good feedback from audiences at MWE WS. 

We thank Prof. Agata Savary, Uni. of Tours to link AlphaMWE to the  list of language resources and tools for Polish - CLIP platform http://clip.ipipan.waw.pl/LRT 

Extended journal paper conditional accepted to Journal of LRE, entitled "Towards a resource for multilingual lexicons: an MT assisted and human-in-the-loop multilingual parallel corpus with multi-word expression annotation".
