# CE888-7-SP-Assignment-2
This repository contains code for my module CE888-7 SP  Data Science and Decision making.


In the codeyou will find "#results here for {task}" where you can find result for perticular task.


In this program i have taken three programs
The code of these programs are emotion, hate and emoji respectively

first in emotion the mapping file is downloaded from mapping.txt
1) all maping is assigned to labels 

2) using !wget  test_text.txt file is loaded in etext
then etext is loaded in gold_2
then gold 2 is preprocessed and tokenize
gold 2 is integer so it is converted into string.
then gold2 is loaded in pred
means "test_text.txt" file is converted into "pred"

3) now we load "test_label.txt" file in gold
now i have calculated f1 score and macro average of gold and pred as mentioned in tweeteval
All the metric used are same.
similarly this process is done for all three datasets emotion, hate , emoji

Reference paper

@inproceedings{barbieri2020tweeteval,
  title={{TweetEval:Unified Benchmark and Comparative Evaluation for Tweet Classification}},
  author={Barbieri, Francesco and Camacho-Collados, Jose and Espinosa-Anke, Luis and Neves, Leonardo},
  booktitle={Proceedings of Findings of EMNLP},
  year={2020}
}

citation for dataset

emotion recognition

@inproceedings{mohammad2018semeval,
  title={Semeval-2018 task 1: Affect in tweets},
  author={Mohammad, Saif and Bravo-Marquez, Felipe and Salameh, Mohammad and Kiritchenko, Svetlana},
  booktitle={Proceedings of the 12th international workshop on semantic evaluation},
  pages={1--17},
  year={2018}
}


emoji Prediction

@inproceedings{barbieri2018semeval,
  title={Semeval 2018 task 2: Multilingual emoji prediction},
  author={Barbieri, Francesco and Camacho-Collados, Jose and Ronzano, Francesco and Espinosa-Anke, Luis and 
    Ballesteros, Miguel and Basile, Valerio and Patti, Viviana and Saggion, Horacio},
  booktitle={Proceedings of The 12th International Workshop on Semantic Evaluation},
  pages={24--33},
  year={2018}
}


Hate speech

@inproceedings{basile-etal-2019-semeval,
    title = "{S}em{E}val-2019 Task 5: Multilingual Detection of Hate Speech Against Immigrants and Women in {T}witter",
    author = "Basile, Valerio  and Bosco, Cristina  and Fersini, Elisabetta  and Nozza, Debora and Patti, Viviana and
      Rangel Pardo, Francisco Manuel  and Rosso, Paolo  and Sanguinetti, Manuela",
    booktitle = "Proceedings of the 13th International Workshop on Semantic Evaluation",
    year = "2019",
    address = "Minneapolis, Minnesota, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/S19-2007",
    doi = "10.18653/v1/S19-2007",
    pages = "54--63"
}

