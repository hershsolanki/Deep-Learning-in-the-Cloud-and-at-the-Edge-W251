How long does it take to complete the training run? (hint: this session is on distributed training, so it will take a while)
```
On the v100, it took 22 hours, 22 minutes for 50k steps. I stopped at 50k because I was about to run out of IBM cloud credits. iF I think about 300k steps at the same rate, it would take ~134 hours.
```

Do you think your model is fully trained? How can you tell?
```
My model is not fully trained, because I limited the amount of steps it could take.
```
Were you overfitting?
```
No, both training loss and eval loss are about the same.
```

Were your GPUs fully utilized?
![GPU](/Users/h/Desktop/Screen/Shot/2020-03-01/at/10.44.17/PM.png)



Did you monitor network traffic (hint: apt install nmon ) ? Was network the bottleneck?
Take a look at the plot of the learning rate and then check the config file. Can you explan this setting?
How big was your training set (mb)? How many training lines did it contain?
What are the files that a TF checkpoint is comprised of?
How big is your resulting model checkpoint (mb)?
Remember the definition of a "step". How long did an average step take?
How does that correlate with the observed network utilization between nodes?
