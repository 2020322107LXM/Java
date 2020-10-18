## G202 2020322107 李雪明 
# Java
# 实验一
## 实验内容：用四个类PC、CPU、HardDisk、Test描述计算机CPU的速度和硬盘容量，Test是主类。
# 实验方法：
## 主类main方法中
                 创建CPU对象cpu，cpu将自己的speed设置为2200，新创id表示名称
                 创建HardDisk对象disk，将自己的amount设置为200，大小为200，新创type表示类型
                 创建PC对象pc
                 pc调用setCPU（CPU c）方法，实参为cpu，调用setHardDisk（HardDisk h）方法，实参为disk，调用show（）方法
## 公共类 CPU 
               private int speed;
               private string  id;
               int getSpeed（）{
                return speed；} 
               public void setSpeed（int speed）{
                this.speed = speed; }
               string getid () {
                return id;} 
               public void setid(string id) {
                this.id = id}           
## 公共类HardDisk 
               private int amount; 
               private string type; 
               int getamount（）{
                return amount; } 
               public void setamount（int amount）{
                this.m = m; }
               string gettype（）{
                return type; } 
               public void settype(string type）{
                this.type = type; }
##  PC公共类PC 
               void setHardDisk（HardDisk HD）{
                this.HD = HD; } 
               void show（）{}
               System.out.println（“ cpu速度：” + cpu.getSpeed（））; 
               System.out.println（“ cpuID：” + cpu.getid（））; 
               System.out.println（“硬盘容量：” + HD.getAmount（））;
               System.out.println（“硬盘类型：” + HD.gettype（））;

## 核心方法主类
               公共静态void main（字符串[] args）
               CPU cpu = new CPU（）;
               硬盘HD =新的HardDisk（）;
               cpu.setSpeed（2200）;
               HD.setAmount（200）; 
               cpu.setid（骁龙980）; 
               HD.settype（机械硬盘）; 
               PC pc =新PC（）;
               pc.setCPU（cpu）;
               pc.setHardDisk（HD）; 
                                                      
# 实验结果 cpu速度：2200  硬盘容量：200  cpu价格：500  硬盘大小：30   
      了解对象的定义与使用，体验private的用法
