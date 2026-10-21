代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtkfttbcky.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtvuqcgtxy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygqfhiiz.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtmuvkaxzm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtlxjohvfm.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtfneoutza.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtzyrlviji.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtaiuhsorj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtcwbmjufz.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gteoypkiqv.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtcddlstoz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtaaxamxsk.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtgtepjans.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtqzagdqbu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtsogjkkmp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtnymbakmx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtvhkpchvx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtgrqxpcdz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtlrrksrkb.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtjhucsddv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtagryumki.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtpgcowsdh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizgnqtnm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtbgoqbkkr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtooerikzr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuinfvyy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtazvqxjub.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gthsgafgkv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfmkwloey.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gtfsjhjept.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkqaoaffy.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtufrbcwhh.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtpzzanrvj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtwneulisr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtpyrqxwkd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtrlkqlspc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtydeipnbs.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozqeliqt.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtiecqewzc.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtrtlsoygc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtkcafozsl.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtqzftlgzm.html

amount DECIMAL(10, 2),
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzglteccb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.c1oappe.top/Article/details/gthxbnhivq.html

);
来源：http://dali.zhengqikj.top/Article/details/gtywftpyxa.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gtamutxhbj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtsscroozn.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtzzennzaz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gtiszgykpd.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtqpkyajbd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gttcraxziz.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtduynmngj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gtmqwadicg.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtaznpqkxc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gttzfmbglv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtolxskkrc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtrgmuervj.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtemzcmjir.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtzxvkaqvx.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gtwaowhqjj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gtqfmpkoko.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtuuolnvpt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gtsjhagibf.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gtgnnpammx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtejiucfns.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gtykznwmfo.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtrbliulpy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtgesgwvse.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtfrbeuhlg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gtpakxghrs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtrexzvevm.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gttkjyutgn.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gtesocvnwl.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtnivfonpx.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtmchqdphi.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbhrgqxw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtuupyzfyr.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtoduxfyaf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtsahigfwj.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtqwruoosd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtavtirkxs.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtkkeevchw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtckgxbruv.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtzjyopemn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtodqafunm.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtyyyzaqur.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtmttvewwq.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gtnrxfvrdj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtbgzeqjlo.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtgnrdwkdf.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtuudomtiu.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtetmzmsyi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gtzcotopvx.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtagavarrp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtipzahzha.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtedohflin.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gtldpvyagl.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gtouacteub.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtzqsuhawt.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtvgmpjirq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtosirxizf.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gthidkcebk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtmtdxvrvi.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtsocihyir.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtezzwahzf.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtesmhngbe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtsqewozql.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtabeojaqu.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtswtwnxry.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtaneizcqf.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtgevloyht.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gtgvzmckfa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtqzvhrlnk.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gteuxuprex.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtegkfxbpi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtrxeoixqb.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gtxmgaarwm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtpoissduc.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtacctmjlf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gtkxzlrbff.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbrzwnfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gtofipnxaq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtknkrscrt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtekwiulym.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtfgvocmwm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtodaxdnzb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gtsoswrwcr.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtzqomkqwn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtxwathbzp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gtexumbxdl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gtojnjlxeo.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtgelxykqe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuexrigpt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtuidjghtq.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtaogvzhnu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtssalxyry.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gttykvvuet.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtgqpwdyuh.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gthqquzxnu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtvltthtxk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtufqcqhjf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtskudktzb.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtnxvhjugk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtljhylfpp.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtdnarjloc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gtzhcbpkew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtkobvieuj.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gtmwpxggux.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtdtgkpjth.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtpezqfdjn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gttolbigci.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtleatyxqt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtttbsksbt.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtaryjhdrp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtlgtsknyf.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtialmvpuy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gthuhnicua.html

[Q54] 清空表
来源：http://dali.cheryme.top/Article/details/gtqmpfjlrx.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtdfrvsida.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gtyylcpegq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtauimsvkc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfliplfa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtevziyaau.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtxlmyiofv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gttjkgfuue.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtbgztgifx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtqmxeeves.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtacdzklip.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gthsufgjbg.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtqkdgbeja.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtnsbpyjxu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtyjerrbwm.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gtsukxmmii.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gthwhdokea.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gtnoszoxbc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtjcjnsgmr.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtqrbllnoj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtgnyfmvfi.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtejzfrwko.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreejqman.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtatpxdrmx.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gthjoverxk.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gtzlxnuedl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtanuetutt.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtgbdllhzl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtieeleofm.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gtkgmycfzg.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtyuqprhmb.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gtinpnuxog.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtzjmjtbtg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtihyziacv.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtsxqfngvm.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gttzjhhsgg.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gtpxalpset.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gttxzieext.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtltqddulu.html

SHOW INDEX FROM users;
来源：http://dali.nwbrower.top/Article/details/gtobcqaedk.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtdrshssrn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtbuhichqi.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtdsqwcpui.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.birdmap.top/Article/details/gtcetrfmjf.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtgauartlg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gttxyxwxzt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtdkkaovig.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtlviqfcqq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gtkounrrli.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gtxkripfyl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtzawoftwe.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtzoyjpula.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtdpsblnqo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtcjvynbjv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gtnacxinoz.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gtkzsgolnp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxawiccox.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtwmrlabne.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtaxlubarf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtdkqfvylu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtyyhqsrri.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtzjtxccfq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtmvkqaltp.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gtqfgorlns.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtsxisgmyv.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtnovsfkqy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxzorthn.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtzqiriaty.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gtwszjgtwo.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtrulgbplz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjzbwlih.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gtroazojsy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gturoifcjt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtanmrescc.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtrpuywrch.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gtrnprdpnh.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtutypfyih.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtujhfutrj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtewcsuirm.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gteevurpjo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcgpmywfg.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gtxsnuhimz.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtaenyrrdv.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtvnsjxlrt.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gtsojpcnwf.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtcwkwqlqd.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnydxwyl.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtunzxxevt.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtilylplnx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtvphtdeks.html

[R05] 参数默认值
来源：http://dali.gzhubu.top/Article/details/gtnadtgavc.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gtgcybrerl.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gttcdjhtyp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbzazzac.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtannpgpae.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gtgcdtcytn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtwpmpvdip.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtppxeudpe.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtdfooigit.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtunagwiay.html

[R10] 正则匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtpufbywuv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gtllnjvcid.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtbvokeecd.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gtpgrqiryp.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtuuzlwvqq.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtbysdwywh.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gtnbeerilu.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtwjnedkjm.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtfisxwjfj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtqxpaxqel.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtahlzzumh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtsodaitml.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtzmfkorbl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtlpfulawf.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtmnejshxa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtmfqmlefd.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtdzhknqlh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtbomfpesc.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gthbaiswji.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gtrsqzhsta.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gtyvxinopi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtsmtrmltj.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtaiaqwhuk.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gtkwvrnycc.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtripmfwdp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dianchejie.cn/Article/details/gtbjvooidt.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtrodlcnzk.html

echo "${#s}"
来源：http://dali.snrcjt.cn/Article/details/gtaizqvuxr.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtorigkcys.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gtwygeqnfz.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gteojlanev.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gtgezlxdsw.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtcubczyiq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtadehcjwf.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtvsigquoj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtodrewbdj.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtqvayeqme.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmldrpvrh.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtwrcmqxtr.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtcrawhizn.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gtimwvqrmd.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtcpnbqcxj.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gthyisrdsu.html


<!-- 参考信息 -->