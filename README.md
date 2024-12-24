![](images/Hello.gif)

# <h1 align="center"> 👋HI👋  **I'm  TOM**  👇About MEEE👇 </h1>
My name is Wei-Hsiang Hsu, but you can call me Tom. I am from Taiwan and hold a master’s degree in Industrial Engineering and Management from Ming Chi University of Technology. I am continuously advancing in the field of programming, aiming to use it to create limitless possibilities.  
<p align="center"> ✊ Never Give Up 🖥 Lifelong learning 😎 Enjoy life </h1>

# <h1 align="center">  </h1>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Horizontal Timeline</title>
  <style>
    /* 設置時間線容器 */
    .timeline {
      display: flex;
      justify-content: space-evenly;
      align-items: center;
      padding: 20px 0;
      position: relative;
      width: 80%;
      margin: 0 auto;
    }

    /* 設置時間線的直線 */
    .timeline::before {
      content: '';
      position: absolute;
      width: 100%;
      height: 4px;
      background-color: #2196F3;
      top: 50%;
      left: 0;
      transform: translateY(-50%);
    }

    /* 每個事件的容器 */
    .timeline-container {
      position: relative;
      width: 100px;
      text-align: center;
    }

    /* 事件圓點 */
    .timeline-container::before {
      content: '';
      position: absolute;
      width: 20px;
      height: 20px;
      border-radius: 50%;
      background-color: #2196F3;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      border: 4px solid #fff;
    }

    /* 事件日期 */
    .date {
      margin-top: 10px;
      font-weight: bold;
    }

    /* 事件描述 */
    .content {
      background-color: #f4f4f4;
      padding: 10px;
      border-radius: 6px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

<div class="timeline">
  <!-- 事件1 -->
  <div class="timeline-container">
    <div class="date">2024</div>
    <div class="content">
      <h3>Event Title 1</h3>
      <p>Description of the event or milestone.</p>
    </div>
  </div>

  <!-- 事件2 -->
  <div class="timeline-container">
    <div class="date">2025</div>
    <div class="content">
      <h3>Event Title 2</h3>
      <p>Description of the event or milestone.</p>
    </div>
  </div>

  <!-- 事件3 -->
  <div class="timeline-container">
    <div class="date">2026</div>
    <div class="content">
      <h3>Event Title 3</h3>
      <p>Description of the event or milestone.</p>
    </div>
  </div>

  <!-- 事件4 -->
  <div class="timeline-container">
    <div class="date">2027</div>
    <div class="content">
      <h3>Event Title 4</h3>
      <p>Description of the event or milestone.</p>
    </div>
  </div>
</div>

</body>
</html>
