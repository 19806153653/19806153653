
1.帮助开发人员编写代码,提升质量、减少bug。
2.提升反馈速度,减少重复工作,提高开发效率。
3.保证你最后的代码修改不会破坏之前代码的功能。
4.让代码维护更容易。
5.有助于改进代码质量和设计。  

package wxc01;

public class BubbleSortTest {
	public static void main(String[] args) {

		int[] arr = new int[]{-12,3,2,34,5,8,1};
		//冒泡排序
		for(int i = 0;i < arr.length-1;i++){
		for(int j = 0;j <arr.length-1-i;j++){
		if(arr[j] >arr[j+1]){
		int temp = arr[j];
	    arr[j] = arr[j+1];
		arr[j+1] = temp;
		}
		}
}
		//遍历
		for (int i = 0; i < arr.length; i++) {
			System.out.println(arr[i]+"\t");
	    }

	}
}  

-  在Java编写冒泡排序中，我使用了-12,3,2,34,5,8,1几个测试用例，最后输出结果排序即为：-12，1,2,3,5，8,34。   
