```BASH
git restore .
```
<p>
     با استفاده از این دستور تمام تغییرات به کامیت قبلی برمیگردن و تغییرات کامیت نشده بازگردانده میشن 
</p>

```BASH
git reset <hash code to revert to it changes>
```
<p>
بازگرداندن تغییرات کامیت شده به حالت unstaged از طریق کد هش اون تغییراتی میخاییم با اون ست بشه
</p>

---
 
```BASH
git reset --hard <hash>
```
<p>
     با استفاده از این دستور تمام تغییرات به کامیت هش شده برمیگرده
</p>

---

```BASH
git revert <hash>
```
<p>
     با استفاده از این دستور تمام تغییرات به کامیت هش شده برمیگرده
</p>

---

```BASH
git reflog
```
<p>
     با استفاده از این دستور تمام تغییرات فایل های حذف شده را بازیابی کرد
</p>

---


```BASH
git reset HEAD~2
```
<p>
    با استفاده از این دستور تمام تغییرات به ۲ کامیت را برمیگرداند و از حالت استیج خارج میکنه
</p>

---

```BASH
git checkout feature-branch
git cherry-pick <hash>
git checkout master
git reset HEAD~1 --hard
```
<p>
   با استفاده از این دستور تمام تغییرات کامیت شده را به برنچ جدید انتقال میدیم
</p>

```BASH
git diff
git diff --staged | --cached
```
<p>
     با استفاده از این دستور تمام تغییرات مقایسه میشود . چه داخل خود ورکینگ دایرکتوری چه حالت استیجینگ 
</p>

---

```BASH
lsof -t -i:3000
sudo kill -9 $process_id
```
<p>
     با استفاده از این دستور پورت ۳۰۰۰ که ران شده رو میبینیم و با پراسس ایدی اش متوقف کنیم 
</p>

---
