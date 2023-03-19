We can access to the datebase from many ways with a graphical interface or writtion your own custume app.

For this example we'll use PostgreSQL interative terminal calld **psql**

To use it we will type the next command on our terminal/bash.

```sh
psql mydb
```
Where **psql** is the interactive terminal program and **mydb** is the name of our databe that we created before.

You can confirm that you are using the terminal program if your bash look like this:

```console
mydb=#
```

Or

```console
mydb=>
```

In this point we can start using psql program, let's see some examples.

```console
mydb=> SELECT version();
```

  The outpu looks like this:
  
  ```console
 PostgreSQL 14.6 (Ubuntu 14.6-0ubuntu0.22.04.1) on x86_64-pc-linux-gnu, compiled by gcc (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0, 64-bit
(1 row)

 ```
 
 Now let's move to the next secction.
  
