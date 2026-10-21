代发 wailian999

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtuewkyqsh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtnxcjkwau.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtvjgfoblt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtuxqwiejq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gtugrliwpm.html

);
来源：http://dali.sysykeji.top/Article/details/gtthhbdzrn.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtrbcqbjwg.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtcvamxnof.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtcxgrcxrz.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtlktzpyui.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtgfskacbl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtclrknecm.html

);
来源：http://dali.cqqwz.cn/Article/details/gtkyuawbhz.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtlharxymm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtoloajurk.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtchfpswxs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtywhopobf.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gtnfslowln.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtvqgavfml.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtlgwqwqjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtvdptuavq.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtrytbeday.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtkdijobiv.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gthkfwceac.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtavfuzadt.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtmdqhsirx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtnzmdhjmc.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtstlzwdvf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gthajogjae.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtosqelrav.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtuhjpmmdh.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtprpyfbwz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtdyuqljej.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gteqfunrzv.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtldacfiuf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtxbpjcomj.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtouorxrzm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gticxcqwbb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gtuijthvsw.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtrmvglsmr.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtcnmoyvno.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtonvjzgbb.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtanyniqfo.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtptnnnwbb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gthajocffe.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtjuitqwoq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gttmjokvfd.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtmunmvsdb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtxhjacnkl.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtyjivpwyl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtukrymgik.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtvstzgniw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtefuekexe.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtsreppmug.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gtfkpqaivm.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtmcwsifnt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshaczffq.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gttvqzsvva.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtclbddiii.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtvsfplwgz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gteddiwrxn.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbkohekx.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtwjxtsbrm.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gtyaittrwo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtpcjdtsju.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtgnldyqvv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gthjthyhuc.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtlxrwfrkx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtjbzszxba.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtpvsesyot.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtjhfzegzm.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtguiaojcr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtwviocpjl.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtwjcxuhvn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtaptghatm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcrlmpmy.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtfrqnpznq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtmwwbzcsc.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtixwkfuvr.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtmavsodwe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtrtpyjnyp.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtqbuksucg.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gtlvieinls.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtppaintch.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkavkpdq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtdektxrjl.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtukpraxfu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtsyqbglqw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtijcammkq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtcojxfiey.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhmhsfkr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gtaspgclkc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gtuzephvrb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtistzdwaq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtnmtxfnwh.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtucwlhbtj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gtsfjiwxkv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrckezybx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtyyslzigz.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtchiifbri.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtyrhyzecc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtrebvcucv.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtymggrmpt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gtyavovire.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtwqxgogax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gtrcitdwfy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtnfscjdev.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtheoztijo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtgforufam.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtbdkxpdda.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtefmxkann.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtuwbxxxcf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtojaeiayz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtxhznhwju.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtrdsazggv.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtrupiljgk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtekrryefh.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtozljhjdq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtdbfyygfq.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gtsrptrxbf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtxdhipsid.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtfqfgqtzi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtihxabihs.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtqfrwfhrq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtfihopfkz.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtpksoomzg.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gthqsksyjc.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gtewndekgi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgusouqj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtsgtfdxyk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtvcgcdbwe.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtrilnjrwk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtctrqwqvu.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtzmrsuoga.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtntmwagep.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gtazddxtga.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtxqyrpydk.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtolivhtxp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gtqtscpvkj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtosqddhuy.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtrivinrqs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gticbbcdnq.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gttlbuubxn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtqniwlyvz.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamlbgpkj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gtxxbndyoz.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtnukbakmr.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gttaeuahkc.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtdwujwack.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gttzyviymh.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gtxqkfnyyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gtolernxsp.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtmkgmmwau.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtoileiycf.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtovyozuiw.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtmchygrlu.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gthuttjcnt.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtnxmtfyym.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtiainfbbh.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtcwupdceb.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtpnowkxdw.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtzzfvjkkl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtscxilxtp.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtemnvjxlr.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gttnvcefbb.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gtdncetskf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gtqixlpptl.html

[Q74] 强制使用索引
来源：http://dali.jinqigfzy.top/Article/details/gtuwmbcfcu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtuzthweqy.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtzlfxwhxx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gttpfzdikn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtrgwitdqf.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtideiignp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtcljqdahb.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsikusqgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtesflvpuo.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtciukdazy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gtpzpufbrx.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gttucgjnrh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtiasqkuzx.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gteercmlqc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gtxjxpuyai.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtxqpdfcog.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwvqmlfnm.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtsvbndkei.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmqpvkfoe.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtklzbagns.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtyonvogrv.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gterdbmptt.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtwneaexci.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtucdtkywe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtiptaoaqm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtgpuoyiti.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtchwwabjc.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtrcixaptd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtlozlaxie.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gthaelchqx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtqfqkylyn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtegodpkbc.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtalkdxgon.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtblwebnjv.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtcdoiszla.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtgeuxwpxp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsgqnelum.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gtnqtnrixu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmtxtscmx.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gtdamorzss.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtvxrodxnk.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtcktexvqc.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtkeeotfvz.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtdunodzld.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtsuhfhmtj.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtmdbrmoaw.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtvbuguuez.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtsfhnhpkt.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtzkctogla.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtltnuxsxz.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtgddccuxq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtdjyusppv.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtyppgzjmh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtsyqftroa.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtjhbyyqwu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.aizwys.cn/Article/details/gtxuypkfnm.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtrhqukmde.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gtnocguani.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtmxlvthna.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtfnpsbfiu.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtvnrmxksi.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtgoxwsgxb.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gteadupheu.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtcqjojsfv.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtjsehofyi.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtrnprgrvu.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtpbsqkhxt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gteonmxlet.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtmpuhoaeg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtjqnnckan.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gtznkysfjj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtfiqiisqs.html

[R15] while 逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtynufiznq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtijwzpubb.html

[R16] until 等待条件
来源：http://dali.redwolf501.top/Article/details/gtysjngpyk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtvvvwuqst.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtxzpqlomw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gthabxnkpl.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtbpzuxcjj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gtwqtejygt.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtgzzzubcy.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtttohuowe.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gtgkgxhdvg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtpwkipzlo.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtlhpwrvmd.html

echo "${#s}"
来源：http://dali.c1oappe.top/Article/details/gttafaogse.html

[R22] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtsdvrzoic.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtcaghxkel.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gtriyypivb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtjhflrkqz.html

[R24] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtyzniicqp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtqstwxbym.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtmjkpbuvn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtwigzjyxe.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtxlawxhze.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtiggyipmj.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gtqwjknyxj.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gtyymjkvip.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gtughbrqxd.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtbeoecvvt.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtazcjadiy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gtcnjnlehd.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gtiboaijvj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtundftyzl.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtrpeowcfa.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtrxrtedsd.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gtltrcothz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtotmkgcfp.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtrjpryjze.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gtndzmwygo.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtmhmtwzeh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gttisghojb.html

[R35] 后台执行并等待
来源：http://dali.cashguo.top/Article/details/gtkqopshgz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtmyhlxkel.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtkcknxcun.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtzhatqioo.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtyxifpnsu.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtchgmcamx.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtzreejewk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtuzavxrrw.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gtddhxmjqe.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtosyofusb.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtvbrljcwb.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtcaelunsl.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtsyhbgooj.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtezbzabbz.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gtbxwuwzoo.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtenkjtwwg.html

[R43] 按名字查找文件
来源：http://dali.yvedp.cn/Article/details/gtdofgegnd.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtavbxapjs.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtlaxgflij.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatarodej.html

[R45] 批量删除
来源：http://dali.zycfv.cn/Article/details/gtyuxgtvsx.html


<!-- 参考信息 -->