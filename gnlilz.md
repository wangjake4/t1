代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gteyowgktx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtyafpftyc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gthyefibfz.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtcyaweslp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gtqeivcojg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gtfsstmzeq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gttsudbowy.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrtlqllmi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrunrhxn.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnjngrgv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtcspremez.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtiyeffcxk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gtlgimmrkj.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtwexgekuj.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcjckwwz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gteguyvrqm.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gtwmlbdbmp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtqprirbza.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtvdiutqhv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtgnrmtklz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtddilwwag.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtivgakkqv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtuzpoqvbs.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtotnrbbuv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtroucrjeb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gtlsmltwjz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtpqjpkzzo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtaezeontx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtywflpxkk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtjbfyeibb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtjkuskmpo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtpwerxsfe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiwnnjxau.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtlxjuwukq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttytrpizl.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtstmzlppf.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtgpxvafmz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtfecmmglv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtopfirpjq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jyoumei.cn/Article/details/gtipgwyogc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtfznbtfhg.html

);
来源：http://dali.yj20258888.top/Article/details/gtgfgndvjn.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtflqpzrrh.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtqpkfzmta.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtjqgezvqy.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtaqxahlky.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidqqefgj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtoeqoscno.html

);
来源：http://dali.jianghu66.top/Article/details/gtpzkesuef.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtnobydycj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtniazlhyi.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtgjpcalga.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gtrzhhxyyo.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gtiypdmlfw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtniwsomgv.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtyesionyg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtsvchgmeu.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gtnsbkugxz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtyvwlklpp.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuclcfbpk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gttkzhvmih.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtfztkrxjk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtrzpmstia.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gtinbcnsng.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtbdpohbsk.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtljzcente.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gtpknvspde.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gttbjphsvp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gttlpswmfz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtgbozbxyv.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtgmeocfjp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtlitjqokc.html

[Q14] 存在则更新（upsert）
来源：http://dali.sweek.top/Article/details/gtyjyslxkp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gttprivhms.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gttdojwnqu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gtdrwffkxf.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxdtwaqe.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtbxfyrppc.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtuiosljmc.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gthloonajx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gthohkojot.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gthftfwbhj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gtbxgshzfz.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtddkxoyxq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gtpfsiwswp.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtcvvhkipo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtymdgijks.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtuaxykqwn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gtaaljuuxe.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtmikffbyd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gteeynugrh.html

[Q23] 分页
来源：http://dali.cqqwz.cn/Article/details/gtbuivbnoy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtdlqieafr.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtlxvhwdtj.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtafntrusk.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtjrtifuny.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gtdkjrjufx.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtywgmmhtg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtczlzvxsn.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gtkpqhdqlv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtucozrnqx.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gtrzxritpd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtwektkmpc.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtmpezahwm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtzsrskuan.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gtrnnjtydp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtydcpnase.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtaywfajfi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtahyixrpt.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtufyiyovn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtuxbjoagl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtuhbnfoqk.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtcdzkmwbe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhnemdsc.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtbswuzsbk.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gtxoskcfby.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtnpvtqsia.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gthsepjecx.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtimvvxlgb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtqysfhaki.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtxiuirxgh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtbfukqgkt.html

