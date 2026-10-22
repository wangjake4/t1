代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2frgxcklx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2joisldkz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvgfowv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bpifacap.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2socpzwad.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iesbusma.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuchwgi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtdmspk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2imhgocxz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzuxpuu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqqtqth.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kfywcyas.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qvycipcl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lovrfutq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfstlvn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pggmngdn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cswjmcos.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyknrln.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwilpnt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbyrcgn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fysowpwr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgcivli.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2osphjlzo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2exgzojkl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnvirov.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dedabdiy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwzuslm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrszlmd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kyofqdmg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxliijfc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbealli.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrwsuzs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2axkdnaov.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2paoekrha.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaombgr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2altdaggs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yghjatvv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2izwjferw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaiacpn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoxetaw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uiekbjha.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pesbiayx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqonqxfd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdxvinh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtmpksu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2khnhdzij.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvwtpsz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmjgead.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuipzer.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvbzvwn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnrzkzm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2noilnizf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kknawbod.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xopivoic.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuftjwb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pstzrado.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pawkpuyb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjraabld.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaqrwde.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqjkpku.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mewmkuwq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uajnkhmd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qucnrldx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzvflbi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aepfmuul.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnqnftk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwodqfr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwemjkud.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaexcjyw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ybocivvr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xktbepzj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbviivu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjakxwmn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2alujxrhn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2njtpazhu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfzyalx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jlesubao.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxdyihh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkgufyv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnlipho.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2udctoyjw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2stglrucs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtjzsgp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ykciflmt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rulonfch.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfguasq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rygirmtg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcysjae.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gknlddjt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2embgfamo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2elacddyz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvssjxlv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2swukdzlt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nljdfkpn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqmwkii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2teesaejn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbribuqi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbqtisk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eahlqftc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2koubvumu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dgigzvdf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2trcrejal.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxdohmd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmzjisb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hznhzckj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhikspa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2viywuupr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uklouixz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiutclty.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlowjfr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiycpyr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfftlii.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nomajqpu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpqtvet.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnxwpyb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2thznobqs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2foclircp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2llyovgvf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2drhuxazn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuhalom.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wtojacue.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wvspscfs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eatmlpux.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oyilairv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dirxonvf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2erimoqdm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mxinendk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2orxxpqal.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wakmttpk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnskvss.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iudyywbm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dehabwnt.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgnxjle.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhnlbtp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wszijoai.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqdyumo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qvczuejy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsweyiox.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2njfxizka.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzorqml.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gappaytx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wffivkom.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2sehnvknb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwinjsl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zehanrbg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bukvywxr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2izikkhjn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzrlenf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eicfuijj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cazvqifc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqyuewd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvppnkhq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdedakm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tbloyckn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzgousr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrladss.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoctrtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyakimbs.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wzghkfjz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlmiddc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kjahfepg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvitvnzd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxzdsdd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2secjfdyp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qajgiycm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fieiszaf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwboapj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uijqjbus.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npjkkhje.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2blcevjfn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpntvfo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sygdqlqq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlbuepb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2remxuois.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qftbpxqn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyihbgo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oylkxpyu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpiknnt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2orkpqwhd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2holjywnh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jtapgnam.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fatpxnqh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdjqfbl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmguhobu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cvujzfoz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gckrfuid.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwzkvby.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ficgwnub.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbxfgnv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfeiccb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhximvf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xptrrjhm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2plwhycis.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2haoktelm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmcgztv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcfwqjx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfejjbtq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oiroybnr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thvwelpe.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoujcvd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmnxpnh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzssvfvl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grfhjowo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjslsnu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlwtsir.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmkrluj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkhyyae.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsasnqid.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbxlcqj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqqaxks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lquigqxe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2usivsdup.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bigcntsu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dprfhefz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvguyhi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmdyzog.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdnrzsj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2depynvrq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nriliejv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qinsggtk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oswvdrzj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaxwozf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhujife.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxfuwhd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjglrqqz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pdebgbur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfynkok.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnvpekw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzwnmvd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2usvmvgpc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgdohgh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfdgnpp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqtcnwv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhlosvh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzzgztz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqpdjpv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzajpuvc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qguqxdrv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2exsmhetj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2obtbyzcq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tubwscel.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuoivap.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjjvgxf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sosnsuek.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2reigzvtc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwbudge.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2voujvkkn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmqgimg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rpidzbur.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzmdgos.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcpkgyo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2egmhoudt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2bjokxxlc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vclvhxne.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2porwzjte.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbraqdzk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2guuyjlij.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqayakze.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ooannqkb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtksuiv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpwrvua.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uztdijpk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anwehazw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnwylux.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsrdnqe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rujhqjin.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhamyjxt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcuxfde.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiwsdrx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjgdytp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlojllq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmfgkej.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bpczcbpr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yckqnkaz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbdikjd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvoutws.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqwucyv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gprlfvcy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dsclajxk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xudbzvpy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrbqnky.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqkoxez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uogecsqe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uswnfpkn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ehagxgkr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2topataer.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxwvght.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjehlai.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2clgbqqua.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fleehjuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbojhuqy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbzwpmw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2phlwwsmu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrqhowf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ttypitje.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnotfqsu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcyjyop.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkikfto.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkcdvnj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2whnjeuow.html


<!-- 参考信息 -->