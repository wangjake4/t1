代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gt2hvgimvym.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2hglredct.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gt2hzwhmtks.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gt2ausingky.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2kixmmktd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahxpfqfh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2jluhcspt.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gt2xwcgjlyg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2leqgurbb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gt2qiodndde.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2itamafof.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2vowsuvnr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykxlzdtz.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjkuolgs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2khtaugjv.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gt2ugnbpcii.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gt2jrodplui.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gt2mkailyuy.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2muoodaat.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gt2vqzxpjtk.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikklwsun.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2osrukddx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2ibexoovf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tspbwbnb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gt2maanllfk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gt2elkhvatw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gt2hbpbypkq.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gt2oivwcegk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2yhroijef.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2rrjpdbqj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwyzmudo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2sxaunoja.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gt2euejtwax.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gt2hgqbrlis.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdgcqdwb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gt2gwuosjdm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yhreeqrr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gt2umdjsrtl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2uynbrsvm.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2otxtaqjl.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkaqolim.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gt2tvpaaagc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gt2reykraxs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gt2jrxszdii.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2xapieimq.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2nvaivlco.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gt2xcruonfa.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gt2pgckeylw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2arfoyxcc.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2plrbukmx.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gt2umfkakcr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2njfkdsof.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2jzhdjrhg.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2fruatkil.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gt2ulvgdycc.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfptqzhq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2qdyamvaj.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gt2snrfnsrf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gt2lfcpvtdb.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2unkxgdwg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gt2mxeblxer.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gt2wxpxhgex.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uknditrv.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttjfnrpy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gt2vqgszopz.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gt2kfvqldlj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2nwuvozbm.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gt2aoedvozr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2stwysxzl.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gt2dwvoyvdn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2agvfxrfo.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgvvwceg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gt2ktjonftr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ybcxt.top/Article/details/gt2rnhnpwss.html

[Q13] 忽略重复插入
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcgknhip.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttxvzphi.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gt2tmpqwynb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2hfdioxjj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsenwkkk.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gt2gfbnjctw.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2nsrtoilq.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gt2cxtztgoo.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrmceapd.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gt2mzjabyyt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2iyrrtrfg.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gt2qgpgtjkj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gt2gtcagfmt.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gt2uqwbnhdl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gt2qdejlidf.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2dyjbmubm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gt2etcbnwah.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gt2aezssiga.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2wdajduqv.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gt2wsmqagqq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfkqrztj.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gt2xexbqjsc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gt2xmuqpudh.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2knrialdw.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2owqwcbtd.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2fdsqqewz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2tqmxmfyp.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2ygbzhtpo.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2iokxakbh.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gt2pvvdjauj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2uxsfstrr.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gt2zxdoznrc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2mqxpuaob.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gt2spwtqdfl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2osoxdflq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnnrowc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxvkytrg.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gt2fixwrsnx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gt2imdprdrx.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2ouihcvtd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpgwmpdr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwtfaitw.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2dwglakog.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gt2cmfjwukx.html

[Q34] 每组取第一条
来源：http://dali.birdmap.top/Article/details/gt2yatncemg.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gt2nzlngbwy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gt2egezncdv.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2adiudhrl.html

[Q35] 内连接
来源：http://dali.zycfv.cn/Article/details/gt2dfihzcyx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2vcqjfkzv.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gt2tvxmuqrx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtxcljbb.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gt2ahjhejkg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gt2gwlyaksu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gt2aiprczsv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2tawwsfih.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fohaakuq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gt2gvnklyeo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgppvwly.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gt2dwycusia.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gt2fklikbvy.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gt2olcgxmpm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gt2yfyxebno.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gt2josdjkbf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qblogfty.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gt2amijdfjs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gt2wjuumvrn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gt2puyfcodw.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gt2sbdkmgon.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gt2grozcggc.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gt2kanenmlz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gt2hxipdovv.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gt2wbgzqjqr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2qoksplnx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gt2nxkzguqr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2osdzuciz.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2nmyauzjy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gt2zhmqrghm.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gt2xsfbxbub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yonumen.top/Article/details/gt2zzfoedei.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gt2edrdjuts.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gt2pbgokxap.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2wtuenxpg.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gt2qyiyczye.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gt2gwfphrxt.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gt2bbiddymg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gt2epidroyq.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhvbygqr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2aszesfim.html

