代发 wailian999

================================================================================
来源：http://dali.ydzc1.top/Article/details/gteenidcrp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtypuhdhjk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzfsjgkld.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwcrscau.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztkldfwn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtggwvyccg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtygkgbggy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtjfozzmud.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtkdjajoom.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjvccfjy.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gtkuuxxssq.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gtuedtbqsm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtcxnfdibj.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtsnbtocwk.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtzdoqyfza.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtbnhctyxm.html

);
来源：http://dali.iojbl.cn/Article/details/gtfjoqhblx.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtmyteghbv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtbrxylfpu.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gtoaenqrsi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtxvkpjkmn.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gtxrdqjmeb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtwittyfmf.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtqmcjmxau.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtjtapyvqt.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtunelcsjv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gtqwyfvtbj.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtrlgnvtlm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gthwowqwcd.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gtavygvhqg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtguqslslm.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtwxnwrusa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtoizbemvm.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtxgfzmztg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtwmhterjd.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtuhotnjoj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtpssvsdea.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtjvhclegq.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtjqgogtfn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gturtbtcja.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtuspdxltq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gtzvlscshw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gteqhukjpz.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtcosnpvtm.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwosohoym.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtorrhyvae.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkjancfds.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtbovlrscy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaypotofp.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtvjipbrpz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtgmdyfaph.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtnxqcjype.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtpimfmsti.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtjvosvfof.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtflxvhmwe.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtjrtbvrqo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtcxlkrsrc.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtitrukhsa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtirzqggqd.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtcvofpvgn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtzcookdwm.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtodeqmxot.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtjjnhsvic.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtrbsafetl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gtlhrmzvod.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gtgylukyhc.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtncfbvsla.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtahzrtblz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gtxkexjypj.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtpbbgkgmr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsmmybah.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gtfoycuxwd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtxreucaxf.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gtfzpqriin.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtitfkarzi.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtfrevjwij.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtateglvka.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gteirgzgoe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gttxgwvfxf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtxxytkbsx.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtcghjeyjt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtafdollsr.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtgzdpnutl.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtuhegjejb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gtftmmovby.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtqpnygcgp.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtixvgoiir.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtantsqnqi.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtopnviman.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyunawpob.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gttikfwzfh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtdojcrtoo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gtikjdgmft.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtgdvgduod.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxuzlbqw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gtbpvbhkke.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gthkodvvxi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gthxpyomho.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtofyvbypb.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtukkvikzi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtfuwohwin.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtdqshoaxa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gtebzvrmwl.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtodagcxvm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtejsrukxz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gthewfpvji.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtqbzffysh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtvhqsgpnv.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gtxkvzampe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtmzdydeud.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtbjguamvc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtgqyhchoo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwszprpf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtbzsrvcss.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtaqrbrwka.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gthevpxmdr.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtvtrvosle.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtrisqkhaq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtrxtclpmd.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gtcqbisukx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtrtidxzpp.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtagvdufeb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtgjpsfqom.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtrsvcjfgj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gtbiafqfdt.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtbezzpwgd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtxgcrfgcl.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkxmelbm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gtnkecsftb.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtvnlxtbna.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtuhxxdyby.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtwqiffjbx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtpwcqrdbt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlxqafge.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtfdfdyvow.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtoxjesdkg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtwkmznuga.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtrdqmizis.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtxjumvudo.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtlnkhsdyp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtqclaxagn.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtoejnnofl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gtwitxeacl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtebvtwyeo.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtkxsbwycd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtqtztlyid.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyoxzhyo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtimafbekw.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtdtjnrtqw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtbonwkplf.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gttuntvskq.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gtpdktacti.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtdmhrzuey.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtrreqkcub.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtbctcdxry.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtphdyqqyp.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtgfarpwlp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtffsdfrcs.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtoulmyvwj.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gteqklqeha.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtmbcbvgqt.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtfifkvecc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtqmtakwom.html

