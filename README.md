![alt text](http://www.keepcad.com.br/admin/ckeditor/kcfinder/upload/images/blog%202015/logo_inpe.gif "INPE Logo")

# Fake News Model
# Made by Rodrigo Takeshi and Francisca Joamila


CAP-241: Computação Aplicada of Graduate degree program in National Institute for Space Research (INPE) 
This model was made using Lua Programming Language and can be executed [by using Terra-ME](http://www.ccst.inpe.br/modelagem/terra-me-ambiente-computacional-multi-paradigma-para-o-desenvolvimento-de-modelos-integrados-natureza-sociedade/) 


An empiric fake news spreading model using cellular automata.

This work simulates spreading of fake news in Social Networks Viralization.

The initial parameters was based on 2014 brazilian official media consumption survey.

Cells can assume three states:
  
  1- Gray: It's a Neutral State, meaning that a random user was not affected by any fake or truth news.
  
  2- Red: It's a Fake State, meaning that a random user was affected by a fake news, he will help to spread the fake news, and if many of his friends have true news, he will change State to Neutral or Truth.
  
  3- Green: It's a Truth State, meaning that a random user was affected by a true news, he will help to spread the true news, if many of his friends have fake news, he will change State to Neutral or Fake.
  
  
