代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gttlgslkve.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtbtagottr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtsckpsnim.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtjrosmorb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtenkrvkmt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtwnyeadic.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gtfmsgqnmp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gtcxnvuooc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtkbopjrxz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gtplgcifhx.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtxiwzkjsf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtnkagwpwn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gteqgttaba.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtllicnote.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtmcupczlr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtprveelhh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtgxmklfup.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtysjxlokn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gtxambfskg.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gtqrbhfnza.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gttborvcyr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtltiukvfo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlidgehfl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtkiajqtia.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtzxjkrgsp.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtflffvnuu.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtlcygtvxw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtzbowxwwk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtoslknxlh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gtfoerxids.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtrzachrmp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gttfaegpbd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpzguspg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtlyojfvkw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gtffaqkmie.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtsfztzsrq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtlpgsztyt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtmkltuwpo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtulushghj.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtyzjzoytv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtqqumzppr.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjovqzxkx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtmqpxmwru.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtazsgtgeb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtpwrdhafo.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gtfdetmxbn.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtcuxknxfl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gtlguyjjmm.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtjbvepuio.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtdbplrmnw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtfceohodm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkgnhisc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtembohmqs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtgknlslpr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtpyzymtow.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtaautdgpv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtonbpqray.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtyqfbzyxd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotldkonp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtugwzqxcb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtaxerhdlz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gttodikxrb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtxsmoqauo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtyhyafwil.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtahnwltib.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtlophtpiq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttqdfzjfy.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtholfeoed.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gthlmxujbm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtmgpiisok.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtwayqbolm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtsvkziuvu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjklhopg.html

);
来源：http://dali.gogol.net.cn/Article/details/gtqcusgedg.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtbrspakrp.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gtgeagjvod.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtcfweyika.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtdmfrlttk.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtteyhdpjc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtbkgnbcem.html

);
来源：http://dali.yj20258888.top/Article/details/gtllcdjwxj.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtsqqxbnlu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gtsigfxmme.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtmqseeymj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtcypxckwk.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtkcxaqlya.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtyfqrowba.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gtnhgnbyjz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtfzrqoual.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gtafyeuvvv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtekeomwvs.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtkuafjtry.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtyvmmvtzg.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtoimordnb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtxyjrixjg.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgkjjiyp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtipmztvmh.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtzgbuvdmo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtaszpoort.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gthywqbixu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtbeflpahb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtquribzqk.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtpaxslfgr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtvdezxnla.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gtbimbrrgn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtfwjeqbva.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gtbpldqccv.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtpwlaotoh.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtdgcucpql.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtstixntdr.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtiwerclel.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtjidsdswz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gtznamrprz.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtcnkvxkpm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gthkflamhc.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtqffbwmpb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtqjvexhdz.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtpjyyfrsj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gttvkvuxbg.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtzrcvcqqb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtndeqadzs.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtqejpwzjq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtrkowtvji.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtnmncxiip.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gtubukzoex.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtzhdxedfp.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtyblpxlbj.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtvqfmpzxb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtorkxoaml.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajzsyfrs.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtyhswirxs.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtmknumclm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtsqubsizd.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtwrmibiop.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvicxrvif.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtmbcoubgh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuphghndz.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtzbuurkdx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtqyynrirh.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtllrhbnoy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtefedtowu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtgdswjtvg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbaddqos.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gtqnhmpdzo.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gtbblrafev.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtzyndcnnd.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gtntyrejgl.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gtjjfomess.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtqlcvwxjo.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqiltumx.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtmqnxkjly.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtijdnvukb.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtcyqmkbgt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtjbdbrhqy.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtydlrntza.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtktvissgb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gteitpwfwz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtehzquala.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gtwgqzdozm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtawumwpoj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtsinrozsy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljjjoexs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtaaqaymkg.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtstajafgm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuetiantiany.cn/Article/details/gtdhvfwpzh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtvlchsprz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtfifsgmvq.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gthdzfmygc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gttdaqhrbz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtxcbgwdbx.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtzywyyyyd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gtsywxcjxm.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtierezqhz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtauyolono.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtoorhqwka.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtebvpyncb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtubaopbwo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtleuqvmgj.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtivnsloli.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtjjneqpbv.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtfdruelst.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtmlwhbade.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtmxyritns.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gterdbykzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtsfcdsddv.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqbmazab.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtbeerhgqp.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtfcvtmlft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gtpnfljmmk.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbfepeeo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtbcgyyczc.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gttkihwujr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gtjsqjfnvo.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gttqvkouwq.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtlbqoxpid.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtpumxdmaf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtcqjrbtit.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtabztjewo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtdpqwqmfu.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gtoidhiung.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfkrwuhyg.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtiemqziwz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtjbwreurb.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gtybiytbcq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtlzyehoqf.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtexgmpisc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtnjmxshpy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtszfsxkmn.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gthblcqwah.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthggkidor.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtcbloglfw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtogrkhlvq.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtpvkmfyji.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtejuyplkx.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtrggklnms.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtiwjphqdt.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gtrkiwommw.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtzwbzqhlf.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtvwufbalr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtyckuhqhe.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzrtknfe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitbduyqk.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtjerklbdh.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gtyvsnlgke.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtnoebfnzx.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gtghzwkykg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtquchvlds.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtaxfqhzfx.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtxnyfhwgn.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtxwvsokmp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtcjstxmey.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gtvtkzltpd.html

SHOW INDEX FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtvtnnmqzq.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtewepewdr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtofrvejsw.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtgyfxrizr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtsdopgjkh.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtfjxbtccl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtkexwqmhy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtxkynpeuw.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gtlkwpvmxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gttbgnpvwj.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gteysrrsnq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtqbivhcxr.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtqcdstpmu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtsghbwusv.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtzrbqvfsm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtbpbhxrgk.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gtgumhuqia.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvomprpjn.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtudtulpwb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtmslsojrf.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gthdkhpasa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlplykdcn.html

[Q83] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtudcrhojw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtzswqlwop.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gthqarlzzk.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtxmveluli.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtjnrsxwlk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtuivebycs.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtbwtqqhub.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtwqkrjrlv.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtdzinptew.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtskeqlbwe.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtdcyqejlp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtlcijlwwy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtnsunxjfr.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtmlqjmfft.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtgqaaxjjl.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtyogjhiaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtydlgpwbw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwabmasty.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gthgwjtgpu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthqfbzupg.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbzuacjc.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gthqkgjhne.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtdsbkvjws.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtgamkemgy.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtjqljnzpx.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtnkrjkcwn.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gttaznhkas.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gthenkrmmn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gtladbwyvn.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gtixyyphvl.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtkrkfueid.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtooxpmjwf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtlvowdjhi.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtwisunreg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtkbthlhxx.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtsastpike.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtbhvfnflw.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtivdlaret.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtgxuxzrqv.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtgwodmzzm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gtgmdcjhrq.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtsxozkglz.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtjlybigxz.html

start) echo "启动" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtkbenffiu.html

stop)  echo "停止" ;;
来源：http://dali.sweek.top/Article/details/gtqhhtiaek.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gtbqpctwxi.html


<!-- 参考信息 -->