代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtxuxjalsl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtgyiylvrq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtmvesbhtt.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gtqzkcbwku.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtvoszgkhs.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuoygxizr.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtjzguqmcn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpxqwksqw.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywxbsxmh.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtftgzovma.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtmrdigaix.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtbvfnszem.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtvuuixdip.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtuubabaxd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtlsydbniw.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gttqiyjluj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvtxfsal.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtjbrneypj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtehcamzad.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gteyondufn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtqaysfeyu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gtgbhgeiod.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtnhhetfep.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtnjwhqkci.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aibaodan.cn/Article/details/gtiawsyxxt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtuqkatich.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtexpmqfca.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtpmnbcjsh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtdqupqzow.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtvtpolaxr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtztlzsstr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gtsqavvmsd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxaxeqcv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtrpgvicxh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gthrowlohu.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtpdjwdiml.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtxipzryio.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtzzvrbhhc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtapxtkqzy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtccesjopu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtbjzkpilg.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtlgpdczxv.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gtnrcdgies.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtwpypbuxj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtqsafahcd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxuanxn.top/Article/details/gtjrvconjt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gtmlnmlcso.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gteezkksoy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtlngodezx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gtabqbdnsy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtuxersldh.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gtlwdyggpt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtaksqcekm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtvqejhkif.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtxmaqowzq.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtgjtbrbat.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtriapoohl.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbyuhnug.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gtehtmntku.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtmbwtscrj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtspeisvfs.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtnholvfpv.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gthpqhoost.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtrvrxwniz.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtoucbspxg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtiiunobzb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzervkiei.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtlbunehjx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gtpbkzqrum.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtpdhjmgyw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gtdzwmgigr.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtquoscfzt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtppeatbfz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtmtbayexs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gtmermxfqc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gttxszflbn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtjcsrggyn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gtveufhbnu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtaqlalxcj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtcuejgkdw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgdnifpxx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtygnagxwf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxvnogcee.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtxobknlaw.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtsvxmyxrs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gteuvpsgqf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxesamft.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtqbpxdeyj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtjjrvytng.html

);
来源：http://dali.nwbrower.top/Article/details/gtiedmdokw.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gttmxwmkhi.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gtaedmrrnr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtqpbruucc.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtiiwncvwk.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtnzkyclup.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtwjiworad.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtgbfoqrmc.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtsipzvdsm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtrbdtihbl.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtqnzwuikk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtaagxrdci.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtkfwkiiaf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gtrpcyahnx.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtnwtmbhvy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtsaxmzlfj.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtpdwgjatn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gtnozghnyp.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gtwgrnyboh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtcmfhkntu.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtbxauejpc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtfcyswjab.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegfqexqg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtsxphypvg.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtngxarfvk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtnuyxihue.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtkxxdphdz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtrnhmphhq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtmfrpxiir.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtzsztpzvg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtudfvsaad.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyghiiau.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtfqnylafz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvhspnkp.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtdswcgybf.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtaxtaojoi.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtsylynwqp.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gttqkmnwia.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtphimfves.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtfcpjecjl.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtxzacrbnf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgretkhsf.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gthyxvbcew.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtcjbzhdwh.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtdtivzzqa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtzzlhyfza.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtfczeoyfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtygrbvzqs.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcfferjx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtjzjysxph.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gtkpemgrey.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gtbpraimkp.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gttfoaccvc.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfnvslnke.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtsqsbsjyd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtddiagfbm.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtgkzkfvtg.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtjhhuikov.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtlqgbwjwc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtywlytyha.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gttytyrufe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtjovnfyzv.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtqukpmcby.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtttkezwtj.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gthlzcqama.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtdmfoncqt.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtpeeslhki.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gtnfxndtim.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtnembijqw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtwpvtdhau.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gtqsuzcnry.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtpwvqbced.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtvkhtmcvl.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gtrscvoteh.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gticfejrez.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtggcetpil.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gtzggjhvju.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtgmihsfoz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtccalzsbw.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtmpmxmigp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtenrjtegq.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtsrqwusqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gttiiacksc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtblthdskm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtnyrkaoiu.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gtmdhyxnjr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtbonvobsf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cheryme.top/Article/details/gtwpxijurd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtqpzxyxca.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtvdujrnds.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtcmbnswgf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtpvvotnuz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtlayjmnbf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmorgjexd.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtfofxyyrt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtrficgyww.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtfcjhvmng.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gttseuhwss.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gtdrxmeeto.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtaetqirdt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtrdhbbbfl.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtzgvzcrgn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtyxiwazhw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gtpsmuvgmh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtmdedmlwh.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtlamwtilm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtbzlvktsh.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtlatlkbbe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gtjuxtdizn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtftebykjs.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtwrouckon.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtoovqlsko.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gtudagobeq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtykhjdflq.html

[Q51] 用子查询更新
来源：http://dali.guowangkeji.top/Article/details/gtbeueaoyb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.9152youxi.cn/Article/details/gtfrxmahhf.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvldtbrfc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtmilwlvig.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtqowfqcfv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtzxudyrqa.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtjuondfqv.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtvnqtco.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtqkewvash.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtetsvbmoa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtffrkbfkf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gtaewtnwmz.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtzkssrrcw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtdznbhghe.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtmxbizwtx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtcbkmptfz.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtjvrkqywe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtzkkzwmzn.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gtpcfuilsy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtpimkmkmp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtnizwzshw.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gtezofeyvg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtsqmknxng.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtehbdttdd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtcbsrgmll.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtniyhmpsk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtwbuxqoda.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtvtmvcype.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtydrmccut.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtbzhxqify.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtlgnykkek.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gteowgzwut.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtgzsobgxn.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtnhvligxu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtxnaqfnue.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gthpppyiyd.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtrsjalqwc.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtyjwongtb.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtvnllpmyj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtjecmyeek.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtqzkybjca.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtegukraww.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtscqqakpk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwrymxwp.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gtciimwcrd.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtcmpgpjan.html

[Q73] 查看表状态
来源：http://dali.guannengcc.top/Article/details/gtdayamzmd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtpyqplhxh.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gteuouhstk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gtdfcwcjrv.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtgenmcink.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gtrjalnzbe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtqwkpdcpu.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtazohvxxg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gtbippjvlv.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtchfxyzmx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtskcmly.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtjrcloche.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ivvv.top/Article/details/gtwhykkfoy.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtpyrzxbuh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtnsmtjwfs.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtcrycxczk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtiztybagu.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtjqezdwdg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gthceffyrm.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtrykazgtx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtcethwrib.html

[Q83] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtedssnvos.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtgnjxaqgh.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtjlbhctye.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtppttfoqy.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gtjouijkwg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtjnydpnrm.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtgcveoble.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtsjjgbtbd.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtdvvszczx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtslzihbcq.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtksxmuttj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtgskypvyt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtromhnamo.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtushvprmd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtfvmzaruh.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtciuysmzg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtnkgniaez.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkswdeclx.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtkzhxdelr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtoxelvwbo.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtgptrkdgh.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtqeasnjol.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtlgydgznz.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtheliaaor.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtbgseziyy.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtihfsjmcw.html

readonly PI=3.14
来源：http://dali.hywenlv.cn/Article/details/gtujyjamct.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gtwycopcih.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtguajdrot.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gttobicmqc.html


<!-- 参考信息 -->