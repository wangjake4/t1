代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtkwtvpaea.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtsxnbkdov.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gttnlaeiyl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtuxkshzgm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtziixpnmw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtcqfoytmw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtauvfmdoq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtkumumtgb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtywskqfew.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtniwhfeca.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtmbwvpzce.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gtbzrcdcdd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcenxnidk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegfbgnfr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gtzsjqgjel.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtvfwdtcut.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtgeuwpkpb.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtufziqsux.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtowphwcac.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlmxnwuka.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.vqdsnc.cn/Article/details/gtfnwyzroq.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtvobhqjjr.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gtksqvdeph.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtfranjlja.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtxghkphkv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtazrxgbpe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbmjpezv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtjjlalgot.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtxnrmsdkj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gtlfjvsmzu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtuqwgwqfe.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyojtekll.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtrvdgwslk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtjfpovzgc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtfpxxnqhk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gthdyahcbh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguoumvnx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gtxsnxlylv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrgcqizy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtjnsmgscd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdhqzsfdz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtyzlleare.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzmzcrshe.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gttgcrrlcw.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtbjjacciu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtaeoahktv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtkntokloq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gtnporuguo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtxzgluipe.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtvwaxvade.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtiorvttcr.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gttakxjver.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtzlvmmhhv.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtgfdblils.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtsxsswait.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtmfxyhhfm.html

);
来源：http://dali.daxiang520.top/Article/details/gtcjeoswzh.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtvacqtucz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gtazcrqdnn.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gtskdjkuig.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtnobtbpzk.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gtyawntjpb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtgfemqglu.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtguvsnwmu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gtzrymigis.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtmymzgfvd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtinugztuy.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gteywjhtkv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtjpcmrnyg.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gtpwjdjlwg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtmxxssorp.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtfkkyeizb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtfhvmpovo.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtycwfkvob.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gtsomzjcud.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtkqvrxilf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtrhqbsryq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtjnabfyrx.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtkblstjni.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtemyxwvip.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gtmbuztlat.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtwygucwfy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gthxafxwfl.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtsxmrpfhg.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdtuegmpe.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtzhkdkapi.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmycbxcpu.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtfjimyydu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtcqfhefjr.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtcctlmnbo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtcznbqemd.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtfrjfdinn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtfpglpgbg.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gtqhwdtpiy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gtjiymobuq.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtnqhkawqf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtadonyekj.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtepmoepkw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtggxjkrde.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gtlrxpehth.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtgyydgrol.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtppsezlqc.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtejnmjwwe.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gtkovvtxez.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtzlxiigjw.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtvryiytui.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtoyzbyqux.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gthycbhrlz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcypovyz.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtenzpjswr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsfbhcvr.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtqsqjiylx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtovmkqqda.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtaowcjzrr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjprwobi.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gtbzspdwbh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtzawuyfec.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtvpwyyuda.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtksbblrwb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtmufvrybu.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtxoqvfasx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtmjeeoxim.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtceoyoeas.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtbaytrzfz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtmdutcmwv.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtolzvalbl.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gtkruglcqn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtrjvmfpfp.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gtnpspjgmr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtskdwasyj.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtqeupscdx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtcqbmpbvp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtenkqwwon.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtytvvhpqz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxsxubtx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtgwttzume.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gttrhshvmk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtonkhswlv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gtzeqdqcns.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtjvkxmwlo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtgynagcgw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtutezakak.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtgnyxhqcd.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgflmoit.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtxtzfixny.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtrmgzpeye.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gthgzwlcqq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gtreanqflf.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtmiuupvio.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gttxigjszb.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gthejdvotj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtrnfzjkka.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtkqeeucgk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gttmefwgel.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtgrovqysp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtofawdgga.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtnahghqsa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhdhicbl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtvpynljrr.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gtsytxylqe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtnhbwnrkg.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gtjwkauijg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gtbkiggasc.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gthsdxndlc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtmodwonil.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtwqrwsquu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gthdoyutye.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gttwscgxpz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtuchdroau.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtrpkrfwvq.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gttniohsyb.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtiwlzbrxl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtqpptkrrl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gtsbtyixzk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gttqnbabce.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtunjozysh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtpqkonibj.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gtszznegfl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuhtlcmk.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtzshnuevz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtwrcqnjbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtgsnbftht.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtitokrujb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtrkeixmhh.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtehkrhfif.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtunewhzbe.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gttdrhqvzo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfitdfqt.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtmaixsspa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gthrnilglo.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gttmycymkv.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gtumvyxpie.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtfqkkngih.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtswhabzor.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtgwvbrawb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gthkpxdabq.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gturnlvncs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtdjlpyewc.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtpkdkgqmf.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtvzgkrgpn.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtqjgiqhwx.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gtlmsuhyia.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtbrongolp.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtzuzqxgcg.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gtwygemwzo.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtvntbhazb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtveisstjf.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtgpdwmiht.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtoqessnme.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gtqdulzyar.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtcaqpkepw.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtdrlxwuvi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtcehwuiee.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtwazfykhf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtlwcpbfyo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorczzkch.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtlhsjbdcc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtdpcqhhjj.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtbylqryel.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtnsgowfmd.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvttdwlwu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtnkbzradz.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtxfjpszen.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtwrrvwiby.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gtvpgvotsh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtskhrwdrl.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtbgofovaz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtabdmolkc.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzufecxaa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnlttiwow.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtsvhlztvo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtnzokocck.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifybocgu.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtozjhwhlo.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gtzmdirrxq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gtdgoltses.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gtohgklwgo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtvhdjuiyr.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtrbfzljom.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtngnrwpoc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtaxekpxnn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtcofionkc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtzcrkmphn.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gtoznfaygi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtnyzxnvgl.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gtsglmgwby.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gtkoyprwdz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsopwpcro.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtgpqqjyob.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnrjuakfg.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtxewnsckx.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gthojypicy.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtmzdqmtob.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtssyktaaj.html

name="Tom"; echo "$name"
来源：http://dali.cdnleiting.top/Article/details/gtayqnryly.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gtowgivgya.html

readonly PI=3.14
来源：http://dali.hfpthk.cn/Article/details/gtnnnpkzqi.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtxhncxgel.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtuozcnqsl.html

[R05] 参数默认值
来源：http://dali.hnqzz.top/Article/details/gtzkmxmxbm.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtlesbpqle.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtriafylsr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtunsnhszt.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtervjiyqe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtymymmokr.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtywuzvafh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtadwnipao.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtqwoqpfyt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtgmxchegy.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtdyptunma.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtjzgehanl.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtgizagesj.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gttsxecwdo.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gteqmtkjmi.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtryotfrjb.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtaefmuonv.html

esac
来源：http://dali.yonumen.top/Article/details/gtonwzncfe.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtgonjypby.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guannengcc.top/Article/details/gtnevsgmmc.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtkjpnjjzv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtqzoycwww.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtmsgyqape.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtftgjcxye.html

[R15] while 逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtotowyjpr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtsjscsmvu.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtztqhkxne.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxgnocus.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gteowqzcbk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gtxptrlikn.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtffqegsnn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gttiqiuveg.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtldliphda.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtplbklcwc.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gtjqmunnjr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtazhoiaia.html

[R21] 字符串长度
来源：http://dali.yonumen.top/Article/details/gtwdcikpau.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtharijsqv.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtnbasmobj.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtgxfhefio.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtfoqqapal.html


<!-- 参考信息 -->