代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtglsrrgiq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtsklrfbig.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtjslxwnww.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtyrixtuvd.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtfelvtegs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlefugagx.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gthqdtlznr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxetnigdi.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtxvkarudy.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gtrozuizzy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtjuovcxfa.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcowxhco.html

TS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtgueoachd.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtttzfwtzn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtfuahtbyj.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmdzyxrd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gthrodhzoa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtftqobyxp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gtemgkssci.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjneiakbx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gthocwikvr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtwxkehrpx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtymakyods.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtpajbslop.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtgisphlyf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gtnplhfnzc.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtztygzghh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gteulapkmp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtswbvnkuj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtokhtggll.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtllvvufxs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtcuzcqvff.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtblcrutan.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtlaapmrow.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gteogozejz.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtguukayic.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtzuyglklm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtpuldamiq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtbtlqhptk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtvqszmlqa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtoxywbdbe.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtdejpatln.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtfyqfyyva.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtqksqxgit.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtaaedlpin.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gttzkkokzs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtydqwqrgm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtfqxipboy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gttkjlynfr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gtjipgixnx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtzwxrujaz.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtvfvvbpuf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gtlzalnwup.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuszwdmna.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gtypsgceqb.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtuhhgyygn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtqkoegqwb.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtmnkwhpzb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtftuzcjzp.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gthajmswdd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtabylzdsl.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtackkuuhw.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtyughvdux.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtveeoykeo.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gthcluvjtb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtsghfodcg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtswtxfhok.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtzkulfpfh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtyzgnqkkn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtroaxzmha.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtxzooiinz.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtvtzpjiww.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtowbpixgs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtoibckasf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtvhmlnzmn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtybthpfmh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gtuccpppio.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gthfkdoikf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtcdosfcfp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtpkybvvqe.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgzjpkvox.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrfxzwiw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfydimhmg.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtgynsryvc.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtbppiavyc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtkdupocrz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtlfmoadxt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gteajgrpyv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtvwbddylf.html

);
来源：http://dali.guowangkeji.top/Article/details/gtxhylmtnc.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtpwqphhbp.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtjsrbbkvk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtkuyytlpn.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtnbjusapi.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtlbusluxc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtlagiuctn.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtxdjfozmf.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtdpjrxtrs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtovohggbn.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtdxhjvnvo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtxqdwvckn.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtzpgfokmj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gtfewwepzd.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtcrnoxzlx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gtmdixjwia.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtbxmskgkw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtgwbudvnl.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtnbgtnkag.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtdwyxhdab.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtcnhpostn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtwlijmbpm.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtznkowzog.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gthzqwsmws.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gttuektaru.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gthqhstzcp.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gtecoywjlf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtmlaugagr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtgomlzhnt.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtqnnpshns.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtxitedtko.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtgmjbpbhs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtezriitcf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtcgniesxz.html

[Q15] 查询全部
来源：http://dali.redwolf501.top/Article/details/gtklirlyce.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gtjmcskloc.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtqyyqsuiq.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdefheafg.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewjiapvx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtupamtdjo.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gtrjgmkway.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtqbqxftro.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtchhzbtqv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtpdylqszb.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gtytgcflcu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadyxukkl.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gtpuwvriwk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtlvlxroyl.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtonamappq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtlgjajqad.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gthwivufxy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtxrmhtbof.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtrmfahvhc.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtkcdylcda.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gtoqlqiopf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gtrwdvlesp.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtirdebrvl.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtliiqftty.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gtdbdjreff.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtaqhfweec.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gteianansc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtyvfoiyli.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gttscwtbwj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtckujzwfl.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtqhlfypto.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtltjxejsr.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtphjypjga.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtexyiscvw.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtilstkhwf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtaysshigh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.vqdsnc.cn/Article/details/gtdigcpzfe.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtjyjudqtp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcjzygoa.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfihptyph.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtdrrcfrjh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtasejuimd.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtcypswpqy.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gtrmtrjmgu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gttoservam.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtvmwcwusa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtlutqowek.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gtyikboigq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gtypjfevpa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gthgvtwjaw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gthmrsclbr.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtjtlrrgrx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtqjuyidbe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gtcibpnake.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gthiydrvip.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtgmwvdtjv.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyznuimzr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtyaqdgzxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtgwaizftd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtcslmnzhe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtrvqejeng.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtcnztcqcq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gthewtrbyx.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtcnnkxnid.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtclmjgzmb.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gtlczuhvqs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtyeasyygd.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtdodkpxkw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtisoyqvrm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtfxneswio.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtgqpwqosf.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtcreymwup.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtwkmjxead.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwiykaxw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtpsxvybjj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gtorrypgxh.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gtqcxgtmlv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtscdotlju.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gticfykqxl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtdhgexhom.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gtbmfzeeot.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtqxsdyrso.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtmnvtxilt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtsceuymqv.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtrbzqdlqa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtwoqazjjb.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtrdyaewkn.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtjyfvpayj.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gtgbaskbxs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtgczsndlf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtjvwdrnzv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtmcxsemrk.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtfhevrsie.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtwifhijxh.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtnokqqfjc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtyavmfiwt.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtrpzgjkkp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gttjcayslv.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtgwtpdddd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gtezqmzlsd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtnbyervmb.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtsugafaoa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtwveqcqfb.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtxiznzlys.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtoezgotgw.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtrnxcenli.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtmhldweuc.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtrdbbvkbs.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gtxsvxljqu.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtfcasdent.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtiinodsvq.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gthfhwdest.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtdfhnphrk.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtxjonenvc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtikmcrloy.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gtotjaxdss.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtyylayxkk.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtfrhuhohq.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtabesolmm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gthlsgiroz.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtfpbwhalc.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmycgcdsa.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtzehenfhi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtcaynbcdb.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtykyejvbr.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtxiyasenv.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtllyqmcwu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gthflumtec.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtnummxvlm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtxboaacwr.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtkaulxkjh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtspategtw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtbpghscir.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtcqhrugfc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gtniqrgqfj.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gtoamlxtfa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gticiiqrtv.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtbftbcroc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gttpnokhlt.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtgobqetfa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtmkroirws.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtqagltbfb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtjhprwtdw.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtooxkgjdr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtjeggjirj.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gtpiafylbt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtbixezajf.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtlboiancj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtadrtxumi.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtsmdzlhuw.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtrvipezdk.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtsfuqzhqz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtvtnkgzph.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtssqvwcnj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gttqkcxnnx.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtmqbsdlpa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtcudzgdwk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdkgmsfs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtalomyzsc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gttlkillfr.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibhuwhtg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gttvkkanjy.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtvttmidgy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gtkqcllfem.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdohgxrww.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gtdeitbvgz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwawwbltk.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtpnkxsuqb.html

#!/usr/bin/env bash
来源：http://dali.vqdsnc.cn/Article/details/gtbqyriifj.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtntnmvrxu.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtahstzheb.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtefxqosco.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtytfdfzcy.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtlmmtgejd.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtkaloyqls.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtrqzdblbq.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gtvhawcrbp.html


<!-- 参考信息 -->