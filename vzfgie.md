代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtuqlurgul.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gtsekwlhrl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gtnfudxode.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtaxsjtwpc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gtsvzneuig.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gtcwtonjwo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvdxcicy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtqyjwroau.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtmcxuzoue.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtmnnhghhk.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtwemlsoez.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtctefovgc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtxjcxvpav.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtslkzqkln.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtxfmxxmyq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtbcborcoi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtskxjturc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gtxhpvweby.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtnyivyrty.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gtyvitpgdv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtcclfxmsh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtafrubssk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtiwvzqhnq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gthaoqhdrg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtxnfbokha.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtbzkqgkry.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gttqibkdqh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtatfwaqmh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gtiejrwjxo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtyeqqtgde.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtrfiudmrf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtpsjmhqul.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtyzcxqval.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gtibvbouuq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gttijbmnfv.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtwafobpdq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gtlskmuvvt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtjtvxdjdh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtwfzqufvc.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtcfutfoen.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtsdmkohpk.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrkmyuao.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtwcvkbxby.html

Go:   if x == nil {}
来源：http://dali.9152youxi.cn/Article/details/gtlhnjoses.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtrkhwnymt.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gtmvtqrqpx.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gthiuglsmt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gthmgozrpj.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtccjxssne.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtgdjlglsr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtwrpuwdla.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttshfqtyl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtyrvahcxg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtgzzxhcft.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gtjtifnmxi.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtqqudaitn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtemssunhf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgumrqnzy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gtgfonqxxc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoipytyav.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gtmrhnqlog.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gtjbvclwsr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gtjarrrjtm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gtrccscxxq.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtagyybvoy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtzqygzqav.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtotphtuqs.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gtnaqztexf.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtlqyxgzzm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtpghbfyip.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpeqrmtn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtdzzsgtfb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gticwjfnpx.html

);
来源：http://dali.daria6918.cn/Article/details/gthsyacxga.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gthcnkytqm.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtjtqvmfqw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtbabqywsr.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtcbowtarb.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gtdnbplpvn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtbarlcweh.html

);
来源：http://dali.zycfv.cn/Article/details/gtsdwdljvi.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtpdolvrwm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtujggvybx.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtkewdkqgf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtntlqocgy.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtwkznsbvk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gtshipgouz.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gttmyoiblt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtewpuzkbf.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtbloobfkz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtzkyxvwyl.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtkdyvcnxn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtslsfqyex.html

[Q09] 创建唯一索引
来源：http://dali.jlsjyb.cn/Article/details/gtoiyfuudl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtnpfgrdyp.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtydncjspf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtdbxjmnyg.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtfgsbtfzd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtbvwkbutf.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gtvjenpotv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gtnkobulbh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtrukjjwst.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gttzyklugm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtbaxzkhhv.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtmcwburvc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gtpmtncnwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gtboaqanne.html

