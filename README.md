## Valuing passes using Football Tracking Data

Passing is the most frequent event in a football match. This project scratches the surface how we can calculate different parameters of a 'pass' event using tracking data. Traditional metrics to value passes in football mostly utilises the widely available on-the-ball event data.

Tracking data captures much more insights as it includes every player position at each instant. Even though there is very [limited public open source tracking data](https://github.com/metrica-sports/sample-data#other-tracking-data-sources), this project discusses the algorithms for calculating parameters of a pass. As more tracking data would be available, we can compute and analyse how various aspects and scenarios of a pass influence the pass's impact. The pass parameters can itself be features to a trained model.

We also implement the Pitch Control x EPV and the VAEP metric for valuing passes.

<b>Acknowledgement</b>
- Metrica Sports: For publishing tracking + event data to the community online<br>
  Dataset Link: [Metrica Sports sample tracking and event data](https://github.com/metrica-sports/sample-data)<br><br>
- Laurie Shaw and FriendsOfTracking: For lectures and code to understand and get started with tracking data<br>
  Repo: [Laurie's code for Metrica tracking data](https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking)<br>
  Youtube: [Friends of Tracking](https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w)

<b>References/Further Reading</b>
- [Valuing passes in football using ball event data](https://thesis.eur.nl/pub/41346/Bransen.pdf)
- Pitch Control: [Lecture](https://www.youtube.com/watch?v=X9PrwPyolyU&t=215s), [Presentation](https://www.researchgate.net/profile/William-Spearman/publication/334849056_Quantifying_Pitch_Control/links/5d434d0aa6fdcc370a742d04/Quantifying-Pitch-Control.pdf)
- EPV: [A Multiresolution Stochastic Process Model for Predicting Basketball Possession Outcomes](https://arxiv.org/pdf/1408.0777.pdf), [A framework for the fine-grained evaluation of the instantaneous expected value of soccer possessions](https://arxiv.org/pdf/2011.09426.pdf)
- VAEP: [Actions Speak Louder than Goals: Valuing Player Actions in Soccer](https://arxiv.org/pdf/1802.07127.pdf)
- [A Framework for Tactical Analysis and Individual Offensive Production Assessment in Soccer Using Markov Chains](http://nessis.org/nessis11/rudd.pdf)