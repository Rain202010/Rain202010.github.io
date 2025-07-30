<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <title>上传儿童绘本 PPT</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f4f8fb; color: #333; display: flex; align-items: center; justify-content: center; height: 100vh; margin: 0; }
    .container { background: #fff; padding: 30px 40px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); max-width: 400px; text-align: center; }
    h1 { font-size: 24px; margin-bottom: 20px; }
    label { display: block; margin: 15px 0 5px; font-size: 16px; }
    input[type="file"] { padding: 8px; width: 100%; }
    .btn { margin-top: 20px; background: #007bff; color: #fff; border: none; padding: 12px 20px; font-size: 16px; cursor: pointer; border-radius: 5px; }
    .btn:hover { background: #0056b3; }
    .note { margin-top: 10px; font-size: 14px; color: #666; }
  </style>
</head>
<body>
  <div class="container">
    <h1>生成你的故事视频</h1>
    <form method="post" enctype="multipart/form-data" action="https://hook.eu2.make.com/cjs2ml1wwg1kknff9qj4w6mp2rmio92e">
      <label for="file">上传绘本 PPT 文件 (.ppt 或 .pptx)：</label>
      <input id="file" type="file" name="file" accept=".ppt,.pptx" required />
      
      <label for="email">输入接收通知的邮箱：</label>
      <input id="email" type="email" name="email" placeholder="你@example.com" required />

      <button type="submit" class="btn">上传并生成视频</button>
    </form>
    <p class="note">上传后，请等待系统自动处理（可能需要几分钟）。完成后系统将发送邮件通知你查看结果。</p>
  </div>
</body>
</html>
