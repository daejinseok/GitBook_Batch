# 기본 파라메터

batch파일 뒤에 전달된 파라메터는 %1, %2 ~ %9로 사용 가능하며, 배치파일 자체는 %0로 전달 됩니다.

```batch
:: --- basic.bat ---
echo %0 %1 %2 %3 %9
```

```cmd
> basic.bat 1 2 3
basic 1 2 3
```

# 출처

http://www.microsoft.com/resources/documentation/windows/xp/all/proddocs/en-us/percent.mspx?mfr=true
