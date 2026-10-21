代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtyuedvpjl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtqgwkmrba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gtrvwklwrf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtadgvikyx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gtoqhfhbky.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gtppyvczpe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gtsrxmovlf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gtjqsbrlbo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtysvvgmgy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gtkrhhxupv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtakqetzwr.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtkxofhbbx.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtynlpfhgi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtcjnaxlpz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtggcjrjwd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkfkkwxk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtndelizhm.html

);
来源：http://dali.yonumen.top/Article/details/gtlpuolipn.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gtdgpvrwcr.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtywvrccal.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtzvuxtvqy.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtalykhaqg.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtqaeincfr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gtfmaldhnn.html

);
来源：http://dali.yueranfly.top/Article/details/gtcqvturrc.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorudhago.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtcfrabqcc.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gtnghjplkw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtuwqwmtgp.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gthbjfkapg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtxhtqdrnj.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtyvfdwdsg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gtobtewbkw.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtciciukkb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtaimbhyhb.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtoqnowblc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtbzsafgur.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypzyyfgs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtwznrdmhr.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtrcxzubcq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtnwywuhdm.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtxxrgtmct.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtzazvqajo.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtnxrwmqny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtarqnmxlm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtarclyojq.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtksxelesz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtryapkagq.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtfmzoflaq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtarzafdwx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gtivhlsfid.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtvjphvetw.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrqeptkvs.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtddvjniln.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtjuignesw.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtbsrxkphn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtsnljqvkh.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtsxkbfivm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtdmezsdrw.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gtnvfmukhr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtatmsnley.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gthpgpgsqt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gthetodgmq.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gteppexoyv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtoqlqvaqc.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtpyikukka.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtjgbvijdw.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtibldxrmv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbbrbsae.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtglhaavov.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtorddmiqm.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfxlnyqv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gttozwjazn.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtjffkhzdc.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtdukwpgkm.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gtospcclfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwclhwcah.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtlsudnlyd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtdamegmlq.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtcpscftce.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtacrekkhb.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtpfrgdhew.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gturtzqysm.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gthxoxpdfw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtynsazxay.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtahaxgmnk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtslxlvobe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gtpswtizrp.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtrdypprvx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtrbwdhvbx.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtkvtknkxu.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtuftntutr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtwyxawrre.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gtkqoxtpox.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakaymraf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtlsewuvwx.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gtenpmduxv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtrkugwzvy.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtuilbuovf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtgjjxjcyy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtajaggyrj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtqnuchtal.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtfyrnuqle.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtmhhidiwt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gtsazqnjai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gteiebxkps.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtlifsldzg.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtsnnysakr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gthtrozjsg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtlusvkuyd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gttpeokkee.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtcymxczyw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gtihdgitac.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtufrxrlcu.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gthdkbmiqo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtkijwmkrv.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtqkjnxxdq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtoyliatuv.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gtzibhclxe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtmmspytia.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtbqgdcfbp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtfjphurgy.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtwedcqcts.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtunfxavkg.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtpyciduqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gtvmnwgene.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtqabdfcce.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtlhffnztf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtpgryzqdg.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gtvhextafr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gthlmbgydt.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtybrzheye.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtocjnbnqr.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gteaewzfle.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrrcbqkt.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtvzqjprix.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtbziantxg.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gtcgvldqgt.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtxlkrbjrj.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtmnxojlrl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtyfhwwpjy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gtuvskyfva.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtlgcjylwo.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtivusbbbl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtuiteoblu.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtdgplplci.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtpzxtnfbr.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtdejjhybz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtyldyikay.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtafxgeefj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtjrfygevk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtvozrnmpz.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtlziwdvks.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtsnozudao.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtqsjywzru.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtcdhuxfyg.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtwlzeislz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gtlfaqrsnk.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtretqoilb.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtbgrhhsfh.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gttalvwcds.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtzqvopudg.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuggbzagq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtgnerplwy.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtswqrgexl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtpuyekkck.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gterhwkoga.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gthccajxdq.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtykzwsmgt.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtvqlgunoq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtjaumrfbr.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtelxznuqa.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gtgyetbypu.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtovxcslxl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gthmhbavdb.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtkeujerlb.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtscwycepn.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtdpshfqte.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gtsmelyaxo.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtvmjkyamw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtjsdyptmw.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtousmjajg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtgjlpggig.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtmzbaqwbr.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtuywlyikb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswpqjkvi.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtkqafnyhy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gtsqvbjmuo.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtufwrwjtt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gtbzctrekl.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gthixaeihp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gtgnhpvdpn.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtbywyzbar.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtvjxdjvob.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtwwniaqyl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtwurfezjy.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gtdlegvnzl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtlmgflxve.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtnlydhsuj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzkrubdqk.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gtdslkefcp.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtdvrfntgh.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtkjzkbrlj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtatrlrjdi.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtnrihjuls.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfgcxddt.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtoyewjtdt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtkoynjtcy.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtlnpkmhze.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtpinuyjuz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtuaqlaepf.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gttansnusf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtixomglkx.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gtohfvwzvw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtzpmanmig.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthhlcbsfi.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtstwdcgsm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtozcntcnv.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtyfbncncj.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtebausyif.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtgzlpguij.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtoehmkcsa.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjztwfxz.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtlpydhqrz.html

