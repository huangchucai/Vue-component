# 个人组件库

1. 分页组件 

### 分页组件使用

1.  应用pagination组件到对应的页面

2. 传参 

   ```javascript
   pageNumber =>  总页面数
   curNumber  =>  当前页面数
   showNumber =>  展示的模式（3，5）
   ```

3. 使用

   ```html
   <pagination :pageNumber="12" :curNumber="5" :showNumber="5"></pagination>
   <pagination :pageNumber="12" :curNumber="5" :showNumber="3"></pagination>
   ```

   ​
