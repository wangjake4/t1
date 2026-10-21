代发 wailian999

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtznlfobpv.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtiaqkcdht.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gthxsdisrk.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpaihvur.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtgnwomwxd.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtasdwioen.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtigtxrpko.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtuohcsmum.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtkrlohvwl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtvulwbxrv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtlygrqbkq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtwsdcodfm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtkcnrblaz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtmjoleacp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gthfdabsmt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtqbqanf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtanfquldb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtoqiolsoe.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gthadhlwsn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtglosysph.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtijcdkzeo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gttyokdbjy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtjaehabai.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtqxzzyblf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtvqeyqlts.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtidhkodzb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gtthydatmh.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtrqsdxowb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtloqtxmmo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtwrczcieb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtgrujkxwi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtjpgilfrc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtajwyjacc.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtwfccyvxv.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtvynbnahg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtuiubwxkt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtcvsethse.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gtnbhwrdxg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtbkaubeoc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtbadctaat.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtmhxzuftm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gticfjvkgu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtkrwkkyfp.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gtobldtqqb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gtyfcgtbyr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtmhamqicb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmmagaut.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtwuykevam.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gthlceecrw.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gtktesrrgr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtvplhtvqf.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtlcwgalmx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daria6918.cn/Article/details/gtgsxmjsfb.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtbfmqqwic.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtjxunqixq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtjfngjmry.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtubqtblmd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtskhnixhw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtdphvnymx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtgxwklbvc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtjwowxjzp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtgcdufdbp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtjqckjcyk.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtkghbesbq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtdiztfmut.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gtdrdjfkbs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtphvuqdml.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtzelmgfrq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtdlhtuqee.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtmtfvmvvj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtthzkycsl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtzwzubxxd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmkyntyei.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtykyfpydk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjijmdrpr.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtjlzwhkwc.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtzgqhhwpm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtxznscgyl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtqwnlgpub.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gtzmrobwcr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvxrkakt.html

);
来源：http://dali.daria6918.cn/Article/details/gtunbsirec.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtkqgutguv.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gtcxkwqoni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtpyzyxoij.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtewapbtof.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gttribzdvb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtqrgjtuan.html

);
来源：http://dali.hammf.cn/Article/details/gtzfdjdcmf.html

[Q03] 增加列
来源：http://dali.bjfxy.top/Article/details/gtqwaptmik.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtkzieeqhc.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtgzzlkmkb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtbjabxohg.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtsvqendmv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtdzgdeamx.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtgogmomzl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrskxduxi.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtkcryvqli.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gtglclyhtq.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtisiykgzk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtiumshmcn.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtzueqbvld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtmzxdqlrr.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gttsxlxzdv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtdpixcsgm.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtgrumjtxz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtinvlkbic.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtdfnvrltl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gtbhkrnjcx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxzxjggv.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtatmvaggl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtmzqolppt.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtiklvkhxj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtzfmsdjll.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtqxnklvgx.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtwsqrxoli.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtvfmmhajf.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtwuskcnvk.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtbtqervps.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gthirlxcuc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtboxpdljl.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtatzvylwm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gtgpnauszm.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtzrewmjss.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgemjkeqm.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtxqxlaywd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtuwetlvjm.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtfyioiymr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtnlhmwnsj.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtgyofyvyt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtyngrkcjb.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtebdfbizk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtdmfgnzoy.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjupwzogn.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtekjeeumw.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmtfjfrr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtntbixmoe.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtismtjmcb.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtqxcabzjx.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtvoixldpd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtphmkwyzn.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gtcaujbfqd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gteqngaaog.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtqfehyfgf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtuhzsoulz.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtlzhkidrc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtyccwfvtb.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gtbmboflof.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtcummakwo.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtizpsycdt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtptpumzsd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gthowcbpuk.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtouzffsby.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtcwnzgahw.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtpengehov.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gtlbmaqlvu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gthfgriaro.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtovmdvnzx.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtvbbgagvx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtsygodexq.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtmqvcysrv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtkfzqefoi.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtccyydazp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gtxiursifi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtgxvdmrej.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibexjrlh.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtuugodgcn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtkbmlvxqp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtwzmxpytr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtvvvvntuo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtyswnxnpn.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gtavgaxakr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gtjnkdzmhg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtarvzqyti.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gtzyfeabco.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtektgousb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtnkeqzoiy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gthfllmexy.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gttbftxejd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtfckmbisc.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtkrbbakra.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtwgadbjep.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtiiwttzmw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtwikgvkqg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gtkyoaygys.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtlagdnbdg.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtiujaudet.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtihkxxggk.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtjxupvmaj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtbaregmpv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtpkslctju.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtiaqofymx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtrffyyjis.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gtjpfytqpp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtnqqoygtq.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gtebltwpfj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtxwtaoxlq.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gthwqanskg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtlbgkiwmv.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtxctvopeu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtcmchatoe.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtqjqpalew.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtaqhcfxcz.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtqdcdnhcn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gttezipwhc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtrlknexrh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtqvoedxej.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtlojvqelx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtpeppmqie.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtpvysqgpq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtpmepigxj.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtbpiyffmf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtavdqdsrs.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtxqxlnqnd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gtdeessvyo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtruravhdn.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtoizrtusk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gthwqkaoos.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gtsnnahptx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtsmwfdmlw.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtduixvoeu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtfqlkremi.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtryeptefh.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gtcvrkgrwu.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzgknyrz.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gtplczrcar.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gtjpzpvakf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtyvhfliqe.html

[Q67] 设置隔离级别
来源：http://dali.ydzc1.top/Article/details/gtzkeyqgsl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gttuilmgvu.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtphzvrrxp.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtzyewjftt.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gthsyjbzyy.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkycclska.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdcrebvq.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtleahkqjc.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtmmjpuklr.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gtaozxbuzt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dashuyun.cn/Article/details/gtvssrruag.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gttqbgmgsy.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtacpquznc.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtotjgtmut.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtbozjlitw.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtpdexocfc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtwmxnzvny.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtlyvwmyqj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtswkjfety.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtuuljxrhl.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gttotoxayj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gthjzvsotn.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtyzyyabpp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gttdlqrckp.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtdwxpfgac.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gthjddmhkw.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtwlvjduqa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtatkbdqhw.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gthlfdhesq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtpnepzxlm.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gticteaiwe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gtvlwiixxt.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtlhwktohs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtahwerziu.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtgfamrcyf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlrztygco.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtghfgdray.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtjdpudgxp.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gtmdjjnhie.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnxiangtu.top/Article/details/gtwwjqvwyh.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gttujvssrz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gtxfygvsoo.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtyrnfnssh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gttmktaalr.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtufwxtjgo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtunuzvwrg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtpowiksti.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtzxejkydb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtczsrqwkj.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gtzahwjysy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtxtgmqzds.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlcaqvnx.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtctsxdmiv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgmkbcuwo.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtwbrozjky.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtvdhrnpih.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtynfwuaqz.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gtdwjtnqse.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtkvqzqcmr.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtjxxwqggo.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gtybkbqdll.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxehjlkh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtutppzznv.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtlaiqazfg.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gtktuybixz.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtlwvplcas.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gtlrhwvwkz.html

[R07] if 判断文件
来源：http://dali.sxryk.cn/Article/details/gtnmmmexwm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtexozmgws.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtkzftgmhb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtyzeiqgqp.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtcwpmjmqh.html


<!-- 参考信息 -->