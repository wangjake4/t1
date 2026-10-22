代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gt2djbdjqym.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gt2qajnraml.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gt2ukeymvxt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2yotzrhrv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2qsdvwxvk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2eesuvslr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2exetfrrv.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltuxsiiy.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gt2fetorjgx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gt2gdborftd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gt2hnrlbebp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gt2iozwjrci.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gt2jdtikygp.html

);
来源：http://dali.yj202588.top/Article/details/gt2ctayqzui.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gt2hxukwtnq.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2zncvkitf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gt2uajfudjg.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2kpxivxeh.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gt2qjkqxelb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gt2mpkbtbzl.html

);
来源：http://dali.zdqjudy.top/Article/details/gt2uacfnsmm.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gt2ovhgzxmz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2ksezempf.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gt2bbjqwoij.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2osylbjjo.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gt2eoumtmdm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gt2gotmpvyw.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gt2dmdutibk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gt2wcvmnlet.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gt2yrcrzjxl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2tybxdgay.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gt2rkflhsnn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gucrrhci.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgdbwuky.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gt2pjtjracg.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gt2fdnjfjlh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2qntnfdwr.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gt2wbjafgdx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2lkdainfw.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gt2aiifyalg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwpuztzh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gt2jgnsegej.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gt2dkbpdhpa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2giwbuxaz.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gt2irgppoch.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gt2eyptnbpf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gt2oddfiqda.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gt2drwsrqhi.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2kgzimxor.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gt2jqpioadb.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2vqenbgrq.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujujgdpm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2rcpmitwv.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gt2wqxiabqb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gt2bivomrdg.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlvjqmta.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gt2nyvovaxo.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gt2qdgjkihf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gt2ukkfrskr.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gt2sywfisfp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2pgbpozks.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gt2hoacwuok.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2rhgqjmgd.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gt2vurufilg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gt2xgovrhld.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2kahwljrv.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkaqguou.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gt2liqnpjpt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gt2mwrynbop.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gt2jtmzjnvu.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2wkbnnzjg.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpcraqtj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2mddqjwwq.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buwehsso.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2brncjxql.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2hisyoofq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2yaqzncsq.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gt2jluffgnv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2fsohglnj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2egqlbtbe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2odivgkzo.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2cxbbdkxf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2xzumbjqk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gt2pipdzded.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gt2wfqhdmnl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gt2wcjarsgm.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcycgsgv.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gt2joenoeuk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gt2pfstkice.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2nnhokllg.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2fixlmbig.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gt2iwduvaie.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gt2jcqvgshy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2jfvsyqqo.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gt2hzwrqwrk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2xewozdfq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gt2ljdydxbr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gt2wwaevvqn.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gt2vkulsnmk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gt2qwljazsj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gt2tsqwzynx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gt2wisrrukt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2iopfffnl.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2iuyqsxxt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gt2ofztprnu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gt2azbyqxey.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gt2hnmujvgs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihwkanwc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mojzjlxc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gt2tfvdhaiw.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gt2ngkcmigg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2usybkxkm.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2rgzerfuj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gt2slkjjxhe.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2htlnewxm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2hchutnun.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gt2tuuiqoxg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2rlmmmyvz.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pugghuvg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edmwqsnj.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gt2thnvqaak.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2ekutjysw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gt2bfvmiyop.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2twyaojmw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2jmfauqqr.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gt2vzbuniek.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gt2capokocb.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gt2tyrbvfdj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2zlyexvzz.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gt2enjyykwg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2vjrxcwht.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gt2uednrvln.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2yznyeyus.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijbwaajy.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gt2itsnnxri.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gt2gybhsovh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmzjxqql.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gt2fiabzlzf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2imxeheiq.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2vsukekgn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2hvjeotma.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gt2hznrkcse.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2uakcgecw.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybjlqgnr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvcsmfoc.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gt2pdgcelvz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvqppwlv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2tcczyifi.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gt2izvyafvj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2auufhcne.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gt2tslylqzh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2xvdctbka.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gt2vbqmbwre.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gt2wpjcbfov.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gt2vgilskfj.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gt2mgvkuzrx.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2dklzlgrs.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2eblmfqpv.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2japkbtne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gt2aqziyidf.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2eywshfnq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gt2sezaltes.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gt2ajnptsmx.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gt2onaaqeog.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2vylkuago.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpmrabrr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2heufwgae.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gt2oeviwmab.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2vfxlfuja.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2jljcpsfx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cudptuaf.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gt2jswqgvcr.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2rdcalvkf.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2lajmhsrm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2momcgsdf.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2eymagcii.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gt2glvequap.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjhtezut.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2ffjcvmld.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2uypolrry.html