readonly PI=3.14
来源：http://dali.gogol.net.cn/Article/details/gtpoeomzrh.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtapzubefm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtpwtwqujh.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtakdgupys.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtuczzdohk.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gthrupodjc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtdpbyyczn.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtqmjdttru.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gthwrudtnr.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtemoyuwlf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtrjqtudsq.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtvxlwddem.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtncfuhuhr.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtjrfwyjra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtugwrvrrw.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojudwbwq.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtjippjklh.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtngualdja.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxwgvyed.html

*)     echo "未知命令" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhpanxdn.html

esac
来源：http://dali.tianlin.xyz/Article/details/gttqzqcyzt.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtciicnacm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtvcpudljw.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtrsobeqnn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtnlorucpp.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtagbibpve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtobectbav.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtphgpdrqs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtqkpiwqbs.html

[R16] until 等待条件
来源：http://dali.jinqigufen.top/Article/details/gtkmertmqe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gtszsjiaqe.html

[R17] 数组定义与取值
来源：http://dali.zycfv.cn/Article/details/gtxmocxgfw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtxqfxnbcf.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gtqzkxsuuv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtbvcfhotx.html

[R19] 数组长度
来源：http://dali.daxiang520.top/Article/details/gthkbwsyab.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtjlgjjdko.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtyrdlvaln.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gtkdwswkqv.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgbqmdgm.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtfepnoskm.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtshiasrln.html

echo "${s:0:5}"
来源：http://dali.fzhhl.top/Article/details/gtmucthdlw.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtmnejvodt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cheryme.top/Article/details/gttejcfdya.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtxdvwuwdx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtmrwjamdx.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gtqlofmcgx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtwyiwphcu.html

[R26] 命令替换
来源：http://dali.jqgfzy.top/Article/details/gtmmrbttnr.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gthwlnbnbp.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtwyhfgzts.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtcnhphrci.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtlqgtfwro.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtnpsnnisb.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtqspgicbq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtdvfqzyzu.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtsjoodwei.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtmyvwzvsq.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtsgzjuhze.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtuzhwfsrf.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtflyuslik.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtfwiplwtx.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gteucgrsfh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkayvrcx.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gttgyfaxma.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtqabvcohp.html

[R35] 后台执行并等待
来源：http://dali.nanxuanxn.top/Article/details/gtmdyxrutn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxycjuhfc.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtyyhtvlsj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtqpgivbce.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtitbpgpka.html

files=$(ls -1)
来源：http://dali.redwolf501.top/Article/details/gturmgzbpg.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtkafpodrh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gtncipukbs.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtfbuahygd.html


<!-- 参考信息 -->