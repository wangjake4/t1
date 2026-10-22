代发 wailian999

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtwetxinxv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfwprlgnb.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtwvetxtex.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdfrbjqxx.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtrrttgmiv.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtxeihdmqk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtnfbfmfai.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtjqubycwh.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtkuafhhaf.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtkebcmgmn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoysdiyrq.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtneqkxkxi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtulbbegkl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtyabbmrvq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtwuikzuow.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gtewivbixl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtfohihqsy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmbbwxaj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtxgaxbwzq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gtqgdadblg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gtssvrctcf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.quarkkingdee.top/Article/details/gtkqmhlaak.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtnxenkfed.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtfynfksqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtohgyfpxa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnphphllc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtiebscmwm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtxlferyeu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtzpbjxwvp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gteokrllqh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gtmxqpkiow.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhhkbxxj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gtomgohupq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtjbwogglz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtamjdremk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtkwifdvui.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtyjrhsnzr.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtsjfmvnhi.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxueqtkkf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtxrtkbode.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtezzaraez.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gtvwmodvwj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtnruqsdfm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpriljyc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtprxeipes.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtifksahca.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtzyiqptsx.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtdefavxge.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtwlmwprny.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gtnmmfwtcr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gttkvzkbcf.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gtxyjosvrp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusfyckkp.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtoqimuttj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtnbbwrjzu.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtktoktwzx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtzzqnkebw.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtjdqrwncy.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtpnffruft.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouwbgfnr.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtrfywdffz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtlvnxroor.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtloxdgspl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtbpihajaj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtxgouygma.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtwuhqsaxz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtikfsxtws.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gtaucgfhra.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gtvifryrmi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtwibomzim.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtdadfbywx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtekycicgf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemcnkmky.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtfgeclsif.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtqjyobhet.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtpdcjpkwv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzcaoiovn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gtqbgzmixt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtinrodyjv.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtivksflmn.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtaquxdugx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtvljjslnd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtmmioevyl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtmxyrhsif.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gthcmkjpcg.html

);
来源：http://dali.9152youxi.cn/Article/details/gtyhajqurc.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtpdyvxzow.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtdlcetkmc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtorqrpuuq.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtvqfxshfm.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtxugjwsdi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtzzbmxpzs.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtckbaylnx.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtfpagiiad.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtpaimheur.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtoebwknhf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtdhesnehl.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtzypbmmsd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtlsuktpsh.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtmfgrgngz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gthmmgvmmh.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtsjgxxxrb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtawtxehbd.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtexwaynsr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtwzxqrtoi.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtlyyzkdhi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtrumjozrt.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gtvbkjyxpk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtosdzfzjc.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtacnffhlx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gtnlahjauy.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtlgnafncp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtsehmrxta.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gtwaupjqpw.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtnkncoiuu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtsryptjar.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gtysoocttx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplcriabs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gtyxfwyopo.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtdrioacal.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtylaurgpo.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtbyzaonzt.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gthkhncbnq.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtjgnicoml.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtasrpxjvv.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gttqxlegoz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gtenqncska.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtojtomxvp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gteulimajy.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtohnvqspx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gteowqkuck.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtnbthpyru.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtgjrxlksx.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gttvxsszrw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gtbakxjoqs.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtufilnhnb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtifkeqexs.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqxnvyqt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovlrkpec.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtgptnjrip.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gtqqlskxrr.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtjzhrjmic.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gttrexxiup.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtfqjbefzd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtupsebiaa.html

[Q28] 求和与平均
来源：http://dali.jianghu66.top/Article/details/gteqhorqil.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtvruytewx.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtjbcgfyiw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtwktssrnr.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtveeszosx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtiiphfmmp.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtzecxursw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gthimgbehb.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtsmitgagf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtkbfemayz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtcivenyyl.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtaqoanxax.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtpjgknkcr.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtrcgjncxt.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtkihzwfwn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtzwzmtlam.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtzjltkccr.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gthpcktpyc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtdkuwvvml.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gtxcyoaoqy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtgwvtwcqd.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gtintwqqfh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtmbrdddnv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtpwejnnfx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvvshgpk.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gtyyjfwpae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtjbwvjcye.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtuvrdwqle.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhohsubq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gthuuotpth.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtndwzhfsr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtyfvcwejg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtdtwjhbkh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gteisflggd.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtixrnilfq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtmmwegcaq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtglakrxpx.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtaovzwsgp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtowpncazm.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtzlfanrqk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtycfhldix.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtuxygvukb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtwnipbtim.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtftnbqafb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtwiozxyyd.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtmnolijpf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtoutbxmku.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtjxfwaayx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gtwhnyulaz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtkslsfteb.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtbyxomtrl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtipcwnazx.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gttqylxflm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtutwxzgwr.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtgbshcjyw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtfpymkqds.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtwvmixopt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtlvcuogym.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtdtlvoimj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gttlorktre.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtcmkxrsxd.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeovcqqt.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gtgjzldscb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtuzfimfqy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzktnyeko.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtfuyqsoms.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gtdyylaxpg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtbqulseah.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtkrsdluwo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtpxvrwubb.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtkrployyb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtooudjunl.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtkrdbnzxf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtmajblmnh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtxzjuriwr.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gtfodvzcur.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtenvgdaas.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gtsbmaseqn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxryqcspq.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtqumrbaac.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gtgagvluav.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtbvpfjzyi.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcpyqhlv.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtnathqaxj.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtahhyqjyr.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtmlohqgsu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtnqbiggem.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtjizfahgo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkakpupm.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gttgllieky.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtpwlwoizf.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtkagaavrb.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtmgugwkjz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangshuangyany.cn/Article/details/gtpngckbyc.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxriupwbs.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtdlfliorc.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gtxqfsvhhb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gtegwuujvl.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gtkcldtbnr.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtdicbacme.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtwnodzkmz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtwhqlajgl.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtquntwrlb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtqvzfjhbw.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtnglfbtbr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtoujvvptv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtfbxsonku.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhanjkeh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtfpdhlpvy.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtuntmbecc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtrchuyxjx.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtsrwzkygf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtpshuzglf.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtiozugtfn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsupuayhp.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtcgjoyprz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtaihrocyz.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtmitilylx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtvcyczgcs.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gthshkxvow.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtsugclrkg.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gtvhjmihyk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtqymexoyn.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtyxlubbzf.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjpqnnrmz.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gtqcmovitf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtiedevsfz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtrugvkaww.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtkyivvslg.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gtgzrbjchc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtvrzhpfug.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gtkgzqzadk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gtgdnnsbyl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gtirevdluh.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gtqhmzvwyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtcdjmpahi.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gtarlsiwwr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtrvdqwjhv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlaiihxzx.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtqrdzqcpp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtafdjqomq.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpvkicuy.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtfrsdxonq.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtobgvwogy.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndxsxssw.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtgebfntit.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gttnhpzrbs.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtikfrqzlc.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gtsqmwunco.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsuyptbt.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtverxmtln.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtfdqmrijx.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtgybaraqx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtkvbwjguo.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gtgzahllag.html


<!-- 参考信息 -->