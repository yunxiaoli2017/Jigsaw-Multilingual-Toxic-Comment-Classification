![Header image](https://github.com/KayvanShah1/Jigsaw_multilingual_toxic_comment_classification/blob/master/Images/header.png)
# Jigsaw Multilingual Toxic Comment Classification

It only takes one toxic comment to sour an online discussion. The Conversation AI team, a research initiative founded by Jigsaw and Google, builds technology to protect voices in conversation. A main area of focus is machine learning models that can identify toxicity in online conversations, where toxicity is defined as anything rude, disrespectful or otherwise likely to make someone leave a discussion. If these toxic contributions can be identified, we could have a safer, more collaborative internet.

In the previous 2018 Toxic Comment Classification Challenge, Kagglers built multi-headed models to recognize toxicity and several subtypes of toxicity. In 2019, in the Unintended Bias in Toxicity Classification Challenge, you worked to build toxicity models that operate fairly across a diverse range of conversations. This year, we're taking advantage of Kaggle's new TPU support and challenging you to build multilingual models with English-only training data.

Jigsaw's API, Perspective, serves toxicity models and others in a growing set of languages (see our documentation for the full list). Over the past year, the field has seen impressive multilingual capabilities from the latest model innovations, including few- and zero-shot learning. We're excited to learn whether these results "translate" (pun intended!) to toxicity classification. Your training data will be the English data provided for our previous two competitions and your test data will be Wikipedia talk page comments in several different languages.

As our computing resources and modeling capabilities grow, so does our potential to support healthy conversations across the globe. Develop strategies to build effective multilingual models and you'll help Conversation AI and the entire industry realize that potential.

*Disclaimer: The dataset for this competition contains text that may be considered profane, vulgar, or offensive.**

*Description from [competition page](https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification/overview/description)*

# Results:
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css" 
integrity="sha384-r4NyP46KrjDleawBgD5tp8Y7UzmLA05oM1iAEQ17CSuDqnUK2+k9luXQOfXJCJ4I" crossorigin="anonymous">
<table class="table table-dark table-striped">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">Method Description</th>
      <th scope="col">Accuracy (%)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>XLM-RoBERTa with balanced data</td>
      <td>93.78</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Distil-BERT</td>
      <td>87.11</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>XLM-RoBERTa with unbalanced data</td>
      <td>87.10</td>
    </tr>
  </tbody>
</table>
