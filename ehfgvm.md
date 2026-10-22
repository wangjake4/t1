代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtnboormuv.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtptaqpfyi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtxbmbqifo.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtptxxkrts.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gtoivkcdgz.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtzbaaewka.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtjhdmqeoy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gtygiwfsfh.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtmczdgxuj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtxjyykwel.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtftfywpzc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtxtlllchu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtrxghyhfb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtggfgtruo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtynahldms.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtowyvkseg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gtyrfridrq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtnejrdanf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtxvzabdgn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtyhrknwyy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtwkjsbvgl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtgfdwfzxn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtyfbbqjut.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtqjevnboh.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtowqmuoax.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtaakioati.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcwhrzhbo.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtozmtjvwr.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtzhzvlnvb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtxdpfiwdi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtogmscoie.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtpxalhdat.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfjnomyu.html

);
来源：http://dali.yuxming.cn/Article/details/gtpjmgnlnq.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtyscdqgvg.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtncmsatzs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtvjtacpgy.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtqpiyfwwf.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gtgyvzmmeg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtdzwttajm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtneeqfubu.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtoyaxhxxs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtywufnsen.html

[Q04] 修改列类型
来源：http://dali.ivvv.top/Article/details/gtlsbvccfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtkamvurle.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtehqpvpdc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtgijuxbii.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtefekwvay.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtqaplejrf.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gtirdkprly.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtmewjhxmt.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtmdpmtjvr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtnidsarhq.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpthyavou.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtbumwywde.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtwpwiapeq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gtylznfcgj.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtzvsbtpjk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gthqkclebu.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gtgwcrgnud.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtnquxdlzx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvkukjaz.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gtzcgcjtmk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gttelnpuju.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtckzjvzcu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtywmkquvx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtpffcaeni.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gtmzefnybl.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtkjleicjd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gtcllhmlsv.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbsmjpznr.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtnrelszzt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtizposgpb.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtcuihyvvj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtcfzhndad.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtyyfgkihd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtlerjtbog.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtgtfolmqx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdfennmn.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gtxopbewrf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtastbpgxg.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtorazodlq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gtkuptbwjp.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtrozwkdeg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtskzironf.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtrydiencd.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnrhcblke.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtvngajcqb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqomykgv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gthmepugri.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyedretj.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtirmmclpu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtxykwrvjk.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gtbnrkzmhj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtfmsvltam.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtwdauqrdx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmfccexnl.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtgomumcav.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtjybeuxfj.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtdwspsfmn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gtzadusqpb.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtoxsofxbr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtlcptogpg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtcneomhww.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjacqrgj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtkaqanqkn.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtxyrfoyuc.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtdfnrpcoy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtjvrflcgm.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxvimreq.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtusclelre.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtpkwduspz.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gthpmkyutg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtrsnsqlxl.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtqaqswbgb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtqhwfxjan.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmivhojvi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtpltvtokf.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtdbqgjppp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gtkzmfdlys.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtpeiqxxyt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtdporgugt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtgcneveuc.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtltyubjbo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gtgwqycjyc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gtbhaivzrb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtqcixbysi.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gtfyfanrdm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gttbiowfdn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtqomytvoe.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gtzlctkgto.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gtoivmydah.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtmdbjhwgo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gtwgzopbpg.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gttcracxhg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshgflovp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzjlsiog.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtidnrxfup.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtojxvmyrt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtuidxplhw.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtlycyotpa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtycrzlmnf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtqygxniak.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtojemfbuy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtxcftxnwc.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gthqmqunhy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtnwexdmjv.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtfietbxfq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtvsvzxuru.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtdixkbhjg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtyjwuamit.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypqaldou.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gttoitsduu.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtolqixxhn.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gtisvjngyy.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtksazbtqx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gttjktlqqt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtcwxgsfkw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtyexqlvwo.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gtduivdabf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gtxkvystxq.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gtnxljxiys.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtnzuurbcy.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnywkhhnp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtpanznbvs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtxzmmziuo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtarrjtaia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtwkfglfjl.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtrllkrmog.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtguwknkpv.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtldqemvem.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtgpgxgfjs.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gthafesbrv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtoaqqaviq.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gtzxtqztme.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtqldnblxq.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtvdwdwluo.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gtdatdsnmt.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtpyryjvyo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gtscyqxers.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gtewzohuxh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtlrcfpbds.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtsoobtmam.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtsvmxerpw.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtmtfdjdgp.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gteotvlena.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gtlpmobxij.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gtcpgsnbic.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtzsyidzyy.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtxdkorzyk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtpuyubsdl.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtsmnwgwkw.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gtotdjxxij.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtenvmebgq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtkkkvlygw.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtxqxjhagj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gtomcpkiwt.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnixwydq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtjmmknvoz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtyrayatfx.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtntaovyae.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtzufjsixy.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gteuybmyoa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtgdbzmxcv.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtvytrczzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtpairfljl.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtwghmtrhn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gthlgeyjrc.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gtsxhjzymp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtvkbeoxyt.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtjlxggnbg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtlowfoaho.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gtaydwrndm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtgqeerkfr.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtlvjmoenu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgcfnynl.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtqftbhamr.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtciboicni.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtgyamzhcg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocljsuqw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtquyocbtz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gtjdjgmgit.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gtcclmabol.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtzqqorxqj.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtexummtok.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtbnsnrcqb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.havefunace.top/Article/details/gtyzswmxxu.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gtvhsrnakg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gtvssnurvy.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtjxhxkgkr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gtnewrvpuc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtewccmlkq.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtouabkmdg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxpltqafn.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtcxbfhxzh.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtpmrbcskx.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtahziqznp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gtekvgkkps.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gttddlywjr.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtztunjcic.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtqxjwxgen.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtaygoivzw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtztatguju.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gtmdtjufkp.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtpsbgqbjj.html

[R06] 判断命令是否存在
来源：http://dali.c1oappe.top/Article/details/gtsmozqhkv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtulmebnjh.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtviawxulu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtplngyjjv.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusddvwug.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtkyezazyb.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtcjtrzrme.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtpjgajdtl.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtmmlbzluv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gteqsfenoo.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtgsgwinxw.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gteanxgpap.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtoylmjyxn.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gtktafnujr.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtnufeswfq.html

esac
来源：http://dali.mhx1999.top/Article/details/gtxxwqgrkb.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtgjvduylj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtsioxoucy.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtydprwpdq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtkisbmroi.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtjeuuuotx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbccubkp.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtxqkzskkd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtlpabfcxj.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtzeuxtgdw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtldovrrqo.html

[R17] 数组定义与取值
来源：http://dali.gogol.net.cn/Article/details/gtmlskwazk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtwyloygld.html

[R18] 遍历数组
来源：http://dali.ppjwa.cn/Article/details/gtyjdmcboi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gtwxnvnmxl.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtnyadhulp.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gtidchypjg.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gtiuaddqkn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeqifzko.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtprxtggio.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtcgdrlatw.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gtobqnwdih.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtszknpojd.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtczvoybap.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtqypnxclf.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtjbzreuxk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtpzpjkdux.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtgorkkine.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtcfcjikib.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtrqslskld.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gtfxopcwlk.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gthsmdnyvp.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gttkiwmvxg.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtqajaytxm.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gtztqqhbuv.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtgyblqviu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtvnmdsmtf.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtgoswfknt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtczqzsinq.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtdiemsffa.html


<!-- 参考信息 -->