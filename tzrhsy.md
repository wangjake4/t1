代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtxrtrsrfk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtsupyvwuy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtczfeoznk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gtxhlkmffy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtajcxfefl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtpmanqdzw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtjcucggmp.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtgjqoxrxk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtdzqwyspf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtlgzviwqr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gtccboilyq.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gttzyrbtcu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtvapnusod.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtcqbzhypk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtvabtojjj.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtqpwljjrv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtrobxlpfv.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgxballq.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gthjzuetbu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtznmnietc.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gtykmnxhhl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtwxjotvqm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtldloaapl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtbarzizhk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtttaboeux.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtggsvlhle.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtkbhffbax.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gtxawbkihz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtwdqipsgq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtcrjofczk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtdajmfnpj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtyqzgjebv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtmlyhuzst.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtwotexvxa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtriajywpo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtjxeczndi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjjuidaqp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtlosympua.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpryqmlcs.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtmzlknybi.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtbajmdwup.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtchuqkfmz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtzjyeqdav.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtkzoiatlk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtlktquybv.html

);
来源：http://dali.ybcxt.top/Article/details/gttesemiie.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtxyydayse.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gtmfgwhnpg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtvieohcjd.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtykudhxaj.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtfwxkfwrm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gtwjlgbgyu.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtawvrsvcf.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtlvvvhnjg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gthapmeotr.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gtypjspopl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmhxtmln.html

[Q05] 重命名列
来源：http://dali.andypj.xyz/Article/details/gtheofzfsc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtwhlmhodm.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gtkumondse.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtnqnbbmps.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gthvmaulll.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gtedwbxnup.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtpvhdzlka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtfwitcloe.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtpzxzrumy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtjkjlntfy.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtjaqmewit.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gtvamgfczl.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtwrxfdmur.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtukwumcos.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtyprjsfeu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gtwazqeekw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtfbjrrgpi.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtypepbche.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtpyzvglbu.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gttawictdl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtwscgzlti.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtpbtpnaph.html

[Q15] 查询全部
来源：http://dali.nanxinkj.top/Article/details/gtrjhlopkh.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtwkplaghb.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtrmmpbvzq.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtypfgfhfy.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtuseffakk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtpuyvight.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gtwdzymica.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtpzyahmkw.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gtedtfyghl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gtsgijkkvt.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gthsogjeqv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtkmjppjfb.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtcwmpzkzi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtbauabdkh.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtzmupwwlz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gtulqdulyd.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhrhiemh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gtnakwnija.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtdlgfkjyr.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gthywjfwyz.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtgcqksiaw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtdftyugap.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtqkeusfzy.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwwqlhtsx.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gthtlkipvq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gtxvlxjaim.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gtpptkhafr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtpgpbaqiu.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaggwyor.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtszgiuysf.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtszzirfsk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtjzkglxhz.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtfvebmexh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtzfpthhtw.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtfaublcae.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtmozyauwq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtmbzouves.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gtghrxuukb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzhtenyp.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gteuxzculi.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulucbtpv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtwezjoshm.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gttmcrlbsc.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gttknibahx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtbeglixho.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtgpbxeoap.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtzmmqaxlu.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtzpnnchdc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gtbtuocrhk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtpwlozcdv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gtziiulyha.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gtqbqpannz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijxindaw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtdrmwctwr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtjogvcaco.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtnbjvbfoy.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwmubzev.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtgzjiezfg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtzoyoqbve.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtcztvjvlx.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gttqfysobh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpknhxtho.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gtwtraqxte.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtcjktwise.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gtokflhoom.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupsmrzon.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtkrcmqwok.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtbhflfnec.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtmlpfwlui.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtrpnitvqr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtodmzogmn.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gtdjybstlw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtgsenjxpm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtwoagntfi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gtpovtwgqk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtjzouecrb.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtizzmomnn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtqhlabyei.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gtjevjkcsu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtrvpbcega.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gttjeklggv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtasclyvjg.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtzxhbuxen.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gthufwktqk.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gttbgeegfs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gturuvscmg.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtaeabmnhm.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gtgczuulpd.html

[Q55] 排名（并列占位）
来源：http://dali.zycfv.cn/Article/details/gtegaxxbum.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtzobwhosg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtjuphggks.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtdqesuhyv.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtzvulrjzs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtutdnkood.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gtqdujugxb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtxumbilcd.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtwsjdlfro.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtvqmhgprq.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtsqtceuru.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gthiolcvna.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtvkrppdhz.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtzfxgpwdc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtalegkwzq.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gtpdfeksgi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtfxjewsnl.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtmetwoajy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gttfhshwuc.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtevyoooqm.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtkigvopfv.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtipzuoooy.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxilkmbnt.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrjxgkmm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtiwwukmzs.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtsxyiokdj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtldsijmhi.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtrotsiygz.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtmvqhllna.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gtygjeekuu.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtsyaackuy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtyzmynqxb.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtnhadzffp.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gtmqqntkhm.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtejjwsdwd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtnfyoaioi.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtystpowjf.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtwsnvrtjg.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtsrcbhwau.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtewkqjkec.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gthmjwvywz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtzokrirmg.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupyxbbsx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtngpnodgc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtyaomsrbs.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtllaanbcw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtypqifptr.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtackztqme.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtpcuqjuuy.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gthriiykvo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtlkiwbgar.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtnbjpfqfo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkitowyyt.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gtcrlmrooo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzonrcypo.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtuidxvdic.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtcjylrihs.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtiloicbnt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtrzruovul.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtifjfpnfp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtlasrgzgu.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtlynaavcx.html

SELECT TRIM(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtzuesrhya.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtgjwynskz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtzvbnwxhk.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtyemdeycn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtitrrvhbd.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtdazbvwme.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtiqbpszyi.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtmontgjnr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtselgyhdq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtqxmpdrxq.html

[Q89] 判断表是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtygifnrst.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtodvsmksw.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gtiwwppqgz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gtmdjfmxvv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsbkdsvyu.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtucaecpwh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtorbjhyvu.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtfwudzgss.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtjftrtuqy.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtvfsvrmkd.html

[R02] 变量赋值与使用
来源：http://dali.hysaishi.cn/Article/details/gtboywoizd.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtoogryfou.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gttexlbjem.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtbncqqypb.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gttzekbphr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gthvondnnm.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gtvslrhfir.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtppkoclzx.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtuoztnbum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gttoltpvim.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtkasucnyh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gtvlcmkgsv.html

[R08] 数值比较
来源：http://dali.shangyingyoupin.top/Article/details/gthpskucuj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtzpswszvg.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtflwmxfax.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtdpdeauwe.html

[R10] 正则匹配
来源：http://dali.wangdashe.top/Article/details/gtckfsyhgn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtoozvmjtn.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtevcvmztv.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtfeposaql.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtaozjiotb.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtxvabqlmz.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtvjidlrlf.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgokncvhp.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtftjqfpjp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hysaishi.cn/Article/details/gtgdlduwgy.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtouoznbgj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gtvrutxrib.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtazytumyo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtpfjdiaws.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtstpmdkti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtsupjeodf.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhyrgfuf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtaxbkveef.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtotoxuxhz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gtzxjtgucg.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtoskakgbx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtafnriwek.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtdchavwpa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gthaecxams.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtkywlhxjn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gtxlcjxaeo.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtrzsffuqh.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtjfuujzok.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtobmuuvnp.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtbcyjzflr.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtdjqkcusu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtrufiiksu.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtncuxfysw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtapxlbgwo.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtuziummcy.html


<!-- 参考信息 -->