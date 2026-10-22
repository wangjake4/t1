代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gt2coiaquod.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gt2whqbcmye.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2xeiqoczf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gt2qchbwwlw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2abgmfhfd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqpsizur.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gt2avoxuyvx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gt2iccejcpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cowrcork.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gt2onpeymbp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2bvsbpvqq.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gt2sjeradzy.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gt2avstzkxj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2srefzqap.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2uztiqzkw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gt2bimlfjsz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gt2mpzfawyx.html

);
来源：http://dali.cheryme.top/Article/details/gt2qyrfzehr.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gt2jpmrrfbe.html

CREATE TABLE orders (
来源：http://dali.0kj1m.cn/Article/details/gt2kufzgxpr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2twtxkoef.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2lhzmvbnq.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gt2yzehnejb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gt2xxtpvyxj.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2fopqkldl.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gt2mzjvwonh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2rlcbfbbj.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gt2kqrkwjyu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gt2btlvotno.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gt2smkavzec.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gt2aokdpxpp.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2tabyiict.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gt2kersltdc.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gt2sjvutabw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gt2wjbastjf.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gt2ywmmckde.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zztowykm.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gt2adkobzxo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2psoanrti.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gt2cykwyarx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gt2qfiwhjfy.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2ajfguyns.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2tazzyfiw.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gt2rcijiawd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gt2qoeoaedu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqdwbwwx.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2ylikbzqb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2ztrbqrov.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gt2gxybpiol.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gt2qnhvhkld.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gt2mfniuujc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sysurzik.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2jtxwqzuu.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gt2cjwvrmok.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2nvsdfgqf.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gt2wzwmobay.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gt2bsizphmt.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2lhidzxzh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmrlvtr.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkdcxdih.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2hrjrrvnt.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gt2dsnvtlzs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fczmqzzg.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovalqkpz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2cjtgwdvb.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2lnoeequl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xibczdpg.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gt2eiszsywd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2obvwruem.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gt2ffuyszzr.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2ztkhebeb.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2yexalwko.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gt2mwdnqtti.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aphtwane.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2zbyupkjg.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuxrbcwq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2exhscfaa.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gt2pbahwboa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2wkbpeamn.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gt2shtimehk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2olvbpzxt.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2zmukssen.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2rqzcfjgd.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2mfcrclko.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2rozcwbww.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2lqwhxdmj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2konalqoy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gt2nunohtot.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2lieyipth.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gt2ybxzkwdn.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gt2cnrxlpsc.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gt2ulkwlprt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gt2pcekuoty.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2dkkoefqi.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gt2wastqigr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2qsozbqyh.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gt2xauouzvw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2akqzjtbe.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gt2qnwegxfd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2anhmoafa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gt2zuixgqxj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gt2ujzanhup.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwcufpzq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txlcfeaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gt2liugbcno.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amvwxzba.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gt2duzmbxao.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gt2zgkvejng.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2ggldunjc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gt2jzbqqvhu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gt2kytzkmat.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2xkmmxuza.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gt2nstglmug.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2tcizacln.html

[Q43] 标量子查询
来源：http://dali.pycfn.com/Article/details/gt2nyddfxim.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gt2tjrtwwmu.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gt2nisrkoyt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gt2nthyddfk.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gt2geeznhfp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gt2wqkfvrgx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gt2owkjijjw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2fshtugex.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gt2ojtcobdq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gt2ucvgnytd.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gt2jqwiiplu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gt2xjrkqnyy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gt2idadmiox.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2efmyvrjr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2heptyuhu.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gt2ebueilbg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2jbykwcdp.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gt2lwmuqrvw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgcnezfc.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gt2buisnzmb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzawobxv.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzbeziri.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2tviaqebw.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gt2wvmoybgn.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2pylhaeen.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gt2pngchtyw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gt2otsxcjor.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gt2chxsqrvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2vgrjgvor.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxdvumxl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgatbkjn.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gt2wpvlvovw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2fpshqwhm.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gt2mloisrcz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2vyjkpyqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hauimugf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gt2nwletozb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zkaqxjib.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gt2zppwgvyb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2kppfygrr.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gt2qvefyjiv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2rkbbmpeg.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gt2rmyorord.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gt2pkzjkbja.html

[Q64] 提交事务
来源：http://dali.kuanghao11.cn/Article/details/gt2ntagbnri.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruzpznjk.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gt2apnwwmmb.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gt2aiawqvgw.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2djwxtobu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gt2tglkuexd.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gt2eqzdnmgq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gt2buvivrqy.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gt2nnxbddan.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gt2vjmcwzns.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2eztvgwsz.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqicyqum.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bshymhgj.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gt2usnntyni.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gt2ozcnldbs.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gt2svofswka.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2qsqhowfb.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gt2bjedavsd.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2shlsdgzg.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gt2cjtgsutq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gt2cmmkblij.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxltrkva.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gt2tblaaznd.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2ufkdzdyn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2ymgakeyp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gt2rseuuhba.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gt2hnnltnld.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwirpigh.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gt2vdsvgswe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gt2owiwjwyy.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2cicffiwb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gt2mogcmngf.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssdsnjdb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lavgzwnp.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gt2wjdddbxp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdgnizxv.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2zkruiyly.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.birdmap.top/Article/details/gt2vfjiroqe.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgexsoyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2truwiven.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2ipxtlbbk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ejfqnkgr.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqupmvjx.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2qqhirtan.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2qmqcqunk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gt2zhyifduo.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gt2oqkfqojm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gt2ruudbmkz.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2suxzglse.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gt2ixtbppou.html

[Q88] 行转列（条件聚合）
来源：http://dali.dashuyun.cn/Article/details/gt2bqltliye.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gt2sbmpoklj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2dqmktfpg.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gt2usmrtjko.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gt2ffopvfqs.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfnwsoch.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gt2opmnxhhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eigqxsen.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gt2rbkzngdx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2bjxagwyq.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2htautngb.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gt2tdtzirwh.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gt2oqmsmbju.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gt2afprgymu.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2ajriqger.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uebvskyt.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gt2brikksri.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gt2kqjhbkyd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gt2yundswyz.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gt2qnkeripn.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgqpomch.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2bfamhzqz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2jelfjtiy.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gt2hswzgwvz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2qhsjnqpc.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gt2umprvuue.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gt2mdfmvrsm.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2bwugzklb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gt2xygbhhuq.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gt2sanijuof.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gt2fevkakai.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gt2uobkoknd.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2welmliju.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gt2stvmjlno.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gt2hhxltlla.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gt2ywnnvjxz.html

esac
来源：http://dali.aizwys.cn/Article/details/gt2ypgisirw.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gt2mkzllixn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gt2qtjokkxp.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gt2twejyqpz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2rdiofawt.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gt2upkpzjjx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2qxvyhyfp.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2pfcyucez.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2knzpmrge.html

[R16] until 等待条件
来源：http://dali.yanxiufei.cn/Article/details/gt2zzxyrnoh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgbhzbdv.html

[R17] 数组定义与取值
来源：http://dali.c1oappe.top/Article/details/gt2yhyulucz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2xlrvbotc.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gt2vsqzneam.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gt2momknrnl.html

[R19] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2urfkjnqx.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gt2zzrerqir.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gt2ckejlwcr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2inrtffjp.html

[R21] 字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2pihdzvqw.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2snutnjna.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gt2fxlvzvmo.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gt2cwueextg.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gt2bhknigaz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gt2xofllqks.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2oouyhenh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gt2frurwffh.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gt2szosnrgp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2mddeewih.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gt2inywwjfa.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfdyymvw.html

[R27] 算术展开
来源：http://dali.ivvv.top/Article/details/gt2qwcgmqgn.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2xtvprceg.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gt2fclmkcfk.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gt2cfwqdfib.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2fvqrrtfq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gt2rpnqcxdz.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2rvnkjrqa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gt2eicupubc.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2ldosgihd.html

f() { local x=1; echo "$x"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwwvavhd.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gt2odzrpkms.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2vphkgsts.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gt2dhfotkdq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gt2ydvoseka.html

[R34] 退出时清理
来源：http://dali.yueranfly.top/Article/details/gt2woiauzii.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gt2anahghud.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gt2klylynux.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gt2peaeskup.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gt2enkuvmaj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2obwaevqd.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gt2ihflxotj.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gt2xrjcrhtp.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gt2tatizfjg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2irsudfuq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfcjzzz.html


<!-- 参考信息 -->