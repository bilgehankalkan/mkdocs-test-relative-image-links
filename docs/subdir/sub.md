# Markdown file in a sub-folder

## Wrong behaviour

### Relative path, same folder

This image **should** show up, but **doesn't**

![image alt text](sub.png)

`![image alt text](sub.png)`

*Linked image is in the same folder as this Markdown file.*

### Relative path, file in top-level folder

This image **should not** show up, but **does**

![image alt text](toplevel.png)

`![image alt text](toplevel.png)`

## Correct behaviour

### Absolute path, file in top-level folder

This absolute reference should show up, and does

![image alt text](/toplevel.png)

`![image alt text](/toplevel.png)`

### Absolute path, file in sub-level folder

This absolute reference should show up, and does

![image alt text](/subdir/sub.png)

`![image alt text](/subdir/sub.png)`