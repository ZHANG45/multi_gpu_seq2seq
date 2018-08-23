# multi_gpu_seq2seq

This is a simple seq2seq model which can work on multi-gpu. In this model, beam search and greedy method are both provided in decoding. The basic seq2seq code is copied from https://github.com/KobayashiNaoki/Parallel_PyTorch_Seq2Seq. And the beam search part is added by me.


# Notice:
The result generated by beam search has been nomalized by length accroding to https://arxiv.org/pdf/1609.08144.pdf.
And when use beam search, small batch is not used, so the computing speed will be very slow.

