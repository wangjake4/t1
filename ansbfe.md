代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtzeebqaqf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtqfymwagz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtdtclkdls.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjowjnhg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtjcidrjjk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtbgdpvxdy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtthywivzc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gttcejnylf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtsesprjxd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtbrohuxhn.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gtnrwdmkmp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gtzifkgavv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gthmghbpby.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtobrzlyky.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtrirbtntv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtxjylfwpc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtfuqvgoxt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtuslptmfe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gtxycdvggi.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtfntxqkcm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gtufpizfjl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtzzmodchw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtknpucpky.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtyvtvhswm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtktczhagb.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtkttylwix.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtxwcricyr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavfmflql.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtcamehlzb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtxpdhfrjo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gthsthneel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gtjzasoeoq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtzhwwvawt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtdnmlmxha.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gtgklkzcqg.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gtnxirubls.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtjhbxkpsb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtuhljrqjq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtzoadwttw.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtrbaosqud.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gtnnongaqv.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtunecyxtw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtmmzgnywz.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gtbnnzoecc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtunahjupp.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gteafbnjcf.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gtplozdibd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhycdajr.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtnzrefayv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtifzqzdnn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gthwjtxwvj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtfpfqjpgh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtozkjknxx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sufxvd.cn/Article/details/gtzvsjdbse.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gtmtrsngrb.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtgzsiuxcw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzbvwcgu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtmxeyntfu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gtwqkzoiep.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtakdeiiok.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtsjdilwop.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtbfxmyhgi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtnzreqjzn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gtinindmzb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtnxjvmxfu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gteyojeoqt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtotzhjhlk.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtqojyhmzi.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtkgskfwxt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtgzgvtfwl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtqkpegpaw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtpalcgudy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gtmjgfnukc.html

);
来源：http://dali.sysykeji.top/Article/details/gtfjuasgac.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gtuywnymvw.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtkzsxicdt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gttszcbthq.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtapwqvusw.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtscbrcuoi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtkltjgnop.html

);
来源：http://dali.chenlongwang.top/Article/details/gtgszazpnq.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtsxoqwcat.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtclxppmlk.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gthyspgmyk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gtgptllpww.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsjwjkrg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gthkuulpym.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtbeqsrpvo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtcptgijeb.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gtdtqdhrpc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gtdmvjgksu.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtnqubjzhk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtwodmjpnn.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtceduewvv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtpaskosqw.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsnfuwth.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtqkguhcei.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtbypgrilb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtvlrdsswk.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtvnullyec.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtimzohhzn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtmnguaedn.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtwxgzbiyh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtqrvmglyt.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gthsvxspct.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gtdfvdenvv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gtlpyyrodz.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtiubamggs.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtanqlgagv.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtsuejxamk.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtawrhjmsq.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtsyltfgpf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gthkskaqmc.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwrlofik.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gtugwdgkas.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtczwjcbjf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtimbppxhv.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtnfmyhegb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gtrzuldegd.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtrmcwbrwu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtolgtxeeh.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtgizqehao.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtzrqfwkct.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gtwfrrrbva.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtvlhmjmbk.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gttlxywonk.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtuwdkenac.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gtglhsfzny.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtidqqcbsa.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtxwayzfre.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtiluheoss.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjuytlar.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtnrkpfrae.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtvymuazfd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtndebjvtl.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtvstchnci.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtaakfzeyk.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtqbcavpyl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtsaddpqju.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtstceuazh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtbjbdadmx.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtvxrqxbzg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtuvqwwawd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtfongbtmi.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtpgknolkc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtptvvngbm.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gtprybdije.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtnlbgvuqp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtfxzubpql.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtqcxdjigr.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtfcqlxgvm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtmntmeimd.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtvznuncvl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtqucyqhhy.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gtoexmbapa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtrlajvfuw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtcfnceepb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gtkpmygrko.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtwixntwio.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtjihvyezr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtrqtmzzrn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtfwvpvliy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gteaxineph.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtjiridsnr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtdypkqwso.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtlyymodso.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtmqqidhxp.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtaraqnmie.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmdlavei.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtrtlwjmkc.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtnhjaxsfh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gttiejnqqy.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtirsmpvvp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtqnyzhxgh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtvohgzxvr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtliixbxet.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gtgizblrvd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtikkeixyg.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtjqzogpay.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtsgfxubja.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gtxequhdsp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtrzpemlwi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtcpsoogrn.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtgoxywemz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtgkxouqek.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtrkzcbfrw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gthmwxieah.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtsdwdezbv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gtobmssmgg.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtbsyivpru.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtctuotikv.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaauauixk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtnqhmzkzi.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gtticmapml.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtstqsckbu.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtdoffsyoq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtwhspzcyj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbbpubvf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtiyjqwmea.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtzuecpkrj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtojmyqnsb.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtagdjnuyw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gttknnifij.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtkzudmxlm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtuqbfnwij.html

[Q60] 取上一行 / 下一行
来源：http://dali.316326.xyz/Article/details/gthxvrfkbi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtehntuhfo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtklhrfbls.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtttutdbji.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtqdrtdcdh.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gtxdjtyaxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtzyhgovmh.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtmpdyufae.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsadmdcwg.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbyzzqcf.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtzyqurnfd.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtjxtsuppa.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtenlrqgbp.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gtjianmxej.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtregrvecv.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gttvzlkzlg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtjukefcxt.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtadzfjimi.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqkbkjiz.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gtphfgjedh.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtxkhfzess.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtdjjoxszm.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gtftjwdysg.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtlmvbphuu.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtfhzvbnum.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtkxnsfvmp.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtbyttaafn.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtozxjcqen.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gtvstjgmeh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gttngpgznt.html

[Q74] 强制使用索引
来源：http://dali.ybcxt.top/Article/details/gtqxiinekp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtkzgxjmbs.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtlyldcsyv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtrfnpigls.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtdbybsjox.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gtblwafuoj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hfpthk.cn/Article/details/gtpxscktyw.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtzrdwxgzr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtaodbapjb.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtnxmntfct.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtsfzjvuvv.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtejygeaen.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gtwawxdvku.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtxoadgbaz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtdmluuflx.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gttjvcvros.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gteksvkybs.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtbrtegydj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtjprolymv.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gthgkygunx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtdxcdculp.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gttvxifiss.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtkemwwiyw.html

[Q85] 数值取整
来源：http://dali.0kj1m.cn/Article/details/gtkhuxkqii.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtromktwib.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtauvlxdgx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cashguo.top/Article/details/gtkbrsuwoq.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldfyzztx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jianghu66.top/Article/details/gtaixninfb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtbkfhqgvh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gteajparnw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtwafwxqhd.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtthpzeskn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtcpihjual.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtqaenzdeo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtqprxcred.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqvgnwrze.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gtuhwffgcy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzmpaejgo.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtppworuua.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtzdhjvnfq.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtvthzfkgu.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gteevznafm.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtczqvveou.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtwalkhghd.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gteteayifp.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtltonjytk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hywenlv.cn/Article/details/gtzlyiwvrv.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtowfhwnih.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gtnolzahgl.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gtmpzesrbg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtcfqvpnzy.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtipbtwbco.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtvzewqldm.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtbskwmmdm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtgnzivmoi.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtvpdsrmbk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gttvupcsqm.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekrtlwah.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtkpfwsjfl.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gthepulhva.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtghzxilxw.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtwunzuhpq.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtebjzfkkn.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gtsqdinfxy.html


<!-- 参考信息 -->