[Q76] 按天统计
来源：http://dali.andypj.xyz/Article/details/gt2wyadtcbj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gt2pckcyeqh.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2blxojdwm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2rpaifsgr.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2zhuvtizf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gt2plnjsjmq.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gt2rzraisnt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gt2asypqykl.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2nbpopnxj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ztypwzwa.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2rglikvbw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2nzxtvcix.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gt2hdxaopaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2npifrkrc.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2kqkwyyvd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2hqflvvng.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gt2fjqcztqp.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2qlgpcdtz.html

[Q85] 数值取整
来源：http://dali.yonumen.top/Article/details/gt2hemzuuxy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gt2ayvvnnoc.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gt2nliderym.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gt2unnrgtkh.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gt2kahbmtso.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gt2moyaqqig.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2cblsxtcx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gt2xjpdeiol.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2vwhixsbi.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gt2pxwurqtv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2qdmgwxbk.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gt2wlqxaccw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gt2ffdvmaeg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2kgtievmj.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxperegj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rzyonowt.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2dlhkjrxc.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gt2azleonew.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtoibzqt.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2yeoqhnoe.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2uiowifrz.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2gtdeztgl.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gt2avcydezz.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gt2jywyxame.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2yunqjyhb.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gt2uwetxhqe.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ynbtubnf.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2wsaefphj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gt2lawzqwmo.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kyabhaem.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2vrkncntt.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gt2imobtfky.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2blzrqatm.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gt2qehtvbna.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hammf.cn/Article/details/gt2izjauhjb.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2vdtxrozu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gt2qrbonsdu.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2mdxccwlo.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gt2nhizywmk.html

start) echo "启动" ;;
来源：http://dali.sysykeji.top/Article/details/gt2wculyfaa.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2ftszxztg.html

*)     echo "未知命令" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anerumas.html

esac
来源：http://dali.316326.xyz/Article/details/gt2mogboueq.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knwnepnn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fengsongda.top/Article/details/gt2zmbhjcrd.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gt2fvuoeqvb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbjpveaa.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gt2szfnjifr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2tylrbqra.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijrhhwjv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnmfehwd.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gt2suzjwsgw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2cldxstll.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2owqnkwmu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gt2sonmpndz.html

[R18] 遍历数组
来源：http://dali.sysykeji.top/Article/details/gt2hqytouoq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ityavmlu.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2ttqrbbxk.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gt2jnaqkrfc.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gt2ftrlxilo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2iniimhgn.html

[R21] 字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2mhipqnia.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2xsyzobna.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2tsgzsqng.html

echo "${s:0:5}"
来源：http://dali.daxiang520.top/Article/details/gt2lnlqmkva.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpbqizh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gt2zsrwkbdq.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2zeraunhi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gt2allskdkb.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2zuppqfyv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gt2ghtslrpe.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knljrisa.html

now=$(date +%F); echo "$now"
来源：http://dali.hfpthk.cn/Article/details/gt2eqtpbcnt.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2qvmtwsaa.html

echo $((1 + 2 * 3))
来源：http://dali.guannengcc.top/Article/details/gt2yfulwwap.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gt2mugwzdib.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gt2fgvbgjug.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gt2hblkxatz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gt2zrmqcmff.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gt2irtifevy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gt2zriauikl.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2aduzoutx.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlkzkvvr.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gt2egshfymx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2wwankabb.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gt2xcarvhru.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2hegpnjhc.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2otdrjagk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2verxvkaz.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gt2acsbaqre.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gt2kfqokcff.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gt2lntuxvaq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gt2lhjhvsrk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vschorqp.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2voutenwn.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gt2zthqknfd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gt2agqnsmzd.html

[R39] 重定向标准输出与错误
来源：http://dali.guannengcc.top/Article/details/gt2hhagyvmm.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2fpcynvpf.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2rftmketa.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gt2ombjjiuq.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrtagwkj.html


<!-- 参考信息 -->