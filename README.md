# caches

данный репазитория была создана для выполнения домашнего задания для курса GOLANG-NINJA

данная репазитория позволяет записывать значение в кэш в виде Key-value
    
```go

	cache := cache.New()

	cache.Set("userId", 42)
	userId := cache.Get("userId")

	fmt.Println(userId)

	cache.Delete("userId")
	userId = cache.Get("userId")

	fmt.Println(userId)

```

    в этой директории находится 3 мемтода а так же инициалищация 

    Set(key string, value any)
    Get(key string) any
    Delete(key string)
    New() *cache