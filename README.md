审计大模型评估基准

评测指标主要分为accuracy,ROUGE1,ROUGE2,ROUGEL,bert_score_f1,bart_score

accuracy（准确度测试：预测正样本/总样本）：主要用于审计考试题测试，以及根据审计问题描述和审计意见，进行审计分类。
 
ROUGE (Recall-Oriented Understudy for Gisting Evaluation)专注于召回率（关注有多少个参考译句中的 n- gram出现在了输出之中）而非精度(候选译文中的n-gram有没有在参考译文中出现过)。
ROUGE-N: 在 N-gram 上计算召回率。


ROUGE-L: 考虑了机器译文和参考译文之间的最长公共子序列。
