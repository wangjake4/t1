代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mazetnbe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kgklrdip.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kquliezu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkiqldq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvomedgv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhygwsi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phwzkfxr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpozgrk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2axdourki.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvokjji.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmcihef.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pstellkp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzwqhvs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qitdtycj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyfylsy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfokqaa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cjczrwfe.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lznwstkf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snhuxazf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mddhjxxc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exlpvfdh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xafmonpa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bttlvyjt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqglpej.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nueykasa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kovkwlsc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlulcwfe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsvyrlq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdmqdjr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odbzkjll.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2moimsidn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjgcvid.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvvhnnj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgtgdod.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmhmrbe.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmpdohs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2uodvjter.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kywyimhq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2whiyvaem.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsorutm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxlyeja.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cudkvzzy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flusmtwy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eerhszsc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgmjxjy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxsohkl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzcehjy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzgmuju.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2maguluku.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqhilpq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bufhjmjr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dapidyzm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkqtypy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rkswjamo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkbmwnl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsrjljo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvtoyox.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqacacj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuqjtku.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlorkcsd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkuguxj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcttfwj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxfvndy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjbxlhk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsbxuyi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfddtdno.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuliwmm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrykmzrj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tskzqvko.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbqcter.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaajaen.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfoftul.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjedbvh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtgcrqt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jurnnlxr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqbzsqf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwvqrqz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2akeulsxm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyyplxt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuzorda.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gfenfyjf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjnoqje.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zamgsssb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpcbbvg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthezqwx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcjmncs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbzibmf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mjffpjsv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqqbpox.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkmkltt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpawpkri.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgumbwt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2efzlrjhe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pahpznga.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzoedsl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evywcgkf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqudccy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcndqfeu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyfpsev.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdsuzaj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kifnxnkv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wieyvukx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyysuqq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2apizrkjc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmuxjwm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2burijvrw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mcebqahl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfkwzmq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jyafphui.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmmkgpw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfhvaty.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdxumvd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snsznjgc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgbvuvq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2twmmfahw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oputveqv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qudxybvx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ivynsiab.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzuqpdd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvejsjm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeovaas.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dosqpzsm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiooycx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yljatbrm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrefydoc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjysinp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hluachlh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbogxwx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2echxnbva.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeckndo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2aonmtqsw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmcmoir.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzqosae.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2keqsfxke.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcckggm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkiwjkz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaptkjw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirponsp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2olqmtvmc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshfbgeh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhhdmpk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrybeltn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsepcku.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtqtgiw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeuilyl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eydpzjsf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2asyzjhtf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsvvhty.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgxfisq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzwsxfa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jysneetn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaouzly.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkydohy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2reugrvqw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvpqeux.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzcrrpf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xszoxawn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrugpmdt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jevsiqaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmrawbf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jghywnpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfwbtih.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ozywlrtk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vfygqzhl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaartnv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnamewje.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2crefxznw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcidxjy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsycwqg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2porfdhjf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlicqpwg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cninzsts.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhmmhju.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2phndkoqg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrikcom.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afbrjaeb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyzbnyx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvzfjxz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjkedox.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tugtqosc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fkckozrn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pozlfoaw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtllqpm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ievugagz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdaivlu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdzkacq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2duivzcrg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofucysvo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqpteua.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnavatah.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2juxyftvm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2apjllxxe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qkskvayn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsekcom.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjhgkxi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahujdbkl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwhranv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxpmcyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2drfxbleb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpbajyo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmudpgia.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdrabik.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkauslw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlytyki.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tghlqqva.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxysser.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnrldit.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2duiylbgb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvtilvz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxpwwqu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uepaggxv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kttnposq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjbgnhr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ihidvpwn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rykmveqd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcekvjz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvljlso.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wawcatml.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfivfcim.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzngeqy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2amqueobx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sctcnomg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoahnob.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frbtzhcv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtpysza.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ethtrujj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2stcjpfrg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edqxkxwf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jafitvke.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzsmuvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmiendn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2doepqavj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlermrp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yslmjqpy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlnapkw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmptdpk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2oftgguzo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaslibn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2opccdeuj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpeafoe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvoecwa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yfedyaki.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeshkfa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoswjov.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsmqlkl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2njjdhihf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lythstvm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfllisg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pavpqeqk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrwegyz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtiqgkm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fauolbdy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtbibnx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xpileizl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvgjgbc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2azxbompk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrlabqb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfesrjs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnnezji.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzsujng.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jexxgzpz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iaagsrbe.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlrsrpn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azsmxbtv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzgnmpl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxgjhbf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzamslfu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2aoobvxbl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqptolw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2owbostqf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjzxejz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eseqmgvo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ucctvcic.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2makhmvcc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbpeqqw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwtodje.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mypwfdcq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2somxdvnx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjjdmp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2liuzvgpf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbtxhoz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgxzwth.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzsdzua.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uqttjqpy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqadbmh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaenzgm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwzjxqm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrnxdxo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2axqjocqt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nywhahqb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mexqgmyc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2clnswwvk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpyqidx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuzcgyp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuygbusd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vtifvjfu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2delfinet.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2phxbcpgc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpqlvl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfmtmkb.html


<!-- 参考信息 -->