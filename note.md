
The command `python examples/train_model.py -m hugging_face/gpt2 --add-special-tokens True --add-start-token True --gpt2-size small -t convai2 -bs 8 -mf /media/haotian/sg/haotian/Code/csc2621-ChatbotAD/model-files/gpt2_convai2`

[ time:16087.0s total_exs:509616 epochs:3.88 ] {'exs': 72, 'loss': 2.495, 'ppl': 12.12, 'token_acc': 0.4419, 'tokens_per_batch': 114.7, 'gnorm': 4.044, 'clip': 1.0, 'updates': 9, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63702}
[ time:16089.0s total_exs:509704 epochs:3.88 ] {'exs': 88, 'loss': 2.38, 'ppl': 10.81, 'token_acc': 0.4869, 'tokens_per_batch': 100.8, 'gnorm': 4.047, 'clip': 1.0, 'updates': 11, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63713}
[ time:16091.0s total_exs:509776 epochs:3.88 ] {'exs': 72, 'loss': 2.46, 'ppl': 11.71, 'token_acc': 0.4494, 'tokens_per_batch': 107.6, 'gnorm': 4.14, 'clip': 1.0, 'updates': 9, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63722}
[ time:16093.0s total_exs:509848 epochs:3.88 ] {'exs': 72, 'loss': 2.606, 'ppl': 13.54, 'token_acc': 0.442, 'tokens_per_batch': 113.9, 'gnorm': 4.152, 'clip': 1.0, 'updates': 9, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63731}
[ time:16095.0s total_exs:509928 epochs:3.88 ] {'exs': 80, 'loss': 2.576, 'ppl': 13.15, 'token_acc': 0.4279, 'tokens_per_batch': 101.2, 'gnorm': 4.325, 'clip': 1.0, 'updates': 10, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63741}
[ time:16097.0s total_exs:510008 epochs:3.88 ] {'exs': 80, 'loss': 2.328, 'ppl': 10.26, 'token_acc': 0.4533, 'tokens_per_batch': 106.1, 'gnorm': 3.809, 'clip': 1.0, 'updates': 10, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63751}
[ time:16099.0s total_exs:510080 epochs:3.88 ] {'exs': 72, 'loss': 2.386, 'ppl': 10.87, 'token_acc': 0.4689, 'tokens_per_batch': 105.4, 'gnorm': 4.006, 'clip': 1.0, 'updates': 9, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63760}
[ time:16102.0s total_exs:510152 epochs:3.88 ] {'exs': 72, 'loss': 2.662, 'ppl': 14.33, 'token_acc': 0.4478, 'tokens_per_batch': 110.7, 'gnorm': 4.271, 'clip': 1.0, 'updates': 9, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63769}
[ time:16104.0s total_exs:510200 epochs:3.88 ] {'exs': 48, 'loss': 2.411, 'ppl': 11.14, 'token_acc': 0.4489, 'tokens_per_batch': 109.2, 'gnorm': 4.266, 'clip': 1.0, 'updates': 6, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63775}
[ time:16106.0s total_exs:510264 epochs:3.88 ] {'exs': 64, 'loss': 2.401, 'ppl': 11.03, 'token_acc': 0.4636, 'tokens_per_batch': 104.9, 'gnorm': 6.27, 'clip': 1.0, 'updates': 8, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63783}
[ time:16108.0s total_exs:510336 epochs:3.88 ] {'exs': 72, 'loss': 2.54, 'ppl': 12.68, 'token_acc': 0.4557, 'tokens_per_batch': 109.0, 'gnorm': 4.161, 'clip': 1.0, 'updates': 9, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63792}
[ time:16110.0s total_exs:510416 epochs:3.88 ] {'exs': 80, 'loss': 2.519, 'ppl': 12.42, 'token_acc': 0.4561, 'tokens_per_batch': 109.4, 'gnorm': 3.855, 'clip': 1.0, 'updates': 10, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63802}
[ time:16112.0s total_exs:510488 epochs:3.88 ] {'exs': 72, 'loss': 2.611, 'ppl': 13.62, 'token_acc': 0.4441, 'tokens_per_batch': 115.3, 'gnorm': 3.796, 'clip': 1.0, 'updates': 9, 'lr': 1.0, 'gpu_mem_percent': 0.8722, 'total_train_updates': 63811}



[ Finished evaluating tasks ['convai2:self'] using datatype valid ]
{'exs': 7801, 'accuracy': 0.8025, 'f1': 0.8249, 'hits@1': 0.8025, 'hits@5': 0.9754, 'hits@10': 0.9958, 'hits@100': 1.0}

[ Finished evaluating tasks ['convai2:self:no_cands'] using datatype valid ]
{'exs': 7801, 'accuracy': 0, 'f1': 0.169}
