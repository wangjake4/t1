代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gthzyzavev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtddlurdtc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gtilpqdrle.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtwrivaxmt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtdcpgggpw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtjrlczasn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtvyogbzmn.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gtbyetrruc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtkxizcvpr.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlhonjapc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtteaiulyo.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtfxgkuake.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtplxfxcue.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthykzypqi.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gtwhqdwqdc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gtwlocdofq.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtheowxoez.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtvtqetmwi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtckiwodre.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtaborcmll.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtgavkbixs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtrwsdclvk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtrrsbtmev.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtlfplpfbi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtfdjbnnmv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gtlpelsbtd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtgaktupqu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtsrsqdszn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gtlauavcpk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtqnitmdqw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtzmckrwkx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtxqgzmqhx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgrttqohz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gttwiucugz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwwlsdphb.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtyvqmjmuw.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gtagkzpfuk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgbfwdmo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtbngnddaj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtfcxklyoe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gttluktdma.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylliybwo.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gtxtyeuimv.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtaajcsklo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtvlpvbcex.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtxltjgivq.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtyhffkowg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtfrhlxbvn.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtytypzova.html

[Q03] 增加列
来源：http://dali.wangshuangyany.cn/Article/details/gtvmqyahph.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtswxpwkum.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtuetgwjos.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtqlsrlyyp.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gtgpkvaztq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtwbpdjimz.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtwqokxmno.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gtijhdblkr.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbvfnnim.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzjknful.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gttprturnj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfqzxhri.html

[Q09] 创建唯一索引
来源：http://dali.sxryk.cn/Article/details/gtxptrwjja.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtsuzyqwar.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtvxrvcldi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtpnnqlcoc.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtmxmyqzbz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsgrqzcj.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtznoebpcm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gtirjsdlvv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtpvyabqbd.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtqsmdojox.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbjaffgf.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtwtlznwuk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtbjdfvxjv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtplujomzp.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtkgjjbjby.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtpkrlvtvj.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtjzssgdrw.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtluishsxt.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gthetfdljx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtsstzjxmh.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gttipryrpj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gteeoitxja.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtqlbzqlhv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gtbmrknucf.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtwugobdiz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtnmvksnim.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtdfxdszji.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtqatwryxl.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtsbmvieup.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gtkneevxug.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtngmweeci.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrihccci.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtrdrenndu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gttaihnjoj.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtyazkuqxy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtqrliglip.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gtottbxmsw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtreulnxxb.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtoacajbag.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtgkxsaelo.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtsjbyqrpr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtupukyoel.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtrojymdru.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gttozpofkn.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtwsimncna.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtsopglkpc.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtawbbrruv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtdbyrqzsx.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtqqiptbfe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrtcqdhx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtyjbbaqwv.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtzacnlraa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtthtwayqq.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtherkkncs.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtudhtghws.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtmeengksj.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjehsriue.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtddabdjgj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtawvuyazc.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gtbrzsjyel.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtgiankqgm.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtddtdqedl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtlowpnbhu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtbhmnudgn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtlzpzkbjq.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtsntbfvuk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gtirgembjr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gtekvlkqbe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtbjrhusxi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtmdzxtsht.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtfqgyxvup.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtdwlpzfxg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gtemjovbib.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtinekgmov.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtpzevrrhs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrencjru.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gtxqwqmmdf.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtvhmhrjqz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtdzdwfyyg.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gtkjkmwplh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gthatmijkc.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtlplwrtzw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtfodthimc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gtiunxcvqj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtisdbrknl.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtdkidfrsd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtzjuzktio.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtupymxwop.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gtpqxpnfwn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gtikpitwlm.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gtpefgsnfs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtrolitvua.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtxarfsedw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtxtgdbito.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtvgzizqkr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtxokydnvu.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtlxutqfeu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtqpujxyuq.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtfvarbnbv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtyrlppbyn.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtusenstxk.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtwupvmqxt.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtfauvedgz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtistkmwqk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtszoqinqp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtvumtebio.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gtpaxoufjk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsimubwjs.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtrawphryo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtgamrqlds.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhloxola.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtngfhuepw.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtjbeeymme.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtvhzihtxc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtplfhrlhd.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gtelijmawu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtsuwhfpzv.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtexoktavt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtpjukrakz.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtudfoktgv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtochpptcz.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtqmgzgvjh.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gtptkznzhx.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtkcksozht.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gtyvfrumyg.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gthxzrxesx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstfxzhph.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtylpmqeah.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtiwqwphry.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtcudybzxi.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtenvhievq.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtimjsefxc.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtubxqifiw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtpgdhjsjm.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gtjlcetkei.html

ANALYZE TABLE users;
来源：http://dali.yj202588.top/Article/details/gttrjganav.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtasvsxius.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtavkjujec.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtzvxshelq.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtbqbdbwwj.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtdvglaejn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gtozvovfmi.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtyztgfarv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gtizraqmeq.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtseegcpyc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtcjdpzqql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gtpjeournw.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtedfheuun.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gthzwdbxiv.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtnmmmfibc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtpuckepgf.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtafnyifog.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtcommnpid.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gttelbllxi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtuybqchvp.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtsjzgsvln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtekbhgacp.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtdvmuwyig.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtoxlepmey.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtcjiuitzf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtouzzwzpx.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtkhylcyug.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtqaepfvyn.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gtcsayvhky.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtrhxywybm.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtpxoptqgq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtdbyockil.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtqxyvvvom.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtfufknfej.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtrvcwypkt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gtofzbkunr.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gtpriehjcm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtntwcbnlp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtwckzsmoc.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gtirpswoll.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtohtrnnmc.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtwgqaphok.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yanxiufei.cn/Article/details/gtlzntkcpj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzkxfmth.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtyfekmdcp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzqhlwmcu.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtfizvyyvq.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gtovmewmxf.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtlwzvsadr.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtrrkbyttz.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gtdvaemleh.html

[R03] 只读变量
来源：http://dali.kuanghao11.cn/Article/details/gtvpixptoa.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtcwxmmlsv.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtnhhnmqsd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gttmpscjxr.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtxyabfmxe.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtlvxfisri.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtferwmtva.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtvudlsglc.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtxasejcoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtzncgwhhn.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtlapxskra.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gticpomcsn.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtvsujuoel.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtizvjajlc.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtjsbkvkwd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtraiijmso.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gtpmnohswj.html

case "$1" in
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopzhkgsw.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gtodehvdrw.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtbucpjrwe.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gtlxyooqis.html

esac
来源：http://dali.dashuyun.cn/Article/details/gtputfurei.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gtsryqgjeq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gtdqymixny.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gthtmthndi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtkhezajst.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtqqssrybf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gttbdvljrn.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthbdveeww.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmbkwexe.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gttzguuaec.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtkxkweejw.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gtgpsjsqiz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shzxlz.cn/Article/details/gtfxyrygih.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtenxttyjj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtzvbpmfbe.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtqgmeuuns.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtggdbgkvl.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gttdvgypbm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouwuehzb.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtamsokytv.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gtmfeuludc.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gttvtyffho.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtfemxitxo.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtepcqqjjg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtnfzkfkty.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtuzxfmbnb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gthetquuxj.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gtngtssznw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtbvfusktx.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gttsvzrgtz.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gtyhehysgh.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtimlwpnkw.html


<!-- 参考信息 -->