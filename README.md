# assignment-hi

<h3>
  初期設定
</h3>
  下記二箇所の変更が必要な場合がある。(現在GitHub pagesで表示できるように設定)
<br>
・コンテンツをクリックした際のリンク先URL(index.html:15)
<br>
・360度写真のURL(js/main.js:22)
<br>
<h3>
  視点変更
</h3>
デバイスがAndroidまたはiosの場合はジャイロセンサー、それ以外のデバイスではマウスドラッグで視点変更が可能。
<h3>
  初期表示画面および360度画像の変更方法
</h3>
js/main.js:17 から変更可能
<br>
詳しくは<a href="https://threejs.org/docs/#api/en/geometries/SphereGeometry" target="_blank">公式ドキュメント参照</a>
<h3>
  上下方向の限界角度調整
</h3>
js/main.js:92,93 で変更可能。
詳しくは<a href="https://threejs.org/docs/index.html#examples/controls/OrbitControls.minPolarAngle" target="_blank">公式ドキュメント参照</a>
<h3>
  外部ライブラリ
</h3>
<p>
  360度画像のコントロールに<a href="https://threejs.org/" target="_blank">three.js</a>を使用。
</p>
js/three/three.min.js 3D画像をコントロールする
<br>
js/three/OrbitControls.js 3D画像をマウスドラッグでコントロールする
<br>
js/three/DeviceOrientationControls.js 3D画像をジャイロセンサーでコントロールする
