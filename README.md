# Awesome-Table-Recognition
A curated list of resources dedicated to table recognition
## 1. Papers

* *CODE means official code and CODE means not official code

*Conf.* | *Date* | *Title* | *Highlight* | *code* |
:---: | :---: |:--- | :---: | :---: |
arXiv | 2021/12/2 |[Flexible Table Recognition and Semantic Interpretation System](https://arxiv.org/pdf/2105.11879v2.pdf) | Others | [*CODE](https://github.com/mnamysl/table-interpretation)<br>`STARS:0`  |
arXiv | 2021/11/18 |[PubTables-1M: Towards comprehensive table extraction from unstructured documents](https://arxiv.org/pdf/2110.00061v3.pdf) | Dataset | [*CODE](https://github.com/microsoft/table-transformer)<br>`STARS:94` |
arXiv | 2021/5/23 |[Multi-Type-TD-TSR -- Extracting Tables from Document Images using a Multi-stage Pipeline for Table Detection and Table Structure Recognition: from OCR to Structured Table Representations](https://arxiv.org/pdf/2105.11021.pdf) | Others | [**CODE](https://github.com/Psarpei/Multi-Type-TD-TSR)<br>`STARS:95`  |
ICCV | 2021 |[Parsing Table Structures in the Wild](https://openaccess.thecvf.com/content/ICCV2021/papers/Long_Parsing_Table_Structures_in_the_Wild_ICCV_2021_paper.pdf) | Dectction | No |
ICCV | 2021 |[TGRNet: A Table Graph Reconstruction Network for Table Structure Recognition](https://openaccess.thecvf.com/content/ICCV2021/papers/Xue_TGRNet_A_Table_Graph_Reconstruction_Network_for_Table_Structure_Recognition_ICCV_2021_paper.pdf) | GNN | [*CODE](https://github.com/xuewenyuan/TGRNet)<br>`STARS:40` |
ICDAR Competition | 2021 |[ICDAR 2021 Competition on Scientific Literature Parsing](https://arxiv.org/pdf/2106.14616v1.pdf) | Dataset | [*CODE](https://github.com/ibm-aur-nlp/PubLayNet)<br>`STARS:571` |
ICDAR Competition | 2021 |[PingAn-VCGroup's Solution for ICDAR 2021 Competition on Scientific Literature Parsing Task B: Table Recognition to HTML](https://arxiv.org/pdf/2105.01848v1.pdf) | Sequence | [*CODE](https://github.com/JiaquanYe/TableMASTER-mmocr)<br>`STARS:190` |
ICDAR Competition | 2021 |[LGPMA: Complicated Table Structure Recognition with Local and Global Pyramid Mask Alignment](https://arxiv.org/pdf/2105.06224.pdf) | Others | [*CODE](https://github.com/hikopensource/DAVAR-Lab-OCR)<br>`STARS:306` |
WACV | 2021 |[Global table extractor (gte): A framework for joint table identification and cell structure recognition using visual context](https://openaccess.thecvf.com/content/WACV2021/papers/Zheng_Global_Table_Extractor_GTE_A_Framework_for_Joint_Table_Identification_WACV_2021_paper.pdf) | Others | No |
CVPR Workshop | 2020 |[CascadeTabNet: An approach for end to end table detection and structure recognition from image-based documents](https://arxiv.org/pdf/2004.12629v2.pdf) | Others | [*CODE](https://github.com/DevashishPrasad/CascadeTabNet)<br>`STARS:1018` |
ECCV | 2020 |[Image-based table recognition: data, model, and evaluation](https://arxiv.org/pdf/1911.10683v5.pdf) | Dataset | [*CODE](https://github.com/ibm-aur-nlp/PubTabNet)<br>`STARS:229` |
ECCV | 2020 |[Table structure recognition using top-down and bottom-up cues](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123730069.pdf) | Others | [*CODE](https://github.com/sachinraja13/TabStructNet)<br>`STARS:96` |
LREC | 2020 |[TableBank: A Benchmark Dataset for Table Detection and Recognition](https://arxiv.org/abs/1903.01949) | Dataset | [*CODE](https://github.com/doc-analysis/TableBank)<br>`STARS:759` |
arXiv | 2019/8/28 |[Complicated table structure recognition](https://arxiv.org/pdf/1908.04729.pdf) | Others | [*CODE](https://github.com/Academic-Hammer/SciTSR)<br>`STARS:232`  |
ICDAR | 2019 |[Rethinking Table Recognition using Graph Neural Networks](https://arxiv.org/pdf/1905.13391v2.pdf) | GNN | [*CODE](https://github.com/shahrukhqasim/TIES-2.0)<br>`STARS:238` |
ICDAR | 2019 |[Tablenet: Deep learning model for end-to-end table detection and tabular data extraction from scanned document images](https://arxiv.org/pdf/2001.01469.pdf) | Others | No |
ICDAR | 2017 |[Deepdesrt: Deep learning for detection and structure recognition of tables in document images](https://www.dfki.de/fileadmin/user_upload/import/9672_PID4966073.pdf) | Others | No |

## 2. Datasets

|Dataset|Description|Examples|dataset link|
|----|----|----|----|
|TableBank|**English** TableBank is a new image-based table detection and recognition dataset built with novel weak supervision from Word and Latex documents on the internet, contains 417K high-quality labeled tables|[TableBank](.)|[TableBank](https://github.com/doc-analysis/TableBank)|
|SciTSR|**English** SciTSR is a large-scale table structure recognition dataset, which contains 15,000 tables in PDF format and their corresponding structure labels obtained from LaTeX source files.|[SciTSR](.)|[SciTSR](https://github.com/Academic-Hammer/SciTSR)|
|PubTabNet|**English** PubTabNet is a large dataset for image-based table recognition, containing 568k+ images of tabular data annotated with the corresponding HTML representation of the tables.|[PubTabNet](.)|[PubTabNet](https://github.com/ibm-aur-nlp/PubTabNet)|
|FinTabNet|**English** This dataset contains complex tables from the annual reports of S&P 500 companies with detailed table structure annotations to help train and test structure recognition.|[FinTabNet](.)|[FinTabNet](https://developer.ibm.com/exchanges/data/all/fintabnet/)|
|PubTables-1M|**English** A large, detailed, high-quality dataset for training and evaluating a wide variety of models for the tasks of table detection, table structure recognition, and functional analysis.|[PubTables-1M](.)|[PubTables-1M](https://github.com/microsoft/table-transformer)|
|WTW|**English** WTW-Dataset is the first wild table dataset for table detection and table structure recongnition tasks, which is constructed from photoing, scanning and web pages, covers 7 challenging cases like: (1)Inclined tables, (2) Curved tables, (3) Occluded tables or blurredtables (4) Extreme aspect ratio tables (5) Overlaid tables, (6) Multi-color tables and (7) Irregular tables in table structure recognition.|[WTW](.)|[WTW](https://github.com/wangwen-whu/wtw-dataset)|
|TNCR|**English** a new table dataset with varying image quality collected from open access websites.TNCR contains 9428 labeled tables with approximately 6621 images.their classification into 5 different classes(Full Lined,Merged Cells,No lines,Partial Lined,Partial Lined Merged Cells).|[TNCR](.)|[TNCR](https://github.com/abdoelsayed2016/TNCR_Dataset)|
|TAL_OCR_TABLE|**Chinese** TAL_OCR_TABLE dataset come from TAL Form Recognition Technology Challenge.The data of comes from the real homework of students in the education scene and the scene of the test paper. It contain 16k train image and 4k test image|[TAL_OCR_TABLE](.)|[TAL_OCR_TABLE](https://www.heywhale.com/home/competition/606d6fff0e04ac0017c3bf7f/content/1)|
