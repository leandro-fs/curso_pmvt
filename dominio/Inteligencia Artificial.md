


# Aprendizaje Automático - ML

### métricas

- ACC, Precisión, Recall, F1
- Errores tipo I, tipo II
- clases: ▮,  ▯

 **Exactitud**: a menudo puede ser engañosa. La razón es el desequilibrio entre las clases.
$$ Exactitud = \frac  {\color{green}▮ + \color{green}▯}{ ▮ + ▯ } = \frac  {\color{green}▮ + \color{green}▯}{ \color{green}▮ + \color{red}▯ + \color{green}▯ + \color{red}▮ } = Accuracy $$

 **precisión**: De lo clasificado como cierta clase, ¿cuánto está bien clasificado? Mejor para error Tipo I (FPR)
$$ precisión_▮ = \frac  {\color{green}▮ }{ \color{green}▮ + \color{red}▮ }  $$
$$ precisión_▯ = \frac  {\color{green}▯}{ \color{green}▯ +  \color{red}▯} $$
**recall**: Del total una clase, ¿qué tantos se clasificaron bien?  (TPR - *tasa de verdaderos positivos* ) Mejor para error Tipo II (FNR)
 true-positive rate is also known as [sensitivity](https://en.wikipedia.org/wiki/Sensitivity_(tests) "Sensitivity (tests)"), [recall](https://en.wikipedia.org/wiki/Precision_and_recall#Definition_(classification_context) "Precision and recall") or _probability of detection_. Intuitively, the ability of the classifier to find all the positive samples. 
$$ Recall_▮ = \frac  {\color{green}▮ }{▮} = \frac  {\color{green}▮ }{ \color{green}▮ + \color{red}▯} $$
 $$ Recall_▯ =  \frac  {\color{green}▯ }{▯} = \frac  {\color{green}▯}{ \color{green}▯ + \color{red}▮ } $$
**F1** o F-score: cuantos elementos están bien balanceados. reemplaza ACC en dataset desbalanceados, sin preferencia por FPR/FNR

$$F = 2 * \frac{Precision_▮ * Recall_▮}{Precision_▮ + Recall_▮}$$

$$ Recall_▮ = \frac  {\color{green}▮ }{▮} = \frac  {\color{green}▮ }{ \color{green}▮ + \color{red}▯} = 1 - TPR_▮ = FPR_▮$$


https://en.wikipedia.org/wiki/Sensitivity_and_specificity

- **Sensitivity** (true positive rate, TPR) is the probability of a positive test result, [conditioned](https://en.wikipedia.org/wiki/Conditional_probability "Conditional probability") on the individual truly being positive.
- **Specificity** (true negative rate, TNR) is the probability of a negative test result, conditioned on the individual truly being negative.

https://en.wikipedia.org/wiki/Confusion_matrix
![[wikipedia_matriz_confusión.png]]
