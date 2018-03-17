### 项目目的

对[泰坦尼克号数据](https://github.com/ShiChJ/DAND-Basic-Materials/blob/master/P2/Project_Files/titanic-data.csv)进行数据分析，并创建一个文档分享你的发现。你可以首先了解数据集，想想它可以用来回答哪些问题。然后，你应该使用 Pandas 和 NumPy 回答你感兴趣的问题，并编写一份报告，分享你的结论。你需要在报告中声明，你的结论是暂时的，可能需要进一步改进

### 分析问题

有哪些因素会让船上的人生还率更高？

### 数据结论

通过分析年龄、性别以及阶层对生还率的影响发现：1.女性的生还率高；2.阶层越高，生还率也越高（未收到女性在各阶层的比例影响）；3.如果你的年龄低于15岁，那么你更有可能生还

其实我们还可以提出更多的猜想，比如：水手的生还率是否更高呢？但是发现数据集中并没有相关的数据。其次，根据维基百科，大约有1317名乘客，但数据集只有891名乘客，这严重限制了我们得出明确结论的能力。这就体现了数据局限性对数据分析准确率的重大影响。