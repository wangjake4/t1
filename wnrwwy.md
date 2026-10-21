代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtnbenzuqn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtgifbtyjd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtnuemwnqg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtdqppnpdx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyircydlt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gtoznqtagh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdwffcdiu.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtrxwtnyol.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtvqckgcnk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtpezykrvx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetlklhkh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtqytrsbup.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtkquhaegi.html

);
来源：http://dali.haohaochexian.top/Article/details/gtgavwudyj.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtlicyojpk.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtojiqkqxv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtotyizzuz.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtdgsuzwyw.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrczignpi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gtnohbwzhc.html

);
来源：http://dali.zdqjudy.top/Article/details/gteirfrajj.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtprpxkapw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtulhaiapo.html

[Q04] 修改列类型
来源：http://dali.ivvv.top/Article/details/gtxjkoljpl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtehohfhyx.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtbsbjcvhg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbsdvzdl.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtqghugeqo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtwofyzpld.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtredyfhas.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumdckppo.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtktmbedta.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtgeiqnsiw.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gthjgdbolk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtznbkaayh.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gteicutqjr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtxfedectu.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtavmhyqzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtbacpnjyr.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtwjixkyxn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtgviuxcvw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtnkfhcdht.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gtljudushc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvmczfec.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtxwydkfee.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gteooifgrx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinjalzwy.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtrqphkxrl.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtilpiumqs.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsuhbvcp.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtnnjmwvyr.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtlffejvgx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtrroizoey.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gttsciugil.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gtfqzicxkg.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnavofwu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtwfysvold.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtjnvfwqcj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtwkioibua.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtqthkzvpv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gttdkygdwf.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtaotbxujh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtxfunnpno.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtpnieroen.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthduqmljf.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtbkzvonig.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gttryjfkvg.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gtmxrcecns.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtdieczgct.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gthdrvugpa.html

SELECT COUNT(*) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gthgoodebs.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtephklrun.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtzsralqlg.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtqnaescss.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdzxxetj.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtodocfkkf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gthkskmzzx.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtoyihjldt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtuzpectyr.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtxujynpkm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtmgruehnj.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtkvxowkii.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtbxzlilfl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtoqmxryzv.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtrruwkxft.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gtfgttjrqm.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtysynibjz.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgzwcfzg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtrtmxdgid.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtyrjoguwp.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtpuxsnumq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtegvubmdd.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtqynetiif.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtlxwhwyhq.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtzjakjxvs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtnrtkfqzt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtpomntofm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gtqmnnrvab.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtwjppsafs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedmnmeoc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaypoiit.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtkngcwwas.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlftbkqt.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtjjedphgz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtbxppurkv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxstjgeth.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtvubyomsg.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtofhajwkl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtcgcuvmem.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtsgqjbzqj.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtmdccctks.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtbokuwbpp.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtcstsnjoa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtghlpazfo.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtkmrtplut.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtwtfumboy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtilwugcot.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtzgoxezno.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtnqzspnsv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gtjygqfmyg.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtoqhywons.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtqshshmlz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gtbhowrcei.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtudxbwxrn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtfenlmrgt.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtlvxdkbfa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtlvchayrs.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtzaoeotul.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoophzvxk.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtfkssugeb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtbjuvbjnj.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gtfzbwirxg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtpupzcnun.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtdwnwaile.html

