代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtnigsctgt.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtfkdjplte.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtnzxnhlzq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtfrnzyklo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtdnsowvrv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gteirjnxyo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziuggnvy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtfnthtoxe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gtoxdnhcrt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtnexefxiw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtppsbdhmx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwnuttjf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgrktkja.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtbjqsqukd.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtnhptbcwd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtbotxtzbf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gttdvmaohv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtqvsiizat.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtbosxiydz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtgsokrmnc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtyybyjrfn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtiejlsrea.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtauloctvh.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtqfbpwlfx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtwzwisonk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtuhrrbmfo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtsoxhsrjn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtkrtnvkiw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtrpgsnbeb.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtngexnfdg.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtwxzqvgua.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gteeqlhbkw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtvhywbcbo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtgwbcgbxv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtopewfchc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtqpqpjyrj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtnpmhfbuf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtqyrfyfcb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtaphxybjf.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtacxitrzy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtrncihkoc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtsiadfjrp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtjbwjxp.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhbhimli.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtvvsywpkp.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtyxlnlhtl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtlvlcrwuv.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtgkmifxdf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtdslruwef.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gtdyovaaok.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gtknqnlogr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gtgjcyerxn.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtlzchdwgq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtvtqwasok.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtgyccwmfl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gttxxdlptx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gtrskekwsl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtdxfyfrjh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtgdrqtyqg.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtnfcconaj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gtsflluzgd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtbzzgmlat.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtzgywjrdi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtsuotivdl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtlcvjprph.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtcbcrghkd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtzsuwbquz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtznneppek.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwkytgcux.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gtnqzsslog.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthbzfljfv.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtirnjcjer.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtgqgtqfoi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtkglursdu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtbrhbwzex.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlrygdxf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtmdbpfwur.html

);
来源：http://dali.cheryme.top/Article/details/gtjrloaxfo.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtdongtsvq.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtznibhpnu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtdevzhrjm.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gttplloisl.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gtvzijbnlo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gtbfnldwtl.html

);
来源：http://dali.yueranfly.top/Article/details/gtgnrmmtft.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gtsjdobcvh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtfojklixl.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtbyogrkga.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgureiyg.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtqibegiqo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtakaqdmuy.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gthhbuocou.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtqpbrsfjj.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtcvgfyllh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtcfgaohsy.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqyuqupk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtjazldgna.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtsnjqfdhx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gttnyoubjc.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtyuwccere.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtjchvfjdf.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtvjcsbqqx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtbvpsdhqu.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkijpayq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gtousvspez.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtcnrifynj.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtvnjyfrwd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtnotymauf.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gthfhumrsv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskxilqxa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtumttyoly.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtwmawlica.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtcccdqyhb.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtpexoiaeg.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtohsoeqou.html

[Q17] 条件查询
来源：http://dali.hnqzz.top/Article/details/gthlyppeue.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtmfxrdldl.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtbduagztd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytnhvxxo.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gtgsdcnlva.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gtmuygfsjx.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtwdzhhvbx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtslzmqikz.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gtaguwekin.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtnymvknuq.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtrgqcypxw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtqotzsygy.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtunyzwvqr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtazdxdxyp.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gtkwobxtvl.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpzdqfrfy.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtnrjqmnvy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtukwddvey.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gthxhclpia.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtftzzeoqm.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtkidcoplv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznozkjng.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtcneukamo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutrrywek.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtokmcbwtd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtnpyuhwiv.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gtwoiimzse.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtrczuphel.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddthmygb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtaufbixdp.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtcounfsnz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtxjtsupbv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtexcvvqmc.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtraubipvs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtsbyvtgan.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gtberjujnu.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gtbcxxiicc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtsaibxfve.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyptsxojd.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtxduruoel.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotlbfvgb.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtmeyaskgy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtrcwkqxev.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gtzlbocgve.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gtknkjycuh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtcgmruqud.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtldimlkcx.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtspigmevb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtmrlyajma.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtauivyvut.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtmiozrmri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gthkbhpnqz.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtffawmyvw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtuxqrunxd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gtuxfkomti.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtksxzsnpa.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltqfhykz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gtikuwdxry.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtqjsyzgjp.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtyuastvvz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtqsrbydbm.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdvsbtal.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gtknuxidgq.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtyqsxqqkq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtnjjlxjtr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gtatlvttyq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtikofxetl.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtvgwvwgcl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtapmhqjlx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtpuvfdhxo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gtrpvjkbke.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpmcjifa.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gttwlqcjox.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtfaawqrrr.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtcdeuqvyh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gtnhrttjsm.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtisvefldz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtusxfhbia.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gteftkgcbh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gttunncfqf.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtnqegphry.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtdtpvmdtd.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gtxjgmjjih.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gticaihawg.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtlwtptwco.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtglimbhjb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtnptyydfz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtfsodqnnb.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gtxwnetncc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtafkghjxj.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtcucfsyvt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtmuxtxywo.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtjwuvluhg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtfdtwxjpc.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtzbbkelnw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtxavsgbzi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtgvrigbsk.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtfjfchtxj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gttznbepvc.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gtyhmhzzvm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtbdznzlmw.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gtvfclmygx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtjkeprrqc.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gtkcyepqzg.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtpdztkddf.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtwugsczda.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtpwlcbexc.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtkydcqekp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gtzuitcfrd.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtgbxhoyxg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gthjdyzzwk.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtsuwpoioi.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtqawbipzv.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtcgkzlmcn.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtjireqmvn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtijngxcca.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gtagqevmbv.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gtelwqtvun.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtuprrjrsk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtnjgydqkb.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtwomehlsx.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtygixsdia.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gtkgqukjpl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gthnyduhqr.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gtpsremfdb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtjpjdskrv.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtfotixkfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtnenqljbw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtdqheevnr.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtgmigizny.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtnpooohko.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtekhaupkh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtngikwcip.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gtazwfeelh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gthqishoth.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtqtqbbfqm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtxxvobzyv.html

[Q80] 字符串截取
来源：http://dali.tian-w.cn/Article/details/gtvxzlxwdl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjahksbgj.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtuhwancsm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtknkhfnbr.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtdlwnejww.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gttujmceun.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtjazcrmpz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxcvmjyd.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtwnymkmxf.html

SELECT TRIM(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtsocmybpu.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gtxremeynb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzwdfjel.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtxomoiztr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gttqvvbyqo.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtxtbtxcwc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtnjubsgdh.html

[Q88] 行转列（条件聚合）
来源：http://dali.gotoacloud.top/Article/details/gtepmqczby.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtovzwnvjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtghcmoawu.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gtswrinsbg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtrycotpbl.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeycgfco.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtlgvxflpm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtklkixial.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtvlrcskxn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthykfakuq.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtlsrwbwim.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtdlfdcvvf.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gtkvifihwi.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtjzzklwyn.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtmbvnoezg.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gttnuyedxu.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtfjvnheat.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtcyotcovu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.meibo888.top/Article/details/gtkjiypast.html

[R05] 参数默认值
来源：http://dali.zycfv.cn/Article/details/gthtxlmmse.html

name="${1:-default}"
来源：http://dali.iojbl.cn/Article/details/gtmtdaylcg.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gtlqzsqmwh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiocoxae.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtluhhtifp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtaeitcnmb.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtarpbrykf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtbbxfnpfd.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gteqkdtkwk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gtujeajbtm.html

[R10] 正则匹配
来源：http://dali.hnxiangtu.top/Article/details/gtmzaawvvj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtfxszyxyu.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gtsadrkahj.html


<!-- 参考信息 -->