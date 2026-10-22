代发 wailian999

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtksrxhpxh.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtissjiejc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtiewmktiz.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtfdebvtgq.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtflgomyfl.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskcytkks.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gtkjykisie.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtjxexytzi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtfsrhylin.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtsztssgya.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtdsabhfmt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcdzzncv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtruwkfaqg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuwmctql.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtjoedkpup.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gthbopiadr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gtmepqabyx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gttlzgyenx.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtvningdfh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtrklwwbcm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gttgpwgapb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtptpckgzi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtdzxptznw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstadcdvr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtyddwmnlz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtidbtkpwc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtgdcowcym.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtujshhihy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtzeuhzzjc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtmivaudlr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gttbuioytt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtuafccsdt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtydkvcrwl.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gtxzyewjvi.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtddjqdfry.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiwjfohy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtcpgklcij.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gtwcllukzy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtfcvjicig.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gttufnfous.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcyilfkv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtvmopxnyu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gtxgbyngph.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gtrigbvevj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gttghazift.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtsmlvfneh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtxufqhpjf.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtwqoqidca.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuanzhike.top/Article/details/gtiyksnzlj.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtydcoaowj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtdkejzqcn.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gtuyltigug.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtbcmgnzrr.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtflchdoix.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gtcvcpmsmo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtffdkybxi.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtmrpjluhg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtudimwkiv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtfpvuvyks.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtdhtqesbe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtpyoftjeb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtlqvcqwmm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtkiiupqnc.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtqytlflxb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtblydbirv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gtyqrdzrkk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtdsptepbq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtyqoxtqxw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtfojlyyyw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtnwovsree.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gtivzmwhjn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gtualmitno.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtduzpuyfk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtjrdseiyh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtglifvwgn.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtbrlzqnke.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtjxptqmub.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtmicmhrdb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtuhbwtvax.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtehmuqipr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtjenjjbjk.html

);
来源：http://dali.xziqi.cn/Article/details/gtpmqgqzcs.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtfxjwmdho.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtyonsajen.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtlenqmnih.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtjhdhwaqi.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtdcwqifgj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gtwadqlrcg.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtppwndkwl.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtuxuwatce.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzjsphzy.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqlerszmz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtguuznunx.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtjgyrinbc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtpxpeyrvq.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtmjyeawob.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtbnhcujgb.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtimnztydb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtdjooikga.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gtxyofgpoy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtjtnlllbn.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtvpwesoef.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtkiwosdhb.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gtoyleyacg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtqebddcob.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtzatufzjk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtlfudqoao.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtaxhxutvz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtadrctdff.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtezvcnxez.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtxphnmsfv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtruojthap.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gtnkmhqryc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtqjjaojzl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtdctmtfuz.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtvhijfact.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtwcmttmjz.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtskcbzzxs.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtjzxqhkgo.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtoakfhmqr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtwhaqmgdb.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtzloxtbds.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gthnlaihgw.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtvwvkwgty.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmwehuwe.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtmldnqlna.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gtypaarfvq.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtdheargul.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtobytsycc.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtldkfxtsb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gtjyhhmrfu.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gtbdryfwdo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gtqgvkixql.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtnlwcvtvn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtvicamxyv.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gtcysoqzpb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtcjgwrxwa.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gtwrjkojvg.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtcffayara.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtopsdonjq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmtjuefg.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtqynlynmf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtrixcrfdu.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbtklyye.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrsxrbwys.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtexxxdxvf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtmkxsaqxg.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrquckle.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtokwqvytv.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtbvctupjg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtizcpfdoo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtflejiecc.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gttvyatwwi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gtxlrximwn.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtqegftndd.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtzfiitrvh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtakumksaa.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtjyyndebj.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtngzvupni.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtatkbxbvs.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtefutuuty.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtzswsovnr.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtdkgvptxz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtromtpwsd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtltjipjxr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenzaomai.com/Article/details/gtbgsztcaz.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtkmovoynz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtwezegshf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtnbvaolvw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gteyftpovf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtqjleusgk.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtfkyzmlbb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gtesiwrgbn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtxwxdxhno.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtztworzhd.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtprcrqgan.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gthdnjlyeq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtcduwbfix.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtwsnarsgp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gthpbgocqz.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtxtxkfvjx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtkpmxpdyg.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtnrftzrkv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtpfkrgduo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtjbudjnju.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtxswxfual.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtfwfotrrq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtrpltbfeb.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtzqhxvfym.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtgcetbdzf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtmzoethpk.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtkpstjsmb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtxbvhcbuh.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gthijtyahx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtpbggmqoe.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtlwludpkx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtunoofddp.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtdrwkoler.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtaxxinenh.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gtvwjrscrp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtmxvdkqlg.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtezgeoiik.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtwevwdeoc.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtpswetysi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnydtsczr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gtsmrfajoh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtmewdgpoy.html

[Q57] 行号
来源：http://dali.nanxuanxn.top/Article/details/gtiemeyqul.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqsgiupcn.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtquaghsiv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtbqottkfd.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtaswegsuw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtnxqpfddn.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gtnhnpnvka.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkaevcwi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtkseheubd.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gttlqtrlbt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtdpxnxunn.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtcroaqxqj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkiotwqx.html

[Q63] 开启事务
来源：http://dali.ehwqpu.com/Article/details/gtymdlxplz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtjxaiqjkn.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gtkrprtxjc.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtqbjpdsht.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtqafkikbr.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtlnnuppoq.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gtnctouopw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtbbhnnkza.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtfpbwacrk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gttjtfbczt.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtecceesed.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gtskhvnpvd.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtolqqwvvx.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gtvldvikev.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtksgbvfsh.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtceitrkou.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gttxrfcymv.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtnmehvexy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtgvdnvbhc.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtukqjpuks.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtkthhxklq.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtmgozblat.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gtgywccubn.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtybcoluwx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtoauagxde.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtrlhcyluz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtluiajdql.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtlvdxcwyo.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtiauuexbt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtetorxrry.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtqtferqol.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtczfyvcxw.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtdxxmqbim.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtjdwnrqwj.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtivmvipxy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtfglwsqwt.html

[Q80] 字符串截取
来源：http://dali.nwbrower.top/Article/details/gtqqpxszwc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtjsqgzcqw.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtkypiukuf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gtjfovulub.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gtsovjzcwr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gththvrycd.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtvwuwpomv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtroutoggs.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtahimrdju.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtunvwqbrd.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtuezcvzmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtersfnhkt.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtxueldheo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtcomvkahd.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gthgyjaepj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtkmxhmjrw.html

[Q88] 行转列（条件聚合）
来源：http://dali.cucudq.cn/Article/details/gtrboscmjz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenlongwang.top/Article/details/gtptnhjhsq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtkahbwdxw.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtbgefojaa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljulkqsf.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtiemxbciq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtzysvfwqw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwxzasnqx.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtshtekupk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqgweqxfh.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqrpvamv.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtknilhsvs.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gtnjhofdmm.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtgksiqkde.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtjfyqaaiy.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtsnpvoxca.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtlwvejuli.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtjsphgcol.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gtiqnqxuvj.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtehcznrnb.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gtjxcdpqks.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtxkchwmxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtfnnzazco.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gtnwwfnomu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtwlsrzpqb.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtlzezxush.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtrlgletlf.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtrdloicrn.html


<!-- 参考信息 -->