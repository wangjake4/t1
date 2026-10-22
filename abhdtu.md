代发 wailian999

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkgnrclny.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtbvdkhabh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlsjgkucz.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtazgpgzdb.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gtdwpneqmv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtagwlpvpp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtrabxcgpo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtsawilmbk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtuyquyhrf.html

);
来源：http://dali.316326.xyz/Article/details/gttgnsosfg.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtrespbiwj.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtovclcvzv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtajyldrbo.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtwlwrsygd.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtxhchnpah.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gtdnysaiza.html

);
来源：http://dali.cashguo.top/Article/details/gtqxayecdq.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtvgvtosir.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtsudzwogc.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtijvkambk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtierpburn.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gtjewlcqaf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtjwdfirmp.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtnklvncvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtwxocoiee.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtyjpwwoos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtfkagsynx.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gtoypynttb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtwvjmhvsl.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtmheajmfk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtpplhtfsa.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtbiacdjar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gthzkekbii.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtzmfolgeh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtyezawtbx.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtzecwjscs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqxtesjl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtdoltjihp.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtayichcth.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtmdzxmfmt.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtwmewehlo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtoxumnmws.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtfwphvytv.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtfojdwtnb.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gtgputqrmd.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gtkdyiyegm.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtqvtzcjuj.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtwajreayf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtldcstfla.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtdmdedrix.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtueujxhlx.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtzqeamost.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnlodulc.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtwsfeymzs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtfgnetues.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvizkrtj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gtvalzwsxn.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtdumzgujm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtrveiqbzr.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gtkzcuyfwv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtwxvdfpdp.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gthpucvmkm.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtrwntvufw.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtaijeukbv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gtpbsksstr.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtfdhpmqbl.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtwxamjefy.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gtfifeuqge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtaramwxkz.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtgbdlnrvm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtndinaqse.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtcsaicobz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtmmcecspn.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtgkcvuxdu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtalrallxv.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtczxrwrsz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtikxjumld.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtigrzgyhk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtaamclwod.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozkehqqg.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gtduhzswad.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtwwrjlwts.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gthwkouyfn.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtbxbkhiyg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtuzzgwdqd.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gtwnsqdjwe.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtblpxdcwv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtkkfkzsvp.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gtosqojkmu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtqmpmjskq.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtmpqkwtpe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtnznsrkcx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtbmbrqsoj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtokmrvbgn.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtaqnvfdii.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gtzkbnsgqp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtgnfakcio.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtmefpaebs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gtilsfcmcv.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtaeeeejei.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gtrjnbhzjq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtsgenrdhc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtuadvrkgw.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gtuwpsenwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtpsutsxra.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gtwrdolofd.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtpmgxecja.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtkatoybvr.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtxgpannfc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gtovdhurcx.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gtinzpdcii.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtwwpzhyiz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtuuwkvfel.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtowftqlic.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gtuwvyhcon.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtinrmmcby.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gtcfsascdw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtpvxuhvgi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gthyhiamtb.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtqgqtdsks.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtcfrfllyq.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtzsyzxxep.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtofsivfuo.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtplgjeylq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtdclfmvgg.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gtmiqfggoz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gttvimywsi.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtjqklaszc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtyyywtdms.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthagnggcw.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gtjvloczwg.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtoklaawcz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtemrgajjk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtmqsjkuio.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtzeaafess.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gtrrzzghhf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtcxmodutz.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gtdkjynqtl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtiwrqypeh.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtgeapqptx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtsnyarnho.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gtauohlxmh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtlfbkfwfo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtvfxwhply.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtkwdxhubp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtzwqxizsx.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtfnzxhyxn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gthjxmhhjs.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtsbqfxxfj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gtlogduxdt.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtgptvkxbj.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtkbpxqffs.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtzczbvmdp.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gtbsdlafyn.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtkwdmyozp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gttvmebrur.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gthwopicku.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtvfgxnqyp.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gteflwxkfe.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtzsmlyshv.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtnixpcdul.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfekgpuke.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtelnbikgp.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbysvgcd.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtfzqaqisw.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gtauswpzqj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtjunkatsj.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtbcjfvssw.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gthiswyhin.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtjfqcldsd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsskwwzb.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtfpgltpny.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtsifxqqno.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtfdlemcvu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtouwqzgns.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gthubdpjdx.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtnamiamic.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtsxvgabbg.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gtisatpuxf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gtbsykrgrs.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtgswvghgz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtolrfcvfh.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtarpfhfkw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gtjhcscffl.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtjcidjxwl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtcxhlycjz.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtqdikyyyy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgrvclxty.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gtyyjmfzdo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkftqkzel.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtwrlwnpmi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtowzreigz.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtcispibgr.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtycocuggg.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtireyuwpj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtingjclab.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gttsmdipfu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258888.top/Article/details/gtvxhmjfmp.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtqfxsnlua.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtplkuxjss.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtupnclojo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtacofzwph.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwfbmjodc.html