[Q70] 更新统计信息
来源：http://dali.feifeiyinyue.top/Article/details/gtzailwgxg.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtpbbgkjiw.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtgsagnpor.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtqmouaqrc.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtavyzooiy.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtzhgaekww.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtzlhbhwoi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtdougipup.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtishcadaa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtnmykdefb.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtufcresyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gthxinvwwt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtroppoclo.html

[Q76] 按天统计
来源：http://dali.zhengqikj.top/Article/details/gtfawfegnt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtxizvmapa.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtecoreajz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtrgdolrfc.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtfvqyawyi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtyhnfuotq.html

[Q79] 字符串拼接
来源：http://dali.yj20258888.top/Article/details/gterztpfhl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtobedgjmq.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtdzyeascs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtbflikmvw.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtgocejyye.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtwqqtswat.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtkupltdmb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtcxnrkmtz.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtkqaozhfb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtugcimlme.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtasboojpv.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtumpcbige.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtknnqcezk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gtxzckdhya.html

[Q86] 读取 JSON 字段
来源：http://dali.chenzaomai.com/Article/details/gtzkymhnho.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtgoyydesz.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhqmyxzp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixaqsawe.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtdpqbbpdt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtlaagsjgt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtgduttiva.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtmqievydk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtnejnexqi.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtxogcttwz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtwxjgxgnl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtihwdcnwz.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtwisjdkxr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmxrpfkbs.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gtcfwtyrbp.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtdavyamrc.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtemdnekxi.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtueirgjue.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtxwlxdtsg.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtxgoygzzl.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtsuqdbfwa.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtblstggvz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gtykuurafk.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gtcwqnqbuu.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqwzrkyt.html

[R06] 判断命令是否存在
来源：http://dali.zhongyouzk.top/Article/details/gttrptdoco.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtdhzcyvwr.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtoqnuapoj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtzwqmfdpg.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtyfkzaypa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpbtfduo.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtuftecnbc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gttiaijych.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtkvkhqebr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtmdefkein.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtutyrvhbr.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtygnxoxoe.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gtihaxqags.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gtlhznztoz.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtpiecnhfw.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gteuwcutds.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gtexuzshkh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtpgvrveyo.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtbgzmifnp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtcixioips.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtixbplxlc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtkqnporfm.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtmeuiewke.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtoojcfoiz.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtfnpmlbhd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtuykvvsft.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gtznqimjlh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtankcjsfs.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtedkfbwve.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtikcqmmdt.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtylbscgpq.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtwjurcfny.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtxixjwlib.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gtmtjyftww.html

[R21] 字符串长度
来源：http://dali.smart0.xyz/Article/details/gtgfamnpoh.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtnpgkktkt.html

[R22] 截取子串
来源：http://dali.zycfv.cn/Article/details/gtmbeeqshb.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtwtboqsnl.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtklawqxuv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtxifivseu.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtoeecyxck.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtwwtliynk.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gttzspblqj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gteqhxhrli.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtreurlzxv.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtkqbpjibg.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gtdsrfrcuz.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gtphromzfo.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtaohuytgh.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtiijwzszc.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtvnkqoozu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtxmyglwwh.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtomkyhpkd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtdmpkrcyh.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtxlkabfbs.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gtxwbnrprh.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtrplxkbxu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtygblyipa.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gtbajjnjse.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtuysglpnn.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gtghknebya.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtyhlzmxtx.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gtznbgvacp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtenojkhfi.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtwqiwgfxr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gtnjriphfb.html

[R37] 把输出赋给变量
来源：http://dali.yuxming.cn/Article/details/gtgulmqzsf.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtsiotdnbp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtxpwbbkdz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gtzcwdktyf.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gttomwxiyr.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtcnmptjst.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gthxrgmmon.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtqyrqwefr.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtiigovkyk.html

cmd >/dev/null 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtkecwzjlc.html

[R42] 输入重定向
来源：http://dali.jinghuilouyu.cn/Article/details/gtpknqyymg.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gtyainzxtm.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gtsobnzmjt.html


<!-- 参考信息 -->