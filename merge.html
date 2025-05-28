<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>合并 PNG 和任意文件</title>
</head>
<body>
  <h2>合并固定 PNG 和任意文件 → 导出为 dog.jpg</h2>

  <label>选择要附加的任意文件：</label>
  <input type="file" id="extraFile"><br><br>

  <button onclick="mergeFiles()">合并并下载</button>

  <script>
    async function mergeFiles() {
      const extraInput = document.getElementById('extraFile');
      if (!extraInput.files[0]) {
        alert('请先选择一个文件！');
        return;
      }

      // 加载固定 PNG 图片（你也可以替换为自己的图片）
      const pngUrl = 'https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg'; // 示例图片链接
      const pngResponse = await fetch(pngUrl);
      const pngArray = await pngResponse.arrayBuffer();

      // 读取用户选择的文件内容
      const extraBlob = extraInput.files[0];
      const extraArray = await extraBlob.arrayBuffer();

      // 合并为新 Blob
      const mergedBlob = new Blob([pngArray, extraArray], { type: 'image/jpeg' });

      // 下载
      const a = document.createElement('a');
      a.href = URL.createObjectURL(mergedBlob);
      a.download = 'dog.jpg';
      a.click();
      URL.revokeObjectURL(a.href);
    }
  </script>
</body>
</html>
