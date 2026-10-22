代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtyanpcyvc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtaveikdab.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtngyaptoo.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtrffgrgcx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gtbernfhte.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtdaspcfwd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtmffzqmme.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthfunimgr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtuodezsxa.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtbpkljrei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtoosmrsrp.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtzepnmfxv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtsmlohmmg.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyglijts.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrumofmyz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gteiquofhm.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzrhhgen.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtnmfjefvz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtarcufpmi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtlpugdnyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtogityecf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtzfsmhewe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gthjisgvoi.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtiuwzuccg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gttnleyhlq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gtlpanpalr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtcxgwgcih.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtptlahgvw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gtfecukyyq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtzyaavjch.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gteizcsmyy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtrkwetihd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthwweevce.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtidredzjo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtguzsfgmx.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtcodsxbwk.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtjtvbfqgk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtmcyqrjsq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtxlboardy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtllmwzmxc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtglbwmhse.html

);
来源：http://dali.aizwys.cn/Article/details/gtljuvptuh.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtwjpaegfp.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gthfpeejym.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtcfymknye.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtfldhbclt.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtihdjicdz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gtygfzheec.html

);
来源：http://dali.ybcxt.top/Article/details/gtmqnvgicx.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gttqoltwpi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gttbsqluzr.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtbwspnawu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtkrsoduot.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gthjhlafns.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtdpwsxalf.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtegvpubgb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gtggcvjjzu.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtkbbzqgjg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gtqhsittqi.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtsmlovbui.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtlxyhbqpf.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtscnkxuwq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtvifpqkro.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtgixahpmu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxpgvngc.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gtabvwhsma.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtxpumrzdc.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvebdvwkn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gthmtxwwuk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtvrzmaviu.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtrlbemmrt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtghbslnes.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtwqxogtrf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gtvgjhkcte.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtcmyigsqm.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gthzqllpnu.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gtcikuwoxr.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtepxtqxft.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gteyhmrezw.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gtmbvurrdh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtynpyjfxo.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuwxzvnm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gtordvpqir.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gtsvuxwgeo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gttoxjukam.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gtmvlvmqnr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtpwluzpcf.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtakgbiqgj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtmmagcwda.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtufqdxkwp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtpeiufgom.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrobkuech.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtupwbnrtq.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtesnvbnoc.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtikijkgqg.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gtgltmcicz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtbseuocmy.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtvvqwbykn.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtuyqnyfuc.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gtzdzyxcfk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtgdainqvp.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtkiumxvix.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtxybbbzmu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtzpouqpnd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtcacyxiqb.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtgaaywcwz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtwfmctexr.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtruhpxeco.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtdjevxrmp.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtjwrcggib.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gttmlukffk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtirgogaqq.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtkkzhrsrd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gtijouwpgj.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gtmrobfglr.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gtjhzpzqxu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gtnwauwsrt.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gttxrjbhvj.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtriasmvos.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtlzemifdo.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtjnpruppf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtcxnsbhfe.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtbhryzvnm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtpdtphxqg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtuyyzwjqy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gtdaugamff.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtmyecjbbq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtxaogfrwh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gtbzrujqft.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yongpay.top/Article/details/gtbpiscqje.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gtiqnpuujc.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtscwfrxmg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtrhsxviof.html

JOIN users u ON u.id = o.user_id
来源：http://dali.redwolf501.top/Article/details/gtumvxrboj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtlkhyfdqm.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtyaytqapy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtaieinive.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gttmzazdna.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtjxybbhfw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gtnokbtnwy.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gtcgihbixb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gtjhgmohnp.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtfymcsbls.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtmrixomxg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtvdnonprm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtlgklisww.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gtqzirjmbr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtkykukqkm.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtvfksxnwf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtcaviglna.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtffgdtwpk.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gtuosadduk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtxhggudvp.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gtmdojrafs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtwdhihmbp.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtlrefyzma.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtidctbrsu.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtnqebuhtj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtypojxdxt.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtqwadysnj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtrvoporqn.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtmpxajieg.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtsozadxdf.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gtasigalsk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtnwmsqnap.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtvwxxpcai.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtmekoycsm.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gtrupagbrv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtmylerniz.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtnznvjdnx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtmxtmyhpa.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gtfrurwyvr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtieaddsgg.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtvojyuhlg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtkwmaedlh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtoltqwwgs.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gtlcjecrqa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtgbcjhwmn.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtgtlxyoxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzyzrmhu.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gtzouwgfoq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtzzaoaius.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtlzdshenz.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtmiyiedvd.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtslktwxzl.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtdayagswi.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtittjxkuo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtppjxobaj.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gtpwwlxila.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtstfyoylc.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtgmmcczar.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtyhqqhlni.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gttwtrssji.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gttveguqjt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtdryopcie.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtailihdst.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtzijrsovi.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvjfiwzn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtggbbufck.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtromkoceo.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtlnommknf.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gtiodspbeg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomssgnrr.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtaluwlwng.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtulgmzktb.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtbyyymlgb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtpyoqcnjm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gtustqpfwe.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjbegixm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gttxifupan.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtkraaizjm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gthmroleoy.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtgzafiysy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gtrfehpwuv.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtbiwhxdib.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtbbswfwgl.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtteligxuc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtctoyasps.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtovzkdgai.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtyajrajyz.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gtkavghxkg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtcsxvyemo.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtehhnsneb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtycopiyhm.html

[Q84] 去除首尾空格
来源：http://dali.jqgufenzy.top/Article/details/gttplflfic.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsyozlkg.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gtzhavpnim.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtzqgzyzcr.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gtejlfupkp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtdafyyybq.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gtlqwezzyu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gtardazckt.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtwojuwtfn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gtgjpznlmh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtdnqczujc.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtijfbvssn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtxxhdbjkc.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gtkxnlbwnx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtlwywwetg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbmfdshlz.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gtewfdqzbm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzwskqyim.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtpikxkwpg.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtrooainfk.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtysuinfrv.html

[R02] 变量赋值与使用
来源：http://dali.snrcjt.cn/Article/details/gtaccbrqaf.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtdpzsfvkd.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtppzkzewn.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gttagbuksm.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtplgyyngj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gtkhidqmgi.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtmvcdhzsf.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gteksbfvsc.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtuzqiaokb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtpzhiyvgx.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtoxzdiltu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtotdbvpdz.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtmbasaewf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtkktshaom.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gtldmmcmlb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gtqbelacsx.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtmhencxxy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dashuyun.cn/Article/details/gtsudosken.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtlgzrxlav.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtwyllznru.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gttlvboavk.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtbokpbfiz.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtnvjzlmxd.html

esac
来源：http://dali.bjfxy.top/Article/details/gtqtkjpylh.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtizhfskpr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtvpxbpidl.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtytpoaysg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtqsiicpgu.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gtqengnxrx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtyqtgevyx.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdodeoban.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtytqiqcxf.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gthhwltmug.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtrkmjuuuo.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gthtbjekhe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtyyvzajhx.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gtlxghtupg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hywenlv.cn/Article/details/gtpzzrkiqo.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gturdqwxpq.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtmrxffcjh.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtyiqgxbvi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtiwsdasty.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtfeqfdqhy.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtydufgtqm.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtcdawiefd.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtcgqfzkwt.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtmrqrzdyd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtdhqyppdj.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtrgjehrev.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtjiggwlqy.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtkyttpmbd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtzlsywkmq.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gtaopljmeo.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtibhfshhy.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswxctehb.html


<!-- 参考信息 -->