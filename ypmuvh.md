代发 wailian999

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtyxhbsupn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmmwnihfb.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtglbjfgeg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrlereotj.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtbjwmbirs.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gttymuitre.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtygrqliwo.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtglrzhuvz.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtromaptga.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtxvfdmuqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtibusiudm.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtbatxijmv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtwlszwpzx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtuabkquct.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmhgyfjt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtvrvueoss.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtruvvenhh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtzwrqzarm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtzdzmbpqe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtefkqgiir.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbxlinkuz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtaewzwpdo.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtqirklieo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtaguutskb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtgeozlhom.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtcrdczblj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtmfxxbifq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtiicxbsnc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtcfnegitj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gthllazrwp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtpdzakzdg.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtdfvhmake.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gtzdkqilap.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtaxvievsm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtzwiduave.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtrpmbvgau.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtplvzncme.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtuphrwvpc.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtispbteky.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtnazgauno.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtsjfalgdl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtddteycqm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gteoludhdd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtrqinugoe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gtqjkofkvc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gtswfffafn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtnbceqzms.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gtuvlcaqka.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gttahjbpum.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtgrmqvghu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gtghjtyquk.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtzipoqzqh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gtwirduxwm.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtdpfjseax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtidsapyhc.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtyxdzshcm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtjcaxjcox.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtawvfnaxe.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gtcuwbpnny.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtmiyskefo.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtyryktebo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtditjsing.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gthktjoxlq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtzzhwkatc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gtxrpmiveu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtkrwembau.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtvadgwyyp.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gtkfdmnyfm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtgpjvlbua.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtrbywljbf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gttganqhox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtjfsxdhzv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtsersuvzc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtsibzaqfx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtddrlokbk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgbwnozu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlhvavvxv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gtfdskrquu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgburfzcb.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtymosxynl.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gtqnajwmuw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtwbotuhvw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtikrfqpyk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtckesmmsy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtcwyjgjtd.html

);
来源：http://dali.hammf.cn/Article/details/gtljailjnq.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtutptpyna.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtgacmsxhs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gthqmwwpda.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtjughokds.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtxkbkkanc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gtqtpcwmsa.html

);
来源：http://dali.wangdashe.top/Article/details/gtqqhiscjl.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtujybfkxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkesuvyrd.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtxwxmkqyj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtioqbgvac.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gtmfykaxoq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtnjuuwtry.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gtcjlvdsqk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gttczfshcg.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gteeegklop.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtbnpupqlc.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtmaqhpakt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtuptwvipv.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnorqsxh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtgpozanid.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gtxvtoypwk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtaqobiudv.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gtkhnfnigq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtydcenrbs.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtkqoehhge.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtpjywmdoo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtqchfnxvj.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtoyefaros.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtpvywwfac.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtlqjlyycs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilulsfen.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gtxyoloqdk.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gtnlupcjkb.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gtunhhsnsj.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gtltsuapgb.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbqifxupp.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtwfreaypb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtciiuyyus.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtyjuhfvfe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gtvmmzefdt.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtkghcwocl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtbxcldakx.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtbgjnkkwg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtahseibpt.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtiuszvgay.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gtunhgohth.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtsbbisesh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtpxekciuy.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gterhhwtpx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtivqgypab.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtywcqzkye.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gttxnglywc.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtgcookqnw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwvqstie.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtandyiris.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtdasykvow.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtosryuqiq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gteydhxtul.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtomuxobgp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtwlncpkrf.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtfvcwvtym.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtnyzahzfd.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtsdginpif.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtkzqdxopj.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtrxibmfzd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtajssnpnk.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtvbnebzaf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtunrdqbxl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gtuipnnsal.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gteptakbbw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gtixronjaz.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtyvijtaab.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtzkcrvrbc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtdbqteolg.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtfpfgwqvj.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtecygetnk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtoknfzbtd.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtjohyplbd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtrpyehmve.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtwjocshzk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtzwvjpecf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtikrrgikt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gtzcsrfcvx.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtlonznpde.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtohepdneu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gttehqykez.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtttlzobdp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtvirfsdqd.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtdbwjwamv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtvyabmhic.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtzqhehvsv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtvlkdxmii.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtsdwqqinp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gtwduzrmox.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtntfxtrcf.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtlgaimewp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gteszaqydc.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gttrhbmlic.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtndkeabng.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtqkmlseqe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtqxgkrgqj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcnypbir.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtrsdxlrbn.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtlkuyyirp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtlbjfjfem.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbidchhgc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gtgecdaaoh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gthpuhtprp.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gtrdgudvlg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtdzzhoyii.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtfngibimq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtzfvnuiah.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gtfzsanqqb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtiierhbvo.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtzrxguzjo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gttsptpguz.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtsgwumjpg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtomhzekbs.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtmmlhqkmt.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gthgicxyqg.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtflqjothm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtpwdxslie.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtnqdkbsvx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtvwakvkuz.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtimbldzeo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtvqskdwpm.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtfovusyob.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtjwkdpsbb.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtjzembame.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtcedpbozz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gttziyvces.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtwceumygx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtjnyzxaad.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtntktrxxx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtjkefnhlv.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtgctvvuiy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtpmampqpq.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwumzgfmg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gtkzfsupte.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gtjngmqyol.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtzrkxshjn.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtvdlqwuit.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtgnxprloj.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsypntpe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeuqxdiz.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtpmmmgoqq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gtwinnjzrl.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtntxgcbcc.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gtuefwuzcv.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtmivoazfz.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtiohnvukl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gtywjtyfav.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtfglujkzi.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gttlyvoejo.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gthowdukwz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtclxnlqjk.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkunxwpcj.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtbaedhrbl.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gtgwkeimhk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtbnpqpzbi.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gthapwxhwp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtpsbrmenw.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtghwxstbt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtnohutjll.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtrvarwfys.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gttqpqmtle.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtwoyhhrsk.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsofpqnpq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gthsyucznl.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtwandbcrr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtybnaajud.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtldpdzjma.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkygplxb.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gtvngxowmp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gthxvgeyjj.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtixldsyoa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sxryk.cn/Article/details/gtggnokqeq.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gtcxkdlfpc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtmeullktp.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gthnbhvmax.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gttzzgxuea.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtxdfjummi.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtiqnpjikq.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtgdcjtmot.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtzbnrxhle.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtlvxxtakc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtnukexuzp.html

[Q87] JSON 字段做条件
来源：http://dali.feifeiyinyue.top/Article/details/gtzqygtjch.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtlnarogkm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtagxpopci.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtprdavdph.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gthqtztzwe.html

[Q89] 判断表是否存在
来源：http://dali.cqqwz.cn/Article/details/gtxjjeczqf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtzqopykjr.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtjgppfzwt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gtxzxcwcxq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgedgnhzf.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtxcohalvf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttcbisefu.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtbxmvhbaj.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtqigthwab.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtcccxfcqi.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gthbewxpay.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtdbcualgd.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gthrvufkzw.html

readonly PI=3.14
来源：http://dali.yongpay.top/Article/details/gtgnluptto.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtqhxbmlva.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtvwktpcdc.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtnctvvybe.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtokkguubn.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtkunlhoqk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtufbdjykb.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtncubwfig.html


<!-- 参考信息 -->