代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaototw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjqdqkv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2oigsxhfb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjsbgqd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mzppylhw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2futhcmzz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dkozjfew.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlffhgwl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcukbno.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuuhawz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfqeudc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmenzkaw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dokbrqdp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyjcrrh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfutupg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cqugcmqu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugealzyg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfavmyej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxzwdgm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycersmok.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2htzdglzq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtlzkjj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjmmxjt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyjorhq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ahesihdq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2myywbqyw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpwcnsk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfwrwnh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2edgszsxh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2krdmrfig.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mszjvrgp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxroneku.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oleiiomd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfounopk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtqukix.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwaxwjf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pchwqggo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgafsjcc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eacwvvdm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgqzhxq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2phbygxrg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uosmqraz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdnhvbm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpsxhci.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbvwuxn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgheydtg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pesnrhvg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2osunabbw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sszeplvr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tarhlhbo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yebackmn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kthzbfwx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvvvffk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbsiapt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwmllks.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mockkrmh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycihrpod.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2afeobplf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pccwxxsl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgyisho.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2svfefyhg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpadciy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiiines.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdohzuva.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgyjlxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcpkren.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmvmvka.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hywonpqm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2emxegaal.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eweoaace.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qniutzds.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrmsbof.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmjwhfe.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxwbnzs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qflcnorv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vujdkaqx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjyqelm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoveadh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2krmnwipz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krfmehho.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pedxsciy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbdtorw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fxngjcwi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hkghlmji.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cieymxao.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhvtrnc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvkqcyv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uepxliue.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2colsuxps.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rnntbtca.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyhpgpi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mifjkzav.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzbfmsn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdgautx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjobegkp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2seopnwpc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hvscltef.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgppwbc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2swjknjyj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdvcyax.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2olkfnwho.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsevlppk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnffujo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2erwhwkbi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvcuxre.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bskzqynm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkoctek.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byqgjcol.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mazeslup.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmhwiku.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iavqnjnd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpzcvvf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwdxrln.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sroylcpb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxcnpzi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqojclvy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2umlllofj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhpdrsm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrggkgnw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwbwmhb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeoxpnd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiopruc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlokclbo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wvctqynm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fzudiirw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfqxhbu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaprhir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qteowkfg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2flnqiktt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxyidbp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xsskhltk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwsnrad.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2axocxfpx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyshnff.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtqbxos.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uetjmrwp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2drrbcqgl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lofnjsml.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrswbkzd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiwtpos.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnbepsk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hozrhsyp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnydnghk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gogdavru.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mujzolvo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsijgxg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mypwcolu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2knlwsqri.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rcojafrj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eegfsntv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2txaebtpc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaxcreg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrubmqn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzlqcup.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvjrzus.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjbfwxr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxukmwg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnryken.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqbpssc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2avusvnxo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2igervnfu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkeptft.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbldjbw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atmctjor.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmvrfvr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxmvjqg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnbcwqy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxkualx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxluepss.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qosvkctz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmldhue.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nmflduhg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uutqearm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhuzbht.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2elpfzgzc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oulzocod.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdagrdw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvpyzfb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcdoiwd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icbmwrro.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szffmkdp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwgayan.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuykslus.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbruhdc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbceprza.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaqbzgn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmfjnfn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2shprwagh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxaavym.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhiysyb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ghghtmam.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjfxpuy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoingsv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hojljmmr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zspkitjs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqxxjys.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mghkgtel.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2korheohs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzedxera.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2owghirkq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuutbyz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuulaim.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zfccuqnr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iagyjltt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqdlawc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nijefkwu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyspxvg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhnxioq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqetmac.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfnuypy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jjztaigc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2frccvzhh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeecvif.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmukwde.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjdhnvw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqtrpvs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivomdlnn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvjamqs.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cewwesxf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeigbpjv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwezngm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rimrnjcc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkyvioj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqfmke.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2duqvrtft.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2genzqqoi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwkuqqg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hchaslqa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnebryr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2phapuodd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pftphkut.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lglndlfh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpwwfxl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jkegonvo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkiefgd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcmvmwg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjrpvfb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiimlxn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbhgyfs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpyftuu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyjeobo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcdtxwf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btpdlvss.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kapykxwb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jofxpfej.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2owsbytlu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aktotwdg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ptselbtd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeaxuyh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqkimtc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjqdjdi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2decxsssk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdmtcgf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgzzaok.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wehwyhup.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwrajcs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vngcomga.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzkcgmz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2eckyldus.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfczcjf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2swmmyclw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrjzhgx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2stukadqu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxbrdoi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpmkceq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyimxje.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmiczkd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmafujci.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfjblap.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxdzavj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mgomqjal.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2azpzafvg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2blyhdrsv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2njsepxgu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbtlcvw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2snxnkdqk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsargvfe.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yptgwozy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqjyvro.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjtgtlc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tibvsqls.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2trtwqmlo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pawslqzs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scielcqv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufponhem.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2misrholp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gvljrxsk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpcilhn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yfczwdpn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2roffgfoi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfmvund.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzppgfl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfdlnww.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfrneme.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpajhkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lewewvbf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bztobadf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crjcqpgn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mleoboda.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dipsxabh.html


<!-- 参考信息 -->