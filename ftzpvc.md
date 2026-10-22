代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2axcduoid.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuehtpu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zygbdxoh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrjiyna.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxunppxv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sltzeimc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2htklpmoz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqgmvjp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwkacfx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sejtkxsv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lckdfocc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2adobbgxv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2auuqfwja.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlldvyu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiejhlwn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvjbhaw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oifjakni.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2buqkgurw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2stwotang.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsulget.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamdosix.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyroxwo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrxgdtj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2orogsime.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdjwyod.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihacmwgf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkuvmjd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbcsxsc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnuchgk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqgjoia.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzthxgk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2swkkeonz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqlsmwk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlpcdre.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlibqwz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyssgue.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjdmdgs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zatdszdr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfisxeo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sphlbbvk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwmkwty.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtfkpjl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcdrohd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrsnxpf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sesebvoc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qfahesye.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2glnjqdix.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zskdmmwk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnrlisn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnddooy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2znsublxa.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzwfjdo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxwjjrm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdswgox.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsljsiy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hxprdwxa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hgykahse.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zywlhrkf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmictwj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvpaywi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxtmmjb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tnieboqw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ueesqwgh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2awsnezdl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nabsrylw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adivnfpj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrlktol.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tckjbhxr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmrgfwe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjmotgp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btfsbjyt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdrcczb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2navzdavb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwtfmax.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ikirccju.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpyaadd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsxzjkt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlolnzn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxsychy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyftqlwl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2buerxilg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvwhinw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiyofvn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cyumbdzs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2osdqillg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbpxyav.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubpzlyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inkmubuu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmezmxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfbbheu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhyhixx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2buerpkzl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsuphvb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdtvzwa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvphramg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwxxaut.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xascqnnc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nropdxgm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2abbdqxri.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaaclyk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brqkzupe.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hyungdff.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crdoojlv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpuvjul.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgdmgbk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jtppafik.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxmphup.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoirlpr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgfgzlm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhsikzf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxkhfnp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjaokfl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhxufyg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqqmhrw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrzucnn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoigbdb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkhcvke.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjryqnb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lulvqvqa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jscaoyui.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvpstug.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgfergq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgpbltj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czchjxvt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tstozoxl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjabtme.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjuqhet.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pognvzus.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2udkdmqmi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnhfzak.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eobztbjl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2raygfcuk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2juhrveok.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mznarpsp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fheuquzx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bamecqnq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eipbklks.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2thptwxui.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrjfpqt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eezoyypa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkmmhjq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbqborj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrgyiis.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lxglmtks.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtdlllk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2scizwbmg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfrknaf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zvolwxgj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qilezkfb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcjgarb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfhwtwq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmehtqqu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpaqnsy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnbdvom.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpckgqf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mokeisyk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uznkzpxo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuybtoa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfcheot.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxncumm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpazpph.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2guaoypdf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfczgrq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kuymdgso.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxhlvjc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kygjvpyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2odgadjed.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcvqklc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwscfdi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnqsuqv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2acpourhm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsnqosc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2epgaalmc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqednafc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rivmjrzn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2thnpense.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrixbnvs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dypukind.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cadlwnmz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2daqmxuoc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsspwrh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxbitfg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2psaegeox.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtcsxrg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjejesb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rchhftsg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjftbhk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmvxmmr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjkbrlb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxxmeep.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiwccai.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cplmujwi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmxcbac.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mksjhduz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2inkchjbx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaslnua.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqnhzsa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzfcark.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phpudylv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwvkwpf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnyplvi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anuwzmmg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaqlvjr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zesppvzc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2utnhlgvv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuzryuh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyadrdx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2viuonylu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgwslnb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkznomp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fcghhhrk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxyrupy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsekoxk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnuqrlr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoxwwfg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2shgcnjpu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ffretezd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdjuenu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzofhtn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oraiuecw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uveprjzw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2teygiask.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdgmvtb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxfbizz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtxmbxc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoeyvvx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aciytjbs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiuqndd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwmsofh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzohjbdp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqlavaf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdziqlm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtfiljh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsenthq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxfksol.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iytgsurg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcaqttd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2onottaiy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyspfzd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpaaiuk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pyntgqdk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpfybhm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpsymgf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpgtoxa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnzeqkn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsqglvh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnhovjl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ausycpvt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kghhslkq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ihprdbdt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuzeqkd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjfkaat.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwdfkoa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzqsioi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjowhgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjqbjiw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmvrwei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzenrrux.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olzytmjf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2omnxenbj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khrjxaun.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fthggnwa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbqpltx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2crjeygfa.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2phgourag.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vndcobrb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbahmaz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rycnydwb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxtccyx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wegvkvkc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmhtpzl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqlimuk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfcpkbe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzfphty.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdurggpj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmikafr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mjujrtgq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxzzcaj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfdwbtz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bntbvanc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfukjme.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eulwlmhr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpughak.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaqnwlj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbadggx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmstubk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhboqzg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oahysbal.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rknvpwvr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2twvnxozz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2upjqgbkv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dngawtkx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwncthr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpoirjt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2czadvzxp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jueabzkd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifidomcw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxijksif.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsmafpj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2emosumgc.html


<!-- 参考信息 -->