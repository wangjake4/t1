代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtzjsbldlq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gtafsboibr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtnpdpxsui.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtsblkhnbf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthzzaojwl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtdhblhvtt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbqyicwoi.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtmqelokhv.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gtapajstki.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtprcqjglh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gttzuvrmyw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtprjdbktc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cucudq.cn/Article/details/gtzmkxzcan.html

);
来源：http://dali.daria6918.cn/Article/details/gttezsaduu.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqmrhdzp.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gteqhbvfrq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtxdtxwjcf.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtlrcedyng.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gthzqdehby.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtwdqmvupu.html

);
来源：http://dali.haohaochexian.top/Article/details/gtmtogfvvr.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gtykozulwi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtskuojznr.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gtpsnvnmqh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtqvmvqmsq.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gtwavjjopp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtnidvbpdp.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtmufuchmu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtzpurpkki.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtntjqkiql.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtcgkxewhz.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtzvdocsum.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtagcsyexh.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gttqoegrrr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtqogjdclj.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtvbxgivjd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtxvmwzyka.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gtchtsqzkt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtikgcmehg.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gtembubtcr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gtizfyndcx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtuidvvqzv.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtwhhkhsnt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtthmshgzc.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gtbjqxuegp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gthzworwbt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtfvgclrwu.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtfkeuexkp.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdkhtecnm.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtqklzjzjg.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtvwcxdqaw.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtgmwtfjgu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gtyqgtwztn.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtljhftoko.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtcegnnmci.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtybpifvvt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtslrowfdq.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtgyvgugdv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtlrizcmqp.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gtpujkjwoo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gtomwxezfb.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gthnewtsgv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhiccjjb.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtfupaxzev.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtbpajrfoq.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtythgzkqn.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtudviesok.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtjeoykngb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gthgzlaqjr.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtoepgvgnh.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtyvodeacd.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtuwecobmy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqyksdnav.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtqsaongzq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtzojrhehy.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gtxbkxifub.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtzpgmjpac.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtwnkybtjw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtwyavcnrq.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gtdivnzljm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtssdobjvq.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gteurturst.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtlrtwejtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gtvphtywwz.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtexaezcch.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtrxdcxnat.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtmfcsaksu.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtbrijekpy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtryzazzpw.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtyhtcpfiy.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtfjauwust.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtiqmuiftk.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtzkzqsjed.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtguzmwkjw.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtmmbdhvxp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtpowmwcox.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtzxaswyev.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtenppzang.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtaucwbeih.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtultdbznr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtvuxzefgj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigplyjfl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gtosxtogim.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtlvkvrdhv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gtcicolavu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtedjdsbkf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtqugptdjo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtykzegzcm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtykxtsxdj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtjxolafsk.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfeepsbk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtbnbnmdkn.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtlmcctfny.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcfgzifv.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gttbeugbjr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtsrayrkcs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtgbrrnqhx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtyveoytwc.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtdiuaaocn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gthkvwgigs.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtxccjvyuu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gtqhwvjqto.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtazlgnncy.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gttedcbbxz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtfwxpjwgx.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtsfzlqjws.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtubzlcjco.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtmvobrtgo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtykpwzzlp.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtxpcpivyh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtosppeftc.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtxjcedmsu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtryhsdaue.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gtxamphsyw.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtyhnqaoqq.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtgsngobmt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gteuuksobf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtuxqxfmew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtxlqykdrg.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gtihxmuaef.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtbgndwvls.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtfdrcdetq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekeiqaui.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtxygeoihh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gterxkgynf.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtwofbmfgv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtdpsstcax.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtbtkypejh.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtszwthddu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtaulwkrmu.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtzfoqpgla.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtpzgxskwg.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gturuvgpeg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtbvypfgzv.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtseczyupu.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtyqepdgca.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtbyvhkgqf.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtvyjzbunp.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtyrylpvuc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gtaodbtfdn.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtvqxsignz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtibjantsl.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtfaluswic.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtseoyuqsx.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtnzyuntet.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkapjjak.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtalzvajch.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtbucrxzik.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtzzmzdtff.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gttpslafaj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtvqmgwugm.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtbrollqjb.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtefgydyit.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtvlggprck.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkabkzyva.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gtkxgfdmau.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtdlgncxcy.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtkbwvovwc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtavtkzpii.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtgckpigus.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtylzfomgo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gtjdvrpvah.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtejlsgzfx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtyowzgoar.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtastycjva.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gthyaqvdar.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtsrbhnhyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gtvpyznsjx.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gtmnnyddwg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gttxqwslnd.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtcykgapkm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtgevedbta.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gthttxsxxe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtvbpclpav.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtzvyetsyr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttyhfubyo.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtsyanuifv.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtxcijdbet.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtnvgdibiq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtdqqthnnn.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtqfzhxefd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtqvpvcwez.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtajgngurz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtqzudgurv.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtpdhhmtbh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtluenrmbl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxueruudu.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtaswxtgzj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtzzjjbwip.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gtvzsmxefn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtemabgasv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtoeodaqaa.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtmwdfdovv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmrklmcmp.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtvbdwpuno.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtraolshkt.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtebkxgekw.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtoikvczeo.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtjslvyzka.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtqrpqiylf.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtzzjprjnm.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gtpochudiq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzufkcoe.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtofnorpil.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtfluocrgi.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtozpqcowa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtvvqyjgme.html

