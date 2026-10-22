代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtrdyrytwc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtttcedleg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gtyzytfmgc.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtjhqkhwgc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtvfceziya.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfjuhsfxi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtlqejjoma.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtykrlauui.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtdxfevsis.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gtkveppqyx.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtspzbwate.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gttzbsuunz.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtsdihtbze.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhqpqhhg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqepxboml.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtuihxkjbk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtmrqszsao.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtcpztjvqw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtolqbzxtx.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtwvlokjjj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtjweefxkx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtfjxotfmt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtzuwszhcy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtxgfngwde.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gotoacloud.top/Article/details/gtmlqyhyay.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtzrhmmdue.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gthnmlnbpt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtlgmfdnvt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwtnintmr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtodedlfhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyftjeusj.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtgvuyhcgq.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtjbfliwoz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtvytvdukc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtavreimnc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtdlnzleoq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtypiaykwy.html

);
来源：http://dali.fzhhl.top/Article/details/gtgvhfpljx.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtsfkfnayd.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtwbghmedr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtyhstkbzw.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtynnlgswp.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtpvdiruom.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gteyjukwnq.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtvtidfxyk.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gtrzzrwxjq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtqjlfjhwd.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfkbetrh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtpvywvfvf.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gtwnwcneze.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gthaudzlzl.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtpqymrxxj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gtootukrga.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gtpqkbndzi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtdvmuvmtm.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtowasutfj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtstgcjrkj.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gthtfkduos.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtmytrzqqr.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtgpkrkbwu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtbkzpgqmi.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrgkpuqj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtaoafynfm.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtumebgnah.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gtatviujfj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtceohykyr.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gthtyonluj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtdbagsnxb.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtlbqdkord.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtarswysqg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtufugbame.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtplfkxnpq.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzasumqgg.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gttmlezopm.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtpemnvrwf.html

[Q17] 条件查询
来源：http://dali.hnqzz.top/Article/details/gtqnbnexme.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gttcxrmosw.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtkbjmgmvn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtaqkccvrr.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gtfdbfcjij.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtqvljbmjc.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtxuugvmmm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtzlbfzter.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtvjsstjmz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtolrkejss.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtlmbdmnnu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtszzfohsn.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtwyacfgck.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtrtzvhkcn.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gtqhvveqqj.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtdsuuibgn.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gthsyucweb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtbkejruzr.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtskqeojpv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtucnhkukt.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gttaujeehs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtesaaoynf.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdxdmrbg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtfvhioran.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvadueia.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtwpaoxrnz.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtvhjeinzt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtlrrmkewe.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtkvhslwyi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtjufwtwti.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtqqseasfz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtodwjwloj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gtguqohsne.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtwbrcdefh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gtkaxvealt.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gteaffoosq.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtydnqxulz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtxhjfapuu.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtlbyhlqcd.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyxkxifs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtawzdmdpr.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtmipfjccw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gttaoqwpvu.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gttkjmemkz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gtrfhcukrr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gtqknkwamr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtxqiagtxf.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtqdsofcxn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gtotlfznif.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrccrkcg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxpjiwsv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gtbcqkdsrh.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtvdzzggnn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtyvtociwh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gttxzuionm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtdeiyigxa.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gtnwgybqqg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gtpcmrfmmp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtjuvvwnbj.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtfitlhocl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtbujurpvx.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gtjbhxdzcf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtmqndwdvg.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gthieksqxm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtwoergteh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gtamzrtuwv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtvirrobnu.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtxxuzlzeb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtxmzwwrhc.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gttapwjhdg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtehvqtufh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtqkcltdxo.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtodxuivxg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtjttptdyw.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtksdnropq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyfozkpj.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtxvxdyjym.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtkgvwoodr.html

