<!--
 * @Author: zhangniannian
 * @Date: 2022-04-07 17:46:39
 * @LastEditors: zhangniannian
 * @LastEditTime: 2022-04-07 17:47:58
 * @Description: 请填写简介
-->
## 描述  

部署好本机的 docker 环境，使用 ppt 中的 dockerfile build 自己的环境，使用 readelf 工具，查看编译后的进程入口地址，在 dlv 调试工具中，使用断点功能找到代码位置，使用断点调试功能，查看 Go 的 runtime 的下列函数执行流程，使用 IDE 查看函数的调用方：  

- 必做：runqput，runqget，globrunqput，globrunqget  
- 选做：schedule，findrunnable，sysmon  
- 难度++课外作业：跟踪进程启动流程中的关键函数，rt0_go，需要汇编知识