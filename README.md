# Transformer-based-Machine-Translation
Transformer-based Machine Translation for Low-resourced Languages embedded with Language Identification 


Abstract: Recent research on the development of machine translation (MT) models has resulted in state-of-the-art performance for many resourced European languages. However, there has been a little focus on applying these MT services to low-resourced languages. This paper presents the development of neural machine translation (NMT) for low-resourced languages of South Africa. Two MT models, JoeyNMT and transformer NMT with self-attention are trained and evaluated using BLEU score. The transformer NMT with self-attention obtained state-of-the-art performance on isiNdebele, SiSwati, Setswana, Tshivenda, isiXhosa, and Sepedi while JoeyNMT performed well on isiZulu. The MT models are embedded with language identification (LID) model that presets the language for translation models. The LID models are trained using logistic regression and multinomial naive Bayes (MNB). MNB classifier obtained an accuracy of 99% outperforming logistic regression which obtained the lowest accuracy of 97%.
