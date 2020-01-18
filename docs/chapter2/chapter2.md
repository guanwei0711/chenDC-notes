2.1 Bandpass and lowpass representation

![image](https://github.com/IamCalories/chenDC-notes/blob/master/docs/chapter2/res/2-1.png)



---名詞解釋---  

1. bandpass: 在某個頻帶通過訊號  
2. f0: 在bandpass signal中定義的一個中心頻率(與fc不同)  
3. fc(carrier): 通過傳送管道的載波(不一定在中心點, ex:電視訊號就在偏向左邊)
4. real signal: 波是觀察的到的(儀器能夠感測到)
5. spectrum: 頻譜，指的是頻帶上的形狀

---補充---  

1. 傅立葉轉換基本特性  
   (1) 在"time domain受限"的話在"frequency domain一定不能受限"。故，實際上左右兩側(f0+W, f0-W)訊號並非為0  
   (2) 在time domain是real signal[純實數]，在frequency dimain就會是Hermitian Symmetric[共軛複數]
   
   
![image]()  

---補充---  
1. 透過傅立葉轉換，得到正的頻率與負的頻率。但是，實際上是沒有負的頻率。  
   正、負頻率在time domain來說是一種相位。藉由負頻率的輔助，可以得知time domain的相位    
   (ex: sin和cos在time domain波形相同，但是相位不同。  
      sin和cos傅立葉轉換後在正的頻率相同，而負的頻率正好相反。)  
