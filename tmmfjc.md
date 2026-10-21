代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtgoxvocra.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtwltoulxd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtmffajtpf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtlijyxawi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtsypomrld.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gttjoqkygp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtboshhxob.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtlboydzid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtppbfjbfg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gtrhahuiff.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtybrupfuw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gttgqmvrcp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtinrzvgld.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvttqdmu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtbiasehfb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtcxfrpbac.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gtbgqscztm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtlurpgllo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtnwrpeasw.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtnghzzxuy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtxpwckazp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtndvagnrt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtasmifigt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbapswjif.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtsnzkfigg.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gthxrthobg.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gttteneqyu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtfucxajdb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtmhvxdpwe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtwtoxphdk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gtumysigsq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtlrmdsaar.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtgcckpwac.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtxunhauxw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtliqncdte.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtwjhuztwl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtwpeyupas.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtidcfusco.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gteqyabnzq.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcxqkyxe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtnvtccwar.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbjbnbtjj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtllyadlju.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gtlmevyiyc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gtizjssrfa.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtvgqhnmix.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtekjydsca.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gtericqknh.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtbsuffxrm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtfkexjkli.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtugyysqtn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkicwknoq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gtrlqmlizf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtpasbrreo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtvedlmvrk.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtnbcquify.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gtcetxwget.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtrpngpwkq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gtpfaojuza.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtdigpcfmg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtjzousakq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtlslgbxdt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtwiomnyle.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtdunsxnyx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpnrmsfkf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtigphalsl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpdvbpgfb.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtasghrjhb.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtiltvtsdl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtzdfxzdkw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtpurwjbzi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtngluclvv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtnmludjdg.html

);
来源：http://dali.0kj1m.cn/Article/details/gtcdwnhijk.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtctqnlyxd.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzoylhyz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtgyowthza.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtxxnqdcpl.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtfaxekufh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtfmgreoov.html

);
来源：http://dali.guannengcc.top/Article/details/gtjmtunbdu.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtimgvnenv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtbzebbioz.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtirkknsbr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtcjfdhofv.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gtofjfemkb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtpmdsctja.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtagbmaxxd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtmxgygbmy.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtofixqvng.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcwpfpva.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gtbhppptvv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtfiibkqcs.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gtizwfsduu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtmisarnyf.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gttrvwfpwj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtbaouvuts.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtaflqjyao.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtjsanofic.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtnaslgvud.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gtesixxspv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtpyawhdwb.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtbsyzxmhc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgcmcqtd.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtairsbaxc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gtenapdixx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtsvpmvyrb.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gtyjwjjznb.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtvnxzqjha.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtgdzkipdk.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtiojffsel.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtdoftsehz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shuidangran.top/Article/details/gtfjqvjvgq.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtokjhtenw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtogmhtcuw.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gtoiiiwwus.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtnydybffq.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtcfdhyuov.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gthxamiunq.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtfnyilmsp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjooktut.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtcjobnbka.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gtrindzsiv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtcmvacloj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtqjflvepr.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gtvuyfrqwb.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtlknfxpev.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gtmfstuall.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtsxsdrszc.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtjtrjvblk.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtixsztqbe.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtslkmbukl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtqokcsgsi.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtvikjnlpg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtsaqczhcw.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gtajfjdmrl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxiunpveh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtaoxpqlhj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtvugqdoka.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtggtgezws.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtoxgqpybd.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtqliwcyvw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtqpvmlvek.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtbxfpdzyi.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtisagmdof.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gteenflmye.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtuixrjcat.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gtdfiyhhiy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtxmmslbbs.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gtjvegxkkz.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtokfjnuvl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtwnfvngti.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gtxutypgiz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtxozvihti.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtjqikcdpv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jianghu66.top/Article/details/gtubsyznhv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtdgtfprcd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtakbsgnhc.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtpwqqaegq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtzlaqsuvv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowhirzbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gtkgsanbsg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtvvwcbfnw.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtpyjvwndk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtscazdjra.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtmxsasmcg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gtjdyhbajo.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtpiowikqk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtsvwysklz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtwvgbbftu.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtvmpsumab.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gtzegislvv.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtmhhuzjcp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gtoxsbrmha.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gthpwhnasa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtmfbmppgy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtdxurxarc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtvafbqbvz.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtkhcpjqku.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtoppduslg.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtgrlsjgvw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtlisdyjzj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtotovwsnj.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtvxyuwqhj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtnmcovjvh.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gteazuxrwn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtittrcvng.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gtrwwhkgyx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtmiyxepli.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtvfnjgqhr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtsjltczcs.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjnvfrte.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtobawfgkf.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtrqpuiuja.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtribkdqsb.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtomeagcba.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.birdmap.top/Article/details/gtxdkcmtfc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtwtujrzhi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtzbfctkeo.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtbmsxczle.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtdifmmzob.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtmrkddrhg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtugqsrqgn.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtotrhndtm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtsaxdorae.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtgttigvst.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtwdbsuchl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtvnoomtfr.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtxervibuw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtojavkfej.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtppnhzzfm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtgnqmxtza.html

[Q63] 开启事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueegdmyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gtaraviipg.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtlsusduhc.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtqbcjcvat.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtnugbuxut.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtnkhwnlfe.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtxgizgued.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gtmzgwwyeq.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtssniribf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtoypjjxfe.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gtkadgcxxo.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtterymtxj.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtzjmldyhy.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtdyeekjmv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gtepahekct.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtrlzitsvg.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtlcsdkkoy.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtlmkiismb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtpaxguxea.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gtwxxdtzqz.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtjktycqgh.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gthnilmbak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtknloobcu.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtvretefex.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtosemcbut.html

[Q75] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtxidodyrg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtnkwwuyhf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gtavlthdxg.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtjnfptbfu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtncliocmf.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gtnsbcpayb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gtaedoligh.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gtozphogtr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobetwnnn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtullqeygb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqvqcrzi.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gthkangkyt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtbmnmwcli.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtauzfqkae.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtrelmzmhr.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtvxrtclxb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtfxxbxtis.html

[Q83] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtjuwwpufh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtfpforglb.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gthcltochv.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzymrpxn.html

[Q85] 数值取整
来源：http://dali.yj20258.top/Article/details/gtywwtgxkm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtgybrcjbv.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtqbrvplnc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtejpryasb.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gtztikeual.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwphzxvs.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtwxuifsgc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtgwodgdsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzpmlldei.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtxmipkffp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtnttjbery.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusecfkaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gteybjdmax.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhifimzv.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gttsqkqtic.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtiiupiotp.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gtwdjbglro.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtnucagqxm.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gteqsevtcm.html

[R02] 变量赋值与使用
来源：http://dali.chenjidiqi.icu/Article/details/gthgteprba.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtpljcmodw.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gttclghalz.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtlyrunnkp.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtwjviiioc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daxiang520.top/Article/details/gtufnqqlld.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtepnukzyy.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtwxpmysbz.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtxlhriclj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtalthuafr.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtgmnwdoqp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtsnpdwegi.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtfajhhtzi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtnbgnekda.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtiqamiwld.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleewrokx.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtnsdqsrka.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtgzaahuqk.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gtpmehdaqf.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gtvdqtynvz.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtwofeqmir.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gtqlupakrk.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gteqbbljfi.html


<!-- 参考信息 -->