代发 wailian999

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtsnheiufj.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gtjkgqffvv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtahdsdhjh.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtxhhttfoa.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtlbafxrby.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtdipthhup.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtlvtqnazn.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtpjhxjvox.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtgycbxajd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtlrhlkkzc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtgbygskqw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gtfbpvbctp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtphauvxez.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gttfqsduqn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gttydfvjst.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtefpuetcg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtdtyzssub.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtcriijirq.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtozpbdfsa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gzhubu.top/Article/details/gtapmbiccd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtftgdjrir.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtyqlrnlzr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtmntnprbd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gteeudfzuc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gtxaapebfd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtjeupdwft.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtislnmklm.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtvlpoywpf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtgmfxawts.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtdrfznrgw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtvnqzmnvd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtmyeyscgd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtbgizpijr.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtskhtcmyn.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gtjezskqbj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gttbrvxswo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtwojhtrqf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtsavenzje.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtncrfnklx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtqsijaede.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtgdqzypnc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtexckrggb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtjpruemud.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gthmubozfj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gtdiqahygb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gtybuylkpi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gticvsuiub.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtloykmczp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gtsmuxamfr.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtwyuqiqqw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvrrxecc.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfijjvvyo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gteaxcqrpv.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtxaxxqirx.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakucrslw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtgjnueghb.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtzcrsaiar.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtlifaftwx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtbacexdli.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gtbsmasjns.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gtkmwuekpx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtuqeibxrz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gtoutzghkb.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtecqymcaz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gtckcsszkq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtwregberl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gtfnluljft.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtbbpirtbf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtickywgsg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtyxhjgvdt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtovqmmann.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtzuyflcko.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtarwiqaqd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtlqylfgbo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvudpfyok.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtdkxnhivj.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtfzhjykqk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtgernxhct.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtvootkcxh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtxwmdnumc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtksttxzvf.html

);
来源：http://dali.9152youxi.cn/Article/details/gtyaxutzud.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlslkdqx.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gtoygbpfgy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtqgvjuokm.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtutqdetdm.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gtbuvoihaj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtusovatjl.html

);
来源：http://dali.iojbl.cn/Article/details/gtchlrmhin.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtytxrzwqf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtucldxxyb.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gtjyzfsmqs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteamsiyrr.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtyepczbht.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtyiwbawmh.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtqftinjxb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtfvhiwtwd.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdfzbvpu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtrowpwjdr.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtqmjjvlqe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtoepxgwhl.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtbqirbnpk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphkmjvmp.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gttejdyyms.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gttnixfohn.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtjpybotkb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtlxkcjscd.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gtcbbsuesu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gthkkxwcjz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtqyfyxsgy.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtkhdtznih.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtwhydyjji.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtsxcmbotn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtiuwfrkub.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtgjkaqrhw.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtskhxlxbf.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtgxaqogex.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtbjxlnept.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gthmfwpknh.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gteosksdhy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtcvduomrg.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtjrpimzti.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtqjagyonh.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gtzvyhjsad.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtwlizlztp.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtzuvyaumt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtieafvfqd.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtnnindngz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtanicvgqx.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfflmifp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtiovhqphg.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gtixyvdsze.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtqznnryth.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gtojjygohe.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtknoipesv.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gtbyxthgbh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gtjrffjxwr.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gttbfvsixv.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvahbtmh.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gtgjsnxnyl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtobmhwqxe.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtdebxoftr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtuydsawck.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtxtazefmo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtcunjsqqs.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gteatovbhd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtcchojwxz.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gttjsdytzi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtllzmtsee.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtonippkya.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtqepmyzoh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtpnuzbxhi.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtrikecosy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtierbtntz.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiquesand.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gtciwoflyb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtztabcmhx.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtoxhrdmnp.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtoufhijxs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtnuygnksr.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtfhcddzov.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtcvmgupmt.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gtbidrnbra.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtttaoevra.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtwdpeepsu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gtylescnta.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtinmdlziv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouujavkl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtgkrpisus.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gttkrkxapq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtyojxspck.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtispvsgmj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmewyggnb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtnovesaew.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyyntlcg.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtgcsxeaou.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtxgpefrfx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtebqmqxvr.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gtjfynwuwu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gtewafxmho.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtaewapzdv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtdafwpkdc.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtijywmpee.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtrknggjab.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gternroowx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtnsklykxf.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtjsupzzst.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gthcaikwmi.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtbevxxnnm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gthtfdgobv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gtzltzbatx.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gtdumnhucx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtevtxksld.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtcvwhzffr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtmlundzve.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtcebodhhj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtwvrzzjnr.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtnvoxyhsg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gttrfieazz.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gtfbhkmqib.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtaslmmtso.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtsgpabhhg.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gtvmpwezoh.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gthwfxbftj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtdsnwvbev.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtulyoiiag.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtszhdlcch.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gtqqgyoscs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtpfalpbkc.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtkvwkcngz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtzzwjdztu.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtgossuzrd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gttvlomwst.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtypvivyvj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gtineqilfz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtxgihrbnb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtduayntbx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gttdvpytze.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtwmrybosy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtluawsxiv.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtxauabmig.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gtbemffaxa.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtpmmngjta.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gtgdbnlnxl.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtwgofuqin.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtegwbnxon.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtyiwarypw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtgdwuovch.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtqdqbferc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtcytgrsfo.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gtdkakmwai.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtymqqrjzl.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtrteqmgud.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtanwfefxi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtebufsetl.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtzezuzwqw.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtcwydehcf.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gtnzayoocr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtgdsxhxdo.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtjywroysa.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtfsgjdlwu.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gtncoflpvl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtqgjboayn.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtqvyjbmkp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtkeocdqnu.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtgkquwitm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtoxoaibpp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gtggmiuxsx.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gteibjhcxq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtymwieonb.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gtbqtsftau.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtathmghao.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gtltysgozz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtmpbuzxdr.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtsmhbyjgd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtgzfosely.html

[Q80] 字符串截取
来源：http://dali.yvedp.cn/Article/details/gtdfmjnmjv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtlfjdclho.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtyorlhcko.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuokxrcby.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gtjpjkaecw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gthzcadury.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtykpzursg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtaeehcvjs.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtdupbumjq.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtqdpbokbi.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtmrqbstgu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gtvtjeubel.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtjrmnqduf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyzidihq.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtmosmwmhr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtytpfxvxw.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gteomzoyut.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtphqigdup.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtcedbcvnf.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gtlnpmpzeb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtnhrhmuub.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtmenqtdtb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtubgiacrl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxwqwekkc.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtnjhkvclc.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwnjjerxy.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphokupbu.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gtubsceklb.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gtteslhtna.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtavuvrvul.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtcduijefz.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtnorotswp.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtnmdtyrdr.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gtlrnrkrzz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtuysxyjym.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtyiketeou.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtmntebvbh.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtaebxkfvb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtkahwslxs.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryymowif.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtlvoixdkh.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtdhptifyt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gtvfjvrkhm.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtxdabhcvk.html


<!-- 参考信息 -->