How to execute the file and tweak the parameters:

The function that contains the editable parameters have been defined in line 98 and 99 as follows:

```
def project1_model(P, N, _C, block, num_blocks):
    return ResNet(P, N, _C, block, num_blocks)
```
However, we pass the parameters into the model in line 139:

```
net = project1_model(3, 4, 32, BasicBlock, [4,4,4,3])
```

All we have to do to make this code functional is to run it like you would any traditional python file.
