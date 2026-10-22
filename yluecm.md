代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtecznndrz.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtttrhttjp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgptwfqty.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtdbxbvboo.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtxvbfzxeb.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtxzmfjiau.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gtusjqeinz.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtapphnwmd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtlmdzrcxv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtnyxhzlub.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gttnfuizhi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtxhlnvzgi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtmteahryz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gtiejmpvlf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtoifwdmrw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwovsvhcu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtgxqwlknl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gteudhzusx.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtqstsxpvu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtbpjfzdkx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtirmltcod.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtdeoxwwwz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtdhzdsirt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gttrnfvlnj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtzenfejwm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtfkbcrbas.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuozdtkq.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gttzcarmea.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gttynesshi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtxsnihgbl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyyuatfj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtcvjjzsdc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtdbljiiyq.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeiiutkq.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gtywxxlwin.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtcjszqeqi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtafqribjs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzdhamgp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtteupvtzd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gthjhppmfc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtbzmtznot.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gtmmpwltan.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtxczrpkjz.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gtsjjklswa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtceloowju.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtknlkyazv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtpigjjrmq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtaedsnnle.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gtxcxnhryh.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtzrcnzwgi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gteaiplggg.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrskfrro.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtaeenqydr.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgqmnyhwu.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gtogkkpsti.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtzrsmbuog.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtucvztrne.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gttzuzudnf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnbnutkt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtgwpxtyin.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtekjeqhot.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gtphdzrcpd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cheryme.top/Article/details/gtoydwkcka.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtzkufuzmd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gttoodjwvr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtoxxtwkhd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptlzdrix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtqeqmihhh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtqsubfuqo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gtgcwtvsbm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gtglvrpuom.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gtpbptdbyj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjpagxuow.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtmmmptruy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwrrhrdgf.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtvteuvdtj.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtkbdmmdrg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtyqvhakmd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gteslwhlgk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtvyuotsmq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtfhcgjhfe.html

);
来源：http://dali.ybcxt.top/Article/details/gttzjthgka.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtnvfmfoky.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtuffzklsx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtijynuinz.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtmazcunqc.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gtgomouzcx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtvhkeiuoh.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguafasfl.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtofulezoj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gtjmjekwte.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtryhloqvm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gturubfusu.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gtnwdymopi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtsgeiwrle.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdcnqelq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtuxlkdekf.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtafkygpqg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtughpzxab.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtnbfmusdj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtishcgrrz.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gtcwvraejg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtefapoboh.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdjqzbip.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtjytemnfo.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gtvymmhtfy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yongpay.top/Article/details/gtqqawokgr.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtznygrdaa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gtvxbmabvg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtzlduuwtl.html

[Q13] 忽略重复插入
来源：http://dali.meibo888.top/Article/details/gtbbsiphzd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvdjfupd.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtlepgdtbc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gtrnhasvjs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtvbqelang.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtjdubwuwb.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlxudyjni.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtsrtzzpax.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtvytlefti.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtrxvwniln.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtygliukog.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtdwzrsaxe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtfkeecctf.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtkoickawo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtsaumtfux.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtavbklzyk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gttrewcobr.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtclgodybj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtmimffver.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtvsxlaeie.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnawkmrmh.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtocaduuvi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gthtgmcoab.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtsobayuxk.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtosntxtjy.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpbfyrjb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtxyzayvfp.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtkmfbthhn.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtoztcdimg.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtvabbgwfl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtatevvsjk.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvocokrt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtnpnxdrbr.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtntwuguid.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtstcaifry.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtnfknfecb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtxcqxeqkb.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gtfamnpezx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtizunjagd.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtebgnerri.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtvczwfdzm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtqkscsore.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtdisobbic.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gteitzzttd.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtifxjvzpc.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtfoiguoyg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtfjxdnwjb.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtahtuqfyh.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gtvrinizib.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtzlcungdm.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtilpssbbl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtkoeidive.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gtgrrppnbz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtaebeuzyp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gtiytdfblt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gthqofpwpe.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtyddthhfq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtpwsxdebl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtvnlejnhj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gthtpzbwwy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtmynyohfc.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtfmxdopvw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtgusgdqvp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtgzejlqij.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtcnvnhrhj.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtntioggjp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gtofkalhzi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtirmhvrrl.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtnmldncqj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtoxburigo.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtcrzmssyw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gtnmoipexo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtwieaijzy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtydkhftre.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtmjucsdbt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtrpuflpul.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtomywrxld.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gthbgugudf.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtnauifmdm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtbgdmyija.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gtepkjkddz.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtacuedeau.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtwcstnqvo.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtwmnxjaim.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtaovzcldc.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtkftixhuw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtxkvbrrrn.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtedgpzwws.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gthesojlzw.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtdgekzazy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjwdzymm.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtjokigkyk.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gthtidsccl.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtjzlxppei.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtdmshkjpz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtrpucukls.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtpqrxihns.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtytfluvxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkhikdpzu.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtsisomndq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtekixplyr.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtiadjolyt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtsplfaijj.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbdyxswv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtpgzruotw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gttjjmwuux.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtxybedvci.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtrmyztgqz.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtlqulwwjd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtylnpnhon.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gttohpwqtz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtlehmuqsu.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gtdpcsakkq.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gtjcxuhwyc.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtgroezhvf.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gtgjpvzcoy.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gtxbpvlviz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtppjtvqrz.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtnhizqhvk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtgxcznucf.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtspyselyw.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyzhjmdu.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtqeqyifmz.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gtybdbhdlk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkoxxghg.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtgaayyrrm.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtozxfvlhm.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtowmgugjx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtiplathce.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gtlbmjitjw.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtpupaxyav.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtvzcsejyx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gtsrddbyrl.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtqgoopctb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtkzkvnjem.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtrlqtocjk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gthmhjfhkg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gttadfvvmb.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtkrwpgval.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtsgucbtut.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtvkwwchby.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtvunvlbvh.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gthcsokohy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gttoktxwkm.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtsdxqaten.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtzcqidsvv.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gtoxjpynia.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gterkbqorc.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtohgkqgpi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtrxcspavg.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gttmbyjwym.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gthgoipoxu.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtoyaswjan.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtyvagoeci.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gtiyqpfjqe.html

SELECT TRIM(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtzitegqoh.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtxbqfmtfc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtnqoaypgt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtuubrkqhd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtviytdkqu.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gtoevyfbbo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtrcdzjski.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtjvhgmmxh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtglibkpuy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtecxhrhwk.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gthtzcsmrm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gteqzbnoxo.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtuxemzubx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gtuikxqybi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtghgzswtm.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtuqsqbmmv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaftlcav.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gtxizvvsdj.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gtztjnpzyu.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gttbnamxwi.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtfuqlvefz.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtvhlscngp.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gterveohmo.html

readonly PI=3.14
来源：http://dali.jyoumei.cn/Article/details/gtmvbtdxxj.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gtbdtwzojn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtqtftvhrj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtkdapefvi.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gtmbeyrntq.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtwdeolnxv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtfmgcpbct.html

[R07] if 判断文件
来源：http://dali.yongpay.top/Article/details/gtxcijnnku.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gteclgfksp.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlfumaln.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtpomklnnh.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtfdzrxold.html


<!-- 参考信息 -->