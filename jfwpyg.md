代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2vrmsodmo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigfzy.top/Article/details/gt2duexhwzv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2nliaoczt.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdopubms.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gt2rrmfczyt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gt2oyoytdlk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gt2noxojcax.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gt2mepuukgc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2ykohwneb.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gt2qgdtusev.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2efzyejjd.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gt2duqyfloa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gt2upopsbtk.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gydrkcbx.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2gutbpujf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gt2zragopvv.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2qkmpfqxh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2saxuuzjo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2vbjnhjne.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gt2baxgazjk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gt2obboxsvf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifyacqek.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gt2kinlkzwx.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gt2cavmygcx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gt2wzrapwwk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2uuuezegn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwdfkua.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2lsgpfjya.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gt2ejjrjini.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gt2maeaatch.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hujysnog.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gt2xcidoman.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkxfesoq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gt2jperbgkh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2wkijkfxg.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gt2ukjuivbm.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gt2xlqhzgvj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2crpfgyqu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpvghnbz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gt2wtavyjam.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gt2eeszodon.html

);
来源：http://dali.yj20258.top/Article/details/gt2ncykwnwv.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gt2gowxumvx.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2szikiusv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2dxwgxzkn.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2qcclguus.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxmbqgec.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzodbfpv.html

);
来源：http://dali.jqgufenzy.top/Article/details/gt2ldlvutfe.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gt2bczrgeli.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2bdwxymdn.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gt2xfrybzyw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2lovreihx.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2wficnjjz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gt2rkjobdmn.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gt2sqcbaaxj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zteajtcz.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gt2vwnbzjny.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gt2wcxrxojm.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2vwetqgfn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2cmlqnqhm.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2eqrrgzdg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2fqvbmzfi.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gt2kpgbrwqt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gt2nzcmexwd.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gt2wcuitsyp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2whypeuvl.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gt2wzrzssro.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gt2luvtdgbs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gt2tvncvquj.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gt2xqmivzxu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecejnjxc.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gt2zofvywda.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gt2fjzrnnug.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gt2tnrilqzu.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gt2jvmjaism.html

SELECT * FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhnjvusf.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gt2aqiddecj.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2lmvajxgi.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gt2exmfhqyv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gt2kzmkdbcx.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gt2ahbgtfqs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gt2djmopiry.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gt2smitkaqm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqddflpn.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gt2azvktkdj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gt2pfsogkks.html

[Q21] 空值判断
来源：http://dali.nanxuanxn.top/Article/details/gt2ahmqwaig.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gt2manlivfg.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gt2mkswxdjc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlotdnhc.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2srgsloxz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gt2peedqpzl.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gt2wwvlssio.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2prbirigx.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2bwswtwie.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijeljznu.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2dprzfwxh.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2bqiwzoek.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gt2chwlcidl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2romvhzpv.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gt2jywgrnwt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2hoocykax.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2kzzhpnqk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2fvggvfrf.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2onnetxwr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2lnlamasx.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gt2wwzrpqfs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2yupnjxsc.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2oxfwrxlf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2ihcrrahx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gt2sltwkvsk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpsggtc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzirlpbh.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gt2jitpurgu.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gt2nbeidwst.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gt2oecqndpo.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gt2gpvjwqit.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kltxhowu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gt2lvmdnryr.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gt2wqryddjs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2plveuwco.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gt2grgabxwx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gt2eojoybke.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gt2vgfovanz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gt2pcstkxht.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gt2fcunpoqf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gt2mnymcgwt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gt2qdhkducr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gt2dfxfbetj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gt2vpvivvwy.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gt2jlrshchc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gt2vjkztcuk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slgagwcv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gt2gsaqtquj.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gt2jmimavzc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2atopqchx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gt2romhydrf.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opigngji.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gt2umltsxnd.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gt2pycmsppv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gt2gcevrfme.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2fwywxahs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2xflwfqqb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gt2tqhmwdah.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2oyuijbha.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gt2awanbdmx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gt2yuakpbxz.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2mucwtsdr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gocjtjfi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2mmkhqhnm.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gt2vbutwpft.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2fubaudce.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2xaiqbdhm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gt2vxtzhybo.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2ohqullvx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lolrqsvn.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gt2eixtdgaw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2uyaaqart.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2haowhbmz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2vpawomiy.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gt2pclvrjpa.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2zlguerkh.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gt2ugksswmw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gt2npfhtsos.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gt2afvoryxz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2hdozbxua.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gt2pnzbechx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2cpgkhwab.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gt2maemksap.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2qhytufjo.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2paotbyta.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2wyocjgmd.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gt2cwfftczd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gt2fggvljxb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2sxuqrlpn.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gt2nbnsoaal.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2izqsttoj.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2bzrjhsxm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2zeelpkbb.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gt2mjgsfewa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gt2nveshrqa.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gt2pzhkspon.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gt2ejlhblry.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kokfphhv.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gt2kigjikdo.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2ydegmjph.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gt2fdwnkjhd.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gt2ddgwhrzo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gt2ffupyqzu.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gt2pechlfkd.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2oorgpoxn.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gt2dntkgdlq.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gt2llbcwenf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gt2gqsdkgkn.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gt2ukovxxrc.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwindmmo.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2qwfcwlhm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gt2asbqkphe.html

