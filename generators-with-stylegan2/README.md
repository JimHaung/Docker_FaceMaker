# StyleGAN2人臉生成器
<i>Read English Introduction：<a href='https://github.com/a312863063/generators-with-stylegan2/blob/master/README_EN.md'>Here</a></i><br />
<br />
&emsp;&emsp;基於StyleGAN2製作的新版人臉生成器，既包含基於StyleGAN重制的臉：<a href='https://github.com/a312863063/seeprettyface-generator-wanghong'>網紅臉</a>，<a href='https://github.com/a312863063/seeprettyface-generator-star'>明星臉</a>，<a href='https://github.com/a312863063/seeprettyface-generator-model'>超模臉</a>，<a href='https://github.com/a312863063/seeprettyface-generator-babies'>萌娃臉</a>和<a href='https://github.com/a312863063/seeprettyface-generator-yellow'>黃種人臉</a>生成器，也新增了兩款更具美學意義的<a href='#'>混血臉</a>和<a href='#'>亞洲美人臉</a>生成器。做了這麼多款生成器已經足夠用，我將不再嘗試做人臉生成器相關的新內容，而是去探索更實用、更能滿足用戶需求的生成技術，以更好地服務人民。<br />
&emsp;&emsp;生成器的作用是可提供我們各種樣式的人臉素材，供我們在多種場景下應用並有助於節省尋找真人（人臉）的成本，值得注意的是，<b>每張人臉都是不存在於這個世界上的AI虛擬人物，他們獨特且永不重復。</b>

<br /><br /><br />
## 新版的提升與價值何在？
&emsp;&emsp;基於StyleGAN2製作的版本消除了圖片中水滴斑點和扭曲/損壞現象的出現，使生成的成功率接近100%（可參見下方隨機生成的數據集），能被應用於大批量生成任務之中；另外圖片的質量進一步提升，清晰度已逼近於官方訓練所採用的數據集。<b>我希望，這個項目能為影視、廣告、遊戲和醫美工作者們助力，同時為普通愛好者們賦能。</b><br />
&emsp;&emsp;此項目已大部分免費開源，希望能幫助到有需要的朋友。模型僅供玩耍和研究使用，未獲得授權不允許用作商業用途。模型版權所有為：www.seeprettyface.com ，若對您有幫助歡迎在底部贊助~ <br />

<br /><br />
# 效果預覽

## 網紅臉生成器
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/wanghong.png)<br/><br/>
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/example_wanghong.jpg)<br/><br/>
&emsp;&emsp;純隨機生成(無篩選)的一萬張生成圖片數據集：<a href='https://pan.baidu.com/s/1AqlNlTY0-tbEORPuKLdkqg'>https://pan.baidu.com/s/1AqlNlTY0-tbEORPuKLdkqg</a>  提取碼：c7v9<br /><br />

## 明星臉生成器
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/star.png)<br/><br/>
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/example_star.jpg)<br/><br/>
&emsp;&emsp;純隨機生成(無篩選)的一萬張生成圖片數據集：<a href='https://pan.baidu.com/s/1LabQMFLsKkYK3hLgRCQ-0A'>https://pan.baidu.com/s/1LabQMFLsKkYK3hLgRCQ-0A</a>  提取碼：p43h<br /><br />

## 超模臉生成器
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/model.png)<br/><br/>
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/example_model.jpg)<br/><br/>
&emsp;&emsp;純隨機生成(無篩選)的一萬張生成圖片數據集：<a href='https://pan.baidu.com/s/1AT4q1JkMvAxWrHMs4Af1wg'>https://pan.baidu.com/s/1AT4q1JkMvAxWrHMs4Af1wg</a>  提取碼：vxf4<br /><br />

## 萌娃臉生成器
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/kid.png)<br/><br/>
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/example_kids.jpg)<br/><br/>
&emsp;&emsp;純隨機生成(無篩選)的一萬張生成圖片數據集：<a href='https://pan.baidu.com/s/1CQYQFiIdXxCSjJwSUo_tvw'>https://pan.baidu.com/s/1CQYQFiIdXxCSjJwSUo_tvw</a>  提取碼：4bd0<br /><br />

## 黃種人臉生成器
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/yellow.png)<br/><br/>
&emsp;&emsp;![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/example_yellow.jpg)<br/><br/>
&emsp;&emsp;純隨機生成(無篩選)的一萬張生成圖片數據集：<a href='https://pan.baidu.com/s/1uC5fQ4UTALA1uU36Cgnnnw'>https://pan.baidu.com/s/1uC5fQ4UTALA1uU36Cgnnnw</a>  提取碼：rqvq <br/><br/>

## 總結
&emsp;&emsp;上述這麼多生成器看著有點可怕，但其實它離真正的商用之路還早著很呢。。如果真想衝擊傳統視覺行業的話，至少有兩個問題亟待解決：1.相關配套技術有待完善，譬如人臉植入、妝容精細控制、動畫及全身合成等等；2.如何圍繞精細的用戶群構建特定的生成技術服務體系也有待探索。

# 環境配置
&emsp;&emsp;· Both Linux and Windows are supported. Linux is recommended for performance and compatibility reasons.<br/>
&emsp;&emsp;· 64-bit Python 3.6 installation. We recommend Anaconda3 with numpy 1.14.3 or newer.<br/>
&emsp;&emsp;· TensorFlow 1.14 or 1.15 with GPU support. The code does not support TensorFlow 2.0.<br/>
&emsp;&emsp;· On Windows, you need to use TensorFlow 1.14 — TensorFlow 1.15 will not work.<br/>
&emsp;&emsp;· One or more high-end NVIDIA GPUs, NVIDIA drivers, CUDA 10.0 toolkit and cuDNN 7.5. To reproduce the results reported in the paper, you need an NVIDIA GPU with at least 16 GB of DRAM.<br/>
&emsp;&emsp;· Docker users: use the provided <a href='https://github.com/NVlabs/stylegan2/blob/master/Dockerfile'>Dockerfile</a> to build an image with the required library dependencies.<br/>
&emsp;&emsp;- On Windows, the compilation requires Microsoft Visual Studio to be in PATH. We recommend installing <a href='https://visualstudio.microsoft.com/vs/'>Visual Studio Community Edition</a> and adding into PATH using "C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Auxiliary\Build\vcvars64.bat".<br/>
&emsp;&emsp;我的測試環境配置為：Win10,1050Ti,CUDA 10.0,CuDNN 7.6.5,tensorflow-gpu 1.14.0，VS2017可完美運行。<br/><br/>

## Windows下常見問題 ：Could not find MSVC/GCC/CLANG installation on this computer如何解決？
&emsp;&emsp;在安裝VS2017/VS2019時一定要將‘使用C++的桌面開發’選上（如下圖所示）
![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/SMVC_solution/solution1.png)
&emsp;&emsp;裝好之後進入C:/Program Files (x86)/Microsoft Visual Studio/2019/Community/VC/Tools/MSVC/ 目錄下會有一個版本號的文件夾，將版本替換為dnnlib/tflib/custom_ops.py 29行的對應版本號（那是我安裝的版本），如下圖所示。
![Image text](https://github.com/a312863063/generators-with-stylegan2/blob/master/examples/SMVC_solution/solution2.png)

# 運行步驟
&emsp;&emsp;1.在networks文件夾中按照txt地址下載對應模型，放在該位置<br/>
&emsp;&emsp;2.在main.py中選擇對應的模型和生成數量(另如果覺得生成的多樣性不夠可以嘗試調高truncation_psi，不過成功率會下降)，並運行main.py<br/>
<br /><br /><br />