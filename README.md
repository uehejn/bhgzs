<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>论坛社区</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Font Awesome -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
  <style>
    .badge-certification {
      font-size: 12px;
      margin-left: 5px;
    }
    .badge-certification.fire { background-color: #ff4500; }
    .badge-certification.v { background-color: #1e90ff; }
    .badge-certification.star { background-color: #ffd700; }
    .badge-certification.official { background-color: #32cd32; }
  </style>
</head>
<body>
  <!-- 导航栏 -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">论坛社区</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto">
          <li class="nav-item"><a class="nav-link" href="#home">首页</a></li>
          <li class="nav-item"><a class="nav-link" href="#categories">板块</a></li>
          <li class="nav-item"><a class="nav-link" href="#search">搜索</a></li>
        </ul>
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#login">登录</a></li>
          <li class="nav-item"><a class="nav-link" href="#register">注册</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- 首页内容 -->
  <div class="container mt-4">
    <div class="row">
      <!-- 左侧：帖子列表 -->
      <div class="col-md-8">
        <h2>最新帖子</h2>
        <div class="list-group">
          <div class="list-group-item">
            <h5>如何学习编程？</h5>
            <p class="mb-1">作者：张三 <span class="badge badge-certification fire">🔥标</span></p>
            <small>发布于 2023-10-01</small>
            <div class="mt-2">
              <a href="#" class="btn btn-sm btn-primary">查看详情</a>
              <a href="#" class="btn btn-sm btn-success">评论</a>
            </div>
          </div>
          <div class="list-group-item">
            <h5>分享一个有趣的项目</h5>
            <p class="mb-1">作者：李四 <span class="badge badge-certification v">V标</span></p>
            <small>发布于 2023-10-02</small>
            <div class="mt-2">
              <a href="#" class="btn btn-sm btn-primary">查看详情</a>
              <a href="#" class="btn btn-sm btn-success">评论</a>
            </div>
          </div>
        </div>
      </div>

      <!-- 右侧：用户信息和功能 -->
      <div class="col-md-4">
        <!-- 用户信息 -->
        <div class="card mb-3">
          <div class="card-body">
            <h5 class="card-title">用户信息</h5>
            <p>用户名：张三</p>
            <p>认证：<span class="badge badge-certification fire">🔥标</span></p>
            <a href="#profile" class="btn btn-warning">修改资料</a>
          </div>
        </div>

        <!-- 站内通知 -->
        <div class="card mb-3">
          <div class="card-body">
            <h5 class="card-title">站内通知</h5>
            <ul class="list-group">
              <li class="list-group-item">您的帖子有新回复</li>
              <li class="list-group-item">收到一条私信</li>
            </ul>
          </div>
        </div>

        <!-- 高级搜索 -->
        <div class="card mb-3">
          <div class="card-body">
            <h5 class="card-title">高级搜索</h5>
            <form>
              <input type="text" class="form-control mb-2" placeholder="关键词">
              <select class="form-select mb-2">
                <option>选择板块</option>
                <option>技术</option>
                <option>生活</option>
              </select>
              <button type="submit" class="btn btn-primary">搜索</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- 私信功能 -->
  <div class="container mt-4">
    <h2>私信</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="list-group">
          <a href="#" class="list-group-item list-group-item-action">李四</a>
          <a href="#" class="list-group-item list-group-item-action">王五</a>
        </div>
      </div>
      <div class="col-md-8">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">与李四的对话</h5>
            <div class="chat-box" style="height: 200px; overflow-y: scroll;">
              <p><strong>李四：</strong>你好！</p>
              <p><strong>张三：</strong>你好，有什么问题吗？</p>
            </div>
            <textarea class="form-control mt-2" placeholder="输入消息"></textarea>
            <button class="btn btn-primary mt-2">发送</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- 页脚 -->
  <footer class="bg-dark text-white mt-4">
    <div class="container py-4">
      <p class="text-center">© 2023 论坛社区</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
