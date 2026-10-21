代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtrniagxbm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtwcitsfje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtygcqvbzt.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtdpzwipkf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtckhnviws.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtgymzlvuf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtwlxypcvq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtuniomzto.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gtlfubcdfs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtrytwumws.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtduzkbypx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtpklomfpc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdyjnfjlm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtbxehrgkq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxjalapcd.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtmmluxrxi.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gttmejvgfu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtutxybtim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtyaucelzk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gtzvyspffp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtoqsbirnw.html

);
来源：http://dali.ydzc1.top/Article/details/gtarvraaxj.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtjanyfvzw.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtvfogfdcv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtuoatertu.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gthrocchhq.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtokoctxex.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtbdmtqppm.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdisizedw.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gtjtsamwax.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtttzesdoa.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtnjauhzaq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtvdqncwmv.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtiistirju.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gtxwztqsrd.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gtvcsofznq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtagmlnzik.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtfajnnctn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtdddgnqit.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtrqxghqje.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtpmyelibe.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtqqgghgmi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gttrkekxwl.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gtrfzhfjpd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtsrjobwmf.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgezllqi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtbzsbvpln.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtfkjwefyf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtkflvxvez.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljroeqex.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gthpbkjyht.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtehlouywp.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtwflkqvie.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtomxfqjos.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gtepvwibdj.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtszhygaba.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvzkmfypu.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gtjpdqnavb.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gthkbdgyox.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtglpbhxzj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtehvgnvdo.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gtobmkhlza.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gthyogztqq.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gtveblwvss.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gaohongyu789.top/Article/details/gtoscliqbe.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gtwxzkertb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtzsbezzsv.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtmlohykrs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtuvqxidjo.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gthnqhskzv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmixwrbur.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtziczypci.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gtyropqxjo.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtdgswnnso.html

SELECT DISTINCT city FROM users;
来源：http://dali.fengsongda.top/Article/details/gtkoqimzlz.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgxqbffz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtepzdhfhk.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtziwaeres.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtavfvdwnp.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gtsgxocide.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtkjgjnycd.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtcorxxogv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtwmhlezac.html

[Q29] 最大最小值
来源：http://dali.iojbl.cn/Article/details/gtxuftrjqi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtokawtwfk.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtstppsuxx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtnmswwfpu.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gtrtoyumkf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtmitmkkov.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gthfwajsxq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtfhbbyrcm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtqaziaepc.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gtrbsftrfq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtibameeny.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gtmzucdasg.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gtrkupjmkh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtganmnnaq.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtasppxnid.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtjkvfwipk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gthsepyvjf.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gtxhabtaox.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtucgakrid.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gtnaingiwg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.smart0.xyz/Article/details/gtogpwxvwa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtzodoiqze.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtmregqhlt.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtmsdvvtyf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtgkzxhcht.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gttdqsjalj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gtrsuyvybw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxuanxn.top/Article/details/gtsilvbcei.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtzamamlqj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwgtveur.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gtqnixqjdf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtwyzybvqz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gttguqkhkg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtchzwdqaq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtkzqxhguf.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxdjyxho.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gtfvcqsioa.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtkkcfqwyz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtnvvhweul.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtutumlcny.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtopczodim.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtngiihxpl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtlsvumcqr.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gthxfmwvjk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtxfmqtvhv.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtzkfgdoku.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtnrwngxto.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtzdgyigdp.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gtghwzsqlu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtakgidkau.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtjyxbdigt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtnplgtant.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtkpxmpglm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtflihdywz.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gtosppxuqa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtglgkmikq.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gtzbybmodw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtbpjytbui.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtaaoblrwd.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtkbhkkonm.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gtbjkubxjx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtwzraggzv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gthpgdglcm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtffvpqyag.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtrtayemdb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtbgmlszad.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtuaxbhpcl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gttxyvkmln.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtfitulomv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gthbgukoip.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gtpkbiplaj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tianlin.xyz/Article/details/gtuthzyvkf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtkpncghfn.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtjrsxbqqq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gthdivhghn.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtkpxfdbej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdftzyfg.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtztzmzodg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtcbnduibt.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtgvthzzkw.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtxoorivva.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtqbzfgxvo.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gtajdlaqru.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtmobnsius.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtrwutvfbj.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtxkeunmzw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtjmtrdvpd.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gttmynmylt.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtabqsztog.html

