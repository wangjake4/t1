代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtkqnderfw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtmympirjk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtygtczqcs.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtjoexgmvf.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtxnvueati.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbqzpisrc.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtrbtxjykr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdowbahyv.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtlffmfpti.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gtogqcbsba.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtefgnsedr.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtmvxsllfx.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtgutdpeld.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gthgdvdlfs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtnmxfmdnn.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtvpeybulj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtugprshad.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtreazngey.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtcjafjnrh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtgqaofeqo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gtdfbxhbjy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtbwepawst.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtphlspzoq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gtztxlundf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtythhnfez.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtryqsuzok.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtrlxyotlr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gtltlxsgoe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtpjeergpt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtpxmyiblt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnloqpghk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxkhresa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gtjpprsvel.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gtpvmzynra.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyxwmqzq.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtylhpstus.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtrtacyeho.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtpwhsihld.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirvbxzaa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtwkcypkls.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gtcisxobxm.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtzbchkvat.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtnesamkac.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtulaaxzpi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtxsljtwoo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtoximaaak.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gthlsspuvb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtowabxlmu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtrdcsbeym.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtvthlixzc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtxezdxyxr.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gtopvhtftz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gtfkkietzi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtliviclay.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdqvkmmt.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtzazmlwga.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzwfnejg.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gtpukhtezg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtupxezmzw.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtnawaasbx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gteucqlzky.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtieveihto.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtgpitmfoj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gtquuofoxu.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtsmhfiqxq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtfvnudsoq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtodgombeg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gtsvunehas.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gthvpykeas.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtoanjnufw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfpuvgsa.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gtgrpaxybe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtgqfqqqbf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtcmhxvkit.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtsdsrdmug.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtxbhxmlcy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtdbgzlbco.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtpgszfnke.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtizlhknay.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtvsucgsos.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttolnvqff.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtyphbenyu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzhknjety.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gttzslmwky.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtpgmuedqq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtacblhvcz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtltsuoljc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtzvurczkv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtikbgpztb.html

);
来源：http://dali.tianlin.xyz/Article/details/gtdryxjfko.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtysdoejop.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtchuvehex.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtkoojnspr.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtcpwcojfn.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtydjnpnto.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gtyyadlorn.html

);
来源：http://dali.hammf.cn/Article/details/gtquibhscz.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtxlziegtp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtmtftnrfd.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtcfevwmcs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtzkfjcsjq.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtnbkxdoce.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtzedtdxcq.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtmubvlxho.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtaoigrdho.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtgpuovqoe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtclsiuyja.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtltaoybxx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtcfxogucq.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofhrvdqj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gthionnbpt.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtxxfhybff.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtfpzykbef.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtadgfnngz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gttrbopawi.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gttgzpaqrj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtmbfcjvqu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtxirgzksy.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtzvharyjv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gttbsqeysl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtspmcstmt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtetkkhfkn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtrhmakubx.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtkbncnbdg.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtrdiqhgul.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtpjhjwyvn.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtevwoxorh.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtmfpowxyt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttwcrxekg.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtvmpmcyuu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtldoygrtq.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtoqckyjxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gtxocqvvaq.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtfsbnjbhb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtniofwzxg.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtxwdpreiq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtdrnvzqmt.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtvtcuenuo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtmutnkhsj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtpwqjzxfu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtoozlnlnu.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtzvjihuyi.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtipjwaisv.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtqqskbnry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gtydsitzeb.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtmqqhcbpr.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtzrzujfid.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtvdcxxfiq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gtmfdsuwhe.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gtxzmgysjy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtjpghhzfi.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtxyllofgt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtnjshaqpi.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtliwfqhul.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtpwditxvd.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtgjklmdbw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtiufgatre.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtenhwohzl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtpqpjpopv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gthklsysbk.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gtbixllgef.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtltqbmeey.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gtiscpyzxj.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gtfhggersz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtpgfeqfyh.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gteotduylq.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtxclktsbz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtxfhgssii.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtvhshbgcs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtqzavkjgw.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtdvdpqegg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gtkxassyel.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gtvlepomud.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtaexadjgv.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtrbrncqog.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gtmoprceez.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtfbngnuka.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtadbebqka.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtspkomfcn.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gttogfemkf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gtgxiqfrkm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtvtiasllc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gtevggphga.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gtfclougxx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gtvcgauouv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtnsivjcza.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gttiwtzude.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmqpehyq.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gtihxyjvgp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtcyhauyon.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtbgppggru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtocfmfhoa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtqagwvqbo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gthkokqqhs.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gteubtfnnk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxmoclgc.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gttvoqgnmn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtplngpqku.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbjafdyx.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtgcdrclmm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtuubfmhfm.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtelajkpnt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtbcgslsrm.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtzmynjluw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtrqjdrjqv.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtwntpuqus.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gthdbtgyql.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtztkywdvh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtktgkappw.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtuijdaoar.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gthhdwounl.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gteseuewac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtfndexwlu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gtvxuxxupu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtdmdmkdfx.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtcohgzclp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtufxfivxd.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gtsxvovsek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtdumxczsa.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtafmkcrwh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtwhkiepgj.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtrjotueei.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtrogmusfi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtpnebuesl.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gthqnolyps.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtkgpnuegx.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gttzqcmcbn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrflgmjr.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtwiesswey.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtiehcgjny.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtvzmxgtlh.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtgfanuxaz.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtfwewilmy.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtnmrxafyu.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gtoctzpgkf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtnnguxdrl.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtktlzyhpj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtfzbqpjwl.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtidwvlirf.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gtkamssvaf.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gtkqowjdag.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtskyrskju.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sysykeji.top/Article/details/gthhhcpkel.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtyxsjcwww.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gttwsvhqhl.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gthcxoftem.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtxfiuanai.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtibtcppyf.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtixqmmuiw.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtwlzcmuza.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtxanmdljt.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlxfoyqz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gtvkawzlmx.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtcnxyxtwf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtwizomgeq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gterhxzidi.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtsiqedwvb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtvzhbojzo.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gtyezpmuff.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gttgsphhvz.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gtwcwhesyc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtiileiodq.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtclsieune.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gtncxekzjo.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gthwjztfbe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwgembqgx.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtkchytahi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gtzeqtibjk.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtsvtjnard.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtpdeaxvdm.html

[Q83] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtyycezamv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtgwremilr.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtktksvwuv.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtvvcwtuti.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtjhkomrxv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pycfn.com/Article/details/gtpmtcbdwa.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gttshnzynk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtcvzacnyb.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtymotslbz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtxoebqqmv.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gtpmahycoa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtkqwxbkvv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gtmjdhwenh.html

[Q89] 判断表是否存在
来源：http://dali.yongpay.top/Article/details/gtwszqnqif.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtvegcuuxo.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtyluuobjy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gthntiaogt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsfxebpba.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtvmskowsc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcaprstrr.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtbealhvwu.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtpheywfrg.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gtmwuthrda.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gtjyutjxok.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gticmdsxqq.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gthfdxbesz.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtamptlquk.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtjyqysxdd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gtdgctcckj.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtwffnjuaw.html


<!-- 参考信息 -->