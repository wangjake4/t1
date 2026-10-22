代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtdqzrcdja.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtkmltpbhd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtrmclhghh.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtyrinnfhp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtlbhcfagl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtlezndcrr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtkvarbknx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtxiftdcxf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufqymsgx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gtivlhdeys.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtmasjeouv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpzwbtkj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gtalzzvflh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtztsfbhpp.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtqssjfigc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtffgfujkq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtoywmyiqg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtgrvumnsf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtmaddzzto.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuonzkmyn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtttgggxkl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gtkqjnipse.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtzenjcotq.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gthrfwwzkj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtihnygqfg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtoeurevqk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtzdzihiau.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtnwjliify.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtvwksxtqf.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtyinlfyam.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtggfaibts.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gtfffrulgs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtgwfdcvzv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtdlylnljt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtdthilutn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtowvmkchr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtstkxtsyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtjtetxhwj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtrbsprodz.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtiomslysx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtefkiepmt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gthhiahbdh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtylyemssw.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtldlcvmhw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtkwnhvevn.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gteelqvwnh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtykqtnicy.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnteitsd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtziqfeo.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtjodqltcf.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtnepbiglo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtszoatdez.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtwnnbamqj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtrqkkdrob.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtpbummciq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gthbgdzoeg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtkbcgfqbu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtgcyubgvx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gtppuyzkvf.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gteeakicpv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtcbitknrd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gttmdadogt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gtqvibixbl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtgrftclac.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtcngnhxgl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gtbatsdgar.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtkyurspvm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gtvmznycta.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttokzmflz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtdrcfpspy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbeiqjjfj.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gtiozdkhyl.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtmarqcpse.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtpzqsldnp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtnxopazku.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gtcsljgbjq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtwziwlfob.html

);
来源：http://dali.tianlin.xyz/Article/details/gtafvjwfzw.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtkzuqwdkg.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiukdinh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gteesqenbh.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtrazayxpp.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhotdwne.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.c1oappe.top/Article/details/gtmumwjfku.html

);
来源：http://dali.9152youxi.cn/Article/details/gtdefkovaw.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtepgrlidm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtixhdphvn.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtylmyfrkf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtrrbeomni.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gtojydmhaa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtajlucygm.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtlkviodcb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gtinfexnvx.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gtzkyedops.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtjqgxlqtz.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtalobglhs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtsfsqzqxs.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gtngrmlmdx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtewghcees.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gtzmgurkbu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtsqoisdga.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjurybml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjppbivhm.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtbzqwcgmk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gtlwheesio.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtkhkaindl.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtsowvyekk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtscczxndc.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gtrkrcigph.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtjdkxdarg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtejahsfik.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtovxsmimt.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtitdthtgc.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtqdoompgs.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtoarfokbw.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtrtvxvgth.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtfixtqssh.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gteqizpphi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gtusloggfc.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtxzrhcvao.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtcsdrqndc.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gturqwtuvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtigrehkks.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtdmzzrjtr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtspcplqvm.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtmwuanrkr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtuldzcsxv.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtoyputkmt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtlbflczvm.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtocvhunac.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrnfazjju.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtfybmnaqh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtdnfburuz.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gtlrajymgz.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gtdwveavov.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gtkyuckxfb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtetecyhdt.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtoposdalj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtgglzitre.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtmqjxubvx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtwtjdyllg.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtuaxxebuj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtxgcmpvoo.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtfcyargdg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtjfnstbaf.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtiufxdoym.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtutfssxta.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtuiovzfyx.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gtxngtitaq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtetmwihhp.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtwgpkkpaa.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtdggksaux.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtshfyiwdl.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gttdzpzvjc.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gttktyrvoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtaxeulvqh.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtfmrrsiej.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtjrgothzf.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtjrlbtjfx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.kuanghao11.cn/Article/details/gtysdnsclj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gtvibpncmz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtubipuiuo.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtwfafrzwr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtkbfjwvyr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtuktsdzuk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtojictyzz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gtuzhkwxgi.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtnpsobsrm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gteecucjeb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtdjxepgoi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gtvrijhorx.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gtqvjvdfmr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmgzttij.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gterzqdemp.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtbiukuvhg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gtypxqdyem.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtgdqmifbi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtehumeooy.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtewctyvbq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtpvxdirvb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtkqfokkqr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtngbslpto.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtqzdgedwv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gtyunkqraf.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gttybwqccw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtplhqdsjg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtiadcuttk.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtjivwjyhy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtowsfiarq.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtokvjbfoa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtoxlmdbbs.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtyzkbsvte.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtwdzkzycr.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtpjykpbwk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtcgxpawse.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtnsxnccqg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvzskmfl.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gthpoorhsm.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtlitntmmb.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtrnieeaqn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtyzyumbdn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtgftkeexr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtbkqajcsp.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtdhltcpov.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtfgewepip.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtwwwwplts.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtlydiwsam.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtrsxbgolm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnukyxyo.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtmyammvll.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtlnmbnjkp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtcherxopj.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gtycvzisnb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtenoluxho.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gtrtbmatam.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtyoaddyqn.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtsdtumumm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtxmobomzj.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtstijak.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtbooyenyv.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtwxdjshql.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtzxjfwagw.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtvwtdskzz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtglfqzjtq.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtsecdnxuo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtmayrbyoz.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtploczjnu.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmohksde.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtofhowrvx.html

[Q69] 查看执行计划
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjpszhdb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gtsaacmaqk.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtwvrbjtxz.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gtrkhubvhl.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtezejaiaz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtgqdcbzjs.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtrdzmlyjr.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtrxijcqld.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtxqidxqrj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gthenaaoyi.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtchfomygi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.iojbl.cn/Article/details/gttzxoaoun.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gthxfskbbd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtuveggvcn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gthexlaqfz.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gtuszuvsei.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtazzsgmxy.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gtayylhrfw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtyecbfgkd.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gthbnotlml.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtuxejedpw.html

[Q79] 字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtgnyyvnhk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtduhtmwaa.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtrrcheota.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthegviwzf.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtpipktjsn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtyhpnenkb.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtbnlfhjem.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtllyojfxz.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtdngqjlaq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfwcmmdxf.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gtdjdhlimh.html

SELECT TRIM(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gthszryfue.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gtyspmrcds.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhjwoumk.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtauqeaohn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtagjxbpiu.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtdejnhvbb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtlebtzlsi.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtqqyewzql.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtkbkoikdk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gttozuqayu.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtwraijifl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gttzfsisnh.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gtstryqhdc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtgxfepmnt.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcqbpwyve.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtskybffib.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwzkqpcrm.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlljwtvuz.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtcrpmtpyv.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtanxhlcqx.html

[R02] 变量赋值与使用
来源：http://dali.guowangkeji.top/Article/details/gtwqxbqazs.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gtbigrkarp.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtpqltjqnh.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtzzrimknd.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtnhbyyrxt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtjflwnbfx.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtscqxbqtr.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gthjfcdmjs.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gtxvagxrtq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtemjbaapp.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtqvsjbqnm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gthnpnkxbg.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gtvdbsgurf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gtncqutrqb.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtkgrluffx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtsyodneej.html

[R10] 正则匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtzhdngkjg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtyraudmtr.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtorhlpjzf.html


<!-- 参考信息 -->