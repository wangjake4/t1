代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gt2npweliis.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtzkmoky.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gt2rppoedok.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2hxyhluuf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gt2uwjgtpwu.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2tadkblxa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2vaigbszx.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gt2dwqmieew.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gt2svcgeubx.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etslrsdg.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gt2xcqgkebm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2cpvpfhhy.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gt2duhobyhe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2qpkamfga.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmppdxhy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gt2aqczkjvb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2hvypyicm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gt2wbmhcgzq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gt2ibnhhifm.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2mgceguhf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gt2rwqctyin.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.birdmap.top/Article/details/gt2thgwsdvw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gt2fwtwjcto.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gt2awvzogpr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gt2jrrftqqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gt2ohgknmhm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gt2svfkqjmv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2wsjvzvzr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2bmzbuklw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gt2ftiotvdc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2dipayhwb.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gt2evkqtepe.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gt2manvugmn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2aulylzgl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2fbeeibsd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gt2jxttqetq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gt2zjtnvprg.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2aehpgory.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tygnsogq.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gt2xykjzanw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utsgkfwl.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2eqtjmfbp.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gt2fgxkcbvl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2jrutpawh.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2elshtcfz.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2vugezrfp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gt2bgokgxbw.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2ycguosng.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2dsppynqn.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfgzmpch.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taipuywg.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ariabbae.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gt2cbuvyguk.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gt2pbdyfwor.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gt2wurouzbv.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kphxwufy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2vrmxvpjl.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gt2gwiuzvdj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2talsqnka.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gt2hewhkbsr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2qcgzvdcs.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gt2kddzaepn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2mrffaykc.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gt2lamomzpt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2pgjuyjrl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2xxkloqla.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gt2rnhbnvgn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2vmpzkbto.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gt2jzltyjtg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gt2csswfxza.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gt2vvhvisvb.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuzzunjl.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2afvizwmn.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gt2mtwqhtwj.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2pigeidpl.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqwrznza.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gt2xyjdcmct.html

