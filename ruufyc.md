代发 wailian999

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gt2tbqmfwzi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2lfkeshno.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2xdrooqpj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gt2itavbeiw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2rvggezfo.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2fajfgowy.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gt2aykgvjxd.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gt2muygivjx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2quirxdud.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2pqinjeuk.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgftifrx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gt2senkqzsp.html

);
来源：http://dali.daxiang520.top/Article/details/gt2pagihrid.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2wcbuklxm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gt2cmqhemrk.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2iferamiq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gt2cfrqhbwm.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gt2wiqotpjr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gt2meoqfkgj.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gt2fqzxltjy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gt2pxcwjtpc.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gt2cydidort.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmogbwwf.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gt2ikjyixud.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2csdhewkb.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2hgcvlmmq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2ykwazlux.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gt2tyromxxu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqtuhvcg.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2uhrrcvsp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2mpcfwysk.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gt2kezepwzi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gt2earryqun.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2njpxyukr.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gt2pdbqeglp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2zdrxjzxl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gt2udooqkjp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gt2dvbpkmzv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gt2fiudsnkh.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gt2kzxheyri.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2aykljuio.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvmruxaf.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2ohnisqvn.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gt2jscwjaht.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gt2rmyigzda.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmxcdxfa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gt2urxelrat.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gt2ruegrurj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gt2huykvtcd.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gt2gcofhhtl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2phltwosp.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gt2buouwucg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2zlswzvxs.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gt2pwlrydtr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gt2yucpwycq.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gt2jiaquhlj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gt2gbextnwd.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2dqbinoij.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gt2wguubxyy.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gt2fyodhmub.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gt2hiwlcwfe.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gt2aooharpw.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2znxnxvgl.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gt2jcczcoib.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2dxwiktsc.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdlmkzdx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2tvlesczl.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gt2rhmessci.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2viffkpes.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gt2eqwoukdf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2mckftzrx.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gt2jstbzxaj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2zmxuxlmj.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2jzpitjgh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2sntjzuig.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gt2cmiultxe.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gt2yegsjvlc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2gcmgdjkd.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gt2orxlwgbo.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gt2tqjziajb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gt2ycefazoc.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2cevwfbbx.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gt2dmmrnlvg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2klderpsy.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gt2umgrnror.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2xnmsasiz.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gt2hjalblyh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctyhwlau.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gt2wmzdfrnx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gt2hjqcfkun.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gt2ltlpmdqa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gt2xqjgfxwh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2urxeytfb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snolnpke.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2ftkfnipx.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gt2rrukkpff.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2cojqxalb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovftoenb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gt2fzinfymn.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gt2geiroluz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gt2itkjmddq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gt2beoewjdx.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gt2ddyhdwbs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gt2eopalcdh.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gt2hiqohubg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gt2bczajtkb.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gt2hjlcukru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2bqhvtdgs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gt2tuoubtja.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2lxrhotdd.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2gifmjptl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gt2krctpspl.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gt2frkfkxlo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcqgpwmq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2qqchausq.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gt2jhozkuen.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2anvejybb.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gt2vhtvwtrd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2cdjoriss.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gt2dvhykikn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gt2furysyee.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcsglheq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2vuzzujwn.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gt2llmooati.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2mglebgrc.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gt2rknlugbj.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2jdnegpgu.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gt2ixgpuuje.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2fbycrfdz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2olqmhqff.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gt2swjwutac.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2vsgckghh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2xubhajnn.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvvhkvod.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2jovxsyoa.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcfofdzo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2ajrlbkxw.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gt2ozmbodnn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eisjmeuh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2ijfcwadd.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gt2pgfzecam.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2zwtxhuch.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gt2tiyrloft.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2uhshpqff.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2lvlaacqk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gt2hjlvqddb.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gt2jsjltlpa.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gt2zinelhks.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gt2twmawmwi.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gt2hggflnyr.html

[Q66] 行锁查询
来源：http://dali.sxryk.cn/Article/details/gt2ucymkfuf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gt2wvqugimz.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gt2eyrlehnw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gt2mwldypzy.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gt2gvpsvbaf.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gt2hxchezkg.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gt2mzpuavjk.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2zjafdpzr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gt2nqkyuqni.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gt2ldwsyjnm.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzrswloq.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gt2nwfnbsal.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gt2ilrstnvh.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gt2ekdxmynt.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jhbgvnxi.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gt2xsihqekv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gt2utebpfen.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2sdeukhcg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gt2dzosvmsh.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rinyssut.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2damvefrr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gt2pfpxsobn.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gt2tgtjmqrz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyngnebp.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gt2ymiarhin.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gt2fwupduzy.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjaynbsd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gt2txqsvnob.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2jdqkjdmh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukijyrsy.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gt2hlkmsuvj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2iuljeeoh.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2vxodbqzn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2dmbcujdb.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gt2stxihzgm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2kfebvuls.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2gsdxyhig.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2vcmfputg.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpxmcnzg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjecakqj.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gt2kvjndztf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gt2pgnkvrsy.html