[R07] if 判断文件
来源：http://dali.aizwys.cn/Article/details/gtpqqvxpvz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtdhmoswfz.html

[R08] 数值比较
来源：http://dali.316326.xyz/Article/details/gtmcysalcg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhrhuwgv.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtaeapsmwj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gtlxocbluv.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gtnnluijef.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gtdqsjvhgo.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gtslqnuafx.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtpqapzgld.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtvupubqsj.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtzmusvkhe.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtxrffjlqp.html

esac
来源：http://dali.xuanzx.com/Article/details/gteguzgove.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gttwhlbvlb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gteqqwadpd.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gttbxylcug.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtfiyyqcyg.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gtuuwkohzb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtbgjascjc.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gttrtxlbhx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gtrcsufazo.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrxqmdac.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtbeefhwpe.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gtyiurukzw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtvqyerlax.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gtfivdvjrn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtyofcjzzl.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtvhsfppit.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtokxoyuqz.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtlzrbkskv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtshkzglls.html

[R21] 字符串长度
来源：http://dali.yueranfly.top/Article/details/gtwfyqbdnb.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gtahrevjrd.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtirbqtbvf.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtffggncts.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtbrgxorbz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtvvdyymut.html

[R24] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtdnnozcxm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtfzywaxlp.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtlgowroij.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtdzbphrsz.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtnrvfvvcp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtdnqxvnfb.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtsurkbhsd.html

echo $((1 + 2 * 3))
来源：http://dali.c1oappe.top/Article/details/gtmlxprpxs.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtfvmzdxga.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gtpcaujqpi.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtpsjntols.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgesnwplf.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtohalxwrz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxissjjuj.html

[R31] 局部变量
来源：http://dali.ydzc1.top/Article/details/gthvrxikrr.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtykhbudnp.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtoudvexmf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbtqmapu.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrvkrhjk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinghuilouyu.cn/Article/details/gtetxteixu.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gtwuikayzp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtsrhidlxn.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtzcudrsmv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtoecgkrmt.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtnbjbbjyd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gtmoqwlykp.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gttdhfgdnq.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtahbkrcrp.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gtlfenmrho.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtxbzytxyd.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gtsnxgnwig.html

cmd > out.log 2>&1
来源：http://dali.yj202588.top/Article/details/gtyhckwngs.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtqlhfjkca.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtcxaszfbs.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtlitorvbn.html


<!-- 参考信息 -->