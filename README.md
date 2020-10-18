# Java
# 实验一
# 实验内容：用类描述计算机中的cpu模型，速度和硬盘的容量，要求java应用程序又4个类，名字分别为PC，CPU，HardDis，Test，把测试设为主类，掌握构造方法，实现定义属性的修饰符近似。
# 实验方法：
# main方法中创造一个cpu对象，cpu =cpu,cpu中的速度设置为2200，再加入一个构造方法id，把id设为骁龙980.
# CPU公共类CPU {公共类CPU {private int speed;
                         private string  id;
                         int getSpeed（）{return speed；} 
                         public void setSpeed（int speed）{this.speed = speed; }
                         string getid () {return id;} 
                         public void setid(string id) {this.id = id}           
main方法中创造一个HardDisk对象，HD =HD,HD中的amount设置为200，再加入一个构造方法type，把type设为机械硬盘.
HardDisk公共类HardDisk {公共类HardDisk {private int amount; 
                                        private string type; 
                                        int getamount（）{return amount; } 
                                        public void setamount（int amount）{this.m = m; }
                                         string gettype（）{return type; } 
                                        public void settype(string type）{this.type = type; }
 main 方法创建一个pc对象pc
 PC公共类PC {CPU cpu; HardDisk HD；void setCPU（CPU cpu）{this.cpu = cpu; } 
                                  void setHardDisk（HardDisk HD）{this.HD = HD; } 
                                  void show（）{
                                  System.out.println（“ cpu速度：” + cpu.getSpeed（））; 
                                  System.out.println（“ cpu名字：” + cpu.getid（））; 
                                  System.out.println（“硬盘容量：” + HD.getAmount（））;
                                  System.out.println（“硬盘类型：” + HD.gettype（））;
}
核心方法主类`公共类测试{公共静态void main（字符串[] args）CPU cpu = new CPU（）; 硬盘HD =新的HardDisk（）;
                                                      cpu.setSpeed（2200）; HD.setAmount（200）; 
                                                      cpu.setid（骁龙980）; HD.settype（机械硬盘）; 
                                                      PC pc =新PC（）;
                                                      pc.setCPU（cpu）; pc.setHardDisk（HD）; 
                                                      
实验结果cpu速度：2200硬盘容量：200 cpu价格：500硬盘大小：30   
感想：了解对象的定义与使用，体验private的用法
