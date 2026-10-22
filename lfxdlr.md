代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2irjjfuja.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtamktq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cubperor.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iovzjukn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwtmzbd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxziwmq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfskqujk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzrblfd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2odvhtmjc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2csntibhq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbccrbe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wugiupit.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfbimdy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2arnbpwgw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2andfwtvb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pgluacsx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbflmbw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbveirg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxxrpds.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2agqffcre.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2baeqydaw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2usvlipas.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrdupbb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwjajvv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqrocgf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvurly.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfojhhwk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zaadxsdb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmosnsky.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gspnmual.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gemtydkt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmpfghv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2imshkmod.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgvrhqu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2peafssce.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvcvyxz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ancohlef.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2owmvgwvl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tbssjvzs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2woqimgxr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nvevtjnj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvblaykj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ibanbjns.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dujemfsi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqubsim.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkguxgex.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrwkclo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwkhdjx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsohrxfm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ateoiije.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hogzdvdb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwjcfyb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2udnxcdjq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xkarlkpi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuocnzq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuqqwwi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuhftnb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmvkuvu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2byfppuqb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjtapkk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yyktsnax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjlknlg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2clrmvlsn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtzthig.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dswolajv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhnnzsi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdiqfur.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kijwxxvj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgltqbf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jffkvxoc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkjfqyr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jlluteoc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqpzlyp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlmmkbv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nitcmdov.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jsizwipj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwltimzb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qweurrnn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2viiavlhp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2moamzxoh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvrhnup.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hserkpjx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbqklwa.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjcjdxn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2krhruwff.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2inleuztt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvoblxe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wgddleyl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgulpcvc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ufldfbby.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzucnxn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzjmmdq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sixnmhod.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcgqnut.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dwylqaga.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hroiqpjz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gefbkihk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqskcszv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cciigapk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2txtcvntm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcxxrkk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cypztlpn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvxsmca.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zthcnrbv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcjglpl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2umnzsklp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hsegpaee.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ontfycim.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdyxvhy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bskmczfa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2usdmirzn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnkjppe.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcsglss.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pnakoxlb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpwonkf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bvimzuov.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxsqmhb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhelmdy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbhxcoe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdblipp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggodxpwb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2elfcznjs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2edagnehj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsexaxa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wikltzyq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prhthpgx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyjwong.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zeicgjhh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmqqzul.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkrflli.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiksxif.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfandqf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2izfsyemg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2caddiexe.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xqodnryh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqstwkd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoejzny.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdeqkfz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnatden.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwumgqse.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2avfclprt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdarnrn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcacqkb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdtxlhu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qzixyxym.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudyxqsb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyhzqmy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwhccvr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzajmmg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoapwpw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hefolyhw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxhmwkq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2szcjdqzk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxopbrv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgpieqx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwdrsub.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kveplwod.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvivzzmv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqkqbjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwsgina.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2acyeniay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwbhlno.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2smxmnfbn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvnpiwr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfmpmsb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gqifirdf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2czywkxhu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpkueqh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zjncgnvx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcvgsos.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcqzizf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgbaoif.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyjjktv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2edxdrmcb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsqyojd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzcdhxb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2laqvbksv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqsomfi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfygijx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mepbchno.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2blwwsgcz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlheehb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lcouauqk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iemlreru.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqxgyzy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpuguqp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrewlue.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkggwoy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sureqkns.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqiaxyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxacmxvb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2okvjzvhj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owimloty.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2witwlhiq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mumucqtj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwppalao.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qctdxljl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cshzjspv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyyyfgi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2prvzhjvl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iccseqjc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiiatkj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vyejukqq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzscflix.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjjrmci.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cetpwrdu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuczkclx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyukqmo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvaulxd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbabvvqa.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhffxiay.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgpvgpc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mowsrppm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxwqqar.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zonphbmu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zgikoekf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szopmdvy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiqjecq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lciiqmrn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cmslbuvp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxwbvqy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2itzqucom.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdwmkgm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghorylxr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwydggj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2koyspqvg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2duervcog.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trcrglih.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygivtmrd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfqcqbm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hipslpqe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cebusiat.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pegqrkix.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhbkjlf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2umrwmkyl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvtpkpn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeqttgb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuyuvua.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nanefroe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eocnalao.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmloeqck.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eetypizt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qatfmcsa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vsycjlda.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2naatehkj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgllece.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fscjzyjr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kazmvgvx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2glxfjwqt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2eckrvyte.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyndbem.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzysvbfc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwixvky.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwgwhli.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzxrupu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2anrfjolb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbhkijj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zozauanq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpqxdcp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrwbpqq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwfqekd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aohztllz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehswfibd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2joxmgkyx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2buglrhgu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ezganegl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zpllxszj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoczrzi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ybppawpc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kopuotfo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2irwegess.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iocshrvp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2faoyajqa.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnkrkff.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcroyfss.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2birlteni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tsljfsuk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuzehwt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjgswul.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2urvxxqhq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgktwer.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mycyinww.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tcheqjiz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2argbsnft.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnulknh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qunjlupn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2csevfnsn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtfpzkm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzccece.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2boacffym.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2djeuompx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxchmmh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lurgvlcx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzvqyiv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gulccpaw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ksanucez.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxhitpu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoqkxqn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2prgyeuim.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqyqidl.html


<!-- 参考信息 -->