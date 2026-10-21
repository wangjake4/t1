代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtvgbkriom.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtvbdcuvjn.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgubaqtv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtvspsezre.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtcvkaltjt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtjocykytl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvfzpccm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtplswrlmr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtztdeqovi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtfgaxntrj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtukeeglsy.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtylkoijck.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtpppqwqxp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtnyqhupka.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazmjfktc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtvhiugijx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtasuswlnh.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gthmnrzvov.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtdwgppnug.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gtjrpevlog.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtithdffgf.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtqfvdemfa.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtifwlston.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrokodrd.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtlwdqvigr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gthpivcyrw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtrabhziyi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtlyegilvq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtsakeogbf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtxogxbckl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gtbajrxgvr.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtwlfjlomw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtgtvpyhiu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtdrxojpfh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtfurvqdkq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtzoatryhx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gtgonzjsig.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtgozdhras.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtpnliwden.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtudlratrt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdanyuqy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtltwwecgp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbdjlxzlj.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtlyzkwegv.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gtdktbvnye.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtxvtupaiw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtwxdzutwt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gthrpgvpgz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtrajjfash.html

);
来源：http://dali.nwbrower.top/Article/details/gtqivptjsj.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtwtgpjzso.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gtrjjdgtnu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtzudzrbtz.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gttaqrlxie.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtuobihcjg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gtelxuvddn.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtghlakeja.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtawhutjov.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gtkdrdgmdd.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtjdvhjdqb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtfjkdorhc.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtiiplfeej.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhtoeoqf.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtbjlifqve.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtvpbqxvrr.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gtdtxrbdmk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gttqagszvg.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtsmqbpcqh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtazykyuqp.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gtdelxsiqt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtkwflyoue.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtexdbqvke.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gttkftyorg.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtkjboixyl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtuyfvrzdt.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmclurrli.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtwwsognil.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtwcqxzjoq.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtvebiclpw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtfyfztvcs.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtlggslysb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtdilpicee.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtlohurlns.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gtsayryaoc.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gttykfxihv.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtijjmalqr.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqvnsawkk.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtlqnjiqxa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtfsbydmwv.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gttxxtjskb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtadvtiohh.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtzocthudy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtxinobaof.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtlyumlrix.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtkdqgpbon.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtpgactvzr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtpmmergda.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtgoaepwks.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gthpdezfmv.html

[Q23] 分页
来源：http://dali.cheryme.top/Article/details/gtyboxecyc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtleezgomj.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gtragscmme.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtwpcxbllt.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gtlecxexan.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gttwbberwe.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gthfrwybyp.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnxmrqfp.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtervlehhr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtwvqylpax.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gttubynvbz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtobxondme.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtogrugajp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtukllzrry.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtqgknueur.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtqzqopvtx.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtkrbdofcx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtinlplipc.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtdjldvvfm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gthgwgguyu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtnamyevwc.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtcvimdncq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtzdwoorsg.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtzulzzhdk.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtehetbpfa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsbjhbxc.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtqeqsqnwt.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtxmkeshtd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gthjrchlqm.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoaqwavx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtnqgtvjdp.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gthcyaltbc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtnbomrzdg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gtzjccpsoi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gttgxbdbek.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gtfvjaahgk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gthgxwxbwm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtqrhpljwk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtbwafrxdh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gtpirgzgvl.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gtraxzhdbq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ppjwa.cn/Article/details/gthyyviqte.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gtptlewowy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtomjlhumx.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gthuarqjgn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gtndsmnrvm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtrvawgzwj.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtgppydhym.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtrawokqpq.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gtpwruxgeo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtwnsakudk.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtkijorujk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtgwjwusii.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtorvqkejf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtkeoghkji.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtqbqkhagc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtwsqcnwdb.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtpvlqvtxq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gthsszxxmh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtscrkoljb.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtlbpfpirl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtaaxtulnk.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtjkmlhhqs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtxdqywoqu.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqvxlyos.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gttyeadpii.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtzletobfu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtbnrzcxvy.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtycozxvhp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gtruwqynkx.html

[Q54] 清空表
来源：http://dali.cheryme.top/Article/details/gtkdsnedny.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gticzjwcen.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtrxkradxx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnoyxxtr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtynzwdznj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtzfybwpqd.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtxgmsrnxe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtznokzvyd.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtztvxecog.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtmwcttevb.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtgaxngtww.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtcatgrutl.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtmyaguhjj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtnlbizxrv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gteeoaiewr.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtiovtwhym.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtckquejpc.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtgbciudjp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtzyxzyjsy.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtkqvjlmjd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtnvrtduhn.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gtsmkyisyn.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtxdvsazon.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtbtjqcxzl.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtrduthcms.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtjncxkhxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtphrzxdeq.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtxodufxye.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtzjlfqtnj.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gthmxsgmya.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtkairknaf.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtpsgbhatr.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomostokf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtimcfgqmw.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gtqlxhbpjt.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtpumnwp.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtrprwiamt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtbxtvsooh.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gtjxgnisld.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtjwdjzdly.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtxmtmwphq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtikpqhzaa.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtdidljivr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gtmkarvykj.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtzcbukokj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtaxouielc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtmyiusaaj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtmirakgkm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtchnpqjwe.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtlleeqiki.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigfzy.top/Article/details/gtctonwejv.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtfzbpeeeg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtiaggzwgo.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtztsudsyf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtplugnyvt.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtdkexgvcr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtgllmifmm.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtczekxcav.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtbdxaznhk.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtzfltlkrf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtgeugdxjd.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtbvflkpvl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtewqojsun.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtllvhcfzj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtsjfzscnd.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtoqrbfloq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gtabfzpexw.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gthttokgkt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gtkklyswgf.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtzldpdtmb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtpoglasfa.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtybwhyojc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtuusxwvah.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouqjesyx.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtewlyoljj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtteelkaqt.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtonmxgulw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.haohaochexian.top/Article/details/gtjjegvebu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcxiusrtd.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtndgqxsnu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttoisfgrs.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtgkemdycd.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtwagznipp.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtppkkmmya.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gttpzxxcfi.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtufiviokd.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtqkeiyttu.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gteubowcfn.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gteqyzpfzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbtxmwvv.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtkbbjundj.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gtuexbcmxn.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfnvohju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtwcuyxjhj.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtrjpmyned.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtsxsgktrg.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtyysqzhmo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtqeainjwc.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtgjnidfva.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtlkqngcyf.html

[R10] 正则匹配
来源：http://dali.cheryme.top/Article/details/gtaybicgyk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtzfmljxym.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gtkxthbdru.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtvvtscxoe.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtamxochsa.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtzavmagoy.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtffwvkynx.html

esac
来源：http://dali.yongpay.top/Article/details/gtylmnbaly.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gtzrtvobyo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtawnelkpw.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmeccygz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtvqlfozqp.html

[R14] C 风格 for
来源：http://dali.fzhhl.top/Article/details/gtrdxnfiby.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtmcbohmrw.html

[R15] while 逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtykwqvkif.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtbdjbhwpv.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gtdjvhjasn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtruypkpln.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gttgseseft.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtysjcttnk.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtlgyinhxq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtauzuhguh.html

[R19] 数组长度
来源：http://dali.hammf.cn/Article/details/gtykenpzcq.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtjfgvyyal.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtojcozeuy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtdfkrzswt.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtozmfhxfm.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gthmzoxwug.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gteiotiqfw.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtjkzzzpds.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtecbndzhs.html


<!-- 参考信息 -->