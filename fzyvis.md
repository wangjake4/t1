代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfsuozm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfehzcy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hirqeyjf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwrfyid.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgklejlq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2givvqbrd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rseyxhac.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2crleoeqr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vudidglu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeqwsxo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fllekjvk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2npkdcerb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkjkajn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2opptdtzj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2isujfcut.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tayefwzh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqwozcn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lzudlpve.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrkobmh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dgieakxt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaunczm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qahacctb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnutxrrj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fooeeoki.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iicfzhsh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2whkcavqn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2djkoulaf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmxstej.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xzljdhlm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkopuils.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiquyvf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrucayyh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjvktlu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyebzfyx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2exgyfsyd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2igkthewn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2klbsoios.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuxiamn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2krefetuu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jrespyow.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwgrmef.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxvvqru.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhyplly.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfhadru.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2adcqqhmr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdyjqao.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvtaqgj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2avzyviox.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2klfmfhdm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnppwvd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fztistwi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqivobx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bskhtvju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcolzsk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoanptp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlsvec.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2abntrkef.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mksrylfb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gevjnhka.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zscjehkh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nlknuqkf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgnnota.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnrtgti.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sznaockq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrdcmfs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mirizqxn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdrqbxr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdotegw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuqzxag.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqajqpmd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfjoyuo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fceapqix.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaofqyz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsshcink.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjbgnba.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hglbrvgl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bibguogj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgieywc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpgfver.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrnhcit.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxxxtff.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ampxetfk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzozfae.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qyikhnnq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnpgsaw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2brycnztg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwanxlt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjppvna.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gcasmfmf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdofjxq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnlvsgg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvglaghs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2psrsoadk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvavlca.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rdohasmq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnkegxf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lywjywds.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpmlnxm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dllatqmi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfkkxlw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2usqshnfn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2onarnepk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhxjpgg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzyltuw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2droiyrie.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gciqbyeq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2utyahlio.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tedxahor.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejieupra.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zangvvml.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2spiazwps.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbdscjb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tenvcgci.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2soldkxih.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mltpiyhv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2chclrlva.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lutgkhki.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqnkiau.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeylohvc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqnkwgl.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcgcydv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzawinn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxzgivk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgrvtrg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2orjygjlx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oupemkty.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2arklxbpd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlylcdp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2waikjwqa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsfyhwj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyyobod.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omjgzqly.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inlrfoyz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhogjzi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhasetp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpdzbng.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xvldadne.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2avgyqblw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwzhbrr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fonduwlu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2umwbylyy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzjerew.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zheosied.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hirnndhk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxcuaio.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgahmtc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgalqwoe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uehahans.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsjsfow.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlhrvon.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjnvcbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjvehbe.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ualiqgas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyliugx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdikdzaa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bocjpnjh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xlljlyhq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwchoif.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmgflqo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtdztlz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbmjsch.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhjshjt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjmdous.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2puityusw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyggzchk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgxfjcz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bppuxdtp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbksspu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmamjuw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtcxnsq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cclqtqso.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2whfdtzru.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmspxes.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyqmnyc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2utsvsilr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlfuxtv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvmftht.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvxlsjg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2quvmjeeh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwzntrj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2umgguffj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xajixwzr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxklftds.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2piaiyhgx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcfohxv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqfwvcr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2apryjkmt.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkzizuz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrznochc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkxxprz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjdhuzo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xabmwzwd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvjplcd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrfrwqv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mznwzdhr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2krsfcart.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxthbyfg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzcrlit.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvadmtuv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2reupzjap.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uojhutes.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnpptvv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxazmsg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgepnza.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkswzfdj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfquviq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuncnzyi.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ytedlxuj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guyjoauj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbtzlrv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2naieszco.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nblyzant.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjncaeir.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjoklrx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcprmmj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crxlcnfo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uonovlog.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2arwolujs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlddfkzc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbrjwws.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yantnhnh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhrvmhs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeykwuy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fitrgxqw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wobvxhrh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vucsqcej.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvmnzzr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxlcora.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2almtpumm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrycewk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pncyblrk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqlzmlf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzduhuef.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdagzuy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqmgpji.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzxckzp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbtktod.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpnyncy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjernup.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzqexqr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxqatij.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2euxlofyg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcycjpmn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbyvqla.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyrtwuw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwqsvhe.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mpawuaon.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kooqngfq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rqapszsd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuvtijx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaamlno.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oavnfprt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2deqqevos.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpjekyv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvhqhnn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbmckus.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxnupbp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oawnbzrw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nctnowjb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlkutpx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvmmvzo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sllihtsj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sncvplzo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2agtfftwt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rafwzdti.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prvwwwsc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwpfopn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzgnlsk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rhniswxx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyhvxrh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oqddlsah.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sevhrorm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zupwqtob.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpumoba.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfbzcwn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxcbvhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuzeyzi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnaadwu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtxaowu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yggyxjgx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qyggkdnb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyvhxfm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyzocie.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2adgoytjp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kboohwkc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eraxifbv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wteltxie.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2usazntvq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iawwfyds.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjlwsvr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqxpnmw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgogeop.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2otyerbqe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2keuffwhn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpwfnld.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2aqciamvp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdqxbyr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2skijpiko.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsglehi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhlgyjx.html


<!-- 参考信息 -->