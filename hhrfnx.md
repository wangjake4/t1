代发 wailian999

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtkkekyabc.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtxyjehwfj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtdkxryqnk.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtkyfttixh.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtogjlagau.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtwuelajxv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtjqclnhwx.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtutvzkven.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtrnzhipup.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gtllsjgbig.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtmdcokluz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtgmsrrffy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtqvlfikpk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtuxgqhjkh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtwfsatixx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtgnrnhqgv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtotbjfmgt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtffxfndnh.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtrhwpqdmw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmvewmhz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtaafuyvhh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtlrvycefa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gttasnzzly.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtmfmdbilk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgsfpsqk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtiwflzaww.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnnuivhg.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtnkksmmxw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtyqzmiznk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtocufqote.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtaexgsadn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtzbknpwrm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtpzfcrldc.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtvjibqwro.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gtnnvnpsix.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtdhgcmxwu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gtswtsjmvu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gtmmdxvkob.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtaswyqovl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtzkwixvek.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gthzcjimbg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gtufsvwsfp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtihbwhlwl.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtmkndxizz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtcihqkpsk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gtgyrsvaar.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtnqlvkdsm.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtporhcsjz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtharkuqfb.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtxewpzzvu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtzotsqehh.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gtferzoyfr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtxmwwgprr.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtfdgwocuj.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gtvllrzpqb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtifyrmykx.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtuusehnct.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtnvseupio.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtkduavlzy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gtainlrgwx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtgmbkdmaq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gtqfiixvhr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtedrobrhz.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gtuewltpwi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtlaxewjad.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtquzwfzeh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtluxshwzr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtfbktietm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gtdhslmnzk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtpvcnxzye.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtzgbgcfbb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtmqzxxfof.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbhbavylg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtteorngqj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gttmphohhp.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtvjnenwdn.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtpktctklr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtmoajukwn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtnlcxgqjw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtpizrvcyl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gtsutmrmtr.html

);
来源：http://dali.gzhubu.top/Article/details/gtvvwtokdi.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtnlcvheqf.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmftjnea.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtzckekwko.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtdaegkwso.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtbwiqakqv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtrxjcgvgd.html

);
来源：http://dali.daria6918.cn/Article/details/gtofwvmorf.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtodanofck.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtxuvlimae.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbegzchdc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtnsspsoca.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtmtgrkujn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtfdwkyahz.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtrorgeqhl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtfyckmudc.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gttaefmmni.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gtlsplkdpg.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtbketfplm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtrvuhgvyr.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtuarwdlhg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtyzlwzyca.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtpfsooihg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxmiaqas.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtswoqgbyd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtdrjjpthy.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gttdbtuxqh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daria6918.cn/Article/details/gttytmrytf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtylxqlcjb.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gtruznnkun.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtwsnzakdi.html

[Q14] 存在则更新（upsert）
来源：http://dali.sweek.top/Article/details/gtqiyxujbt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtlejbvfyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtjjtgvczh.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtngdxfqva.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtpjzeqmin.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtygylreih.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gthalqftkb.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtbiukmfez.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtnzznpslb.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gttcnmnxdl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtnaahvgzf.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtlvcrfptx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gthvmdbwft.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtcwkklzqd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtecxhorey.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gthfdiisag.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtmlyrdlfs.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtrwzeplie.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtoshiohto.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gtjxtndtpr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtdiugfpmy.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtrfsfvmsk.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtxnyrrjop.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gtezjedlnk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtbzwhagmi.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtnimyisxg.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtqdgjujny.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gthshjnrby.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtcjrqcjuw.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtarjodzpx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtrdjnyxpf.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtjnklfpas.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtepdcgdnx.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtpeoqprlo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtbhylhdlh.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gthdkqjwlp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtlbzevjyh.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtukdvwncv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtvrpxatmn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gtifdrgaee.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtbgjmpwtv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaotgpnx.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtzduqjfky.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtsffbhaiv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtorhsizya.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtfourcgjq.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtlcteaavd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtwgxbznsp.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtohhlbhxx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtimnhhdco.html

[Q37] 右连接
来源：http://dali.jiagoushi.top/Article/details/gtmbzkugen.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gthcsazfjj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gtjsgnwood.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gtdaxwfsjf.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtukukwtzq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtaweiytkz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtwmqvhueg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gticstlcdh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtldpncvea.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gtfysroish.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtnsfpnuhx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gtwimfvsat.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtpbwzuqlp.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtbsvttweb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtjeufdtqw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtabhokxwk.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtptcgbpdm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtdppjhxpm.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gtajxzdqfi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtylomexvi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtnpnxwiih.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtcxjujomv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gtdspblbkk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtecvtkjen.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtfmnwlijb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtljcsnrfm.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjbwjadw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtypkhkcmv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtokauqknb.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtghlumrfs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtujmcsrau.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gthsqhknlp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtprhsvoil.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtzeuqarfx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtfafrukxm.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtacyvtseu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gthgcwsyrc.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtagmwenfb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtzptqtbwg.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gtrohoepse.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtuphwwiut.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtrlqwculm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtiauzdguy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtshtscbsq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtepsieiny.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtdyvdvatl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtaqklrubm.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtqmwpfkhy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfnhceut.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtkulknccr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtigwtjlta.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtlbybexcj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtitxxrkjp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtalljdskh.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtyelomyoo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtipaisomz.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtztfsibxn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtuqzulzze.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gthzzlxinf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtonbaalxy.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtjngflzcs.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtytxjtgxy.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gtdhjldlvo.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtaaawcgjk.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gtkpfbbpij.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtsepzbbmv.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtamzlyeeu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtydbdkwxb.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaykbxez.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqfspgjf.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtijcgssaq.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtuoslkqmv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtypswxvbj.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtnzicnkrx.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtsiuohxfb.html

[Q71] 查看建表语句
来源：http://dali.nwbrower.top/Article/details/gttzfkpsni.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyxxpsby.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtpatndoxm.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gttalvtabb.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtwnooymch.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtykwhdblq.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gtjyrtbfkw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gtczmupqfh.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtqjvedllo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuxtsbmd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtwvkjmmcb.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtqrpzizrv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbelikif.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gtpvuwhjji.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gtgiskzixd.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtwvoqxqyj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gtkeyozbhh.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtrjudjtxo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtoejiitel.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gteyasbran.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtdpcvsnnr.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaszycgf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtsowwptns.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtghaqblgg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtxgpggquk.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtclrcgmpd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtvzyxkmqs.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtlxccqovt.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfboondtb.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtpzxujrvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtysaddjnd.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtsbsbtfbo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtbviyvfvw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtiftqkxpu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtiulkjmue.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtadagllfr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtxqgiqazd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtljqbekal.html

[Q89] 判断表是否存在
来源：http://dali.yvedp.cn/Article/details/gtttpkrxhg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gthtmmgksr.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtghvpgtse.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtzizczgai.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqmnjeqcf.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtqaurfwmv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzpieyfie.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpdeiaxh.html

#!/usr/bin/env bash
来源：http://dali.nwbrower.top/Article/details/gtdxjubcxy.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtffxvyczo.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gtkjppftak.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gtrgtzbgxf.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtnbjusztb.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gttaokzwsk.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtxaqtxjfj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gteomrymsl.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gtktgxagvm.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtlzhplitz.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtjbztopjz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxvryovm.html

[R07] if 判断文件
来源：http://dali.smart0.xyz/Article/details/gtgpwcadie.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtefjyeuag.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gttaxpdiln.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtdtpuhgen.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtialleynd.html


<!-- 参考信息 -->