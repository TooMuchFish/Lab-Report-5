# Name : Shaodong Shan
# Course: CSE 15L Lab 5
>Date: June 1, 2022
>
>This is my fifth lab report, welcome.
>
![welcome](https://user-images.githubusercontent.com/103075501/162642398-9902f982-4aa5-4e33-816d-d0eba4ceace9.jpeg)
>
# Choose TWO tests from the 652 tests in result.txt files
> By using the remote account in the terminal of my VScode, I used the command `diff` to compare the results that we get from running the `bash script.sh` on the both of those implementations.
> By log in with `ssh ieng6`, we can access the remote service, and we can use the following command to run it in terminal.

___
```
diff m3/results.txt markdown-parser/results.txt"
```

> I renamed my own implementation `markdown-parser` to `m3`.
> And I cloned professor implementation `markdown-parser`.
> Here is the output after I run the command to compare them in my terminal.

![result](resulttxt.png)


# Test 1.

> As shown in the screenshot below, we can see the difference of actual output is existing in line 270.
![test1](test1.png)

> As shown in the screenshot below, we can find the testing correspond to the markdown file: 
![code1](test1code.png)

>Link to the markdown file
>
>[links md file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/22.md)
>
> We can use the command `cat` to check the content in the 22.md line.
![cat1](cat1.png)

> The expecting output by using [the CommonMark demo site](https://spec.commonmark.org/dingus/).
![output1](test1output.png)
>
![code](code.png)
>
# Test 2.

> As shown in the screenshot below, we can see the difference of actual output is existing in line 492.
![test2](test2.png)

> As shown in the screenshot below, we can find the testing correspond to the markdown file: 
![code2](test2code.png)

> Link to the makedown file
> 
> [link md file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/32.md)
> 
> We can use the command `cat` to check the content in the 32.md line.
![cat2](cat2.png)

> The expecting output by using [the CommonMark demo site](https://spec.commonmark.org/dingus/).
![output2](test2output.png)
>
![code](code.png)
