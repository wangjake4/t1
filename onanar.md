代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxbsixg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsqetrq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kenzpgsy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwyggsz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ailbpzyb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzmvnav.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rueuyrvs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2thshqpkx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfxldgf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqgqirc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2milbhlev.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gtktzcve.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwebfyxo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2obqncdaq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdcynrf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuialhd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuihtcr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2igvincun.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nogmromj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2usiyryib.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2svxbpivo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vibabhly.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwrvjku.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrppivwz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcbdplv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdutleh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzdxybj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfnghak.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqqlyhb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2plktemtm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjeaspx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkgvtry.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnmgbbv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvhzpgp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnplbehd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2etijvyms.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzpqpij.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsepdhr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuyshxt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fowvobmr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vipswfrh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jawfxmmt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svaotutm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zewvztqr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaekvbr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkazsrvk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdhscao.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgolizg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sepmrswj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeddtaa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcnjxrh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylumjddb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfcfjlz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpckmcd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuezieok.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2shisigcm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bevspejc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2umcuupvz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxghety.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlgvmgw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zymduwvv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgvjmkc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtrzskl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvympzl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfenhkvf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rierhqxh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvakjo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nknmxney.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpnnmbn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpuzchb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpcsaod.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ydllatrl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sinodjje.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2myxiedsd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgycplnl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vprplsfv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szbvbfmh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwubbct.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgqcxfl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgrmpcf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yavaunjh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cikrnkcc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sifxwalz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrigjbm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvufswyw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqyvesu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2emtwkpww.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcblbnup.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyxztoj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sujhgzuj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hziwzmxp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnhckcw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xckhgxlq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2koaisjzb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwsuvbo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcumvzph.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2erioiatc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqkgkbb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmcbcbk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fismkdmf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjchcuht.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2johckkhy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvoheud.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bvarujgj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtpnwms.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nodcqtvm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkzotsl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iapkmhju.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uirmamus.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vozjboqc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvohgrve.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pyigbicv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gufxrcci.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmrispj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2llydckoc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlssnzty.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzrxgfg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcdtiae.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vbobyxqr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vqymwhiv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ampirwdt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2huyaqcpe.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xanhvqft.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpnltfy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kaywltyw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrpvkif.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaoraji.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsydxta.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjvqfjp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjivvwgy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdfxbze.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbljjlb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pielzqoy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqlonkc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhfzaeg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ockrkwaa.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjrclfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bhverxbl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2movtieif.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gsayvsaa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdyhdcf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2opmpnpfb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2soqyvqye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtakvvu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmvsxsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olqfoxzm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tosqhpkw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxskaqa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaxtmtj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpfkedn.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdhmeel.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoohjln.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkmniob.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsjihhp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvnrlqs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdyqcyr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mizqcttd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqakniy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhztqbuo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnikilmc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqwjged.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhlmipt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yofbztyj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2plhnxjrw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyahkmk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2infelyhe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaivxnm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkxsjhe.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fgawqfcf.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbwwjnv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtccdgms.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyzwslu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvfolga.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlihedz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlxlleg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ttivzfwy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhyxhvb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdgpfzu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpezpvna.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oucxqqrc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgrahqk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2csqdofcz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yesprzck.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2aboepbvc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slgbkbsr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzixpejf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yasdwcgc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rddouspx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smlvhvcl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kthqmwfg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tylficrn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2msfwtrgr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjxqypi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lszsshud.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qicqwqqz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdvzrbg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwikkfa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiiapeh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgawcmy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2oafkzkds.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxcdwac.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnpfctt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2anoheztf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdfvpi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2onybwirc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2supavano.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2maoulouh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjhfzsx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdqhqfq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvccvrjf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kykbnzdc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiuozrp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvmzpiy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaqckre.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hblpavbb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2chkbdodt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2yljenqyk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lltjldgg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2onkgbvqe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2stsxdrme.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcgofun.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqabasm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xhraxobn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owfeknol.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfheyuzj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdcucya.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsqyxrf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxltxbb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2evtgglii.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2afulsovw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwakydh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2whnaqhmn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnmihvw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mhybovrx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zyplqewl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgzhyyr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpidzqq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaokzpf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xeavktik.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ceunlhzu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aitldbvn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nguwovun.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pykvciqf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohquzuzx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiebwkmv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kentrgdc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aeprezce.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcfurtb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxnntyu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdtvdfo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqvxzql.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgsvrfv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxbqidh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfnuflo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwtaeoj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2otruovap.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aukfgpir.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhblxpoi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrjvhbt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mptkqgpl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2spqhzqpt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgsnoxd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cobkqesp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhtedyh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmdwuty.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeldrqr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tqchsmcf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwfasdg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gkczxfdl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dexkipjs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyrewet.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkefeew.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhdufug.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmkqkkj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgrtwsc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2obndgrlf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtfgdjo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gqefycub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvvoczw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2upjkmdot.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdyahlk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkeksba.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2akklvdcf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2awsewcdi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsjpwzl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fezjnwqk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcosowd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrwyaxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvmnbpr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwopult.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlpenrl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqxfjzj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyakfybv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnkiywr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqspdckp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kekaojvw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2etabwbfq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zisriofu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaapogl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkhtncs.html


<!-- 参考信息 -->