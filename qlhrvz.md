代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2uhnxbtzp.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gt2cpsoctxx.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gt2kabucawz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwitakqi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gt2gtcbnolg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gt2ugpyysle.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gt2ldoogcdg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2ivjqdtsv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2vwckiouz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gt2mpdskvbo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2ykakdyty.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2zcmtkdis.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtrwxncb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gt2jofuernu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gt2lpakdbiu.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gt2bbcmssfe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjhggrcd.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gt2efajyyqy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2dmtwsqri.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gt2ltuhukdk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gt2bthynjfq.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjbsovod.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gt2dzkskzbk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gt2ghnsucvs.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2znvbxgby.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2mpgdqldw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2zsikjasn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzguzjtc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gt2ggyaekei.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gt2tdgmsmhd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gt2rlxvyeqn.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2svgaybdb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gt2niinougf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocqgklew.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gt2kphcqvbm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gt2edeogyec.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gt2zkxusoxc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsrxqmld.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gt2qvteesnt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2vbpggtma.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kiqkocpy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tianlin.xyz/Article/details/gt2tcjygprh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2aikhecbb.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2xjldoqpn.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gt2uoptrgpm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwtncnyb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2vuxuansf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gt2jgwnxwya.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gt2wdfscaht.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2impnspnm.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gt2bensnzex.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gt2pfnunloi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2cjmjvkxr.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2uqseiuzb.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gt2vqhoeyyj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gt2ayshialn.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wojtylvd.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2sepwoyxj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.svipenyu.cn/Article/details/gt2oydnonet.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrnfyivf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gt2artdcjgb.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qadeeuae.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gt2yxpddhie.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gt2hrpspvet.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2qggdxjbq.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gt2lmbidflq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gt2rjcpydna.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2wpezpcrh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2gqnhxosg.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gt2dqaxibua.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2uupqulhq.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gt2kjwjopur.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkcbojd.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gt2bwkbosct.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2mlpdeqlz.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gt2zojiosgy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gt2ebqlaxam.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gt2ousuioxp.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gt2zmlckdje.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2jblzgeyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gt2vqrqxzvu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2svzdqsqi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2asewlesw.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gt2mfharken.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzvqderz.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gt2hpsquwdq.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2oxfusmwv.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gt2havzkbze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhjxiavb.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2zhdnspaq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gt2eysvprra.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gt2fwehnijq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gt2nolnvyop.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gt2rglvborq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2bxbpmbiz.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifxpztxj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gt2whhxktqm.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gt2udolzeog.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2kavuttcc.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2aoowymfn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2pctdieec.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gt2bqrdtccw.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2pbkpyjnu.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gt2lfndzgbc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gt2cuzcmvov.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gt2rtjfwong.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2hyebchof.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gt2ejsysakc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gt2bqlagbhi.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gt2tabqwyyv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2xkajzkwu.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gt2kbrbpacg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuzgtpzy.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gt2yhbjlust.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2bumxnypk.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gt2zixbzajd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yyqqhkkr.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2hlbeqkpk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2aosccfio.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2javfuyau.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gt2giyguncg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gt2xoopresk.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gt2kctojuge.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oicjvfom.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gt2mjzfauqr.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2otckuxbl.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gt2uxqcgoqk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvskqoeu.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gt2ivsjtrxa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gt2clwxqizt.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gt2crgmxycw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gt2jlgjfehc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gt2lmetfais.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slcjokrs.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2undxhlsd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gt2zvokbjac.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gt2adwcljnr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2cmbseerv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2lojvubjh.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2icdbprjy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqkycgmz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prdtngge.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gt2tiasadcn.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gt2kanxtiqj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gt2wbybfbgj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xufuemzt.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gt2otlsfwmt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2xryojhaq.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gt2xlomeixx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gt2pdsebjmf.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gt2tepuipvl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2hofihsyg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj202588.top/Article/details/gt2lcuoweqr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2pzysqfig.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gt2cilmjjvd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gt2zodwirxy.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gt2toieebmo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2suwydqlw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2zhgqrfnm.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gt2qmjmlxyp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2babokkkz.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gt2xkximifh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2dzctpofe.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gt2qbrwetwt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gt2upamhvir.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gt2phzxatbz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2unimhegl.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gt2biruldfa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2digksfoh.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gt2vjdcxqbr.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gt2vgpulqig.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gt2jhybgvff.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2cuqwfyje.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2dzttexad.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvwpdzkm.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2rlwdsqtc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2kvdxntxc.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gt2irplnoxx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irgejrri.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gt2mjkakuyf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2qnjearwk.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gt2ttgmfrgx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gt2sweqdspg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2niwyfeiu.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2bbhzirno.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2jicasklx.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gt2qzfkhzku.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2rmxtmlrd.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gt2nqfhpwzc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2ucckurto.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gt2csoinrnr.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gt2zsubsqcb.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbrlqxuu.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gt2vriuodms.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcydhqzu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2cmluwbws.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gt2oklediza.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gt2uupvkxqb.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2obhfwuzx.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2tzumqtzs.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gt2rjzsjkjf.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2kiwchlyr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2mebtgsmc.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gt2wxjyajaq.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gt2snhoyavf.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gt2glzsskyz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2iodtmhqi.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gt2bsjpxprq.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2xbxsooif.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gt2kumhunsz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2nsamrkdd.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gt2khccyzop.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gt2vocnwipd.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyuoabzk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2jorwolaw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gt2zaevjhiw.html

