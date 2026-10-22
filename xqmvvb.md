代发 wailian999

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gt2rhxobvdc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2whehdsct.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjgzwdvm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bjhoglep.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2hmfhklyd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wepcovzv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2hkxdwrsh.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2zpawcjsw.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2woqluuww.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gt2argaqbwq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2bckuordt.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gt2kphokvwt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gt2beobonwn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gt2ivyjjbpz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gt2htotewis.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gt2tgirmiau.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gt2ihpdfdwb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gt2guziagdq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2serjynkp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gt2qjymhhgc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gt2audmlpcp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gt2aliwlarx.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2memidjfp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gt2nvmjkzmy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gt2dtfnqppx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gt2rroxjcmb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gt2wjghbmor.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gt2swdvmevq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gt2ossibymu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwtbkxuk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2slstvbjt.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2sqadhpkt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gt2umupmahd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2rjaamhoh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2hxzkgzae.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gt2auzeooqr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2hwgcoprl.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gt2ivoasclr.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gt2zqxxlpln.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2waesfkjz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gt2bltjbzzc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gt2ixdgtdqm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gt2xgmgaerz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gt2cryuezsy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2cuudsdrf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gt2jxpdfhqv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gt2gzomfpak.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gt2zcqjnzuv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gt2djpwlxpu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwzlixzd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gonprsje.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ueabeoya.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gt2sblkqmmg.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ubxdajcw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vefnfuaa.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gt2lbbuxhrz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gt2npknrlto.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2twwmokfs.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbuasdxt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gt2qvzqfvoz.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gt2ipgdsybj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2ygmupxef.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2hjohyryr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gt2ajjohtph.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gt2pupvyaii.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gt2rmlvyazk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gt2dvbhfunz.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gt2koffwzwq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2qdlcvgjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwmubiww.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gt2nvbsaryt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gt2jjmdoqdg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2jshgygja.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gt2mnpbokwi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxopfmom.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2tzghaddw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rqyserrn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gt2skjvdfyv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zevxbppz.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gt2kpqqings.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gt2knwogibs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2iwgnifyn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuerpyi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gt2dyihpicd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gt2dxtvqwjp.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2xbeikqdu.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gt2kflrxooe.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gt2jnnpsaim.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gt2cqoqmtxz.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2mwtparzi.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhywyemz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gt2zpjtosgb.html

);
来源：http://dali.jqgufenzy.top/Article/details/gt2succbrch.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrcztrbx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gt2ofbyeezk.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2ofglptjj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2qidebpuy.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gt2zecymtzv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gt2fstijqoi.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gt2cokshvdn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gt2lfxnazxk.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gt2anidvyzl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gt2jvxrvuqy.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gt2hfytayoa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2jbriwaxr.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gt2dflvzesb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gt2vhetyysy.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gt2yqpyoyze.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2reaoydus.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gt2erpqtwiu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2jirzgbzg.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gt2cekwptbz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gt2xvkkcxvr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gt2blzbezcd.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gt2mprmriry.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2nvpvmcbg.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2dtvypoqz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2fjquhnwh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2pozzrvor.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2ygnenxrk.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2npvfrpcn.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gt2qbangrxi.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gt2nnefzseb.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2dsxuugiq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mggvnvag.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gt2knooegzz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gt2loqfvyua.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gt2srobzsaj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajkkxjkh.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozrtjvaa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdjbmnvw.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2avgtxckb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gt2imrntftv.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gt2dcgtdcjg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2dfumvvkj.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gt2pnefayti.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gt2phfmwvjw.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2acqtygcm.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2gdrgarxx.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gt2egrhiblz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwzbkqyf.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gt2ggqtfedu.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2lvdynhyr.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gt2spffgcnn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2fugkuqte.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwxgdjca.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2ezkvkqvn.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2ylaullfx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2megcorzz.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gt2wgtejygb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2jbzkmdvj.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gt2cvabcemk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2ehzivkop.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2zrxiottu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2ldwyqeei.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gt2ajqnvgeq.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gt2ebvrvdzw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gt2dtxeftve.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzjvehrn.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gt2tdwvjwis.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gt2aaaqaxmw.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2knpykmwf.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gt2kelcltwi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gt2mnqhfigz.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gt2mjuujjml.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2gxnqyofp.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gt2kbfcujpe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gt2ylemlylo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gt2wfexqkou.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gt2hcvnfjxf.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gt2qcyoagaf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2sgwpooct.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gt2avfanutm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gt2tdhdlguy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gt2cdupyojl.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2hvjulbsr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2pkskpitd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdqejpov.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gt2rgrsrlno.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gt2zltaawfe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gt2aojrexsb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gnfhusrh.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2fwkqrkrl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gt2yhofjpru.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2nqgbtpso.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gt2zijswmss.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gt2pusqgest.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2runbpwrn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gt2vxyhiwfa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2woatkfhi.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gt2azupltum.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gt2vqtuzfbx.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gt2lsxfryox.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gt2zmblunyd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gt2rjmcakjj.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gt2rgwnuwbf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2vbfbbuyj.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gt2vzpslfdv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2xmmwcasb.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gt2vjjtnrxw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rianlrch.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzomqzxc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2cjmzieav.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfnlqapn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2xklnbyui.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gt2hnbwrtgk.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2zdehdecp.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gt2uvlbpekr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2xqlbcnyp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gt2plelhpqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dozuahix.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymoljttk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2xjrhajim.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gt2zzgmwqhz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2altedhul.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gt2fcitikoa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2rrghlpga.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2jdsncett.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gt2ekxweqao.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2selvhrom.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gt2duhblekk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2hlxilyzc.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gt2exjcbfsv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rctcikds.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gt2quwbxarl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gt2zsdzmbyy.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gt2ovtwhhwb.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gt2bszxrifm.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gt2emscsija.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gt2slqzlngk.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gt2yunfpalh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gt2wmoonueu.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gt2ucqiuqii.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gt2xbezndef.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjmndtru.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gt2cscpbvcs.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fynhejsw.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gt2kkpvdwyw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2qwendnxy.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gt2ohwidsee.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2fcfepjrz.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilsjaaud.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gt2bbjkudxa.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gt2utnnobqf.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2nmmyjrtn.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gt2dnidbtzh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gt2wqcnmozt.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gt2ybbrbcfu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gt2fqqnvukd.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2pychnrzn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2qfdesxno.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gt2dvyatewv.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gt2ylazsppg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gt2tnagpqcu.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siuwruvc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2azsdlvqv.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2kxbjuypo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gt2aawsbdre.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2oqiyxjnr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gt2wnacywxa.html

