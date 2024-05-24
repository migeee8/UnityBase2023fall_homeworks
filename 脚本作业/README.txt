keyboardAndMouseController中为鼠键控制，其中查找是按照标签查找，所以如果报错SpawnedObject不存在是因为没有添加标签，加上“SpawnedObject”的tag即可（或者导入tag命名的资源包）。

键鼠具体操作方法：
/// wasd控制物体前后左右移动
/// 鼠标左键按下并平移控制旋转
/// 鼠标滚轮控制缩放
/// 键盘按下空格复制物体
/// 鼠标右键删除所有复制物体，但是保留原有物体
/// 键盘v键禁用/启用物体

UIinputController为ui按钮控制，点击按钮即可实现相关操作。