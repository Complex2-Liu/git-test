# Test

这个仓库仅仅是为了测试 git 是如何工作的.

Commit A
New Commit A

Commit B: Commit A 的 hash 值为 e451e43fd1d763e2e0d00bd9b011511681bb4e06

Commit C: Commit C 的 hash 值为 7c29ec4c5a776c460cda7f50039b2f85a9780832

# 第一个结论

Commit A, B, C 都变成了孤儿,
被 push 到 remote 的是 New Commit A, B 和 C.
今天日期是 2022-01-11, 不知道过多久后 Commit A 会被垃圾回收.

---

开始第二轮测试.

Commit D
New Commit D

Commit E: Commit D 的 hash 值为 4bba6aa20844b7a855229a7b5065fcc4cdd04f48

Commit F: Commit E 的 hash 值为 e6ff50ff09507ff19764d3bfe91c56e3444d82ba, push 到 remote.
