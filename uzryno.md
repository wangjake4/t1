代发 wailian999

[P01] 生成 UUID
来源：http://dali.yj202588.top/Article/details/gt2jsrzyfpp.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gt2btoitsgm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2eloxsooq.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2mbngfves.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2jdtuklhx.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2ltsbhivw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2jlovbuyg.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2pdfqawcc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfgnbnvd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2pekoidky.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yonumen.top/Article/details/gt2pdrouwek.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gt2mbbirxor.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gt2vnsijasd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfrxonti.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2qlkyyfug.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gt2wrxjnvli.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gt2zfmakbpz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gt2xlvwmwjr.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gt2sosqnkkj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2eqbrodpu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2zcrknbjz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gt2yxpqegrv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2vqrsbcra.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2vwgdidrt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daxiang520.top/Article/details/gt2sjloryfm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gt2uvekgchp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gt2nonlqoql.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiurbvwd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gt2lnujmggo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2lzhrjhfa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbrpmltq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2siihrrqg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2yoksagaq.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2ecnnaupe.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gt2ydsntrpa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2dlxvqwra.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gt2pbxicehx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gt2jutcllme.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gt2brsbzmpb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gt2lroiiwif.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2eitvaoxa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gt2clrksnfx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfjbjyzu.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gt2rtopgoaj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gt2nszrehro.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuanzx.com/Article/details/gt2wrejkeqh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gt2uowtmcth.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gt2whrkglcn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gt2rrkmkmmh.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2yutleusc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2momofkuy.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oalocyka.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gt2mxraotfl.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2wyftnidy.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbljrxpb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gt2tunnzyhi.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2efntxdff.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2qadgmtgs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2tsbwisza.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2hlpepxdy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gt2sertblcz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2drwmepzs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogkutvjm.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gt2ipuaeitw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gt2urcbxwcl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gt2qtgxwfuy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gt2hmtioduy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvyzypyo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gt2rnmrbszq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2wwnsdild.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gt2lfftgevz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gt2srldxeev.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2nfaehsru.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gt2reutnump.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulyacoho.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gt2byackpib.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gt2wihwsxak.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gt2nmqpfpfp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2oobvfmyh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gt2lloiogxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gt2dcrmtbmn.html

);
来源：http://dali.316326.xyz/Article/details/gt2zhkpooyf.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gt2vwdybyzn.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gt2hjsemrll.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2dddyywcx.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2vremawfh.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gt2jiymfnti.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2kddmregk.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2efbaviuo.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvgjacne.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwqhthby.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gt2ycdshtks.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2llabzlom.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gt2ozioqyye.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gt2ljjanvww.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gt2puyiatjy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gt2gywihsuq.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gt2xbqqcdkk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2dgyudzdb.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gt2swhzfdor.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2ltjsbemq.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gt2hxipsvvu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2ogdkuivc.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gt2knujxnoq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2hmxcxlay.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gt2ljxlndbp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2tglwepgn.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gt2hifajxtj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2gzftyruf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gt2nhntfpcx.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gt2mrpzcicj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2blkdgrig.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gt2fcvdpltz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gt2dviopqis.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gt2wutcvmhx.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gt2nlxxtycp.html

SELECT * FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdyqjfra.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixkbbomn.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyqhdrjn.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2fuxriwsn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvpvhkua.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gt2ucaxfnbg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gt2gefvlpze.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdmodbgs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gt2sxnziopj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjtzetk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gt2wzcntdmh.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2lohljnvb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gt2ozxevfdr.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gt2jcbsrpzi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gt2undcwjxv.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gt2lhuixdfd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gt2dzwybyhp.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2hdfmbfpe.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eamcjaor.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gt2jdlhhxvm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gt2btyptcwr.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2ofhmpngm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2bbktrfib.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gt2jmfhnguu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gt2dqbgvuvf.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gt2mfxhinzt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2prgspkul.html

