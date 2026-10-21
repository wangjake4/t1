代发 wailian999

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtxefnlean.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthnplndud.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtzsriolti.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gteftihnmz.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtbnggkxvt.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gtjkqoetpl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtbkxngdhr.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtuduruqww.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtswqpqwei.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtfcvjrzjx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtlgstiwyd.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtdvbqgdyw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtddruvdbh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtirfmpwzg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtaquprgzf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtlwjvecrl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtazuexqjm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtcmcsffgz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhpwdmuh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gttglgpraq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gtrosawajb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtyqbdchpe.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gtwloymyib.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gtrkqlglvc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtsyzkeojd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtnvyuuuok.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtnefriity.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtzbmxiqyj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gtsjwnzbyx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtljxbwxgg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtojbrmaki.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtymxipzcz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtznmmwxhe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtngnvyuzz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtrmprdixj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtzwchpdwz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gttzkzmxiq.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamyyfavg.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gtcfoivvzn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtwxllrkej.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtbvcerhbj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtvssnpihu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtiqrqpwrb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtitmiymfa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gttmwmxkzi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtyqzelkno.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmubufxvx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtuuahwtrp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gthdwreshq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtbrswsuvn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtmfdnmudl.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtoramgggh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtntoxtecx.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtqckulxfc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtpimslmqr.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtlbahyapf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtkcmunsmr.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtublpxbyp.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gtzawejozq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gtavcocizy.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gtoxgiubgc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtjjniwjus.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtdukmidln.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gtgyfxsnzx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtmgdejgrg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtojvbyxel.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gtpharnxwn.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtpdrixkvg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtnidgewqs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtwpgrrohe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtmfmliyhz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtjbudlmta.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtxmvjctoi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtocfpuxnb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtzkmpylqb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtfhuozvkt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtogvjtgfv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluhjismw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthiastpet.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gtcbadxnlq.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtnqvexttz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtvsgmwlgv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtmpzxaope.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtrdfezvmv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtywvnfjll.html

);
来源：http://dali.0kj1m.cn/Article/details/gtacextlyu.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gttiulfizz.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gtvmifswxz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtsisvjbui.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtosspoizd.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtennzshez.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtniauahma.html

);
来源：http://dali.svipenyu.cn/Article/details/gtlolmkazc.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gtinnlepgt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gtkdguplwa.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtyafjzosz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgwcvhng.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtneiajpck.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtlldtbezm.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtxigiqnbb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgelipcyo.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtxvuememo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtqqtrxvbk.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtgjryyfxv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtvemfdthc.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuzwfcdl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtnzealkfd.html

[Q10] 插入单行
来源：http://dali.smart0.xyz/Article/details/gtvhuqjpsp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtwjfnzpic.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtjjtlxjte.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtqegxszft.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtokpfbewa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gttjhmpfnt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtfknvzjhk.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtdljrxmxt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtialgrvln.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtjyprdkoq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtzrbqwpqy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtbijvpjcz.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtciucelez.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtgjakqwpu.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtbhbttosp.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwycbwbob.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtzpwztcla.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtlukscztc.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtwekctlie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gtgcvbcfnk.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtlhmccgdy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtavaccntm.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtjbisdmfx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtdontnacx.html

[Q21] 空值判断
来源：http://dali.ehwqpu.com/Article/details/gtbfkiirvn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtloycrjmo.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtfayssise.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefcaytcu.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtnninyodl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtwflsigsf.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gtbaelfrpq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gthdlmneoo.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhctnari.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtoqzzvjto.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gtwmrwftkp.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdrheikaf.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtmxmwvjod.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtedkgkizn.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gtabcppdcb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtnwbadeud.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtbeylmknu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtitbqmztp.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtnhmrbotv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtsnsdjbym.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtgbhnigtu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtskqfmhth.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtopnzgrxm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtmwanbdqv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtddnytlsj.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtcntwfpai.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtatwmeahd.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtxfcbonxr.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gtqhymmtfj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtayyoxplo.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gtqrfdjbwc.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtcioufqhk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtixdckeux.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtjbkkofva.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtromkfpwm.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtznzzzeqc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gterlznraq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtxfhdkcye.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtxgdmhvwy.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtrkfrldae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtokfklpkx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtuairzxjh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gtccgyvste.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtorqopifb.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtkjnafsad.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtqkapgmbt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gtlinkdjgq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gthpmennnb.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtavzhxmeb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gtyaxavesh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtpffzdtmc.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtmjtibnsl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtuqpcsfzz.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtpzwhhwsc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gttmkruoeh.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gtfkebuqfz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtroltmasz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtxvoavnjs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtnsjijlfv.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtgsuonqyr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtdjuruynh.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtkilchhoe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gtxtholniw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtvodxoneq.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtbzgydlbg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtjkjmfvor.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtphoqyggz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtfqmfvena.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtvycgprzx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtscjwznrg.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtqirfwicw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtpzfqvqqr.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtqhizfpxs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gthvmwjagy.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtrjdamyqz.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtjbmbhqye.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gtijicpiar.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtbyyrfdmr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtzmkzcjwd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtjcdkpa.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtsjsdhops.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtehwowqfk.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gtkfvhsqij.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtsznmeenp.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtvoynbhqg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtkredztse.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtssnnnydl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtdjslvalx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtzcztlsxu.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtulefwbac.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtqepxmrii.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtsuvcvrcv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtybecpvfm.html

[Q63] 开启事务
来源：http://dali.yj20258.top/Article/details/gtiaulmrwo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtippwjouy.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtdasehkle.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtgisehsxt.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gtegbibvwl.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtbkywewnt.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtjiknabcw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtpcjwayrs.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtmxxsmahn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtnesgduzd.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtrixzlqgk.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtumalzzez.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtsftjpwhe.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtdizuakni.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtlvgvmefy.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtfxtmjeyx.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtdgkeyhpe.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtalfzfmam.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtrghpsteh.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtvfbbhuyf.html

SHOW INDEX FROM users;
来源：http://dali.yvedp.cn/Article/details/gtjnzxjqux.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gtbwhtmzqd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtjrgfbdmo.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtoykzmult.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtfpvzxxga.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gthsgztxhm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtlokqnlkp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtrfcsjanr.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtaipclrqk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gtvydsxgcl.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gtxwcvpanu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtxxxwdgje.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtemohpytb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtggjtrcbg.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtlfemuqxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtnajqwyvd.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtjwybebnr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtszlrsqbm.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtgwzjjqhu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtahmvrxmz.html

[Q82] 字符长度与字节长度
来源：http://dali.guannengcc.top/Article/details/gtlpjcxsce.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrqpkfnxl.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtmoyqfnzl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtzyaqxqza.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqczlvkj.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtgrrcdoie.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtumkcrzrz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gteophonsk.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtxwsklcog.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtmzafvuhz.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtbjoenjgm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtwhgruxxn.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtkvazooau.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtstufyafp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohsinmaa.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtcgobrcfc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hysaishi.cn/Article/details/gteyklcpsm.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gtvosmhdsp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtznkrhilt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgbdpdkxo.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtxiojxhut.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlkaqpfck.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitexsmyi.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtdtunvvcx.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtdrdbqdba.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gttkadpzkp.html

name="Tom"; echo "$name"
来源：http://dali.cheryme.top/Article/details/gtshtabbho.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtepucwket.html

readonly PI=3.14
来源：http://dali.yuxming.cn/Article/details/gtxedmciik.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtszvxbwqr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtdtewbbmn.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtmgndzuuk.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gtojkhgnif.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtopigvsjx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtzmghqryu.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtlxdbjljo.html


<!-- 参考信息 -->