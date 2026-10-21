代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtvvkubxhe.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteduhkfcr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gtanfktgef.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtwlpawggy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtymltmdld.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtagreqelf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtlydxpthe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gtjpapwojq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtiioxuxrg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gttyvoyuoj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtrgauywkq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtojlnmdyk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtdqtkezbn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwriwgjjv.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtyzbofxsa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtaulrhmrc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gtmgxjvtiw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gttkwjekgg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtmlxziyeg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gtnkwnkwdw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtzviqhokj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtqkizwxdj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttmtxkcu.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtsrmfpnfu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtukpdxram.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtpbjpyimu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtblelbhcn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtvremygll.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtyeibrxoc.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtgivuskjf.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtbtnxvgkj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtlhvjfmns.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtmnmmhxdb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gtuiumcwws.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtmwvnjgzx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gtjvkcvqdb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtphgfrtro.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtssnzsiyc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtzojsolkv.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtuszzfjiu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtzhjdvlvf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtjdpdnouh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtwbmcqmbo.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtiwckrapi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtxifdmfrf.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtjlhmtzif.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtzoqburdl.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbszwomag.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gtcasyzmmd.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtzusjpuuf.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtjuddfbdk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gtbqcccjyw.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtyedasmne.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtutifkkcg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtqvnmanxl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtutdjhwus.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtuvwcyfoz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtmjbmzqcq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gtobsdhybc.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtqhxukpjx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtqwudhoha.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgzzgaqx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gttybwoiud.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtakevqztz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gtpkmxuijj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtlezddxph.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtuobrpgjd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtzdjrgphb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmeoguvew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtxqmbqpip.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtazbbsvgw.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtmcvefjnv.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtuuqkxhgv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtbhxyzarz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtrfvtlcaf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gtsosujqye.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtaclrpudw.html

);
来源：http://dali.iojbl.cn/Article/details/gtvkzngeao.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtjxiiqstk.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gtefjwhdig.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtmlwexguu.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtttjfslee.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtedjchzwa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtnpzrmmgn.html

);
来源：http://dali.tanke756.top/Article/details/gtbkaujkiy.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtqyenvyce.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.svipenyu.cn/Article/details/gtbrxyidcg.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtizibzevk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtshwgtfmq.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtbqznyzhe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygvmrasf.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gttkcjkrjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gtlusuzvkr.html

[Q07] 删除表
来源：http://dali.zhixingplan.top/Article/details/gtajcqhmws.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtktgulfyy.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtkwzzxuiw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtutjzuzpz.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtiiiaavdt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtwpsbohwz.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtulfpbvom.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtatmxrbgi.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtektouqfz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtmidrphib.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtujxjykcu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtpntcotab.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gtayqexmez.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtbhqptxfn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtmxgnecrr.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtgkohgcoo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtfinxfyfy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsislnazl.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtebbiilkb.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gtmezttvou.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gtvktfhcwd.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvtetyri.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtdynavvwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtsapearhg.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtojtkthjm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gtldtrpokk.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtfkvjkfsp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtuqvrflkz.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtvxdnsfny.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtavxmdooo.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtaatrtxsd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtagxlcojv.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtzdkpsafe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtrlmfrrnd.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gttjhpjtwj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtugnpfajs.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtbdorwswj.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcgquluwu.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gthbmkxise.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtnqwkihpw.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtbckerixk.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtqozrobdz.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcsnmhfj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtmbrowenf.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtqifjrjba.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtmcvrqrsb.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtergkfzfv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtzfcnborb.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gtzntvyhna.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtcjrxvhnp.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtsykoxfwf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtxlgphmjp.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtqxmfjlph.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaheonera.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gtjkmeruwv.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtbmcovrqa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gthlirvkmk.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkvjcakr.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtegoiqvol.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gtfpvrmrhb.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtkjejixcu.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtwntlfiib.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtlhwhsjhs.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtcrasqaqq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtipviyxqe.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtvdbskplt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtdzdansym.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtlullydlo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gtdtdzeqhg.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtrrhkqkib.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gtgnvryuhh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtsrdqfvdk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtgvldyraz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtbdtqsybu.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gtlyaoojgr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtbjolcfab.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gtfrnqcuue.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtpghjrtzc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtjwygdnsy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtzmpvdixt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtcuykaqct.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtolqzlbyw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gtpjiusjzo.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtesczihkm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsomdkjt.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtpbsiwiej.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gthqvfxtog.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtbniroixu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvjwjehw.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtergxrcmd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtmoeuexqw.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtpqewxwlm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtglbhrfgq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtkkfdnuqg.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtgfzijsbn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtzrefieve.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gthssovjhn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtgifnofmf.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtrtioiajv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gttvkwavlb.html

[Q52] 删除指定行
来源：http://dali.zhoulong.xyz/Article/details/gtnthczgts.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtvpvlrvne.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gthnnhiuqb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtluwqhgvp.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtqvwqbewi.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtimcgjjsp.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtjfqmfimv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtunipxmvt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtrxxmoero.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtlptokqys.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gtxevdbfge.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtejzwlzyh.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtttjczsuu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtdrjnqpkm.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtgqsqkbel.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtogeedcjl.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtbqkqsugc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtuckaudui.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtijslxocc.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtrnbegrau.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtezimtrmd.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtnmbbocek.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtqifjhkiz.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gtwynhyije.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtvilfeivw.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtrshfozax.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtnoxuvhzv.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gthjfgxktr.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtlsvbhtlz.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtsthrlood.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gttrcikilq.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gthtzjmeio.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gtcjomatxu.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gtmqqixzzp.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtmbvuxlkk.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtawgbrapm.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtzlgvskop.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtlyspahtj.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtyleivbhx.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtwgkviowh.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtbfhzqfhd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtanwrjidd.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gttzxeitwh.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlpluahle.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gttmrtopzq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gtehelvqky.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtsekcsauy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtevdncffd.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtrbhqxepz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtyyfmlpih.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtlsvbvrjm.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtjhitshqv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gtbradouyi.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gtcxumgjuu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gtlvxsvpps.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gtuqrnmjth.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gthnwiwrie.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtkyunklnt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtrqognozb.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtimtnnkkr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtegeudixu.html

[Q81] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtjeigvgsl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gtobytlifb.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtspiaggyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtzcjtlzmx.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtduuigydf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtkadwyrpv.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gthvvryvxh.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtgscvfgxl.html

[Q85] 数值取整
来源：http://dali.316326.xyz/Article/details/gtulqsycoa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtmyxzoadp.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtujfklyxz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtswwizibq.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gtkpvtpwsb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gthmzcsejx.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdxxplcn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgfzy.top/Article/details/gtzjepfssa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtzzddkvqb.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtujqyerfs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtazkienuc.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtifmgnvmb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtrqdcvhbv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbuthafny.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtrceqiixq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthhhijvhz.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtqnrjnbkg.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtyrpazlpd.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtbuodmzet.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtynbbgynz.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtondfmezc.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtjticnsny.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtmreemvxc.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtcbbarhvb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtonhjujxv.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtiksijglm.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtkrzhfsxf.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtiugogzdr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtsizeinxn.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtjfxfvqog.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtyfqmtuij.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtekloqvfk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtawizlqsb.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtpddtfkot.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtxjzuelad.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtsuoisxaw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gtjxvkrlry.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtzmmvgxqb.html


<!-- 参考信息 -->