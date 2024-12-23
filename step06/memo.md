### テキストp.121、注意
誤：「backwardという用語は、バックプロパゲーション（誤差逆伝播法）に由来します」<br>
正：「backwardという用語は、ニューラルネットワークでのbackpropagation（誤差逆伝播法）に通じるところがあります」<br>
```backward()```関数は、英語の"backword" ("forward"の対義語）で"backpropagation"よりも古い英語です。<br>
どちらも「後方へ」の意味がありますが、```backward()```関数は、"backpropagation"よりも、"feedback"（"feedforward"の対義語）に近い意味を持ちます。<br>
参照：<br>
<a href="https://pytorch.org/docs/stable/generated/torch.Tensor.backward.html">torch.Tensor.backward</a><br>
<a href="https://qiita.com/windfall/items/073cbb4ffdfab356e495">【PyTorch】自作関数の勾配計算式（backward関数）の書き方①</a><br>
<a href="https://zenn.dev/hirayuki/articles/bbc0eec8cd816c183408">Pytorchの基礎 forwardとbackwardを理解する</a><br>
<a href="https://qiita.com/simayan/items/ea8bc5df150f7890d0e7">Pytorchのnn.Transformerのforward関数を理解する</a>
