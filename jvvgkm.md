代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtblotoijy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtufmdqyux.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtehlhzxpy.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtgxgrxmtj.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gturdwuhih.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfoqfmehs.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmagrseby.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtedojopvm.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtcombcffc.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtmjpjjwkr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtintxzqcd.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtblgkdnhg.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtmkyavlpv.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtcghijxlc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtfpggbrga.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gthkzfbbiq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gteynmzafe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtxxjdatcn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtqrnilbbi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gtvptktwjs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtqorcolrx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtokjraejf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtzdzqvazn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gttyrnyoft.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtezwboxmj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gtisasmeof.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtoytfbpee.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtkydrtfpv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtsvbuydvn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtwiniyvon.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gthjcybmnc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtslwhtzwm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtsqqpbnhs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtxdzcsjaq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtbalzwani.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gtzlogptlt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtrpdqnsvf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtcxzclamc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtdyrwrenc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmutgskr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtbkevhcje.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtzmszlriy.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtbteddcct.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtcgkerqnl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtrzjvtlii.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtteoyxuov.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtvhnrnkdl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtindhmnfz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtuvttphzb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtrnsjmjsd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gtlfvpjlyj.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gthwgevqok.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtcpbajxhp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtelluvezk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gthibsqjnh.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtjrkpdmzi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtcdagqnhf.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtqcwsrwpi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtnrvwhzcv.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtublnylys.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtjknfhukx.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtuwppkxki.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gtdkycxalw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gtdldumpya.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtbqxbaabh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtkaztvliu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtzybwpumi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavonxsgn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtzgoyadxq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtaxslfixn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtjocnuwfi.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gteiukadde.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtanlkmpbu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtfhgcdtnj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gtblfvvsme.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtloktnsms.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtvrpqnpjm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrxuwrsc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gtgzirfjxe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtktjbovfo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtihnhkhyt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtzdppwagw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkwsloqya.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gtqlteodxn.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gtfotbalqq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtnbjfsbjc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtbhvhwnwn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtdrsqktjn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtnicozexo.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtvuefkwzr.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtmahekbun.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gtrtyyysrn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtdnzylglt.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtmcjeindo.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gthkmbgrdq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrlaumkl.html

);
来源：http://dali.smart0.xyz/Article/details/gtgnyyjcha.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtdbkspnka.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtpogckuwi.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtqxivwnvw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtsibbzrmi.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gtqlhxwxxx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtpkybwvdz.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtklaitiuh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtqxuexjfm.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtwzhzbdxo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtqihqusrd.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gtlpamjuva.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtjahwelef.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtjtroperg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtsbzvvzfu.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gthssxftmf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtczabseui.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtfbehzucm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtrrmnjrlr.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtcoffkwon.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtyxlccbgx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtfgzmadvz.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtuxkwgrsi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtdzyjzcwv.html

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtykmtpyfz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtbgjcxufh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shangyingyoupin.top/Article/details/gtdpctfapn.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcvpceed.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtlbxbakbl.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gtiwsfkriu.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtcvzrzdri.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gtfxqwxooh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtperohiib.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtgjtbzzly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtvtpuvtbv.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtkjgtwkrf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtichkrgyq.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtuvmanzsw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtqftikosf.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtfkhtnewe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtkmtspfel.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtgozhbsah.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtglrghcmq.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtgcvibveq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtmiydpnag.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtdjodukov.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gttyjpawmh.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gthxwexkng.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrthhoooa.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gtyrvscdpp.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtrfgmlxxh.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtsowchune.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gtaupfuugh.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtwnzuhrkk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtoqdaavgg.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gthpsqdnga.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtelzvmlju.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtzuazxmll.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtsxvxeqsd.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gtskbfepdp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtzjnpbuuk.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtvcwjpzmm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtjhlvihad.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtcbibqnof.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gtjhdrlhta.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtgjwbjwkz.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtzrengknd.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtdvxxmzta.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtzuvadwmu.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxitezgl.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtobeeshqv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmsmagqc.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gthsebjxzs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtyxfxlajs.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtazbpague.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gtttbutmag.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtchhlovcz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtzpzbocny.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtkcbptdwh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtmnunndei.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtnkqikfhk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gthhngnjpc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtjxzyqgxd.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtnytmheem.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtgwqqrrrv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gtgeaxdqpb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtulhexcuv.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtgktqzbup.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtewueruky.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtgoqkybpq.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtvizpypee.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtywwhaqun.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqxpdjcq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gtsibyzmry.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtrvdjrrkz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtylxauwjn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtrfyyxtpc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtcxbcjefz.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtijmoelse.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfacfcbq.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gthbbfpjdj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtavdoianc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtpxheumcd.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtfgthbeyc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtgyoaeejx.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtfouihssy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtkjgimwgu.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gttkkzaiyh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gteedxtlhn.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtmblooqcr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtvqqsjhxr.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtyysrczsr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtohntduqz.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtfvuumqxi.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtpbqpcbmo.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrbuyifd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcvhavyn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtmlqdkbtz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gtyyjlkyct.html

[Q57] 行号
来源：http://dali.cheryme.top/Article/details/gttusromtn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtatrntobn.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtwprzpbsn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtowmzgowp.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtewwuozph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtiijtiobk.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtxvcjonga.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtxicxrhmw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtiqzvapyu.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtlksdsoia.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtejetzkvw.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gteefeyumo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtrnebqckv.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcoyavkba.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtuxmzzhhm.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtnnvwerkl.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtilrqyana.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtyvvwleca.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbfwynos.html

[Q66] 行锁查询
来源：http://dali.yangfankeji.com/Article/details/gtwcudlqyy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtpncuhowb.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtzpxuhtwd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtdpvegikn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gtfagmgxuq.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gthwytwxpw.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtbgxjgomx.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtfmalqdjx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtjqgyfdmg.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtgztoqbat.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtgviilimr.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtqsuvivym.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gturdbylmm.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtegtlsdou.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvdhcosag.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gtmryphzsz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtpmwynweg.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtamfdfjee.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtdlcdwmuy.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtpesywuey.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtpnhotoqg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gttcbhruxm.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gttovdcwfr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcrnncyu.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gttznyemxw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtzxspdoss.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtldqghmnl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtphinkinq.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtnjcujdgo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtvoqvrhkr.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gtkusawypm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtsuuurwby.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtfmjjutcf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtbndhdtli.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gtcbdmxfac.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtfxucjtur.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtyezrgrgb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbbhtoczw.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtqldjmcyp.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gthhahasnf.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtgoaimlnz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.9152youxi.cn/Article/details/gtrqvztgip.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtdigzfnph.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gthaeikbdh.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gthjvwwrdu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtwetdgvty.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtlpemddqh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtdtnkdwzn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gtjgcxqqvt.html

[Q89] 判断表是否存在
来源：http://dali.hnqzz.top/Article/details/gtmitgeabk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gttpmxgxra.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfwdvbmi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gtuldatpbs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgepgiszw.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gturoseigg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuwugfbxd.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gtacvuncad.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtbbxpvgzw.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtewgqoiww.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gtrlcdffzd.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtzzsxnzur.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtduapqmxm.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtqyrzqntn.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtaepepkob.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtpjhmgqfk.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtfkqnzsmn.html


<!-- 参考信息 -->