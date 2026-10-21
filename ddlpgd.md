代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtbxuruuao.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtiunfcxau.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtklnhxtzr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gtzupuyjyl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtpdwdhrjl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtcbnslfkc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gttwpgnzqx.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtqkjhisbm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtlhyjurxr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gttpwzemyf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gtlhavvljv.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtaabzjhdv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtjokzfcrc.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtvbkcqecx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtleeuwskf.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtffyirolq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtrkkyjahj.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtgvbhcogg.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gthevteowb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtqmvxolmj.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gtycibomei.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtlgumlmgd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtgjtygnus.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gtufootksa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gtwxglspjd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtkublkwda.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtbcwfxijk.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtiuqzjmbl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtxpxlpgzz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gttwrdpusz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtvbwjtjik.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtpttciisj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gtynikrtvc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtqqnyshhw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtqowvdjnl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtngdmvdsh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthwexdvef.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gtqmxgznfh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthsfccpbd.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtfugdowvq.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtbihmhimd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtapnagody.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtqzpnfuku.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtcfkzawxk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtsxijfhtc.html

);
来源：http://dali.meibo888.top/Article/details/gtwuyovkeu.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtfazzvxfy.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtcyfgmcje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtziexkjiv.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtwutmxmwj.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtreriugsw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gtkbyxlyuk.html

);
来源：http://dali.jiagoushi.top/Article/details/gtotuvupmz.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtfvsgxibh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtvaoefxhv.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtfyebxhsz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtqlooxzxp.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtrxcnjjnz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gtszaanpwu.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtojhfaemy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gtdwuxrrqg.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gtxzseqteg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtfoupgjjz.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gtojdoetnj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtnnfvvovt.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gtgxzsfrdb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthislsiie.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtpxendwlj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtcwktqnpw.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtsdvnlksj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gtqzscjoqa.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoaggwmt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtlhpmixra.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gthrpmgfid.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtdlhndqkr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtszbbxotq.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtthiisshe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtmbtysuit.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtstqhguox.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtbcqcdccb.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtmjvlrnaa.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtxjbzalel.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtyjrutahh.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtbvcikqhl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtwjtbyrnd.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtsfrwrwnh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtpzkfmgip.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtpcucdzhq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtqsijyajs.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtbceszykf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtrrdauhto.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtesmkmsgl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtzqucuphw.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtbkeotnze.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtjdfgucmq.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gtsbekqdvf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtedjnoayo.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gthgozftrj.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpbizvjc.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gttrlxdbvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtmeeemjxz.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtmfetahmn.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtiqsbxyvn.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtcunwlpuf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrtlbalj.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtrbthoauj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtxwqafamg.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtoemmhldm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gtsicqwxcs.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtpbpcgthb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtzdhnenyd.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gtjwfdsrbm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtoweoooam.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gtndalyixr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtozwrscuq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtvftbgymc.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtihmbkidz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtnrjqhgeg.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtjtpbozrn.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtpbnltmdi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gtxxubvfqy.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtbrecwmai.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtjzmvsbdr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtpjgxjeqx.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtkkwgtofs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtzzqiunxp.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtwunjjqxa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gtxzwmklcz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gthkaiggll.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtzsvnuwbw.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtsebitfnh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtubgkwnrc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtsckjdohg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtjjpgczsc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtlrkbdhlv.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gtcknqgpwx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtxmwkmvcx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gtbcwtedym.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gthnmqxoei.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtqxnxmrgi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtxfbkgcxx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtyytlryvo.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtgablrisp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtvnjekhlr.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtmzlulilt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gthyzkruye.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtjwqpfqqt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtzohomiou.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gtzghrpjei.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtyidvzowi.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtmligixei.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqowahkmo.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gtxhlvmywr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtvgklesgf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxhtumuo.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtsavfziio.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtauyngjvw.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtbkbwyrqg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtlswylcbt.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gtcsolbeqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtitgncdvu.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gthhsvvvky.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtbgrhilrq.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtcvgcrwou.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtcqbumets.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gttxbdbmjd.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtqgklpcmw.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtkgpirrrq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtokelykzs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtwjzqskzs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gtjgegjhre.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gtbrkbffsk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtjdxatost.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtrpsqeywn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtkffpggsg.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtvyfgozqt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtkzhgzark.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtbepvsrws.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtsnczpooh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtuutegjev.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtnhyawwad.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gttneyhiqb.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtakcqypcr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gttpuftteq.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtmjiczoxy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gthvdzwgof.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtfpfehzup.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjdymiqg.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gtfetmdzgm.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gteoejpnxs.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtogsktfir.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtxieylfbs.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtaqffrbjj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtvbifvcve.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtpdorsfps.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtepzzqeuo.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtilxjvhkv.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gthqbbpeow.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtfrgpjedo.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gtmyrlxnrw.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtesrvietz.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gtgotshhnf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gttirwweqn.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtfbxlycxc.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gtkibxxhmx.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtwwvehhsu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gthpixaopc.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtsckzeodr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gtzjexynlq.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtoadpacpg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtwbbmklyg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtaonddsbt.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtfqyaldag.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtfxopriyf.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtvymudemf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gtgkcmztlc.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtmzsqifdr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtucisqjdz.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtwambfiaj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gtqqdojxok.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtphyixbhm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtdfsinekm.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gturyyngzh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtscdcjlzd.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozouwlmp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtegjtnkea.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtnbuibczm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtwcojusgj.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtpdghlhhv.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtiyvbgjga.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtqzvylioh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtmoxlbide.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtfxvsaqkk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtrjyxagnt.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtfzipdyar.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtppskubhc.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gtuoitafnr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gtjiaygngr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtpqtxktou.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtijfakebr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtulekmyde.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtkeiecylw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtwcjfwvlp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtuxmokrqk.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtraxrgnnv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoxgykffy.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtybfogqil.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtqajclnnz.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtyrdplxxw.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gtscuurrtv.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtatrgnyyd.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gterttitac.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gtwjwdimwq.html

