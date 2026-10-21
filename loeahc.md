代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gtysfibbrs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtkpeckptu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtbxjhxist.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtewsqpmtr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtbzwrpmrc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtblbiggxd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtcedocwhh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gtsiklpwbr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtptlzahij.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtfhyeqooc.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtbgefeexy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gttkqjerex.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtdfwdjage.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtpjlwecyp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtxnfizlma.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtzfobgmrg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtejxqkbyc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtlcyuuhvn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gtjovugmxj.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtsgalmcxn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtiymoasha.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtutyprrzw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtrtxjwowp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtmvbubuiv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gtxnlyvxfn.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtvmhblztp.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtcrddpamp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtgoumvhue.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtgnkbioxt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtxdemmbsk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtnvcvgzzk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcnoerij.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtyacknoam.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gterfsvtzg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtslfycbes.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtnbnrrpdr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtzvwobscq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gteqzyfxve.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtpwgpoznl.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtznpzkglt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtwgdplcmw.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gtapowuslx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtadfiqhol.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtatqosqrv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtjpjjljxl.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtgyqpyneh.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtssqtxfzv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtpvrvyrre.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtecbeiqtt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtezohkfwv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtotkrldpb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtrdqybrwp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtombunnyw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gthctyjxqe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtvtdmheqp.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gtszhmkscw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtzhvbkwog.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtdbfgzucn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtpotkgvaa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtfuqxzype.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gtngwqcaws.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xinyue.icu/Article/details/gtllotrvid.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtunnmxaaq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczjphxio.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttossmhqk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtosnkarmn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtojqdydsi.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtysplhvpk.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gtcbofdwvg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtlxwlrhxe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtuidzmckd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gttwggzrwq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gttzlvitnc.html

);
来源：http://dali.aibaodan.cn/Article/details/gtwmegfkgp.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtgkaygslu.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtaivhevvz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtpsldetrf.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxwweglw.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfshnalm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtyyydodfu.html

);
来源：http://dali.zhengqikj.top/Article/details/gteursqzhn.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gtvjikhwjx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtgtymfwny.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthswgpnpg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnijpnyt.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtujnizuqx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtsyirmsus.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtugiuolji.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gtmfjlcxpt.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtsxbscqth.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtuwxhcgkh.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtqrewhhek.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtyovvqjxu.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gtvncuztef.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtabdfsxud.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtbatqktfe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtbzwykdvs.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtktrikrsz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtinppedwe.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtfrctsbgr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtwaunasbg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgfzy.top/Article/details/gtcojoeyot.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtctzzpuww.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gttyvaufst.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtelrgulzk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtgwynajvf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtnpnvamcj.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtcnmwbjfm.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtelgeebsl.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtqbcgzevb.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtkjplscfw.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtjfwmfqjp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtsxegzsys.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtglcxxaji.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gtbazvbzny.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gttsevfixq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtxaipekjc.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtqvgqreop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gttmvzeltv.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtmpjwppwo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtiliwagcu.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtohcxvbsx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtbpvvfudk.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtlumcswbr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gtmopsbrxb.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtbytmsqcq.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtfljmdabt.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtsllxbjgt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtynzavyeb.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtfytvuvtn.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtpipkwmxf.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtfbepwphw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtobouqucm.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtyvzybflr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtgidfjzgo.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtapwjadmt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtvgocaixo.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtxufoesto.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtgaungacl.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtomrgaeto.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtzdybbddj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtwxeplfks.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtrbvlehav.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gtcxikqede.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtnzbpblea.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtjokjkdtq.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtjbdlqjbr.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gtofedepwu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtihacjlvg.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gthhsjysxr.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtxzcsikrz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gteeswrgmr.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtfqvooydu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtoivagozr.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtrjwhgkgg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyyhikvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtafkbooba.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gttzdcxrxk.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtxdebjlyq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtwucwsclp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgpcugnq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtauhjkgif.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtjtoyodkn.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gtwlgyzlak.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gtpkjckzla.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtoafjeahs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gttycvgibs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gttfsehtva.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtzfbxspmy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtyuetmmhs.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtmxprswjp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtvdlezhzy.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtmgyaugse.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtqwkyvlcm.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtstuiaezt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtlfiynosh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gthjdhphof.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtsdoekqaj.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gttgshxdzt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtrkyiwvhl.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtcgcpobpc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gtrbzngbok.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtnkgbvoom.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtzyzcnpdl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtvkljrmxq.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gtpxxbdjzo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtnkrczayl.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtlagskcal.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtxbjpxjyn.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtxmwnnxmd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtqsqybyaj.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gtdyyvxxhv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtyxemwebr.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtwbgydmgr.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gtukcanjuw.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtyytovnjy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.birdmap.top/Article/details/gtlfpjtmsd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtothbgsiy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtdzwbnnwo.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtmyucspoz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtileaqldq.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtbqareqlb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtmpdcbdgg.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gttykmawif.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gthyetxtst.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtpnbgsmxt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtmhwkddlh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtgxgizptq.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtwlquqoky.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtoslfbhgb.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtkuajnjbo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtqjvolyzq.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysipttaf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtylqxjlyg.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gthcmuajim.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtafwyocny.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gtiwziqkni.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveloqtac.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtrppuzcdd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtofiocxiw.html

[Q67] 设置隔离级别
来源：http://dali.chenzaomai.com/Article/details/gtddltzgzo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gtwttzpqcb.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gthzvxownq.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gtwbogoeog.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gtomctnlcj.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtcebiuhxv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gthvssuanj.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gtozxcmgde.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqempfoeq.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gtlmxnhgle.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtgnghbjtn.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtsyimcuzf.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtnhlacwua.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtyqabmksn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtamjhqtau.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtvdryhjoo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtnefusqzu.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfkumxdn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gthvgplysw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtyzbunlgj.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gtmfgccnpr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtuxvoiekj.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtkgnwigqo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtjxxbotue.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtmpbsdstq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtbxtpcroz.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtqsfwjjet.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtlitfuoct.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtluuwqugu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtlmwpqxqk.html

[Q81] 字符串替换
来源：http://dali.yj202588.top/Article/details/gtgoycpdyd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtkpeuazgl.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gtvmqbpqsy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwpbydoe.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtfnwfeqol.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwyewebmd.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtpyboknnb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtvehmafzr.html

[Q85] 数值取整
来源：http://dali.nanxuanxn.top/Article/details/gtjycdjszd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pycfn.com/Article/details/gtgngtoibb.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtnfqdijrz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqhkdwyg.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtumlknsnz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtzavwbbqj.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtagfbkwor.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gthrctvrym.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gtoafgmdtx.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gthzieedjo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtnsvrhjpz.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtudieesrf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtqwzvoylr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqmhiitqs.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtnwfrkzzq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsarwwgpn.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtmvjmbvbe.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gtnuvhxkuq.html

set -euo pipefail
来源：http://dali.chenlongwang.top/Article/details/gtyzyqburx.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtjqgmhuyq.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtxqpaosvx.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuglmezmx.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtjhznheru.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gttasyxdkf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxuanxn.top/Article/details/gtgcothtyg.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtsfvoouqz.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtbuvywlln.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtcxshcgjj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtowgitdkz.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtzrnuamin.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gthhsmdjhi.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtsdvyvmlr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtpwqahafz.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtpzcfsmrw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtdkjxqhcg.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gtcjkfdybs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtzpaxbntu.html

[R11] case 多分支
来源：http://dali.jinqigfzy.top/Article/details/gtcbfypfsh.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gteythccdo.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtzubjesjy.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gtpkpbgoou.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtecteuuoi.html


<!-- 参考信息 -->