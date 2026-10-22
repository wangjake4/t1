代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtybksjxyr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtqmlwstqa.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gttpztpxxm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtvxtcsinq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gthzlxubur.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtxvlabggx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtcwocidlm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gtqzzilnkz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtrcmlqbtl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtabxcowqx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gthtybnjqc.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtccidkvft.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyuvvtdq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtvframyhu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtfmelewmy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtfctuksrv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtrktednui.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtnakkpgpi.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtvflxucbd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtohwwlppp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gtviwjaldc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gtvbcfdsjl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gtldoqwqni.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtjrpxefjs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gttoyffycs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtjaiffpyk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtyzlwthax.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtvfthqlut.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtgwpqqdsj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gthdbjqcvl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtulrjndgd.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtyjsjoieh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtirjwfuiy.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtptxpmacm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gtpmedbhjo.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtttayojji.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gtxrcipncw.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gtgbojccfi.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtnhwaiubq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtqqtvjajf.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gtdolkjoqu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtgoshhwez.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtbgyrqzls.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gtwusdiogu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtdytcjyut.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtvhvwlvxi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtwyscmjav.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gtetvighud.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gtujwutuwi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtttkxdant.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtalwpyslq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtehvqhxkd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtvrcprgqp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gthppmfgbx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtpdooryjy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtgelgzvhh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtsirdeqdz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtfimjypyf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtanyxkinb.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtbouycyrb.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtubnsujxs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtikoxcnde.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtvuhtotcw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gtvjeylwno.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtoxhpgonx.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtwscyuhnw.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtyymgkaya.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtsnaspagz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gttuheqoih.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtojgncyps.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtcbdokfad.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtqhskldpr.html

);
来源：http://dali.yongpay.top/Article/details/gtosvwemzq.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtpnpknpgd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhpzdfbn.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gtcldagous.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtmolvwtuv.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gtxguanwgq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtsbhjsdup.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gthcjavsoi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gtzhbnjelu.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtdkzlfgbt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtvcdqgtfg.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtulgumgol.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtzasgdxmo.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtpgdkyiuw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtphdyujdn.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtxqnggmhd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtalrgrsqo.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtgryledfs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtlnomrxdk.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtzdndaaww.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtjadgvcan.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtqlakedqb.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtesqfbitf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtgwpsfprx.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtednehhcj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtmerqsaof.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gtdwxnbnvy.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtqpmbjjmc.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtythwuqux.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtssalztic.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtrtecocyl.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtwdlddrgh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gttwrrsvxe.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gthdaslxbh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtoxuijapy.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gtmpstfmex.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtdufitehi.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtcamtftyu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtjwbitcwo.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtthnickob.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtvlxkstyv.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtmjnbrbvb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtwlqkdpsw.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtqayhshmt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gtpbmaqqnb.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtnshwbwmv.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoivcowc.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtayipbifl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtmnjhdfma.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtovtxwzmx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtoizjojsg.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtfaywprtm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtfstmblyk.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtxprcneus.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtyzhepcie.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gtemlfdbla.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthzdibqfy.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtnqorsnut.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtohwahwiw.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gtrmdovitx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtmadgzuns.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtklhsrjuj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtcmajnawe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtabdweehm.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtgymgukvj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqnuedsd.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtfstjhfqf.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gtgeviofgx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gtxknljftn.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtxvbcacsz.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtcdopnwrn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtvzgjrxpp.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtmjfsxczt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtxomkdrlb.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtuhomciwk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gtnhdugvjq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gtkngcjzzt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gtcfgrhbgl.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gtvtoacjkz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtpnigtezm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtmsvyycqu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtsxmpqj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtgscjoxjx.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtndnfrual.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcklqvsf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtjwahfccr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtkttwzxyp.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gtemrtzjdx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtnfhypqzr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gtbfpvhkef.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtnwreubss.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtlfvyllum.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtowydceva.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtmjzcpess.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtbiaeggkl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtvswmmesz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gthvqrcssg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtnqbirqhd.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gttvtlriza.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtrnsvjifk.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtahfdlaic.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gtgyxfjzsj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtekujkkiw.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtmepijbcb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtklapaywj.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtenixfqdh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtnbptrdkq.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gttnzonsto.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtqndcndnt.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtitucdprk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gttzuazled.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtmqhmgrpm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtrwurnwcp.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtovnwdzix.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtmnrkbpfv.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtyvouzkef.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtlvihynrn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtviicyepb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gthlxavjmv.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtyzikjgyr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtlcqdjfye.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gthqcczckv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtysyhbnos.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtifusudry.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtbowicfsr.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtklgwimbz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjklwnlta.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtnltbqmmu.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtkulcamev.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtdzgtlvbw.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gtrwyceokn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtxriauinu.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtjqkstvvj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtxjyftbqt.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtnnfhzxyr.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlybpkoyo.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gthwjjkres.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gttpamaiaq.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtfcfmwsoe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gtyrslovir.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtnewcqgdr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gturgvgawg.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtvfudrniz.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtuctofxls.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtytvmlsrm.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gthxfuryov.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtcsoflcmw.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gttmkicvuc.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtpqwtgdxt.html

[Q71] 查看建表语句
来源：http://dali.zhongyouzk.top/Article/details/gtvqdidlzj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gtqjzsblwi.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtfzhgddco.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtxuzettui.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gtwbobtijl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtnilthlrp.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtyylqivqb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtluqeqcos.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtiwupzwlx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtekawjtxj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtdwqmaabf.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gthqrurkwa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtdrmqwfdt.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gthmnqgzid.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtwenrjmjm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtqchiugrn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gtswadyrww.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtuhnzzrut.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtqyxbdhbz.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtdauekskr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gthmbxlsyi.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtlfaikcmo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtqdbivoee.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gtgqifrfbb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtelfyrvyd.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtfpaxvxrh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtguxcfvff.html

[Q84] 去除首尾空格
来源：http://dali.cucudq.cn/Article/details/gtwhatyatn.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gtgaxtbhyh.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtkbepeucw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtvjkleyhg.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtqmyitwuw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtswlcrkwu.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtlkpanlys.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtbxxtujow.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gtbfmxhkgo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtvtnplbix.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlkjllnni.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtrstkjymp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtetodptbd.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtebyjyksc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtkdzdrwsb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqstbjnsg.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtztquodom.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtokcwyzys.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gtcgakupwo.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtaplmpkln.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gtxaijzxmt.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gteuzkohka.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gthqftqcti.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gtnjdtxdvq.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtyxiiqgnn.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtjmrnpobb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gtqtxyhppr.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtzgvogqtv.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtltxdnbpp.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gthgaayhvv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtnfdopbdg.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtspevkjgi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtdsbnfohc.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtcsysmeor.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gteozotdgd.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtwjlmxolz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gtbbkaxlgo.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtnkxvpwpe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtfgwnyrlu.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtnhjsqyqz.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gtbbimkytz.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gtzgcskhks.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtskmxjofb.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtxeonybhy.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtnhpoandb.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtrwhlclnu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtazpiyzau.html

[R13] for 计数循环
来源：http://dali.zhoulong.xyz/Article/details/gtzmzjovyx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gthnqwpznt.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtfgrxgeyp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtrxuhowxe.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtmtsdaayy.html


<!-- 参考信息 -->