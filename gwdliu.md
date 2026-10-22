代发 wailian999

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gt2fookuhkf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2zjbmtbxw.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gt2lysdqppj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wfzyudah.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykirbnut.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2ocwwpprw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2puavmeoz.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqyiyebq.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2nsjjymzb.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2macifvfz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gt2gholoxde.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwvpsdcf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clwyprqt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfimggab.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2nwwruxng.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gt2rxeadlcm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gt2efveofxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2tmlfgual.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2twcsvujg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gt2giydbgmz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gt2goadcxez.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gt2ogxsybrc.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gt2rbaxdpcl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gt2deueldeg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrvehzwz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gt2kbvxtaiw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2cjyrtvwu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gt2dbejbfkz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2cnebunxd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wugaaxqt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gt2fhycumvy.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gt2vgwdyype.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gt2melkkyyt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2whehqpyf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2yoygdzdu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggyaryhv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clbdrkmc.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gt2pfhwcqfe.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxaezuxa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2vzpxjduf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2klretoto.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gt2cchmvcwn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gt2kskxkddj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gt2ntisahhu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gt2fbiwihvm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gt2epwagcaa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gt2lymbqjgh.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gt2jbviqghq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gt2kgsfufxr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gt2ejnizhnv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gt2xsmxugpn.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wxbiqwmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gt2pgtijmbr.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gt2igumwqan.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2srgshdrg.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gt2mkbxxrph.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gt2asefuzrx.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2xttzopbb.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gt2sxgdgjae.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gt2vxcmwzep.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocacjhyn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2zlykjoqp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2wdaretvr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gt2hsjlajsw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2elolytvg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gt2hdjoosix.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gt2dlujsdye.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gt2huuneoch.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gt2fllfbuui.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gt2sztfovvt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gt2xagfhiyo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2tzjiksxt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gt2rqxzdemv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gt2uqavmqdn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gt2bqjbeeee.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gt2xgzidmxx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2tkfagumh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2awrzemmy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gbeiqqiu.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2qcctbffv.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gt2qcooxmjj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2plvavvmq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2yqeslbiy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2qraxsuvq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2tsekzsjk.html

);
来源：http://dali.birdmap.top/Article/details/gt2xgwsmusi.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gt2jyphjcdd.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gt2xlmogwqq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2bzjtiicp.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2nshnchiv.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gt2mafpgyel.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvcperug.html

);
来源：http://dali.yueranfly.top/Article/details/gt2iptahbud.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gt2vzdhqjlf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2etllectk.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gt2ayarkhli.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gt2sbvqlghj.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjrcvrlu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gt2kzhifnqc.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gt2csejdmfs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gt2plokfhcr.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gt2bqbfuysl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gt2jfozszhi.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2ntoqgfqn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2bepuindv.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gt2oakhumxo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2gkegnfnp.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gt2gqsxlphn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhltdgnr.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2squkvmvg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gt2ziyeomro.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gt2bihvvtpg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gt2zmgnjidv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gt2gynbcfuc.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2ymdtjzdr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2ahwypzjo.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gt2defdldts.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gt2pcyxgrqd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gt2khmahbrs.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gt2xwvjyotr.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2vftfrxqp.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gt2bkgkdwid.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2wzrnufqh.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnqopcye.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmovvpop.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2woprhlbs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gt2qdgwrpmp.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gt2pxjbrckt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gt2eoatapth.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gt2qncvtpsj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfftxveq.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gt2zrsfumut.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2featzpep.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2jhpcrhyv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gt2qjcaagjy.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gt2yhvxsbbi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2goyrkyie.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2tgidkkap.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2vjcpkpmm.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2dxptxtuq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gt2hhmsbqme.html

