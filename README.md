# 104
This is a paper started by Bootstrap grid systems.

<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <title>统一建模语言理论测试</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">   
<style>
#header {
  padding-top: 20px;
  padding-left: 40px;
  
}
#paper{
  padding-left: 40px;
}
</style>
</head>
<body>

<div class="container" id="header">
    <div class="row">
      <h1>统一建模语言理论测试</h1>
     </div>
     <form>
     <table> 
  <tr>
    <th>考试科目：统一建模语言</th>
    <th>时间：100分钟</th>
    <th>得分：100</th>
  </tr>
  <tr>
    <td>
    <label for="班级">班级：</label>
    <input type="班级" class="form-control" id="班级" placeholder="Class">
    </td>
    <td><label for="ID">学号：</label>
    <input type="ID" class="form-control" id="ID" placeholder="ID number">
    </td>
    <td>
    <label for="name">姓名：</label>
    <input type="name" class="form-control" id="name" placeholder="name">
    </td>
  </tr>
</table>   
</form>
</div>
  
<div class="container" id="paper">
      <div class="row">
      <h2>一、填空题（每空5分，共20分）</h2>
      
        <div class="col-md-6">
        <form>
        <ol>
          <li>UML的中文全称是:
          <input type="text" class="form-control" id="part1_1" placeholder="统一建模语言">
          </li>
  
          <li>对象最突出的特征是：
            <input type="text" class="form-control" id="part1_2" placeholder="封装性">
            <input type="text" class="form-control" id="part1_2" placeholder="继承性">
            <input type="text" class="form-control" id="part1_2" placeholder="多态性">
          </li>
        </ol>
        </form>
    </div>
    </div>
    <div class="row">
      <h2>二、选择题(每题10分，共20分)</h2>
     
     <div class="row">
       <form>
      <ol>
        <li>UML与软件工程的关系是:<br>
          <input type="radio" name="answerA" value="A">A.UML就是软件工程<br>
          <input type="radio" name="answerB" value="B" checked>B.UML参与到软件开发过程的几个阶段<br>
          <input type="radio" name="answerC" value="C" >C.UML与软件工程无关<br>
          <input type="radio" name="answerD" value="D" >D.UML是软件工程的一部分<br>
        </li>
  
        <li>Java语言支持：<br>
          <input type="radio" name="answerA" value="A" checked>A.单继承<br>
          <input type="radio" name="answerB" value="B" >B.多继承<br>
          <input type="radio" name="answerC" value="C" >C.单继承和多继承都支持<br>
          <input type="radio" name="answerD" value="D" >D.单继承和多继承都不支持<br>
        </li>
      </ol>
      </form>
      </div>
      </div>
   <div class="row">
      <h2>三、多选题(每题10分，共20分)</h2>
     
     <div class="row">
       <form>
  <ol>
  <li>用例的粒度分为以下哪三种:<br>
    <input type="checkbox" name="answerA" value="A" checked>A.概述级<br>
    <input type="checkbox" name="answerB" value="B" checked>B.需求级<br>
    <input type="checkbox" name="answerC" value="C" >C.用户目标级<br>
    <input type="checkbox" name="answerD" value="D" checked>D.子功能级<br>
  </li>
  
  <li>类图由以下哪三部分组成：<br>
    <input type="checkbox" name="answerA" value="A" checked>A.名称（Name）<br>
    <input type="checkbox" name="answerB" value="B" checked>B.多继承（Attribute）<br>
    <input type="checkbox" name="answerC" value="C" checked>C.操作（Operation）<br>
    <input type="checkbox" name="answerD" value="D" >D.方法（Function）<br>
  </li>
  </ol>
  </form>
  </div>
  </div>
 
  <div class="row">
      <h2>四、判断题（每题10分，共20分）</h2>
          
  <div class="col-md-6">
  <form>
  <ol>
  <li>用例图只是用于和客户交流和沟通的，用于确定需求。
    <input type="radio" name="answer_right" value="right" >√
    <input type="radio" name="answer_wrong" value="wrong" checked>×<br>
    </li>
  
  <li>在状态图中，终止状态在一个状态图中允许由任意多个。
    <input type="radio" name="answer_right" value="A" checked>√
    <input type="radio" name="answer_wrong" value="B" >×<br>
  </li>
  </ol>
  </form>
  </div>
  </div>

  <div class="row">
      <h2>五、简答题（每题20分，共20分）</h2>
     
     
  <div class="col-md-6">
  <form>
  <ol>
  <li>简述什么是模型以及模型的表现形式？<br>
    <textarea name="answer" id="" cols="70" rows="10"></textarea>

  </li>
  </ol>
  </form>
  
</div>
</div>
<button type="submit" class="btn btn-default">计算分数</button>
</div>    
</body>
</html>
