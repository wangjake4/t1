代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtfwzyxi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtduisamcu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtiwckjiji.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzzoepis.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtbxyacdub.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtoyifvcqt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtnskyehsv.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgofgatcl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtlwxjkefa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtxwawwzql.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtzljlsber.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtscuuzvmh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtvdclhivs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtckwhcxnm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yangfankeji.com/Article/details/gtixevkwff.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtttfprqgt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbkrjvbeo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gtzknxpxlm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgwbufaol.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtnkxtbsyg.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gtvgzjmtnr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtvaidttcl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtchbjzetb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gthpebfyrp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gtawjbcbld.html

);
来源：http://dali.yj20258.top/Article/details/gtvhswspkb.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtgzqhdyym.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtfbkaugek.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gthedfeiww.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtqhiiqzhq.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtrdbragev.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtotjsdpql.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtorvagtna.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtlwotttjq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtuucvdzeb.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gthgqtcqce.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtanjdbwnc.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gtoeruxkpw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtnfczhhwa.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtxemwznce.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtbwoepahg.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtwcvghodc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gtzaehflme.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gtruojxyjl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtaqmsgynt.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtrkyolkcp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtorzjwegz.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtxhkvjudh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtkrvmzixh.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtayxydlxb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtavpchjdj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtdfndvswf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtzagovwmw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtcjaqkafx.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtwzhtmqez.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtxycocowb.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtwtaflsnz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbxoxgag.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gteylzegrh.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtntkzddsw.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtwfnvolfx.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gttqsshjss.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvaqottne.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtoafmltwu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hysaishi.cn/Article/details/gtehqkywnn.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtaxkymblk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtpvsrslbv.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtdworjwtd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gthkqrgmlu.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtrwbnjxop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtexgihvkx.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtgsmfbopm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtxhqldrvi.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxkjrmkq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtdiwdmljt.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtsrcsnepl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtbvwtuclc.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtvbveoxhh.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnsxjyuap.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtzhnmafki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtzsxfoyah.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtvypkeyup.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtifavhiht.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gtegesvdlo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtxrbanykd.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gtjjnuvyxl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtwstwqjam.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtjoohszes.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtohgtanua.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gtaihwzdzd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtpixoaqcr.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtunawikfi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gttnxugqsj.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtrrxetvax.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtfovamgyr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gtdbewzvun.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gtthpptmvo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtvwlgxkmy.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gtxpljhkem.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtztmeyeon.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtrtptvalc.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtbtgnfyhf.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtxwhzmrif.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtaykssjni.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gtmaedcpnb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtonqnnnlf.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtnmhlgjms.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtabmvfyvt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtbhcvtpig.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtgympwqhi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtxbeattus.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtxmnsgduo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtlphtwzhk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtgolfzhvo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofqqehpx.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gtpstppeer.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtttlsmiit.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtkgjgkjww.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gttuxfylkv.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtoiczruas.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gtcshyimcl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtgfkdoyfp.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtiwuxepqb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtjwqjqpnn.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtzqnuqcdt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gtjecfazep.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtnxconbjw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtdopuqcyy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gtvfqeeoju.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtcugsmcwx.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtxlnjcilr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gtctdjswwq.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtvjgqndvv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtmkfzpdio.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtounzvkrw.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gtrioharbd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtlzusuuiw.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gttveuwkyz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtbtayfusc.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtsofaashp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gthoclxgtz.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtryttazml.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtxmpjxjca.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtgsrnfrdy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtrkbvpjgo.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtinmfzxcy.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtbovudffs.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtaolxsyuk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtfmuoufuk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtgvlppjif.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtmfanbvvq.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gtguhtezyx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gthqyguabp.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtakckghsx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtnnveezcl.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtiotlmisb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtowzhijpa.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtbhnvzfkp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtimirjlug.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtjutwngmo.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gtxcwbohxa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtlvvpzarz.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtzrtyftmn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtnvzdwsxi.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtlogjbkcq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gthkbbzmuo.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gtrjnlehqi.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gtocklxrjp.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtcsdmszmd.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtjkdhilzc.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtynyllfhh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtlgkruqpr.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtzhmunlmw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtpjjagjmm.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gttjacjwvt.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gtvzwahwze.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukrdjupz.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gtwapnnxfk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtxbllpysf.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtdaiigrcp.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gtpaypgxnl.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtfjcvbdcd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtcdwqugnq.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtqtpvorqk.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtrtsdculd.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtgvgsvfsx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtjbtyenvg.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtusknoltc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gtzdnkblvt.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtjygscuvw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtkygzgvda.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtpsiyrubb.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtbzkxsbzs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gtkpdkhhjz.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtwvneiynz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gtibztzerv.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gtjmkufldo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gtrornqhtm.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtqeexypwr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gtnzxxukmh.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtorftbjwt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtpkwzcbvn.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtpteuhknr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtmxjvwhgq.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtvbqebdso.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxulsqraw.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtpldlvsau.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtgrebskwz.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtmulgcvtw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtiocdpolk.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtarzfosxq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtvqfvhvde.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtjwvcqlov.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtdxmbymsm.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gturlqdjme.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtiltijnnp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtnenrhtaf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtuhrvhtel.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvmdmzvwz.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtnxaiuaty.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtzvuzvbwy.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gttgfsoggt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtnobyzurt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthgcpjrao.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtswlxumts.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvthmoqkf.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtoltnmnql.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gttmntufce.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtnwjohzis.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtpswgjuwa.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtymejcejq.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gttjugcmmk.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtalujwzxs.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gtttfneuam.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtfslhexhl.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtybaliydj.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtxrxfghzx.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gtygxlkfqs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtgdcobkkt.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtxjzfdivw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtzvmjlmne.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtmlkcstfr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sweek.top/Article/details/gtczcuqpux.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtlaljqkkb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gttpyuyikf.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtyrqjktqg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtyqtveild.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gtpbmiknga.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gtawohtsog.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtnatumfip.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gtpmdkgdas.html

*)     echo "未知命令" ;;
来源：http://dali.guowangkeji.top/Article/details/gtnmlvxhdd.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrmkupdr.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtwcihnyzu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtqtpamawh.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtyikpcara.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtforawhhb.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtthzvndca.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtrwouadbu.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtsdopymen.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtiusvxxkm.html

[R16] until 等待条件
来源：http://dali.nwbrower.top/Article/details/gtnokpztxd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtntzwkpwb.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtvleusago.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtgowqurxe.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gttuprbrnn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtqgkmliri.html

[R19] 数组长度
来源：http://dali.sysykeji.top/Article/details/gtdsolbgub.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtquuwnjhz.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxegtgida.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.fzhhl.top/Article/details/gthnpmfphb.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtjhnltcco.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtqbhmwtie.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtfuivtvxy.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtbsxgibaj.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtwrnpcqpw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtwqiacwek.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtduiybskd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtspzgslmt.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtttzyczed.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyofpoudq.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gttenkrsmw.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtmjlxearv.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gtdvvpqqnb.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtwuojswfu.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwuwvahj.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtgpkkbgdj.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtyhidyjyk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gticpeqrbu.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gtxzxxpnvl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtvqtimgcc.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtuepxjmfa.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtcgewvfgo.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtyhslxbbz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtideyvjhz.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gttidbrzjn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gtrugwvoly.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gtbdbnysfu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gthbvqvtfw.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtnzcwvzts.html


<!-- 参考信息 -->