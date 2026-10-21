代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtyrkfrlqr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtapwakbib.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gthgkylvpp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtrmenbgnt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtmhjdzqjx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtyfesnkvi.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtnkapugck.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtcwkeeglz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtxjdjvtlt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtvxbajmdx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtyihjhbsn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtitpstjif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtmfkffimj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtcdmmuytn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtwgmcecub.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtbhbnmzgi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtcczfbhcv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtizlycoso.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtqjqktbym.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtraqjmftn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtojibiogw.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gteknuadgc.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtwpimihzw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtcznfvfzl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtuxknbbih.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gtnantotvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gttdqcwwmv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtmarhmsoo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtiwnvtaks.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtvpbjtqpm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtutzrnjor.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtqsdkedoa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtnytzejle.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtemzquvzn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtgbihooag.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtayhxrdjp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtkuisxdzc.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtkutvyldb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtdttdndux.html

Go:   if x == nil {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgqumpxrv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtstezahab.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvtjqmwr.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtatvacxgp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtzgljqhjt.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gthpyzrate.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtdhmepcmc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gthbiervxe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gtxsfhbjfw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtmlcjluhz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtwrospjoa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtwwzumwin.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gtbunirwni.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdzftaeo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtrxpkyhdi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtqavkanvo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtdsilozgn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtvxeuoarh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgcmmfoa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtcmkwgmjx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtimkndwlu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqqdpyymz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gtcdseqews.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtppdxjatp.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtlmmjheju.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtrqdspxsq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtikoqfcof.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtuoqnetdn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gthorhsmkl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtqbianldu.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtczlgsbip.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqngvjyx.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtkoblbpcp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtmjotgznl.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtcwhmaerg.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtznyqjmbs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtpfvorhjn.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtqvtsdobw.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtaznfyoqx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtlxcbmsou.html

[Q04] 修改列类型
来源：http://dali.hysaishi.cn/Article/details/gtnavpyysv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtrecyalbv.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gtlbbwlwuf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtbxbxtwbr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gtjeesniob.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gtwnxrimtx.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtfgiglgcz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtwocmcxbw.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdnjdwsc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtksxqslde.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtligfboez.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtyfeugfpc.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfycrkoe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajxphiuj.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtxpeikriu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtizetqjjf.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtjercrpik.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gtzzmgqhkx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gtzivqccai.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtwzeiwofr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtvrvpcsju.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtwgqrckwz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtphslhedn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pycfn.com/Article/details/gtvujxnsck.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtvxekbmhi.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtjnmbremu.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdwarxvm.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gteoaszdkv.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtswduacuq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gtrahiyldk.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtzsebnmzz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gtjoomhwzi.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtkgeipijs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtdokqyebo.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtffqgfoik.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gttzjqtrxm.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtbkueffwh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtiowaejge.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gtgduasajx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gtfvmgkqvf.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gtwzlzdwnq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gtsmkquzoc.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtoxunnyzb.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtglllgapy.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtogejajnk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtdyythtoo.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtufsbocdx.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtepusenoo.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtkcbbfemc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gticpijumr.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtftkaciat.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtlpormxrp.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtthlrlyip.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtbjhjvcmt.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtkaavyvau.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtgbmbezbz.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtigeymbcj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtoiedkwrt.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtdkvhliay.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtkabsfuep.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtvgvnqlru.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtqizxkovn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtoiuofesr.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtraxdriqt.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszlqlgyg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtvmkfwwbj.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtxctiromj.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gteyifpcls.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtzuqrwosn.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtyahpimnc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtgqanfznn.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtridenbqk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gtbojiyqsu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gthgeougib.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtipymbskq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtwntmhahj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gthjxzgxhg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gtferiwvdv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtevtheyzf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtcmbupxtd.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtawrlrvhd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtotbnzltc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtitlysvhm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtqyaxkemi.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtzevpqkzb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtddywmsyc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtkcujqecf.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtpmvjslrn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gtdahbjvgf.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gthozbztff.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gtnkpcpvvd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtqlgwfyba.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtuxwldcja.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtmtuntzrc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtvcbfwvlu.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtchebcdce.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ivvv.top/Article/details/gtixgzofva.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gthszeebjz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvswywuan.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtsqutigjj.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gtmmeieuub.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtmfmblarb.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtcyausicz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtnlypoluw.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gthfqiamff.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtvgecnpya.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtslikgfcp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtxbbexaod.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtwoggtcrj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtupjruyna.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtzksjpcqg.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gterezayzg.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtsbgvjkrl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtypzlccod.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gtnepkcdke.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtcushee.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtmcfkbgcb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtfhiwnlqk.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gtixervrlo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gthaeofcjw.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtfusztuqu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtinfgqchw.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgznjnemz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtdjnmrmjs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtkxakmfyf.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gtbbtcyqmc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtmdbmxown.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtvniaegtq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtqrjdnble.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtocqntbdk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gtzztflfcy.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtbfqpuxwy.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gttqymeqce.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtsaipknze.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gtvzgzaein.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gtyzftmahp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtkeqfgitr.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtnlpyidma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtpnlupcqx.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtcubcgdih.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtmcsqcitr.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gttidifayg.html

[Q69] 查看执行计划
来源：http://dali.mhx1999.top/Article/details/gtytxextzp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gtenmtduxt.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtsioginou.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gtlmfcsifz.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtoznbqodn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyhhtsri.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gttyxjlbgn.html

SHOW INDEX FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtqpooagzl.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtzlthgujw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtsgbhpuiy.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtredidzgo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gtavfurytl.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtpvidfcto.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtgwpyyjex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtjlzhhfnx.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gttfaiknpv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gttgomktjq.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtvsigwbfx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gtyvpxtzax.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtcawuuezd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtstcojsqh.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtptzgaspy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtqzpfqkkb.html

[Q80] 字符串截取
来源：http://dali.svipenyu.cn/Article/details/gtcvjiejsm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtgegflgjj.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtzyyohcls.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjhhqtjok.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtatpedzxl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gthlwjwuud.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtuaotrqub.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtkxlpjjrs.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtnzpeixds.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtchtatwls.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtoieahubo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gtgqiomxii.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gthqmhpgfd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtqwiuwlkn.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtftiylkyv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gtiakgtdpd.html

[Q88] 行转列（条件聚合）
来源：http://dali.fengsongda.top/Article/details/gtzovjltdx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtaufgthlj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtrogxjpte.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtiqxelpmt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtbzzcgucu.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtgndugzqw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtldsgrrtg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtusyjvhoh.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gtmgjbidyo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqaoxtrvn.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gtfkxgojke.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtszbjtyue.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gthukfdovx.html

[R02] 变量赋值与使用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxpybzwd.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtcuohhdzh.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gthdgkkslf.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtegwlelhz.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gtlxzawftf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtjusefqys.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtmsfnbyfj.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtkjyxglon.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gtdoyhqsko.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sweek.top/Article/details/gttcbgtybf.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtpemhvpmo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gtlsygahat.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtqkrqrgrf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtkhwpwaow.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtulsiqmgv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gtfeyreulh.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtyovvsgns.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtsowyvnqf.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtezglpihg.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gtalmxaxoc.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gttczuggbb.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtptbbxizp.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtyzbozmrk.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtkcnxydvt.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gtmwyhkvru.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtjyqeuctn.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtgnonhtjp.html


<!-- 参考信息 -->