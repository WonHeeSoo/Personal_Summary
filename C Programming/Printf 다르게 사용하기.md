# Printf 다르게 사용하기

일반적으로 printf는 이렇게 사용합니다.

```c
int32_t i32; // 32bit integer
i32 = 1004;
printf("me32 = %d\n", i32);
```

 `""`를 나눠서 사용 가능합니다.
```c
int32_t i32; // 32bit integer
i32 = 1004;
printf("me32 = %" "d" "\n", i32);
```

매크로를 이용해 사용 가능합니다.
```c
int32_t i32; // 32bit integer
i32 = 1004;
printf("me32 = %" PRId32 "\n", i32);
```