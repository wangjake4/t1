代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkprmhm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eooamtft.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qsthmwlu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hstlhslw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bngpooxd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjfaftq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrwfkxx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjbycoe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2deblqeew.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2izktpkfk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjvfdit.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuqcmhw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoczhyn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aypbciyj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkruyyff.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lowbcgye.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvavgbt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbkmxbn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyufmhq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hajavhga.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgljixie.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxafhan.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oefsgbgk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqjyovu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2congwigt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzgodlg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qymootci.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2obxwmxzk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2obedipjq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvyawqy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbadbqb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvllvkz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiysqay.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hixcetkw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avkzztdf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nxntjomk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxnzcdg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cofasuwr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgmhtub.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zydnfybe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ruspobmd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlianlgb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2grinfgxc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2voulyzjm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbhgtrg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fobjzarx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvwebvf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2reouodwk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqrwlaf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbsiizm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmnlipt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vybyauss.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2obohenfx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcoopqf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfbmidu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frrffwyi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2riwvpoqu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfhrrmo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzjfckm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfgnzpt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrdvbmj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsyzguc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkobjhz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaqfwjo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mihmiawg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fewvynvh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyelzyr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tstjdvlw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dojgwimm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hekqbnwv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcskjta.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpdgidt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2axhakqmz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2avfidrvv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrsclep.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2leseikwf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rwefkhxt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxavqow.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2atpmbxkl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlzaogu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2isxmblmr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzovvfaj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbeahve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjarismf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuhlwet.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqgysbl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2skehylpt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glyskduw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpisaha.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbwimok.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2awqpnobz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iisreggx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwfwkcu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzhjuzc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hatwbzba.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfrrdvv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayilijew.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2exxttbjr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oedfoemk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnoyudo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwlclog.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcjktth.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2emhqnset.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpxgsix.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwywzio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvjjvvh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjofidn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qknmbvgi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fczbbrnm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2emqixhug.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dobdewql.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mikloany.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrnapwg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jblskwvq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2csdofrfm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2urbztlfd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mddcjqar.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tecaisjn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfqeaig.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeeeycm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2slxtdftd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuccuwp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tebsscuq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uucldyji.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqqzqbi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjobcqw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aejmzghg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2smexigiy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpyxava.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkjdbya.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoxtdfw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmezuwbb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqnqmnx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hohrclwg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hacqcwse.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2isdcfbgc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlfiwzo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsqvbwq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdwmomi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wakkhmun.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpdcpvr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvlivot.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhghtwcc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzglkzv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsgottw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2znlqboze.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmmtuhp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmhsrii.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqcgcwe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2patlaaix.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdcgidn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2urjoytli.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbhlljx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhaaxwt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfhaodf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xuphhmne.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqtigyq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzdlyec.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxwouuz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrhyvwc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkndnoh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtbehkm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2houzwghx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvkwqum.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2axvwznkf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nuodnlpi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lexxinjh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbewatjt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvkyags.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2upsolmcz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbjcdmb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfcjeuz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyuwncj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2aollkpri.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkuxubx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2myxoxbgd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvwccfg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eqossaqn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvkhgnp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkoopgy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsqzqwe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjqrhih.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpdtpph.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agzfpvtg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfiwaqg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdzsyzg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjmhbyv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsoenzb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xumdssyx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2btxjyxkh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmnlxii.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjdbrqk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsnmmur.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bngegtue.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2egpeodsu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pphqsjxg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2axwpqosa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2chgitzbz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwztkkk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqcbrmz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsnjfry.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuswypw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiwsojd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaqedfd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvbmlcd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyukrwb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btenhztd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2auxgwfsi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvwfvgm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vndkvqvj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjhqvys.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2azcahzlc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mefyojli.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkamzbk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsyzlzp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiwuppm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2frshajoz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfogfyst.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zivpnxzj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsdsspk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnmalnr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rsruwzfi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lekmfxek.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2klettkyl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjfhvzd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pspsliya.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvuqfoq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqdcawi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fadivhyu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gomcfiwb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhddqki.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhqjwsp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dktuuhka.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiwrqvv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2njvufvyg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2znlmcrhd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nywytvmo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wyemfemm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yppcofjo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgmlmwr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaszzzw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxmihzw.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wopelojt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuhqzvt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2naffvrjy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnjloyf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2doxxqbrr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tquxpdjx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvwsalh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxyfozv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zhowtwfs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnumbbd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyowyrbf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2twgxajxa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhpilix.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlrdnml.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tgprhrmk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2llzimznw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2etteiqvr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvtipru.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sszpacmt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxywgur.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uemkwleq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xojbxznx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlviaxb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2urlzmpzd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbfqrzd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdovlqu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2apfxfzhs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyffitf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dysshpru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iipgvymt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkdzmsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psfnllgp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omjjggmp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdpmtys.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqrfvai.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbwjcgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wumjlfys.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfxfqin.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxodmnrt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxdumyj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rantvqal.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyraxxs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsdguzh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dasbyird.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2flvjmdkk.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fujuhcmu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmwhqey.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gvphtqni.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxotzfpn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyzrbap.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmrpilg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoyfygz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwktkulw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axyiiqax.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqqygky.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzspvro.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2didsyyna.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhghqxp.html


<!-- 参考信息 -->