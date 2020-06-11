# Python.Pandas

## Series
  - 一維的陣列資料結構
  - 可放整數、浮點數、字串、Python物件(list, dist)、Numpy的ndarray、純量...
  - pandas.Series(data=None, index=None, dtype=None, name=None, options,...))

## DataFrame
  - 二維的陣列資料結構
  - 可放整數、浮點數、字串、Python物件(list, dist)、Numpy的ndarray、純量...
  - pandas.DataFrame(data=None, index=None, dtype=None, name=None)

## 資料分析與處理
1. 索引參照屬性
    - at : 使用索引和欄位的內容，取得/設定單一元素內容或陣列內容
    - iat : 使用索引和欄位的編號，取得/設定單一元素內容
    - loc : 使用索引和欄位的內容，取得/設定整個列或欄位的資料或陣列內容
    - iloc : 使用索引和欄位的編號，取得/設定整個列或欄位的資料
2. 直接索引
3. 四則運算方法
    - add() : 加法運算
    - sub() : 減法運算
    - mul() : 乘法運算
    - div() : 除法運算
    - Nan的運算
 4. 邏輯運算方法
    - gt()、lt() : 大於、小於運算
    - ge()、le() : 大於或等於、小於或等於運算
    - eq()、ne() : 等於、不等於運算
5. Numpy的函數應用在Pandas
6. NaN的處理
    - dropna() : 將Nan刪除，然後傳回新的Series或DataFrame物件
    - fillna(value) : 將Nan由特定的value取代，然後傳回新的Series或DataFrame物件
    - isna() : 判斷是否為Nan，如果是傳回True，如果否傳回False
    - notna() : 判斷是否為Nan，如果是傳回False，如果否傳回True
7. 統計函數
    - cummax(axis=None): 傳回指定軸累積的最大值
    - cummin(axis=None): 傳回指定軸累積的最小值
    - cumsum(axis=None): 傳回指定軸累積的總和
    - max(axis=None): 傳回指定軸的最大值
    - min(axis=None): 傳回指定軸的最小值
    - sum(axis=None): 傳回指定軸的總和
    - mean(axis=None): 傳回指定軸的平均數
    - median(axis=None): 傳回指定軸的中位數
    - std(axis=None): 傳回指定軸的標準差

## 檔案的輸入與輸出
    - 寫入csv格式檔案: to_csv(path=None, sep=',', header=True, encoding=None)
    - 讀取csv格式檔案: read_csv(path=None, sep=',', header=True, index_col=None, names=None, encoding=None, userows=None, usecols=None)
    - 讀取excel檔案: read_excel(fn, 'Sheet1')
    - 寫入excel檔案: to_excel(fn, sheet_name='xx', index=False, startrow=xx, startcol=xx)

## Pandas繪圖
    - 最常使用plot()，使用時需要import matplotlib.pyplot
    - plot(x=None, y=None, kind='xx', title=None, legend=True, rot=None) #kind=line, bar, barh, host, boxscatter. #rot旋轉刻度
    
## 時間序列(Time Series)