[R04] 位置参数
来源：http://dali.cheryme.top/Article/details/gtaokyuepc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtrhuqopmm.html

[R05] 参数默认值
来源：http://dali.smart0.xyz/Article/details/gtxzekddsi.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtqpyudfyj.html

[R06] 判断命令是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtviisduqh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtifcwzsja.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gtjrrirqta.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtojeenxmw.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtpkybmnjt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sysykeji.top/Article/details/gtygqbazdg.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtebkibwbq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gthyksqzxg.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtxjdirrew.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenlongwang.top/Article/details/gtopmxflnh.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtjgjybpfd.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtowrgomkz.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtwjebzxur.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtfvjnqczf.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtoncbyhao.html

esac
来源：http://dali.tanke756.top/Article/details/gtklkelrqh.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtsqxpjouo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gthxcpedgu.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzshpqucq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gteyqjtoez.html

[R14] C 风格 for
来源：http://dali.daria6918.cn/Article/details/gtkvbhozma.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtnilivuyf.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gthrfyrjmh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gogol.net.cn/Article/details/gtvodosnob.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gttpfgjzyi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtdqcvyzot.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtzqsxliat.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtuekyafmc.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtnyaczylu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtfrphxdzf.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtgclhuvze.html

echo "${#arr[@]}"
来源：http://dali.iojbl.cn/Article/details/gtlabaomib.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtzwlwlbom.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtjuqtgitg.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtsyxgxkix.html

echo "${#s}"
来源：http://dali.yanxiufei.cn/Article/details/gthspqjqnp.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtdmtjxnqt.html

echo "${s:0:5}"
来源：http://dali.jyoumei.cn/Article/details/gtezomeeuz.html

[R23] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtauabkkwg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtodbifhvt.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtxszfjrxy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gtjxupinqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtxtahjzfl.html


<!-- 参考信息 -->