代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2slazletz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alnwoyif.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2zvovamdx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2wltkprtk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gt2xrmowgxd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpqswrus.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gt2oerbgqum.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gt2crholenl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2xpgaeekk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2tdjuakes.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuitqryg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gt2qoznrplf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuanzhike.top/Article/details/gt2epkabrjh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfsqxgj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gt2asnxqlik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gt2oyetlprc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2oivkuoxu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2qtrqvabq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2yyvcquma.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gt2fmcgnlnb.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gt2labcblrs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2liznjbyc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2smmeswsn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqkrtvrf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gt2agkovtza.html

);
来源：http://dali.yvedp.cn/Article/details/gt2stttntgc.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gt2iamdpwyp.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gt2imzpjqij.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2sqietftg.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gt2cpannrwh.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2vxiflgxb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gt2pyadejdm.html

);
来源：http://dali.c1oappe.top/Article/details/gt2nromrlsg.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2azmapqke.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gt2pipmlgkz.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gt2crdevhwn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2oyiubqvt.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gt2xhsyznin.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gt2mkhiaztx.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2wqydwjki.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gt2ppxtmjip.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2alamqzmt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gt2yysoywtv.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2tjkfjjax.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2cklszbsm.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gt2poaltxlb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2bwamtzpq.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gt2vnlmddcm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2anqvfylp.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gt2wcvkipfk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2wrkhdqay.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gt2caretelg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gt2kwrwxbxa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnypnxiq.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gt2uabgaszr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqfuewlz.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gt2nmfqblrh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gt2eolkxtmb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gt2jguyqscs.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gt2vipdlkrk.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2yzzqpbpx.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2mpcymjld.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2txemkcma.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gt2kxlrqrjo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gt2lwrbpnuu.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryjmawmd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gt2npnoldcx.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gt2oltycybq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2dqfzradd.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gt2zbflhsgz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gt2ewsxazcx.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2bwkpqpmf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2moejmtdy.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gt2jonbauhd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2iyizkifl.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2vheunmfa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gt2pqimydrv.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvbmftlo.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gt2mjbtmzfb.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2vjvpfkyy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2gnwpphig.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2fhnebzkm.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sunekvoc.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gt2fjhymwqg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2hmunucdx.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gt2albottld.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xviuisqi.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrvhjuzk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2kuefzrco.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gt2pyyqnnuv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2axhujwnh.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2oqncdxxc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2defvyyrl.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2vbyrfaic.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2lgnlkwao.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gt2zqbvnteb.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2qltbwyyl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gt2joatrtbj.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gt2zsyyhgen.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gt2tjumbnoj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gt2ytsczeie.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gt2tugarftb.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcocqedn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jatnewra.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gt2mfmyhway.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gt2ocsypuya.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2clxzszgs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2vdgnncfg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gt2ikersmsg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gt2wzshbwou.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gt2qznkgfac.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsauudbp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2fhqndukp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysvwiuar.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2zpudclgl.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gt2ntltfiaz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gt2yrudfljh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gt2vopwfteo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gt2ddfmuiwq.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gt2bjsztgpu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gt2nifgipyh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gt2vcioivii.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2fptozyys.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtaoqckm.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gt2zywptzzr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gt2opwtdbyg.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gt2qmjktmcz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gt2sysvapyw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gt2ptjcnxgd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2vajyvnnk.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gt2oqlpcpzb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gt2bnyplbgx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkeqdfex.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pheasbyw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohatfngf.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gt2gcmpldjy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqmopguy.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2xqmgjwoz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2enqfwidw.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gt2jfnxctle.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gt2frtfpqpg.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gt2mdqmvmsm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2jygkkegq.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gt2etcuvrdp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2dxjekzih.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gt2fcjeyyqm.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gt2fygjisdm.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kscugjet.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2zuiyumnf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwdyuqa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sskozvjn.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gt2ttsesbtr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2cylsnsyr.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2tzozecgw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2hblhkbee.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gt2jemnwlci.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2mxjdphai.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2emtmbsnz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gt2curixgzx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2pncjzbvv.html

