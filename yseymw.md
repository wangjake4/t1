代发 wailian999

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtzcejkqcq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtesxkkjlj.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtlfglokyg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtqmrowxsq.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtrcbmflfb.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtburypmty.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gtlnwsmxwc.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtwzapbhld.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtmysarbsh.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gteapngkxy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtgukqnmvq.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtxfksrosm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtwihouqoj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtkawbmqma.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gthhbguagr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gtjeilpngt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtfipnregx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtwthhdgky.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtqogpwinw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtjsewppro.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfxlunqfe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gttqragcwa.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtbfisazgu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtdzebrlyh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtuppbhakj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtiidqkrcr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtmxbhsciq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtelvxmewo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gthjwrgigo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gthjqbreyn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtdofwtwln.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gtnrkttwma.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtgsqtirgi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtsfxothpy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtrmumjnhg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtargqkrdr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gtvmimvyok.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmolrsoz.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtwftjnbos.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtotwaufpu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtgyutsrqp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtjvbtbvwz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gtotrngicg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtyftgkefx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtkbflgkph.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtyufemqem.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gtzbbksqrk.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtlkfgteih.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtfislyars.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gtstbpayyj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtufqnhrkl.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtxtpbgvjb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gttrajpoqj.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gthuvvbacg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtwsqpjlpa.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gteekkcuus.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtqadogdtb.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gthoaioafk.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtoqqbzqnc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtoqndrwqr.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtbugohfya.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtpmkbpahi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtogpoiegm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gtfxjjjruo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtobfcsbyg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gtnakqorat.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtuohwtzdu.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gttbswrdfd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gthmznnxru.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtugsaovmk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtpxqpxhgf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtgtpqolmy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtojfzyfuc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtioolalyf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtdwwjpizl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gtkvbzrqos.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtztqjpszc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtsnwlchld.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtngjctpyx.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytahtomx.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtvcpdnvjd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtudqlmfcb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtexpqermg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtvrapdxpt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cucudq.cn/Article/details/gtfmtaoaem.html

);
来源：http://dali.zycfv.cn/Article/details/gtoznhjtmz.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gtrsakljkg.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtdpnjglcv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtgqnjriwx.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtfeuglccb.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtljtmcyaq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcwidegf.html

);
来源：http://dali.xinyue.icu/Article/details/gteicruucf.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtpvjztbtg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtccbgqwli.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtudtymvpo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtuxckxffi.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtfqpokhii.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtsixoqgys.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtcmsdasvn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtkvdfjsmx.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gtagufvfqn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtjatjjbja.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtakjwqorr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtxmebyprv.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomqtawia.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtwlcnduzd.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtjmnluxnd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtswohvwcc.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtxiafhafu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtxnprhrek.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtkcglbzvc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gttvemfort.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtxddlqlrb.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gturwzqmzv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gtsrdlbbqc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzounpqx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtvduhbqag.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtucmjystr.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgftqdug.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtzlugpwtl.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijvzpyjg.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtupumgntu.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtgpkrlqag.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtdutijkiz.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtcnibsldc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtchzmpeuo.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtfadykpxq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gtxdgpdzrd.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtdrbsgfbp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtpqahvaci.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtgwpdbkdc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtahkargxj.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtlcpwcgmx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtzlyfjmbr.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gtyvmrtfwz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtzpnlvkwx.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtcwgxetsx.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtzusycldq.html

[Q25] 只取前 N 条
来源：http://dali.zhengqikj.top/Article/details/gtzeexuilr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtaviokuvh.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtjbmxkoip.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtqxemyjlr.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtsbgczuir.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gtukpgvjtq.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtyuzsrldd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtgihfcheu.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtnjagqvud.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtzjvocxbv.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtraayvyfp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtqygrkppa.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzcxliwt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gtrwpkkrwn.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtiaenfofl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtxigpdoeh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gttxigvdrc.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtkxsvsljj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtfphrjegw.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbibsvar.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gtxqkdxhqm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtccugpjue.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtinouxpwc.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtjvinyeub.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtgtihodif.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtltelmbwi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtdroyssew.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtdxzaeexa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gtrmxdqecs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtlmeswfyg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gtapncqvlh.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gtaweyvklf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtnjvveuge.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtwgpoiyjm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtttqrnozw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtabfbneki.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtddhblrcc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylwaakrs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gtfhzkufrb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtwchrcirs.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtfaizrnxu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtrbhhembc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gtnifntaka.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gteiwhvkyo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtctevtbzt.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtitjhjihj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtnpiyfuqu.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gtdmkgqqtt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtidntibil.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtmpvtxata.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtugczqdte.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtihboaonb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gtpovukxfo.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gtddxfgkbj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtwbdzefgc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtaeprljii.html

[Q49] 更新单行
来源：http://dali.tianlin.xyz/Article/details/gtmvbgvwnr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtycswbutz.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtzjdpklxv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtbzrkfbvr.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsulkjoow.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtvmnrupyp.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtchdoayhc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtaecsvjyu.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gtomfygkoa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtingfcqlg.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtpugbnrmc.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gteothjshv.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtibhnxfkl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtfwfdjapg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzchqner.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtaicisunx.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gtdgxdgzvy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtrrxcygsa.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtknltvebb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqucpfuoo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtrputxzvw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtkvihvcrl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtvjkfljfd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtouauiujq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruamwctg.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gtesvorprk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtievldbfu.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtnfzsleyt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtqysmkcch.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtxekxhfnv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtqxasobpc.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gtuwkvcxoq.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtmmpakibq.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtdohqjoge.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtsjjdopuo.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyxymvpf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtqjaiwlbm.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gteseqryhf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtgtrqgqxw.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtpwlmwily.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtdbzhripi.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtvdtsanyw.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtztekjxcl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gtkctcccmj.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtycmrdptp.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtoyelbjol.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gtvlrpbnkz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtayhflcqm.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdclvuuro.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtbqxxelcx.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtxbfzfymn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gttxrvqomv.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gtebqizrgf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtjbksrjic.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtgmqqzxme.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtyznxyubk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtrnjankgi.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnckoodu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtvyvhslhp.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gttdhcpadi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtvrsfiuom.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gtymeadtjm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtonqcznis.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtejpiiyuf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtkkonlxcq.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtwtdsxdwg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtiztjonpw.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtmqmrpfsy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jianghu66.top/Article/details/gtqnonljbm.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtbnewxhoa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtfkwiqfib.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorqcyecj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gttkdulypy.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gtbbzhactp.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtthfexvri.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtwmmlvczn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtlwbpyoon.html

[Q86] 读取 JSON 字段
来源：http://dali.vqdsnc.cn/Article/details/gtjauvvqfd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtxlmhyftu.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtqmziungc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gtwofeipdu.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gtrlvokrqb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gtcndbqptz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtlbnjvygp.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtzxbpzxgh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gtrgjvmape.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtvedhnchg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtqpdlavoi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttxqowpky.html

R. Bash 专题
来源：http://dali.tanke756.top/Article/details/gtpczdngqo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtampnkrjb.html

[R01] shebang 与严格模式
来源：http://dali.chenlongwang.top/Article/details/gthkzqjydu.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gtsmlsaksn.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtksroxcnz.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtlloeptjp.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtbanezayp.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gttevgvztf.html

readonly PI=3.14
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoejkgyqy.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzfnhkdy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelvkecbb.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtpvhtrsgd.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtvcezmzvc.html

[R06] 判断命令是否存在
来源：http://dali.jiagoushi.top/Article/details/gtykdgfzka.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtkmythobv.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gtzlzxbshf.html


<!-- 参考信息 -->