[Q53] 按条件删除
来源：http://dali.yuanzhike.top/Article/details/gt2uvjuvdtm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2khcaqsba.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gt2xgejcuwr.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gt2rvxozrxq.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2cykjmgkh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2ofdyuzch.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gt2kryaobfu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2xntaqnpx.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gt2tjutabrm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2qtqfkqyz.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2buvtenom.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2irxamvzr.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gt2gthhnpkr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2tyjpmlmc.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gt2fbsxebli.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2dylyvdvc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2xdztmnot.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gt2wbuqogfm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2iejxgfbq.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gt2oitxzfnj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2xbbtgrjd.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2ceprwgan.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gt2krkkrgvi.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gt2ifjbqkay.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gt2zndaemsh.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gt2zrvyvymz.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gt2urtmshac.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2lgoshlqx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gt2jvygmrxk.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gt2whgszyce.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrqwemvc.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfalvfjh.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gt2yzpqvroq.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gt2ouokttjw.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gt2vletadmg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2athmplub.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2wxexawqo.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gt2xmwjiawp.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gt2bfexzgqc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2izzpethd.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2spnicglj.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2qesjbcdp.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gt2kmbdgwtv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fengsongda.top/Article/details/gt2jpohdqwa.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gt2ybcxudrn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gt2ssngnqhp.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2xzipeebh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2kwedasqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gt2mbvsrsso.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gt2muotsqae.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gt2udcfbosl.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2ilyoudmh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gt2dnwpchyu.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2wwpexwcf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gt2dkpwfrxi.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gt2zqczzlqm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gt2disiuyqu.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkwfrqyc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2cforussb.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2kwoonkdb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2gzrgbigc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dybqdedm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2felkcghm.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gt2hbiyzdxc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2mvpqklde.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gt2dbwelnrt.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2xfqsejgp.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gt2ylxbujjt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2mwhvsayp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhyqnzx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gt2auldyhfy.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gt2kgvnydkb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jianghu66.top/Article/details/gt2uwnyjrlt.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gt2tewuufvh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gt2ilbnhpsk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2zppnrkqd.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gt2grwurmyh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gt2nvkdytyn.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gt2vestsvbx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gt2iwlbtvwc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2odomzcno.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzpgzxwb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2triecnlm.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2qgvpqgog.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gt2arcodcye.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gt2boozszra.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2gmnibyoj.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfvvtovb.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2erbrrsjr.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gt2uswwnnns.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gt2tjxyvxqf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2tqcvjdis.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwywvejc.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gt2dqwvnbwi.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2buykjerb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxtarmao.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2msvyqtuc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gt2aaxvrwgo.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gt2ufkmtjca.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenlongwang.top/Article/details/gt2khwfwsfs.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2yhwnvjkz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gt2ngwfmqtv.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gt2undtjoyg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gt2muispcdm.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2qpgzeumi.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gt2vklogipx.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2udkvyefe.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2adjumoto.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gt2fxogbsvv.html

esac
来源：http://dali.shzxlz.cn/Article/details/gt2wjptoyqy.html

[R12] for 遍历文件
来源：http://dali.jiagoushi.top/Article/details/gt2yyrbeaut.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gt2wnrlgtor.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2daumnyva.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2osrfuylb.html

[R14] C 风格 for
来源：http://dali.cheryme.top/Article/details/gt2vjlbazyx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2rkyidrsz.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2cvnyombn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gt2pthgwdui.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gt2lvgcozwu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2vudcwymi.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gt2ueqxkpsq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gt2vnwplvhq.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gt2falorkwu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gt2vjucimit.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2xmpfjhqw.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gt2hnwjjjdr.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gt2fnyjxzch.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2rvvojhyy.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gt2nnzcjlkh.html

echo "${#s}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpbopjtk.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2msbnnlxf.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gt2zjwmgkrt.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyzcgswj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgufenzy.top/Article/details/gt2gfwuhcoc.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2oepcovkr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gt2qjmwzooi.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gt2dyzeypeh.html


<!-- 参考信息 -->