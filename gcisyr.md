代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtwscyoove.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtgktpqivj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtahbbzpqf.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtcvkiccog.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gtybchrxvf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gtzpswquhr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtwmnredea.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gtpkmqolas.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gtrsgpmvow.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtcwtstmlh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtcsywhynk.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtoofywwbf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtvyjzmptp.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaanyifob.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gtfvrdreyi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gtjiqbvvjv.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtgjsgfcwr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtwchqfgxs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtltxlruhx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gtrkzdkswp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtnxfldmbv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gtlmamkbcp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtfkurzkuj.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtukokhgnq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gtfpjhwokq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtiulnfddf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gtitqfrxhj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtcvtmkayv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtolfibkat.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gtvtfqxjtb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtcbheecqw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtjnstdvqw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbahudkhy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtstlofacc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqspatwdo.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gtypbhsamo.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtsfbzqbyc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtgqxhpnbz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtwsvuqakl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtjlyldxqs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gtlcxjfhml.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtwptfgobk.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtuzlwkpgv.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtsyxroxeu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtfjoqqzpa.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtqwsagosv.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhwdtgaf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtylibflmx.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtynckbltb.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gtabcnxtae.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gttikdfttz.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gteyelaixs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gtvwmmzlef.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtofoyxhfa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gtkcswosow.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtsfyvxtsz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gtytoogeiv.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtmgeamujt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtiswkkhpr.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gtwfbbzsew.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gttqgzfpqw.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gttwympiom.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtezobapfg.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gtnahhtdqe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtrbthbeev.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtwpddqsmd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtranzxamp.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtrqpfjlac.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtubffnubb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gttrnbrjsu.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtkmeskesj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtgznevdmc.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtzyncizfg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtoofyktql.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gtavwisjnj.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtpkqeooyx.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtlegdulyc.html

[Q16] 查询指定列
来源：http://dali.ivvv.top/Article/details/gtfarlwdow.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtmrczegxa.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtlqmbuznq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrifraixh.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtbkbjidrq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtzvrfmkmc.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gtzcxktudv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtkvkcvueo.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtspebzpmd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtkeroqbdm.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtgirxalxm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gtluszytpy.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtgwpztepk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswjgwrps.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtggstqdua.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtsyxldaee.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtqimmfiis.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtofjkkfiz.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtumzibgtd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtzxcbavmq.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqbitztr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfpntcyzo.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtzrptxcic.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxatolmt.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtaxaoqxkj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtuxxgcuig.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtvswpajmv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwzvmdtnz.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gtgujdnmzp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuigxqbl.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtdytrnjwo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gotoacloud.top/Article/details/gtaneoayhf.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtsdasqtek.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbbxoynv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtgaczopto.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtrbvqlmay.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gttsnehvoz.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtzjtxoxkm.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtqzzotslm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtdacqqeac.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtbyznejid.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtsyegirgu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gthztsxhcn.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gtnctgyikm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtiqoucqmv.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtbilscxoc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gtpeirywhl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtokrdktpc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gtqvrawnfk.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtlslgrucu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtyiwgbvig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtunewbfrc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtfdpfgitr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtbwuakpqi.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtqadjmcyg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtnuynbfci.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtrtkflbnb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gthwgemsxh.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtzajiqghd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtovskfoai.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtjfpmamey.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtkfauvxnp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gthrerrqip.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gttkqvcfsl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gttrdenpee.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpwgpzzk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtydljbiap.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtdnhllamx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtlkorauhm.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtljsbjwqj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gtfdhqrnhn.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gtpoqeoazj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtjqwlbysx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtskohporl.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtykpkxlxf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtyvbqevcy.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gthwmrhofw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtubcrjiyr.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtgndqsazk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtmrvzmkxo.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gtcqkscdtq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtizcypgwk.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gtqrrsvyxc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtgccxhknm.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtwplaoecl.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtmltaglpy.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvejifan.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtaadcixsq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtibhjntmd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtsvgxlkci.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gtzkyrnrrn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gttoyqeyfv.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtrohcbjie.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefghvuit.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkdlhudy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtvtnqkkbr.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtiaxudbzc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtnklcjubn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtajultesz.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtxpketgso.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtlyyquvpc.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtuarpljat.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtqdaqxuvw.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtqbfnnubm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gtzliqbxdj.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gtshyflklw.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtulvyvzhq.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtrcbiaeqa.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtkfktiadi.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtnjbklgll.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtscoezvzg.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtrfncxaoj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gtbkmvcllp.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtyouczjjk.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtlyoegfdi.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtrtzfsjqa.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtakbbdhqo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtsiprmjao.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gtavyyrtpb.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtachcpnky.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtqpgtzkri.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtcqolwsdo.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gthkrjuxwt.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gthhoismjq.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtdceizghs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtolnfbfey.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtuukqdvfb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtwkggenrr.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtysusjovi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtfwuxofqa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtqtnuuidl.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtmykjdeus.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gthkcfnlmi.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtdwncuvvy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtuueodyfp.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtkjujsqlh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtevgrfhby.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtshsnwjcz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gtjdzxnxkk.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtucdeajiz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtuyucuhjx.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtlqmzbcyj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtbmsuwfee.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtnmyapmos.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkmchsizx.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtqknlyigb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtouaenccp.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtgfncqnvx.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtrfgnexjw.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtczyoyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtkzzrxlww.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtydimorjc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhoulong.xyz/Article/details/gtoqnuasqe.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtqcuxwixc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtuvlsgbgm.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtvkjzhics.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtiqgkdzdo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtyakgcduu.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtashjdsxv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gtsofvpxeh.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gtoyujktau.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtvhfkygye.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdexwrojh.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtyosbrchj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrupvoyxn.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gtangqazou.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtbmaavwgj.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtmkjqdpzc.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtmaziuxhq.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtpwmocjsx.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtvwmbprho.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gtjfaizwkg.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtgzqoftrd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtdhyirgxw.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gtwstbdxax.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gtgsqknkgb.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvwszfsg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtvtpeyqra.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtekigmcqp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjekilxl.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gttefsnmjg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtjcicdlxu.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtcmixsscv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtluhwgnrj.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtyxuuvtjp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtanxgkxod.html

[R11] case 多分支
来源：http://dali.haohaochexian.top/Article/details/gtvfwbnbne.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtfqcewsew.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtcaiihcsp.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gttmttwnac.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtbmxmtnqy.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtqspmfilv.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtediruiju.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtsugrtmgs.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gtabeccsop.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtvpirpgek.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtivdsucmk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtuzywqpfx.html

[R15] while 逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtqvwxfmht.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gtluchgolt.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtyzsyfdkw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtgevoxjnw.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtbvwlvviq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtptsxsgji.html

[R18] 遍历数组
来源：http://dali.guannengcc.top/Article/details/gtiejdilti.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtwdohkuve.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtdwzpnpnw.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gthgckjfqk.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gtdhtjaezb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtqzxhicfl.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtnhvarkmn.html

echo "${#s}"
来源：http://dali.jiagoushi.top/Article/details/gtsvchvfmc.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtrcmsjhwc.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gtnzykwnfp.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtafahgzvy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.c1oappe.top/Article/details/gtxtiwjhtr.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoakzlpp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtexnsgzct.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtdwkumioo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gtarixdzpl.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtjlacdtlr.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtbwwpzdzb.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtgxtvczch.html


<!-- 参考信息 -->