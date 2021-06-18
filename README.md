# AI DeepLearning Personal Project(Kaggle Competition)


* Competition Title : Contradictory, My Dear Watson(Detecting contradiction and entailment in multilingual text using TPUs)
* Description : 다양한 언어(15개 언어)로 주어진 전제문장(Promise)와 가설문장(hypothesis) 간의 문맥을 파악하여 entailment(0), neutral(1), contradiction(2)로 분류하는 자연어 추론 문제
* Evaluation 지표 : 
  accuracy
  
* Model 
  
  . BERT를 Fine-tuning한 **RoBERTa**(Robustly Optimized BERT Pretraining Approach)
  
  . RoBERTa 중 Competition task의 데이터 셋의 15개 언어 특화 지원 추론 모델인 **xlm-roberta-large-xnli** 활용
 
  
