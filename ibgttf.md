代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gt2olkjzsvr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gt2eqpqbign.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gt2gplojwnu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gt2ruswctnk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2pwuqpydm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2pmcwursg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2uqgedpvg.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2kxjvftzk.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gt2bjcnfvrq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gt2dtfikofu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2dferpewe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gt2eslmngya.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gt2rwggbgma.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2uebvgyfh.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2qgdorkbs.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2raqbefik.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2neuplyag.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2akkvvpoi.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gt2hkuiycjj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gt2habqlgpl.html

);
来源：http://dali.sxryk.cn/Article/details/gt2gngkqzpf.html

[Q03] 增加列
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldqgqfmj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gt2tlrszoym.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzshjzgt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gt2swdrmqmu.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gt2uijzueap.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gt2msntwajb.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gt2degtwibk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gt2ckkovhak.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gt2rtstylrf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gt2xanvetcn.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gt2zrqfrkha.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2hgbllzvq.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gt2pesvrsrl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2augcpfba.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gt2pqmhabiw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2giqunbqz.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gt2ljgoivji.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gt2pyvjyrfp.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2lroubkar.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpnuqxeq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gt2wceaafhn.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gt2kzdgrcoj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzjhsztg.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gt2nqvvddwn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gt2sykdxitj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gt2exephivh.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gt2frjjujov.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2pxxekrkx.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gt2lreyjkum.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2knbhxjle.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2vmfcwxgq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gt2cciwreai.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzmwhqid.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gt2ghflvwxb.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2whrdkjml.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gt2tciiqybl.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gt2bzrirrdy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2favjhtzi.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtqzdlty.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gt2dapzbsyz.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gt2wegvmtno.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gt2lhqbntwa.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gt2wmzrjcey.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gt2tpbcawfu.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2pbhicfny.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2akiltfmj.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gt2wlgfhkoc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gt2cteksqlc.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gt2gtzunksg.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2glrqhqfg.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gt2jtfzpzpe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gt2nzweidle.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gt2tyjirspw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2eshiqjab.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2ztlwyreb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2fjliyxzw.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gt2rrrlzmwz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcsebmlt.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gt2nbtmwpvc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gt2bbncktuk.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2xzhiulzi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2gulexgpi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gt2gytcwiou.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gt2tuteohgv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2rdpaxjgy.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2ixxjaxxu.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gt2kuojizmx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxdvzbot.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2podfscjd.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2cliibrxk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2enpxxseg.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2novbhegy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gt2vlkoxzeu.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzuichbl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gt2alqlumbl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2xanxolpj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gngoezge.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2tktiezth.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dugswovy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljfpnbfu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gt2gjoiwzio.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gt2eozipcci.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2csplwgls.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2autbjtyq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdpwzfyd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gt2iwrpfest.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gt2qdwydqkt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtjktpuj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2agkfkjqz.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gt2cuspjrtd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2skcjdqof.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gt2yrerigsa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2awhvqxng.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gt2klofnjnj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2mygybiae.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxuanxn.top/Article/details/gt2rsnzgxzr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gt2pmuulaft.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gt2ehfkcfno.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gt2pfflhckd.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gt2zcwrbzcd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gt2pnpuqstp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhaqaafu.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gt2qjjkboxk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxnpptqf.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gt2arpdogog.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2ebhfpljj.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gt2guejgsty.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2koghvtgx.html

[Q52] 删除指定行
来源：http://dali.nanxuanxn.top/Article/details/gt2kijqxwrx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2eotvzdhv.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gt2rucnkbke.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2vdzucwee.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gt2qvsxrvgn.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gt2midspzje.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gt2qskceluu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.redwolf501.top/Article/details/gt2ekpgngue.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2swvoozow.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2htmajphw.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gt2fzdgsrgt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gt2jnwuwnme.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcxsfjsv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2slaorooy.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gt2nlmfidhd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2pcwykyzo.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2wqrrtpzn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gt2bdhyqojr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2xforhgdb.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gt2smcsnivd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2ecezrrzu.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2erhxwmnq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2lpfkmxor.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gt2mujolikq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2dgqlyowr.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ualkbzke.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gt2aedmiaft.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2rcheycjo.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gt2oehikikb.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gt2nyikjnyu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gt2zyfajfah.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2ciqvdagc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gt2epiovcpw.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gt2mczeljsv.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gt2dyvpozlt.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gt2zvdxkffr.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gt2qjkydjpb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gt2mkkwwwln.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gt2xhzbyfju.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qefshijh.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gt2kvqewqia.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2gaujwasm.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gt2vmjptrxb.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gt2pamyiugi.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2vneeqveu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkmawrtm.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsbilvat.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gt2zjwqibwj.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2jutvaulm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2odhovckx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xitkbhgi.html