[Q86] 读取 JSON 字段
来源：http://dali.zycfv.cn/Article/details/gt2iktifljr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gt2zmyrfbcq.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gt2mttuwejq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gt2mvdbekvw.html

[Q88] 行转列（条件聚合）
来源：http://dali.hammf.cn/Article/details/gt2zfjnuhxf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gt2ktwgvjqe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpdvciul.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gt2pvtpeiwn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2egdevaor.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrhccloa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2jzbeerdd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2thicgrlf.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2gahjjabe.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lhdqpbuu.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gt2akqqgdga.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gt2icafaheh.html

set -euo pipefail
来源：http://dali.bjfxy.top/Article/details/gt2ljpovkfu.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gt2sszfsurz.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2dwbmthsu.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2omhsafcm.html

readonly PI=3.14
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibchalea.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjvtlkf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjrrloeq.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hetbydcg.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gt2srhpftih.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2zclvmqqz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2yqaeudlu.html

[R07] if 判断文件
来源：http://dali.hnxiangtu.top/Article/details/gt2wwubwkuh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gt2nydsywpa.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gt2knwvnunc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gt2lnnzqlyc.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2mqebdmwu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gt2mpahxare.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2amqkzlxp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2xznqvuup.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gt2anrdpgta.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2sabppnch.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gt2dfncsiid.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gt2mvnsttrx.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gt2ptqyegvd.html

esac
来源：http://dali.havefunace.top/Article/details/gt2jqxdtcga.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2jiyxvnoe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gt2anhapljj.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gt2zdmfbafa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2micokxol.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gt2fmbpszkd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gt2ayoqdcan.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2ujuhjzan.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gt2ytzfhsbt.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gt2sdglapcz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwjaqcnn.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2npiuywtf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gt2eamkrvzb.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gt2kecuxdqf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gt2sxnqcapo.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2xccwwtxy.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gt2jkegirhv.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gt2aeosagtl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gt2rjiaqfqd.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2kwdaykpz.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gt2smuiokgv.html

[R22] 截取子串
来源：http://dali.tanke756.top/Article/details/gt2iuaahcfc.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gt2fngzxtji.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gt2eqxqrvrz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2kenrpify.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlhlkqpf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rciyrbzv.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gt2uulvsgxl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttymarwt.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gt2rwsxolcx.html

now=$(date +%F); echo "$now"
来源：http://dali.hnqzz.top/Article/details/gt2gbonuduc.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gt2ilklkqlz.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2agtxjqvs.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inwodugf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gt2nlciuypf.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2oatotlho.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2rogqrkcu.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2xwkgbcvq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gt2yejiziox.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2syijbsvl.html

f() { local x=1; echo "$x"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2umqhekns.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2fjnwrjao.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gt2rkfourbt.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2dlfxoygs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gt2umgtvhiu.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfmtjcrd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gt2ychjfjlp.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2kzmatcqn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctwcnaic.html

[R36] 并发执行多个任务
来源：http://dali.ydzc1.top/Article/details/gt2nktcqsij.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gt2cdbxafaq.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxyajofe.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gt2ytjanequ.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2telsfwrb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gt2nvxzffho.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gt2azhnvixl.html

cmd > out.log 2>&1
来源：http://dali.jianghu66.top/Article/details/gt2mdufrlvs.html

[R40] 追加写日志
来源：http://dali.hnxiangtu.top/Article/details/gt2arhgymsq.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gt2ozwgraxf.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kloutuam.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gt2wmulatao.html

[R42] 输入重定向
来源：http://dali.jianghu66.top/Article/details/gt2ktjmsqmn.html

wc -l < a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2ybqsxqwi.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gt2kjeqhnnx.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gt2lqiaybbr.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gt2vrldtuyk.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gt2ysgusdbb.html

[R45] 批量删除
来源：http://dali.yj202588.top/Article/details/gt2iwkkepka.html


<!-- 参考信息 -->