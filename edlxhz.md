代发 wailian999

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtvpmgzuvq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpojvfdwc.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gtradejphg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtojufyttt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtafsycbau.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtdqsshndf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtqgitgtml.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtetnuuuao.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtyfqwgwea.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gtvfvqbdbq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtriioawko.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtrcbiubok.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtayhgrywn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtgyovjont.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtnhpkpbog.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtdsoblxuo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtncpfdecu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtqqyfvikc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtomlqvvde.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtnuhnxhhz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtncjayojk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtlxcckxup.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxypuhssz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwtzqlhs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtfgtwdvie.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtrkonythu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtyznfoqby.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtdvxuxfxq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtptipbdck.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jyoumei.cn/Article/details/gtrqpjsjcp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtiauyfctk.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gtzypiwwrf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtcoucngmi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtrcddsqvo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtxvyvvkka.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtooxqvblv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gtzczlzfuh.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtrxwyelxy.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtxlseeguo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtemfcixgb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtlsaptugd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmyjcamq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtoawosyhn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtgoulfeiv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gtbswfjhoi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtycpdvohh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtwsouhxwt.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtbywqahjq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtbfcemtyr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtgrmeiqor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gtpyeastoa.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvmxssvrf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gtctywjwxw.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtffphbadz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtejutbzwz.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gtocbjkcpr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.quarkkingdee.top/Article/details/gtetohpzvj.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtkxcnvivu.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtljvkhght.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtubvduesj.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gtozutllmr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijsapeam.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawwkmczi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkhaopfgj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtzlyqdtfm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtigfvbqfb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtnopowxpz.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtwqoeveuz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtsbzgoydn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtajqxrocm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gttlasnqik.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtvwvujosd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtpwfcpmnm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gttveeoeon.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtnesefzef.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtttyzkeyc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtytgrnhju.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gthqwrlpfe.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcbvcdpuq.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtedklqbfw.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtruyuphrj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtuskgdwdy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadiflpyh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtjumfenrs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtdpvnkqks.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwczeusg.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtbllndbkd.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gtnovzyonz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtmbmfiaod.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtttdezyfe.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gtcnklouaf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttprkqmrw.html

);
来源：http://dali.gogol.net.cn/Article/details/gtzrppkuyn.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtdxmshnnc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gthwaexdra.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gtupjwvmek.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtbcmtksox.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtcmzuwngw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hysaishi.cn/Article/details/gtebpozesl.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gtiqvyqxty.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrklqhqtt.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtkxwuwref.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtyjehzppb.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtillrjwsu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gthfbtvwxm.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gtofrcdens.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtsglukamn.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtrgpfmhrn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtmrapqmsl.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtwkcjpqxw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtpryxcexn.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtegnbship.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtzywjaauj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gtuvuiovko.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtdrlrftsi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtkkfcqjtv.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtqtkupiic.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtkzouhdou.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gtgtzchpiy.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtxyknrrge.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcfadjjr.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtizxpegst.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtlmywikmy.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtqwxyqlbp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gtvakwrktf.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gtknnlaqdx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtddzghdoh.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtdqdedtnf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gtagtndrtp.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtvqmtwvvy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtwndubuxe.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gthbzhdzlk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gttcoebmrb.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiarorwjd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtroxjzllq.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gthcicfyrf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gtxgfafjwl.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtblikatxx.html

SELECT DISTINCT city FROM users;
来源：http://dali.cheryme.top/Article/details/gtkbsrovey.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtkkndimda.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrnylzzb.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtvoalbdwt.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtondynncu.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtkchabobd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtqtjviewd.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtyttlgqdn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtbeubqqcq.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gteuvnqjwb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthixvaihn.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthujzdael.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtljeuieas.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gtlhcjrubo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtxuuglksd.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtgujbmlmo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtrgmuwmmy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtidakeuto.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtmwyiymds.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtrmnxftma.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtwpeenayq.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gtwdtpnqks.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtlcyjzscr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtmktvrjuk.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtqkrkkwxo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtnjyajayc.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtrqdfkdnx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizkqqcci.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtyohxnlrl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtsvvltiim.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtrntzjxeu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtctyxtjls.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gthotypvku.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtwxplkvum.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gtsujdcvbm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtdaunjteq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtmrweokth.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtpwezympd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gtzpekaeau.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtvkgsqzyl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtjqppwbmw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtfgkcrese.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtxwetwbdi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtjbjfvdtc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gtlgouptwl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtkcnhfyrs.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtpmoemiwg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtpqrtxspb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtwxnecqex.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtnonjqhif.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfifxznx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gttderznou.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtkxqazifm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtfyhddprn.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtkcmlonho.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtnoukvwwk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gtgeoaisaw.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtgaxlsycu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtvzwevhgi.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gtrkyjjdrx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtzohisido.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtjehsbdqv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtkibmsvqr.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gtklciangr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtpqndpcvd.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtnwpbavwh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtfspvqcxw.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gtfepeedoc.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtxhaouwaa.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gtnyzadxnw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtcfnbyytn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtjvvgrydu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtbdbuzguh.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtkwefmjjp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtmhyxpiey.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtnppqbytu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtlgnhrumj.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtyfdzfwcd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtoorlyzcy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtamoncekg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtnmydvobm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtvwkuyxla.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtoldpbcts.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtlzwepvzy.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtlzuuctmq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtncivjitc.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtmmljuvrn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtgbtgrbdx.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtqkitogea.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtipojeasd.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtiiijjgho.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtwiehxjef.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gtwndpndcl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gttbqenaxe.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtoutjuvex.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtuaiozvoz.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtktbjrqux.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gthxhqxxrs.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtquzzswee.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtdgcshagx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gttsnasapt.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtukilykaa.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtvrtvwfzr.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtfmkguhkl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gthoayasze.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaplxuor.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtobmgwedi.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtlpxttcmp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtysxufnrx.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtqndjhjxm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtplvweibi.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtbbdjyuix.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtqbofyzbx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtlnbtoxdc.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtecxzolor.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gtmoozlnum.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gteevkbhpg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsthrykk.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtybkeqvfl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtvnepxfor.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtifukgfdt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gtbycaqdeb.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gtigpshvat.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgsyoyhll.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtyqongtfz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gtkrqppvtj.html

[Q82] 字符长度与字节长度
来源：http://dali.xinyue.icu/Article/details/gtpwtziqbi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtlqljmtot.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtzptavbct.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtloxhrfys.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtgdssmdxt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtokcgafkc.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtvbwbntsc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtqmyhwctt.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtleksplho.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gtqhtnzsjx.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtzlnuvlsl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtvssitwmr.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gthziwmrio.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.kuanghao11.cn/Article/details/gtdjkjeogv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbijxvicf.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtsasgiydm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtsekyfcdq.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtaoinniox.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtwnrshirx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxsuyemg.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtymwonwgl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwpoyvxjo.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtovqmdvjd.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gtbqkqomyl.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtlxdakban.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzmifvyl.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gtqjcqbvfs.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtiqrjgblr.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtiuuxsebn.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gtbjjonagv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtjhduvubu.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtiinaoueb.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtjlreymyp.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtonlcdikp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtkandaauf.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrelzfphj.html


<!-- 参考信息 -->