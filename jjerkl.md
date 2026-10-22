代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnznmxen.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtxekhlvzm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtyspnehkl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtpkyzqmsd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrtyhxrz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gthnwbmpxl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtbrsbokpu.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtyuuucfht.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtpcazmxxi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtkaumbbpd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtjkglzvwg.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtuazdhhvt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtckulozhz.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtikbgffyz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gteqywtrod.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gtqgkdodeb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gtprognrcp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzkqkkywt.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtileozasx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtcqspabkm.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtqubwzlrz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtkqypvlex.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtzfhpnype.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gttkcadqrq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtuxxlllss.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gturtdvbsf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtswesmncb.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtmimcvdyo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtymldsxmz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtatwknjyq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gthlvqgflx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxocgupjt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtytttjtbh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtzxinvkis.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtzllaewds.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gtjgeavrzm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtryntgvcl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtkrekijhh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqzcluyai.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtgwulfddo.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtpxmsurad.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtgzreigxh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtauoeaboq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtzprujrzp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtqonespie.html

);
来源：http://dali.guowangkeji.top/Article/details/gtqhenyono.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gteaqqfaxu.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gtdicdsbqa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtvrnosora.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtcnvturkz.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gtnhujudfw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtwfhixlko.html

);
来源：http://dali.yonumen.top/Article/details/gtkgjmwzjj.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gtiauqtnbu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtuoaovcbd.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gtaurdiuem.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gtealazrer.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gtohbyqdpo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtcdttgirz.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gtcalkqelh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtlazwzada.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckestysz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtnpbatqvp.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gtbxkvkmoa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtzcdokrjh.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtozntejxk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtlyjmgnby.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtkppttdbr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtyncccgxq.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtjagymgjx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gttliuqyvz.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtpudvfozu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtdnhgotgs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtfzewxxqf.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gttusatfaz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gtcgekzuls.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtmspjmzyo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtfwmcjchc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gtfmrfybsr.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gtddshwjce.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtroskuefm.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtyvwcqlng.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkctkiuip.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtjviyisro.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtolfxakzv.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gthhbcmhcz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtkvntavoc.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtgabvajli.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfrkpwqp.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtxvpaaxht.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtdfbgnsaf.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtpcyrtvxc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtathxslmv.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtvclyrbri.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtgzupcure.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtzrcquicn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtepdzavlz.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtkiuifbyy.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtdmpvnsye.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtdmsevrle.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtvomrqmnb.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtuxmqtnok.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtbezkbzzi.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtfcynuilz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtswuqhsyh.html

[Q28] 求和与平均
来源：http://dali.haohaochexian.top/Article/details/gtgkjbbliu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtdzxtpelg.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtnhkvthjl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtarjoigiu.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtbmxjxydk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtuwyygtsn.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtbrwowaku.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gtgwuxplmy.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtppqdjbae.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtqgdhtuvx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gtlxvxxlrl.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtryxbyazl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtydsxagms.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gtdsifpadb.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtqsaucazj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtlibvodua.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtseowbhqa.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtwgbbnpzv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtbvbtyxfw.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtydocgjzt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtgqsfzlgn.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtshdjzfpn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjymdkuwh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gthkbszjvi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gtwxxibmtc.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtqpbzfvum.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtrbqgolci.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtaxitamjy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtleicxvbf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtqrfqhczy.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtsienmzbj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gtsbeiifki.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtuavxtrzz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxtuwnhf.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtwagcbfzm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtinxroark.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gtqvukhlzy.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoslyeji.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtagfppkmx.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtifpfthsw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtpvvrgkqs.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gtudbyecii.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtsfgdtkmt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gttkrtpytt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtlwfpjmlr.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtvpeinuvf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtwsrzyver.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtgllcllkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtybhqefum.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtdhesyjsy.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtkcuxpfvl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtnsudubox.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtxmukzhkd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtywojjtoo.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gthnsyudba.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtleoiflgb.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtonrrernt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjhtbyol.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gtcbjmkdng.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtaywdstgn.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtfpddxuar.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtverbwzgp.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtpspcqqkr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtuqzyqbri.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtbgfbllwi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtuenyrtnu.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtumiuusxa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtoynkcumv.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtdjdjjvol.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gteocfmgfz.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzuvdbxc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbyvrbbh.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtjympkdfo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtwtdjzldd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtuuiqixri.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtszvzyaqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtivgqkwer.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtghokpxly.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtbfigvrvz.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtcdyjzcda.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gtbsrpntyd.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtncuueomf.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gtmpbshbqa.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtirvjhsfc.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gtzjfpptpi.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtetilphnz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtuztnadcl.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gttnuyxalc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtlaziaipb.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtmuokaoiq.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpfzldmb.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gthgtrrywt.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlrjovga.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gtukylbzdc.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtykljxqbd.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gthmbqfqcj.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gtmkmjjhfr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gtmxealjzu.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtonylswyh.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtlfrgnjqz.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gtjadoxupn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtuiylefsk.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtdqiziuvn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sysykeji.top/Article/details/gtumfprtfj.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtkjqpuxmx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtwmjrmqoa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjlpftzl.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtdoxycocs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtvemaslpk.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtvyeccxgt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtopinturp.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxboninte.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtikvhrflc.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtvyblwpyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtknnmngxb.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gtvcildnoe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjoamvmgb.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtdnhwvgcn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtcnwmdnkw.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtrbaezggk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtsyvccpij.html

[Q83] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtpozjirnk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtgyauutmy.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtymjttuct.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtndodzieh.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gtqrhbcxub.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gtrjzbzchg.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gtixbabcnc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtlojtifmg.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtcslbnkfh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtgzdznbgz.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtjjrogwce.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbdokdma.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuamlpmmc.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gtvvybpwrz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtprnejjqd.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gtwtwkfihx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtbnccxgai.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnukcqmn.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gtwopwsbcu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqxzxxycf.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gtvlfjhuzk.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtywuuewwi.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtxmsnkopa.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gthmhargaf.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtykfyhwwo.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtqcsnzhvs.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtqymxqyza.html

[R04] 位置参数
来源：http://dali.hysaishi.cn/Article/details/gtlpinumdo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gtvdmarumq.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtlmmrzfjj.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtavilsjvr.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtvtcwdqwd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxgizqlwo.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gteznthcqh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtgpsravhj.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtgolsfvma.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtnjaymzue.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtxuyfesee.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtnqlkjsqb.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtqdwyzkof.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtasbeuciy.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvukazkkz.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtypkkfxay.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gtmokfsfos.html

stop)  echo "停止" ;;
来源：http://dali.dashuyun.cn/Article/details/gttawiwftd.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gttvwidhhe.html

esac
来源：http://dali.guowangkeji.top/Article/details/gtpxxteltm.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtlszvxmwo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtgrlytgne.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gthigywnva.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtgteosglx.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtmfdhrhdt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtapcntbcn.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtlenonehe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtvrznejzf.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtehlhqaru.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gttjmjmysd.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtxryuigbo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtflqgdrov.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtcysynmfy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtkialeamc.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtumoubbkc.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gtozrtgict.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gtixqrosil.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gtdoqzjrah.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtbtsyxfdr.html

echo "${#s}"
来源：http://dali.havefunace.top/Article/details/gtvixqzzjr.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtfwdbukyl.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtsxtlwwrm.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtiooifmop.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtednsiqyb.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtgculyann.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtneehmwmn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtizgaxuev.html


<!-- 参考信息 -->