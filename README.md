# MiniAxios
mini promise based http client for the browser and node.js


1. 发送请求（实现最基本的发送请求功能）
   1. 实现两种调用方法
      1. 函数式调用：axios({})
      2. 对象式调用：axios.get()

2. 请求原理（request ➡️ dispatchRequest ➡️ adapter）
3. 拦截器
   1. 请求拦截器：hanlers、unshift
   2. 响应拦截器：handlers、shift