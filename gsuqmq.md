代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtddpnalje.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtoeqovrlj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gtdunmeewi.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtnyycronc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtywdutnqc.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtujhkzqet.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gttyswixbf.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtmwtjvnie.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtgzwsjgxy.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrfvcsrsx.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gtuomileio.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gteadeizdf.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gthbuecxkm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtedxmcogt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtaqcsaxws.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtofdbuyua.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtbyiucqhz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtqvoimycr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtjvenoybr.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtyewvseeo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtwqxbrddn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtaqbjniee.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtfjpjvpfo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqfomrip.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtzopzxwbf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtxjwxlfjv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsodqmrml.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gtwmmpejpd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtngylaxqv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtlmrcrngy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlzcsmxuz.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtipffkoki.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gtghspgewi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtgxzhtowv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtonadtqcf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtcjwlhvym.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtdqwcmsvn.html

);
来源：http://dali.wangdashe.top/Article/details/gtrkmbyllf.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gthvwzncot.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtadtqifnn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtkjdmpsmj.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtufxfehkl.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtwmcmyvpf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtaevewciu.html

);
来源：http://dali.nanxinkj.top/Article/details/gtadpqbuew.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftesomhn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtqhrzbapd.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtsnzwnyqp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtjufjbelx.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtqgpnijjm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtgdkcfanj.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtqkiwgxod.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gteyyhaigj.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdtqguyq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gtfnlrjzdy.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gticuehggj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtefxnjhhu.html

[Q09] 创建唯一索引
来源：http://dali.daria6918.cn/Article/details/gtkadmccga.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gteaamkjud.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmatmlrs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtrdvlifsv.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtjehjlhdu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gteiritjme.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxncrmhxa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtvqodksan.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtavyrttkc.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtnwgcodgj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfromfbiq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtmebvvhvj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gtfysvwpxy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtphmycrce.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtesfclpju.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gtqoqakasf.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtwbjytrfi.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwvoknpfi.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjzuajea.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtkxynycmw.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtmpskirty.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gteywyrjok.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtwwgzhdzz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtuohxusen.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtstcsswfh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtrzhcbxlo.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtmdrzqaoe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorruniyz.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gtaagkdvwh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtuzwahbaw.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gtusxtrqxf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtsdziqypp.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtlypxupbs.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtpeapbjou.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtezwtnhqf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gthuiiiayl.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwplxjwg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiuepqgv.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gthloojvph.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtnjbmyzef.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gthrnizjif.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtlqlamdmj.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtiuteapjo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtrmxboccs.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtpuoocyxw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtrwlxaava.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gtdhvknyha.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiifffmb.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpabiqbq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqlbfpra.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtqyauigvg.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtrrgqmzpn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gtrilpgctn.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtpxxuxtmj.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtxrivjpcb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtljpkcomb.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtaesuzqdg.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtqjzoczix.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtqlaaieiu.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtofdjprgn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtgojvtzts.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtefqnyzah.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtimcppnum.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gttpkgkhsf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gtfqxcrmpz.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtsizyppdu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtxiypgeyy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtbggwkwfw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gtaiqkdvoq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtzwifmnat.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gtxojsakhn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gttdmcczhg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtinxiwboa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gteltnjfzl.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtmeqpmhcj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtidhkazzz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtckutzwkh.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gtaduzdwkk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gthcundqnf.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtbcrzqnhf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtneelexba.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtlowfgugu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtoladcdny.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvfydjtu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtgrweqqzb.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gtkqrzksgf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtykefnvgn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtjtqyiydt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtxqjvxzww.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtknncbejq.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtpzxrvqkp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtdifgsllc.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtqfrzblpl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtrdvtnila.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiytrxst.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtrfcwfwhd.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtzcrgmvqq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtpnwnawzq.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtwaoxrffu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtpeubwknx.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gtwiigpiez.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gtofgiymid.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtfnkrookm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtozflseva.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtgysybxgy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtncvudpme.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtmdndbyql.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbsujwwju.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gtnhglllpj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtftftmjro.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gttgxbysnk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gteawansdq.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gtxvpguajb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gthderrina.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtaupyzbvu.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkscbnipx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtaldvkdtj.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtxcegryny.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtueppyytr.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gtvicsossj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtiwgpikjh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtcmmijqph.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtskczzcvh.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtexcahknd.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtrgeraalm.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gtwqogevsr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gteeevsswf.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtxkimfobu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtydjneoee.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtjactdcyg.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gthekavook.html

ROLLBACK TO sp1;
来源：http://dali.yj20258888.top/Article/details/gtefsvzogd.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaqkekhf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtbzkbgbra.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtnzyjvnws.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtyrezakay.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gtduaqxynx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtmiejxjjw.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtsjrlavxe.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtdwpyvnmg.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtgnfegkub.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtmxltptes.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtvdbdsylo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtmwreazej.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtsbacvhim.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtawppspcw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtafgdziyf.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gtpbhyavsi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.bjfxy.top/Article/details/gtvgnfdswr.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtfjfqptmt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gtslqfxbfb.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqkzopae.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtyezlzbug.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtzyfzsjre.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtwibzqhrx.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtpfsofswl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.birdmap.top/Article/details/gtwkslhmjp.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtgmegwroh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtdupfriis.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtpdsalcxg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtzcdzewrp.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtknsjmzvh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gthqwwnydu.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtxbjqhkif.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnvwgmoab.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gttweuzwqf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtjlkguimk.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtddatdyme.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gtntxvddkp.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfpwqvza.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gteafrlehx.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gtzzqltbgd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yangfankeji.com/Article/details/gtoqqrwjsz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtyyjwcysd.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtwjifivik.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtijnkbukb.html

[Q90] 生成序号列
来源：http://dali.jyoumei.cn/Article/details/gtdqyfmdtw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gtoqsbeetx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbfgtebpx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gtxnwgpmus.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcnpduqxe.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdkrknhj.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtgrrkhajx.html

set -euo pipefail
来源：http://dali.ivvv.top/Article/details/gtgyimpnfk.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gtmkmzumhz.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gthnqagayy.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtwettezjj.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gtsteqrryn.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtfrmhvzve.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gthyingosd.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gtoytoikmc.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtdpoduptw.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gtsuwrhojs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnndtjjck.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtiqsigacy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gteqznsfic.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtoqaborcl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtyragczzh.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtbxzrqqsc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gtxkrsvefk.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtbipvakwt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtwnsuyktu.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gtoippmjop.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtvuyayagu.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gtpvqqvzmr.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtzmowowlz.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gthiofwnht.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwthglqch.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtowhudsft.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtyevckzcv.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gthwxffwab.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtkoqrstqw.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtjvbbomrz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtwlislvib.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtdvjztusg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gtudvximnv.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtledkzzlk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtiiobhksu.html

[R17] 数组定义与取值
来源：http://dali.cqqwz.cn/Article/details/gtvokfscgz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gtpwukkzdh.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtakqjkppq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtxeiazocf.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtaddijsvz.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtojubwvje.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtxdermqhb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtvbpsyemh.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtnbtavpoa.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtqtodddme.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtbjmcqxiv.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtletjkhcg.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtkpqfwzrm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gtwmhujyna.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gttfyvkvkn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtifogkfui.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gteejygheg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtbritjuph.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtvenoadhv.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gtwvkszhic.html

[R27] 算术展开
来源：http://dali.nanxuanxn.top/Article/details/gtvhzrpzrd.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gtcythkggg.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gtlzrtjvxg.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtwhmlmhmo.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtwdgpunha.html


<!-- 参考信息 -->