代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtcbvgqahd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtsrtmeelc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gthefmxohx.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtuvuwjioz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtvclekfnc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtpzlfnhpe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gtclnhmqon.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gthlxbvtiu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtnadynbwt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtnqrdlvjt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gteiedtpby.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtqputniik.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzooytmaa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtloohmkvi.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmgvlvzvl.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gtlvimeyju.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtbgxvbsyy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gteivpshco.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtinrvihjh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtsjyrnnqj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtiaaoetyr.html

);
来源：http://dali.birdmap.top/Article/details/gtsungbltf.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxrsnwp.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gttdaavubt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtlibrmvdz.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtprvzbsfj.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtrmtyrkgk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gtscapaqtn.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxknjjjq.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjqxfdum.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdwupqzy.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gtaehduqbz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtqtaeuaze.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gtvfonsncz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtpjqfupez.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtaksdqaxb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtzxozsflk.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gthhdxtgoh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtmmedvvuq.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtxytwbgwb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtfgceeley.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtdqhbughj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtzimkpspw.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtlgfuhbid.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtorwkghsh.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtcozyvoaz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtnebsvyth.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gttnjobfbj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtykzdqvet.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtvxnnaxhn.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmmdwfze.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtoavlmcwa.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtwysijyfd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gtpoiukmmd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gtalztkoyy.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtubqqygwh.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtrxypksld.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtpxpzlfsi.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtzgefegyz.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtgwoebffe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtryyajvue.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtzbefjifd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtnqvvtvzg.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtirgezvhy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtllfkqikr.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtqpujnjfh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gthyaunggf.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtnsfxgxir.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtfxsbhpka.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtkembrxij.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtyfsoxkqn.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtptdoczjw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnjldrmm.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtawzxojbq.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtmsumqlae.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtpxpbscdb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtwpkmefod.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gtqenplpry.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdrhgyhtu.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtbzpaippv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gttvaqdyvp.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtvmfhjyjx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtddejxvgr.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtohjsjywp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtfgeundrn.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gtxwtrzhwj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtwhczciik.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtlfauigrd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gtwgzgwizt.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclbsoasv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtilfhknhl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtmhsfvwcn.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtskvcafig.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gtokkobrrt.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtcnwsrqgh.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtwikcawxf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtsvshsiao.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtqnfclflv.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtlwogiwqx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtpphhvrmu.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gttpioydng.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsmrlqlp.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gteyssxxhx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gtsdofpxmm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gttdjhavbl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtaqmyawlz.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtxpkpvwez.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gtltoraiyr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtpiemjuek.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtrylzxzji.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gthcusczbj.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gtyppcydmq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtmkuazpvq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtpmbvmqgs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gtplsnwiou.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gtwsffffsi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtjanzhdet.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtgiogrntk.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtrwyadxlb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpflhtxcq.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtqraguqri.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gtezyvvhki.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtuqhgddhu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtshjbypvw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtvzpkbogs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtitgqdqzr.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtcpfwjvya.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtznynyxmj.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtzjqiplvk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtnjdlqeog.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gtcocsqfeq.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtkjvjwefz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtzxqhhokg.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtaxfiaugn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtdijitjgu.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtjamiltdc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtwptluqio.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvurzacvu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtokbhaslw.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtteifvlvr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gttqupmidf.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gtzskdwaob.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtnvytwsrb.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtmlaataun.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtsccxpsri.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtsbqotkoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtkggrytaa.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtrseqyvvw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtyyqiyrsh.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gtthmoaylm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlynpujz.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gtznehrrzi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtnfsvkjmw.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtcjvzioqa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtilsjphil.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtlcilxxxx.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gtqcfrsjlq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtdhfayvco.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtwnwsjuke.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclufaemg.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtqoljyvaj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtyagsgzxi.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtyavbqwmp.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtrzbgamht.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtjrrpfiuw.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxikluyo.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gtyxzafaef.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtfnotizeg.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtqjrmfybf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtkmbvehih.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gtpqreprdk.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gtgbgsvful.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtngqfzwrb.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gtwlzaxmbf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtleapdcie.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtdbzqwavu.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gtgtzcdvym.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtfbpabepb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtuddbmuid.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtwmknutsh.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsfjrshwz.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtsolruihm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtuqhfctzc.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtouatztnn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtvrggykro.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtvodyvezw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtgubifyjp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtmreawrdh.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtcrdbnqhj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtbslkzhsj.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtmsfpzend.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gtbiaxegxc.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtsusyfnjv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gtsxthipsk.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtjogdaqah.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtbeimlzih.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtlzvsfzxy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtqyzuqxei.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtblknjhcm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjujmbfzy.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtyibuunzt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdrlfknws.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtgjkcmimv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpshqgrd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtylwprznk.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtupvjbczl.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gthgzcafki.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gtnidxchlc.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtxxdrkysw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtylwiwgbc.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gtmyahqlwk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gthgovmbaz.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtygthypvr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtwvajhhrj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdgcpdqrg.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtaxzvchay.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtkxcrhdpi.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtwyknaxjd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gthpometuw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxdnlkztr.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtixdwkewr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtktodbkdw.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gtzkbezdbp.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtluqkkdwn.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtzqfrxnlz.html

[R02] 变量赋值与使用
来源：http://dali.hnxiangtu.top/Article/details/gtinfvduop.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gtuxkgdqxj.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtbiovlwag.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtmjfwkbki.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtiluvhefs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtttyooztz.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtbqxqzarb.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtngcwfier.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gthzkmzapa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtstbezeat.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxrkevlv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtrpcaknuf.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gttnwpygvy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gtaemaqraa.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gtbgcgbsbt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gtgrihbkbm.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gtogxryfsy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtrpcqrict.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtzcfedpjh.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtqmvhoioh.html

start) echo "启动" ;;
来源：http://dali.fzhhl.top/Article/details/gtzryqcyeb.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtbpkigqgw.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaoyweei.html

esac
来源：http://dali.yangfankeji.com/Article/details/gtlkkpaynu.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtxzdfdmbl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtdpnrndsg.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtfjabquuj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ppjwa.cn/Article/details/gtdumvuqgk.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gtqsbqbdpc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtbahotnnw.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtabzirjqm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gtubfvpolw.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtygmwloye.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtigtqkrce.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtlpdcfxqw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtzpbcmljl.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtzouottqe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtojvhuifh.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtjzxslyfi.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtonsckpvo.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtxubdlrcd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtvupxanyv.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gttwkjlyat.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gtquspysrc.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtmhckwoqu.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gtwfyocujp.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtoltrfcbt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gtyxalyfmf.html

[R24] 大小写转换
来源：http://dali.tanke756.top/Article/details/gttmrinqpn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gtkzrzmmiz.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtfjokqvfg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtzcqvdtgq.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtwtfpehva.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gthqlxhzrx.html

[R27] 算术展开
来源：http://dali.quarkkingdee.top/Article/details/gtmmczemle.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtnbfishbv.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtbsywdafw.html

echo "scale=2; 10/3" | bc
来源：http://dali.9152youxi.cn/Article/details/gtqignnycr.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gthmhdwwsb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtvjvxaxoc.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtsgalmzam.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtplrwcsku.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtavtkvzks.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtivohzrpg.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtzppfvrou.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtskbgnyqp.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtfkudoreg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xylfe.cn/Article/details/gteejwtucl.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtthqesuaz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtjvvlyrtk.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gtawnayitt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gtthalglsl.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtijepcusx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtcqrddkyi.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gtlbfvlyxz.html


<!-- 参考信息 -->