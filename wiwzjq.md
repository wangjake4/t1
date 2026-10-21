代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gtjqrlokcc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtjrdexysn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtswfjhbne.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gttvmhwacf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtuuzoosfr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtqellxsds.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gtapnpxbng.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtoudabshr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gttdlvtwlf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gttlthwgxf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtkxchnggf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtorfiugou.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxamnvxpm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtqvaykuot.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvyfdauix.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwdxwpac.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtwmcrrnny.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtpdjicnny.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtwbqfprml.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtpueurnyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkjttuic.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtydoggdyc.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtsorntkaz.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtipzkebdr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtakgndpdd.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtacqvkyzt.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gtiknbpgtx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnytmhkf.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtnuqmvvap.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtuwiixvwi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtvrjdiwmg.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtizjeepcg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gticmwwuko.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtduhdyjvt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtebpssfmv.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtnfaiohsu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gtqnigmlfx.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtqjdbnndp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gtwvhkmkln.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtbmblnsjg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gttyhwpbly.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtbacjquzi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtrhcwwisn.html

[Q10] 插入单行
来源：http://dali.fzhhl.top/Article/details/gtkpgqfvji.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtuwuwddau.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtptkjeqee.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtbcmwgaaq.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtxowhaalo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtcqlhyfaj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtxmlezypk.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gthmnhgusz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtuncxkwtm.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptxywwav.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtuihxziiv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtzhbqqtiy.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtdudzhzbr.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtoiuicpkg.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtoddhbwqp.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtlcqjyprh.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gteyyjewht.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtinoiwljc.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtzzfgkffp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gthzfwdtgg.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtelhwehtw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gteptdiwsj.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtwxnsirwf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqcwalwt.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtwsepshsb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtepmnpdtq.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtvisynanf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtzcvfecff.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtqszvhmvg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtwubesgbv.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtvhxfnwwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtausyltgp.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtmlwlqsnp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtmpnglody.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gtbysuibkl.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtnyouzpkp.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtqbrzdthh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtlylgzlcl.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gtugfknuyi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtikdhwvqt.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtgrzljabr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtlubtyfbf.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtqpkxsakd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtcjcgtkdo.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtokyjrxbu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gthlrahrot.html

[Q32] 分组拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtgursxtdp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtvolkjloc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gtgwtknufw.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtcydxiwdc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gtidtxtazf.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gtgwsogult.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtlijmhlwv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtuaglwlyd.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gtulljtnqe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtwwyynjbn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtxccwzusx.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtdnteigdq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtufqvziyd.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtktekpczk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtfbjoitvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtpesyrqlr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtifobvcbp.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gtmlrlbzul.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtniulmrzh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtnguhubww.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gtbbhesydo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtbgyyypnx.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtdgpbevdj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqgfgvvu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gthyqggqtt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtvebmrxgo.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtessropjd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtbrorzvuw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtldxrvgzx.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtysvbamxh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykflhtbv.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtmaeqvbhz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjdcqkhs.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtdevulqlt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtrjxipivx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsafyvtgr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtqlzrgmii.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtqrokifka.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtvaduesgk.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gtguietaes.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtkhgentvg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtjsowrfyr.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtnpwkussa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtrayzkcar.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtzzxycqhm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtobydpfdm.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtkgcvrclb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckqxhfoq.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtdillrxuy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtsoexwyuf.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtckbgjdbg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtkvvwmkkx.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnwlbbrb.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtfwdzhwfa.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gtaofmauwq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtpxeebefc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtgyfrdsxz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtozkpmmjc.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtfctxcadz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtctdbbhxh.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtdgqedveq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtrtahgxka.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtvllldggs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtqauujfcm.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtajxjyool.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gtkxtzgcss.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtbekptaay.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gthdvovbdv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtzyvbpnud.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtpzaxpzcm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtydhcyiyb.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtuetzwawe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtpmifyakw.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtwnrcaibp.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtkinnjvro.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtdzvwjyox.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gtqeondgnr.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtioxnwnkn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtgdszkozo.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gtiunrhgfe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtsxhzdzyk.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtriyqgjxd.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtbterqfiq.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtgofeaamh.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtnjbpvmki.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtlqfgsywu.html

[Q70] 更新统计信息
来源：http://dali.vqdsnc.cn/Article/details/gtgcnoshjj.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtmmxhnncl.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtninzdajw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqviraas.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtpwbljqmf.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtyqlqebue.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtinibcthv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtgwvnumne.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtpmfgctii.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gteglllpvw.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtatxcixsy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtcipyvpry.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtuivazbdd.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gthkkwolcj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvududigh.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtxayiozyy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtaflkdlph.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtdagceafx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxwjwrxe.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtdfizomnp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtmqvikjlg.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtsaqpfrrp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtfcxpwvmt.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtgzvxvcft.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpsbxstxf.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gttiwjjtdz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtkvancmfl.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtznrezjep.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjrbyfbxz.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtpncmhdzt.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtipsvttmd.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtlnpvweem.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtcfowkoso.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtwpkkuojq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtlhdcrfjp.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtcobzkpqn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtmwoiojoj.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtugwslulh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtaszztect.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwzoozyqq.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gtzwlrvama.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtnpbknhvq.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtgqbrxbjp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gtflnuzvcl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbwzudnfr.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfdsdslp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdpflgdlt.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gtnhzrqgiu.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gthvdrqobt.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtyfdhqome.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gthzhkzpqo.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gtkskvpimv.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtlzlggiuc.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtgmaasrnw.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtmwtrrkek.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtujnjiryh.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gtxsotsasz.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtrkacflsu.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gtnaoehauv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtkhxtxazy.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gtfrcumeai.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gteazykidx.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtgawjnzhv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtdpakbnqp.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtytkmqsjw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtrgibuhxt.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gttfatnooo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtqqctyrky.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtslsevsfy.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtsheltekk.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtrtqekhca.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtdpjnauhk.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtmbmybvvi.html

esac
来源：http://dali.andypj.xyz/Article/details/gthkmolouz.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfravxzah.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtmepeqxsa.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtsxohkhle.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtxecmulks.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtnqrvdcyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtesfwfocj.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtvusoahyt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtzcwhysxi.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtugvrznpa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtspsnkgve.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gtbwuaudbv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtueixmbbn.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtrtnkptkb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtstubgtaj.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtzdvfqbae.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtbptbywdm.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtfuofabia.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gtjiviycxp.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtwmuvcbmu.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtnlwsoggb.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gtjqckhirn.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxokeriev.html

[R23] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtzjnjbjga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gtallenuqj.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtacsoxbfk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtjaexkcov.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gtqitiqxrv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtxxepuzdf.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtraxzockt.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtijpgilop.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtryjywjmw.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gtshojfjvr.html

[R28] 浮点运算
来源：http://dali.cheryme.top/Article/details/gtklxcrhzt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtwhdcafue.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtclcdoiqk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtuclchzvx.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvknkcss.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtxumvncsl.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtqquykjla.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj202588.top/Article/details/gtetrwuiat.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gtsroebmur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtheweeopv.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtbwomyeaz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtrulhgxjz.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gtlmyprnte.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtlsuxczym.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtusstibtm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtrrfzvvgp.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gtjwqeqbjd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtpfdixmru.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtbfxkgexx.html


<!-- 参考信息 -->