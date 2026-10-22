代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cgawcwkv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jskgkzpr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfifcvi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zveykbye.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2okdjmmsk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwqcbab.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dlralfde.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuihstt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrjriux.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeuawkt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2coikjbvu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiiyysn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhdazry.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tllmjibh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxglmzlw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuqnxsw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqepadt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxluchtp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nntfddej.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpjxrbj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsydhon.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjshzbt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgppaia.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zctwmqte.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiqgshs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdubqtm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qifsxszz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmptdlzn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyekqjn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snadiwwl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdgcnvb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgltmoat.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2crzfrsho.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2poyosedn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2brpknmbr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxdwlgk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tqomgtpf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgmvqpb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjclgtc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kepcyvib.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrcpxfs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmbhntb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vczdyvtk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxcoiuz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkstcoay.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyylucz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2atmmsntd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fagdrvdz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsrhfph.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2poigpbks.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2quswupvd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmakgku.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mftrweqb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmbemos.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rzauwnwd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqppubc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2exswwxci.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjczyyi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbicykh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcbevbh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxbmvtc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2aluiqqyl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjugiwi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2exsoriod.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zriuferz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrhldfm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xksyphtu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pnptqnja.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2owswmter.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpxcmzu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjfbyhh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhrwleu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmjecol.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itxobmwm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlshkth.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbawzaz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzxbicz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgyvdpb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaihovb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqdgffp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2alecyvvw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2acdvvadt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxojkum.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuxvkmj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tolddwbd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxsvyhy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snqoyhkv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmmdpqx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnuzlyk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgxoepc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygbqhzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wigjafwn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvwsosc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpmkcqk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2laqfvyhj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vximtaam.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzkmglj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvycntgy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2msebxpbm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfjymkj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xvthxdkr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aayynvdo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dliumhpd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjyabwu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzvahxj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efclabhn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijiwkk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xapmgcqh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jetqnssw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xoonbuhh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoaumlm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2isbgwsle.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbmfdln.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhxslhj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhdzmvr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dtynpzmt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vnehtpxk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsoxekh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlulwvn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzopdex.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ucelghay.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dafzshxn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjlkekb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xhezuhkv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cantiqkn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2idmbrhmi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwhuzyw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uysuqwvf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbbzcju.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2spyhgxkg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vihaswui.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvwjnkz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhcdkko.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqgtsih.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewucjcal.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwalbn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifktybux.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2aybwdcuf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2flzegkzq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2akbwrmvj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnvkyxx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlygdxjs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cikfncxj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxptgti.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuyuzyo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2szbrdpgx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2esskpwxe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hnatsczi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uazkfucv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2btduatel.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2penmjpec.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlafbyv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbzggpe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2inhrxuxy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qfenvwcv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbhwbjc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ophxamuz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dndrhgrg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwendrd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qafiwcuu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbaohil.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlyqkbi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huljupbq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sqatxtzd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdfhjzc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrbfgwb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gcazufdc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2octvfnwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uatbwyvi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hovizsyz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tcahmgnx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzoyjji.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpghcon.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzgcqzm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmcakmw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iaonrkfl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2suosblwn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaifzvb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oymialhm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtchckz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dduaisby.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgaozo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmxnppb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bigotiru.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2snwsuhew.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uivmotjr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvcpbok.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfwybfh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2stsadwzp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hviixgwx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgcamte.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzbfqyd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isbmospp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxksxdby.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpykmsod.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkasupw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtderdy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgtlgrm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2osmaxuem.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nyskvyew.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ocipiugu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2axpflyii.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdmahlq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2omnbkcbe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhmhemb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oclxfjhc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeixrrk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yenooxtg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vggwmyfv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2akefxblo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvmdzjn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhsvvhj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2htjkguaz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbumuyfx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrbnglo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuponfe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkiumte.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vexwehvf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcojilq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvgzhhy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkkdlvz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tofmndfs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2npfdqbgs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ceepcmyi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdtqskc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqlgday.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ealxpcyk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2etcwnljd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyqhxpa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrjjqot.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvgwzsq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzfydln.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgkqems.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2htxxvsnu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbuwequ.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqexanp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnxziif.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gbryldcy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdwbbzr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxerpcm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2txsvoeyu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnqbxua.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmgwvza.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrfvvxt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2chglfqzh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqjrynt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlxroni.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scetkjrw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlnwwcj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoanhwf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxjkeii.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbobriy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2krwvpbbc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2clqmpgmr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzuwydv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2njdjufuw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyxasod.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbxluac.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ygopvakb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxtzlqp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wztzvanp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dszxvgvi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxnbqmj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2falqwmfi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejgxvcv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rechoflf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvaibbx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbazjrif.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmooabxx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiuygrp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjefcve.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wieqiufs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejciwsxf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnrruan.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsfdaxl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pnplixxh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlrfvdg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bojhtcut.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxsyzsl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqxqphv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmduwls.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdkqzcw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaidmwt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibukzemo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrahnxhq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrxcmze.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqhszqf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsdgwhe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2atlvwhmb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qirzhywy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnlfmel.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sczuzguk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uepiossp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nttiqoec.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xyscemqn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cdufjwmc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbduohh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kcatvmjf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehiksn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvxclmj.html


<!-- 参考信息 -->