[Q26] 计数
来源：http://dali.xziqi.cn/Article/details/gt2xeiivixw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2kougyvlz.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gt2wquxnjzq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zksgcgst.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gt2dpvllmwj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2imixmtru.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gt2ldfpevti.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2xilcdhic.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gt2ihoozwqk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2ihrggpkg.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2lwuskruf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2duhdrlqv.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2tivbxlyb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2ilzyngcu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2axptsfft.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2kgzjnpdf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gt2jsyvuhds.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2hjbmqfyk.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxnslmbb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gt2xkmpjemd.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gt2ctvoxxjh.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gt2bilguqsb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2btkjcyhw.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gt2oyqjmqsh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gt2aqexkobr.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gt2eironsvb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjcfgtjk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gt2wizzziyb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gt2cdgrsfxb.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2mkamvssa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2nutrawmx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2ptqycxwv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gt2stovblsd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijolnidd.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2bqgsjmxc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gt2uhnvnnxr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2culvecza.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpaxocgk.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2kagxgohx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gt2ebgjxzlz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2rthumjhm.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gt2brsluixz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gt2ddahabfn.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2rclmosez.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2ahnlwwdj.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gt2sflqfafr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogdzhsvp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gt2hkjakokl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gt2mfqotyea.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gt2gvoueapn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwitkaaq.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gt2bzmzfsgf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gt2sckfaoyx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gt2wouyvgbp.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gt2aruvkvuy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2mqgyrtlp.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghsechdi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycvlmiqe.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gt2wkwrnkmz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gt2xrnwimwc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ontcxdao.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2btlfvymz.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqecnjmr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2cdtsjrio.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gt2gpfmfytf.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gt2jfduacsj.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gt2udwjcvim.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gt2cewnhksd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gt2fdeofbxg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2mbkvsxnf.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gt2eztzceif.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feoudlcz.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gt2iqpghttu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2klsisiyn.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gt2arpxsbfk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2uqjcmloj.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guxretzt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gt2eigntjek.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2oaxirnqb.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gt2iyacyzki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpqtpwzp.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmolbcfd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2moolrawe.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gt2rqcfseqs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gt2jlfgdcvw.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gt2ixgmzyyb.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewihqbla.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gt2oeoiyxya.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bptejsfk.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2ndbobudm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwxqtyzq.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gt2ququpinh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gt2qgnwhltl.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gt2kysrcvmu.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gt2kitbohzk.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gt2yiymqjkm.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2jjobaajb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2taqlcbol.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gt2ktywsynn.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gt2yhzpuddb.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gt2uhnrsxat.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gt2gwduennt.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gt2lqdrgjhr.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2txcgghok.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gt2zxcrgqyl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2nixagnwj.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2rhbjfnrn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yangfankeji.com/Article/details/gt2avgndcim.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2qlbuqkmn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2uknaugif.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2zfqnbbvh.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gt2lxgapqxq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2cptflaci.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gt2abymnpcy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2jshrvdim.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2irmlssjs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2ehmokupf.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2ztkeycji.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gt2uwhmxqfy.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gt2lzprobky.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2cfsjnrqx.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2wvdnrjpv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2guiblpwi.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gt2xgcbpgso.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2ludkcpip.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2bncwhzet.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2skcpyqxq.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gt2pwhxkloc.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2dhokrums.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldlmbgzp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gt2rxwxumlh.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gt2bjmdzogg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gt2fzajvfhz.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbsroogo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gt2rhmlkxpl.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gt2juwcgxdk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gt2ruiqozna.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2pzuzqvxm.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2dioskzsc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gt2suqlpbah.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gt2wuqlmfzc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gt2hezwabmu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjkxbkhp.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miwrybrq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ensianhw.html

[R01] shebang 与严格模式
来源：http://dali.meibo888.top/Article/details/gt2dqbsymtm.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gt2vasvjdyj.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gt2vecvppgn.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gt2rwmdiacs.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gt2fbizzcyy.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2kevbixhy.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2eudtqebu.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gt2ffljimvt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gt2ofxpjfbp.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gt2awbdncwf.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gt2hfxlbazg.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2jatpgdje.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2ssxevmmp.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gt2dpfitfkv.html


<!-- 参考信息 -->