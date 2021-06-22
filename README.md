# ansible_hello

cloneしてすぐ動かせるansible playbookプロジェクトのスケルトン。

なんども同じようなコードを書いてることに気づいたので、githubにあげとく。


# 実行例

```
$ ansible-playbook hello.yml
PLAY [hello] *****************************************************************************************************

TASK [debug] *****************************************************************************************************
ok: [localhost] =>
  msg: Hello from localhost

PLAY RECAP *******************************************************************************************************
localhost                  : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
```
