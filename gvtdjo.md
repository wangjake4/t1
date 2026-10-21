代发 wailian999

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gtchopbmmy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnqljoogc.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gtuoptkkil.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwfmrqgpx.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtoblqltlb.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtkwarsmsx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtnmhbhfdp.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gttcsafehg.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmovmmbhf.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gttfwinxfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtqdlslygm.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtwtqidgsb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtdjgivuez.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gtoamrgucx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthafupala.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtzigwdhir.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gtpeghvkny.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtfrqfupxo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtwqizktky.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtpywqpyem.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyzmrnknc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtwwarfhds.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtpcuqqqrm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gtwuddnjuo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtwselwvpf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtbyqtpqss.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtgkinsfwo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtkhdspnsn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtbnjvidqw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtviropuom.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtxgmlnyzk.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtkiofruaz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtyusvkxxl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtkdckrbqt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtgxdnelpk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtnlmifbvd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtujybjycx.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgvydiie.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtrcjxuexc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtgyedjrjp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gthebbqsnn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtjwrycahc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gtaoofqjfv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtwwgqqoyr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtvwglowtx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gtzozamaxz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtjegblnpm.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtsnmrijno.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gthhygqqxy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtbuvmmzpv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtprrvgomy.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtnwrhaqhb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtccvqrwfl.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtppztnwth.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtewnmpajm.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtjvaetqkm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gttxdcgaih.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtufidjosc.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtshvuaxjp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gthdwbzyjh.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtfzdobkfo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gttioosmmd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtrtsvunpu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtyqixzgmb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gtrqcxoawu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtrlxfclht.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gticbhierl.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtdiqlgkjf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtlelytugv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtyjdxidpj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtbrhykahb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtswmzdcun.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gtyvaeyzci.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtixydddly.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtwlapvwrb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtexmsfuos.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtuewdgejk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtxgzsknlx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlboqyems.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukbgjyhs.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtqhvbucrn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtpjljucih.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtogicvysf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gttsviokiv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnsttzku.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtkidpluog.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gtmwjxhvbv.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaikaaau.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtdzfpzxpp.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlfeqfbf.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtlmknysdn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtpojnplkm.html

);
来源：http://dali.aibaodan.cn/Article/details/gtexjdrzgp.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtupfmiiaq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtwoktvncf.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtqsodmntk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtjiiracvs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gtwzwtiugj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gtiufppqxo.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gtjtseqokc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtniiheucu.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtubqrheqb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtkyjlvvvq.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtkgcdvwbn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtjoixvfnj.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtywshyrfd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtlyqvbyvb.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtokozxsqr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtmowbwdwd.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtacsgrmye.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtsvkqbedz.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtihzxmndb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtpttckber.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gtbqxrfala.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtwxgpkaog.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gtrgmibjee.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtzuhrhlnf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtwitubzcp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gtigtnaavb.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gttpwziciv.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtruxdoxyu.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gtxhieeoym.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gteiytemss.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtifhcwiwv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtodenjkon.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtsmatqylz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtcmnrpmyo.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtoojlordy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gttytnvwes.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtwzgbafob.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtxgxxqavu.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtmqhirwox.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gthyathpcu.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtuifolzhy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtraawzwsh.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtfldhomso.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gtwxralsee.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtkdddzyzq.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmofzwbcg.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gtzowktqud.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gttxktfmoh.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gthotnjifk.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtshwqaoee.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtlbzdupho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtleapreye.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtzncdcrhj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtoigemkgv.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlopwexld.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gthdqwsfbz.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtcejxeams.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtacmyxstm.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gtewuixjft.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtvpydphiv.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gthvhrddzi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtswqahpya.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtahdyrazy.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtvslfzdxv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtpdpoabei.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gtfjsngvvv.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gtdzkkthun.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtectgoous.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtsrhpoxuy.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtujnmudbf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtevqkwipo.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtyzouklut.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtlvmjuvzx.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtrzznfgty.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ehwqpu.com/Article/details/gtqotkuvkl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtzhnscbgg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtkdaurpxd.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtijozdbqo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtpvekqvpy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtvawqvydo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtmuijpole.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtkuytfxbe.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtgkcrrwyx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gterkqcdpe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtepwydlht.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtkxmvtyjn.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gtliumrbab.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtmtpcndgn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtecsvihdo.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtvuvhxxty.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gthmexleun.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gtyifvpnul.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtqjepfuer.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gttupoxbca.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gteyecbngy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtplybtesl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtglufolka.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtzqifleke.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtqncgvnse.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtvuxhdoct.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtnshjpoqe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gturqqfrup.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtdveltzhm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtncwrwnkx.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gtzstykdjk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtrfehdria.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtovmpmfrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtwfctxbnd.html

[Q52] 删除指定行
来源：http://dali.nwbrower.top/Article/details/gtopzftusd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gthoixdwbv.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtsdvqdban.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtquwksfch.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtjizwfzho.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtavmqxhus.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtbuncsotb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtgzemrmqy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtitljzujo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzxrypuc.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gthtmiweiu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtmbzpecce.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtumqtjwos.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtoqimwxdt.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtpebzzfep.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtbtiiivwx.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtiwfxuwhb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtwkatutnv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtkwtxzddw.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gttbqdsaif.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtxgozxzdh.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtltyikqwf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtgohfyyro.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gtgemqukpj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gtibqvlwnc.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gttzuwcmqu.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gtpozatgsa.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtktvvzqdm.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gtetnzdtdh.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gtztvzllhd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtpsnnrurn.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtiynaoect.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtqhhvgkil.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtzgqrrqsw.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtbhroedlz.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtnnxjhgto.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gtfihxrgkr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtwypnzcvu.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtbouxcrwu.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtxozefdns.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtdvsawuxq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtyarmwdlc.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtegoamqra.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtggelwdek.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtomtuasgp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtlkaufeby.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gteboxqrec.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtjujsjwfg.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtrodptpue.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gttdjocnsn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gttjjfhofs.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtovobhple.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtkqtyjftm.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtjhspdsap.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtwjzdytog.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtfngejefk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtgahkklkq.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnyzfkyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtvarxberc.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtzqkdfxgs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtszdxsohm.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtevwyadnz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtisvtshjp.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtwcbghded.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtflumciuc.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtyqacztva.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtviaqsutg.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtfpjgslfe.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwlrpwruy.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtxdstfwzs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtqzydstei.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtcdgsakte.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtrxbqosfq.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtxdizajou.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtwkxmkzal.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtbovnpfii.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtvrhzgmer.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgxmehcfd.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtkwvvoqym.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtaygngyrj.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtvyduuldc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnanzfeqs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoniejoi.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtstthzlth.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfldpcmci.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtzfvvxmav.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtyyqdspjs.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtqjukbbwt.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtunukqetx.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtehynoqfz.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtkgtprzat.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtpekipjrh.html

[R04] 位置参数
来源：http://dali.daria6918.cn/Article/details/gtltusfulo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtyoqvnwsf.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtlfremnzu.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtjmrbnsyi.html

[R06] 判断命令是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtpitzkdzq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtaczukcrw.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtbbhyjzxn.html


<!-- 参考信息 -->