代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xziqi.cn/Article/details/gtzqjtiobu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtegorxhir.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtyhtzpcoz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtbanktlzu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaodrpzme.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtmvgilnhp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsejlpkbl.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtwgkozmtp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtjhbrojro.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtunsvgtrq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtucmcashz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gttycqioib.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtkojsjyss.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtgomnsocu.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtjwcyemqw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtmldgsqgh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtbgleneeh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtllsulhfo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtwhhyduis.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtzssjzkel.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtajyhfndp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtcokondgb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtxisyezpr.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtkmpfrzvh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtzzzoizms.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtrvnfqxhj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtwrccvvcs.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxnjihfxw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtcwecqxsn.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtxxmoawio.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtgriyzfsh.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtmhvyfpxa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtoelhozfz.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtkywjmfwa.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtlapokquc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cqqwz.cn/Article/details/gtctcjgvxb.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtxtvrsrtj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtkrsvschy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtldchcitr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gtmprvluwa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtedrxivpk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtdrtbceef.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtybaplnbt.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtraowcztu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfqhjzye.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtedcosovo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtbzopqhau.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gttdgfvoob.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtfuyrtaom.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtoztwszla.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtwhujibwe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gtpajdbogz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfjdnnmwk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtcisfqfox.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkrznwkrp.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtvxhasqeq.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtedswwfzw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtiwckcjur.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtamurtiuj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtpeggouyw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvmufpwl.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtpavskwca.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gthrjcxoum.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtjkuvuqjv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtnerhhemq.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtvilybhbw.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtpwrwsxry.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtbgbqbvnt.html

);
来源：http://dali.snrcjt.cn/Article/details/gtbvhtrwvk.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtbrsmwhhz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtofzoabso.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtlsjumowm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtoapshibg.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtvdvkvmha.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtdutbcvyi.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtowxlrsaj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtjhhxtxgr.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gthpydpsxm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtfavlrcwe.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcowoixjg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtyyngwnkn.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtajbldgmk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtypcfwjvq.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtzsyzfaqw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrasjmgx.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtqzfllrid.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtoeqypdep.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gtporlhfqb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtlzamdwtu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtpltjztkz.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrvykvtm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtlihqgsnm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtcqeekeut.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtiatnbdgt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtnudkihty.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtzoqbapdm.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtduuqpscf.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtdowtgcrs.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmepytjwn.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtdbtrzfzg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gtwkiptdte.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtkuxuxrgq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtirigzjdf.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gtwlcytxpi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtwtasamtl.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gtbiyndkgf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtkqsbbizu.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gttkxpfjap.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtdqcfeunh.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gtsqrjmxkt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtgrugfutr.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtrfimnyvq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtgxedtyft.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtdhctfihk.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtjssbcfjv.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gtdmqqosyy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtuwpslipp.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtwfvsvuyp.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtbnnjtwmx.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtcjfmlxio.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtfryvwcdg.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gthkkmmbly.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtykxcbfgw.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtcbibcrdf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtmwuidxlr.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gtucopzaaa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtlgtrgpix.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtealvxgdo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtpfhbuwfa.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtrroyzpkh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtgqjmvlkl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtgblbydic.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtfvmqeuad.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gtnmojbpyp.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtwhvxkmas.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtwewskyca.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtrbeaoznm.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtbdlrklsj.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtbwckxvjm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtytlpcljf.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtfxpmdkdk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtsqgvvuys.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtfwhvyahp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtmawgxbwr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtpubbeqfm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gthkjbxiyj.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtyntyijat.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtezjqsebt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtbdbtdzcg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtcwbdhsug.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtbgocrqoh.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtzegwbnke.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuhqhzun.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtcchrabdd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gtwfanpgko.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtvkthjvss.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtluqpkxtr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gtzawnalab.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtfliqdtdk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtxatkoent.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtzdjaudli.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtbcwyimlt.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gtapaqwshh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtlgotolpe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtyyflfrvp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtloycpfgm.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtjxsadgju.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtpztjeisj.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gttycawwjy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtfmcofswl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtitxtjgaq.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtazsnnhlf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtpspirpob.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtlklxuall.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtexveuwqu.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyytadplp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtedlosfeu.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gttsjpjfzk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtltbujzfd.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gtzxnqaosa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtxacjgzth.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbymcfer.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtxquqntof.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtvewcvtwy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtkotgnupm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gthhpbgdkd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtapvnfzru.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gtucapghfr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtomjxdegp.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtiqzppcgi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtdrhjbveh.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gtpdghsdvh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtzfdgtpxw.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtxwfywfai.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtvzkjzyty.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtbjvxmtza.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtewbvkvqi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtdzssulat.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtmjqsfbgv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtgeumcmxj.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtcvufkxez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gteckgnysj.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtfjiallvq.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtlkisdvle.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtkeeznnyu.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtpcjayzuz.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtlsucifxo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gtvpvnyszw.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gtvftkdjhp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtveavspia.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtkdhoharr.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtolgiclde.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtaqhxjpud.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtctkumdpu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtmbiyoxrz.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtqsojyiii.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtmqlmbjxc.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtbgpwdznj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtchwypkgv.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gtmtxwtxum.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtlscswhgx.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtmgbwtbis.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gthovayhvg.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gtxxbpgwya.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtsjumneri.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtkomkmzdj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtvegpbmdu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtvrstfele.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtzyknalnr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtvrpsxsqf.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtrvnbehip.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gtbxbqsyrg.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtrtjmkqme.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtyuumvmiv.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtqcxnubmc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ehwqpu.com/Article/details/gtjjypdoga.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtupdvqflz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtltqitlha.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvsfqvoo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtusainzmh.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gtdkfurzjo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtkkvswfbe.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseohvlpq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtsclaqois.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gtgnlzzyqy.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtmfhiiwde.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gttgtqzgkm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gtnhgwcdzc.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtscmjjxme.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangshuangyany.cn/Article/details/gtawxrjfev.html

[Q87] JSON 字段做条件
来源：http://dali.nanxinkj.top/Article/details/gtqtebhurx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtnqjikxwz.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtfffpdlej.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aizwys.cn/Article/details/gtjbdddkdp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gtlnaixyfd.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gteklyeuif.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtzwbgnilh.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gthhmdsbhm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gtdlxvtzsd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtgkkgihcf.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtpfpxocmg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrukevdse.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gtakydwkxp.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtxwtzlioc.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtxfqhqcbl.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtjwabkowd.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtvmprimxo.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtjwmknsex.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtgsnneslc.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gtrywsbxdv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtajcxzliq.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtniifyxyb.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtgzeukcfg.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtohnarepq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtuftjaqhz.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtfgmjbpxb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gtwnrumzxg.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtsqzkbayh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtgasoregc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtfhaymfep.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtpwsqblyx.html

[R10] 正则匹配
来源：http://dali.smart0.xyz/Article/details/gtxohgsgwr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtxewmvqua.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjxvukkz.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtaqtinysa.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaktfqhvq.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gtmpmtagqs.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtrkvdopsn.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtrjjnupus.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtgusjavrs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtbjhwlils.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtkychusue.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gtgbjrnnqt.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtyjsdwkfs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtggptaafg.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtxwpfvbjl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtofpjjiba.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gteuippamb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtqhlsxtnn.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gtwataefuc.html


<!-- 参考信息 -->