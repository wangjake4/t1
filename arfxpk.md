代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gt2nkcwatgn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2pwuoaaaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2rwnbiuwr.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gt2fkahcqek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2yusztelx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2tlpxwlee.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gt2iotsxwsp.html

PHP:  if (empty($x)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2qoempauq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gt2ojthlmkl.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2edgeqwpg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2omeouhne.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gt2xwavnkow.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gt2rcnmuabs.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gt2idgxlfjp.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gt2abaemntv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibqmcbsr.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gt2dxxkblfw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2ddibbtck.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2ckiqauuk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2znkntexy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gotoacloud.top/Article/details/gt2dewiwmmw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlumaorj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gt2pdkppumk.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2urxvkbgy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gt2vpwkypqd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2xrpqdewz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gt2hethhwmn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2goqjivoo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aapyvssb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gt2clbwhprh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gt2mfhbrqbi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gt2ezqfcrhk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2fabqaall.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gt2ihcvozot.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2itqeozci.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gt2banoenhp.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2kdywizwf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2fduaqmsl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2brtsbyzo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gt2vcglgrnh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2qypuqdby.html

);
来源：http://dali.ydzc1.top/Article/details/gt2ohftrsvk.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gt2qtcxnhnn.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gt2gvpdllxd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2oooivcbq.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2gboijkps.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2ydoszxqo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gt2ngqkecpw.html

);
来源：http://dali.hnxiangtu.top/Article/details/gt2admuztxc.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2jzhdlnub.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gt2upfzsusp.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2pcvlqfcp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2tlhfdjmg.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gt2ijfjkchu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gt2nhalhtov.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2xyewznzi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gt2stqfpxom.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2mzeoyoqi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gt2aafwtvod.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gt2qhzagwkq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2hzslemsu.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gt2ltvseuqa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2nfsfybmg.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2lwsvuuij.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2pimqtspd.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2mulyhdrb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlrpajzr.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gt2jytwrwyq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gt2xiqmbdon.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gt2udcnrafp.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gt2imbdxzyo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2vhjkajbl.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2ekkfqenp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2oyvfbkfc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bajqqkyu.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmfvynns.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ecfsight.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2apsdrkkx.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frlhuriq.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gt2vobrehbc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gt2pxeuanil.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gt2vmcfjabu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gt2thowzjly.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2zhlxxhkc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2qfsaxcrk.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2luottcnn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gt2wggxlfif.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2hbqbxfwv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2poeulhbl.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gt2mjzpzken.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gt2fnchucjr.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2wxollabz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gt2meduzhzq.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2uhiihwuw.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pukjdvtc.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gt2hdcexzic.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gt2mzwsytmt.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gt2drlirzal.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2ewmqcysu.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gt2cbtghvar.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2cwvcaloo.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gt2soxhnbej.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2dlgnhmsi.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gt2vszrwugq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2wwwltifh.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2ywbbdaum.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmktgfek.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gt2xitfezmt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gt2xngdmjsu.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2gjhstilc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2ngxdzbkr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gt2neoxxatc.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gt2gumousuq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gt2dprxcnaa.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gt2esmzmlmz.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gt2sdnetlzv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcholyju.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2iujvnckd.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gt2nwftiphi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2nkusgvvr.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2dtrzmjga.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gt2zqlvhjkj.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gt2jhrwxaoz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gt2dnofhtdp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gt2yrrrxwae.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfdkgggf.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2amgnmkrl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gt2tewuahmd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gt2axiycxru.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mobhuurb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gt2felaljzt.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gt2jdzcncpg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gt2lohfzqdi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2mwfmrbze.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2brgmiiwu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gt2wxwcodga.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gt2nxyxqekx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gt2ncibqufk.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gt2cmcpwyzi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gt2zdrhqfkn.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2yrvfwzbg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gt2mrgehzff.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gt2yadbiiot.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftafdgen.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gt2lhqccmjs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2ejxfutfl.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gt2pwxijfms.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gt2rptyerqq.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gt2rpsaxjkx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gt2tmioprtj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gt2vkgiesgc.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gt2isayxobq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2maltfrub.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2pufbbyzg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2ucatxajb.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gt2fmdhwjpg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2jluyvxqx.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gt2qzuiyvfw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hcugrgba.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gt2kqnpjxuy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2corlmghj.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gt2otxjycil.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2dkxhrkfu.html

