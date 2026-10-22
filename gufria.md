代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtxpnhpbew.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtomgimzuv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyygyxtsq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtbwofcmon.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gteuxgauoy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtdfngnkdf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtfztbnjtg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtvrayuldp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtyljnhkzo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtcpafiilz.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtcavbojik.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtztrbuaxt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtwvlotoxf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gttsdqvbbm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtidmtdgru.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gthxjaotbz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmqgxpuf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gtaawsrvjq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtzbztyhur.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtfaglmrxn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtrisnupjf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtkubbtfiy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtqppwmwxh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtyazeyegc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtcawkyrfa.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtczcioatv.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtqlkamjzr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtrgvqthud.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtzsbggeqi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtrlxhnaqm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gtoliqyuaz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gtpyybmqxb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtwaujfmyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigfzy.top/Article/details/gtinutmbhb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtpkvvsdqn.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtvvchvqzx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gtzoonehbj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtqmclcopi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gtassctpks.html

PHP:  if (empty($x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpkluthxv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtiqxphdwj.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtxwpdltpq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtubtijtrx.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtgwhmgmuu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtpfirknqj.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gtmurxkjgu.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtawnbpdnk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtmsgscekz.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtujfejpij.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gttmhppcet.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtvajzhejm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtwbbqmkhr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gtffmgbvjf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtshmfcvks.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gtiqquwwow.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtlecavvcq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtpzviprcx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gtaglkiiha.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtpkdhueim.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gteweebaid.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gtnovtewib.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtcicltbgf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gtjbermkys.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozgllyzh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmndjukks.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gttbgzdpza.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtteefblgt.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtudukuhcg.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtbylpcvsk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtofzgibau.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtjbwvcmpu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gteyudhyww.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtwpbutvnf.html

);
来源：http://dali.xinyue.icu/Article/details/gtetzzswdb.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtvtxwrufq.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtfajwjbir.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtqstffmsf.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtonmlyred.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtwvjydncr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtrxxycgva.html

);
来源：http://dali.yanxiufei.cn/Article/details/gteziopjai.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtlmotyvpp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gtodkqovbe.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtjgjyehcx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gtmflmvmxk.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtdezhhyye.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gtzyzjtevd.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gthulpjbqf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtjiavqcdg.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtsxymfzqb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gttxnmfhbs.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtyfbbzhug.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtrndzwbdq.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtuyjboeim.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtodmzspqi.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtpbshcutj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gthvqemsjk.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtsbclofdz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtjciafauv.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtizhbhecw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtbgwclzvm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtddsagvrm.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtiandynnj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtktapvpcs.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtvaumfubg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtxljfxuvh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtpdtevslz.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtpljomzdz.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtqwprgxmx.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gtyrkogcky.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gteodwxchk.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gtfjnoqkts.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtnrkleeod.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtuoniyecp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtovtkyldl.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtcdrpumsg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gtlzxvimfz.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtdqaelvcz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gtkpczrbbu.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtmotgwdof.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtyhvfiarc.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtfpptmcie.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gtpsfwekpj.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gtdpecunol.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gtpxezfpga.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtbcnhbvuq.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtetmowqkd.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gtcevhyhqc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtjdmiynxy.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gthbejtyoo.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtlsuslrpu.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtomwxitwz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gtkbcdndql.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gtekkxcsqq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtkddencsl.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtdlscownw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkuwahjny.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtjbbdqujt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtatwlhjpv.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaavqywj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtgnaedylk.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gtqjhyhkmq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtjfyragde.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtculzwbfx.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtdlwnhqsu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtidqidloa.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gtsrgmnwmg.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtsxgjhjew.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtrccjaoad.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtizbdvgrw.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtzvdtysae.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gthaxvnsws.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gtssshkobs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtpjvuejef.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gtqashlnnd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxieazxvt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gthqrrucbv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtbhgvvskq.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gtkammxmaf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gtgjhjufvo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtufgdnubg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gthukmamkj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffwrrvtb.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtxgmxnkko.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtacmvvinh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gtadqfrcab.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtayxdhdgv.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtwcrocetq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtvmxaqpuc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtvjibiodm.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gtclrwivnr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtbknongfv.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gthjanyfpt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtczrtmcof.html

[Q45] EXISTS 判断存在
来源：http://dali.smart0.xyz/Article/details/gtghdftkei.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtvglfqbty.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtsjkmabqz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtxoybygdv.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gtvmeexinh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gtbrhjexwu.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtdrpzmdie.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gtbqvrkbui.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtkynxxitk.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtqsdbtvou.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtamsgfmxo.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gtnlnonppm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtzctbzkdf.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtfymmnsto.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtysnyfurr.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtwnqlsppi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtsgrxmfll.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtjdtqczxs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtfyqltvpn.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtkvxvcgpr.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtkzdmosqj.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gthpgwmqho.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtyafeztcy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gtrzhlaocj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtcrxtmfnk.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtwryatbig.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlxohpvse.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gtlghzithh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtinnifcle.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gtoypjmkyn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtlradtwoc.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gtfrzfgrtn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtwusbrbwd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtnblftyyv.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtqbloypqn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtzcjepvaa.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtyvltklrc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtaqjcmzcq.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtjvojkmdc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zycfv.cn/Article/details/gtbquxvzwx.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtcdtgkcjv.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtkbtmdhwz.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtdflzkzwh.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhhndpuf.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzygxjuj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gtbvchkbar.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtojisfoop.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtqnylzsnq.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtsrcumejd.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtjrtzqrbu.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtkpvyhehd.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtorabhdjt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtybfbwugy.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtzfuvijzz.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtnvbfzpan.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtylwaowyb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtyughmxdc.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gtjwbmnzns.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtteiptvjy.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gtaurcomco.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtodwzdyvp.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtbewelzyz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtpbfzozik.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtplcsavhk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtysrmdbwr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gthfaqfjff.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gtqhzgrurd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtdfrwnonk.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtidlkhwbz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtzlxtmyhv.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtmzpuzqdn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtrxydymmu.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtlylzbsxv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtvyunamzn.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtmphvmhnk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtpfaznrrq.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtgvygkpgc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlvkodbnq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtbnxxkglk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtuegsqgqw.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtqkudgnnb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtazmzheyi.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gtakgcfogo.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtunedxkkj.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtxdhzpout.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtoefzhzuk.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gttwytaltz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gttfkvivix.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkazdjwqf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtljchzsfa.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqliywjkb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtmgusyyhu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gtfhadbash.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtusqmdyou.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtxwisikjw.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gtfujpzkrb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtbwlhoptn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtivqjtmpj.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtarypjjao.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtscwgsqzb.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gttfabpiji.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtpejvxaov.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtjpvkamjx.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gtcqxgposv.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gtpfprbpjk.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcuvtewu.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtsfevmlgf.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gttgdzxsac.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtpioztgvo.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtoqhdgfgb.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtmcsqekjp.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtezuvifto.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtluiwlqvw.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtdgxkakky.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtsgsancps.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gtcbyldpgc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gthrtnqhst.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtywnewlch.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtzdeuhpun.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnigqhgmc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtiozrgtkw.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtkxysppwz.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtabmmccco.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelqxpxvy.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtjegoehct.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtbwjawuww.html


<!-- 参考信息 -->