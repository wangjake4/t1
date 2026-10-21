代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtdjoeuyaj.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtoresmsoc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtkszvbens.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtpzjvbksr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtyabiqlik.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtqlzgeuhi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtiabeizzm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtrbgsrwod.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtyxnmcgct.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtbfyoerbs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gtreohmfny.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtdoityfwr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgznbykeg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtulfhmfom.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtshanynky.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gtqvyneoxp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtjhufgxxx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtejqzdhhi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtxrwzrrqd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtqooyehqh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gttvzgxipr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtabsawxao.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtrataqheu.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gtvtyvocgj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtruawynwu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtrgvenuwo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtahdcxdky.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtyqjshmtg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtsgwwgrnh.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtbmugdath.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtaxmpecgl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtpwicbaea.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtxlucjblt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtitxrysrp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gtpfgwonkb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtpxqhvjjq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwqvwacv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtltlwdmdj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtihdwhrib.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtikhhcdot.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtefbkkzwy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtoyggiftu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtzqggsrio.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtgufpstll.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtlfqeoxco.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gturllnizb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtzswmstko.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gtauubvply.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtqcdbwngh.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtgcacgukc.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtmegctzto.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gtlnfbdwxc.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gtayejhhnw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtbdmaizob.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtwbrwuufw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmilzfvt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtkpokrawe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gtddpqjyom.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtjklwqhms.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gtbcufiyms.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtkmvmoiny.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtxkeeynyw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gtykqkxrrn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gttkslutuj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gtsejanvtk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gtrmtyenyg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtdltffmew.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtazvgcnae.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqnzhkcan.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtlhzpmuqt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgsgxctfj.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtrhhoipfs.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gthwyyxnkt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtvcgtotit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtrdyiijlw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtolqvjnvr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtucxypjfo.html

);
来源：http://dali.tianlin.xyz/Article/details/gtkoupmsog.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtxhltlncp.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtnvklbtbb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtdrnbovqk.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtuqpabeuj.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtpakeaamb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtuodzasas.html

);
来源：http://dali.zhengqikj.top/Article/details/gtlmitosgo.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gthmkzekxw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gtmfukdxyd.html

[Q04] 修改列类型
来源：http://dali.chenjidiqi.icu/Article/details/gtmqszctmr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gteenztrrm.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtbyggrnkm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtqloleyvf.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gtnemuvzbl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtencaaqky.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtcvmjcnio.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gtzbdfpina.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gtbgwiayeb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtqpxitpiu.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtkrpyqtog.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmkctffc.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtwhesbpfw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtrtokgoax.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gthzsuqejg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrteuvmh.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtgrmtrrzo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtliprdpqz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gtmfanrzqc.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtrpbjhawh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtvuzxvgix.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtlnzlrbgt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtyehuouno.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtghqwxklt.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcjqxlfb.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxzimnahg.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtymvcrubk.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gttbdgnqnh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gtcfkutfao.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtibbbyryb.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtbvcdtixa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtmhpueskt.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gtmbveywnj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtakappndd.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtljfzlbjm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gtenlwttsu.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gtgbgcrths.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtnthcadmc.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gtszojqbdt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtbsbskqgs.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtlxibcetg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gteqphlrhd.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuzvuqqp.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgicvrow.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtruajgcrf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtmgyojfhv.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gtycidknuq.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtltvpmosj.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtvfwptpjc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfwadiofp.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtzczifban.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtoitvahhe.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtwgpqftyq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtjdqkhgym.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gtsmwdffle.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtnkdlaizv.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtlpmmvtci.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtckhlfgvi.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtmrkmavfq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gthurygmpa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtssauaccw.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxjwaxee.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtmtsmiibx.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtpqfzuile.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrifhtjqm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtdgiqcehn.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtyukaztvt.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtbtpzgawd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtvesbbesz.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtkvpxzmih.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtmewivvew.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtnrondgby.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtjcposwaq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtiqxgrwuv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtewyjpkbv.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtzsfomrxt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtyqmnmtbw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtijytpzex.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtdkartnbm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cheryme.top/Article/details/gttqiqdwmi.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtbkdygrbt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtxyzmvwzy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtmfntlkyb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtrpypzxpq.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtldzasgmo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gtcvfbqowu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gtvpjhntce.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtlvqcqqey.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtmepzgcsm.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtrvbmyvax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gtyhmekqhn.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtxbwuggrz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtexootqrz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gtbuquajob.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtegvipyqz.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gtndtxfcja.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtwwpyvvyb.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtjkrzlhmq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gtvwgntxdj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gttvkloxex.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gthzknyard.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtvfpuhhfe.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gttzgznxfz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtofurgdwt.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gtdjroevco.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtaxczzklf.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtcmnlwksi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtndcfcpoe.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gtruufdjvk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtcdtvqaxd.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtpqlqvsmh.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtrwmtmwis.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtrpnpocig.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtavezfbiv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtuqqmsuhe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtiyrrrlue.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtjxeivwfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gtyzpuvbng.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtmxmqwohn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtrihwhnel.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtucmyxjka.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtjgxzrzuh.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtliwdphpp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gtivjzxama.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtebunswow.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gthwlpzacg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtpuhrjrtc.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtnppfwaol.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtqdhqqfsl.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gtisthdskm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtfmfnenih.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtjbcfopwv.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtjrsknltw.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtozyqlltg.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtcdkdudpk.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtvpyrrfgh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtunhxuyrd.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtmjpkbaue.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gtsrdaxeja.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtzkinwqwg.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtmccbonrq.html

ROLLBACK TO sp1;
来源：http://dali.aibaodan.cn/Article/details/gtmsrfdewx.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtnffpzvrx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtwphsilsz.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtdrqkxjtk.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gtjpcihhyo.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtdelmhsxt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtyrxsnmlg.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gtxrevgsxd.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtnpvycvst.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtfsjumfku.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtsmmxxkuv.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtqpyxajxu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtjyludlpo.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxbnujnd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtyagkxjaz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gtdzdzoqmn.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtyaulbzkh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtkkpndtsc.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gthahrnwlt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtfxbsqslt.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gtggouljyq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtzcahppge.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtxhvnfowa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guannengcc.top/Article/details/gtyouyakag.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxhkbnni.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtznirpgal.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtqhvhievk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtzrheyyfk.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtchchqlrj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gthanqfrzq.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtjfiesulm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtmtdpuoog.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtziquoptb.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrhpucqtj.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gtnemhstbp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtnosxgfne.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtkrxubglz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtfgfipnfo.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtnenhonto.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gteebdikpf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtfewrcqhq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvvsatgy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtecoxplzn.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtfvrokeyv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gtahijhytm.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtijbpnejk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gtshqhmxps.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvpllirlu.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtlylcxvey.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtseeuuvhh.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtagllmyjp.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtjxndztpx.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtdzeciaxd.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtjobxabgu.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtkfcwiwmc.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtopaluhof.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gtnfzukgak.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdcdauyn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtcwiatrtj.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gtmijvmsmq.html

name="${1:-default}"
来源：http://dali.jqgufenzy.top/Article/details/gtnrfgrfda.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtqjdzpevq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtyjgkdqbe.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gttwadedkn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtjeldkevn.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtjuiivkhf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtaranwwjq.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtxfmgoote.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gtcjperauc.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtbfsuuvja.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtnxptqvex.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtqswdmzba.html


<!-- 参考信息 -->