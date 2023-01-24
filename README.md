# MNAD - DASA 2021

MNAD, a large-scale news articles dataset, based on four of the major moroccan news websites, containing more than 418k news articles corresponding to 19 different categories, we collected: the title, body and label of each article.
The data has been cleaned, preprocessed, and saved into four .csv files for easy use by ML models. 

You can download the data [here](https://www.kaggle.com/jmourad100/mnad-moroccan-news-articles-dataset). The use of the data set is restricted to academic research purpose only.

# Citation

Please cite our paper if you find the data helpful, thanks!

```
@InProceedings{MNAD:DASA21,
@INPROCEEDINGS{9682402,
  author={Jbene, Mourad and Tigani, Smail and Saadane, Rachid and Chehri, Abdellah},
  booktitle={2021 International Conference on Decision Aid Sciences and Application (DASA)}, 
  title={A Moroccan News Articles Dataset (MNAD) For Arabic Text Categorization},
  abstract  = {In recent years Natural language processing is one of the most active areas of research especially with the emergence of deep learning algorithms. More attention has been given to Latin descendent languages e.g English, French, and Spanish given the availability of high-quality datasets and compute resources. In this paper, we present a moroccan News Articles Corpus collected from four of the major moroccan news websites. The corpus contains more than 418k news articles corresponding to 19 different categories, thus considered to be one of the largest Arabic news articles corpora. A description of the collection and processing steps were presented and exploration analysis was performed. To prove the utility of the dataset. An evaluation step was conducted in the context of text classifcation using four different Machine Learning baselines: Random Forest (RF), Multinomial Naive Bayes (MNB), Support Vector Machine (SVC), and Gradient Boosting (GradBoost) Classifers. The experimental results are presented in terms of accuracy, F1-score, and confusion matrix.},
  year={2021},
  volume={},
  number={},
  pages={350-353},
  doi={10.1109/DASA53625.2021.9682402}}
}
```

# Sample

```
<!-- [
  {
   "Title":"هذا مصير المتورطين في أحداث شغب بعد مباراة تطوان والكوكب",
   "Body":"أدانت المحكمة الابتدائية بتطوان، مساء امس الثلاثاء، 14 شخصا اعتقلوا خلال أحداث الشغب التي تلت مباراة المغرب التطواني والكوكب المراكشي يوم 28 شتنبر 2018 وتسببت في تخريب عدد من السيارات والمرافق العمومية بوسط المدينة. هيئة المحكمة وبعد المداولات منحت الكلمة للمحامين المدافعين عن المتهمين والذي طالبوا باطلاق سراح موكليهم، قبل ان تعلن الهيئة القضائية عن توزيع أحكاما تراوحت بين 10 أشهر نافذة وشهر واحد. ابتدائية تطوان التي استمعت لافادات المتهمين في هذه القضية أدانت المتابعين فيها بعد ان وجهت اليهم تهم تخريب ممتلكات عمومية والمشاركة في اعمال شغب، وقضت بحبس أربعة متهمين لـ10 أشهر نافذة، فيما حكمت على عشرة آخرين بـشهر نافذ. الاحداث التي وقعت بمدينة تطوان، كانت قد انطلقت بعد نهاية مباراة المغرب التطواني والكوكب المراكشي احتجاجا على وفاة الشابة حياة بلقاسم برصاص البحرية الملكية بسواحل المضيق عندما كانت تحاول الهجرة نحو إسبانيا.",
   "Category":"Society"
   }
] -->
```
