# Mesh Check

Mesh Check allows you to display triangle and ngons directly in the 3D view by<br />
dyeing them so you can see them quickly.<br />

<img  src="doc/mesh_check.gif" alt="" /><br />

Blender2.8へアップデート作業途中。<br />
細かなメニューなどは対応させたが、<br />
メイン機能の描画方法をbglからgpuへ変更させなくてはならない。<br />


## 旧版のBlender2.8 ver

マテリアルを使用する古いバージョンは、すでにBlender2.8にアップデートしている。<br />
Blender Add-on : Mesh Check [Ngons / Tris Checker Blender2.8]<br />
https://gumroad.com/l/tsYGF


## 進捗

Mesh Check ver1.0.0 三角形をハイライト表示することができた。しかしバグが多くある
2019-10-31
- 裏面が表示されて邪魔
- Nゴンが正しく表示されない
- Nゴンを作ると、三角形が消える(消えないポリゴンもある)
- 色の透明度が反映されていない

<img  src="doc/sintyoku-2019-10-31.png" alt="" /><br />