ROLLBACK TO sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtkprpausd.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gtfxeligpg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gtnithsrfd.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gtwafhwyfj.html

ANALYZE TABLE users;
来源：http://dali.nwbrower.top/Article/details/gtxzmuonfy.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtbgjfctuc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyrwsblo.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtkoiraajx.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtaxqobris.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtxvwohqjk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtewqtowxh.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtfgxybbgu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtktxxvpfb.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtsoogwenc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcofwpagw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtvhqfvkbi.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtpopnynql.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gtfliotciv.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtzmwchdcj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtcuifabmc.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtewgmrvtw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtzohaienh.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtsbvgyvio.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtkdcibzdc.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtllouslbb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtiudrtzmf.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybvszsqj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtumvvsxax.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtknxdcmyi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtfoaokzgz.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlahdwgr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtjmipiose.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gtiepszzrj.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtirvuizyb.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtawozpqvh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gttlnbnwqx.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtvgbkbnnt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtcabvbdje.html

[Q87] JSON 字段做条件
来源：http://dali.shzxlz.cn/Article/details/gtvessdyrb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtwvkxcqmu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtzhhutytx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtnpoydhjt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtwquexjjy.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtcdwelmpl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtaedqvvnh.html

[Q90] 生成序号列
来源：http://dali.shuidangran.top/Article/details/gtybjjhhcb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtqctcurfl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgxzfgeqk.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gtljlekpxp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjiireqz.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtfplyereu.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gtltqfalmd.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfbgexow.html

[R02] 变量赋值与使用
来源：http://dali.mhx1999.top/Article/details/gtkepjpbhk.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtzfaysisk.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtiawtobuo.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtygmzkhgs.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtpluxqqwd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtotfgwmrh.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtlychgiyl.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtgbduztik.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtpmezamit.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtdoarzmeb.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gtmanzfbww.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gtudfbimxm.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtjzwgnfrr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gticiekovd.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtnsmgpqlh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtcmhhacqp.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtwcqniqhk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtlyttxdgs.html

[R11] case 多分支
来源：http://dali.zhongyouzk.top/Article/details/gtjwrgvqko.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gthmdnsijm.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtegmwkyrp.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtgnpwkucw.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtqdgsojwq.html

esac
来源：http://dali.tianlin.xyz/Article/details/gttesvohuj.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtsplvoqdb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gtfiakhvjw.html

[R13] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtqszqnwhb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtoipfntfs.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtemcectnn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtdeccplav.html

[R15] while 逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gttnkvtmlc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gtnhuqafhe.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gtifuwcgem.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtvisusvym.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtuginzfdv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtnuxvmbqg.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqjvmpef.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtthmjsrut.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtrablugnj.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnipkrnxz.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtdbaywuso.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gtbqbbwdai.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtgewltbyt.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gthtwhklaf.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gthqdrswjt.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtgthpaemm.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtrktcirhd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtbyfkhcvf.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtgbvlxxhk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yongpay.top/Article/details/gtadpyfdxx.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gtddlahtuk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtobwusyad.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtfqjxzlza.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtwjiojutb.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtayobbqvj.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtvicspapx.html

[R28] 浮点运算
来源：http://dali.kuanghao11.cn/Article/details/gtwpllttfa.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gtanhfzkrq.html

[R29] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfcppgof.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gthpvvphoo.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtwxonwkmq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gteqcdwzrb.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtolmlhvtk.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxuanxn.top/Article/details/gtgleeiyvl.html

[R32] 参数个数校验
来源：http://dali.shzxlz.cn/Article/details/gtwczuejtn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtxkcmqnnk.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gthbpklkhe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtwrkpdqcc.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gteunomosw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtwedmhwrz.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtlqrcefzd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtemzmpwgh.html

[R36] 并发执行多个任务
来源：http://dali.xylfe.cn/Article/details/gtqcrmynas.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daxiang520.top/Article/details/gtysflupte.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtqlcrtjxu.html


<!-- 参考信息 -->