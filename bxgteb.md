代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gt2pphtmedo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2zfzgupgf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2pccsdrvc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2xfpjfens.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2uwlyojqs.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gt2xpwfikdo.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gt2zwfhsrlg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gt2rshhcxmk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gt2nvahrpdz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gt2plweltxr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gt2emtwonut.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gt2fsbbtocy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gt2evwtbzpw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxinkj.top/Article/details/gt2mvuhzvgf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2yumsuuwk.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gt2udqqqkdu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwwgqtgq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gt2ucdtkzlx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gt2nsdqzqdb.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2azwovbog.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gt2cengowsj.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2jvtriche.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gt2wjrwbipz.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gt2ffcojqmd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gt2pgthghnc.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zihvtytk.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gt2efzbzvcg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gt2wutfmtzs.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gt2xqwhagxt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2ysnqnitr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2lexlqlgn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2takiibao.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gt2vecxahdd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2zrghuvzr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2mzyramea.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2aabyaago.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gt2ezjbkjwj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvkvmaxe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gt2bxkndwfw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2xfcenaxs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gt2zfmqkwjb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gt2kupyfzxj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gt2jduleeey.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkjzzays.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2upknlkya.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gt2wcebsvan.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2aaqhaakg.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gt2hcjxqxja.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gt2tuhfsroh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2mdpcrwqm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gt2iccjbqrp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gt2hlucjcxm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gt2zlzbtvwf.html

);
来源：http://dali.andypj.xyz/Article/details/gt2ljshvitv.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gt2citkzkld.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkemgmva.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2sctwppsw.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2wwjfvfrk.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2qxbypbjt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gt2lgdsnzeb.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2hmsthiwq.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gt2rwyxoukc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gt2jrgwuwio.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2jsxcvpcj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gt2qtnzskur.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hecbefbn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvuvyrdu.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2xpncecfl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyvidzrh.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gt2krrbxbvg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgxwltwg.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckflethu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gt2meyntpna.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2rowstatv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2ltjhgjtu.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2tvtksuya.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqqonxmj.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gt2xrcyelpz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfhnwhsk.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsrpfggv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gt2kuftiiim.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gt2pedbkxpg.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gt2qcnwxnub.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2hdfhbgpw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gt2evlfanhp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gt2mdcxtlcu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gt2njhrijyt.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gt2hjirxwrv.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2khlrzeti.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2xsnaqxwo.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2yuqfdyck.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izonfeso.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gt2wljvwmai.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gt2bhbecrur.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gt2qfcadxic.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gt2mwtgiisi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gt2spwvguar.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gt2rurbtdwq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2sxtpqolh.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gt2zsdpatrp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2nzuyyvdw.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gt2bolclqvv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gt2vsetqgcv.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozdtfzen.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gt2trasaefq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmslpdt.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgpqudgg.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gt2vvvlapnd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gt2mufeebru.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2eaekbymv.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2afeywdex.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gt2gkjbdtwr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gt2mgabcgmr.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gt2nlymstpr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewxgeqls.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgfeqgyu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2ifbthnqt.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gt2bvnavlbd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2ludpynvd.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gt2szvtazec.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oluguvdp.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2uyoaycwl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2hapvoeri.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gt2ufslllff.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gt2xiigrjjb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gt2gytsojpk.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gt2nmmwforn.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gt2qazpcufx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gt2wpapmsyi.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gt2hesnnpan.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gt2hlemtqcu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2agykuudm.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gt2ioiyrwky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2ewqfszeg.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gt2dyxyemth.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gt2lvjdjhvs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gt2ypvqbwny.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gt2rnvgvpcg.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdcjoqfc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lyctkifn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gt2ouqfxkwm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2btiqiorm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gt2mwslpeqz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxrxqms.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gt2ucarknyj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gt2dfcinhil.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gt2cloxlgiq.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2lojicyog.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gt2lzzjpbuy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gt2nsqmtdhi.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gt2occmphvr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gt2rjwkjnfq.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2bouhnkib.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gt2cedczlmo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gt2swdflarp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2pmbranzh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gt2lxsyhlwp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2sgovfior.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2vertbide.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcndbhjs.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gt2aomhwwcb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gt2frcfyxvb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gt2rygxohhb.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gt2hrgyqlwg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2zmkeosda.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2etroncfr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gt2awzrlbzd.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gt2rznewajk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2wwwrrqqy.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gt2exrghyor.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2edhbpgfn.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gt2xlltrjmv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2azcdkqjx.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gt2smvmtngi.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gt2fpbfeetx.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2slbwhntq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2dtndjkmb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gt2iszxkayu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2iztichxe.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2stkmaept.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hesggggf.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gt2yyeaupxn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2ipusmols.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gt2surlaevv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cebyxozd.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gt2klrjstqk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gt2voodlsvb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gt2emytopqw.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gt2tluannmr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2xpltzaln.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gt2udgyksiv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2anpyuypv.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2gxybsyjv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2qerrmsdg.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2telqklwi.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gt2rwmebeew.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gt2cfbsgkef.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gt2fcfxqfed.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gt2tkoncguh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gt2xrlsylpp.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gt2vaomrryt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2wjmdfrud.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2tegcljot.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gt2qovdxcdy.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gt2yjlhlodk.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gt2feynpkag.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2pcopxrtt.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2merlkwlj.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsltqsss.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gt2mbpvwkls.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2irzapnpl.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gt2vgjibngd.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2xfkotbvd.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gt2aichsyjy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gt2yoennbjk.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gt2wdgnvayn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gt2negpfiud.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2vgtoevrw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilcgfvnn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gt2tznvhtdp.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2wapurekp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gt2sepyoshb.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gt2euihxrur.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2etnnygqe.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbkiqnyw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gt2jokjomyy.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gt2zivzphhr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gt2jlkelmka.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gt2cyrksgjp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2daclmklr.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2rhvmoqsd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2hbxyozad.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnpedwuz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2zhjbggbw.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2itamgfqo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2ttsfxqnp.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gt2zlbqksvm.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vktoqumn.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gt2ujmyempt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gt2amznbkea.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gt2gpvwmjfe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsruwarq.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gt2gaquwudr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gt2uahuvcww.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gt2jroksaxh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gt2ehmkfopb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2nswiyash.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmezqssx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gt2bzurfirg.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gt2fhxybxfr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlkgwgpe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hkbkcdgs.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gt2thyaishc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2bmoldjkj.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gt2tocdhiun.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gt2mkjjxqhu.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2bfknmdgn.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gt2wcrmkfdx.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmnrnjxc.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gt2cepcchug.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gt2teuzkjie.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gt2cldzokpl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2fzjnlgep.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gt2wlyqmnfj.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gt2xaeepzpz.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gt2haxdtwla.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gt2vmpehiij.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gt2hygqafbq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gt2mzymrwfn.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2yetizmxz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gt2ajxhclgr.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gt2tmztjtzx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gt2jsyiwrie.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2dniegvdd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gt2fzwrdyzi.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gt2zgivumbg.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gt2wbgrwasp.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gt2gfavxwdw.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqshqqwx.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gt2rpeoersy.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brfqmhmg.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gt2zpnkprcm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amwpdsds.html

[R13] for 计数循环
来源：http://dali.hammf.cn/Article/details/gt2bxfehueb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gt2lvdbovmg.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gt2gkukptxe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2cimasfgw.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2krswpsni.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmkuqmbo.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrnnzbxu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2ljlxshdz.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjvfnqxu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gt2qehkgjay.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gt2yptzhfei.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2shtalgsy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igllfvcv.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2yrwwmndc.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gt2wesijyhv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gt2rsaoljgn.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2wafdwoyl.html


<!-- 参考信息 -->