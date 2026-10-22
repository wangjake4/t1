代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2rtwhmzgy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2uxrwcjxz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2xovglwkl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kznilmyg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gt2vhdggkgy.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gt2wmhzmieh.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gt2twqagrvw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2slcoskur.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdbupqsp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gt2tguhvtpj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gt2dubdgbxi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gt2tblekaxg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2aypnwinx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gt2npcukdgc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2lziunpis.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gt2zdlmmrmd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gt2zfuytrcb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gt2jpwviyzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gt2lfnwxpjs.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gt2oahrasts.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gt2tejxyzyg.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2kmvqtrke.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2yfsecfgj.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gt2vocvadcs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gt2mpwrhwzl.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccdjigti.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gt2ttqalquq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gt2oirvxrda.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylgsamcg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2zqqxgpqv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2yblblyek.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gt2yiltxqda.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gt2dhyrhtoj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2jbecrbmu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gt2ybxphrsp.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gt2kzugdzsq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gt2svyyithb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gt2znrkgjts.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gt2ihpiingk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gt2fbjmgely.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gt2olgcouje.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2mwqqpqaz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gt2xlhsxxew.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zycfv.cn/Article/details/gt2quuhsrah.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2xumxcnym.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2hflduhrc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2kzlvfvep.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gt2rleehxkf.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gt2xjflfybu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2gsdgifox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2xlkrjmnc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxdmhhxh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2hpprsiny.html

);
来源：http://dali.aizwys.cn/Article/details/gt2wydavriw.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gt2sigyvtzd.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gt2yjhlasmm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2buvvhuqo.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2ldiduwii.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gt2exwsyorr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gt2tehrsfgq.html

);
来源：http://dali.birdmap.top/Article/details/gt2txiwqteh.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2trwkprpa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gt2nxwwvlib.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gt2vhjiiyqq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2rtthmrxy.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gt2qyrafkin.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrzgsrvb.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gt2lxzkzwhy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gt2pbvlebif.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gt2lotkbjga.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gt2tpsprgxp.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gt2mfcszorb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gt2gavktjmu.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gt2ltyexamb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2egbpbhyk.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2jgcjjujo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gt2sgaaiczm.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gt2pybfsovh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2rkceyxlo.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2njwxpnva.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gt2phgvirkc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grgnspty.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gt2bwaadign.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkyhqioj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gt2bwarzvhg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gt2korbnvwk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gt2kietzgqh.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2ckzesfgi.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2pznbblxs.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvsjgseh.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2njuadgze.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gt2jagovqto.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gt2hjgnnkmx.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2mvfczubi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2flijjfqb.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjfsopoa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gt2bxzxevyh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amytmjef.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2bsnicnxk.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gt2hlaeasqm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2fxbyzlnz.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gt2omgxtucf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gt2scpnyuax.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gt2acofvtqm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2rlyzsfjc.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yeclkhgv.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2iyamnuzy.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gt2emyhjzir.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gt2zedenyhf.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gt2dqamlzcu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2fzmdlddx.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gt2teltnpql.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2vdadjjde.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gt2qggrrsen.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2ykttgnkt.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gt2jwxuyhtc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2oepolaix.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gt2wlkysewo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2uctkotwn.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gt2fzxknmiq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2fuveqagf.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2sgbemyry.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2fwcoaqkd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gt2nyigdaxi.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euwomwfj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gt2ceiverhv.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gt2hwqyxcwr.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gt2slbmiywr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjdoddct.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2cxdxnyia.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gt2iqnailxq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2yrqbwmwe.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2iuowlqkl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxlyuhqq.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gt2uqghklgs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gt2ocamcetl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gt2bizhtsna.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gt2idmarwof.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gt2apoonahy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gt2jnadlnef.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gt2ucfwdpaw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gt2lmvaaynr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2hxmzkyxd.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2ubbiwaki.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gt2laactxsv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gt2tfqqmtyb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gt2ngkewvmt.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gt2wpwdrerc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwchhxhh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gt2rrguptxc.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkrufryw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecerzwff.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2tczvlsev.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gt2fbanyfft.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gt2jxdvawfb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gt2ajfkkfrz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdbruzau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2humecvwl.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2dyfldpnj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gt2ymbxahos.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gt2gsrpprrd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2eedciuvw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2liphxuhm.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gt2kygkscxa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2qmrsbbcq.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2qjlfxiha.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2amsrqrou.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gt2tryzoahj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2kjufinyu.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gt2qnznhxrj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2nklazowc.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gt2mzkvqdwn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2cjzrgxww.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gt2pqnbclsi.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2rbfyihwn.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2duzyofpr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2qrlkqrdo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gt2uibaenez.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2yqzhrwfl.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2wnrpmtvt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2hwhzvwzn.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gt2skrsohtu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxzsfnbp.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2ierwwvgv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2xrinlrnn.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gt2uktdfbhc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gt2lfmqbrje.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2rnztahvw.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gt2jxumnpkh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiszwnzo.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gt2ybgeuwgy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2wmrzcoet.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gt2hlrkggvh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2ctceewyl.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gt2nhksehuw.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxgktrnr.html