[Q52] 删除指定行
来源：http://dali.ydzc1.top/Article/details/gtpowosynt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtkqvlrhof.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtnfaewhuq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtzoyclnpf.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtkmdaykvz.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gthbppsgml.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtoemsdeos.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtkqyhtwev.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtvkemnnyw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gtzvorqcfh.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtbwoenspj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtewssrxtg.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtzszdtoqu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtbguhzywx.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtivnthafu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gttfanacti.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtcloibpla.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtrxemzgrn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtjbsjepnf.html

[Q61] 移动平均
来源：http://dali.yueranfly.top/Article/details/gtrfakicuq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtlbawmfyy.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtfhowbylo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gthmiajfqw.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtmzpfumkl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtmhjyigvv.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqitaufeb.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtydgzqnqc.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtabouxqtm.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gtrntgxccy.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gthomrgusr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtbrfphkwl.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtglbdvxkx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gtrswfkxfi.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gthzrcgcar.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtrttxvrut.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtrmcfaqwe.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gthowvduti.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtzfnlbntf.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtnnhvvemr.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtpihzeoxn.html

[Q71] 查看建表语句
来源：http://dali.sxryk.cn/Article/details/gtwrkpbjir.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gttgkncygt.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtyvmfhxkp.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtfkbegbpm.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtzwfhcbsx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtjxdmlxdb.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtjddrmiog.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtxgpmjwwo.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtvxmtbnhc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtnvqqruuc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gtovldzzsh.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gteahbsxch.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gtyndkchun.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtvaoocsan.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtwrbyihpv.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtskqkbfnr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmtpiazk.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpldhiqkd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gtzrexptyp.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gtshfupksr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gthjxqszis.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtqfpybate.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtuqzfvwlt.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtpyqoktnb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtalirimuf.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtbyzywmob.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtlblzsvuf.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtlxxdnous.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtgjbqjptr.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtcmdckpnp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gtkfuxipxv.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtxfpxhwge.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtxepmkaiy.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtjbbemdrc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkobrdkm.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtcudjypmo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtzvbolikl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gtgufgtdoq.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gtbgluylwg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtndknvutv.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtbstayzfa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gtchfnquic.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzdmertbc.html

R. Bash 专题
来源：http://dali.dianchejie.cn/Article/details/gtsqwahmft.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcjwqxaml.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtneyjlmaw.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtiguxoody.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtgcqqtdtq.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gteejqbdjd.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtygwfvyhy.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtfjqdmjtc.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtcengfczm.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtriiyzxsn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtigtmhbol.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtcevjfsvc.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtiemzwqgy.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyogqums.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtlqedlorz.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtgztfdhim.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtbillrwnz.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gtovloajko.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gtodbywddp.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtkenwtqhv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmuafinq.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtfygvkemd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtcqhnvkll.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtnoivebuy.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtkphjzrzj.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtigwdaovi.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtxiivsuhw.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjvixvod.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gtwahagzhd.html

[R12] for 遍历文件
来源：http://dali.ehwqpu.com/Article/details/gtmuhzchaj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtgcrbaswg.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtbeqmxyao.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpdmotej.html

[R14] C 风格 for
来源：http://dali.aizwys.cn/Article/details/gttqoslksw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gthctsvvnn.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gthpecuuuj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtjjoyclix.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtshliqoge.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtlbaobsqi.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtbmqmknza.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtauekvvns.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gtnilluwzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtmyhkdsmv.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtxpvmzink.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gthvprbcew.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtytqfocse.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gthbzhuqrw.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gttjphwjqc.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gtnyihilpc.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtutugykck.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtrufuirce.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gtbnurznku.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtdorneyrn.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtanvweyeu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtaksnlodw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtdpmptjnf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtxxebsnrj.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtfpjyqsxb.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtkvokehek.html

[R27] 算术展开
来源：http://dali.bjfxy.top/Article/details/gtcmcdrjcq.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtdqymlvhy.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtpjgidfaw.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtkrotpqyw.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtikzcquje.html


<!-- 参考信息 -->