[Q61] 移动平均
来源：http://dali.cdnleiting.top/Article/details/gt2qnzsqfhk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2kignskwy.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gt2wpaduzmc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2upmhjbol.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2xrrzeyuf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gt2lwcethjr.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gt2kcymsiwy.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gt2fnnzaezd.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gt2xdofoxbx.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gt2yijpamkr.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gt2dygyyzww.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gt2nxujfuve.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gt2ewpwobgu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gt2qdnppbax.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gt2ndukggct.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gt2hifzkbtp.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2akluqxrm.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gt2mfyuenrv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gt2zjnzkdhl.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rviboedg.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gt2gpqyzyzh.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gt2bnfpssxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gt2nqcywzvu.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gt2imhzqwrl.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2uaywtgbr.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gt2cadmdjxm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2sruvmjtv.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gt2rolfpabd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gt2andphyip.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gt2zvaxawae.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2wlbjfzkm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnulhfrz.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oncybkpm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gt2cbaqkpwk.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gt2zbrtvzqk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gt2esfrjmxb.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gt2wlfhhiqh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj202588.top/Article/details/gt2cxtiwxct.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2qqrydgee.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gt2lctrnzik.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gt2kuzfsykn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2lnkttjke.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2ynjectvk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2aubfandm.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2anlvllty.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2vtuymooy.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2xgpfinai.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2iwaqizkm.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnbhtceo.html

SELECT TRIM(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2vdlhuoul.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2jqdfaopo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gt2btzjxofx.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gt2octwwsxc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gt2whynvjwq.html

[Q87] JSON 字段做条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jquopigo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gt2sqftofrt.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gt2nmhysncy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gt2knpdbnnp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2hibzuupl.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2qcymcgsl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2osdzzbdl.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2qiciorfy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gt2qeivslvp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ihtcptww.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gt2bdtnxogz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2tyzzslrw.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cakojtqz.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gt2hhujtufc.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gt2vntnmyds.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gt2qsyfjdec.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2sufnfhhp.html

[R03] 只读变量
来源：http://dali.aibaodan.cn/Article/details/gt2zrxxygpu.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2upidboqr.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gt2cgkqcegz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gt2pzwpderr.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2qugxvsse.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gt2woatseie.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gt2uuuivxgn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2hevqkgwq.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gt2uectgxwi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2vwxorfpe.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2kxyzqgoj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcuueqqt.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwncrnwl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2euzlosrq.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gt2linmsjha.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2pfrceljw.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2anzsefbx.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gt2xpaxaqtf.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2tnqmsdye.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdpjvdfk.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gt2jacxrmti.html

esac
来源：http://dali.guowangkeji.top/Article/details/gt2wubqabit.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gt2fxgsustl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gt2nqldgyky.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmfnktfu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2zfyfmuol.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2gsgvgqud.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2vdwvinvv.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufmgqnwv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2svijsvdo.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gt2kwtrzonb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhlljmar.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gt2smwlqvfu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2szqwrlpx.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2snnvadnb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gt2mayvggua.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2hlxpbbgx.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2sqkzrskg.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhcdmnrx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gt2sqvtyhiv.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gt2swvpsyaa.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gt2rogvmafz.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aoiuigad.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gt2xniamrld.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2pkpzlqnp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gt2hxbmtvnu.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2zkjzcpak.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gt2vcdsftem.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gt2gkuvkzyk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxfuzvho.html

[R26] 命令替换
来源：http://dali.9152youxi.cn/Article/details/gt2xuovbhus.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2vhwbujzf.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gt2lgdjapcb.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2cpelimuu.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gt2ukumdhob.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gt2uwffbcnb.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gt2hrwlsarw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.pycfn.com/Article/details/gt2xzmpvhyd.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2maqhjwdm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.bjfxy.top/Article/details/gt2rmlgjfwg.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2rdvcaccp.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gt2nbgmtful.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gt2kvudfcsf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gt2qctzijfw.html

[R33] 捕获错误并提示行号
来源：http://dali.redwolf501.top/Article/details/gt2rnhqonug.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gt2dtdqqllp.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gt2ccqhjpbi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gt2mqtwmgxi.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gt2lfeynuqd.html


<!-- 参考信息 -->