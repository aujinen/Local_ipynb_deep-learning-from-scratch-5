### テキストp.121、注意
誤＃1：「backwardという用語は、バックプロパゲーション（誤差逆伝播法）に由来します」<br>
誤＃2：「バックプロパゲーションは、微分を効率的に求めるためのアルゴリズムです」<br>
正＃1：「backwardという用語は、ニューラルネットワークでのbackpropagation（誤差逆伝播法）に通じるところがあります」<br>
正＃2：「backpropagation（誤差逆伝播法）はモデルの該当部分での関数が微分可能であるという前提で、微分にて得られる勾配に基づいた誤差を上流へ（＝backward；後方へ）伝播する手法です。」<br>
「```backward()```関数は、ニューラルネットワークでのbackpropagation（誤差逆伝播法）を行うために必要な機能を提供するPyTorchの関数で、backpropagation以外の目的でも利用可能な汎用の関数です。」<br>
＃1詳細；<br>
英語の"backword" ("forward"の対義語）は"backpropagation"よりも一般的、かつ古い英語です。<br>
＃2詳細：<br>
```backward()```関数の詳細は下記のマニュアル類を参照してください。<br>
参照：<br>
<a href="https://pytorch.org/docs/stable/generated/torch.Tensor.backward.html">torch.Tensor.backward</a><br>
<a href="https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html">Pytorch/Neural Networks</a><br>
<a href="https://qiita.com/windfall/items/073cbb4ffdfab356e495">【PyTorch】自作関数の勾配計算式（backward関数）の書き方①</a><br>
<a href="https://zenn.dev/hirayuki/articles/bbc0eec8cd816c183408">Pytorchの基礎 forwardとbackwardを理解する</a><br>
<a href="https://qiita.com/simayan/items/ea8bc5df150f7890d0e7">Pytorchのnn.Transformerのforward関数を理解する</a><br>
<a href="https://t-keita.hatenadiary.jp/entry/2021/09/04/145412">PyTorch の自動微分に入門する</a><br>
<a href="https://oumpy.github.io/blog/2022/02/directional_gradient_optimization.html">方向微分によるニューラルネットワークの勾配近似(大阪大学医学部 Python会)</a><br>
