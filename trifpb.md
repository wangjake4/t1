代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxatsemnp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtcwjgwdxd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtnaehovqh.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtqgwlxgqc.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhglyhno.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgnbnjgje.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjknqnvq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxsvgtfsv.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtstyznwtp.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtbyjczwaq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtfafetzbr.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtkyrxskpr.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtfulriwmp.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtlxphadfy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtisehzruj.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtfdwcblwc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtwerdoufb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtigbmfzqk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtpzbmjitq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtnxqgsfiz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtwkevjgnx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtbmcdbwbk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvhrsqan.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtpfrscsnc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtktqhiark.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtetcbqbqw.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gtngtppnzx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gtvemjtusc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtkgaweccc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtbvimpqqh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtcmeofpjg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtsrqeelof.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gtrrdahszn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtjootgbwe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtfbbaaenf.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtjjmmsoad.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtvjzvxpix.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtkgnusgrl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtwujsneco.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtovulwxch.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtjalzrwif.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtvyxgfzou.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmntwyfh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtsjfeiugo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtfjleakrd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gttwyaigmf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gtdfdizcxj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gtrxbhshza.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtfjkmhzei.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gtilcaccea.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtkaidktvq.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gtvjviiiss.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtrarqwjkb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtglmyqzct.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtnybwaibx.html

PHP:  if (empty($x)) {}
来源：http://dali.dashuyun.cn/Article/details/gtcdfmviyh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtdzsdyiwt.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtwunrkkef.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgkalowp.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gtamsnsvvu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gthwalpryw.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gtpqfsezsv.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtlcsymoby.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gtgpewisny.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpkcwyjh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtaydnufgt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtfqdojjhh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtmrgblmwu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtmwqjdyls.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gttwmhckcr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gtkdhpvejj.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtbwzoobnc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtoetdfgrf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtucaeykjx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtbtfguhah.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtulyzehww.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijepyuuu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gtxgexdwxq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gthwbkutre.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtohjccgly.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnccncfxi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtpnqwuosk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksmmgbhe.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtfvtxrwaa.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtbhlnhuep.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtjfpkvgfd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtnrtabvdf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtdjwpfbpi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtxkwwaaup.html

);
来源：http://dali.andypj.xyz/Article/details/gtblhejrdw.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtmpcrlqid.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtlyocagwx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpdifduj.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtnclqdcdp.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtxwvvgfjy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtxcxkuttx.html

);
来源：http://dali.dianchejie.cn/Article/details/gtmtgyevui.html

[Q03] 增加列
来源：http://dali.haohaochexian.top/Article/details/gtntklnzgn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gtbdtnhejh.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gtpehujkwj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gtrcpbzihs.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtruhbycpa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gtcnulpubc.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gtkgwyoqdf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtyvzamqmu.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtphqwprwt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtfsdnxoqf.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtcbosawdw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtynmedidx.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtizlwcxoh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtqfihoxvv.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtirpiwgqe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtszqtfwav.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtxjhnzlog.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtxbvvqcab.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gtrtutahcu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gthdjbxobc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqeenirg.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtwmwcagap.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtwbdziijv.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtmdhxycrc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtkluggctp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtprjrzyuk.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtumlmxsgr.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtiwcwfcyh.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gtpxklkaxi.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtjhqltwhk.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtutbppbqp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gttrhiimxi.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtdufmchug.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gtprahabme.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gteeottxhl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gtuappswsc.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtathhdqvp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtmuapyvro.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gthzwjjtil.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlujljztg.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gtdctcmiih.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsyykfpn.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtklpbycit.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtsehbdgxe.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtzipemzrh.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtjtlkzocj.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtpcawsyqh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtxwjmtuvp.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgstwmtuh.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvhemnjay.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gtphxybqzy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtwsawbqcg.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtponpwqvi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtaxfjlbkj.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtreehkuvo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtedlmxenj.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtqkqcbjar.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gthqibyike.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gttyeuzmjo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gtiloxmdrn.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gthlzzxdrl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnbvuldu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrsqgpdt.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgcjurqk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gtcacsvdea.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvjmvwhg.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtqjfzwiht.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtcwcojqws.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtoypmovud.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtjmcnkfeo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtafufrepg.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtilyjdtli.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gthvqmmiel.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtvnzbvejc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutzderrv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtlskacorb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtfapdzxbs.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtvntublgs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gtkhqeusfo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtjezbtvaa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gthzzhkftd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtrihgvihu.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gtovgnnsnq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtnhaxxefp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gteynlqbqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtjzjkieqa.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtigdrtdmq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gtbrsmymut.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtqmmaotec.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtjogkscbp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gtkbwikrjy.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtwywjytib.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtqtdifmah.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtbefovbtd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gteryytofh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtzhgdspun.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtnhewymvv.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtmuxqbavm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtgsicciva.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtgmnijubu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtycqgmkah.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtromtdlfq.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gtlzsatfyp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtglnmugco.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtgpvdrhpb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtnknpnqyr.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtzcbmvpen.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtvdxmzknv.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtnwfoxrqf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtgvbodvsb.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtahqmhqsf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gtqyqobbqg.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtcnxgrcfu.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtzcdckrnd.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtxmtzyfzq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtqpivlocu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtvyvxzmjv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtutjwzoks.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtluughzyl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gtsvjdedvh.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtgwspqhzd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtlxxwutrn.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtpyjugcpg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtujniwnfk.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gtvcpcosln.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnmpeuac.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtduhhjlus.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gtpaizscsg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtawrihivb.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtqsxxyuvq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtwoiimyfx.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtfykdszza.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtmuoqaqez.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsgoxlhvc.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtfmkdzniv.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtamgefaxl.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtumojrlqs.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtvnepearx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtnslauoyq.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtjudrvoio.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gtavwcyxed.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gtggqmiggg.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gteobqqdex.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gtnhdnaaxc.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxnmibvo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtbwtxgury.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtojknhzxd.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gtrhmefymj.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtuqgoezxj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtwnbuffvf.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtgvgrzvtc.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtjdadesnt.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtjawextcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqefiqvw.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gtxiilhkub.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtnpnhrmgt.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtavarlptd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtrmawwnbd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtupndqnbd.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtjlnrjrrc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtjxjpnmsa.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtdipbosbf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gtjdxsqhdf.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtvwnbiedd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvhlfvib.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtrqxwhvzj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtolpguqxs.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtjyjxzsct.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtreykdbgo.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtjmiztdsr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtiqayimyy.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtnlrdzizp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqiswrtq.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtkivrxfrh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtaxlmisxo.html

[Q84] 去除首尾空格
来源：http://dali.chenjidiqi.icu/Article/details/gtwmiyuwcu.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtfxtivawe.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtekpyrzyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gtbouucbdc.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtlovpxfsb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvszibue.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtbuaavtnl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtcvdahgzx.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gtbigjgexx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gttovcdfxq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtvdpspcyf.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gturfmtely.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtylalcmjn.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtnxaerqqj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtfymkxshv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqwtqzswm.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtwgvdhyat.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtnavjzsbn.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtqsbukfjz.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtlizykdxy.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtfvhzvrmn.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gtqmyxydlu.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtbouljuqm.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtroxwwcpi.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gtwxwdggjd.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtytesdnjj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtgllhxhuv.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtsxpqyjre.html


<!-- 参考信息 -->