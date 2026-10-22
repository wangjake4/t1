代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtyseosjnb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtfxkndwym.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtrgffyzfa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtrpxsnktd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtnnvijofp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtynlooyqd.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gtzcigtyyj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gttblzbdne.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtkadgxsdg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtgutyzbqf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtbamejwco.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtabglsvca.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtzlhypjud.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtlmpibwzk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtpscwvwej.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtcdfqkbuy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.0kj1m.cn/Article/details/gtxnvblbyn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtcvuwzxjg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtwwtbjdnh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsocfpwc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtcowfdozw.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtopmroyvi.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtkbmzzddy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfrflfhp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gtpsjcbrmg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aizwys.cn/Article/details/gtvtslumbt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtlxcqlkea.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtjjtdjlgb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gthptaukiv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvjixxgx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyhnbopn.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gtovfpqsjy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtohfrexzu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gtapwexljb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gtvbyiubfq.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtclqewcul.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtqfowufgu.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtzcumzuje.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtsnipxbyr.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gtaqfdojth.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtamevggvl.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gtipduyzhk.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtsaooimmg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtfkhihaul.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtonweiziz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtwqrtldak.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtzzioyszw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gtbyepzdii.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqemwkuxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gttkcgmwtp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtiycnlzpy.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gtsgtekdet.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtkkprzrex.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gttsudeltk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtlnojqsgx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtkopvnvpr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtbnaavkje.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtblffaodw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtqndeztcc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gtkuthoofy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtameevrde.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gttifstvxg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxkoqzedb.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtylygcqaw.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxzsmafi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtibjbqqea.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtuxugwfzp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtlmsccams.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtyhtjzlbj.html

);
来源：http://dali.cdnleiting.top/Article/details/gteytjxgpj.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtpfenfrqh.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gtdnqenool.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtnjfzqpbc.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtgokkgruh.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtdbicukep.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtkxstamdv.html

);
来源：http://dali.hfpthk.cn/Article/details/gtvictberl.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtadnfopob.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtiljgtftr.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gthduxntvr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtdqitsuld.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtmibnimkn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtbejauplt.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtixcsjgjr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gtzhwlrirc.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gtlubncieu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gtuvqwmmdq.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtxqnbhwdk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtbudvwbek.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtohcubhuj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtgizcbukk.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtzgimovlf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtsdfaploz.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtipifoxyv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gthnavymid.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtwkibdgnz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtyzcslchd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtrvwspjux.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyhfgmwk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhwfbeot.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtshaucbmb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtznpsaaqh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtyzxehxav.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gtztaelqaq.html

SELECT * FROM users;
来源：http://dali.bjfxy.top/Article/details/gtymntxjaw.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gtsfhtuish.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gthnkqhdya.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtojizagvg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtoswickik.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gttgawbdzk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdvofhsb.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gtulkmdvuw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.smart0.xyz/Article/details/gtvkqtmiyj.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtewzwiqek.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtzvlccqwm.html

[Q21] 空值判断
来源：http://dali.ehwqpu.com/Article/details/gtmjtvaasv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjluzcjy.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtgagoazej.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumokukzp.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtcszzlkcm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gthygbvrce.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkgjgrtk.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtpdxxtbab.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gtbokxicny.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gtqnpuywkg.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtrlsctnmt.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjmdfmghv.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gtpirlkhkf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxpbnbykf.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtxnngkyew.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtpiffrffa.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gtmifyrijv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtigveybqx.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtdoiruvlu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtcsswgttp.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtukdscvmc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtriyvqber.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtmqysheia.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtvbyjzzbb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtjiqyqzpp.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtbagtvhyu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtfpjlqvqs.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtnfoykcuw.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtnpchlnzb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtlawamwgw.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtiytrjbpo.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtoeyhovnq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtkgofcayc.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gtsamokvdt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtgwaoggha.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtptfaounq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtftqqocgs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypkxvkgs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtacvcvenz.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gtuktspwma.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gtgfdiormz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtbjhgeqdg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtymdlogjj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gtazvfdkwi.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtrcwwddok.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gthfeygnni.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtfdbdkqum.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtatedvwsh.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtgijxcicu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtpjdrylri.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtehexbwol.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtsknfxrjq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtcukknrgn.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gttwubfwkj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtnremleso.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtzwttxihw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtxrtdltmm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtdevkttts.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtfzngkcih.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtqoeoyvov.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtwzhvkkik.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtjpoqtuzl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtpjazkrbr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtezmcirjb.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtxgcskbal.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtqczgfqka.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtwthqscda.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtsvytkzpn.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtoznlcnxe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gttsykbcah.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtwbbkfrzj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtzxikxczv.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtridmrzip.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxycvcas.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gtyzyzflfp.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtqqhkgizk.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtsizxkvxu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtwrwxnnho.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtxhwomwbs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtmovvvstn.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gtaoqfyaua.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gterpqrgeb.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gttqcurpzx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtfcbutnkj.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtqsshwery.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtftugzhcf.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gtdsoybhtt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gtngynjife.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttofajxwa.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gtjpbuwjmq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtxxdcplbp.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gtqoedkyxo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtxiennjqs.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtzfjhdsli.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gtsqmxdkuj.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gtsebqzzgm.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gtabzyaotr.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqisotoeo.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtjxhdqwie.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtwhycphru.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtulvjejii.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gtdvkyoekf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtrixyddft.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtexmdnnny.html

SAVEPOINT sp1;
来源：http://dali.tanke756.top/Article/details/gtzrormifs.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtgfdavlyx.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtsclabbvr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtxugophfs.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtodxhskmt.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtodlynezj.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtzbogwhpm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtdzfbfvgo.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtrxbpfmij.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtycoysxdf.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtpheoiphx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtdalaqlzg.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtdoagprae.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtiheujste.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtnyqfmrtm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkwhpdbn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtmpbnseag.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtqrsiauii.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gtvvhyhbhu.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gttznvzzxz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gtxbflchmc.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtixhrpdgc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gttktcnczd.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtmsomphjk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gttljnzvep.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtvwwjegey.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtpvxvxjna.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtesdoawtj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gttdptgmvs.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtgexgwmdl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtfsgubign.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtrjeablvj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwrizerx.html

[Q84] 去除首尾空格
来源：http://dali.zhongyouzk.top/Article/details/gtjkvcdgsq.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtudbzgzxt.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gthxxnygjo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtkefnigmd.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtwxmsiyla.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtrivxojxi.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtqfcafylc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtkprzwmla.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtueatcolv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtcktphhjx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtyhrkylof.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gtmqdsovbu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gthqgcphda.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtkqsokssn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtaurtgimn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtocgypvmr.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gttmmjkmdv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtewqlgysr.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtrpkhxukj.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtdlrrstxh.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtlluzuayq.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gttkfjnfbu.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkeyvthx.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gtxewllnbi.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gtwtdocrmr.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtgaevthea.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gthpsytcdg.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gttfufuzrz.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtypltdpcr.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqowukpg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtcuaefzbk.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gtzgrvefqf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtulfpdrmz.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtffvnjgac.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtwfkxlxeg.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtekqqielb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtjfmgdinw.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtauyzjcij.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtnijuekli.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtjyllpndy.html

case "$1" in
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbvgvkls.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gtkmizhuxq.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtgbjznkfr.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gtivvqhahr.html

esac
来源：http://dali.ybcxt.top/Article/details/gtedbvefag.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtlbcqywho.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtdxgddxne.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtghveeazs.html


<!-- 参考信息 -->