[Q89] 判断表是否存在
来源：http://dali.yuxming.cn/Article/details/gtiigmuodm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gteictfaab.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gtmqqfidoq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtxamntmhs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtugwjtsre.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtbowrzaug.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmwzvvsev.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtarfnnzse.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtaifuqdwc.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtnatqhhkn.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtgjrsizai.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtatwxifmk.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtnpwbuhbf.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtfumabzca.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtvwqixgwo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtifwningh.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gtsxofuurm.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gtdrllgukg.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gtsbzkkfpd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtapgrbgpi.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtleguntic.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gtghbmodpn.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtpbrfbqaq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtfkivutoe.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtfpymwcbj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtjpcvclgb.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtrykecklv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtzyhopkbj.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtijckdmyj.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtmmvointv.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtlqhjbicr.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtgdshbwal.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtbzgruntl.html

esac
来源：http://dali.xziqi.cn/Article/details/gtkcsfukip.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtjktjmltn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gttfmvroqx.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtgyvofmfw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtwiqvmdiz.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtymtytexp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtxrsxnsox.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtlbcvpntt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtjgvjbegd.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtnyqmjmzd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtggdxuefo.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gtkiiidmmx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gtedonrlyj.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtjgsgycck.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cdnleiting.top/Article/details/gtgduxtfla.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtjojafbek.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtlkuhnmme.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtyhsbfoxf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtlfziyejg.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtcxwwczwv.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtysdbcztr.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtrtjxrtgv.html

echo "${s:0:5}"
来源：http://dali.kuanghao11.cn/Article/details/gtbmbecgax.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtobcainka.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtgbxdcmda.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtpgfscmzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtcsjdoedx.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtwddgdczm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtjrzctcvg.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtymrdshjd.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gttrduqomv.html

[R27] 算术展开
来源：http://dali.yj20258.top/Article/details/gtljohpcoh.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtbeegtmlw.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtnytehwce.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejblvlfp.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxygbhpin.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.c1oappe.top/Article/details/gtswzmurri.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gteliilnsh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtqsiiasfa.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtrkyvsmyk.html

f() { local x=1; echo "$x"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjswigcug.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gthgcemjkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gtkwyzzahe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtplqsdjlw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtlfdfuoto.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtrfdfmsra.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtngoofpll.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtdriknbxy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtvanwdmwh.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtxirqgghx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtqdyfowzd.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gtlvlsszdj.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtakidbauw.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtlaxrxblh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtuvwwapal.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtbgsalpgt.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtqubrscpw.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gtzdtgshku.html

echo "log" >> out.log
来源：http://dali.jyoumei.cn/Article/details/gtcfppsmbm.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtwrkmdhfh.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gthqaxelhl.html

[R42] 输入重定向
来源：http://dali.pycfn.com/Article/details/gtepekbnxb.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtlcrfxxsx.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtohrhlgku.html


<!-- 参考信息 -->