[Q55] 排名（并列占位）
来源：http://dali.zycfv.cn/Article/details/gt2trnmydrk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2vvdtvjzj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2esechnux.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dccxsuwu.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gt2xbfmvrxk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2mttaxbcs.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gt2ashifacp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2sevefbqy.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gt2oxqrhbyy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2yopdqhkm.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2posdhxvs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gt2rfwxcvco.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2uidxtxmj.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gt2dhxpzfpp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2iuqqfltt.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gt2wduqstbz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2ldajbcst.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2aswohjon.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2xelffcsa.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcchetah.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gt2drvocsru.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gt2ulosyntp.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gt2ynwnowff.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2mkrheouk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfzopdsg.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gt2smhntdze.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gt2irhaztwa.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaqieotq.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gt2qjemzxfm.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gt2wvqqwwcm.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2dhwebfrj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2hgvdjdqy.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnfobhae.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gt2jsumlmiw.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsjofczj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2mrhqchqy.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2vknoidhf.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2vviyezpw.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gt2brrfbpcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gt2dqhdvxfg.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gt2tavotxku.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gt2mdanyesr.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2nauyfkoy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2edmbtfxa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gt2lsjikisj.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gt2hsdxnmhs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gt2awzuctin.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gt2wuidvgbg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeukbcpt.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gt2tamymjnz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gt2aakutfus.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fjdfphvw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwoxxpjh.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwkimyvd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2aedxzshi.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2eqfnenqc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2xndmlqjn.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gt2ragwmpkv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqewyaoz.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2bucrxjpx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ykelkewp.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gt2jgvnymxs.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ldjnclig.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2yibjyfyz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngbxxfug.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gt2clcrvqyv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gt2ugyvapqq.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gt2wfmkklwt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gt2mdnxcegm.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gt2nebfherk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gt2vcykiyub.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2xkseppyn.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2uxukzifw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gt2dnpoppgt.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkgvhnqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gt2zlmcmfer.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ugluuojs.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2tdrjzotb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2umtdnpda.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gt2eiapmfby.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gt2wwyegtzb.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gt2bfuexmzm.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gt2jtzfhrsf.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2yvnvryav.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gt2omzphuqz.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gt2dcznytui.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gt2hdationl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gt2aogdrcpj.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcguuzey.html

name="${1:-default}"
来源：http://dali.zhoulong.xyz/Article/details/gt2spklyraa.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gt2utfdpifc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2tvpongnk.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omssvidg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gt2vduttrgj.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2donnmywt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2remgnidq.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2gikeoamr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2iltfvxrk.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2azlygzrd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ybcxt.top/Article/details/gt2iuohhask.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gt2zlfmlotq.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gt2arawhfdx.html

start) echo "启动" ;;
来源：http://dali.yongpay.top/Article/details/gt2mssyutqq.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2sarbnvlf.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gt2rclfioaf.html

esac
来源：http://dali.chenlongwang.top/Article/details/gt2kxnkagye.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gt2sdctroix.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gt2lvuexwgc.html

[R13] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2rksuiwek.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2oijfrpqi.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gt2yobbnmvr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2wvfjolxw.html

[R15] while 逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2fmsnhhvn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gt2wrmsycar.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gt2pnwnuoab.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2nucfjxob.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gt2bclsqgcd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gt2mixwjboa.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gt2upelwpmv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gt2sjloowtz.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2fmqznkdd.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gt2rdhqxfif.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gt2lvuobocu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2bthsyqkm.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irhyjzcu.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2ifzqmfor.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqqrasmd.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gt2uixeszxi.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2enixvmje.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cucudq.cn/Article/details/gt2ahrvlnhu.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dazyqxch.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gt2mfyqbvuu.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gt2mhnmzwkv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gt2uovywrpk.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gt2rvnpvfja.html

now=$(date +%F); echo "$now"
来源：http://dali.yueranfly.top/Article/details/gt2ngzotvdo.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2lhojkhgb.html


<!-- 参考信息 -->