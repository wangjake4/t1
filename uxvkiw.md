代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhntsedq.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtchqohabb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtbdjyjdrd.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gtydutcvzx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtdvppmhnn.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtsqurtjgz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtgjjazjmc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtwkamwcmc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtawuwypwg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtpbtsmrcl.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtgtwmcfsa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtcbhwsdbi.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtptiwilue.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubbkgifl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtkxtyqjvf.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtrsqljzqz.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gttnvwtmwm.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtwhbjjxee.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gthfchxutn.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gtticnjmcg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtkswmykcl.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gtauymzmpo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgrggngo.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtjpipalvn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgmgkytg.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gtncbbuswb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtoqotoken.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtpzbjaepk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtvogcyvnk.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtippkutmb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtwzlbabyt.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gtsijbwfke.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gttxvfyqkb.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtrmdofhqm.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgkfxiyoy.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtzqrkvgib.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlighobkq.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtnwwgtfvr.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjzrizqqc.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gtjedwpgqn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtjigfaudr.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjfomgyb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtvrxtvxwf.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gteclmhmrt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtlbagrdbl.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtofljbcax.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtmbixqzzy.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtqiwuvusl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtyihataks.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnedktnr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtibunwmsm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtqkcwktwh.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtttrbhomw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtsqadxdus.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gthsnjxcdv.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtzjdriwrj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvobdjlhz.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtmwpxunnc.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtfahebisj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtbzcvixdt.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtnxhbzffe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtmnstftza.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtubugvwtb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtzctomdfl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtufcqcrle.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gtjuapehgd.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtfjcuhysd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gtxztwcnpe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtosyfmahj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gtbxdtijwk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtsvtyddsz.html

[Q41] 多表连接
来源：http://dali.jinqigfzy.top/Article/details/gtwkznfzqq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtvpkqmmpd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gtbusrfmqw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtphwbkmud.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtseawtxwo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtkhurvcef.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtwjsjyrou.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gtmpjcbmsq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtwzayfmdr.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtsejapqbz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtsktseuex.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtzmiuyvcl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtockfselr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gteozahgps.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtjpmszmgt.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtnboynorn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtukxvemzp.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtwcroxnjp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtexzmmgcf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtudzobsje.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtvnmlzddc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtyfnqybnu.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtnsxzzqgo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtwwnzqhcy.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtcboplsdp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gtysdybyef.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtmftmwhig.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtvorzhoot.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtsugvzlhd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtjcbbkzpd.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gtisyxsusr.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtctyghsrd.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfqfmrii.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvugtitie.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtoznqlcie.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtglhzypqn.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtvsrbcmwx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtrqtflcxn.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtgcwcepld.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtjtvdvjyf.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtigmziugf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtkbqifzxz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtrkgcksvp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtykwmzqpi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtqnzluzft.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtsocrypdz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtrennpkiz.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtigfhcpfb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtykydsvze.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gtyirudcar.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtaxuzldre.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtgtdyixvn.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtlwmpquuc.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtgyidmmnz.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtjrnggups.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gtwufidtds.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtdysgcevr.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtjekppkgx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtawcsjgni.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtehxqffdg.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtmbgdxaxc.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtlupsbnjq.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gteywhmsfk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtxgkayjdz.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gtikkxnqhl.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gtgunqbyfi.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtwqnkgkuv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gtgvfppkdc.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gtoedpwmks.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkbuffeu.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtkmqkmppz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtztyctwyx.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtmtatoaib.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtqmsyopsc.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtjhplgyfg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtwgaavihk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtqhqzsiys.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gtxcmzbcur.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtedmpvrgu.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtnyswsvwq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtqapduqjz.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtytsofqmx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtditidiwh.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtkponmqiz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gtsgkkjmvz.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtqnlkpepn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtjtjoccif.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtvtdwjjns.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtepfhyvtq.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gtthfyshcq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoglsxolo.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtnngpuxvr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtflkiiifz.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtsyvrrztz.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpdfggjtf.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoguvsvmh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtmanefazp.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtuphxxyih.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtaozfsdxo.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtcuuymqwz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtthmnahiu.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtijbhkqej.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtemohpoaj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gthjaitcjm.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gthbdgymup.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtwdxylayw.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtejkqlabu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtmrkflvnt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrvdvsjwx.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtrgktfxcn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbpsbavjy.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtcfiwrsvs.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtnhznybkx.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtqhnmuedp.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gtecubqtow.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtkpcpqxlh.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gtqcnltueq.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtmoyymcio.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmailbgjw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtsobutwkv.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtugqezzyx.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtwlkzekfn.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gteuxlkdjz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtawrvthln.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gthejecipl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtcgotaven.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtajrnyuhr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtxtarsbsn.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtdtxjqkis.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtwtzoclxt.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtiggdburt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtuhpbtmiw.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gtkbcpapvy.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gtxabtmuel.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtxlpdvwiw.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtdfobnwaf.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtciueowji.html

esac
来源：http://dali.xinyue.icu/Article/details/gtycgwuvav.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvhagchsb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtjbcjjgwq.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtonxcasyz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtbmvoaoxp.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gthivetswl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gturcdmyqq.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtxnjgoura.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtwaiddgue.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtnqfkoqhb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtfupbparb.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtczajgrni.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtueuumvlz.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtbioyua.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gtqybhrxhj.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtrwbgzmdw.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gtcxbohrfh.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtlshxgctb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtavahztqc.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtrzypmzyx.html

echo "${#s}"
来源：http://dali.jiagoushi.top/Article/details/gtvgsynuzu.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtxvyrreye.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gtopofyfzi.html

[R23] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtrorfgrgp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoaklsdh.html

[R24] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtxxzuynoy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtqnnpvoam.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtozikfkjp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtezqdzyqy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtacyaufin.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtwduaarir.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtfapdzshc.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjgkokvq.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyznwqwz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gttrrqywcl.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gttxsavhfy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtsejrogif.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gtvcnpvjoh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtilwzfwhr.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtwixcbbzd.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gtarfqsgln.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtogahnrgw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtttfhyrdo.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtjajcpygp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtegcxpiuu.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtqahanzro.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gteoyuqaiq.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtjeegqwhv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtuwrykocy.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqwbvnou.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gturtxiros.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtepjngsil.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtqaakhjsq.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtuvwdizmr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtafjqppio.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtgxvqcojt.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gteytxcppm.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfnlfoxk.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtugrloohn.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gtzkteinla.html

cmd >/dev/null 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfggmgabu.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtohnmhpte.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gthiudqmji.html

[R43] 按名字查找文件
来源：http://dali.jqgufenzy.top/Article/details/gtuyszkomy.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtyzphkbtd.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtuftcdkur.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtcrvaqcou.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtuaiiyqrd.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtienkjqvx.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gttgnmhnax.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoykjvmjl.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtzzqcmkmi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtfysfensx.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gthyqatmun.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtpaghintl.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtbgqehqyi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtdyzixeeg.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtkoyjtikh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtnzgqoapu.html

[R51] 排序去重取前几
来源：http://dali.dashuyun.cn/Article/details/gtvgfyivcx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtvxbksvkf.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtpmvnfhfz.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gtvjdgblaq.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtljdfysqr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtyhjbpcoa.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtpvecfjls.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtseywcjxy.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gtraklhjmq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gttoztxqpp.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gttepukuds.html

scp file user@host:/path/
来源：http://dali.chenzaomai.com/Article/details/gtwtlsxcgx.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtkgwqbpyn.html


<!-- 参考信息 -->