TRUNCATE TABLE logs;
来源：http://dali.ehwqpu.com/Article/details/gtgvjdojul.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtvfrqdkja.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gtxfygllgq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbeokxvx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtcvjoldny.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtobqupauk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtztkgkwcq.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtmmfrilbf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtfixbbhza.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtpyjcteuq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtfqjcwulz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtoqeruocv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtqlyojiub.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtytasazqv.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtpsmqsncv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gttllnmeuc.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtbtfzwxei.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtbjtoivgi.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gttkdwusuo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtsinixask.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmjeplzb.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtnqzhlsef.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gticoscpfy.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtaxzkgqvg.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gthadcejex.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtgxhvfdtx.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtnaspxzrs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtnyleaseq.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtnekveycz.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gthmhnidsy.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtytxsjdxp.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtcmfytrat.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gtxbklxzna.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gtnamkguxn.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtbpejoutt.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtexcupftw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtkkszuliy.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtuscwcfoh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gteysfyojh.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtugfhhjdm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtjnjxrvlq.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtqhdszzrb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gtkscikrkg.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtppuykfbp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtgnvuhcry.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtrblmlimp.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtqiazjnkk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gtvmecxsvg.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtwcihkuwn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslycolvq.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtqmgishus.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gtkeiphiyq.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtljuhppgl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtvbqqhfuy.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtgsiexeiy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtnsupybsv.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtxvzezvmb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtabduglcr.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtudefnevn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gteeninxsq.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtuifnyppy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gterjmtskj.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtghqalqis.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtdnfggtww.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtdbwcevzv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gttcbmiwtw.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtpidesaht.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtyfezmqva.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtgzkuyfxh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtxjgduuvp.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtfvohfxki.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtoingeldy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gttrqovrvz.html

[Q89] 判断表是否存在
来源：http://dali.cashguo.top/Article/details/gtllbfljhv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gtccogpkgu.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtsxzwjwef.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtdzzloxsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttiicwiyf.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtvytkosxw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjscvwefk.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtrmktoftk.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtnncluuvo.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtbozxdxrk.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtbrogzaie.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtncoauqtv.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtqeppwwjs.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtzqaisdhm.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtssutaptl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gtdnzuyvff.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtaschpkgr.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtebmtvfjz.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtbwlxetpr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gttkwiyefs.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtmpjikbip.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtalmzerru.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtwymisofr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtjcwgbgdi.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gtahbladkl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtubcoasyr.html

[R10] 正则匹配
来源：http://dali.yanxiufei.cn/Article/details/gtrzfvsssv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtcbqesfhh.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtvbiksfiw.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtmrpjebvz.html

start) echo "启动" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtplxvfxgu.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtkfdjxhli.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gteawguxqf.html

esac
来源：http://dali.bjfxy.top/Article/details/gtmrxgoxzh.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtvvcwdhhz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtmitdtmme.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtaqxvtrop.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtihlxvujx.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtqznzkeew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtuazpawjl.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtbouauvkk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtclqghtpw.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gtpzgspibo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtthtyrnoo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtvrsymold.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtkjrjrqyi.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gthbqftrfr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gthrdgynri.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtunzwtkzf.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtdbbqngna.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtzfebnrpe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtlejjnpwb.html

[R21] 字符串长度
来源：http://dali.tanke756.top/Article/details/gtmflbbbho.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtwjwnsdxe.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtmdvamddt.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gthvliffye.html

[R23] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtjhlagtbe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtcpjmymtu.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gttbfqkoaw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtkyipibso.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtdqxmxuqq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtueqwjcgm.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtplshuoem.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtnyhejafz.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtuuwfliom.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtsojrdotz.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtdpyttfng.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gtjjhuvbgs.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gttlvjzqkb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gtzbkjzvza.html

[R30] 函数返回状态码
来源：http://dali.ppjwa.cn/Article/details/gtkffqxuxf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtttgsmvbw.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtdrlceynv.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtxyyumtfz.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtxsuzjvgx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtqnznqnpu.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gtiyzkijnn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258888.top/Article/details/gtfunfuuio.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtgjuvwiep.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtqjqhipxc.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gtdxmcgfxb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtebnyqqqn.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtiqgzhhlb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtdkmmrmbd.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gtufvxzbhj.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtbplgtcnp.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtmrywkgch.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtgruojjgf.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtmmymjdnp.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxozhqfg.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gtgshfrlmu.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtycovextq.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtoizivdet.html


<!-- 参考信息 -->