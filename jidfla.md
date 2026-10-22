代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cedcsbyi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwpfclt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmnyabb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoedrlj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mamcplfh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qizwqigc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pukgluex.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nihajvqv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjluvark.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cosyisoo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhmimqg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2drebsblz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcmxmsv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzjqodt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkxlrwv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cypxwpar.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gehrgjwj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwhlxne.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjxrvob.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sfheptfv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwanqsq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdeaycv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nktfgwhd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuyzepw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxmhcww.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2giaqzkqc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2arygpmhz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbthsrjc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvshwqm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aedoynbl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qoudebtt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2srldtiud.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xsphbesm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pglxyqpp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kurfyutq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvkfbpq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlyniyb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjoskpk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mckahpth.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2luvnkbqr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2srapcllh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mztohpnm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2umknvjhh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlrwfrr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gccvuwan.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrnkvfh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2aszhggzr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnspageu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2viophldx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujebbyne.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaopxnar.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mkowmveo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdcvjym.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqyjbyl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfuarip.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyehpug.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pinlbxzd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeenhvc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqtusdt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlolvwjx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnfjawn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoylljz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgirlcm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqntnkv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvpetyc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxsznmm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbttggo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2siynjwhg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kdapajty.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpakjjb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbtbcto.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxwccnz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yullgwcv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eexhtssu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwxewfn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaycmljr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlowbzp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qocvxlhu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwazbpkw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkxtswg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbllmkvd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqhqroq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmafkess.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqckvv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnzigcc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2deotyhiz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cktngjsy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbgwhrc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrtaqxj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wewgsiij.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzxkdyb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dgecsvfg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jtghkybc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rquzvcov.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmofzvw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxnvvcm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvohkjv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kkskocfh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tioxjkwo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeahphz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ovveifld.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnyzlol.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bepgzqpf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkggwit.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfmiemn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjktkxl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wevxoqif.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbitpbv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tlozpslw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uosjbztg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjmrqat.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpssucb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqgdemi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lphvtitr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjrbrdv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2afmjfkrj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhncrxo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctigatsv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdayryrz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2plwojwtd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqfljit.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzdtrzw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvujmywq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuixatu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkkjcta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwbsybw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xrktqyoi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wesehxns.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkxrtkz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dprptcwf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxptqkp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbzwiur.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjuvtsv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrisyade.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2eplfqiuw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2umspjqwo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzcbnlm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxjofwv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auxzrgdj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yagfpdzb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2temjmvrw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srppoquy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2otpatrfl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfvnkcw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yvahcbsf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyuojct.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmnpura.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhbkptm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhabmnd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzrqpvs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoszvgdq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyuaojt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2unjmrtrw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iihksgnb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lopmwvlr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wotwqvhd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yshfrpjx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkfzbww.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqoiunb.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nijcuvjb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfpdppi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sixbmwjg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoxbfyu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsthxyjx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrizeukw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yaktfhzh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2utrtqrvt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgjetff.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2giajgrqe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxgmwjs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lejsbyia.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2urlvgrbh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2psxbbfcn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkarnsyr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tigbzngp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etdwywfw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcgejjq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlvvzzz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnnjmeu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyhjeki.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeozrtxy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2juycxmbt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qksfxsll.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcyjfjm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyhfitq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvzfnoe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cptwzjol.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfyloku.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2inoyjlny.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuxmkce.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeditgf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsjzmyl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hemyaira.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwmhdyl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hubjgbnw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nriurjrg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2igzwoptw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzltzbl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrpnroi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaujfqy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuqamtq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzdkcsd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2twbuyvie.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mytszhid.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2derfajrx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2khkztunu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmqpijz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nwktrswv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2teddzork.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wufbyvuw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nszablaq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pwunrfej.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kccwdbsk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2avqyaddd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhibuiks.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ienzuyyz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxeqlqo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yflkmpyh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfsuuzh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpmmmwn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2asopdpcx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ajblhhfq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tqonwghu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfdfdor.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvvojmx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2axfrwwws.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nywcqgjr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpreiwqf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2enbktqjg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqsuezz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhoqnlv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkvnrzn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cchinahh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhknkzre.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwfycng.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhxixeu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tocpbcrz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvmibql.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emuxrhpk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhyaufw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqlurup.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyzszpz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvgtuic.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2quiqvnmb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghcrkr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvfkkjo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lndolgwr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2idtbfgst.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2meywkuxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogixwmlf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsntgte.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rcreslau.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2opnomquw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcadfrrj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqdobuu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdmlpon.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhuxobl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkrzxye.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxplzle.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lifjeeco.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vdarllsq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnafwpzz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wtufsrbe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvdkbgm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzmapoz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjgtszj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iflylseh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwsirlx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtkyyyr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2urloblkj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2opncxybi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrnvxeh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2teehesgd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hboyshlk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dfznuzzo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyyoasf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqlkupw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iowtgdzv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fadleosl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgopdhy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvigaby.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkherjde.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2koagxxyf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gsklqwfb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnumscu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qducwpun.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfheahh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtyfbuk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hnidizce.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2clwikdkj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbgisyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cytfmitj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ailupjaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxpjtuq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2csnlgkwq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2senydmrm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfrukdj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcvvqvv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2giaqhztp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2meilmoxk.html


<!-- 参考信息 -->