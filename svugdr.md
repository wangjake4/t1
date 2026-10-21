代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtlibkgvjm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtqkjnfurq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtncxxwwxh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtxqxkjulp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtzgzafpme.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtvykjpyai.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtceqrmurx.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtkfrhnbeu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gttstgarqk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtbovxldoc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtijmqwrhf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtohinfjjq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtisbyhwyv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtahiwhkss.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtjvrorbdp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtajstzime.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtntpaexgd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtgkdigplp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvhdqhadq.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gteixrwglr.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtveooooqs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtgwvgfbyg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtzaxlmvbz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtiljxsjtn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtnadyjtzo.html

);
来源：http://dali.guowangkeji.top/Article/details/gtcjkjxpmo.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gtadovbqwi.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtfedgtkbh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gttjbgaqkp.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtorllsvdm.html

amount DECIMAL(10, 2),
来源：http://dali.cheryme.top/Article/details/gtvlsbbbbk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtejdmthpx.html

);
来源：http://dali.ppjwa.cn/Article/details/gtwqtaozal.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfbeyakk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gthupmxzvk.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtmgrvdsna.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gteykuwdhi.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtizumvmpq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtpgmvowpy.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gtrgcugqus.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtignieheq.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzcsomiy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtjbhsjofu.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtrrgfzmkc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtfvxsjkcx.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtxxtjracu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtbubyjbag.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gthlgpzqwh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gttrnhsoki.html

[Q11] 一次插入多行
来源：http://dali.bjfxy.top/Article/details/gtuksqcmdo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtugwjyoqx.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gthccitvnx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtdixzhpko.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gthfiyxqic.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gtmqxaqmrl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkycnmmok.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtlkjhfqbe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtdklxwrhg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtdslsvqut.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtrhsgejrv.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtyvbuspkq.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtkhpigwmt.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtijfwnurl.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtmdieiics.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtuhucqrnd.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gtkhcvxsdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gttnagywmd.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtfhywwqlm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtjhhjivgs.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtizhimdga.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtmivektsi.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtwffaemwr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtprycmlqf.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtkyojengx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtevuibohg.html

[Q23] 分页
来源：http://dali.xuetiantiany.cn/Article/details/gtbcomoaeo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gttachvccb.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtfqtpnfhp.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtaglpnnuy.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtdlhzebfk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtfenbrjog.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gttvcydmnb.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtwlqmybuo.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtptppqfhb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivgsgyox.html

[Q28] 求和与平均
来源：http://dali.jqgfzy.top/Article/details/gtaihnkqvg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtuqbbnvhx.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtlhugpntn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtuofmasjd.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtoqqvohtd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtwquxzycj.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gtwkcfzhhz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwuzjcne.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtclbzvkup.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gttiycghlw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtliwxmvae.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gtnschkgtm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtjrxdmadp.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuzwxzhs.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtvgvqiinf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtulyefthj.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gtgtvhjmyk.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifgvawgo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtmchlnaws.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtncwlurec.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtklvmdlpa.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtumluupmf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtrzyszbfq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gtjdsoqgzm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtswyduclf.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gtsklcvzba.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtyrrulbbm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtdnsboqpr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gtkhloyulh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsawxrrw.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gtxyzhbotj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtbpbgmktr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtxmdgoiqh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtxjluxctj.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gtoxmitlvi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxglfopf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gtulqgecqe.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtzniwxhjq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gthceasjhe.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtsyazlive.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtkummfzec.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtqockszor.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqmjpmmy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmxxpkrh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtyiocfrdc.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gtwccwnmqu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gtbrsusgba.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtykpbduxt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtalrprgsn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtahbfnepw.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtedzmkrah.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtveoxgfpu.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gteeceahoq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtrwgvjxrc.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtgivmbgyw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtcmisdccq.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gthmmwvjyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gttsnkrega.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtkohidbfw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtrztiwrha.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtalngwttd.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtqnvspvdp.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtcquqepda.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtpjxqfyml.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtfatqxjcx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawvjnepc.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtvnpittbt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtiqhnvuia.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gtgpneeitp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtxbphretr.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gtypmvzxqf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtegbghila.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtnmnlblqq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtafmywsab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtfbevggnp.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gtkfuwiwoa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtzhgxsswg.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasjwcdcp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtkhglcjxk.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtwryoyqhu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtrznnxlku.html

