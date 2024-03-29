# Arabic Bots Detection on Twitter

This repo contains the labeled dataset (```Labeled_users.csv```) used in our CSCW 2019 paper titled 'Hateful People or Hateful Bots? Detection and Characterization of Bots Spreading Religious Hatred in Arabic Social Media.' The csv file contains 450 user IDs along with two bot scores. The first bot score (```Botometer_score```) is the language-independent bot score obtained from [Botometer](https://github.com/IUNetSci/botometer-python), and the second score (```true_score```) is the score assigned by the research team after carefully examining users' profile information, tweets, friends, and interaction with other users. As per [Twitter's Developer Policy](https://developer.twitter.com/en/developer-terms/policy), we are only allowed to publicly share user ids along with annotation. Users data (except for accounts that have been deleted, suspended or made private) can be collected using [Twitter's  GET statuses/user_timeline API](https://developer.twitter.com/en/docs/tweets/timelines/api-reference/get-statuses-user_timeline.html).

Please cite our paper if you find our data helpful for your research: 

```
@article{albadi2019hateful,
  title={Hateful people or hateful bots? Detection and characterization of bots spreading religious hatred in Arabic social media},
  author={Albadi, Nuha and Kurdi, Maram and Mishra, Shivakant},
  journal={Proceedings of the ACM on Human-Computer Interaction},
  volume={3},
  number={CSCW},
  pages={1--25},
  year={2019},
  publisher={ACM New York, NY, USA}
}
```