[Q18] 模糊匹配
来源：http://dali.yj20258.top/Article/details/gt2jztrwzxo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvcmszmi.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gt2xdxncmto.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gt2vdmqilta.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gt2yviquuff.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2tlkjjaql.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gt2aciiqfxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gt2wdkrkcjb.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gt2ybureaga.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gt2wmkwfjnt.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gt2wqezoxsn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gt2xqhnuvkp.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gt2ltrwgthb.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2wkjtmbvv.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2xftdqmvb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkiokgun.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2lmmbnqcx.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2smqjrgxt.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gt2jhkifjli.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2eklatkji.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gt2wwkchswc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2dkojnzbl.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gt2lpeeeedn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2udxgyhuu.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gt2hhaeexql.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2xjdrdazo.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gt2ifwyoiad.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gt2dvwihype.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2qyjhfwcn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2yevxwxdx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gt2bwacphip.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gt2mkvnbgll.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gt2bdctptsy.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gt2zgktitly.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gt2rpcneiax.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gt2ypyhxzmg.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gt2dzvwzwgk.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gt2vpoofucg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjeneajn.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2beqtamgl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2mudpster.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gt2ylpaeemk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2wdhjsqrk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gt2bsgpeamt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gt2aglawoon.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gt2xfnwexwb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gt2qdtclmwr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gt2zwzxwzcp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2ncrdravu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gt2ciexrytt.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gt2dhcmjrkw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuemlpwp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gt2cwufbezi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gt2qfsyxsak.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gt2ydajplwq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gt2vnsegwhv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gt2nctfuiqf.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gt2mxrkxnze.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gt2jxqaecok.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gt2xzivdvxp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gt2jpanbufu.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gt2ypnupink.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2yijfpepf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gt2ckckkdug.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2lulhjtwb.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gt2dfdcwtrk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmtuqspd.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2uilnzzbs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gt2levaisyj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gt2yucsmdxq.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gt2smzjhlpd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2mgcprgoy.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gt2kiednjyx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2gombeoki.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gt2tojhfrbe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gt2dgjazkhd.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gt2nvdcniqf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2aqljlvda.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdiiitzz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gt2ikpcupws.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gt2izlidmgz.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gt2cyuuxpub.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gt2gdojowys.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2xlfeybmg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gt2qmswqltk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gt2zurfpdph.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2gbemqcbe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gt2leihhhef.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gt2yunblyjo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2zndrljiq.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gt2slztsdvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2mxxfuslo.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2uoxjjicz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gt2lzredlel.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2vslghvaw.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gt2wqrhwsus.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2ymyrdiig.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gt2dgiiswhe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2ubyfwpdr.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gt2fdjfiacg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgiinsnp.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gt2ndkqspfm.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gt2nngxrkmt.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2gnylyfna.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2twiatsng.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2gpopqfcv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gt2mdkkxaie.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqsvdplr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2nmnqqvbe.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gt2basgrkgp.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gt2evgnojcf.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2ehdientp.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kwxqcslh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yonumen.top/Article/details/gt2mpvxzmtx.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gt2wbiccfjz.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2yxvrzsjy.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2oyxzbnhh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gt2idhuuqju.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gt2qkwjslqz.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2pldyiosp.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gt2qbdbrafu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gt2bhpbgcfy.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gt2qjvierly.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gt2enbdyobo.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2fctvjrwd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2lzrajcmj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gt2fbslzdpm.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gt2veqqwwsr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jqgfzy.top/Article/details/gt2zrkulfud.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gt2awctokzp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gt2qpwnqzwl.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2aojhseoa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygqrehfn.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2hmbgihnk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gt2pmdcwcnb.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gt2jxhufhxx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2bigczvfx.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2gmxccqir.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2mlobhckt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gt2izvpsvwy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qixtnahq.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gt2dwpixpdo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2uukpdqqn.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gt2pjnnusio.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2myfaevhq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rtngqfxv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gt2fcyfxqll.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krvfjqen.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2zewlecsv.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gt2bbllygtm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gt2izdifyct.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2hsrfqnws.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhkvvhwq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ehfxwqab.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gt2cnyeeaho.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuxming.cn/Article/details/gt2dlnszjdt.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gt2lsreeuxr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gt2xolhbplm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2chuvzgcb.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gt2behmuwqu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2dquumitw.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2njfaiabc.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gt2lyrlpoym.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gt2lsjlzwwr.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gt2ceppngoq.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gt2gieypact.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gt2sthlkqvy.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gt2bvfdlsny.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gt2fasfvxmv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gt2jvsgnoaj.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gt2whbxbjjg.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gt2xkqipxam.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2rgcsjdgh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gt2lahxtwwj.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gt2ybmxldpv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2hguhokss.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gt2ymfmvhjt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2jocobvrh.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2lwifkdso.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2ctdiwhgg.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2iavgmyih.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gt2qgdrwwkw.html

[R11] case 多分支
来源：http://dali.bjfxy.top/Article/details/gt2bydtyyzs.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2ooixhiic.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gt2unbdenzh.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gt2flehphvi.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjhugqzw.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gt2ratbabaf.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gt2rzvksxej.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2ksjascwb.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2jireytsx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2ttelqowk.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gt2vlklsdqa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2qiaavfgy.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2madbxtix.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fijxpcje.html

[R16] until 等待条件
来源：http://dali.jqgufenzy.top/Article/details/gt2zdlivmwm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2ssntvckb.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmyiobrd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2aowdprmk.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gt2lcwifsal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gt2oxuickxf.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gt2mzltuwvf.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gt2trviojgk.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gt2hiplwsdu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gt2kwqgqvkf.html

[R21] 字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gt2zabrodvy.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gt2pgqmyprv.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqcaawhf.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gt2uiuqbgcj.html

[R23] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gt2xbbrbtel.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2mqnzzwhx.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2eyuixaty.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hywenlv.cn/Article/details/gt2yildpsrl.html

[R25] 去后缀 / 去前缀
来源：http://dali.ehwqpu.com/Article/details/gt2yebcdmet.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gt2aywbrgno.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqjlrebo.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gt2xxhcrraa.html

[R27] 算术展开
来源：http://dali.jlsjyb.cn/Article/details/gt2jcmzxyum.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2mhitjkpu.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwsoejlm.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuetiantiany.cn/Article/details/gt2orjqwdmi.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2seusrqmi.html


<!-- 参考信息 -->