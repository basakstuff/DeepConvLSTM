# Abstract

Human activity recognition aims to classify a person's actions by a series of measurements captured by sensors. As a result, it bases the development of many potential applications, especially in health and sports fields. In the last 25 years, a growing field of research has been formed in the field of recognition of human activities. The human activity recognition problem is beginning to adopt deep learning instead of deep-rooted analysis techniques based on handmade feature extraction and classification techniques.

In this thesis, meticulously researched the hybrid model of convoluted and recurrent architectures in the OPPORTUNITY dataset, which includes motion data captured by wearable sensors. How to train recurrent approaches with these models, the effect of hyper-parameters used on model performance, and the success of hybrid models in recognizing human activity are under the lens. This thesis presents the performance, advantages, and limitations of hybrid models. This study not only compares hybrid models, but also highlights the significant advantages of models.

Based on these assessments, the best deep learning model and parameter selection strategies were found to separate movements of the same type. These strategies include convolutional and recurrent neural networks for trait learning and classification. Significant differences have been obtained between alternatives for different types of motion, indicating the need for feature extraction and classification modules to be adapted to each type of motion. In the OPPORTUNITY dataset, the best results reported a 91.8% and 88% F-score, respectively, for non-competitive movements and postures.

## Results of Task A with Null Class
|     Test Name    |     F1-score    |     Time (s, ms)    |     F1-score/Time    |
|------------------|-----------------|---------------------|----------------------|
|     a            |     0,895       |     28,66           |     0,0312           |
|     b            |     0,858       |     28,66           |     0,0299           |
|     c            |     0,860       |     28,66           |     0,0300           |
|     d            |     0,848       |     25,12           |     0,0338           |
|     e            |     0,866       |     25,12           |     0,0345           |
|     f            |     0,859       |     39,92           |     0,0215           |
|     g            |     0,866       |     50,12           |     0,0173           |
|     h            |     0,862       |     167,40          |     0,0051           |
|     ı            |     0,863       |     276,1           |     0,0031           |
|     j            |     0,864       |     28,66           |     0,0301           |
|     k            |     0,866       |     25,12           |     0,0345           |

## Results of Task A without Null Class
|     Test Name    |     F1-score    |     Time (s, ms)    |     F1-score/Time    |
|------------------|-----------------|---------------------|----------------------|
|     a            |     0,930       |     23,66           |     0,0393           |
|     b            |     0,918       |     23,66           |     0,0388           |
|     c            |     0,909       |     23,66           |     0,0384           |
|     d            |     0,909       |     21,12           |     0,0430           |
|     e            |     0,912       |     21,12           |     0,0432           |
|     f            |     0,912       |     32,92           |     0,0277           |
|     g            |     0,918       |     42,12           |     0,0218           |
|     h            |     0,908       |     144,41          |     0,0063           |
|     ı            |     0,914       |     31,18           |     0,0293           |
|     j            |     0,905       |     23,66           |     0,0383           |
|     k            |     0,916       |     21,12           |     0,0434           |

## Results of Task B with Null Class
|     Test Name    |     F1-score    |     Time (s, ms)    |     F1-score/Time    |
|------------------|-----------------|---------------------|----------------------|
|     a            |     0,915       |     57,13           |     0,016            |
|     b            |     0,880       |     57,13           |     0,015            |
|     k            |     0,861       |     48,23           |     0,018            |

## Results of Task B without Null Class
|     Test Name    |     F1-score    |     Time (s, ms)    |     F1-score/Time    |
|------------------|-----------------|---------------------|----------------------|
|     a            |     0,866       |     18,14           |     0,048            |
|     b            |     0,671       |     18,14           |     0,037            |
|     k            |     0,649       |     15,23           |     0,043            |
