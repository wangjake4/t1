代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2ajkacpug.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2cmhcwcei.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2jnmklkvl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gt2nntqgzso.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2qbywrgdf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gt2juxdmwfn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gt2ekkaarxr.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gt2qxwincic.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hfpthk.cn/Article/details/gt2slcfirre.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gt2eydogoye.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgockvbn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2ahdeujih.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gt2hrkdspjt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aekhvntz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gt2hiodpncg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2bcyctwtj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zxpsrwus.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lbmgpfvk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2zwhovrmu.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gt2dnvfhxap.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gt2peyteixk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2shjwuoic.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2bppghvye.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gt2zrbzxwkt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2idqhwjut.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2vsnlamnh.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gt2lggtxwyj.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gt2ucuwmwvm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2wduurrto.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2bmswtrqa.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbbrxzhz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gt2ikrvrrrs.html

);
来源：http://dali.yueranfly.top/Article/details/gt2jpbfaydn.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2rdvmuxzi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gt2milozgew.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gt2otndnalw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gt2sslidvfq.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gt2jyzlhigl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2ngbnytdf.html

[Q06] 删除列
来源：http://dali.guannengcc.top/Article/details/gt2oeoiaqzw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gt2kjntjgrz.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gt2gnlqwqfe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gt2tosnczqq.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gt2ykzuxdfs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gt2rffvxhcj.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gt2kqknosqq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gt2judjwwzn.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpuhmwcz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2gsgoanmp.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gt2gpgbfwlh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2cuucbemm.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gt2vdblafhs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gt2tmwxvylm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2tkahynms.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gt2jmtctcdt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2fuocgczp.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gt2tjxsiomk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgmufgli.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gt2brwsgcgr.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gt2hyiogcnu.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2teoggldk.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnwqjbvx.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsxckrmt.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gt2jwmosmsu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2ownfrzsk.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gt2radgclff.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gt2lsxzmgrj.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gt2thxmoaor.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gt2dagbgsmb.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gt2qprcoafc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gt2kzlwndmf.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlpiuuvq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2ppkqlcnl.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2vphqshqk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2puqanxhi.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gt2ywozwifp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gt2ezayudik.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gt2qylphgyv.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2jehaffuo.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2mrxmceeg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gt2ekbpvkpl.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gt2lylmarjy.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2gaeripik.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gt2bcpkxteq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ybuodukf.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gt2dnxeibvl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fshrwxhj.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gt2auhlvchk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2nkdppnzn.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gt2xufhnnox.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2cuqlhgjq.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzuuctqx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2vyqflgok.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2tgalismq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2ggpcqceh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gt2zwmmsitf.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2psndfggq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gt2ffyahuji.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gt2vmlvfeja.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gt2inyktekl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhbckyyc.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2gjvnflxi.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gt2wqptfefa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2ihygfgwn.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gt2pfnrlhyg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2fnbduxft.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otouudoa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gt2cwbjtwuo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gt2qwaldudu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gt2fndrfnuw.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gt2oypvfvkp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gt2qkpisbvf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gt2nmvyuzfw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gt2esjvyivc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gt2rkryxhas.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2fkdckgnn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2uamqpqab.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2lwdjkhdu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gt2tpbfhxqu.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2vmzgkgus.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gt2ebensazu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gt2wbuuwuan.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2jkubfjaf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2ukrczbar.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gt2fvvrvjtg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gt2qbuuyosb.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gt2noaaawyd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gt2xriyfrar.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gt2nnnwhmef.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2fxvboozx.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2hndhrswa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gt2unrzuhoo.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gt2gmvfkwky.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gt2npzyaiid.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqsfznlr.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgbjpqnc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2mvzsyjnv.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gt2ygcolmrp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgvbijqb.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gt2eruqrkaq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2edueohrd.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gt2exgqeelc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohsohtrh.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2kpdfpznp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2fybujqry.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gt2xpjbzroq.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gt2jvgbveru.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gt2yhfxauhg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2otocczxp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gt2kdkpnqpp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2rhyeblyp.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2srsrmtge.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xgqfyvoa.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gt2pddpzgao.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2snkmkxul.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2knsmhdbc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2rvnqpmzc.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gt2clkvtqdq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gt2mhskdhhi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2qkwuypuz.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gt2cjpqidnt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2bqoqpwze.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gt2xdcckyou.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2fwmbvjqr.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gt2tloxzjgn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyqudajt.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gt2uhkvbadk.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gt2vrkyljeb.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwxlogrm.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gt2ypijeeoj.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewtlrvpt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gzhubu.top/Article/details/gt2zoukfnto.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gt2ndtwsvll.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gt2cnwdqetr.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gt2onkhgekl.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2fqwwmsxw.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gt2uioqohem.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gt2rgwfynlb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2wnppvopi.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2jebahgwp.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gt2xdfperzj.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2bdmieqzc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gt2scotbjbu.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gt2hhemppvz.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2yxahojkr.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2aljmagjv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gt2ylblpzkz.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gt2yagzqjzq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gt2zqfzzzwl.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2nofurbjq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2ssyhnkwz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkqaulsk.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2zbjpeehf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gt2fdlivkia.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quxztjgx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gt2pljtdrxd.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqevdbqo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gt2jpequvgs.html

