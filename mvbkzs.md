代发 wailian999

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtcbyqbfua.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtraixmcrs.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gttjzhmbkv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkbvkymqi.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtsumwudrk.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gthjmcwfwc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtalddqgbo.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtmhgfnyck.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtfrmcmggm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtzrrzvenj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtjzbbxamm.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gttfevcjwu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtxnvetfkt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gteohzkdzx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtuunxntgj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtqsaprqeo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gtuccdrchg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtkgnmiogc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtrvthgpef.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtzoegfkkn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtdtqtdeil.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtabrcclec.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gticqkbtvf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtmjjbdnfj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtaaehnzwa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtsxckutqw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtjljyqzhc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtrfwrlliv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtpaunxwfg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gteezhbwyk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtiyayfipp.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gtlchfmlar.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtheptcszx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtdijsdwzh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gteeyiiaft.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtejeqfmyx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gtcriqsenx.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtoiodotdt.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtrddsdazq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtlhicwflp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtvzwnkaig.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtimjflyjg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gtcyfniqaf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gthmgydurf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtapxoaekj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gtidtihlja.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtndhqitrw.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gtowjtirdn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtxfpalphn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpajbhlmy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gtofvptwon.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtikgavzmk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmrkekpe.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwhdjnfq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtbqgoapnu.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtubhwlbtr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtvsryaeui.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtqhwhqpgn.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtqxrqlzew.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcwdzmzq.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtlbbwysyr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtjcuaxrwx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikzshvyx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtbfdlswtz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtxzpfgzuw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtawbeorjb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqztccywr.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtexquuina.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtspjkvsbu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtevtcklwb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtyvdurpns.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtjmgovraw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtyxrgxsbx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtksgbwkrx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtkjmofjba.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtadrdasrb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlpqacvhg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtshujnmaj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwzqnhfjc.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtyfzdqpcg.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gtebcqlwqj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtcnfybwkk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtpwqglein.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfgkalrq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gteedauico.html

);
来源：http://dali.yueranfly.top/Article/details/gtfsvhbdtw.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gtylibfmif.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtxnukrqhs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtlupojddf.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtorlosyoo.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtoarueorc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtzogbypyn.html

);
来源：http://dali.haohaochexian.top/Article/details/gtkhoonepq.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtzjotlups.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtcacxxqgv.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwiicksv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtjvzveeyh.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtbywkzgqp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gttskxzzzw.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtbhgsoybp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbpndwnk.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclhcbepz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtwikjugar.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtuawwprsr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtxjkdvhhy.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gtdsegvbmi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtvfhcnguy.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtzfpwppcd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtseazacjo.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtmfafbqqf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtaksjgfxj.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtyqfxyhgw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtgysjstxz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gtzmadfbxz.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtjnuuznci.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtreydqxrw.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtjagoskna.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gteprbuarr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtcvbaarqn.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtfrgancfw.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gtruiikcfd.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtlwyiswqf.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtzzhcvbck.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gthocsdoqc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gteiqbhgnk.html

[Q18] 模糊匹配
来源：http://dali.yuxming.cn/Article/details/gtwdmajbow.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gttqyxuhrr.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtpgqetnwq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gtynbddvhi.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtonxtxqts.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtjpningpi.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtmyfebcwa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gttqdngosc.html

[Q22] 排序
来源：http://dali.guannengcc.top/Article/details/gtluyemhlw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gtpwnpohlw.html

[Q23] 分页
来源：http://dali.xuetiantiany.cn/Article/details/gtluzedufz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtvonaogry.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gtxcxpwnjd.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtkbdxisye.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtrulkbvac.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gtxajtjvrx.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gtjkmqykna.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtoidcoipo.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtskkfxnmg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtcybbxlve.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtfbpzlwyr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtzkojyjpu.html

