This repository purpose is to stock all the solutions developed for data challenges in order to use them for other ML applications.

## Techniques used
The main tools used to adress those challenges are transformers with stable learning based on the article "Deep Stable Learning for Out-Of-Distribution Generalization" (Zhang et al.) and CatBoost. The technique of stable learning is adapted to the PyTorch framework by using a penalization (instead of constrained optimization). The results are promising since the optimization seems more stable.