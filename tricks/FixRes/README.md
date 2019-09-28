---
titile: FixRes: Fixing the train-test resolution discrepancy
tldr: If you use zoom crop augmentation you should use a larger resolution at test than training time and tune your model on the larger resolution.
labels: training, image-recognition, augmentation, zoom-crop
---
# FixRes

### Summary

When using zoom and crop #augmentation a disparity between the size of objects at training and test time is introduced. To fix this train on smaller resolution and tune the model on larger test resolution afterwards.





### References

| Date | Source |
| --- | --- |
| 6/14/19 | [Fixing the train-test resolution discrepancy](https://arxiv.org/abs/1906.06423) |


### Implementations

| Framework | Link |
| --- | --- |
| PyTorch | [https://github.com/facebookresearch/FixRes](https://github.com/facebookresearch/FixRes) |
