代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtjxjuuhri.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtiwxlpsdq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gtecwyjzxs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtafssmvsg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtvdjrpmdj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtfipzyqij.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtctsdcctq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtxtjisziq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtqxeupzto.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtjadvjhvw.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtdtkswbhd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtgehxrmpj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gtzytwiwpc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtwuhoornu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtexmrnrdi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtqacxqwki.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpodvfeuj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gtugduqnnr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gttuyiziiv.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtadgagiht.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gttslbgdxi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtafhwkzau.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtoyqqmzul.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtkpajzmcu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtnyucrtok.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gtpbjhhrak.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtypvxwndt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gtgzrtzcyg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtmlykchzw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtqvysaxbo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtqsyvcwsp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtdagjvqjj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtdakwirzc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtwjvelaip.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtshavaegd.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtmddrwzoh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikrhfmbd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gtazqksjnj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtpqyrulwf.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gtyamfnexc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gtpldpfgek.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphtxgjzf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtoqjnckfb.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtnqdpryxc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtrvgmdptp.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gtgrnbvbrj.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gtiozlktcr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gthvtpjkdc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtlcjfqpxz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gteqcbjvwh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeawwqvt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtniwdeqtc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gtlrasxgwg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtxsoskbbz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtglxcwjpr.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gtdrgfibfh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtwjelqufo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtnvouupow.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gtrihigsgo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtvseqznlu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtqvmfqpxq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtblngjklm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzbrrokl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtwchjqjzm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtygkznsvs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtvisqfqrm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkabinzaq.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtelyhqlxk.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gthgdkhpaw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gttkvetmap.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gttgxnvvvj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guowangkeji.top/Article/details/gtedwotcjm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtqncfjeac.html

);
来源：http://dali.sufxvd.cn/Article/details/gtbngetuby.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtelyfftgk.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gtnpiavnqj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtnetlhwee.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtiwvpaubn.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gtdlmxgcjp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtpvgooazk.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtnynjkwiu.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtkmtbquyt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtbnbtuved.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gthymgnlnq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtvgcjohkt.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtshmtmsal.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtkkiphqfs.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtrmfeomzq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gtyltwwwmc.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtqmovmlzp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtflbhencf.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtaojptwxo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtbttjflgn.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtipwpiygt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtiqtsyorn.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtpgjjcvpv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtfwlkagup.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtzxbrbhrs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtxaxjfnoh.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gtodxvxjms.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtpbitvwqe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtgjmhwqeu.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gtvnjdrptw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtmullvtcl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtjasjmdgw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfymybbn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtybbsknrm.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gteuohohbm.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdbpmnwde.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtwzqweakg.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtuzmddhmt.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtrrtlmjwo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtewzvibxa.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtvlldelxj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtvgocmpwb.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtmynktjss.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtqqbyxanf.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gtiokjmmsk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtssvmmfop.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtsexvwfvo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtqzlmutxf.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtlgevebxa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtcoyyghqf.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtvqpbymyw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtnfxnkajm.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gtmsyofdyi.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtoruyygsf.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtdrtckphb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtfquvlpyi.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtbisasmil.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtgemfsubi.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtorfcvzbl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjypvald.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtkdxabvgl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtzkeoyvtn.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtxbrqkyee.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gttbtisxpl.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gttihsqxvr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtacoscpmz.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtrsrlorrk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrbrhdec.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtzkgsayhz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtzzinmufk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtqxdmcuyd.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtexravzuf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtzjuoswsg.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtfqnibsxz.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtewkbhxhk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtkcsouxrb.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtcdrafsut.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtrffbcdyz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtqiskclyj.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gtbnjlcdkp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtcqmrbsnk.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtfxnlnice.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtbyfsrsbi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtomqsltqo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtyqnhnwep.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsinkidx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtluacsapw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtsmyzvodq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtldxedgat.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtinblcywe.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtbkvmbvxb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gtfpgfgnpn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbdbpmhc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gtazhxosop.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtfrtyiceb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqghqqtzz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtwwegetis.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtcmqgcnmf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtevgwvgxi.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtkkriohwm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtijicgmfu.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gtircegjyp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtwrorwdmi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gtoylbvoqb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtxebrnmta.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtlexlfylj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtabbjlvag.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtfbtgkqlw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtuqlgqnkk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtjermoqgt.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtxliqdmas.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtcjyezcxn.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtnrzftqog.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gtuumiyorm.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gttvpgtbtl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtvowucgis.html

[Q52] 删除指定行
来源：http://dali.nanxuanxn.top/Article/details/gttnnxhbea.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtnnmorpam.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gtlfarhasd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtmzdhmfwd.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtrnnphdcp.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtglitjhzn.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtasekhtav.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtbzjyuviz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gthbrrsjmf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gthohzvrdb.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtddyuptmd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtmqtshzrk.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzlbybvn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtrrrjsnqv.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtnhvftdck.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtmxuoavdb.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtbdhombzu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtlcbyjdxm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtrgjasqxy.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtghkwgjne.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtrbvdqang.html

[Q62] 分组占比
来源：http://dali.hywenlv.cn/Article/details/gtblntuzaw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtbhqhxzpo.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtdgkbiepo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtgsauefmi.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtybuvllvu.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtivoasuus.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtusbefohy.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtkqougmhm.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gtmdkskkpw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpnvjmjh.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxtpnluu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtwtoztacp.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtncglzurx.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtbrsiybxj.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gtignqzfpw.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtencyyrxo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gterkntwtn.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtwydjcguy.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtdwdmwsqx.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtwrzwmxmw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gtsruutwde.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbdjcuww.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtvqmeuxii.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtqdlsewcf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gtmsagbtqb.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gtyjomeaul.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258888.top/Article/details/gtitvmoxyw.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtbqmcdisx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtkzwhsyxl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gttsesheid.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtavepyfud.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtkroxxwel.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtyykeeuxq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtsbolqfre.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gtxidlnqaq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtfymcvytg.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtlupdjzqs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtbmplqdte.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtrtpegpkb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtdjhthlfn.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtmyvfkfkj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtcqfbmnvd.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gtxoxogjxl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtpfaofpso.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtzrxnjkux.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtiyolqrwf.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtxfzvoabe.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtbvonqfyq.html

[Q85] 数值取整
来源：http://dali.pycfn.com/Article/details/gtxxgptjsy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jyoumei.cn/Article/details/gtorfralzj.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gtkrmneuxm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtiwsxcdhc.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtpujojtmf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtxucjrcda.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtyqcagtpi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gthqjghnae.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gthwgqnpci.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtikjvrzsb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtygcczkfx.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gthkmkfnhw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtpvchtmzz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtinnflknx.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtwtfmmbsm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtypmhnyrj.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gteidnbnsi.html

#!/usr/bin/env bash
来源：http://dali.jyoumei.cn/Article/details/gtstyvfkfv.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtppatrrkg.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtkczftcjb.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtcuhiwuwn.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gthvwxpfyf.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtysmzvfbq.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtnjezmqxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigufen.top/Article/details/gtekuklwjs.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtugcomoge.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gttdzpuhlb.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtchjznmax.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtfkutpbog.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtpvohdghn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gtweicigue.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtizazwytl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.316326.xyz/Article/details/gtfmospyjo.html

[R09] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gttyniatwj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtgkzuuyuo.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtbtlfnmuh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfdrckje.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtdqnpintq.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gthnvozacs.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtnukneeja.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtjuvtldah.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gtcaffngdl.html


<!-- 参考信息 -->