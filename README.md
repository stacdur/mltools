# mltools

`mltools` est un package Python pour gérer différents modèles de machine learning 
et de deep learning avec Scikit-learn, Keras, PyTorch et Transformers.

## Installation

Clonez le projet à partir de GitHub et installez-le via pip :

```bash
git clone https://github.com/stacdur/mltools.git
cd mltools
pip install .


Utilisation

Exemple d'utilisation avec un modèle Scikit-learn :

from mltools import LogisticRegressionModelManager

model = LogisticRegressionModelManager()
model.initialize_model(max_iter=100)
model.train(X_train, y_train)
accuracy = model.evaluate(X_test, y_test)
print(f'Accuracy: {accuracy}')


Contributions

Contributions are welcome! Please fork the repository and submit a pull request.


LICENSE :

MIT License

Copyright (c) 2024 STACDUR

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
...