[Q76] 按天统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlcmzyjb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gt2kygiqtlf.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xejgjdja.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gt2dbdnzhns.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gt2dykwqgbb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xylfe.cn/Article/details/gt2nclsjsvr.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2hjlcbifb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfvcnchf.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gt2fdruredv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2scfydwvv.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2lqqsmapv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2fvgwgacs.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gt2fhvnhyhv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2iklaqpyk.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2gsvvfinl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2cpeohjyh.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgttosqw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdptzjft.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjgrgulp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okfkhfaw.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gt2hqenbics.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnxiangtu.top/Article/details/gt2vabvzzxz.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2xovialmp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gt2mlehywcj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gt2dnwenjqv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gt2tdoqgzdf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjepovai.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2posnrukl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gt2illtuyrp.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gt2rhelasvw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajisvnuj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ebjgtisi.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gt2ewlxvejz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ruddrlct.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkymgpvu.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gt2syzcjtzj.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gt2gcusrowl.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2xtyuxsgr.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecpdvkco.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjlchxj.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2vegrbabh.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gt2emwnxclb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2gxkzniqa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfarkjav.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2hfuiwjbw.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gt2afqwasdb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpcfbckz.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2uplvwbnj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2nweghhpw.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2uloijamu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2wmaexpdg.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2kjmeskux.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqwkmahz.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsutvook.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gt2ctxczohn.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gt2rkmstxfw.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gt2mgsdtgdg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkvekeq.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2ijyhwhzb.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gt2msuftbyn.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gt2cnihjaee.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gt2guaxqgdc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvxgakmh.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gt2ozzhudhu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gt2aweiglfo.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gt2vsvyczwj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gt2zzqqgzwi.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhyepjxq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2pgorzegc.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gt2klzotcoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwptkehh.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2vlujqrfa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gt2gndfpffy.html

[R18] 遍历数组
来源：http://dali.cdnleiting.top/Article/details/gt2dukfiyrk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyrsuyab.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjudrdnj.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gt2nazckokb.html

[R20] 关联数组（字典）
来源：http://dali.aibaodan.cn/Article/details/gt2tfgumnfn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2azwcppok.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbymmhmf.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gt2fgswdgvd.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2ifkkjefi.html

echo "${s:0:5}"
来源：http://dali.9152youxi.cn/Article/details/gt2fczrhvmz.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2vbdswpvd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gt2rjwkzmpo.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2rilevfek.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gt2iggubfmx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gt2qmdnacyh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gt2lemfytat.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gt2pqwittnu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhixingplan.top/Article/details/gt2ttbjyxdk.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gt2yegvulml.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gt2jcwzwygn.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gt2msqoibco.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2vfrghyxw.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gt2aiyedsdp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gt2dxkbsblv.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gt2hqpqgwnq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gt2jnesduai.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gt2ykxwxqst.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrlmdwwo.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gt2gdnnfhfa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2jelnmeku.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gt2uncigzce.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahaoazvn.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gt2yjiggfsu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gt2zaburmqh.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekowktyo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gt2dkriejow.html

[R36] 并发执行多个任务
来源：http://dali.tianlin.xyz/Article/details/gt2ikbpcdsc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gt2zzreequc.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gt2patdywgd.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gt2oapgjrhu.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2iagjaxtl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj202588.top/Article/details/gt2jsgfeurx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gt2zqrrxpww.html

cmd > out.log 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2dbsmaeei.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2bugitijo.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gt2gmzgydzz.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2mbarwkaa.html


<!-- 参考信息 -->