# Open-source-information-for-a-paper
It is a great honor to share my work! Open source information about the paper "A deep learning framework for inverse design of non-unique photonic structures:  DBSCAN-based quantitative analysis approach" can be found here
说明：
1关于代码：开源的代码是我实现论文中的算法的代码，代码是一个动态的状态，不同的结果可以在同一个代码中实现，但是需要修改部分信息，不是每一个测试结果都有与之对应的专门的代码，一个.py文件，可以获得许多测试结果，但需要明白代码的逻辑，并根据要获得的结果相应的修改代码。
2关于仿真程序：所有的仿真都是在FDTD Solutions中实现的，我已经将仿真得到的数据开源并且上传了仿真文件，其中有各个模块的连接脚本和扫描设置，可以按需修改。
3关于DBSCAN算法代码：同样DBSCAN算法是一个动态的代码，不是直接运行就能得到结果，需要根据需求修改输入文件，得到对应的结果文件。
4关于python和FDTD、MATLAB联调的部分，这部分在论文中没有体现，不过如果想要做前向验证的可以参考这部分代码。
5关其他说明：因为本项工作是个繁琐复杂的工作，由于测试需求在工作期间对代码进行了多次修改和反复测试，代码被不断的注释和删改以达到调试的目的进而导致代码的美观和可读性不高，所有开源的代码和数据都仅作为一个思路参考或部分借鉴。
