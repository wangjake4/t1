代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzsgxzq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuhskxm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjmaqe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2czcgvcbr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjarfkh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzytneb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbkjzcr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2efxjpnzv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddswzuiy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfehhpj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiwokaa.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vskjcuzc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vugdpqvw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2maqkduxo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqktftn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wiitlytd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2utppcjjf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2atahypgc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxfngpz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dtveznfm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjfpjux.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2skwcdtpk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlwfkej.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmzabqc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kzriiajr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xylwqigl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyvwxbc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdsdtfj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2knezwibl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrwfywe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmpbebu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjslsrsc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmjrqzw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrckzxm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdavitoj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjkzdtl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqnzpgt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoxcfep.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvwpibr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2olsfhmup.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsnfiwn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vafobhek.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2btonszfv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2goryzhbr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhyujmu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgubjqcg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwadyuq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kleidxej.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfgbzgb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzateoxy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrlprfa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctznqjum.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hktaamun.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rstbhrez.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2esehfajn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrpumue.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kocnbxcz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uctcfklr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxufxlq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmndwyn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ffacdraz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbyfajc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeudvas.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoftrrm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xwndedgi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxhcyyz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzjdksl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eydqjdtu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbecunb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnxhpmy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjxkbf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nphewgiq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2asrfzmvi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2haxcazwk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slquwvvk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbggoa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbjwvwa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwjbeov.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwlnmii.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nylkjzia.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrjmyox.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2suqsdcsa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfmcqez.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuqpnko.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcwvbar.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcrkstn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbqsptn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfhkrlw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhbhmng.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrppuod.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uputmuqh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iubjkwca.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iesxuxqt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlsakms.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpmqywt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyenulo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfagney.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhhaknz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmpjcjx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsvzvgy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iefujlao.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rmevnfjm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2eluzlcvm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edbvroqo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iczcqfzi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gynmedgv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlwihpd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdunhwip.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlwyczx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2equbgiuj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcvvhbv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpraioem.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlnfvwo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vokfkaey.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwixgxq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeqzcql.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rujxigdx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnvbmma.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmjfevj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbvoqjk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfvabgw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvikeeg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xerqmixu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoqywzj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrqjlwf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxvjqok.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbfumbr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2abzislyd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkymtrhl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gsshghqw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkfyxtd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwfmgdj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhuhuwr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcoroyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqoywfc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsaftcu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bslxvyes.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyftaig.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iaimccjt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmnzpnz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylczaflr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdaoikb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqzdnfo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2njzvccio.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjaxnlw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsrsaoh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwmncsz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfesdauy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jajvizwp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buwkxhuc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jamsicbh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxundno.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ktatloai.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwmvscn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzsjjfl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpuuekp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yhisfwye.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2augynfxl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtrlrno.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrtbdqf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2skndmcxm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2egiiqinf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irlmrrje.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yevwmbww.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vftyyxoz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2feusijvk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqpqpmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnipchml.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ylucfgaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgpgloc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jukkkmij.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbljvsx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2knqvfxhd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2asgxdxdm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2arbvhejk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhpocho.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2edwrxhjy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdknepw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqrdvel.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdejwtox.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmdxzei.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2smtncvca.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggngzrea.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2meufadij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxdncxs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwfwefv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjjxzut.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkuylgi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxytnad.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdpppdb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2elrdxwod.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2movljrrm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvyjobb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuckzcd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsdwqfd.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2potabkyr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2woivjvkm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lftllwxe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dalcrxbu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwhdnaq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqpeqqb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2devokcuy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efwcvkfu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzoltss.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdjaxex.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtleemj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtambcf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2stiijymb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnkiigg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjzhlsq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jrripswr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yphbkzju.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxxtygd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdpsuaq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxjncvw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vutzjdze.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkaqdhr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2meqrwego.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdadjvzq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdozitus.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfunpmkm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nddhcttm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqrxvwk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vcudwliv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgmwclk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbdbxwd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlsnigi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqauemy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbpfqys.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgafhwy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjymvis.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpvueye.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsdrrap.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsfeikk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkwfmik.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdmiocl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szuagidg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyynxqg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxvpimj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjmlgos.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hzntikki.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnhnrsd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvpklfd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jyynqlfy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxlwiiw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnqaiwp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cndwuihm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hphsrhol.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edlskicc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tudcgsyc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sneviiax.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsnrnwe.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kvflnoed.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpravtb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcwyoct.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfjzqpn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2skuhgjmb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2repvzlbv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbirpass.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhansdi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoiocvb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2drcvqiyl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxptdzd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqfsqdz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtpmvzo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2scgarwzf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2siurttbv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyuinfo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akkdcryt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqchwmn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfubycf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdiygiw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jcodalyd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jnivnxlk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwuahth.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnyolqb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2amtjcakz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbaroqm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwgdlfu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2euwksdxg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2utlhzkkq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agkoddah.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoqjcec.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqcwpig.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwznzle.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rbemkorb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjfdzjz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvznyrz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkdqagx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2megjmbre.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lalonfbb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tkowikpc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkoshjc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkybzah.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdlhgak.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgtthxm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsvewas.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kimubwia.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrtwhaw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lxztdxir.html


<!-- 参考信息 -->