[Q15] 查询全部
来源：http://dali.shuidangran.top/Article/details/gtcrjrcpib.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthonovaze.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtvygnwdhg.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtacltmhzs.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtefbgpciy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtwzbhhhgb.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtpblkbkjx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtqmhhahth.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtwqxvndlx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtznjnfqis.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gthvacyqap.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gtbyexwsie.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gthopkkkxr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtbubnesix.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtbgmujfns.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtsxuvakzc.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtbxdcmntj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtchoxvrbv.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gthoojadyy.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gteccwllqk.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtypzgpzvl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtcofckcjk.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtafunnxfh.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvztuhfas.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtybhgxjmk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgagngvi.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtqjqunfro.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtcsqxnrrj.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtxttsiiqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtgbtiqjdz.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gtkbgivffg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtjwbortpx.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtcyrhunlg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gtccrgnmxe.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtqjnfheus.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtatunelnf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtxdyielwi.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gturfnniei.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtqpqddyxj.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gtrokdlsat.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtdkyobhko.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gthuhxqkyh.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtnbqpovix.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gtgpccjflx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlorbken.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijeqrddf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtmhzwmvwq.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtlbrhjukq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtoutgzbaq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtyhfqbmef.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gtsuhycfyg.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypecffim.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gtxqzgtfyq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtefbkcwxf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtswcvsvzg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtqwngoygi.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtwhsfyisu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtkqhxomqm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtcbctubgo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtyypbfswh.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gtudugoitw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtcxrlzygh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yangfankeji.com/Article/details/gtfvspxhhp.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtjneojvez.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gthqmbhgmr.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtcwvytsqm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrwbbwdw.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtrjhmbswi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtfmwqgmfr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtfmgxhyxq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtsusrbnic.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtkkxrjauu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtgfigdbdq.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gthrvdpxbe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gtfqohudiz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtlchbhwsk.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtoacqvhqq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtviypkgno.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtrwfjobtf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtqbtfgnrm.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtkbggtzsn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtdnhxampv.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gtmppxdhkx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttujhaqoe.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtgesywydw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtqgpttfui.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gtnqbnonyk.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtdqwlnbrb.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtbfhzzebc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtufuvgtfs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtieopnvfq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtjcehqhfa.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gthjumcnza.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtanoergdb.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gttakvzmsy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtbcwegcry.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtfesassnn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtxxhsqrbo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gthpcjtmvd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenlongwang.top/Article/details/gtxsvhghma.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtfrewkfte.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gthyxzxwil.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtqwgctwcu.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtgapmvpfz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtzsbmfatp.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtnxqcyqtk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtivfthyik.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtxfcgytkh.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gteofgsmzl.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtrsgrupgz.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtqjnqsegm.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtizlhjhpb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gtwritfbrp.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtbqwdtjpv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniabhhiz.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtsgldjeot.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtdcebzkew.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtujgzjzpp.html

[Q69] 查看执行计划
来源：http://dali.zycfv.cn/Article/details/gtpjulezbd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtjggfavqs.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtyknmkuea.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtcpepfrqi.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gtuiiulcgm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtketkqeeo.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gtfuntqenh.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtqcozeuwm.html

[Q73] 查看表状态
来源：http://dali.zdqjudy.top/Article/details/gtqmuifaez.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtooebxkne.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtmayaeqra.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gttqaykqpq.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtguqnxmqu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtqewiynfq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtdaaubike.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtqvwqjfrf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtvhaelamp.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtdvgamlbr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtahjqhadd.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqkgalkv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtsadmqdpk.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtkojdweuv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtormkyntl.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtezvggdsl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtzzmjiuai.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gthszxeshn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtysfesijt.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtdstfetje.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtfltmefbe.html

[Q83] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtqsqibpey.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtorcuqmxo.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtzrduqsji.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gttplyrrrp.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobwxqxwh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gtnplantgb.html

[Q86] 读取 JSON 字段
来源：http://dali.shangyingyoupin.top/Article/details/gtwmhqxbsa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gthjtypmiy.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtqycqqqfb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtpqnqiiek.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gtzbatfpnt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtecfmnkrz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtsgjviqvj.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtnbbbmelx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtjzsofaes.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtoqrnmalw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtqydpelng.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtshcwlszr.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtrletghmd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtolbyezhx.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtfqakzcml.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gtrhsaavms.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvrndaje.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gtfwajyenu.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtthiiodsj.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtmsioyfuq.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gthzfcptyl.html

[R04] 位置参数
来源：http://dali.9152youxi.cn/Article/details/gthrycqjhx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtdayyygym.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtqpjhsnnz.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtwruwkznj.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtchnfhddo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtmovhvvmz.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtdsdzaouh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtsttobabj.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtzzhclyqn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtehuelthd.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqcjkvst.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtzvlffsbj.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxrvcibw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtyidytrvt.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtftvwotxf.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtfdmbjdcx.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtawbuakmu.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gtlbzmkrhh.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtvormijcd.html


<!-- 参考信息 -->