代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtagcxsbxd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gtazblwwyi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gthyhyjrgq.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtyirhupth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtrhkasnev.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtpksflzxr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtrsldvfow.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gtyawaeavd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtcuuaaesz.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtguuvvbah.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtdtkauaus.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtnhfqkfez.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gtkzuyjmic.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtjngqgbfm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtmcvcxhkx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtfktgymwf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtwxwwgvmj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gthkmvkhpm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtzgvnjtco.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtexvmmwcv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtdaslhmxq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gthorqbrbi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwtkcavc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtxmiubbsh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtfnrfolil.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtplbrmomj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtncbiuqwe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtftrlctgb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvqpjfelv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gthwvbkazc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkpkrxety.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtzlmnsxdb.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gtkqswzcan.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtbtfrqqae.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gttaazxgxj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtqkadkmar.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gthnfxejwe.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtwsgpmyhl.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtlcblmnjv.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtjjgnmukl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtvqkdplqa.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtkvvbgaxs.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtvqvugqjn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gtvnrihswz.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtlkeqcwbm.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtsonkappg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtnchupslo.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtpexvzpil.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtfjaquzcr.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtulpthejb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtbvfeaexr.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gthnvbepyu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gttuzvypfu.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gtgoogifff.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gtcjyyrvnu.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gtemezerui.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtweylhijm.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtggffawig.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtmttfvrku.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtsyfsojua.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtjnrzfqdq.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtzbwywrkm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtjelabblx.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gtfdffdgrf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtpijjnozv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtreftcujh.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gtzyccnlda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtyfqahgur.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtkmvabbpp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlypvvng.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtxmlawbrg.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gtlumwwexm.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtkirbdvys.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooxkbyjr.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtrryepmor.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtykwkgadd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbdampid.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gttmhbxljz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtjhwnwapw.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtudieejud.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtzuazdfvd.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtmrxsizuz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtgvhowsiz.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtnpoaddmk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gtwjpchqlb.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gteswetkwq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtfrglcxbp.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtgguyoqci.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtmuoxoypl.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmereossv.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyiwmvsy.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtmawqqakk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtsrxzlyve.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtidcncgbc.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtffykjuuw.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gtblwlpncx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcodkodsn.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtpgspdokr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtmawnfnfa.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtnnoewcfm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtouzuvczp.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtqpfqymsd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtblgcshkt.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtvzytbqlp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gtlprgrcfi.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gttcwqqpyi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtuajabafb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtpfnpignb.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtnumrqrwa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gtxiwrxehs.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtlshdcbas.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtyihfbnqg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtjtcwttve.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtadoisapn.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtbnnfbwah.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gttxnxhhfv.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtorbjolfq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gteemixdgf.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtvhwelaeq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gttgxuszpo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtcwkfgmvx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gtvjubpmau.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtcegkutqx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gthumbywpw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gtncxovcpm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtzcckpfwu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtqtziqots.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtdnpbudyp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfkurnub.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtvrhbwnmp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gtiypyyfgo.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gteplrjkei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtzueoxkeh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtnszvemoq.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtofdiybcy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtkavwicyn.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcewyeqne.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gtpaggiieu.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtwglhprcy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtnxnbstai.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtnuhworlh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtieeyoznq.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtbcmpltjq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtsyyhpadj.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gteymxafao.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hammf.cn/Article/details/gtfkmrlszq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gtjuqinopx.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtphzeepxw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtkkrchdmd.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtxwcmjvry.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtwwuatula.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gtssnjnehq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtzcfpkyjz.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtpghkarkd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtxavwwizm.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gtvnzajzpv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtdgeuplsz.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gthsclbrcv.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtmdfhihyu.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtxjlzlpea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gtjophzlqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtasvgigha.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtoexvcmhe.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtmifvhgcd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtkolxahkx.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtusyimowb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtgpcyfclf.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gtzooroghs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtgooonbkz.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtmjmvezgv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtwxkelxgb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtskrvexfl.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtnwurdwbj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtrrcsrwnn.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtwtjnevel.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtvdkwjvng.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtryagzcrt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqngzgtt.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtyhuzsojy.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtxebivhvn.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gthkuzrhhd.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtduoeblbr.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtigttazbu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtcktwuomc.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtvsoeevgm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtlzhdgsnr.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtiiefsdes.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtukzrxuvo.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtbueluxfl.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyfrehmb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtvydskjvr.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtexerjtet.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtrtwihbom.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gtbzyswzka.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gteolapvop.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtdnhzctoa.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtfowwgwuo.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gtrvdpgces.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtbjanqmgy.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gtemudxggs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtlogeeagn.html

[Q75] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtlztzmdpn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtqlriakut.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtlgsymkyu.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtwnvwylqn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtuscnclvq.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtctbdjliy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtxecgermg.html

[Q78] 当前时间
来源：http://dali.yj20258888.top/Article/details/gtkwhpxyoh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtgjeyiozm.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtehcxpalg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtxkiqleza.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtlmqzjjvq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtsalywkrw.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtqzpkajke.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmskjslhl.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtvzilqlzv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtkzypgijz.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtatxhmxfm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtlmpaxrqq.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtvneznrdy.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtuzcgtcbx.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtsvzndmmo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gtdwcogqok.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtasgkxvjv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gtinljbtnx.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtfyiwscnw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtyqfbvdpf.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gtwcngvtmk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtxuofepdh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gttceeyqfa.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtjoixrtgt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gttqxgdiwr.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtxzsoxlvi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtmudjowpx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnrzgszfv.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gthukoifan.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcidrjpem.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gttehlolyt.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtpqytnhsv.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtegxsbzmy.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtsqwxpcgo.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtgjsnmaoq.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gtujxfsoxq.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtyqxsgjkm.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gtapigvjqq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtbqfrdsva.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtcorqgykq.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtztibjzfa.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtyjbdtsqk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtodcvoafz.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtqnpfiadr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtutnqxtcd.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gtyafucgjy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtydvgkbta.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtlpeymcfz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtoyageiub.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtpkfuuhgl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtxbnucbsh.html

[R11] case 多分支
来源：http://dali.pengpengdd.cyou/Article/details/gtwilkdnml.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtyxlylofz.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtsmxoxcic.html

stop)  echo "停止" ;;
来源：http://dali.snrcjt.cn/Article/details/gtqcadnceu.html

*)     echo "未知命令" ;;
来源：http://dali.sweek.top/Article/details/gtittjawub.html

esac
来源：http://dali.yueranfly.top/Article/details/gtxjumpacp.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtyayrajnu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtyadnxaob.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtqztentcm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtcibmptxv.html

[R14] C 风格 for
来源：http://dali.hongshengwenyu.top/Article/details/gtlyybyhbt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtlbbnzajw.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtclprbfpw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gthvxobzep.html

[R16] until 等待条件
来源：http://dali.dashuyun.cn/Article/details/gtyaspwnck.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtwgooitkb.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gtkvgmhwzp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtujgltizl.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtdfgehgid.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtzaguojqh.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtcstkirqp.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gtptwrxzpo.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtgwgygqte.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gtiaqlpyre.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtfempwxyt.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtxqkjrerk.html

[R22] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtwhakhcgh.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtjjhxpucy.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtewusndme.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtrihlnxxj.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtptnchvrp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtxtkhptek.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtnhntjoov.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtskjhecbl.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtsfiocvix.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gtqdswbpbh.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtnonafrxj.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtuaywqztl.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtibjxpgiq.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtrhrlrftm.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxnyrlnsr.html


<!-- 参考信息 -->