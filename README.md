java数据结构
一、排序
1.冒泡排序
public void bubbleSort(int a[]) {
		for (int j = a.length; j > 1; j--) {
			for (int i = 0; i < j; i++) {
				if (a[i] > a[i + 1]) {
					swap(a, i, i + 1);
				}
			}
		}
	}
2.
