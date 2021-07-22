# 2017年度プログラミング応用期末テスト回答例

## 問1
1. アドレス

2. 4

3. - ポインタ演算の際の計算単位
   - 間接参照の際の参照領域

4. 配列の先頭アドレスを示すポインタとなる

5. ポインタ（アドレスが指し示す領域に格納されている値）を読み書き（参照）すること

6. - ポインタ[整数]
   - *(ポインタ + 整数)

7. アドレス

8. 数値

9. *a

## 問2
(a) ![a](/2017/img/q2a.png)

(b)
```C
// 要素数が51のchar型の配列を宣言
char (*b)[51]

// 50バイト先の値を取得する
(*b)[50]
```

## 問3
(a)

1. `sum += node -> data`
2. `node -> next`

(b)

3. `0`
4. `1`
5. `node -> next`

(c)

6. `node`
7. `n`
8. `p -> next`

## 問4
(a)
```C
struct HDR1 {
    int hdr1_size;
    char file_name[20];
    unsigned short reserve[12];
    int hdr2_size;
    int file_size;
};
```

(b) SAGIYAMA

(c)

(d)
