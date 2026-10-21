代发 wailian999

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtbtczglbv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsgklczgo.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtrnabnroj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnujktyyd.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtgvlhsiid.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzlcmldh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gthqfnxtsp.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtqhagbvca.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtbyagjbdu.html

Java: UUID.randomUUID().toString()
来源：http://dali.hysaishi.cn/Article/details/gtkgxfjaze.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gteejhzgac.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gtlwfzdqkd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gtzsnplwmt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtmrykjkac.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtqktzqjjd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtweuofuvr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yvedp.cn/Article/details/gtxotxtoqa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtcuynphvw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtndibucuq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gtmdrnqpjx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtiveyereq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtujwipwou.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtahdtrvfy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtiqgdaclc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gtcaxlsovz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtkshojhvb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoovsjdz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtmgzthcpk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtvwtfgqqe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtjoottdnk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtbxaquvbo.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtgwbypghj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqndoggb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gttaatztfx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtxmdqrkwh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtxvnokpbb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtwshjdoqk.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtzzpujdoh.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtujoelzdd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtlrdmqdlc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtkimyeoca.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gtnyigzaau.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtxwkikhjj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtyrstjxdc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtpdzzocfd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gtpffjgakx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtwvwugumy.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtbkkcvdqp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtvxehlmnd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkuqnkxb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwxlhjig.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtnzxiahzk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gtqhkueega.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtamlohxpy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpevvnbsl.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gthlbhxnpj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtiqoesptm.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtmjzfmvzt.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohtsjkei.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtukudndez.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gtyhrmzicl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqqaouyf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gteuafncit.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtdccgmylq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtnuahxksd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtlwiowiit.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtykwaoetf.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtpwyxnpgg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtafwoiqit.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtniouiekq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtuhxmzobz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqhuonew.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtjldwrtld.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtcespatyt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtkmxdjgrx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtelclzfyf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkyaozqpj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gtpuosbmfu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmgzubsqt.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtxwysgtkw.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtlvpeaesc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtbmjdcmum.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtpzgkzefp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gtbvitnrsg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtbsbbaoaw.html

);
来源：http://dali.nwbrower.top/Article/details/gtvphhnvrn.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gthmfcccvw.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtgzurfsoo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtyvgvwlls.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtetnwsohb.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtadgvobak.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtjwecnqpn.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtftkucmho.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gtclmptfla.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtzshiwkzh.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqivpxoys.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtvnslllis.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtfycqdclq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtjiqukybb.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtpjoriyve.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gttgrrgork.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtvckbzcsh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthkwyfmc.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtpjjtzxly.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtiiggiuzw.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtgyxpsqtl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtafcohgul.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gtymeeecfy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtuhgvoyie.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtvoojgsuw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtsmedawtq.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gtmzxddxsp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtdypegqgv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzvujlbz.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gtqqimemyv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtwrpufgyi.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtdurwqqhz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gtgfquvxga.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtpgunckot.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtfpwfaghb.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtftlwyviv.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtxwvjyvij.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqphiupy.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtlfjfvgmy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtgeyomlqx.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtlksincog.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtqcphrjzm.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtpubdtjik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtbljdxfvz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gtzvemncxr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtzcthmnmu.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtdvljfhop.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtenrpsqef.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gtgadgnjvv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtofsjhbaa.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtllhqhujh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gthofhixzk.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gtxzcrrgxu.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtzydjjxqp.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtzbjskclp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtmgusbxdf.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gthzblpwzw.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gthugecgpu.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtbrpbmeoq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtddmnyqvj.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtbfrgfxwr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gttdmasnmn.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtcysxugxq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdesgxri.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtwfukizaf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtjcsvzejk.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtznhtotxd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gtrhnkolrs.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtskwsrlnm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtlbfcysni.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gtstjbjwhp.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gtzdpmiiwu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gttyhvlara.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtsgkhgndm.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtvvyauvro.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gtthzqtxnh.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gteytlwmfu.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtgbalfiwh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtkqggsdur.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtdsvdndqt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtuopoxsjn.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtxxnuyygq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtimjjgdba.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtozvqpomc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtwllbmklt.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtbacpxkex.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtfebigbsy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtaxsjsnpx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtgfdmfxqa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtvtoymklr.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gtxnmohdwq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtbzuiitwe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtmvmjwoch.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gtnbloyddq.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtfxozoviy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gthqxpqinj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gttxremrkr.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtlmvinebm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtpmqlpoax.html