[Q76] 按天统计
来源：http://dali.yangfankeji.com/Article/details/gt2fgfxdwih.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gt2wpguoddz.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gt2npgkzbig.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gt2tnjnksto.html

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gt2hlprmklc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gt2zcrlcquk.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gt2orjioxuc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gt2invzrofl.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gt2fpoeelnb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ngwyfmjc.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2vmzyqwez.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gt2fkcihcwe.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gt2ithoigdf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2pfxsimfu.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2eeqwvyqj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2okdctumg.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gt2wxqeuqns.html

SELECT TRIM(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhldpcov.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gt2yhlqylry.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gt2iodtqnzo.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gt2bdqdmbcd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2looiyfzf.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gt2cdxiwzxm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gt2dsxtyiqs.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2mrpqgxdl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gt2ozsftcsq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2vynbjwus.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2zvfhalbz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gt2tjxlnzlf.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gt2kyhkjybw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gt2idctzkgu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2epvxmqmx.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gt2xmqufrtz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2trcwahbc.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaqpsqls.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2ucztsfsi.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gt2ztjdngam.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gt2vegsdivb.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gt2iielexgh.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvpzgxxp.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gt2jyuhxjyr.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2scictwzo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gt2wofmyyct.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gt2fqdbqetp.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gt2diptgajb.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2akyulnoq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2irkblicd.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gt2egwhhvlb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2gsoqwlgt.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2qonrrzcp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gt2dhntceey.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2tnwcsxnt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hlusapqx.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gt2vzjwsbct.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2anvivatj.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gt2phtocotz.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2ocmmmzlg.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2dqyoxged.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gt2btrompcc.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gt2sdjpglaz.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2ddvdqvon.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyqzfsjc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gt2rgexpovf.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmwwyrdk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gt2txwocpkx.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gt2sposqrxa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2mrovhqsk.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tiolpozd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gt2popdmbrs.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gt2oavwqwel.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2keopaeja.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gt2qsztkeha.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.andypj.xyz/Article/details/gt2wipomlbe.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgvscqjn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gt2dmwmkdip.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2alweapyz.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gt2ndcaojqu.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gt2zcgwwmez.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gt2xqsjkqvd.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2jixjverj.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gt2mhggpaqg.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2lizoxlzi.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gt2jehcxoey.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2hlnzplbm.html


<!-- 参考信息 -->