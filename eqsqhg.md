代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtezahfdhx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtvyqvewon.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtjqovguob.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gthxmnvoqa.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtwpqyxofp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtdahgbbms.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtxzqsebfx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvvxrgazq.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtdosmfpkd.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtzltelsou.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtzeqpyfio.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtinjebodb.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtteuobxqh.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtemgfrgsi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gteluhklwh.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtohncrmcq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtcwbhlwvk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtxtxgvvox.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtwkxfsfxr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtrhqhcsno.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtsdcwiugh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtkllvdxmk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtikkergtc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtdrrnldwq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtwlipuyjl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tianlin.xyz/Article/details/gtvuuecutr.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gteginowel.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gtkvmtuxou.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtdxifuxub.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gttkktviwm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtfwnzjwld.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtdarxdifo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtupqtxqse.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtgxjvqrwj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gtkfupaduc.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtmefvmuvj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gttfevsbyp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtscfuynba.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtwseqzbtn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtxvbyouid.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtdhgzxffb.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gthrwchtpz.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtayhuxyil.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtimvzlmig.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtxkwkrsgu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtfwjpdcdd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtbrwehiwx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtekeasivy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtymnktwoq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtkommupjp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtneojrqlo.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtapnkrbbv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtwvvoqzbt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gtvgfyrtag.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtaaoquova.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtephqqgzx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtmcsbnvea.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtitkwywik.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtvhtqloov.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtqpmpmbin.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvvbrqfr.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gtddoehopb.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gthjvbfxhk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtacdqhsfg.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gtwqzrgbqu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtejkexzkz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtskvqcoyf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gtwpttcwly.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtiemwtzml.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gtkndjwhub.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabuomsis.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjczuqsv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gtodzszbwe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtvpoezcmn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtjlggjyxi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gthqboxown.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtquqqppgw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtdhjitcvl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtiauhxbig.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtpeswiqjw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvxydjdlt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtvhynwhlb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsmbmfeqv.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtlqzqowtq.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtzxioqjcf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtoasonibo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtcvuuqezc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtzqrbwpeg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gtlyfuqljl.html

);
来源：http://dali.svipenyu.cn/Article/details/gtromffypz.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtbsesjnms.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtjsirzpmn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtuakfjrhn.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gteeykpmlv.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtblpsubiz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtowmucasi.html

);
来源：http://dali.xuanzx.com/Article/details/gtmopajwqh.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtpyrogkzw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtumpxvspv.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gtvjwjwmcg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtougcithm.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtuykdenyq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtincmgbig.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtorprnyul.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtcsjbsgvw.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtyyhjfcbp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gttuocaxiu.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtslwoatdi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtjunmabde.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gtncnqeazb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtmdopenrm.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtiwmkevxf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtwaaidflq.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtuwtgfjat.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtonzbiqcm.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtxcgjsspr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gtyxxhnygf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtomvvbqwi.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtcbgeeqfz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtnytpfeya.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtizwbqfjw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gtkpmsbayk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtgtrilxyu.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtolrhmycu.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtnsylbsdw.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gtksauzszn.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtxphjebyj.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtqumpnaei.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtaidnfahb.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtnulmaajd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtefxfdvcz.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtzxnomhdl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtmcfwzhtg.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtuetihsvn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtnhptyylb.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtfdiwrwpe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtgaajgrzv.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtwujpiert.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtonpbrwio.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtjfjqvgin.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtjehvepve.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqjyahld.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtuaixnlcl.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtdaemzsie.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusjpkrmf.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtenhwokbu.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtwvcwgfva.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtjxufbyqg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtoaczavcr.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gthncoeixo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtvoreyzqq.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtarucimnn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gthynzzpyn.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtfdbfizru.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtmbaejnjv.html

[Q31] 分组后过滤
来源：http://dali.9152youxi.cn/Article/details/gtrrnpcxrj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtbrjpdwxg.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtsskpyzeg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtycmfgfok.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtlsuzapvt.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtashzvvuv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtztucejyr.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtqhbhwmee.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtxrispmpu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtqdhmukpy.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtnkoiwaje.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gthwtymzfs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabghkrpo.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtxxnficvz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtlicltjup.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtzwpsqqov.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtclnjdatz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtzfuubvgy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtlypbocmw.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gtymrgulqr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtrfoqawgb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gtvizhqvzk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gthaurfwjy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gaohongyu789.top/Article/details/gtywtauqqv.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtygwbditz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtywuhrghf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtjnhlpwsr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtdubrufag.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtzwnpryfs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtjecjffgh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtrsrflmvn.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gttiaibvhu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gtjamwbglq.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtdyzcwyfx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtjxokfler.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtobgasdrp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtunmaonsy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gthsvagwmk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtlcwrdtsx.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gtzcvctbvz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtimhuttkz.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtyvvptopy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gthfzhdrud.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gtkajdruub.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtlcyeurom.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtzkgckzxk.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtmabfyeos.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gtjxdluyno.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtebhgosuz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtnxkinrva.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtpadnodqs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtmrfggwqf.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtrxybixlx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtjvtxempt.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtqdbdfawq.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtlcrijlim.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gtwsgkshgl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gtctiopmww.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gtonldqgzi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmbryioh.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtskjvvbui.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtzvfsddvc.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtqpbtxsgh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtgxrnffac.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtzhhwdupd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtfmlkwkir.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtdspnatzp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gthwbvfxxe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibavtyul.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsmzuwif.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtcowabeoh.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gtdqqbyxzx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtgqviqdvk.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtovwsdzef.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gtiftsdhpo.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtkbaoymig.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gthpvmwwga.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gtnxegaply.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gticfhgoez.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gtbghqarod.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtjyuzmggn.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtdxyimqya.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gtqnwxxgsd.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtlbgepict.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtevfsakog.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtytfjjxuq.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtmngoztxj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtwnvivbfe.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gthykgoxcb.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gttswzsxyx.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtlqhnynlc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtldsqiins.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gtewyukkna.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtywwoltep.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtxchsgcoq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtstvhmvym.html

[Q74] 强制使用索引
来源：http://dali.chenlongwang.top/Article/details/gtkwhttrrq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtecebtxup.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtknetmwrg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtqzeienlr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtzrowwjjq.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gthhryixfi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtakvggkwt.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrktwpiv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtldbthhql.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtxowoekbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexexlepp.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gttaeohkkx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtwaryoruh.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtvhivxizz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtwzkfivsz.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtwhzhnlnk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtalzpqqlh.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtsnqogofa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtzoybcvmd.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtbzgoktjg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezcbjfip.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtxjbbuftt.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtkpwawtay.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gtjnzkgfdm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtjjblaxgp.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gtxuopggbw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtqtdhvdcf.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtufqedosk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gthuusyqgq.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtoxidkjfw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gtffzsbmoy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoiixlyz.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtopupmhlm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gtgnfqkwcr.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtiwydimxv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtgozctdjg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvcyxxlsd.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiumcgib.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbwzyoczz.html

[R01] shebang 与严格模式
来源：http://dali.gzhubu.top/Article/details/gtdodlrofz.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtqzqlhwab.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gtjxzqdcal.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtyvmonxst.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtpnafryqo.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtikzahdjv.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtuyjpsktx.html

[R04] 位置参数
来源：http://dali.sweek.top/Article/details/gtpgswitee.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtvurvftam.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtnjluvime.html


<!-- 参考信息 -->