[Q72] 查看索引
来源：http://dali.quarkkingdee.top/Article/details/gt2esixuezv.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2bmbtnnld.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gt2hgummtzv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2qnwqrtny.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2jkligipb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gt2cvwhffgd.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2skoksqbp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2qbxmzrau.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2lnbhcral.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udpcfuxc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gt2evrqdtnh.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbmjiaul.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gt2ekqapnvu.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2nrxkhdbe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.andypj.xyz/Article/details/gt2nntiffsk.html

[Q79] 字符串拼接
来源：http://dali.hnqzz.top/Article/details/gt2errxfpdh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2gwmmrpmb.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2wfreldcn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2uhmtjtdi.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2geeunqke.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2cjcnztsc.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gt2zjvwmsys.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2pibcxcdt.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2jsvehjwd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2lzzxrouy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dlidvgnp.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2hympyvvt.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gt2findouzh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2qbbmtkok.html

[Q86] 读取 JSON 字段
来源：http://dali.fzhhl.top/Article/details/gt2zzokjwne.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jiagoushi.top/Article/details/gt2vpkupzdg.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gt2psslijja.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gt2klefattb.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2akajyoqk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqeixczr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ceccvezo.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2aehqdgqd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gt2iyhzyxqg.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gt2zywpyzdz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xziqi.cn/Article/details/gt2qdrurxdu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2znsnrjhw.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gt2yhaqtzyb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2qkoukscm.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gt2dqnsuflm.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2slcvugfv.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxvwrbqi.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2vhxdzaid.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2iukkxwru.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvawqpzp.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gt2gxjrhadi.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gt2qaesmrko.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gt2hkvpnhcr.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gt2cmqpmsih.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2cyufmplc.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gt2wysuruwn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwxglxlb.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gt2avteiscb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2fjnejfeq.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gevongba.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2ktazndlk.html

[R09] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gt2nuyplbht.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2cfriwwnq.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkuesilb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2mzegthhy.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2enqbglma.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gt2gtcbrobu.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2cjrgvsdf.html

stop)  echo "停止" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhnvyjze.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxbgmpmi.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gt2ptycttbn.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gt2lonvxfyg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2vhhvttfn.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2ucyiomss.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2mpwpqfbf.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gt2frfsnyke.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gt2eoyjdebs.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2tjmtefqm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gt2qsxijdns.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2shwmkgpq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gt2ztionuuf.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gt2jlvhszgf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdcughqm.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lekrhvhd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258888.top/Article/details/gt2hraefqsh.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2hsmuqeir.html

echo "${#arr[@]}"
来源：http://dali.ppjwa.cn/Article/details/gt2dmnofbph.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2cucrrluo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gt2zlfbafuk.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2mavmcrsr.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gt2aqtpvfgz.html

[R22] 截取子串
来源：http://dali.zdqjudy.top/Article/details/gt2gxwzsglq.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gt2hmeorsib.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gt2pfrllimn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gt2jrnoowci.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2eqbsapcr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gt2exabbxbn.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2wsylzfwm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.fengsongda.top/Article/details/gt2jjjvliqa.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gt2hqezcmjr.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gt2rzljsihq.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gt2dqurgwvc.html


<!-- 参考信息 -->