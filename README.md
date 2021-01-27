# Simon工具箱时刻表管理系统

## ① 关于
Simon工具箱时刻表管理系统是由B站Up主Simon1356创建的专门为Simon工具箱生成和管理时刻表模块的工具，系统可以导入/导出或手动新建列车时刻表，导出的JSON配置文件可用于Simon工具箱数据库，并显示成易读的时刻表。
https://Simon1356.github.io/time-table

## ② 使用方法
- 方法一：直接导入
  - 点击上方的 **选择文件** ，选择好后，点击 **读取** 即可（示例文件在data文件夹中）
  - 在下方表中操作，更改其时刻、标签、备注（备注格式必须以类似“S504次”“G2222次”开头）
  - 如果车次是4个数字，不要忘记调节 *车次位数*
- 方法二：手动新增
  - 先＋添加车站，输入车站名称，可选是否开启不同颜色标签
  - 可直接点击车站后方的 ＋号来新增单个时刻的车次
  - 或点击左上角 **录入车次** ，在弹窗中输入添加时刻以及对应停靠的车站，最后填写备注以及标签
  - 添加后依然可以对单个车次进行调整，方法参照方法一中的最后几条
- 搜索过滤
  - 过滤仅车号数字部分来快速筛选，注意：筛选时，列表中车次备注信息中的车号不可修改，标签和时刻可以修改
- 保存
  - 点击上方的保存导出配置文件，默认下载到系统“下载”目录
- 基础信息
  - 线路显示名称，尽量不要多于3个字
  - 列表中位置，指的是在Simon工具箱中该线路的位置
  - 滚动通知，需要输入“时刻表更新于：”后面的内容
  - 车次位数，3或4