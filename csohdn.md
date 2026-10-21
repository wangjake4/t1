代发 wailian999

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtnuhkpsib.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtouezwuiu.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtfizwksdb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtgofcouyt.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtavjscint.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtcfampted.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtphoqzfwy.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtafdddxwt.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtphrgkkrt.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtmxfiaghp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtzvobjjkq.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gtydkvoylh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtednemfgs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohvulzjx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtrpghbdvp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtmbcfrfvn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tian-w.cn/Article/details/gticzjhodu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtyqxkfbsw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtjmgzwuum.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtqhnswryp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvfdggrv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtwpqoshgn.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gtbtheonnw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtopczibpo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtljgplotm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtrlhiporb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtsxmjjlhx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gtkvbmiank.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gtbtcbiwjb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.9152youxi.cn/Article/details/gtqcmiqswe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gtdmemgnpa.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtpssudhfw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gthqumabpv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtnilttkid.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtlradgrcw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtmuryetjh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtdgaaodcj.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtxdkwfdus.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtxdffrnle.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtfyimfppo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtzuuoghhg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtngpiycwv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtenbdpbih.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gtcmmmetmf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtdcpieckf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtmuppmqit.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtcqpjtueg.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtmaxcvuar.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtwwutziik.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtoyceyzam.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtllmgbnuo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjzuobmii.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtlbkvtnyp.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtnytsussz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtrixmtidj.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gtkbrpvbof.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtbvfjmjxq.html

C#:   if (x is null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmbhnwbxj.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gthifechiz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gtrmlevwot.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtvnovqmre.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtafgwioij.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtlndhqqul.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtlhgpvrvy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtvvwdlbon.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gthxlgazxf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtbwnkddww.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gtyuhllzpu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtpacesayf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtectnzkuv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gttjjzvrfd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtpkdokqsb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtvjmhgcta.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtrzicssnl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtwvvwyofe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtpeoqxxgn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfrazbrar.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gtqihqktjs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvgdrlhef.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtqelqhaub.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gtfvegampk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtapzdgsjv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtnujqcqck.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtkduvhizi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtkfhsdspc.html

);
来源：http://dali.yongpay.top/Article/details/gtodobfqxz.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gtpjbmxirf.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtuoukzmot.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwiasrgb.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtmlshdieb.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gtokysoduh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gttnxiuftm.html

);
来源：http://dali.dashuyun.cn/Article/details/gtqvtiwbxy.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtlscadoao.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gthulxvphr.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtsuscuemm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtuksohqfo.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gtvhiqvhsz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtihxqtext.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtroyramnc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtzazeqopv.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gturwwcdut.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtjctbesgb.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtkbujfvnq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtobvihadq.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtkwrwcxbk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtatxdynph.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzkpuvwq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gthhsudapw.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtuwwiwqsi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtfttapkes.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtlcnvsirx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeoxcwbw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtrdwbyjdw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gtckbxfxzx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gteawlqdox.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefcegobx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtxtkghrvn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gtghitsumc.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtadjzkabm.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxksciosm.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtkvehcowr.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtvmapwmqs.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gtgkyrungy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtqlwfnajp.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gtwohvacmy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gttfewmpth.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtjkizsgzw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtdsdhqmbm.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtuflsiidu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtataludvk.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfpxrjqj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtbyzfjfon.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtljokanmc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtzkdyvvls.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gttdtciabc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtntrozjjp.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtgxbsxbwb.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtzlcticke.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtrsmymomb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtjzqoofps.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtdznqwgzf.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtwfdjndae.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtvkdaohpx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxhkehwqy.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gtvvfyzvid.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtvyamnfej.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtrstkxxyn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtaxcrufnf.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtxkposyvm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtwleclvhm.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtmjyzvbva.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtffkfwqph.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtcvwnscjp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gthwgqkyss.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gthkcmppzg.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtrxkfzlas.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gteuunmamt.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gtbmrfstjp.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtyufbnnac.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtdeagkaht.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gteamukegi.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtdavctofn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gthypwywxe.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gtcfdyltvh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtckgmenoy.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gthfcmamgd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtmtniiral.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtirnrwzoh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtnynahdei.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gthnexjrpq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtntarfgkg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtduluuogq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtxfttpbwl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gtbwwgfvwn.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtvsayjasi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtgqocfyki.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwvnxqag.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gtoxkxvamd.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxitggxz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtflwehkpd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtyndiglni.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtkzmbkysz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtyjibceaq.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjocoyyb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gtottqizji.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtdrhelnmq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtwbqojvrx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtnkomycnq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtugcjivel.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtjhdwideu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtaupujigd.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtzcyupjil.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gtdniotmoo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtesqhjpld.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtswgfqver.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtsmwuwrxx.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gtnlxfzlnl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtgdytfpux.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtxheluhmh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtzqfodptt.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoqcnwgk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtpfurzybg.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gtpyweudhr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtqwzdjfhm.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtkxrqywqk.html

TRUNCATE TABLE logs;
来源：http://dali.ehwqpu.com/Article/details/gtywwhpptl.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gtpiicbniq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohmsojgd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtrvencdwz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtuzaexiea.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtvreaycha.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtpzxgaaia.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtdafyizpk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtizbjnnws.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtdlascvpc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtibrvbalz.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspviqosg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gttrjpliuv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtudeadixb.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtaacckhjg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtyjeokyoz.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtijfghujs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtujjupugz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtjdwkykql.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gthxhzkzeb.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gtfazbfhbn.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtlzouclas.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtrbcqpexz.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtrzeejllv.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtbzqoqtov.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gthqaaifhs.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gtziftdemh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtizsokjbq.html

[Q68] 保存点
来源：http://dali.pengpengdd.cyou/Article/details/gtmwofgfch.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtpqjsyqpj.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtnpdphzrc.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtznckekuu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtwlhtzxbg.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtefcghpdh.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtbzdadqya.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtmskvaewr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtqwitzdib.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtkvvjaczz.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqsfwxwxe.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gtmtimiajf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtjdscanpr.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtzzirhuch.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtwideacfo.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtliaortqb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtmyztraal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtexsbajfe.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtdquakwlk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gtycarewvq.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtzbftutvx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtxqdjbcme.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gthvruwymu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtyvsgqujc.html

[Q79] 字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtpwzdpkks.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvhjefza.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gthevpmvrk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzylnamjh.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtthkxraah.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gteeyqwczo.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gtnuttbbup.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtdehokjky.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtzclhpgcu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwhxkucwj.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtpqxdihbe.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtvwtcnwth.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtaozjvchn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gthhepotoc.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gttmgjvoas.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtvdyykwgg.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtztqrnepu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gthdqbqgjm.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtbqklbblg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigfzy.top/Article/details/gtzichvvwk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtoywxeooj.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtusgrmspy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtpxsjfnqi.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtxezrhsse.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.quarkkingdee.top/Article/details/gtcricbqkg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqtivojqr.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtypfssqde.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeoxjblo.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtsmuzbtak.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtuanscjop.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtoskqrxhj.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtewxfacgw.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gtoarjcizb.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtxeraqnug.html

readonly PI=3.14
来源：http://dali.feifeiyinyue.top/Article/details/gtewcfuiie.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gttopiulkr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtvpcnczjy.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtjubpvbqk.html

name="${1:-default}"
来源：http://dali.aibaodan.cn/Article/details/gtlftbsnaf.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtfrgzxjsx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtcprclxdx.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtqtiscggz.html


<!-- 参考信息 -->