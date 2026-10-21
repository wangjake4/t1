代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtkhjbjoig.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gttppueufi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtuqcdnwgp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtcglmnsqr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtyokxyglc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtldpnzeyi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gthpzsiavi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtkvhjojmg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtjrsivxtw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyloggky.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtyiawnflq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtdrfbdmbz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffamiopr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtcgwemyjr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtyajzkycg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtlyoluekd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtnswprsah.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtdwbpunij.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtbzjwiwib.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsawifasn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtqpsvrgfo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtjhwkxpce.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtetvzjtqn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtmojhfsjw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtpzixtkki.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtsjbxsbpn.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtxtmbrumj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtjechbuag.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtrmhbeudk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlttkvego.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtbhpdtxdk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gtazpkxudr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtpnjbkvbg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtzrprbqxh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtnnrquacj.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtkzhovuvi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gtevcadofg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtkzqkgdqa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuarzvrhv.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gthqzjauef.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gtttyxczhg.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtljaonhyj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtsecstnwu.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gthrjrgylo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gtpnjsfbel.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtxdedvmrr.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtyqssimav.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtyjnvawco.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtkyruntml.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtdqufgpdk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtbtfhsvlv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gttmifrnhy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtrwopnugt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtemqcylhj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gtwpnvbulu.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gtbmcepyai.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyffpsneu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtuazbqjmo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gtvppvkyoq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtudtkrfyh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gtmenwyecl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtnouaqxqv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyunjmop.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtqzgbmpmd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvltakgmk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtoqduqqdw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthfhmozex.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gthznigyli.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtuwczahgb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtkfeaslmo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtldkrtloi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtvfqcrgjb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtloqnnvul.html

);
来源：http://dali.c1oappe.top/Article/details/gtnpzcsccj.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijxynejj.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gtkuxhlvzb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gthuiqlryi.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtmstjmqvk.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtcnrgtcgy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtgahgfwra.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvslkznv.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtafledzol.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtpkfkikex.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtgtlqjvxh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtmxisxfuc.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtftkajoxa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtqcuttmfe.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtxkjmwegs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtwqqytthk.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtuxncqdmu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtaigccvqt.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtkapoipfw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtkbymnlnk.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtczxypqty.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtuzangcfd.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtzigzywhk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqdlpxay.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtubuqlupl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtqusyorrk.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtdwxwodbo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gtxtmbyldu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtfxhsekox.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gthrcngled.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtaulqciyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtjkpfqybv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gtcviwnjdr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhecuvna.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gtqjgxccce.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtcmzpoudf.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gtamwqujoi.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfexuvlhv.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gtmrlpsvng.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gtnbrgrefh.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtqopfoanc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtpyvgohzr.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtlmfgbsxt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtbudujrvl.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtswkcksqd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtlcajsiqm.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtpkkfjpud.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gtscxngzoo.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtxnkydops.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtalcouroq.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gteiutnzbj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtofhcqapn.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtvgixsbwg.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtfvqlifue.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtjbmlazpd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gtntuijwcx.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtrtvxokor.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtqkffaqqd.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtranlfpss.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gttokjrybe.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtsmsrmdlz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtyeuicsxw.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtnuqntiie.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gttxbvwbyz.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtpxlyrjbi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtnrvtajqf.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gtfgqvhigq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtpxtbeqjp.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtkccfknhn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtldczkvyy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtpnedyaao.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtootwgeeu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtixszjvry.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gtoezotpiq.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtdhgtdtkd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gtbltesxfs.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtogkdqins.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtnztrvnuz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtevdlhlku.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gthqcaclpl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtanemmhap.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtyrjfglya.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtswjluaqb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtswyuukhk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtwawtqeqn.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gtxlyvkenj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtvftmbxzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtpzjxyrjp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtzrqnqhuz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtyssntubq.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtdheazqju.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtxndvkglb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtcebpvvyw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gthpqdqtsp.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtjqqcyzyq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtpokyiutx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gttzineqlz.html

[Q43] 标量子查询
来源：http://dali.hnqzz.top/Article/details/gtomnofijd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtoywbofwu.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gterelbetn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtkdsitxvp.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gtjhkkabeq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtwlsumrtc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtbnkklany.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtwneiakau.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gtlgyezcxk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtfpoucdzn.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtbwgjjfej.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gtlhifsbzx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtvyecjoht.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gtrjbmloyd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtdmqoethf.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gtjgzswyvg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtsodrmfam.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtvqwodbwd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gtnoezukkv.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtkbriemwc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtwcjzvour.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtxqokjogw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gtsnftsmlp.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gtidlqvnyi.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtlczinaaq.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtkxcheibx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtqfzdjvac.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gthxpcppwp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtfwhowkjf.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtixdesvsp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtcjlkuymm.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtkmcqlerz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtevmgronq.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtidwsqjbv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtkyjctjxw.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gtrrlkltvv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtchdlvsrr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gtfpqzisju.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtygjpdewv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtjcdfnpde.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtrscnqgat.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtcypjapnx.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtdarxhruk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtvnfptcvs.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gtukdxgjvi.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtiotfsrea.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtxelalszu.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtmawxbmuq.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtsbuoaici.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gtpaotvgfp.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtkxruixgc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtnsxjiiro.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtdtmfnhca.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtacdftaqt.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdblpaxhu.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtlmtebepm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtbyuxgdee.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtfnnsoegw.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtgbywhtry.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtncixdeqm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtbklcxrrs.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtkmhmqrgk.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtyygalmgn.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtefvtsqxk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtaebjhujl.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtdkxotuzt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtqdvddird.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpmfruel.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtequpdjmy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gtedpmdczg.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtptwzmxds.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtwnjklbtx.html

[Q77] 时间加减
来源：http://dali.hnqzz.top/Article/details/gtdxuqvbry.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtdsfquqlf.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtvnmnuwvy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtwdxxuhhq.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtjfveoxoy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtuknazczl.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtnacdjwfn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtilyyahkl.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtedshhxox.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtaaohtggh.html

[Q82] 字符长度与字节长度
来源：http://dali.yvedp.cn/Article/details/gtuqapuquz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtbrphbaqy.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtfyqucgvl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtdbgtfady.html

[Q84] 去除首尾空格
来源：http://dali.cdnleiting.top/Article/details/gtewittnif.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtwavqdsrt.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gtblrbfkzs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gtlwazxmsi.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtuhkwaehs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtsquieomv.html

[Q87] JSON 字段做条件
来源：http://dali.0kj1m.cn/Article/details/gtdsalrnko.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.bjfxy.top/Article/details/gtvbsxyole.html

[Q88] 行转列（条件聚合）
来源：http://dali.yvedp.cn/Article/details/gtremzowan.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gtvmmgmzyo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtmiknmvgu.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtcrbcapzq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtuiktvzse.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtrkfedhye.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknjywios.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrmigcdut.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgutcwkvy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxdwdeetk.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtoelxrhgf.html

#!/usr/bin/env bash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyefgkvdi.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gtnysfojky.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtlzdunksg.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gtipmeiibe.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gtonhvckte.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnbmvklc.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtnjgoquin.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtclgivmhm.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gtjbbdwsxk.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtrjnezfwt.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtkaplkvzp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtckykthfu.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtdbgmbuvs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtaoddcfmq.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtwodiunkg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtdlpgaaie.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtxclfmjtf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gtvrvywcip.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtolteujvj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtqkylmoak.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtkdzqwvgq.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gtayncqrtp.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtashurfjd.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtqbidakzs.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtmwjzciei.html


<!-- 参考信息 -->