[Q44] IN 子查询
来源：http://dali.cdnleiting.top/Article/details/gtzniwdnmg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtlduckrrl.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gtcearzlsu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gthpmjtqwd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtwlbctshe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtwuvlhwog.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gtmmpocfmc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtcjfkwpdd.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtoykigpuv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gtshdkniwj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gtmduyabci.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtdjilmyvv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtgttfimtt.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gthjsaptpe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtuwpjvpsq.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtmbgtmyuh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gttjihgmsq.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtauvytpcy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtbatsusnl.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtbatxgwxp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gtpownwpbc.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gtmnkdvbgd.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtzjakhofv.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtytnukcso.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtxbvvnvjc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtaxzbrydv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtttywbchw.html

[Q57] 行号
来源：http://dali.cheryme.top/Article/details/gthmmbxxoj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtmsfgxfji.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gtbpmbyboa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtwhsbjtdz.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtlelcxlbg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtalmaugog.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtxngntnvy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtjizcilng.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtqwbzofbi.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtnmpvegiq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtjxcfnraz.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtjholumnw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtnbcocbjr.html

[Q63] 开启事务
来源：http://dali.sufxvd.cn/Article/details/gtfbtpwepg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtdvgznuvc.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gterrqwsro.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gtyvdvhnvc.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtlgkfeklm.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtbdhpnaek.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtarcmtmpb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkqphrix.html

[Q67] 设置隔离级别
来源：http://dali.ydzc1.top/Article/details/gtnhgqcacs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtdaioeivp.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gthdabtnrw.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gttnulgshy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtvlkwcsdo.html

[Q69] 查看执行计划
来源：http://dali.hammf.cn/Article/details/gtloqnqiha.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gttosqyrme.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtsjsawgfa.html

ANALYZE TABLE users;
来源：http://dali.feifeiyinyue.top/Article/details/gtiiygslwq.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtbqfdgyep.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtojebuqdp.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtjggwqktl.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtirmhawpi.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtfwbamlid.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbumqjefn.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtlcfsazss.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtimftqjho.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtrarvnyjm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtzdvfymon.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gttgkplhhv.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtvwlckudd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtvrjcfmzh.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gticpndvnj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gtkrvkzwzo.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtwqocxqcn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcubtgttj.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtyqikovau.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtmgvxtrrr.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtfmhisddw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtgehcrtyz.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtjtixijwt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtbczepctg.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtyujeyycj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtxskwywao.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtimbrdmyv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtzxutizkr.html

[Q84] 去除首尾空格
来源：http://dali.aizwys.cn/Article/details/gtyprurqjr.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtatmyzhva.html

[Q85] 数值取整
来源：http://dali.shangyingyoupin.top/Article/details/gtcfwihiiq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtmvebngok.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtkpevliib.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.snrcjt.cn/Article/details/gthhjfnsix.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtlntgcdaz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtlsffzkhb.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjquejpy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gtcfnumeef.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.meibo888.top/Article/details/gtgpzaogit.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtgxapezqs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gtwkdegwcr.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtlkcbqzhf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gtdiiavmea.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrubvvkjz.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gthpnwbicl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtytsqbojq.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtlobebkpi.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtjstamrlv.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtfiqddtwi.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtgpysrmxu.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtjthpzuct.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtpzlpkpzq.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtdeaexjvo.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtrprjufkj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtanaqephx.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtzcmjzkgr.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gttgwunjbb.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gtvoyythsm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtvtbcqksv.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtgkfmqitg.html


<!-- 参考信息 -->