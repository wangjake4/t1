代发 wailian999

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttweuddyo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtsztakzmq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gteppggmqu.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gtnfpwrehd.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gtisnvhxwn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtlgoebybf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtabsmdpxk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gtpqcusqex.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtropzteha.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtcqmdcwnw.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtsikyybqz.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaijtnzna.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtgijafpii.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtnxqeyiof.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtkdaqnjns.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gttzlyybbc.html

);
来源：http://dali.jianghu66.top/Article/details/gtmncjgmwf.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtlvcnddgl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtopaalssa.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtzsfescym.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gtszfhsneu.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtfgasnfmi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtlovevqem.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gtahcaymjg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtfksiogph.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtqutirvol.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gteghcxmds.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gthqabnnbd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtripystyp.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtwwopgvvs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtlugzghqp.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtjtewcbbu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtmmwkhccf.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtvzjgjlbi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtrrhpimxk.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gtsqpfhrou.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtrdpdvyha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gttejgiqmn.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gtkpbkvrko.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtlgessrfs.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gtmnpxhlxc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gtshjgfhna.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gttwocbmzw.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtvtgrstjz.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtsyeomefz.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtetlepsxk.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtcxpygnep.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtrrgousks.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gtohfeshxu.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtukuuabek.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtihvbxgux.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtwyuucoka.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtyyfyutul.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gtyynhhlnr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtpdafspah.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gtzpxnormt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtogqhrgrm.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtvbywaird.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gtxthbviow.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gtsifvrcyf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtbiswnudb.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtfetzatps.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gtmkctofsn.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtkwqxscvg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gtknvwbtpa.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtyeflhwug.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtqiwbxdov.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtwimfirai.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtizrxjoql.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtjlthwjmv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtbpjjtjez.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtyzaksjfl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtjraaxnkz.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gtfphtrjno.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtfxorkngj.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtecalveol.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtqkhsmtcd.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtwjihdaco.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtaevlnazd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtljfazenl.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtlvoeilpe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gtrwddhvja.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyyzkurm.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtbljqfhan.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gtwylynblq.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtpskcbfhf.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtiswfonou.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtyboiivnt.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gtgwhqpysy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtmkecgzhc.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gthaegifxw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtnrijefbg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtomwqlirn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtuuabkmuh.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gtxxrzghyk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gthjehbrfp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtstneoknm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gtuqnbhkbn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gtfkpnzsze.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtlcorygez.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtbvnxnadi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtgrjvymwf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtfyqvvalj.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtxeurwxzi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtapxdmfpl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtrcnlizuy.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtdqiilsik.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gtpzjmbppl.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gttghoerfz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gthssjvldc.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtkzgozshm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtmtvcdkwn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtfxvnkwxn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtemyyurui.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtxpjomcrv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gtixyputqp.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtlegngbbu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtguuqjhxv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtgqjqdefa.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtwpfhljme.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gthqozrnjr.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvprrjvtw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtrffhpmjz.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtrzmhmvwo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtrjcqlarj.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtgftvcgsj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtkyaoguvr.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gtrhrmnxtp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtywmvbooe.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtuvsspryq.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtxvqddrec.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gtlvrcebiv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtjnrjdncw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gthddljfpx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbaeofko.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gtfgasufoc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtdajjflhz.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gtlksugvwr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtogteceqt.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtugwakstq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtizyscsku.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gtdgkagkmi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtbayaornc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtnhlzofmg.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gtirvvtybg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtrtccicfl.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtchjyffnx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtjpgzvdek.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtyukppbry.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtwnzsbctp.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtptayzciu.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtzqguxcyl.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtrtpzinkf.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuxgusjb.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtbljhrxwm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtipzwxuvh.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtqugcpbeb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtttoudgri.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtuvxlqshx.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtreriotgu.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtfhadxmke.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gtgrsbobeb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtaqeifkmb.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gtvpudfhla.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtsratdsts.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gteiqseqay.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtndxcvsca.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtyxuybvtj.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtoqvkuvkf.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtnrspczpi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtbpjtleik.html

[Q74] 强制使用索引
来源：http://dali.tian-w.cn/Article/details/gtfqnrrwab.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gtruaehvxj.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtezdykatr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtcprekjaf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gtlwaupvfu.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtgadfamnb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gtymukfmfj.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtpjctbflg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhengqikj.top/Article/details/gtfqehcbut.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtjbumrclh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gttxnriqeg.html

[Q79] 字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtswnhytuh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtxzurnzaq.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtkssonsfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtnjjghcxw.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtjhodrxta.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gterbcrhzg.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtwtfirdqd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtjwkkkxos.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtixnxqktt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtuipkztjk.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtpylybytl.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gthquyegfk.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtbqrndexa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtjuihivrx.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtcdmrwypt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenjidiqi.icu/Article/details/gtslsozgvw.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtireugyxh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpsuyihm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gteumpwlvp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtkfplwwdj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gtoklunmnc.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gtwmdnhgsh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtrdamccil.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsqtclpj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtjyoseaxv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthreaipba.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtathgdldl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxbuwbvqh.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtqokialms.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gtykoolrso.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gttvcthavn.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtsuyomaiy.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtovvvyhhb.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gtkomdusdd.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtqmstxjmv.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtjmvvgdqr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gtagzbyszk.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtjrljcgfw.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtpctddkil.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtaudyeujd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtarxrvecp.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwdpasdwm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gteucwrbal.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtrxniortq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtxlxupwbk.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtdzdyrord.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtpggbznnj.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gtzvocjkhc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gtoshebqie.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gtjuvtjqom.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gtngnafqmg.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtwxokgtaa.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtdzuvnaqg.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtklsksfog.html

esac
来源：http://dali.shuidangran.top/Article/details/gtmjkcfhki.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtvncpkukv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtjnbrbuxb.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtbrkjblzb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtsrxdtptv.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtkfsiglbo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtvdatewut.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtrpahykaa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gttirrbnjx.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbewznkf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gthfsxywup.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtfgvjtubv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtzxxmjjpc.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtejkajwka.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtjgsxagrx.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtaimwbcqi.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtkpitzilh.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtkjwkakcr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtejjenlwe.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gtaefsnpmc.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtbebpuwdp.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gthjixokhh.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtkmvqiycr.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gticorxoqd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtajdbzpkh.html

[R24] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtfpivevje.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtynuabsep.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtafjaxenw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtxdrfuvlg.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gthnhctdqy.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gtanqlsuzf.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gtdjmnrtyg.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtqweootvk.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtirersmjw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtvrdgwlhb.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtqtnlwrrn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xinyue.icu/Article/details/gtqocgaode.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxhjxisy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtkzqjhigq.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtnujmukmd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtyaqqnfoj.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtfgkurevg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtwecdycjc.html

[R33] 捕获错误并提示行号
来源：http://dali.hnqzz.top/Article/details/gtfpyvrqqf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtltrtirgd.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gttymfwldl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtigndlrud.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtcolgpziu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gteaiqptrl.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtpsefojio.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuanzhike.top/Article/details/gtmqzyjybn.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gtqsignoqi.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gtvoqzmifa.html

[R38] 管道串联
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoynppxfg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtozfdlgfy.html

[R39] 重定向标准输出与错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzguknhl.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtmecslfmf.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gtvluwznbd.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkuvbedr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtqqabsuxq.html

cmd >/dev/null 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtptzqrnzu.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtjgqbbljs.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gtmtvtnggm.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtzzazoasz.html


<!-- 参考信息 -->