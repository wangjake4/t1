代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtikqullwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtukxkslsd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtbiqjnvuj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtilicmyax.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gthauiraxr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gtfnrezfmr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtzigrfvsi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gthmojpqrq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtjxkkbqnd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtciuqcnxw.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gtaxeqhxtg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtjqqldwbu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtmotxrjnd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtqanegyli.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtfmvbxjzu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gttqibpuog.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtgvotvljf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvfoqzct.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gtmgjopfpa.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gtgoqprhrn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtfcwytleg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtyxjqglxy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyurubgok.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtmstqqjld.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtunfqpiqx.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gtgmebnuns.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gtfrzwreir.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtqbusejyq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gtwvossabv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gtqsfeiasl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtujifpffp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtqseegpcp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtfnoiafvn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtiqbdlolx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtkxqilbis.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtprfyndwt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtnzouqvua.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gtgxrjasnu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtpnazaguu.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtnfqeuwwz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtijtomkyx.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtkrqdlqts.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtvjbhrieo.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gthwvoqjck.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtlxdbblkc.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlxpjalkf.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmchhpfrr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtrsdkwzda.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwvyvopk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtllodvgoi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtbpyensbu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtvczwayou.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gtibblijmn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtqstflbor.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gthvjfhtpx.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gtfhqywvjn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtlsfrhdnp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gthobbsigz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gthgssxipk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxwbzwoum.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtwjydwaon.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtckwpsize.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtalmhkayj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtxbkrwjyp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmwuzdqks.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidjzzbew.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtarlrgtgo.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gttcdfklbc.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtmfrftvau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtewbqynai.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtgswllthy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtfoxvpuuc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtiqkyvmnx.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwozdtpzh.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtalbcxjul.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gtwbacizks.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgbgooiq.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtqijkgwow.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtakohelaw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxjczknj.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtjuyhzvvn.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtkqipftif.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtsizmblhd.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtgpyqknsd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtstgvsgyq.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtqqylnqqh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtrrpuhcwn.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtdtzuikbu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtnsoxfiwy.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtrurhqazs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtdnurvdoe.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gteuvalhht.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtmjhyrhoe.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gtzvjvumjb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtigijjtwu.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gtzhbxbcre.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqnewaht.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtkcwerszi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtcnbiwxwc.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtrgwnnvnt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gteyrxfehj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtimsuhyet.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtzzxcwzqj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtveayjsru.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtypfzjosf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtvecewlhl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtpokgrfkx.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtevmmgrin.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtzunupmzz.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtrlybpuxq.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtberoksah.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gtoxzrhing.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtznqqzyeh.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtsaxqdilu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtsukfortw.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtfwuintqp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gtsjwezxgb.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtrnwortvm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gtlavpwlgg.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtzfkamuar.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtkgwyqihl.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtvubjyimy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtgafqfkte.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtviiucmhn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtcrxezkrs.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtdyjvfhyi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtlpjdbzkv.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gtxytedpuu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gtqoyevxpo.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtaytnahhw.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtipjiqvag.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtzfefxrpa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilnfnhun.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtkhybrito.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtqtyvizta.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtquqbxxzr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfwnfusfm.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtkeibdhso.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtismiqcet.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gtydyzpzqf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtfrcjaudk.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtannqqcsu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtvzxjltar.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtgmaqsjbb.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gtdevrlzsh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtldmynkmi.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gtibbvzctb.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtbrszqppc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtnjhruwyq.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gtiyycnimt.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtpvwmphio.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtmxfjqnch.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtsrgdhspl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtgkbtbxvb.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gthnhjxdco.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtutdwnsuo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtoeqkfthd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtjsxmzwsq.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtcsmpbtkr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gttnircyce.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtaasgwggb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gthwbzxpqm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtydoupsxn.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtsqpfbncf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtqdiuasai.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtmcukswxf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtleiosbbz.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gterfzjkde.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gtryumdydy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtjvpbyqgu.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtlzguyeul.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gttzryzsrk.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gthjkzachu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtngcaunru.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtxvjubatn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtjqbnfdtm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtcskfmkuu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtxkzlgoqg.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gttcsnavcp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtqgmndphb.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtebuhntus.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gttlifnyas.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuprpvvah.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtjnxcaekm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtklepswgc.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtznfpczvo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtscgpxqib.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtuofvsuro.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gtzcbjpfnh.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gtnnngcpwz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gteradlgab.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtpkquvrfl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtcvcpvvjk.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxwmcbtw.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtxakfbnev.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtprqitszh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtzzuwmhqc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtgrlnxhsu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gttgzsqrtg.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gttgrbktyv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gttjvjcnly.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtqlhysfkj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrztuyedf.html

[Q59] 分组内累计
来源：http://dali.ehwqpu.com/Article/details/gtjnnsceud.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtdnxpyuzq.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtucpfznbl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gtbusstdrr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtoyfbjlzu.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtkkibkjlz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtkpadeavc.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gthhxqtevt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gttdonuooz.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gtcqloaxgq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtubhwpsfk.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacvxilim.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtdcwvmwpa.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtnohdxodh.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtyvstwqdb.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtypbptedd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gturbqarem.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtnxeaqzdt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtmpatodxp.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswunoyqw.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtzvgkvjaj.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gthsqcgeis.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtrlcipimk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtjwnvtuxf.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtvsvuqqqj.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtgwnrsooi.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtfuohcbdk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gtlieyqujq.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtlyzcssss.html

SHOW INDEX FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfiydjhf.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gtxvjrmxgw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtumgipadk.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtrvwhyphm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtijolubgs.html

[Q75] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtcmwzprtm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtlxmvkjug.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtfhcehkkn.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtiahbesps.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtqagputhf.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtmflnuvfl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtwkvjpwty.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtpmeovlbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkcykquw.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvzxvail.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtqeeuhqci.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gtxnpplyar.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtqzspacgs.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwxbdcaj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtfllxaqvx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gtqxutpkle.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtutikbohm.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtdrercsko.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtjbqglwah.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtphmvjxua.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtbydhnvbd.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtfivjbfij.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gttysljduj.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtuqivhgqg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtzdnjvbop.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtepxgpssu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtlzapjhvd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtmwrpafyh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtirmjoahw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtmdzmckza.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtdpqmfpdm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtfgvsivpc.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtpltebyod.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gtcqfekayq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbbmetvpy.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtgxdhfdrv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbpjyhers.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtklfgpgtm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gtogjqagzv.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtxaodmhak.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gtharswbpq.html

name="Tom"; echo "$name"
来源：http://dali.jiagoushi.top/Article/details/gtsrbyyian.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtgruosgmx.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtxauvseil.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtlrpascep.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzotstyi.html

[R05] 参数默认值
来源：http://dali.yonumen.top/Article/details/gteoccjuwn.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtjgbpwcog.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtwqlgpkai.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gtumrpuetv.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gtotlodgzn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gtucewjsxe.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtzkppaiid.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtgayuidxn.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtojzcsasc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtvwfftfsp.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gtwcjxmhou.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gtbvavkmqc.html

[R11] case 多分支
来源：http://dali.xuanzx.com/Article/details/gtlwknyzoz.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtyxvbykud.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtqtwqwtcb.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtascamfce.html

*)     echo "未知命令" ;;
来源：http://dali.sxryk.cn/Article/details/gtlridmknn.html


<!-- 参考信息 -->