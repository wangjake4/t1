代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtngjriaor.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gttvogjcnr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gttpnyxsco.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gthsdyrzru.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtksfuandf.html

Go:   len(arr);  len(m)
来源：http://dali.andypj.xyz/Article/details/gtdrbnmjub.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtwiymcjys.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtcfvwymql.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfmfujlo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtjlltnqyg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtwzhemnbx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtcarhpzwg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtmvsmytog.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtjqviuhfd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtemkmzmqj.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtpklldtyz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gteotddlom.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklgjdkyr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtqfysdvqy.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtverytykb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtqlmpvjze.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtztgfwhku.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtkwpidmqr.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnxsdnjgy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gtkkdovogr.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtgubzyits.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtxzeysxcd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtodptiuqg.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtcsryhrsf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtjjhihxtw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtwkduzqdp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtijnwnmjg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttenvoxby.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtbysmkppb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtfcnxixvl.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtmjferssm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtilpiswpr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtxffqmguj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtlakonolg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtjacrvkmr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtovyxfpnc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtykyffwkt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtrpaazxuc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtlxxlztij.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfulztrmh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlozeqis.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtroaizkgb.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtxtnrucon.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtzgbrkibb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqmxmcnb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtpozmveyl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtctcnupuy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtluvfpjjg.html

);
来源：http://dali.jqgfzy.top/Article/details/gtbqjxlmfc.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtozbwcuqk.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gtnmwesaei.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtszumjqel.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtlwhenoap.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtcpqozgpq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtdjhboniy.html

);
来源：http://dali.shzxlz.cn/Article/details/gttgxjqqzs.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gtzluabexb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtqhubfwdk.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtonhlysop.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtirxqwqwd.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtfqobgvil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtaaxixqwr.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtaatzwcwb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtbynkdnby.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtxzlaulib.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtcybdetlq.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtbeyzxjis.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtmwwwxgfu.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtomeekydb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtvanlappg.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtimwsceoj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtbqwqybtm.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gtmvjyoomb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtpdyxucsv.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gtzaodjktk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtcggixlug.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gtzrkponzj.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtionjztgj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtgjgldwyg.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gteibrlbnd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtvzpjoqmc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gttlvptvkh.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscquxuxu.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtsmexknee.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtgikhgomd.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gtyzjxvdsv.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtasnygtoa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gteucfbjnl.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gteekmcisy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gtevfdorcv.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtgjxdqhmf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtnlsgqwfp.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gthbureyqy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtgaknzwmx.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtjlactfzi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gthkysepyh.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtwhqgknli.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtyfdvirgd.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtrotijtpi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtztdhygdy.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gtwsqhpwrs.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gtarnfhxiw.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtqwwuuxrw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtfnzspert.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtrafhxdog.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtwnjujkpx.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtgeidgfle.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtzeouxolx.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutppysiq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtakwzywus.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtsxatgkin.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtxgzqvomi.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtspjyzrym.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtzerbiawv.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgavgkirf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gterhigzok.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtswucdszo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtmrdqtkgh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gthdqphbqf.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtlavnlaag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtupaanlou.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtgiglhoys.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsknnfvs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtskwqnefy.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtuveuhfkm.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gtxbmrycgv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtebgfvuex.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gthhimsklt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtornbivyb.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gtecefjrxs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtdxmhdwcq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtswxrpkbv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtlerbadjf.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gtwkziztqn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gthjhnwxcy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtqmgidtuh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtdmcsogba.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gtdfryopdh.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gtixtkelbh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtvishagsv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtkdcffsmq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtxlyjvylp.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtdhopxxol.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtorngiono.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjttsvoxw.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gtutgpiwqd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtzuljyjtm.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gthkjhbpmz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtgdisyhbc.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtvwbnceow.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtisnqketc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtutqsxhio.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtwptkqtwl.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtkqufeomz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtrsncfsxb.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtabaejmms.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtcimxhkpk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gtftqgloun.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswtjufgg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtzqmyzbbq.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtnwmbmbhn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gthhqsbtaz.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtlqowkxrg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtwrvpmvap.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtkxjykfjh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtlxbvwxsy.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtplgpfqcg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtncmsogza.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtzbivezds.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtysnefpsc.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gtwrtahmtv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtugrkgwym.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtkijlfpwz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtbmzvmgzn.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gttabmefyg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtkahxbkqh.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtetjzwyqf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gtzonkhxbc.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gtwpdunmhs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtdfyjfuuk.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtsnamymkn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgwbemxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtjoenvaca.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtqjsqudwf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtxubmfich.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtpldekvad.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtoztpajmu.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtcsgylfql.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtvrbfviaj.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtbrzmszcw.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtuhemkwhz.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtrxhrdnby.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtsfftdeie.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtjwtdhyhh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtttxsvaek.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtreenfyhe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gthsuclnhg.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gtreqnpsej.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gtvzixgvzo.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtbyefrnaf.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtzqqcbile.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtonhcyrio.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcbagiwo.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtjxkjasgx.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gtuumdxxnb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtcfmykznh.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtvdmojldf.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gticwjbqjw.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtumwrbqyp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtqyvdgiyj.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtkzearhee.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtptckuzmt.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyikafcvb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtljmvemfs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtrvzapwky.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gtgwssdnvl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtmokdtuxb.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtzrahlptp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gtupmduawm.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gttfnfrvcn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtmmseqtgl.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gthaicvabs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtdwindruu.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtgrrminjr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtzmwhzvfp.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtigbwbxyx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtzymrqgcn.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtmklmjcbd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtgiwrqrnd.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtmrvzvyoz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvxyzcoky.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtgulmtxzy.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtlzcnlkpd.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtiohayvok.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcbzbunc.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtwokeohrr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtdijmljhb.html

[Q87] JSON 字段做条件
来源：http://dali.guannengcc.top/Article/details/gtmozsszgh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtxweyckdp.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gttlhkjnlt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtkmfxhptq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtkhowxogi.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtiuxclsqs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.9152youxi.cn/Article/details/gtdvtncfcn.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtqmmxhbde.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtbxjuqowo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbwxmztjl.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtfymsztxf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtttsjrdfr.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtpntceayq.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtonlqgswp.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gtsrgbtxpd.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtyohrqkti.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtsccbluoh.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtkkrnpfza.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gtovxuaejh.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gtlypymozk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gturztsflp.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtoxgxziji.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gtnlfuipbr.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtjjepwxcc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtmkghzvwc.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtuvkiifwu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtrtdqfztp.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtgkojezdl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtligyqgfy.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkubczxib.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daria6918.cn/Article/details/gtremmytrj.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtuqqixeld.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyzsmbgl.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtyxupfjdv.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtsnvbiows.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtbktmuuts.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtqqzwgamr.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtabnvhspz.html

esac
来源：http://dali.daxiang520.top/Article/details/gtnhqcfieh.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtoppfgoxh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtlxczggrg.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtybdigalu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtmmifxwjg.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtibsigjlt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtfelnemog.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtqcipgnhh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtsicschpp.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtzkvawyrx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtduyobhbr.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtojefarkv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtxksdryac.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtxqvgdxpy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gteupmmstt.html

[R19] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqwgzrvd.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtnupgthhb.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gtqleuxber.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtfzggooav.html

[R21] 字符串长度
来源：http://dali.redwolf501.top/Article/details/gtokitpnsr.html


<!-- 参考信息 -->