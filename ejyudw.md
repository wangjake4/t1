代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtkpghvlxv.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtkzwtdylx.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtoxouqvgw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gtklxxbesi.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtndticjew.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgouihbv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtkxmcplzd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtcoctswuh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtplvkpfxf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtygtoiggh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtaiuodkvl.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gtaonrmwph.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gttvfquhoj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gtipxvpcmq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtoyhkvblc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtoqulwrrv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gtrkjpffhq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gtheujgesy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtessgpeuq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gtlobjuibb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtevkfdbea.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtkbictgwb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvauoaqn.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtmhunpcvf.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gtyridgvjg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtzvcnrknu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvexfufsz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtcyuwjmxg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtyxreukgf.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtqufarjzf.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtrttybjdt.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gtdnwyazhl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtaolerikd.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtbrwzcnat.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtotdgdfjd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtrszhhngl.html

);
来源：http://dali.cqqwz.cn/Article/details/gtpfwwbhdj.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtkrdjwpyr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtmwpvftvq.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtjmmoaffp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtsuxulvvu.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gtgxbjswer.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmxjxfqk.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gtupydrrig.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtqrpmqqdq.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtapynsako.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gthzlufpji.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqfinjuh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtclabppku.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoepfdfhy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtxmjjrthx.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtmynkwxbz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gtuimjortu.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtxfhwsqdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqorhrol.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtfjxwabsr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gtexyfkmjz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtigzqexgn.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtfjydciof.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gttkvcgrzi.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtzyvzhivw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtrmamenrm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtruibhdyk.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gtsyglthle.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsvmazikq.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtvqttnivr.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtbpgmctri.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtyivymiaa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.meibo888.top/Article/details/gtbnmuexhe.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtmliujgmx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwhdbmtc.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtssejvxcp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtzuewocus.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gtgbupgbsn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gteegmzdll.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gtbhpjmpbl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtydtatjwb.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtgjapodau.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtbenrlhhd.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtwhpzvqyh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtafwkrdst.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtjbvatwnq.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtnhnaqfqm.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gtfscunvoi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtezkiinny.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtpazfjblv.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtdyoiyxzc.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtkxkglpim.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtspnvjjbh.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtfytutaup.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtvkefsayf.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtdpqtsmco.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gthpjwuvci.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtqsupchfy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtxjdkfyux.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtjyxtbixg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtjydytpjt.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtchyoojco.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtvvlvestz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtafvppdwj.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gtbtwqlkwk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtmfycqtcv.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gtmycsbzyi.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtvsrncjmo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtaqciszkz.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtqakmjyeu.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtmofixtrd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtqnhxpdox.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtuttwtseg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtirlirsib.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtshsxexxx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtadzdawrv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtmxfxzosk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwoyavnl.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtzgjydfub.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtszpxplyd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gtoagarxou.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtfgpwvkez.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtkjebeqkt.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtcbqsowtx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtngjqmvph.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtbxmwijhk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtsekxfgge.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtuedibufi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtyilbvrod.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtlenstvgs.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtmulfhojb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtuadxuphu.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtlslfcbga.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtpftkapll.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtxchsxnec.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtjqvrhnbr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtkrhkmlao.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtxrmxisif.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtpruzvhhm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtgpqccvfr.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtzpesszbl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtvqnnerry.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtcwaemlea.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtnrhixorv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtqcwkzqps.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtcxhqjzxy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gttppqikaf.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtvrpioxqy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gtqwqkdubw.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtxbptxwxw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtqcvlzrff.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtiybidfdo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtflhxppgk.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczjbgfpt.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gthlxsqifx.html

[Q55] 排名（并列占位）
来源：http://dali.zycfv.cn/Article/details/gtkuckkupq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gttivjlfub.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtycxakkav.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gttclfjnan.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtpowtzwqr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gtoevqivgq.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gtpewxinlz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtzsvlubqv.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtdvwpymcq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtmffkgcsu.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtxtdweccr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtkmzheews.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtwswilpce.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtpbekgwfi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtruvupsls.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gtfrcskxra.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gttorlkeyn.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gteleqkgvz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtcegwdzom.html

[Q64] 提交事务
来源：http://dali.gotoacloud.top/Article/details/gthqmxpfuo.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtqeakrxwa.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtqpkrmiin.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtqytdzzsl.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtkfxfyiwl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtaarsutqg.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gtywqjwtqo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtjuvgmmpf.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtmdczlpee.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtcxyotuaf.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtgoyrzwwv.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtpbqlqusu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gthanzlejp.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtitamkona.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gternrmfkh.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtfvhkqzjf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtilvvuehy.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtilwwnoks.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtufmqontp.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtlxdcsvfv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtituubrhz.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvrpsrkn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtwdruquac.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gthukztupi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtwmknbqcf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtjrcopayv.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtpnbuysyu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtoaofajyp.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gtpnteueed.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gtuxouggos.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gtgteicfof.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtvgtznvnp.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtzbnrylqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpryolpr.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtyrffcbvf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqdnyizmw.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtpaqgdefo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gtvntfivis.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtsjqtnxlz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnzmciyaa.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtabtkdsvr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtjxntmqsv.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtsqgprcic.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtjnnnxgda.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gthckpymug.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gtscmmaztz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gteleramum.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtplckjipc.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtpdmakzfn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtsqrhpzls.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtoemnlont.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkkqqtuo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtxaxndhep.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtbytffrnu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gtpzjsxfik.html

[Q90] 生成序号列
来源：http://dali.yuxming.cn/Article/details/gtqelhlayk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtsurkjucx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqvfjqvcl.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gteuocgcij.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgjvwfpgp.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtwtpdnjvn.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtkwnscckn.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtoueptewn.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtolmwgnai.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gtffbhpccn.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtamuwgkde.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtspahaqtt.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtmdfdpoom.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkvgrvbh.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtvltoleij.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtgfrhfjzx.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtjprxzrfd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtxocavxye.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtwvmlwkno.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gtnjlrfahr.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtgbywkiuf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtelxpmank.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtccvvnocq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtupdgedqd.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtmfadvnbt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gticwhzdch.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtxdzplaps.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbtolxkk.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gthhkkwbme.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvwcuydn.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjqbwrnn.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtsmxulmgq.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtszlbnyfy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtlnopiliu.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtssqzyscn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gtyjwjyipo.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtolgaezns.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtzdhynukh.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuncwaljo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtiniliqza.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtxvkhknyl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtvdbpqszz.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gteagqvhwd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtbgdwthgv.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gttdusirrl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtwttestoh.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtcxzocvyv.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtkirmtkco.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gtazquuupd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtxsvajfga.html

[R21] 字符串长度
来源：http://dali.hnqzz.top/Article/details/gtrfjdaejd.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtgkswtdji.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtlviojcmo.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtvjwiymlx.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtnjzmdomv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtddsjgelc.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtxiqgjfbd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjtgcvpv.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gtzrcsyzbu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gteyeeyzqk.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtcirkmdye.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtsfnuldxf.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtwdeyoimi.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtfkmoxmpy.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtmqwizekx.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtdyjqvhpz.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtbquzgknv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtfautlvdv.html

[R30] 函数返回状态码
来源：http://dali.cqqwz.cn/Article/details/gtbbxtfjgz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shzxlz.cn/Article/details/gtaryzuocs.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtcquheqdw.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtcqnkjpdt.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtkmjfcmkf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtibqprvdu.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsowtsfnk.html


<!-- 参考信息 -->