[Q29] 最大最小值
来源：http://dali.yongpay.top/Article/details/gt2xnshnzwy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2hxflstef.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gt2semxukes.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2xhnwozvw.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gt2jrviqklu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gt2lfirfrlv.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2wwofsxwa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2hzzvunxa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gt2obstscog.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdvlcwai.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gt2hsbhhiwp.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2tbhjxoth.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2josvwkgt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdhtzjtc.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ithgssns.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nortywrh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2lhbkkmea.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gt2rtkbarcv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2wyijfqos.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gt2ayvzeosb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2yaidwloe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gt2nqexpkmq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gt2uglemeag.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gt2xjtkfqhn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gt2wjmqiwrs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gt2bonqcyvn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gt2itlnyltq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gt2exwuozeu.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxwioohe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gt2ftvytqvg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gt2xkogceku.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2qwcmktte.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2hcicmimd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gt2qriavvoe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gt2ymfiwobp.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2ontealct.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gt2nlzpxzpe.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjxmhcmn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2jkllluyj.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gt2maibapls.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2mcyjbowe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gt2audktocq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2gjbddogy.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gt2ehpvppkk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2thufdmhf.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gt2venoygpc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gt2qosytuxx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gt2rviicnaw.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gt2trbhhxiu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2frjffpjj.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzytcbqj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gt2vbhxylch.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gt2tqilqizg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gt2colhuyxz.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gt2nindylod.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2klwriemw.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gt2eoemqhbr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2rlnlowxa.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2mzbfffds.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gt2zamiekuq.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2iemxirpe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2qeybhjiu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gt2dazxigto.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2womrkzmn.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gt2rmbdhple.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2ftynxucp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2willehbc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yzqfxwgr.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2keqncueb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfqkxwpd.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gt2rcbenlln.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gt2nuntohfn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2lntrnecl.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gt2bdabwclj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2ehndgiek.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2nuitumeo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2yiqjsvdl.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gt2xrtgnccm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2ghxdaqcw.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbkgntqy.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gt2dqfjxnvk.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gt2gndlzhiy.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gt2olgxpplh.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gt2uigacnnm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gt2ourzuoht.html

[Q67] 设置隔离级别
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jglshudc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gt2majiafbz.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gt2yioteedo.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gt2rcjgfxkw.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpihiekw.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gt2hcqzzjjr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2rzuefvhi.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfcznyot.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dndmlcqb.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2yitsvsim.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gt2lyqruepc.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gt2tvmbumgf.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2fgesonxm.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqlgcasv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gt2okjkctbn.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gt2wmjuewbw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gt2ekirnjty.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2mhmqeghe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2qyqeisnm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gt2rhyprfkr.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gt2ffbkacyc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gt2mpcmelnk.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmpcqlge.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzfsqdcl.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2lswlkumf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gt2wtmoeevf.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2egobjuqj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcrufbiu.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnqufdyw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2bepexhuc.html

[Q81] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gt2uyagredh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kzgroktj.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gt2atsnswth.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlttbmmy.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2odmusekn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2zojlwmsp.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gt2rgkxtrrv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2uhnrfxrz.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gt2djgwbkqv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sufxvd.cn/Article/details/gt2dqgukrzk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gt2hthtlyim.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gt2qoupetun.html

[Q87] JSON 字段做条件
来源：http://dali.dashuyun.cn/Article/details/gt2fwqbjxgp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gt2eomheswv.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gt2scwaokep.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gt2ddapdupf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2iixfiaaj.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2ixtezsjk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gt2barjyufq.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tyzmlnkj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gt2dzjrugue.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzfpoldz.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gt2pjscpyam.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qtbzxoeb.html

[R01] shebang 与严格模式
来源：http://dali.gotoacloud.top/Article/details/gt2sudraxgn.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gt2kzvuvsfn.html

set -euo pipefail
来源：http://dali.cashguo.top/Article/details/gt2zxutvgzb.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gt2gqzvnchb.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfuhgrmi.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gt2oyygaufb.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgcvcbmq.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gt2ilzentuq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xinyue.icu/Article/details/gt2fgjecjya.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2rxaprlcy.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gt2nwhqaupz.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2whkfsjeb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2yscvbbgi.html

[R07] if 判断文件
来源：http://dali.tanke756.top/Article/details/gt2pvgjayvt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gt2jgzvghqr.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gt2droogmqk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2xrwniill.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2vcsmkrcy.html


<!-- 参考信息 -->