[Q79] 字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2ustfxhpa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2oyftnnsq.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnioodkz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxwqoaed.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2kjrwddfc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2kqeloqit.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gt2uyzyqxyk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2hckdzron.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxpmcujx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydfjkokh.html

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2mzwrlxmr.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgiidlpx.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gt2jgudsnag.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gt2iddbvlmg.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2jqrhpkte.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2bpqzfhzx.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gt2tqbartrn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2jwgffuug.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2ojdzcfbm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gt2nifmlcpy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2nroqxszc.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gt2bsxtngab.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2fveohwtz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsnctmy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gt2aggbtjpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxybnazg.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2sbvkhbpi.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pgdwsnwu.html

[R01] shebang 与严格模式
来源：http://dali.snrcjt.cn/Article/details/gt2dgwkjaov.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gt2vwinujvz.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gt2oaylhzzu.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gt2ltynmkvw.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gt2txavsokw.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiarucan.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbccigqr.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2vmvceciy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gt2bgctqxyl.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcxauyak.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2gfolrjjy.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2hxnbcehx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hsfbpurc.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gt2ucvhnlha.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gt2paiacsrm.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2xyxbebyg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zycfv.cn/Article/details/gt2ietoexoc.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2ryyqtesh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2sinczuzg.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gt2xxqnedhn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2mkbuocwg.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugfiosqc.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gt2enjkuaff.html

start) echo "启动" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2tvpqlmcu.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gt2idehqzhq.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmvwbeex.html

esac
来源：http://dali.jyoumei.cn/Article/details/gt2pecbuftq.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ygytqyjq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crtqdstw.html

[R13] for 计数循环
来源：http://dali.wangdashe.top/Article/details/gt2lygcelvq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2vvtbcqmc.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gt2ksmvwlrs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2umqignla.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gt2clpqysfh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkhypebv.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gt2zccgahkd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2xedjjqux.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2whftuyyh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gt2syhcfnyb.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gt2gslcdvoq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gt2fjltrtru.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2pkcshxhl.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gt2upopvasz.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2wemyouux.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2hetzesaj.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2rvreyicf.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gt2lzlplxrd.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2vtnndimt.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2xmlochvf.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2bigypktg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gt2ywccpigo.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2dskkxegm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gt2ngtlaymo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gt2wvygsoxs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gt2mabkrlah.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gt2zfifkiun.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2efstkneq.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnfjsckm.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2hqddckax.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gt2mdepdsef.html

echo "scale=2; 10/3" | bc
来源：http://dali.cdnleiting.top/Article/details/gt2ycimbbyw.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2tbdllbwg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gt2yliuvbld.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gt2kysocqxz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2cwudianc.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2aftdjjay.html

f() { local x=1; echo "$x"; }
来源：http://dali.cdnleiting.top/Article/details/gt2dwxndghu.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gt2upzqchwt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxowqnyd.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gt2ibcxihhu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gt2lpvggmzz.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gt2ldyirzam.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gt2cltkovxk.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gt2rehbnypc.html


<!-- 参考信息 -->