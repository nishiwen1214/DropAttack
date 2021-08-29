# DropAttack: A Masked Weight Adversarial Training Method to Improve Generalization of Neural Networks
Abstract: Adversarial training has been proven to be a powerful regularization method to improve the generalization of models. However, current adversarial training methods only attack the original input sample or the embedding vectors, and their attacks lack coverage and diversity. To further enhance the breadth and depth of attack, we propose a novel masked weight adversarial training method called DropAttack, which enhances generalization of model by adding intentionally worst-case adversarial perturbations to both the input and hidden layers in different dimensions and minimize the adversarial risks generated by each layer. DropAttack is a general technique and can be adopt to a wide variety of neural networks with different architectures. To validate the effectiveness of the proposed method, we used five public datasets in the fields of natural language processing (NLP) and computer vision (CV) for experimental evaluating. We compare the proposed method with other adversarial training methods and regularization methods, and our method achieves state-of-the-art on all datasets. In addition, Dropattack can achieve the same performance when it use only a half training data compared to other standard training method. Theoretical analysis reveals that DropAttack can perform gradient regularization at random on some of the input and wight parameters of the model. Further visualization experiments show that DropAttack can push the minimum risk of the model to a lower and flatter loss landscapes.

<img width="770" alt="image" src="https://user-images.githubusercontent.com/56249874/131253058-b2efc608-f3e8-4633-977c-77e1c3f1e426.png">

### Stars are welcome, thank you!