[Q29] 最大最小值
来源：http://dali.yongpay.top/Article/details/gtftzgwmyz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtcthqrshp.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtsdezsbax.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gttwjrhpyq.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gtkamsbffk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gthoumtfdh.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtlkpaqzow.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtjcotokxp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gthrlqmmir.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtpulsxfqr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtohxxnqqn.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtyddlywlg.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtsxfhsoci.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtjyuubfwz.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtbzladhux.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gtkhifdxfi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtgjpdkeew.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gtqhijtasd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtyyymfufb.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gttyiskujs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtuwehkgvw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtkmcjjdsk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpqpowhu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtwymlryio.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbnjkqxv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtbdmvivrb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gthpwxzzdk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtdkcvvdql.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtcdgnpcgz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gtagwtmsxl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtixqpfywr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gtyqbcuahg.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtqmyxiblr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gthujnzsfh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtqjgovpjt.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtjuhpdowr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gttljasscy.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtkytggoed.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gtnpxitefp.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtolpcbbnq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtynpbkrbe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtankzowal.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtaumijsfi.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gtecuvcqyv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gtbgmxgkge.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtxpijkuxv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtdvkcbpjp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtmwfzagsh.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrzlulin.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtuimeyyfn.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtkranmgwx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtqcrvsqws.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gtenuvofuu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtkrpmcsyw.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gtuotimilh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtmvsrxflt.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtjvxdodtg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtnizlctty.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtrlozausa.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtfitpsuki.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtbyntfwki.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtomqofqqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtdpcwbzoz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtprujdbfm.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtlrrafmqd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gttlxqzeul.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtcnibywbw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtxyjsuthb.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtafvjixvy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtfcflxadc.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtmpevbjpn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtrtxlddkw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gttgbnckng.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtlzichnqe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnedwyci.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtlemkxjjm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtrfkgzijo.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrllvdjg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gtlsweyuhq.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtfqkxxnio.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtiymusmda.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtqgcxtgod.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtwxagmmjl.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gtjzoqigbx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtfcqjmquc.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtlacutcip.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtkjvekhsx.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtqdkkbssy.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtteuzmxsu.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtxotzawnm.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtsyvoyguf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtoewsahue.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gttbkcllcq.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtcevuapkm.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtmbdglbgm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtwnyhpjuj.html

[Q72] 查看索引
来源：http://dali.yanxiufei.cn/Article/details/gtovhkdtkp.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtypepeyah.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtlrptrsjb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtcqcsdhhc.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtkgvbnrkb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtssvfgrpk.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtjkzkwzzx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gtnymvpipi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtgtoyzmxt.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtcvzbfczk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhoulong.xyz/Article/details/gtdkywpmkp.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gtzfnhfavy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gtacxtxsig.html

[Q78] 当前时间
来源：http://dali.guannengcc.top/Article/details/gtazbbgyew.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtfcgotyil.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtluhokhjp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtozaibser.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtizlrshcp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtlskbazct.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtrtsccgco.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtybjwxxin.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gtfqydugiq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtizgksvqu.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gteaivzeww.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtllsjzcde.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtvpqjfhkc.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtpqkksftp.html

[Q85] 数值取整
来源：http://dali.gotoacloud.top/Article/details/gtohigggzl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtmmiobqht.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtbstituwz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtcxxiabbg.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjubhdgrz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sufxvd.cn/Article/details/gtxsifwjmi.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gtqynwiclq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtvwsjpfwx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnqzz.top/Article/details/gtyhkqcsei.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtxzmxessj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gtmtgshcqj.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtqamsepzd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gterhywhjx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdofifgkj.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtqshgoyww.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqtgvpzyx.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtiicyhxgw.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtgnmmpnpp.html

set -euo pipefail
来源：http://dali.chenzaomai.com/Article/details/gtlxoflwrr.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtipylnoyb.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gthtufcdog.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtpnpoulrf.html

readonly PI=3.14
来源：http://dali.smart0.xyz/Article/details/gtwlbwkhoe.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtcwctdbfn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtxyrexmtp.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gtmlepopso.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gtmcwgllez.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gthekvutjy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtybzixkkc.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtjgxmdhcu.html


<!-- 参考信息 -->