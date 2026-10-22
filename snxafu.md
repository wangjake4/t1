代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiulxyxb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2behmyxga.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxilgrje.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wukkqxsa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlqltut.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2smwqvgwt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fucgctwo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzjgois.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavqheww.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fepmjbpe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwbjexf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vuimldne.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzehzdz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvxlbci.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgptcil.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2izdtqxcd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqficmci.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsaglqr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmpexuk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xiausemr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpkipza.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oarqhxhz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sapakhdp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdcanpr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iabzkjyv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkarsjh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoepfzt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2olhratcd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbndjbp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2axretedu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xspjjfym.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hejykqdn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrqcfbl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlmtodf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2errhalmz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xknaaypc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2snayethq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwpluwx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsjtzvh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxydcova.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpplpduz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2etjxzzoa.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rldbkllp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2itjhouvh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbefzaer.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zighrmcq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsexldl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pysnbpmp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbvouki.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuxbxka.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgvddfu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcaxmuz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxndcqq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ighkosyl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2msdeztjz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnopqpky.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcbdmcb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpwrdic.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqautgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvakwpdv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkfhxjk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2huchxhpb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xewvycdw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnyibuk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2euvsygby.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcnfsgo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2culwlwuy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvceew.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqvftdl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2spjzqfqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2peafhjbt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rerjeree.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ickocuds.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsdukah.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwghvekv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sexdvxsp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ufagvonb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbardluz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsvvjod.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kigapclp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxtbhnr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhcplcz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzkadok.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mllbbtfq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyitrgy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnftzme.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpxrtdw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtldsis.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqfhmct.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhllnen.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2atibzdjk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2esbqmhyu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyaghou.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpsjltp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cuttawpf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytkipkg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnfdldx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2quxkobna.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgoeqzz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lypasyju.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrwzyac.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyqmdrc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2unickmte.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2muegdgro.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iryzfjqu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kytglgxy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmffojy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vavmdkrm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djkfpcsl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2balthaok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dprdqnny.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvwzwxc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrgzqtr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuoamxv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkluiyx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeqbtbl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsowfnkz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcknywz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhljnqe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlgbuhw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrfgurz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dttgleve.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbaxmxw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzjzwtz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyrdhbu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2arxrowxv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fphlsffz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwyxwcz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgmmcee.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrahpkr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxxwbby.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dqctxlan.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mizjhmbx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuzbtxy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvdlctb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmzsxpx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhwfapd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgljcemg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuisfrp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsmaidn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jhplecip.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnefxfo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmmegdk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpesrqd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gehfwran.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrxyljv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgmapls.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vimhnifh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhrmosa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pjphctfw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lizepocf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wugpmxnw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbwryke.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcwdwxi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvkgvbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhbyrvx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcaihgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gepkcypr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjigxhxu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2swuttmdm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2doblokus.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tibeltth.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbgrlfs.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwpeedq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcseklt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iltijaix.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifytzgwc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkuurpe.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzngpxvg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmceucx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmrfbek.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdanlqz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lnphmhka.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wouaktva.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlvpxrx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gowfnthe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2udkhdzsl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dceyeqrb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2metdsxsj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ultoynzp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2cthdliny.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2basvprnl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvfhstx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwczvhd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbfmhvs.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmcecyn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2apkpyewg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcxdmru.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrmfxly.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jmawruoz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krnkcmff.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adigkddp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wakyeouo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wijcpwae.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvhxnzz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kakpucqf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfofngf.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pninuhsp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrprxtb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdurarx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqomrin.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsainzcu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knzvfsfh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlmdxfh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqmzywz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2coorzgfk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgrudpi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeagizn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2haptachl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaxuxda.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tikxrixf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2egonxswy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2glqsktau.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpqhabf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2clzirtnb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2sslmlnet.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqazmxl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbckpqd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyynfbt.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksswpmcm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2samamldm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqkvmpv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2spctupal.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iolaacet.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlnpgas.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdyvqhl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkozmjo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sflnjmir.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbnvwpp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcrdmlo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxahsgu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aizryzra.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sljkpfsl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dycareld.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bdncbiqu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sseyljpr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oharfcar.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgkgibs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2upempxbv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iotqugzk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2amcukzwk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bysgqjyh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tulkphbu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaijqar.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmultzb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zchrxkkc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnbaqxd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyyvmch.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvowhhgl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rxggztem.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hdynnmtp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqghfef.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2onjmgykb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxxmjmp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhddqih.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxihzhij.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnapjwlr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbtivda.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urqtbkdq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2usvkgfgc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2boxsbaki.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hakobwte.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnhykpy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ujavfvgd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyzqhji.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbptjoba.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwjuluz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2erhutjha.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2trxofowk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2noeiurqy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfllatg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fdykruxv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxjkiaf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsesrpo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qqckvuuc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfygioh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxpiqfn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuminvv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmxhofw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqimbtr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dcblukvh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbmdqfx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhmlepv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvvxmau.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2keamfkrc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icqnotiq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkxiiwb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yujdxbkw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ljywtyvd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxuwllx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aicczmqg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fwehlpwm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xnczwqqh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbgjwjc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnmtfou.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sytaamrl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hccoykfc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkhdyug.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvzkmfo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsnpiww.html


<!-- 参考信息 -->