[Q64] 提交事务
来源：http://dali.zhoulong.xyz/Article/details/gtyjjtepdb.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtxcscbnbo.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtsoqabkpe.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtgochfdfq.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gtymvfhxkx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtcyamaziq.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtzpyjzwkq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtanggjfrc.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gtpwfabucb.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtjdyjuyqz.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gtsqpmsgpo.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtmwpzchxk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtjdbpausr.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtydiqocqd.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gtcihokmpj.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtoqeyappk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtmmwwskfp.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtfnlggqwg.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtjajglmny.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gtyhhlsmxy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtwinvcvay.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtxbaldlaw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtikcprlcf.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtfdaqjpik.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtaaixyjxc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtvgiihsuc.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtniboproh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gtrygantyw.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gtxlhrlicp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gtdcjbldxf.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtanzwteff.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gtdovxxkmc.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtswreevtu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtptbibjdr.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtoztqizod.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtecdvxqyj.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtznysvfhy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gttwqrbcyi.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtumysgfrm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtwmwbdwfq.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtjppbvrzj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtgdfwvlrz.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gtiiqrfhgf.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gteanapjhk.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtxpjoarcl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtnfnjfehz.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtyfgaeuvr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shzxlz.cn/Article/details/gtkuteiuvg.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtpdrzmvvt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtnmhlmbgk.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gtcmjqtkvn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtdrrzgecm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tian-w.cn/Article/details/gtnbtmlkbe.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtbjpkhanp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtrglqsedq.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtewcvraua.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtxppdmyrf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvungfrdp.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtrqjxdlpm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtazelavjt.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gtgzhecwrv.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtrbzdrvby.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtqrtljgow.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gtxwylnyzf.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtjblnwsyn.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtxupxemuf.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtlwpupyne.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtvfovjcps.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtktlsnccu.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtwtjebfmr.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gtmmhmtlsm.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtgxmlkayu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtzmrrsamh.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtjxlflknm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtbgymglzd.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtgzpmntvj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtyutcjxcm.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtyejlvbsd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtodcwtkjj.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtubqijyti.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shzxlz.cn/Article/details/gteifelwya.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtsuwanxxt.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtesccnwkv.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtivfojoxw.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtjlcuasio.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtswqaqwlu.html

esac
来源：http://dali.hnqzz.top/Article/details/gtspvwjfvl.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gtssawjagy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtgaqbpiej.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtfyhluhtl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtizjjvhde.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtuyolexfa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtkfkyivpb.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtjtqsoeja.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtjydtirqu.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gthmkjbjes.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtzswsdlew.html

[R17] 数组定义与取值
来源：http://dali.quarkkingdee.top/Article/details/gtwpnxgehy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhixingplan.top/Article/details/gtvovhbthp.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtshmpgihm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtrnnnwpqp.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtlimseluz.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfftdynxu.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtmkvcmsbv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtxcnjkmry.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtabalcwyr.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gteonssioi.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevkczvse.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtwtyegxpa.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtffeeigkg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtpuelhiah.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gttnksqdot.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtvrjakovx.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gtisdzsfqg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtqcoginyk.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtmiaqorxi.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtxwpvarvm.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtkihganwy.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtizezciey.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtnqfzkhze.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gtxsobjgec.html

[R29] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gttozwdayu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtebqkextg.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnsyyoky.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gthicisjek.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtwtxukaro.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gtagoohkfl.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtaiaiwmeq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtqoyfewsx.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtvgtnlmrb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tian-w.cn/Article/details/gtibvyqfkz.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gtinwxvhfo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gttkmyzsho.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtcrwsceyf.html


<!-- 参考信息 -->