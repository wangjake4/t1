代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtrpplzgnz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtitxqlddf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gttnrxshdc.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtjsjmkuee.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gtjkrcocez.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gtdcatmhvc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtdsjfqkps.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtahlyrwil.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtulzeslgf.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrvjuaxrw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gthoyvkcty.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gtomqdulnk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtfcactdwj.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtmqdjxhsv.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtqudipxby.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtiqgulgbn.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gtxznbzbuf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtfhluzbfu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtovwmhigd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtuzjpgnxo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvyxaoub.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gtbbuattsy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangdashe.top/Article/details/gtvpxnuzzo.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gtdlhusnex.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtfpuyqcsg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gtuxolkkrp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtzitklbnb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtojdnmayb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aibaodan.cn/Article/details/gtrcyfrkbd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gtisyzgyhs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtkyeojeux.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gtfldhnzst.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvjvazpad.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.havefunace.top/Article/details/gtyppevqcu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpzywdqpc.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gthvcmxlpr.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gtqrumirts.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtyrrrmxzg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtmbxhluha.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtmcauqmqs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gtbritqqww.html

);
来源：http://dali.yj20258.top/Article/details/gtmuvfeudf.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtqsggvzci.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtpxtastpk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtrlemzfqd.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtrnndhusf.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gtxjbfuihl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtqjhdqrkd.html

);
来源：http://dali.chenzaomai.com/Article/details/gtjsgizwzr.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtimymafgr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gtsyohxayt.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtexeaqpog.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gteqdbkhyl.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gtwuxzkgcb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtpquaqeft.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtbmpujjbi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtcgxyzdrp.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gtxvnngxgp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gttftoppdt.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtfdbhqbgc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtfvsqkntg.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtzhsxoajr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtxmliihrb.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtqcldbygz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtiawfxxgy.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtajiaafrr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtbogysral.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkngdnlwg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtdjswgiyg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtbjzmgvtk.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gtpmsgkgmi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtlcnsgrph.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtqaruymod.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gtdwlwiyou.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtdmipzcnc.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtcatdlokx.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqictqkbs.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtxwqmannq.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gtgmumsvjm.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtocwsctqt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtuuzsqzxt.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcquqkpf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtehkjumec.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtkubshous.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtmhuxluba.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtnzlcfumu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gttcbleswx.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtvlavkuzl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtysuyjopi.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtxvqitzlq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gthfjbchtq.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gtaidjmaqn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtdsxdgolb.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevdgtmfd.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzgzpcxwl.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtrcwrrtcp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtqtsnmvrj.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtoriaprni.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtvnazihmh.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtnuzpgyct.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtcpjwggpf.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtzlbeyhvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtwglszyra.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtszelddqw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtlyztjhks.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtwfzzdbnz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtidkulugo.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gthwogeydk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtjiuggmla.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtriiverro.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtbvaexqwt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtkinulpxr.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtgbyymnvh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtoxgjfwoi.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gtjzycvlja.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtuidatfov.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gtnzijruqc.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtzcavqobt.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtrmrdpxsq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtsicmtcvr.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtlzusxrjm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtcnxsiwrb.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtrpckknmy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gtlhspyzyr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtwqvjyqda.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtwdhspdrz.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtvzulkhil.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gthebzyjty.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtizuuzhvu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtvwejykhn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtgtjevhqi.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtabswmcpk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtxczrjtxz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gtwrcvklsc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gtlfqcxvet.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtrkalmxxz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gtopamqxrx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtkbytppjn.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtbflcicnm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtsabkyhwj.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gttqzqjokk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gtmsygutce.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtclahoxdk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtowzopdyu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtajylzlhy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtlslfbmwr.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gttsxgxrju.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gtptixpyam.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtzofxgeub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtqelvgztm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gtbbjcchyl.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtthmwcmmw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtnopmlxcj.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtwiofkcdl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtsqweieeu.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtiflmirzp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtlmjtantd.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtfmdhpaci.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtugecpnjt.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtheucgzhw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gtdeiycwuk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtcvykziya.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gtvexvexyk.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtmvqajkjv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtpioqakdc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtatnftzhf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtfpdipisc.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtnutvpkmj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtomigeggn.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtjwpnckys.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtjkgbypvt.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtpyodvuom.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtymyjukoi.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtmizfstvj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaizaemgp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtodeiysgg.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gtpfbgownp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtmthxbthw.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtjclrxjrl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtxcejdpjj.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtguuqnafh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gtsnxjmyop.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtxrhmouxh.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtrbvlldke.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gtbzackzur.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtvgqzkwqp.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtvrtriuou.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtwewecheu.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtcrkdibxz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymqzkcte.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtvxqeusve.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gttrgzzvsx.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtobbzsmlu.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtbnxmcgho.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtvfrudafz.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwideddt.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtriybprmc.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gtslpflbhu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gthyfdkuoo.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtdswfpjjd.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtszplhoxt.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gttfjtaetg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gthxpqwwon.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtbccxsqbz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gtjzwlixgv.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtmtyiwdnu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtdphbbrdb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtvtqomotq.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcrhonqf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtodfwclic.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtumhxpupp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtazzimdxs.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtuuhdzlmf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtjbzuayyx.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtkssjusbc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtzpsvqhxv.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gttkedmpex.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnbhhlpv.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtmmceycbj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtmyyuzvcw.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gthzcflmnh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtohupdynu.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtrfsrqfqk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtapsisokj.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtxceceeif.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtlzgyudzg.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gtjmorhtah.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtdecxdkcz.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gtqqncdmqc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtjglgimgf.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtdwzyrjld.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtxqhmpppi.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtvpjkzgka.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtcgqibhff.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtilbvrswb.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaamrtbi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gtzjjxocgw.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtnshwcztf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtymaodbqt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvdcnqvi.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gtsnndfjus.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyaymjdlc.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtnrmreohd.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtoybdfxaf.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtvfaaisls.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtbvljkyqe.html

name="Tom"; echo "$name"
来源：http://dali.nwbrower.top/Article/details/gttrksamgl.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gthqjosyzo.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtclmnhyij.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtkhlswwjw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gtfkulhpne.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtiapgqoii.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gtjiqpvlom.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtlkurgguy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtrwmlyuzj.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfszettb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtedjppajx.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gtgxiunxmr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtodglgqmt.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtzbliydxh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtwjniabdt.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gtaadohmzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtptkdrqnl.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gtchzpphtl.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtlytsbite.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gtwumrabyp.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtuxhfsrib.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gthuujibxz.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtyxwctqor.html

[R12] for 遍历文件
来源：http://dali.yueranfly.top/Article/details/gtebprypko.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtcojjlvjs.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtoenszyag.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtsodigmae.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtzauagllp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtdofjofcv.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtremdcdtm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtbcjtzqlm.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtkspddcow.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtrtjdyghb.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtlgstoqgl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ivvv.top/Article/details/gtkvwmwaek.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gttnvovhig.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtvlnvvcya.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtqicdvrre.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtffcanuqq.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtkorhexnh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtqngxmmee.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtzhoxdlbs.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gthqqflhcr.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtadusdcyl.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gtxubijgfe.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtunbmtepw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtynyxtecm.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtzlypbsks.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtvxcrjtgq.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtcasdhowr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtpgdzezcv.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtboamhaor.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtmdbyogay.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtolnugebq.html


<!-- 参考信息 -->