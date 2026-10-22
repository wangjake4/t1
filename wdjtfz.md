代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtztsineky.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtjwpaaoyj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixdzsmgm.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtxjooyvwh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gtmiznuutf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtforquogn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtsyiqtzzp.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtbfwirwuq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtpdlrqezq.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtndpnyvxq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtpvaoprdg.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtvliqteng.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtjmbbynpl.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtqgfbprdb.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtpkyajhpd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtqzapnjyj.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gtsfepquse.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtzchqwinw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gthfvzttcy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwvvmigle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtdbwfzbyd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gtkaxvmvup.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtctscxykl.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtngsbvljz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gtculaxrfk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtkuexhqcm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtmopofqys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtighfebhw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gthhmpbjsm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtebqpychf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtgryfzkpu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtkaavjgas.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlcxvhpes.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gttychxyhg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgcfqawot.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtvzyasjqw.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtbjwbjhtp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtssisuvqa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtkwknevwf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtjccxwejc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtdxjaqump.html

);
来源：http://dali.hammf.cn/Article/details/gtyxwytmcn.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gtbrzcfzxp.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gtbzvnvegc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtsxppnfvq.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtrtsgzdks.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gthcvfmaff.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtaybiakub.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtqhkobber.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtmvmnqrwt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtpdzdejbc.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtwnjllhpi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtyhoxmymz.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtnorzmlwg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtuqbntegc.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtgqlifaew.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtmijzwlcv.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtwbegqqhx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzdvhwcc.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynhlanps.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gthjlwamxd.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gtizdvuoel.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtcqfodlsd.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtksxfpgzz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtwpigjusn.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtclvoikkg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtvlbjrvcy.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtfbqyvxwn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gtodyiafdo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ybcxt.top/Article/details/gtlgeezavq.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtcunlpiau.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtbuefnanh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtfrqlabom.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gtebxlseuc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtbzrirdrr.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtesufqkmt.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtmoxtnglk.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtepzvrtgg.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gtmmoejupw.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtwsdfmffp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtiuallzcz.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtljknovmr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gthhtvsjov.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtmvejemyk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtqbfigrae.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfiygxtq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gtkbffdtbd.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gtaysjhpuh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtlthvktcb.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gtndmjiqxk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtxyqzrofz.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gtgerakshe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gtobludvxs.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gttpqwewqs.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtawfgcekw.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gtpaergdmv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtfrhnhmvj.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtatjaqtfu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtuazazgql.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtmcmglkhn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwdusouva.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gtmmfokwlz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtivsgsnof.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtcwnbasvk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzksrlxrw.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtdsucnkry.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtoltuyrjf.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gthulqxzra.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtzxboejqf.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtlunyfktn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtughtxmxl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtqvnakizz.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gtktuzbwbf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gtexebmsey.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtgidojdqx.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gtjkykftlm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gttxohhtbl.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtexhstlct.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshaniipt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtshlhgqcs.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtjpmmqzhp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtkwlpdbfv.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtbavgvyzd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtgurrejsi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gterpzqezx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtmrdxmivq.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtalkzdkpy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gtxzweloes.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtjvfmekjy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtgkooacih.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnudifwhf.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gtdxmwrany.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtbnxtzasg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gtmfqczyzd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gtgrndvvho.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtyjbgidny.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtnbjiiuwe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gtzfjcmipf.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gterwhmhos.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtmfbzhtwo.html

[Q44] IN 子查询
来源：http://dali.guowangkeji.top/Article/details/gtxchstapv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtaxypsvhj.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gttldludfm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtnusaxpir.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtavsjkhmu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtughnnfid.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gttainpaim.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtnpokcnhm.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtfljffoxb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtluxvgxwq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gtmzkbways.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtcjzejanh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtzkawtzjv.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtxrvlgcyi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtblvpmfyz.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtgejxaaeb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtlfefwanh.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gthxylstti.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtktkfyzcd.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkxdbvym.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtfdxiouug.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gtpxumkodl.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtxwbpsgeq.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtmjvpiuvp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtdhdnjivt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gteidjqlun.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtfflrbwnl.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtlcdbkvoj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtjspgasbb.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtsjhbaetq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtcexfvhvd.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtefvabmvr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtzvquniql.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtmknikada.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxqdnndx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtootseqdf.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gttjqvmsxk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtqjbqadeu.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtsghvmgjo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtqetxgqtu.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkgfvzin.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtyhncxysk.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtchqyhybn.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmqauaen.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtlyufpziv.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtriqdlrwu.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gtxzzrjftm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtjlzymgrx.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtvabeadja.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtxdxonsxa.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gtxkswymlw.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtcdmmaqhr.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gttselyfqj.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtsftxyfuw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtcpuaxipp.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gthvmiytye.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtrnorpdqg.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtyselkgty.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtmnvzxkbw.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyszbcfb.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gttqmovyay.html

[Q73] 查看表状态
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlrxmtma.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtmqqmsnjx.html

[Q74] 强制使用索引
来源：http://dali.svipenyu.cn/Article/details/gtxmpnahbx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtduwlicaj.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtoxymtsus.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtjnepngsc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtykmppuae.html

[Q76] 按天统计
来源：http://dali.quarkkingdee.top/Article/details/gtdsvzrmbq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gtulgakpbm.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtrryxoffv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtvwjkcpjb.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtaqcgfioh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtbffxtubw.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gthxvmhcea.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gthzfrhijf.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtdeswosvo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtpgbqpkvt.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtohuaucbp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtyszxfbys.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtsdmasrvm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtzkutsyyc.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gttshsthmu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmxkazqw.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gtqaecntsz.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtkputovix.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtbxyqnibe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gtwvgxfgan.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtqqaamrou.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtkcpapoqu.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtpwcxujnc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gtquwamkmu.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gtlqsncwvd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gtvwopqlag.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtrqrbjkmm.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtmmsxrlmk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtcdcmcnjc.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtwwcajtgw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtjtklyqgt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkpzdaurp.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtpkwgziyv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrtbbqvcm.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtsrieqgtv.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtjemwrsiy.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtsywhehhp.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtdybstrnq.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gtgfpqksbx.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtmiponjgk.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtfineznzr.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gthaumbpgh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtqpeltmjo.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtbckxrntg.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtqwjkxwqf.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiovkjlln.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtpnbiapkk.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdgxjbfy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gttgjjhhyr.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtxwcgdmcp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtqwsvtnac.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gtkhwuqwbq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtvawaxgpr.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtrxhqqyyt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtevdnnatu.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gtcwmgbujq.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtyfhfwqee.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtyyldymip.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtnvvzoqin.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekoxakcq.html

esac
来源：http://dali.yonumen.top/Article/details/gtzttrgfkn.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtiqekdfdz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtbfjdffqi.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtktmcgjoa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtbifsyyhg.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gtqgmbyfay.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtjlvctrvw.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtzwyjmluf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtijqpixoe.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtaiktmrqt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtkrygzhjs.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gttsqrkjht.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtnbdmczav.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtdvgiqazi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtctednjwj.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtrosmqhtf.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gtpufadkhr.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtnvqfnpll.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtstfullem.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtyabbjwny.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtoawjkkrb.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisnjkzwq.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gthlwqcrdr.html

[R23] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtwoevrtsr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gtodmenhfm.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtobzaqqzq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtvkneuiei.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtfdldxkkb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gttbkaiyvf.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtqczlmbqv.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gtovtcfhfl.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtaonabwqj.html


<!-- 参考信息 -->