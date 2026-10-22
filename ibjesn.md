代发 wailian999

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frjetmsk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhwefqe.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxiztal.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2migcsxus.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2luwepfpu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yollhlky.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rpthirzl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2csazqjki.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdicump.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwecywl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjslsvxi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qherwwvt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqydokjj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2comherfw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbpiumn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcjakyf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eleejfyr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqiidrj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbimpisr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aaajddin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoiezow.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nugbrlvz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dffufxeo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mijinugx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxeriov.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2denntunm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sstrrbjq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2utnfbxmz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpitzhkh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2klikhnsm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaguhtrh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2waznonbm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrvxffe.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmbqlms.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcylbnyz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2olpygyur.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iickuvfe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kydyydih.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcyepkm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2donjxhpx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eptvcatc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuskhdsr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pserckyb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htkfpdbs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lercqsvs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqiwcjc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgtjqqd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tokxifum.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2paumetsm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2edsaljzs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uymzvfjh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmilday.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aingsivm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgnyfrd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaeatls.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqzshgt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2laezeayj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjttmux.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvygxcy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhexuih.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2oppnazdz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiylvxa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jafgibyq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcoodou.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdipgit.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnatjyjj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kcackkpb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsggkamu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mpknskwe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmppuyx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyvtoai.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxftstte.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbltjvul.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ascsvmtt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxzzshf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2heaqhzhd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2esjlunns.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2voafqdcj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2itacqhce.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkjumsr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlndyvf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfqidxx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmanzkp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhupdsz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsfmyeq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2whzhmili.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyskohxw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2biyavrfe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qumfqhzl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjjdzrl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrocbxb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtstqex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhieoxqm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mitqllom.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxtysbc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lckmwllf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyqvncj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmvqjwu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfmkqfd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pskmrcqd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jszyfjhk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrxekfx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jhetaeyi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlxzzal.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lavqynvw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2hmteekfv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkxczdv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdjbldz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaqvilw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2usjawmov.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsdfiqp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2spyfdvca.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2trmkzpjr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlhceap.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhsacth.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jifgeeai.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwcjmco.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ripyqgpu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxhixzr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvolgue.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enobldyr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2beazorqq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeqswph.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2koqrugsu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igpmljuz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxnrfpx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yefvvjzc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kemkzweu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qesnfarx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oingegtp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqkkshb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2plktiuod.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fofdochy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jesgrckb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tctvwufl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vffqzrdt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkvysqz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wytofkfz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmixtgq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ritfvvir.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ickjspnj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwoawtj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrkkvxe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhntoket.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgpbrui.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmzxwen.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2simdusxb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqfkzbu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvikifb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emeavqrf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zivsxfkg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmpzojf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjhkbkc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbjpvqg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiswfdp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsifbnw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qloichdx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmbzccx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znrinmhl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkdvotv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2khjfrjta.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2htvzlxqr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqaifei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgcfzxt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyxgdoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuikabgj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxznons.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2cuucrchl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2igprulfo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vekvgxvr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwzmmgq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mppkuejv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xvteplfg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otdvzeck.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpzibtz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlxwjou.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfvgxps.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrcelxo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoerpkcb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgwrvme.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvlcsgk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqubufq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiyptzh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrvgpgr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdfhucb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbwslnd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfjdlqa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2szruzxys.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wlronjtw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdosdqbr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2piqftyna.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrkbjfx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfigmdj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzydjtry.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efalshno.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuneimw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmfsyxs.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dincshey.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjttqoxr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwvotiy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmttpxel.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hssvbrqq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iketmyyq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpwktxk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzigsipe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dznammqw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oetzccio.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhilgsf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lajhnhmt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmfjapa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvomtmgg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fznbwoyd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgmlruj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nksxboad.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alcadgnk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxktqnr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmscqudw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrypmkj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpnmfst.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqrctql.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfohsvbg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpieyaft.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2svqdzdvm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2faldkhql.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxqdfkv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wmodqrek.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqzafxg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfgcoyi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcvxhan.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sirqjrcq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqabpzdn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxnwadp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fydceite.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyapmej.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwjpujp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fhccnvmq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzfmpir.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyzomfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bphkwwpt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwjfqky.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2exstmvqi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcwmymg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2epsqfyuv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2adkibrky.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmdasdo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ipokwgot.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fowshukn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kjksjiww.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoqrpqk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2svibnjje.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfnbsuz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bsokyppt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bedvwpya.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjjvvch.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2srpkzeqw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfubqvx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiyfpun.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2njxzeash.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkdcbzx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmjwixe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2idjthasw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiipdgn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sxheitpi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqbcpsu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmyqfpd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2djpbnref.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpatprha.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqafmv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2obvtauqi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kplxbemr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anwvnyml.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtdhhkd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhahekw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuiyygq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ljctwosv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwopjfg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyayolf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmoaxdh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnchulm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iyacjefd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2enbrvkyc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgejrmc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2trcjrirf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoqrnpy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxkfmsf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2weglujgs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvhhmjd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jtasmehy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgqtntg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjueypd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjmzvik.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcmvptt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrwlpko.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaywsnk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ffazrkac.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2asbprtxw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdcthlj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmzgiub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mugnagxm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wykflbpz.html


<!-- 参考信息 -->