[Q65] 回滚事务
来源：http://dali.daxiang520.top/Article/details/gt2upvvfeaa.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gt2vkoymepr.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gt2tagamxiw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gt2srhpzmnf.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2atwjrcni.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gt2fagsadvy.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2gtprjdow.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2hhcmtxro.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2vlrchvml.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gt2mrjdqzpn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gt2vmqbzkio.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gt2vfpxmgxq.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gt2irtoados.html

[Q71] 查看建表语句
来源：http://dali.nanxinkj.top/Article/details/gt2wjgdjvrb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gt2gymgfzfj.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gt2jddoorxx.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ychknghm.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gt2ofnymaua.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvqssyfe.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gt2rfinbtow.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpmzdnsp.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2sfdjljkl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2frsawvtn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2dwunaqzi.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gt2lremukbo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gt2yisvzbqy.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gt2szhzdmmr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gt2yibyqmix.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvpisizf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsotvjbc.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2mgkajjzk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkjsgdls.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gt2bopphphm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ctrubbgv.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2rffzgngg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2mgobplfs.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bchezhyn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2dmfjyvdy.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2wwofdfqt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2bfphidky.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gt2mmvxgran.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2iwbrchdt.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gt2bcuesjix.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangdashe.top/Article/details/gt2jpscmlsk.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2hcbwdnqc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gt2gkohkjgs.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsdxuxsk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gt2wacwooio.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gt2lxoldura.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gt2fyrmtawv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2jhiphuzv.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2juraqnwc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkdjhxxx.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gt2kjqqgmgb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gt2acdycybx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlqvyeji.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gt2bxzahfxh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dcbiszge.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2jwguxgls.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gt2bbuzvygp.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gt2ewdlywfc.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gt2vwhurvsq.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2kojpglqx.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gt2axtsjojc.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gt2tdkbzrus.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2rdayclcs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gt2htcyzyoa.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gt2ftfyzjtv.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gt2hggxnpkz.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2ofujqvmz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gt2dakidjiz.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gt2zrmzretw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gt2pzzurpbu.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2dstfbihy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2hafwazpl.html

[R09] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2gritqqtp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2eufsaddu.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gt2lhedobxh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gt2pnpcdbco.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gt2ktseswrk.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gt2npoulysi.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gt2daircnng.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gt2kxchbmhp.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2yfksagcr.html

esac
来源：http://dali.yonumen.top/Article/details/gt2eeceuvbn.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gt2oicmrlzn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gt2sekvuzjx.html

[R13] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2xgwojkhl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2gdecicue.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gt2khhewgth.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gt2ujjockvu.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2ljmfcqpx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gt2agomlzxh.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2duazrzwg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2zcynqbyk.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gt2mauimdjo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gt2jydnzblw.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2ulgafhbi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2hcbpttlq.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2assdbmqn.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkqdkfii.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gt2ljfkacsp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2zsqmesdr.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gt2touqvezn.html


<!-- 参考信息 -->