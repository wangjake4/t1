代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbraifsd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhdmjxs.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iegullqf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnckskx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqksezg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fabqdrhh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2utmveevn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzgcwpo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfckltw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgatchu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2khttektv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwekuki.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxdmvtz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxjiuhf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vohaovxf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwhocr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpapsizk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2igktrdcr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgpibfx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2htvrmlri.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jecdguvn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlqgvai.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iiddbecg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2myufdgpf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmvhoqu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfipanek.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpvensv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhiiowu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwyybad.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hccpciod.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uamzqdrm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdprgjtz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xywsxasr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jldejlds.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqrunhx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ellkkxqf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwtwlfo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvcmyny.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmfqvve.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ilialoxo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzuxqzx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeztyff.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2muwejqbv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnnhsgh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfeyllg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xexfppaw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrnzvfn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pedxcqdb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2witfmsbw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2eskibbbg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxmxhpb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2atyejvpr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzwyfqn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxpiusc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lakyhyzr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjezgjr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2umpfnqyx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgaczgg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iphycvrt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2emwesafu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrwlvqc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ogotcyqn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhsmxyc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iualzppn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzoiicn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsgyqzw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmpbkkh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxsjpdx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2otkattwy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmyngxr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgidwxd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdbvuaq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2recpersq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ythyirca.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbtcpol.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ywviuybd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upiczndm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wndhcdew.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2egeefkze.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmadcln.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbexvlie.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2alxxboxb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqjlcql.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyazjue.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2etzeqtcb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2excqrjrr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2csrpimyq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iamdwbop.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpbbfug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jasqkipk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvqddib.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwydysg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkrwgio.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvygnanl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtngxnsv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcejupiu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2phszgvix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwobgrj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2thcilaha.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pspmwfvb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqmutfn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qsexeedd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmtdsxr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rtstjwyk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxmwzde.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyrvwta.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtdsube.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sdedpxww.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfqaxtd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ufavkhnq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2viodtsmv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2riagogrh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fpksyzyo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cteivmxo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2alujikzq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2msfnibqb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wclcftmk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2isqnzrjs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuaidre.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfqxkux.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfjefun.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gntlwtcj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwmfiue.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpbznkj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbdagud.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbxqqpj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srgxtqfh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjincwk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjfcxli.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hngifqbr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fflizvlf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzektubi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hliydvip.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxymqmq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2utsvwtpi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaoqlhs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jxffumqn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzttkzpd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2isbdjcry.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kveteboe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlahblz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbwipqn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugskvbzf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2obtitxzp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2udfyfllo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2avbjhgcz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxhzeeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wllrcqgj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uudeugbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrnrqcd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cuejelxx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvuckoa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkvffly.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xppgvkag.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2amurwfsr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cklsjfqx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtmbxac.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbcplzp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdoyasq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsrmahu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqecgsf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvqarmi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiebpqgi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elsyzbdw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpnhiep.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2svhtqtzw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsgsgnx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxxxkej.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ixclvexq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2madairkw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhndbfds.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsdzpsl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vywjiexl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2enecfynh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjdqyxi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbadcdgo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxovwdm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phhfqqdr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhxgrso.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zyijqbpp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdidohd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlkvbux.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ammmlfxt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icjjertk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmztvbku.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkbsbyw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dsurrvos.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2niszwwmv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yojczyno.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeuxaiz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jaevxucf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmxttef.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nafvnbxv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnwxedl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2glbfrtcj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyfohab.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfviznku.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmduynee.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adcuhrxv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoukctx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2acvtydrx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukksfmks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhffqrt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zberaeym.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2chwsxnlc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzorltfh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxkopvn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtunzqq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwkogxm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzzrvel.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kflabyxh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agjikljd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqdodjh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ftthzump.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpxdxrb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkypnbak.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkuzdev.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sswuitlp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlbahdx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2frlthnnc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdexzuf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2odmznowu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2otnnbmzb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdctspo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkjdtvu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mibmcerd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kzygqwlx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcjvyzv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dshzephc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bevhwmss.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fvagsljj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2htvbdxpd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlgpxiz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwkcbrt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwurhcg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtdgpch.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmzzxgy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuhifrz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icinzdsb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frroqnbk.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gywpldpl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxbbsri.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2svvmlivw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dlumgygk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbeotyl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oawyaywh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmoxzsj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzpbede.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odmovdqs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fccpmyuv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwvujur.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2llibszqz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2igflunmv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqtjzbk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opsklehb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbhwhec.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhsjggb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxeqeks.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2luktzkdk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqhvlfh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2advqmpmw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fplijeqc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwybaxrs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwiacrd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2czjybaph.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsjufks.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcqgtyl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aexdzyts.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpuredo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzonbihw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwztbqd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nbimexjk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjkvnbi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkixkzyt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bizoyjpo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqrkylh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2scyhwona.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxhwild.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xehfjxxi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hdquaioy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2axdyjjrb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2agpmklbr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibfptgp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpabqgv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2evwhzmro.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxjpcsq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vgusszsn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjxdmrm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhjkqmf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsypokjp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2suqssgdc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2reseslcy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkudyhs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhfqewi.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrfdgaa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwjddzq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vongucnx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxmrmnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvrstap.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sllvteow.html


<!-- 参考信息 -->