# GRUB problem

### <a name="objectifs"></a> objectifs


> Solve the problem without any data loss!


First, a photo illustrating the problem :


```shell
error: unknown filesystem.
grub rescue>
```


> [!IMPORTANT]
> Use the `keyboard ` to type the code that follows.


</p>
<h3 align="center">Solution</h3>
<p align="center">
</p>

> [!TIP]
> Ensure that your typing is accurate.

Type the following commands in sequence (you may not see anything during the process) :

```shell
set root=(hd0,gpt8) #for my situation i have "gpt8"
set prefix=(hd0,gpt8)/boot/grub
insmod normal
normal
```

> [!NOTE]
> for :
Enter the following command to view all partitions:
```
ls
```
You need to test each partition until you find the one that does not return the message ‘unknown filesystem’. Try running the following command for each partition :
```
ls (hd0,msdosX)/
or
ls (hd0,gptX)/ #Replace X with the partition number
```


> [!WARNING]
> There is always a possibility of error; therefore, we assume no responsibility for it.

</p>
<h3 align="center">Copyright © 2026</h3>
<p align="center">
</p>

> Thank you for contacting us here. If you have any feedback, please feel free to reach out to us at:
tknohamzacontact@gmail.com
Don’t forget to follow us on:
<a href="https://facebook.com/tknohamza">Facebook</a>, <a href="https://instagram.com/r/tknohamza">Instagram</a>, <a href="https://twitter.com/tknohamza">Twitter</a>, <a href="https://t.me/tknohamzachannel">Telegram</a>
