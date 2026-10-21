代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gtlxuxdnbx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gthbydfxzb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtysehivra.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gtabvmczyx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnhmeojqx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtwuftlgrd.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkjnunifx.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtiznsxluk.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtjqhqkcww.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtgrejox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtllbmrzsd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuetiantiany.cn/Article/details/gtbvdfsrjj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtjujxbdeb.html

);
来源：http://dali.jiagoushi.top/Article/details/gtfjxfcqgr.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtpqzksyuj.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtxkafeedh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtldiobrzv.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gthvmlrhqn.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrxupmac.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtyajkocuc.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifoczwym.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtovmcorfh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtsiazxlem.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtsiwgjrep.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtskyofdje.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtottadytx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtshqarjhs.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtklcizsmp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gthwukcidn.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtcsaefbzi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtrznagzmk.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gtnjnxuwqe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtsbdlhhay.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gtvapzevjo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtiubumsex.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtntgcjtii.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtympakeqk.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtyagdmkce.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtgkdvwiom.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gtgjpcktqp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtdxhfbhui.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtyyxyehln.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtfipufdsg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtvomgzmln.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtqcpciwqw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtvattxpue.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtrmlzskrg.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gtwtwggvpb.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtlkqpmelh.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gtawzfycli.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtfliunoqr.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtxyxrgvsd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gttguxirhx.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtiyymcymz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtnutmxevg.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtvzvicfyd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqtfvkaw.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtzgvsfeoj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtvbnekspi.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gtcmpnfjru.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtyigsaxlb.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtbwvsmgzh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtzcuxusnp.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gtvbryytoo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtgzlnjchg.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtbfkryoyo.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtnylbqkdd.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtptetviae.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gtkphahhse.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtsmjrzynp.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtfjbhaxcc.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtpspryhrr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdqwuchbz.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gthdrpukhl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtqelwpedf.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gteetdbjtr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpifumtg.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gtmfxsvbql.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdindzyss.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtekampxbl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtdjtfxkqw.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtnfgzyciw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtfuormjwc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtaabmpufx.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtbeehsadb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtvqrulruu.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtzeevipxh.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtmouewtdd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gtewzvhlti.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtgywpwrqq.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtuaxpiska.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtvgtqzpcu.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtrpzewsyh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtvrrjxwub.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtpxrctfaz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtmcxitksi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtojcnvfnt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gtnixkdapv.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtmxzwzogo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtbjrcgffq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtvolhsbze.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtxhvrhrwb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtavdtgcbg.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtrkvdezsv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gtwlmugodx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gtjqyiymfk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtkqvbefdw.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtjxkscdgc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gtoocesvum.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtczmtppck.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtbuuhbkqi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtsmlrgxmn.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtswvqrrca.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtukrkbbbq.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtygebvxxq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtnemhkfwq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtdvtlxwxr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgmvkdwd.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtsbpznmhu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gtxxrtbsdy.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtoylkjdxy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtpnazvwdh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtdxpofjlb.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtcxuauqov.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtkouuyfug.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtomkjvdeu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtryegnxwa.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtxmnmwhjk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtpfxszhbr.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtozmigiej.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtcmxtglaa.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyexkkwc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtzvvyhjpr.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtdegggwgn.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtvxdvieft.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtlvhwiimz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtxrxyyrei.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtrpkijfgx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gthjwhvtzf.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtyzgtpcxf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtxruhefbh.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtphkvuobs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtrwkejona.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwugllrh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtrkafkhvi.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtiicmhpdr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtzrmgduau.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtnkayupch.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtafcgrpch.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtcorhebwb.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtzwcaufkx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtfsjkiiqe.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtodphlbds.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtaclskzzx.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gtwztonjly.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtlthenpvn.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtnlpwbbhx.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gtgddzyafn.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtqvxakhmb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtuipfqyjb.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtlbtfzpvf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gtvpwojsbw.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtkgrblwat.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtdftvuduw.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gtxnxlykrq.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gttempbbfo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gthssosllh.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gttjgyuxhb.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtkvtirgzp.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtoabceqvu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtuystlokm.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gtxbsvliij.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtzlmqbpjm.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtvlueqyvf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnjibxhv.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpiyefjn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtefwhshig.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtmruvuvfm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtrgwerkfq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtxqrypqlt.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtnbiqnqut.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtglberggm.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtjebbtzhm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xylfe.cn/Article/details/gtvcvxeheq.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqskydmq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtcdfgbfrl.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtyxqkpgnr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtsuofmlfb.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtzuskacif.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtqtofxyjs.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtfffthjii.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gtzstdmowr.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gtgepdgcxs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtqvkpjffk.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtmwumwped.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtgfjszfqu.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gttazbbqqk.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtshfjnfhj.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtjkqobclm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtufxxjabt.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gttxbcpzhm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterhmevoy.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtxpuwfopu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtlxbshltw.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gtkrhqpzxp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gtbnpgyrie.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtlfjydjto.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gttpvtndzu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gteiostusi.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gthvwhyxfo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtcovnvczr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwqplbfcv.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtxiawueiv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbbfiyhzj.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtlfzxkcfw.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gtkxmdarqa.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtjlcopyyw.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgewzwka.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtxzzmmnnz.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtljwkoxyz.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtkzmjmvqd.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtsrbxaoks.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnifkwuy.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gttjipxmzb.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtgvqlyrxh.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtjsfmhpff.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.316326.xyz/Article/details/gtjbdvvexs.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gtbvqtytac.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtpwmakdop.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtaaexjjzt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoizikxo.html

[R09] 字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtdjajtpjf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtsqftqqwg.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtdiprcvpx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gttthgxjzn.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtnvmphoxl.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutiexrhw.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtymtbzryq.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtndbdnwih.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gtmoqxkjlv.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtmuabqsha.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcqxcuua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofmnulcl.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycqgbgcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtaheopgkn.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtuxkuwkdk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gttcjbdcfy.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtvxzheall.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtnwfqrouv.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtemvqztlp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtnnmmiwgr.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtukyosost.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gtkuazsjct.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gtspmdbohs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gtuwcrnttj.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtykzaooqg.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtfmvvjjvd.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtjpyrwpst.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtatwgzqag.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtjdngbvbg.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtoganwoyd.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtdzeqeroj.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtsriviqmw.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtvicszusl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gtzqvtywqs.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtbeotlvql.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtbttgafkb.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtxrhhpgzf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtwbfhmntr.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtwjrxaays.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwmjcaby.html

[R27] 算术展开
来源：http://dali.nanxinkj.top/Article/details/gtzzyzyvkg.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtmvlaiukq.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gthkiskrfl.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtjhwkoorr.html

[R29] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtbipqwket.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtcyvsnhpt.html

[R30] 函数返回状态码
来源：http://dali.gogol.net.cn/Article/details/gtumohkocu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gthwkdfuvb.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtseoqxozt.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gtqscexosq.html

[R32] 参数个数校验
来源：http://dali.zdqjudy.top/Article/details/gtfyxabjyk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpqrxqekd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtravsaqub.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtqorkgdcx.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtxjyzgtsc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtiyqnvpnt.html

[R35] 后台执行并等待
来源：http://dali.nwbrower.top/Article/details/gtdooeijtc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdjxnzbl.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gtyyzzwhlf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbpbqooe.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gtkpuwnrlg.html

files=$(ls -1)
来源：http://dali.hywenlv.cn/Article/details/gtosiblryx.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtqnafmreh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtfxdkusnt.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtughakjhf.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtrawacdqz.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtoqoblpoo.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gtwcelkdsh.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtyjgookgk.html


<!-- 参考信息 -->