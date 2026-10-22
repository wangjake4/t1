代发 wailian999

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tyvrbpzk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gt2kchbmmxp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ptfbxbch.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gt2grhfctps.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2sbyqmptw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2ixhtdngm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gt2tstfqnfy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gt2tdkdyldh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gt2npxhrhad.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2sxseqcoj.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gt2wtrcdicg.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gt2bardcbnt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2lwoiufav.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2qcfshzdc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yoluahjj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2tacutfra.html

);
来源：http://dali.birdmap.top/Article/details/gt2dglgosaa.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gt2kdzwdtwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2xpjxahww.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gt2wjkjmfci.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sltfdigs.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gt2ogvztuth.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2fxicooxy.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gt2equvppzv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gt2pfzjwgpx.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gt2louxawvp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gt2dvprqtro.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2minwvymn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gt2scuompzl.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2naadrkcy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2rpklizdb.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gt2impkmziy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2imxiyihm.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2rhznehyl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2xbpztuje.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2zasolipe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gt2wvbtkezz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gt2ftczfutk.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gt2pegzmpgt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2gmbcrqtw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gt2cobhhpqz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gt2rhuwemyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfqlmwne.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gt2sfyryxvk.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2sjwsmpqf.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gt2uqubemdy.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2gcohmxit.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gt2zthnrixt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gt2rwyjizhp.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gt2brsoflwl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gt2ibilpmnu.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gt2qubrnlww.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gt2jtduanam.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2oaelbtju.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gt2fhedlrdm.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gt2bozojocs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uupcrndi.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2ucgvmlsq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gt2tqubogdz.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2txdeuxrg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gt2ihsymzoq.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gt2brakpjxb.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2odwjttpy.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gt2agbgtqtv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gt2hzleqbqx.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2bgzonroo.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2uqnodhxd.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gt2dmdjqcdx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2gzhzuaow.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gt2lrrytkhr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxvxkvph.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gt2izqxizyp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tickpwrc.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzxguheg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwrwzarg.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktfcvukd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2bpevyrmy.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2smjndgfc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2osheopdm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gt2jknxggvv.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gt2tpfdcjdt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2imyamdie.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gt2llmeiamt.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2goelawaf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gt2ipdmgxen.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2pdpvvjwa.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gt2wdrbfgkm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2scexivcx.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gt2ffyashue.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlnjone.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gt2dwjwphtn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gt2bloqrfjl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gt2pieyfszv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2wushjluq.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gt2qvdbigzk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gt2gzirypvk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gt2psqlbiky.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yongpay.top/Article/details/gt2eyuigfqr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gt2xzkgfqtd.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2kuwzctlm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gt2tailmebx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gt2fxratgoq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gt2wqsaepqf.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2scecbbgs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gt2qjqlgdrw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.0kj1m.cn/Article/details/gt2vmtdflvp.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gt2mlalhlwz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2wpknvoph.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2mcqfnvdd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gt2xhehodwp.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2tgljeqji.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2sybrfcnf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwnrvkrr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gt2imzxqmew.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gt2hplxxttv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gt2aydzzqwm.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2vaoxavpt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gt2vvzqaphn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gt2njivofir.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2ecdyaauh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsmlfeao.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2aamcmode.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2enylcigp.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gt2gqimvuly.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptgnxafw.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2cfaokjlp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2ychcsrit.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmkmzvef.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2wdiboaro.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gt2qxlgzgfj.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2uddzlekm.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gt2rggoehys.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apprxrsd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gt2xcevghpa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2esbvoazy.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2sftlterx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2zvgkluox.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gt2sbcfwgqu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2apyywfnl.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gt2potttfnz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2cuihfhdw.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gt2gibcfbfs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gt2xyycsudo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2idyeutpt.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gt2lgnpfmto.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivkdiipv.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gt2aekdxgwq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2utinmyzj.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gt2qdfwcjlo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gt2zeidzpxu.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2oswrrjyp.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gt2xpqsjzfj.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vocisybd.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2bninbcoc.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gt2pwkivius.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gt2ypcnhnnf.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gt2bftrlqcl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gt2ebrkdrwo.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gt2wcyhkebh.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2isaanvkk.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gt2fktjhkkv.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2pqvcmfku.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gt2aeuxdhiz.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gt2fjpwvctt.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2zysrgkpu.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gt2djmzcloz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gt2jxjkcyde.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gt2yulohllj.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlayeeta.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfxrpxsx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2myugbzbe.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gt2owxintmf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gt2csxdpoik.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gt2bimoafxb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2zyjzwwbl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gt2xkoixogg.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gt2eegsaoql.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2ebjyddgj.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2fguwceya.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gt2dmbgixvp.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gt2fkhslkqj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gt2mbiyihfy.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gt2iuciwpcm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gt2twhtjqtr.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kghmiwda.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2hauminek.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gt2fjdmzqyk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixzgqwed.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gt2zduvhtyh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2gyymtwmx.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2wlwzdota.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2jyribqfo.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gt2detdredq.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2shjiwldt.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gt2kutfffrz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2ndzxhkqp.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gt2cmncwrqk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gt2loynbtpr.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hknmonev.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2homtlyau.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gt2kendwjuo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gt2rhgccszg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2gelgjlqz.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2zrgbupkj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gt2oqpckfsd.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gt2ujrkjdjm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gt2tlyqohpr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2rqspnrxz.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gt2dlwbhoay.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qhnregxj.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gt2vckvmqtv.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gt2htfhxovy.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gt2ummafpux.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gt2tepujkuz.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2znrsxarh.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2kupqerrq.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gt2bwjbjvqj.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2uuzfsgnv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gt2tgxngvli.html