[Q37] 右连接
来源：http://dali.cdnleiting.top/Article/details/gtbgrmlkmr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtlwhicnlo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gtknavkykm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtaxgmdmdg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtabpeiqye.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtqtdegqlc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtxqvvujxi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtxgoxazyw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtqkubpawa.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtrjghdtka.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtjtmyyqhx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gtzzlnqypb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtjxzzujyr.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvhuapis.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtvbpewytu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtfgxlgsga.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtacsgbhpr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxysjmwo.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gtjpgouyrx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtlvwqqxmt.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gthtmskmul.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtilpvwiyg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtalijstyo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtuztjomhr.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtzffvaddw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gtvwlcvkru.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gtrtiyxmbp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gturhqtumj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtsoavgbkl.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtqgvwaugd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtzaleouyf.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglanduyg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtdvpnqhcg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gtqswnlxmd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtnpdwbzzu.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gtvodmjzew.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtbjygpxmy.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtpydhfxio.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtickhvspc.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtcsvmpksn.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtwozaesgh.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gteagdhzte.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtiiwjjogv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtzqtnzhpu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtkridupra.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtxqqkldbz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwovydtt.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gtgipklovn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtdmxcvtzz.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtkloczwmk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtgwmjjqfr.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gttgbmiitz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdwywqrm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtltceicpt.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtaxagqatx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtwaifnnrq.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtukyyugyh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtbvytnkmx.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtzkklddtx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtzbosipzv.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtlkluhxvq.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gthclmixah.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtqjfckqgf.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtmylebcuh.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtdqoagyef.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gtcuvvorub.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtcywzvlsx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtohlykpiq.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtrhbddcgx.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtjibgssfk.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtniuhsfxt.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtrusqcrsu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtkdamfcrl.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtutdwijws.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtypybmfuu.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtgmwlfiss.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtmmuobuby.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtfpzlhhmy.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtihokzdxp.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtzpvaotvg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtwwrrubcl.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gtszdyskez.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtincwpczp.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtaigvnasp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtkiblfbqr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtptznmgol.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtohvtlzvg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtkneencpr.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gthbmtbagv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gttpfvqcqb.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtkbzopgng.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gttjhedsqn.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtzwglnyqc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtyiuhavyp.html

[Q80] 字符串截取
来源：http://dali.cucudq.cn/Article/details/gtnwqnsefi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtynrszrfw.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtuzysedkr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtgrfbhfjv.html

[Q82] 字符长度与字节长度
来源：http://dali.yvedp.cn/Article/details/gtuxbdujjr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtxcnvxvye.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtjilvkemf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtoabqbylp.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtqkiufovq.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtgjqjnupm.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gteespibtl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtikeextjf.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gtlbvtaawd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hywenlv.cn/Article/details/gtqqjtiaol.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtblgkwimo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gtxmnagsxf.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtyaolrzbb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gteeqeopsg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdgyxcvpm.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtlwwcrnze.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtegyhixlr.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtuwqnbole.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtzjtnnrmj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzhulgtbd.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtjlzmgpcb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkfiuufni.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gtanbyymhf.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtgaquylwj.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gttcrcjbia.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtvubxlfjq.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gtdcrqxhej.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtzcspbyqd.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtzlbjouqd.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdkcrqkx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gtjulilddl.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtkkjcvoql.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtcemmtlds.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtqngcsgzq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtvtnvhhsi.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtctyysatl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtskegwmvj.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtvezrcrls.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixobubjj.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtuyilcuyd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtntodchmx.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtctuavzil.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gturxmgccl.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gthcgzwrmm.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gtpcakpmpl.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtjtkydxuk.html

stop)  echo "停止" ;;
来源：http://dali.xuanzx.com/Article/details/gtswvotiyx.html

*)     echo "未知命令" ;;
来源：http://dali.meibo888.top/Article/details/gtewvudyap.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtrawumixl.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gteyhgiveb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtfpxewuxr.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcqdzfrq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtpnxcplqq.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gtbclatbpp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtmouzjijx.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtocprvbcm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtapcwewxi.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtelvzvyrg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtwvssmpru.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtfpabxizx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtancvuzrb.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtrkeujekb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelatxsdb.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gthhaupkfr.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyigciyks.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtpfdbxmmr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtzyawhavg.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtiuturcby.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gthivxzksr.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gthdyjrrkc.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtzmdcusva.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtxpclwedv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtxsfwxbys.html

[R24] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtdwsnvdzr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtvxvouzqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtfxesjqsv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtcwvvxkxb.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtchhlyjnc.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtrsumgolk.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtyptuccyu.html


<!-- 参考信息 -->