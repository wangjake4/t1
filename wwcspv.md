代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqfwfzq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrnkghi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsszvol.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lujelyrt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2usorabyw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iacsxwca.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrzzqik.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkdrykb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsihrqom.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuwvcmk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqpxypv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oncocxrt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxizfnw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oidvbdbk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srflbbkq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2esbprjsa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecamzdeb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2famweyvd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpierlhh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpndrisu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wknbyapa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hhchbbhn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2shnlnzom.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlemxey.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2unvfgkbz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrelfts.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhtnjkr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ucltkghg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpvptcw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccerjuvp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmrzmkr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpwemvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mtahxhym.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzalkecr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2benebgzj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dopbuokk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gokwnloc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sejctzuq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2knmdcyut.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtjshqu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gppwcshf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwpfcec.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mryjcfyi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdbtcpq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2osfebkpn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvnbsrg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2irkwulpi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymskkbzq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgtclxe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxfxauv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mypqkyrc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lvinozdm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2snlcivwa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsieoiml.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yshlxwsy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwzvkxs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tpogsqcv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdofbkth.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2huepsbfl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2terzmvdu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfoczhx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fybaxfkq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jgabjbal.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxqwfy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnbfexz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fewfdvfc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhgomft.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dczohvto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtnkxtg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2memrzxga.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfutovh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uoobrhix.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrmcyms.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgqgbkp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2abmnfhbz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgcgwge.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqktpdo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsrrbif.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnybvtzr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2psksliiz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbjmvii.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbbsdwp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yejjecow.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xtifevxq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfinuntp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2henbrvbr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yddvujbz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qtchwbij.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mythsqii.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfyifnk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbztdoy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdolfbd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfynofk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gorgxlpd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rogitlwi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cstanrde.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jngyttne.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxvmvcx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qywwcbyf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbzzras.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwygpst.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqcctkd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxfasir.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbskkch.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxaorrb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtyzuui.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvogovu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdalivv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzfeano.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vymddjju.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjahuag.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwpxlfe.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wptdekzj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyzuvjt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aalzmdjj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrfjqmz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edsdtfrc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzppaxg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmzjyvt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2duukdhsd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2axtrkzhk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yciiaaod.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxabdyzq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcpcfhb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vclpzfnp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eosdzpgl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrigolv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jduoaukm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtzxgng.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhufgna.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wscmvaft.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkujcup.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cnebbsex.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsczeju.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsnnkzm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlevcaey.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qknelrvd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkasbxt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqxeivi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2senzkuxx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyujaoe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sinuuivu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmnyyso.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkabbmha.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yulzoawo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ifupfujr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmilzrj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjvlagb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrrxmyq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmlwkja.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zunzudpw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2soosqxxn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbhgdzj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjogvhp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnnqlaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxejwck.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2efsotlhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiavonc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvtezvv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmmbqay.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtfdnqo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhwlzhk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2unlwrgch.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axayavfl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aokntbfy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2detkhkpw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiydnhg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvovupc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upmjblbe.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xgklself.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyziuzsd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wruxnyyt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzsjuq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjfubrr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2czdayqir.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgugppd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nsehgwqn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqvcwir.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iognomxj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrolchv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwoklbl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2btomfdvf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceabnsri.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uewtofpt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwfiomc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmlkcjr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usthvjxe.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2exuomrdd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwzdglp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbdwaqa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpyqkhv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzbughp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrsiykv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouonzccc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvmvvbk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vblbolqk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghjyyi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tntftsig.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtklzmw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiegtco.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbcvcfn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqxtcju.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgryhqg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jreiobka.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnkmvrp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlxqqsz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfnhfuh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kamqxoej.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfthsxlb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aevczyam.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yngmqyzp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rwenhrwh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nomthhwg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfmppvz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2elqwmsjv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvgiofp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdxvfqx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgerggk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfhagnh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kziyjpml.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpujivd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsokotu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnccrvno.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sihocdea.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxypewiw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqyyurw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxgcwwd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2akactnnc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2btepqkyk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eosjxrfa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2evrspmkv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2laurrdux.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbqzmbm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfmgodg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zigewrox.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsvrvfg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhpwnco.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bifgznsp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfdpkmu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qadkzpsa.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfdgvnn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aeycqnta.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wsetzbdl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fozuvail.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xkylavps.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfmgldg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcskesf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uunewmzy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbqoxli.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qpslrbno.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbhsmkl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lukvoqxk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaqhddw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgjsrvb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqyrcub.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dipvuzts.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2maynfjdd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xlflktsk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxsfugq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyapxgc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzxcrin.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzmovtj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2legghjmt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtruquc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaouncs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gauakrjh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thfyltlb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hjigbsow.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2prnqgyem.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqmywuk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2siycbqex.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwlzjoc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjkhbgb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcxrvnt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2umyhwbnd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyumjux.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwihahe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wamrbvtl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tkazjdmt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnufmvr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fqahjzpx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmzmgef.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdeisfc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2plfbpwyz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oetbpjzj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwssrzmu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcjfrrd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhpmghm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdcvlcb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2aoifqart.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvirwknl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwavfxqb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtugivj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wajwobcx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yppgkjis.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmioxcy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqsseqe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiklvdy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpijtxs.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkelgfe.html


<!-- 参考信息 -->