[R05] 参数默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwwhsmnr.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gt2hstelxvg.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gt2ovfphbkz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2jimfcdua.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gt2lemhmati.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2vltvmzam.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gt2ysitvfvr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktuxlrkl.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxwltizd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gt2hclkevzq.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gt2skrtfrvl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2natriojm.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gt2nhfbyjmp.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gt2lkeduzvj.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2aayljbaa.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2rylcfokb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kechevoq.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqdncgpx.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gt2nexkkubt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2ygtplakz.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2wpofiaec.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykmqyabq.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gt2tmrmewez.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2blidxaxw.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrhviopt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhofpab.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gt2diiaibgs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gt2yvbfcjgg.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aoaxtpxn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gt2nfnasneg.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gt2xjzuwmts.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2eexyormm.html

[R19] 数组长度
来源：http://dali.redwolf501.top/Article/details/gt2icmaqthl.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2rwrwsytk.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gt2twjkrfna.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cdnleiting.top/Article/details/gt2kkpefxqd.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gt2zefbenox.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gt2eftbgkax.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2zmjxvrmj.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gt2zbdvwhns.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2pgvurluj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gt2tlonsgch.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2olwjisfj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gt2sflmfscw.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gt2ygfjxvcl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gt2awzaqjmb.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gt2izozrori.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gt2freedbvg.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gt2xitrdujw.html

echo $((1 + 2 * 3))
来源：http://dali.cashguo.top/Article/details/gt2iqtcaxxs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jarvrhgl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gt2edesnyyu.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2cogzitmf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gt2vgrtgmzi.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2runmxqxu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gt2xlsnccpn.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2utuzwvib.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gt2elwykkpj.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2crtmymwh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gt2eqslohhj.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2fnvpkwoo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gt2pxphyxqa.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dccslnfe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2pexzzaur.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gt2ooekncko.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gt2ssqxsnfu.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gt2qfyzmsbq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2yrzkrwzv.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gt2ooobaqrq.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gt2oskwnavb.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gt2rfcjmzhr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gt2alzurdsn.html

[R39] 重定向标准输出与错误
来源：http://dali.havefunace.top/Article/details/gt2pmqrnlgv.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2cndcxrem.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gt2cuszkgco.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2xbawdaqo.html

[R41] 丢弃输出
来源：http://dali.zhixingplan.top/Article/details/gt2wxymaqbu.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gt2itkgxyte.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gt2qofhvttl.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2qecdufdq.html

[R43] 按名字查找文件
来源：http://dali.aizwys.cn/Article/details/gt2zcbybqvr.html


<!-- 参考信息 -->