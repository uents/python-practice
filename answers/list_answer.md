## 問題1: リストの要素の合計

``` python
numbers = [3, 4, 2, 5, 1]
total = 0

for num in numbers:
    total += num

print('合計:', total)
```

## 問題2: リストの最大値

``` python
numbers = [5, 9, 2, 1, 7, 4, 3]
max_value = numbers[0]

for num in numbers:
    if num > max_value:
        max_value = num

print('最大値:', max_value)
```

## 問題3: リストの要素の平均値

``` python
numbers = [4, 2, 3, 6, 1, 5]

total = 0

for num in numbers:
    total += num

average = total / len(numbers)
print('平均値:', average)
```

## 問題4: 偶数を探す

``` python
numbers = [1, 4, 7, 2, 6, 3, 8]
even_numbers = []

for num in numbers:
    if num % 2 == 0:
        even_numbers.append(num)

print('偶数のリスト:', even_numbers)
```

## 問題5: 文字列の検索

``` python
words = ['apple', 'banana', 'grapefruit', 'orange']
search_term = 'an'
matching_words = []

# プログラムを書く

print("条件に合う文字列:", matching_words)
```

## 問題6: リストを扱う関数
省略