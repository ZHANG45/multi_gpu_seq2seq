# multi_gpu_seq2seq

This is a simple seq2seq model which can work on multi-gpu. In this model, beam search and greedy method are both provided in decoding.

# Notice:
when use beam search, small batch is not used, and the computing speed will be very slow.

The basic seq2seq code is offered by https://github.com/KobayashiNaoki/Parallel_PyTorch_Seq2Seq. And the beam search part is added by me.
