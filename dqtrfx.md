代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtlsslmchc.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtasrmdalg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gtfoucltxu.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtohdvjooj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtriphqxue.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfcqsssy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtwybrsrti.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtfeylydhw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtxpcxgxvy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtacoixcso.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gterwibecd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtxzlyounz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsfiiuwox.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtvbuunifj.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtruqjyijb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtprcldeqg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtweommlop.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqjvaske.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtlhgzypgy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtuizzqeoh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtewphanoq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtirpqkzvi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtljskxyhy.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtbobakcph.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqhfavls.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtwkhookzm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtgaecnjkt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtfvmohhzx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gthvhdpdkn.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtxsuvttql.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gtrfvalzpe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbuabfpx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfulmgqcx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtmtzifywc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gthtqfjmkp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtbjckiwtu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gthfehncmx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtufalqmsx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gttwjcjhyc.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtlfriqluc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtdkwgxbfj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtsjyxeqhu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gtwfnqvurl.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtufwzordz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtvlonzexh.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtfajjcxah.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtzhotvety.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtbfpheibu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gttcngasrl.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gticwikrob.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtnmmziwxv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiyaztxe.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtdwingvja.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtmjsxynla.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtwypcaylb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmafsstj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtkrdfukte.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtbphupsya.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gtejqcieeu.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gtdxaiuybu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfxjkxpw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtockzxsne.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gtxqehhcjf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtquzcdhiu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gtuzylhkae.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gtspnpmspb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gtwmoloctm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtostlelqu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtawdnolsu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtqemdlryc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyahyeeww.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtztpkktoo.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtyfwdusjr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtrqzneidr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtjuzjpabp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtfbrkaclw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtdkqcfzey.html

);
来源：http://dali.cheryme.top/Article/details/gtksqlirla.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gtuzpsvpxa.html

CREATE TABLE orders (
来源：http://dali.birdmap.top/Article/details/gthhwiyabw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtgeoykfdw.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtdpdmiytx.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtlslxnryo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtzzwzfevj.html

);
来源：http://dali.tanke756.top/Article/details/gtflvbvprn.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtcyscyosy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtlnughwoc.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtirpqxfua.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiersadyn.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtdduichom.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtgezhvviy.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtalrnarpj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gtvbbgunaw.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtotqunyeb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtbznacwju.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtofvrjhoq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtniyovqzq.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtgoilbvlo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtqtdqvbnj.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtmotmnmkd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtrpzswyyu.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gtixbfkczn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtwigghbbo.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtgwaizowj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtrflehpio.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtzmzybnld.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gthoxysxqy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtgbfqgkxy.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtovkdjtpa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gtfmnlxsef.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtomyfdjvg.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtifciihta.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gtdtgkmcnb.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtumizeqgv.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtenzzjfzi.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtkivqweiy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtovzlcdyb.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gttumtrssr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtnyofotnx.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtbgqpxhfu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtslijxycd.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtatnqsovv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtzhujxmol.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtjmgemepa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtbyoybrme.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtwgoqyhxi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtiqivvlel.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtrtfvwqaf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtccdzhjvn.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtgdbtolso.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtznaikfbb.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtyavqcluo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtrzcbwohp.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtasprnzgk.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gtdgzulqhx.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgmyilal.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtppccsqjb.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtereoxwzf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtgieclofk.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtbnpqytao.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gterwpqngz.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gtkglwonvm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtzjyqyzdq.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtzhongotu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtjapbljtv.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtripshiig.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgwopzsn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtfhbqlogv.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtzzcvxnbc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gtgoijpdtj.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gtpjhpkzys.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gttutbncjp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtcphcvrug.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gttbybsgfb.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gttcmcxwtp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtzafxvkur.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcjsffwc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtarirkojq.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gthtxevquu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtlywrxvqh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtuakmvryy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtprrjmapo.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtueivayum.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtegcrxbee.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtawmlsmxt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtafhetnwy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtoiallizd.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtehocqjqz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtttegijua.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtfcbijrgq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gtamlivabn.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gtelmurnge.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtxmzcaayt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtohsqhrmp.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gthkdtpyhw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gthdfxtzvo.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtsycipdhs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtdrdsqcmv.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtyuwgqlve.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvadxfyhv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gtqztjugcd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtyjnzaxpw.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrpxwwit.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gtpxzkyrip.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gtquccqvmx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gttawlwcki.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinljosat.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogbfmyqe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtwrmoafev.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtzfldnebj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtuqvhrqqa.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtwqkyoymq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtfntzuxra.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtfpvgxtfy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtvfnxsren.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtwtbormxx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtlvrysjgl.html

[Q54] 清空表
来源：http://dali.birdmap.top/Article/details/gtxbbdsmsq.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtueskkfim.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtimtzmlgz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtvhipuroc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtaeietltp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtlvbpzmzz.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtdlsaumpa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtibmyrqvm.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtrnansmsz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtcxjydref.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcbesnpd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtkdybbltf.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtavumxeze.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtunqavmju.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtmbtvluci.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtgfpsmiqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsattixb.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtapytrynk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtaswgjnhr.html

[Q63] 开启事务
来源：http://dali.zhengqikj.top/Article/details/gtbbzysgnp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtzjysinfu.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtlqvxpexv.html

COMMIT;
来源：http://dali.ivvv.top/Article/details/gtwzxqjjxv.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gtriwvnnlb.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtbyaieghf.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gtbpwbtosj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtzfjjwplr.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtuwpaozrf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtdzollayd.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtvmpmpalq.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gtkvzuicei.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtpgwbrwdp.html

[Q69] 查看执行计划
来源：http://dali.yangfankeji.com/Article/details/gtdqpfzmfm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtaeqkleau.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtzzuqwzri.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtibzjhehm.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtlghipnxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtjzkcokuu.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gthzaxbujb.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxaykeeop.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtiwmictfn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtnirjyrgq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtcgeqtkiu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtcuqaxstd.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtvjtbisrh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtgyjynhsf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtqiqfmfkb.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gthlzsytbi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtjnjymqyb.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtdnvulwgg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtubedzuli.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtplojdybi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtfwfeoasa.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtdnjoprip.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtxyzpklkk.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtepcflkhf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqertbcng.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtkyfqbods.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgbughwvo.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gtwxsqkmul.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtxulvdyvj.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtdtyqwyjb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtsxsqalfb.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gthggwpgtn.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzlcjeoe.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gtbzoqxcsf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtcwapupoi.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtbzfjwnyq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgufenzy.top/Article/details/gtnuqwcuww.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtuemyhiyc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtekqgqsps.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtpuwvegsp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gtnuldbsjb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gtjubvvkql.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtkmxhhqtc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtkmivavfu.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivrnyqwv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtbxbokebe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjydvfmxe.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtstzrcwgh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpnqxrmvn.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gtczdbytrd.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtxwijojlj.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gtltfqmbvg.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtfsamxwgn.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtvdvzvisq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gtswzgbzel.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtfgkhlzrh.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtailqdbbt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtvikcmuqk.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtoijgmvzo.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gttdniojvr.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtqiakgsyd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtevnucpdr.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gttenyescb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gtxhzhflhg.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtbgydlxtz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmznrewf.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtywaspxoa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndvsvdra.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtikdqvgyo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gtaulvlwkk.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtewiprtkr.html


<!-- 参考信息 -->