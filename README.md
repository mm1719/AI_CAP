# AI_CAP
## 檔案說明
- groq_llama3_70B.ipynb: 用 GroqCloud API 測試 Llama 3 80B 
- mbbp_test.ipynb: 用來 fine-tuned 和測試 Phi-3 3.5B，包含使用 Optuna 找到最佳參數
- mbpp_test_with_tune.ipynb: 用來測試 Optuna 調參後的 Phi-3 3.5B
- phi3_evaluate_origin.ipynb, phi3_evaluate_1TCDH.ipynb, phi3_evaluate_3TCDH.ipynb, phi3_evaluate_3TCBH.ipynb: 測試各種 phi-3 在 testing set 的表現
## 資料夾說明
- data: 裡面有 testing set, training set 還有每種模型的測試答案
- eval: Phi-3 的測試情況