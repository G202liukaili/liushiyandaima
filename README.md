Describe CPU
=
## 1.实验内容
>1.用类描述计算机中的CPU的速度和硬盘的容量。

## 2.实验要求
* a.要求Java应用程序有4个类，名字分别是PC、CPU、HardDisk和Test，其中Test是主类；(基本要求)
* b.类中定义不少于两个构造方法；
* c.每个类定义不少于两个属性，切属性的类型应该多样化；
* d.尝试定义属性的修饰符多样化，类中定义方法操作属性，避免直接通过“类对象.属性”的形式访问属性值；且定义方法内有合理的逻辑判断；
* e.尝试把本次实验的多个类放置在不同的包中，体会修饰符private的用法;

## 3.实验设计

1.设置cpu类，给cpu对象定义speed、name方法，并且将cpu类放在computer_lk1包中。

	package computer_lk1;
	public class cpu {
	public int speed;

	public String name;
	
2.其他类（pc、HardDisk、Test）放置在另一个包computer_lkl中。Test是主类涉及调用cpu类，所以需导入cpu类所在的包。<br/>	
		
	package computer_lkl;
	import computer_lk1.cpu;
	public class test {
	public static void main(String[] args){

## 4.重要代码
	
