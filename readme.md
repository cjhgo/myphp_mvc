#architecture
```php
index.php
	connection.php
	set variable:controller,action
	layout.php
		routes.php
		--->call(controller,action)
			+ pagescontroller
				-- call(pages,home)
				-- call(pages,error)
			+ postscontroller
				--call(posts,index)
				--call(posts,show)			
```

reference[https://github.com/Raindal/php_mvc](https://github.com/Raindal/php_mvc)