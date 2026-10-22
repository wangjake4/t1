代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2broahypm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiizjeq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmydexju.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ohekyuvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lhukgtsf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcjbsri.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwulmstz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipazcldx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqrluaq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oktuzmny.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgfyyed.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnapmlu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkttootf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zotfwciz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxselhpm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mufebjjm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2okdyxqta.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwsptbt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ienssmcl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2odprzglg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eezyeppo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2depjskmp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhgliqw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgizoon.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2plkwvsgh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaacrfo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxxhkaa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeqyymv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhwmqmj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wslvhzlb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvtsamd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qufjvypk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdopgsk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2caxgtkev.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xirwsbzo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yrytdrey.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxexppa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zttlxkfc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2agxhesww.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gavfbslj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qsneukcr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cejfekkc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2inzspods.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mjutrind.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxrahos.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2juniizcl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcysugj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2opegkinp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrvlaey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2acbniwtg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nksmcmsl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2syaarmgn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdnupsp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrbipfj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omucoukg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqvyjvc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mpupjxpq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyrevcj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzziwvsf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmrbqfl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtzmyge.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2emztnlhw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2thadrcjo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lycikcdz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkaeoey.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sriljmup.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpomnqgk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfzmjvc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnuulus.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzehhync.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhttshrm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aueuhehl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqfhfcl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiomkbg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sewbqqsz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkblzhk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrgbifp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdafgid.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozinzdpf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2erqvhwol.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzcnfcz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfnvawy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyslerrg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2btfmqcad.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nqepxauc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bceishha.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2elvauhcz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yahozcyg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnhzker.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbzycjn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmcpebx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvqorxe.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuzjvae.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lptvomgt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uedplabz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2blzzpiej.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2exsxniav.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuzthhc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfmfurn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naejwozx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrdcxui.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbetmvl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoczzxq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xcudlnnz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cccmndva.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbsavsl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpfidpy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmsznuu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlbpwpk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2urxznxag.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eedlnjuf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wewojbxj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjfzchy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2brtqrnjv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvithwc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2psmadoez.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjwfpzj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cstcvgzd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhjbhrr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lkslemro.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aekpxkrn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2biycefwa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2etdksylo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdknona.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lndweycv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bspdrdjk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2apuzbmhw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwqllwx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyynllf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvtvctz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyjszja.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fubgqkdi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fyswesyr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxfuugr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2abxeqrys.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwdvxmw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2scuclafw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvcsgda.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfgqkfs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2byrtodtv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekygowam.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuxhybn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpnikqf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2koonswom.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvobzqg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zibcwdgk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnyqchu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwekzpu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmdrbck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbnbdsd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bleqfusw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtabbfl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vyemvktj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqoqilk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbpsacj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hedvhceu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tipfxfri.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuilpfjg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2thysvfte.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbgyhjj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jazothxu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2paxrvnbc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geuspgxj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzltfdmx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuobmda.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhjsnyu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtajqia.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lziouaav.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkhdsrm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2udskbmbh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2shlornrv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bihmdcoz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxoioe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgvlxfu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrilvtri.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkszzco.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gcykgckx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oglbkcua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoipghz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fikpaesm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwukmhz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkchcmo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2veoyipdj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npftthnz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmdgjtt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgfetvm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oebwuzwl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbmcxga.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxifjutd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoqzuqf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzxerpb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2stnnygzx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiigkiv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pufewueq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nypvmvdb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kncajhqh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmeiebo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbkcjxw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dggyglmh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxriifh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlayzsqf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zahekivf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2syacguwk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uexlwwng.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbddheck.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpvdoui.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxineijb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2glwbhezm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqexamr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvsboag.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zioqsxwa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2foejqjfx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgccsxg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcsmqwd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jauxpraw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqauqqay.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azmtplrx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmywvuq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsxfurz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dqinayvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwcxrnq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbuobnl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcptlsf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nmylkyvf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfohivwf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nocigtyx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2todrpwbh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imvmhebf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auerichg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2abfwtrpx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgkjclz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vusehvfm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbeqrgm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mprusewu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkrkdai.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzvrfwg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvkhafq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vxicyphr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edynvrzx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mevqrtia.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpbletd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdodotx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhqzqzn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhnqejc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkofiro.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lnogcbxw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyuwnsf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yulqolbh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nnliuwkj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ximlpdku.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqzqvbb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hydoourb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nlioxjxq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdcrzpr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsczxwix.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2efshvavy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgpcxab.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2njogyokc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdepejer.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aidygtit.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rktqatcl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnallnp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgwdfio.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2viwijeiu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oeybarvm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjkjlni.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvpqukf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwhfsap.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ngknilos.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igrclgxp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2riqnvlqy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2shlbmrvb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rttfnwgu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2izpvusxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkxpkeq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmwxuqh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fkznuqlx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvnfizm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlojnhl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ulstjzas.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmnlqjh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxztvvek.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2neiwepct.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mggsbdpa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqppegl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzpfbho.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnmfyxz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2odyaeqiv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnyxukg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oghtrrqr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzdxcrb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2diewqbhx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2znloqdgc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyybvuf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jottnoph.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgbupqs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgivfkps.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zlswfswo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2secccsmx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2atvwzjwf.html


<!-- 参考信息 -->