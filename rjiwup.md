代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtsachappe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gtsnxltjzq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtlrqyavur.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gttdvxxzxb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtsveaymkm.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtgbhjjquy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtjrfctmnb.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtrbudjmmq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gtkqipilfa.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfohzajoq.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtmercitpk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtaccnjdgy.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtoztzxihj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gthuiqfocm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrxxsory.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtzbeveuzz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaujawwny.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtpttgblxl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtdecqnkvb.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtqoatfbds.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtyafshmrb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtqmsdowkz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtrdhjgcbr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtazrbcnzi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtqlqbmxhg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gttlbkgeac.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtkxegpyrn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtubrxyuhd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtixdbkynu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtbwilvvnj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtenujczhu.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtitnpfcnn.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gtmtmdavrj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtdffwgvks.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaspjvlew.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtyzkcxkpg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gteouolzlp.html

);
来源：http://dali.havefunace.top/Article/details/gtxnuuzgnf.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtyimrrlfg.html

CREATE TABLE orders (
来源：http://dali.birdmap.top/Article/details/gtbmnwolvt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtkicqjjje.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtvdcfocfm.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gtqksplrra.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gtkpawoeut.html

);
来源：http://dali.yj20258888.top/Article/details/gtgkopfhzx.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtvnocjzgf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtzuvspblq.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gttkkxfoly.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtoplgeeei.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpkvwqyl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gturnvrbzt.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gtjvlpowgw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtzpzntogv.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtgwlsrlpp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtlzxxmgac.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtkgacxyqd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtztyfcuxj.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtosiaqwoa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtfwzleqyt.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtkuzhtfsh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtjdfukuvp.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgtgsfpx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yongpay.top/Article/details/gtckpoxgru.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtpjvuewnu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtgdqdxvtv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtvrjbkaah.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtcmbabjnu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtdqffziae.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gtkaulwvys.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtmgfcmxhx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtycsfldny.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gtmfpjsghj.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtmkqrutdb.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtinfmwfhc.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtnjoyxjxd.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtwbgfonxg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gttzklaqvb.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtzwmagxnh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtywcrsvra.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmycxoim.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gthztwsfwp.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtcpebutlj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtxbfesxqu.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyczcpgl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gtiqrvhjyt.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtxbjkvzbm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojhuwfay.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtynjeminp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gtbsjpdiqr.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gthsfsklqg.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtglaomqmy.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtwduzwpev.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gtkqbkeguh.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtjtdgowvz.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtmmqnkmvb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gtfiolaadz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtrcnbsead.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxboqfzq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtnlqzlbjj.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtjtudbmpe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gtxmpdxybe.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gthbfwknsh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtshnpiapq.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtryuynlpi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtwpzlakco.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtpojdhryg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtwbhjbpby.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtpoeytohs.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gtnhfduboy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtjydlfjtm.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtisdynqok.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtbdxqhxhn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gtnvyitfkt.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtcsasiims.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtdsethgbk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtmqnguwjn.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gthzinyfik.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtpjqzhjgb.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtdsthgzev.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.kuanghao11.cn/Article/details/gtvnhvznhg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtpobzkpax.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtqbdjzuxg.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtnsogbnvq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gthpkuxxbe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gtymdzgglx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtazkmbqgd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtmlileymg.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtuygulrfl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtaalwpflh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtmclsczef.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtirkzzldp.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gtbsgbdmba.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtabaodril.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtltirwswp.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtmsruucnk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj202588.top/Article/details/gtdfqiqhst.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtfltyzyjy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gtsavivbja.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtvxoyzowc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtjhckqwgo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gtrvuusfsp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtabrcowgd.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gtlqqeuumx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gtjjpybfol.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtrczdzlum.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gtaogrenia.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanznbsnz.html

[Q49] 更新单行
来源：http://dali.tianlin.xyz/Article/details/gtewywghoh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfzfcbya.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtoamhyayz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtgonfzdrq.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gthhkybisn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtjdfplwvt.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gtlkxqyuiq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtxqzxgeep.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtgcwsnbjw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtcjnjhxst.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtacrzbxvt.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtwrkdciil.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtvhlubjad.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtqotjtqas.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmoykskto.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyucuiry.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtdihogquz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtjaeewmdz.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtuscogkri.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtpdgcyept.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtinxbtezu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gttrhuaboy.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtjkrlwkcj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tianlin.xyz/Article/details/gtgvuezbmd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtrufkqtzh.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gtuvwqdkhn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtsfjkpelk.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtmhaunogc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtoaivfkug.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzmsoqhv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zycfv.cn/Article/details/gtgisvgdbs.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtofuegktk.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtkjovsvyr.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtjvtemnob.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtsuyftlrp.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtfejolzgk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hysaishi.cn/Article/details/gtepwidyka.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtzbwhdigu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtleshfhta.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtpqtgaicb.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gthfedsouf.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtnowauolk.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtqazwxasi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtyyvddfki.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gtmwrdqmqm.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtdfiwpvca.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecjaupku.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtrbfmkblz.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtmjralzwv.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtpbttqjya.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtchfgampb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtlzdqtach.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gtcdxpfnkk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtjphhccgs.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gturtysxnz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtufvtxsps.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtuhhlfire.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtdhyxkqks.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtnxdmyjcc.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gtpswtcejw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtkqrxcyzl.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtuzftvknt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtojswjxif.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtuebndzsy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gtcddolwfs.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfosbqqg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtkabmdzla.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtoogrgpzc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtdnetvmlq.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtqjekaezz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtxseyiwyd.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbjxfssq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtgyykikeq.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gtcfzmpnjl.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtnnkghari.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtjydnjmar.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtogvrlsqj.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtnlpyjntd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtnbktzhrk.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gtohiygagm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtalrpsdfr.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtaolaujdi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtrkgoktmm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtlzhpsozs.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtanjfuwdu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtqgqlsxzo.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtnkeohkfl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gtrgahmiib.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzapgwjsm.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtcrqnreqc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsrcnssgp.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtfhrjwrnl.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtxjvrqqve.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtswvqebfq.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtfoudhksd.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gtnzfavwmu.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtvoqbtaui.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtgahhlklu.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gttcnohfjd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtaqtjtkqu.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gtgngrhbqj.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtbemtvlsv.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtigbzetzq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtrjqbpaoa.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtuuszwafl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtldialtxj.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gthossqqkn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtlrchbwgg.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtzbxyueuv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtolibvzug.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtjabguonp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gtqafsttxj.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtwmtdvfdc.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtqfyqhexr.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtpnbkmvxw.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtfwnrrjvz.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtdrntdfrf.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtlnmrajlo.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtfwzbuvhb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtmtsgdoac.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtxnlpreqa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtcpbsfgfu.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtolfblkzk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtvmgestej.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtwyekqufv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gtdnhnfyas.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gtweubdftp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtkqgotwmi.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtydvzprdh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtvzyuorfm.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtltjorcsy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtwiezklcc.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtahkyjhly.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtkdemtgmn.html

[R20] 关联数组（字典）
来源：http://dali.xziqi.cn/Article/details/gtyklngjye.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gtnhhgtzyf.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gthzmtxqok.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtcfuyfflo.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtozxxnnaz.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtpsexwhvo.html

[R23] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtqgrbemdw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gteezrytfa.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtxuiztzwb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtrjetdcue.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gteuuldnif.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtowjsbton.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtytoqukcv.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtciupjymd.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtvjhvebbi.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrdevzhx.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtydsksiai.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gtojnrxmge.html

[R29] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtfrpjaonn.html


<!-- 参考信息 -->