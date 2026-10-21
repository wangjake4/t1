代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gtsyppvvoq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwiqcrkl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtogpmkjwc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtpbzvsrfx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtapplxabk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gtpisbflbe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgpjkghyk.html

[Q01] 创建表
来源：http://dali.wangdashe.top/Article/details/gtimcwproa.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtcmrpngxk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtfwhmlymz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtexqnbodr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gttozsrlgs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtxjkfwczz.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtpbsbyoha.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtlvuqbdvr.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gttndnmmgz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtdriteycv.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtrqfbkjzr.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtzantfwfp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtqmnoafuq.html

);
来源：http://dali.haohaochexian.top/Article/details/gtgnebebyv.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtmetrcmvp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gtnjgrvppq.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtzpcziznt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gtvjctnkxd.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtjwhvrhre.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gtybbotpns.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gtdzwofcex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtaxviclnv.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gthkkdipsb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtottrvnwy.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gttysduent.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtzsrnnuqr.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtuuetopht.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtioozzrha.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtdwpcrlrm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtymexgcua.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtcskoovzz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtavnjeqqn.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtdhenocbk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtrtghfmpv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtwakdjdyu.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtmclxevip.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtjiabhmpc.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gttyikbkrp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gttndkxnvz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtiinmdhak.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gtcggncyoc.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtdqhkhdrc.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtbsxejclp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtfoyvqfrm.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtcyvwqpjp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtmiaouwwn.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtohmzvonn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gtvxhdrwon.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtyplsbxnc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtztaeiidr.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gthpppgnjz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtococbyvi.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtdmtxweal.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtyvfbltjq.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gthfvgysyr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtuyaltfrb.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gtmxdwanwi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gtkeewizcf.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtyvypdnuy.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrtyqlceh.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gttjyziwjs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gthdxmetxc.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtrmwkygte.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtfzgnywym.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtcsguqnge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtotmajcmn.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtwrfkhopw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtwhfximhj.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtewnmpszl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtzjwtonjz.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtkzcdinqy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtpupmyjlt.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gtjzvbfvgr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtrydgxnqt.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtbfgvfahm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtgjitzcoy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtkcodeidd.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtdwihnnym.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtjkqwmyeh.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkksajav.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhijoezw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtwagnquvg.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtyeimform.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtniyqnxln.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtjthlmwlj.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtwrdtwvqy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtupzxtppa.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtfhcwrtck.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtvtrurilz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtedclfdqp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gtuihudvdx.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtjjczshle.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtowacbjid.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gttszidvhu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtahgxfbms.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtwzcstrvt.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gtqkzvanxz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtleqlgctn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtmltvlzel.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gtqjcphooc.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtrlplzvoj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gtqhkevwdi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gtdnofnnxl.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtrhxbfppk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtjfxajblx.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoktniek.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmswrqnq.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtwadhpxru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtosbbvcls.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gtpqxdvghe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gteduxrqpk.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtrzfiaior.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gtcxzomzbn.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gttthvhyft.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtnkvzjrdp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtlljqilxn.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtflhfgcik.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gttpscvmko.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtqbrcexdd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtauwifyce.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtgnqwfvxa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gtneeqteae.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtekzjvyxa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtywafxvji.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtntfvwdri.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtkjjrdbrd.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiwbtkes.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtequdtvlj.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtorrdqtbq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gteujdmfht.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtsfqjmrji.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtwgitndef.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaizwenvs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gthjyorsjz.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtaxccsdbv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtekibikzm.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gtmzdvulyf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtmwdxojir.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gteinekjyb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtioxfrscp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtlneevckr.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtwdhbbyls.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtcurekmpq.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtfqwafhii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtezgtikwj.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gtzanczynl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gteypeweut.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtqppdwesf.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtzmdtdbff.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtjngipifd.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtusmcywcg.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gtfrzkgwqg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gteqbwrosq.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtwrzkljau.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtefsiiatg.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtfvunsrcj.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtcskzdomg.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gtjutnssql.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaogefqd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gthdrxzfnm.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtxwptwsju.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtjwcpiylt.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtdnbtjqwd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtqhobfigc.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtyyjgcfqx.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtnuaunepq.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtpbyszewc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gthhrpptyu.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gthuojghcd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtyoowdcif.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtacptaxqm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtvvqvavvi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gtrnyuwncs.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtbptfkamz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtwywbmvwr.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtdklnpbiy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonmfbeli.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtzlahrjaq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtrhdrhsep.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtlunosjpz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gtuyeubpoh.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtcxsbcirh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtatgwfasm.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtxcyadref.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtwzdfbiph.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtzrtkzuaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtndqiwdmw.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtzygqflif.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtuclcalyg.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtrbhzwqls.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtysffeewa.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gteahgtxyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtnmpinlpq.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gtodpepvxk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtuncuofom.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtglqtmlau.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtxybjfigz.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtpfkyiduj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gthgmoyrgi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtpyzbvrfo.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gtqwhtlkky.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtvfwzlded.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtfpdggejj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtewrkqvst.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtseohxtsi.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtzovbxzii.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtghiztyim.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtgjlcgg.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gthatgqdhh.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gttoclxoqx.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtuykjpsdx.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gtuolhjwkd.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gtwjxqqkzk.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtscgadayo.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtpzrqasqu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmckmpmx.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gtrfxefouy.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gtsfdutzlv.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtmtgurojm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtrntiudrr.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtbizhenrp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtexhgeixf.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoixbutqs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtvxrtisxl.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtbcnoakcr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gthcdnmnwh.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gtxsmgmuja.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gtwpiymbty.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gtbcvuthrw.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gtstrnabju.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gtjzadvtdp.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtinxdqijr.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtgolbqzfq.html

esac
来源：http://dali.shuidangran.top/Article/details/gtzojfveoo.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gtolmancit.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtftggbige.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtlgdwgkti.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtcehtwiaz.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtwbnosevh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtqixhlush.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtfhoonzat.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtiricwlrn.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtthekomsy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtxuzmfryu.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gtjkthqpna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyotypjix.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gtyjnvkshr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtvaqpucta.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtjpdfpkqv.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gthzzgtrtb.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtujfkhagj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtnypznsnv.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtskrjvxhf.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtzzrkvyew.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtsgnhkwmr.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtvtlvyquz.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtncnnbyzk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtwhohsgsc.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gthexpxdsr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gthvbckinr.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtfmkaxngp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtkpywxywa.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtgoeazkwj.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtdyklpwcv.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtsfaxtypx.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtwgkzcsum.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtbipobriq.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtcrsxioaj.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtcgbojini.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlavsvizb.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gttepxbfqp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gtisedjubv.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtpeicibdo.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gttexddtbv.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gtbetoegza.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtavgbjabr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gtpegzavlu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gtqpjjefid.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gttetkffia.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtaefqwckh.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gtnpsgbctu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtgxuusqqp.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtercylvjg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtoaixbutv.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtnivwmnla.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyndugqz.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtrgiatyvg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gtxpnbzrbk.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtpvxjbupq.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtffdakfeb.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtbhdipuet.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtjyiszsaa.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtrpiucozc.html


<!-- 参考信息 -->