<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <title>申请表</title>
</head>
<body>
    <h1>申请表</h1>
    
    <!-- 第一部分：基本信息 -->
    <div class="section">
        <label for="name">姓名：</label>
        <input type="text" id="name" name="name" placeholder="______">
    </div>
    
    <!-- 第二部分：职位选择和其他要求 -->
    <div class="section">
        <p>感兴趣的职位：</p>
        <input type="radio" id="designer" name="position" value="Web设计人员">
        <label for="designer">Web设计人员</label>
        
        <input type="radio" id="manager" name="position" value="Web管理人员">
        <label for="manager">Web 管理人员</label>
        
        <input type="radio" id="developer" name="position" value="Web开发人员">
        <label for="developer">Web开发人员</label>
        
        <p>其他要求：</p>
        <p>包括薪水待遇、工作地点等。</p>
        <textarea name="requirements" rows="4" cols="50"></textarea>
    </div>
    
    <!-- 第三部分：发送确认和选项 -->
    <div class="section">
        <h2>发送确认消息</h2>
        <label for="experience">经验</label>
        <select id="experience" name="experience">
            <option value="no_experience">无经验</option>
            <option value="1-3">1-3年</option>
            <option value="3-5">3-5年</option>
            <option value="5+">5年以上</option>
        </select>
        
        <div class="buttons">
            <button type="submit">确定</button>
            <button type="reset">重置</button>
        </div>
    </div>
</body>
</html>