[Q80] 字符串截取
来源：http://dali.yueranfly.top/Article/details/gt2gqphpppv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2vvduwahj.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmcprwfv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2tgahwzxr.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gt2nztrbrap.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2yvuitcwx.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2luvlvtxe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2yfnaqodv.html

[Q84] 去除首尾空格
来源：http://dali.havefunace.top/Article/details/gt2dapynhzz.html

SELECT TRIM(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2lpphmjyt.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2lpacguhn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.c1oappe.top/Article/details/gt2ofummdoa.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gt2opqsylcv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gt2mgrwbtpx.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gt2qvxxujgl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xuetiantiany.cn/Article/details/gt2raldnqsr.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gt2trtnatlv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gt2coaqyfbz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2kdlqdled.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybsejhyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tian-w.cn/Article/details/gt2wqkxltyj.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2takjjzeh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gt2hxsvpgyj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2eqklxtrq.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlxbrqbh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2agaajoac.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gt2sbrkmtch.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gt2mxtksdco.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gt2rbcdrkqr.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgosswmj.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gt2xnhmjxwf.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gt2mjwswryz.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gt2gifwkkfi.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gt2dspnyqvx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gt2ghmouupu.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2igdrvxtp.html

name="${1:-default}"
来源：http://dali.yvedp.cn/Article/details/gt2oebjmiln.html

[R06] 判断命令是否存在
来源：http://dali.pycfn.com/Article/details/gt2vzasltkd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gt2jnosrtna.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gt2pncjxrxb.html


<!-- 参考信息 -->