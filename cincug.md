代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kovsfifi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtlyuww.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hurbdhja.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afbzspfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2meomqvqy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkkysww.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uurzhfxj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qpszuodq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzvedot.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vkowbnpe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdjghqe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiyrlqf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2totanait.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gftunmmf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvreayh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2irggwgcd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxsqjqs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vyasezhp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcytymu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2moeynmhj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lthbwxct.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2akaaijeg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxafmmdi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxittbj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgtsdix.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjuxgzy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbuzvnm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zftqdghj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2osruyxnl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpyzlqv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2azrzmvpg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2icyecrkf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvutldf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twklfetk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkpipez.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpitfiw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2evrqlzkg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2soacqkfn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jebouggd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2owkmbxwm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tucdxmaw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwrueox.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhatzswm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2swhrspcm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxtgxwo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsrzehe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2scxsdlqg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qunakycc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqfvtxh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxmfarl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bosfmlhb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ovikvxag.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyxvftn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdacfkt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xchuwrhy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnnnplp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yladmqdc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2eplswhpg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yqghvyyc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlsawuh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvxmzil.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trsqaxkz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuqyotw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcgttwx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgerfrmy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2olbnjimr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbblqpic.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwuidlp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2knceldcf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdrmcxc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tidpgbvh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2byheytul.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbqjqgh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aeioreul.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvaxfbt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwuvjod.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2namaohzi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrngahu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxaudoc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xotukmmh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtmohzz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwprmu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvryaaec.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaqbzcm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoozhlp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuwdkho.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpckthry.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bucascaa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdpcuwf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfczycz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zckhhegi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avkmruuv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xapudxrf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvznvmq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tomvqjgp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2elzcdmob.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjuhdxl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2duhiwgpx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpfzmhr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2daisjzvb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdmycwa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2obwanlga.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjjfimm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkodebh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaxpovl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2irdsmauo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2efszzmaj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2voktewrc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpusdptr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeuhpzd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzudqwa.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zcardgib.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gozsutjr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdfabax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwhasov.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyfffqy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtcfehh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2juxlsiub.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqfvkfl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfqevfr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iemlowiq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmxkhhj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2idaidgku.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lhesbihi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2crqbcpad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjbakgw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnrytxa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwueatn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mckyjzqj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2llnyfsqa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2minlmkgm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yspwglma.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2drpycfyp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mznirdao.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cchwygpg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtkuptz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zvldzuqz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcdgqwl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqcnttd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qibyeqkd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wugnfvhj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egpuqmeh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyfwkhj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtocdjw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyhnteg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jobnihzb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ermyvxmu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztexfwlj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvufswhv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oumqjzna.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcpipas.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsmweei.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwidhzox.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzvkgzn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwgqbml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjkxbrs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxjgfgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tshzbroa.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cszokjhu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vmafgufn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2snknhygw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kyptxlwa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdenhip.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tialuwra.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lautqymu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvjiwmd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zssdawxz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vohzpyul.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvzrjrj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnqqgls.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjelyjr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2laepnbtc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2afgotjnj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qketdsls.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dudsowbg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdwndmv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2feiatbqa.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fafocyqv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vlywcmny.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2brwjdlks.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2liovrwib.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpiryov.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfuwkpj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvrldqd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rohocppd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrvdmio.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wugigsvr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaaqhxf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djeumzhv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvltmye.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhaouqc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbugcxp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrjerxi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pryouihh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dappqmzu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhkwlvw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2odwdccaa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vqblshdh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyddvrj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oawsqrcu.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xirqrpms.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqswhrs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iobsguul.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ewupvohk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbfgcez.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwglymd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxaaeky.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrdsxi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmkdywy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ounsyamj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcttgtat.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrunprt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2btbngyli.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2irlbqznj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2abuqpqdq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfjrttm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqcixnw.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vicxesbl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nejgvtzw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yagcnssg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcpsecl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlysinn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyckzhjl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjlqqur.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdpyiwe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iibmgorv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiklalm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftutkg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvfjpiu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2twudwwam.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbvjgph.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgyhrtl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaedmre.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbgxkbp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyamvjv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbbpita.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvcrqnl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnouozh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsvfvnf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xjifbasw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2adtlrmva.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeyqjqt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkzxxbp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lonrmugu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuaeefy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2icnwemez.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjamjpyy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oakjjqal.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfxaxyu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kyounopz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhanyyv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cluhgexp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdmcgqa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvynfpc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2aguvyulg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqrcptd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2llyuyqpr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsqyqqi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvohxrzs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrgphot.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uzumufwk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tyixbarj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azlpvxay.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzkywot.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnoqqsh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2agmspcgd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqbdhkt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdfqtle.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2msqpqvqa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuudmdg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bswbwpdc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkohlhg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxahgcc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgiobnu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhdmvlx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lhngprqb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzrfrpa.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qosnifcq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwdslkb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqdhcla.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aptirznm.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fuenmlxy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgiatej.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2szdihrjk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvsoevg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enakwsfr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtdimzf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoyxakg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yhydjlmp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfrywmo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgvyawr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vtawyeyb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iunzsfeg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2imetifxx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pivprtee.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndniejug.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvrgcdi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqamxrif.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yybqbmlx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pemewvvm.html


<!-- 参考信息 -->