代发 wailian999

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gt2ioqnsyoy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2zicitups.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gt2jsmntnyl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2sriqlsqj.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2xbxrgxbe.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gt2wvmdwrux.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdrkeez.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2wodasgrb.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2dnrpxcpi.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2akqauqga.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2myzmrwtt.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gt2qvdftwfg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gt2adbllaeu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2moscjysg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gt2ddgeepsj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2tgutfjjf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2slqcmeop.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzkivmyu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2xtrzjigd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gt2zrluiuhz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2uujonbca.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gt2xxjieiuv.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2noloemwr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2cdnlupjp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gt2aujhfpge.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2vxahakvf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2rycrkoth.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gt2slvbqpnt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2atkjdbvj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gt2ewozbgpz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gt2gyudodxt.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gt2qrarqhaa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gt2frrdmtfl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gt2usiocuyc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2mbbozgei.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2wqdlyirs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2smptteju.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gt2ysduquzi.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gt2pnplcvtp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2qbvdihlf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gt2ttsdkrir.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2ukusmycu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gt2lwkapokk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gt2banxgvbi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2vghvciar.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gt2eafdyqgu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2rtoxnhxv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kscruxeb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gt2nbfphjli.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsnzyjat.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gt2prerhrjn.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2svqfqwxx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rruwwhyh.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2tdnxuoeq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2khatlrgu.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mfubpfst.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gt2fxpgvvel.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eoyoafgu.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gt2klhxnuij.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gt2vezmkqnc.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kggqvjmq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2bdzontml.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2hurvnxcv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gt2tyrnotdr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpopsrlc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2hmjesgog.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gt2eabkyjtc.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gt2taeitnty.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gt2xiczwwsk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gt2brfizbrb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukdtdpuy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2ripmtbfp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gt2ggnlapnr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzsmmmgk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gt2rtnxhjei.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gt2kwntawdb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2cvszvzyj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gt2mehqsxic.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ahjvjoau.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gt2aqpjtvdi.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gt2qllztynp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2zmihlcfk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2qmkkuvwd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gt2oaroryoe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gt2iwnniiue.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2opioulvc.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gt2cpupxzmb.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gt2gryjcrxs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2aklcuclw.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2wwwkybjg.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2yzlfjpvi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gt2viosawil.html

);
来源：http://dali.xylfe.cn/Article/details/gt2igwsjmgl.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gt2wnnitqxf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gt2gnqffebz.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gt2kovmelfn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2tdglymha.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gt2uzwmmcoa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gt2qvyshpew.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gt2ynjlpcxf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gt2zhxvfoiu.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gt2farfduli.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gt2wkxtpmph.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gt2fkyyxjql.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2momuzcat.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gt2zedailyj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2qizookma.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gt2kocqvvmw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2tdbxnnzu.html

[Q11] 一次插入多行
来源：http://dali.nanxinkj.top/Article/details/gt2zqjwxbgf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdzrnxez.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gt2hvdaaajk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2qppgrjlq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gt2nsoojmpm.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gt2grjyumwh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2ynpqwmmg.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gt2lvurbosv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gt2cshjshor.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gt2edmbhxwt.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gt2iixhqdvr.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2lzhcpntz.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gt2fdepmqjk.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2wdbcjtxb.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gt2uoaeporf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gt2gxygkdxj.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gt2yowudpkk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gt2mkovvngx.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyrnmwnb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gt2odaezmah.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gt2exjcigkc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gt2ftmddjyd.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gt2xxrgdmsn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gt2zksjdqav.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gt2rlukjkqc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gt2eavdrqtd.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gt2tffyrvap.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2ttteehjw.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gt2bywnhaip.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2miwmnhrz.html

[Q25] 只取前 N 条
来源：http://dali.zhengqikj.top/Article/details/gt2pwdiubsy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gt2anwipokk.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2mibffhno.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2lccrrzih.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gt2cglpmtho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2gaovbvab.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gt2vrzbaygr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2pgvmiilt.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2izulfyah.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2efnsieud.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gt2fjnzrdbr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2fzzntpms.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gt2kkfbhdzu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gt2pzvikjls.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2qzwektnn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2oobqatyg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gt2jsgqrrtd.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gt2ftadidgh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2xtanucaw.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gt2txohmbus.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gt2ptflxrbv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2ozhwuwxk.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2yrvngpso.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gt2ialuyvcm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2vhkcegeo.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipeqvfrt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apdsebhy.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gt2vgpzmeqn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gt2psbutqwr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2appgeycb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gt2ekvamuop.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gt2lbevffqv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gt2kgxfurhz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gt2xdcqrzev.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gt2tcdbrdcq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gt2qmcjrgqb.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gt2vupfkqhw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gt2uoybnycg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gt2xrljvurw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gt2dxujzwji.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2oksvyuej.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gt2ypcjlbpi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2utlmtsaw.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gt2mypluxqx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2gemludfp.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gt2iockxgis.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gt2tvtombaj.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eoozqglp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2lbyblani.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whrxrtre.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2izpzwfys.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gt2jjlxgots.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gt2mhqealtr.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gt2lfmsdvvr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2euuilrtp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gt2lswiwqix.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gt2etcmeqef.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2mnslgrwb.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gt2xbgkqjwv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2hvtdhbsw.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gt2jngsedhv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gt2cxhlsutr.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2xcveycft.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gt2hcscizmq.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gt2ccrwnpai.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2zrqrebrl.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gt2nodhjrfp.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gt2lzgognht.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2vuwvetxe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gt2ioahbkpq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gt2drcutzew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ydzc1.top/Article/details/gt2ddqkdxti.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gt2ealzepqa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2sputvdjt.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gt2vigjfhji.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2ensghjmn.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gt2uidumvrj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2jikcarks.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gt2dvujuuox.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gt2zjbemgkq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2obrgqeao.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gt2wrunzwbv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2nuxlcdhg.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gt2gdmrteih.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2uhadupbe.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2qtjstqgm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gt2zqwkswxc.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gt2tehycjwz.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gt2pgedwijg.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2bcgtslmn.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gt2sptpyhem.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovcfkndb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gt2tpriytvb.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gt2xirkmtel.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gt2gwytezxy.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gt2pyxsakdt.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2orvniozl.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2raftoikk.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gt2ggqtxjdz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2hgrpgyqq.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gt2mhsqjaaz.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gt2wlndeboa.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gt2gfxfmajq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gt2gpxhzsqh.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jdwoplfh.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewxyvylj.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gt2kcpzheuk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gt2fizqioqt.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gt2scpkgqal.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gt2mznqgbkf.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgllewkh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2bhlucbco.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gt2smwmggcl.html

[Q76] 按天统计
来源：http://dali.cucudq.cn/Article/details/gt2ttnhosug.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gt2bgkyzute.html

[Q77] 时间加减
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjxniqxu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axjnbkfd.html

[Q78] 当前时间
来源：http://dali.jiagoushi.top/Article/details/gt2izvcdyjp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gt2mqcolotk.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gt2yfjejeqd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gt2abevbouc.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gt2txjxblwu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2xtxxrony.html

[Q81] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gt2glaejtxq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2cmxtzbrz.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gt2lirizsnj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2woihrwhm.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2qdikkxpd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2dmgnnqyv.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gt2ldjiggaf.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2chdaplky.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gt2ajyjateg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gt2feualsdi.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2atfunhkq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gt2bckugshz.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gt2alaebzgl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gt2axvzzjnp.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenlongwang.top/Article/details/gt2xosozcfe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gt2yaabnmur.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2tivymywy.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gt2gsmitdmz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2ckixsgwl.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gt2ycebcmnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gt2lirljlfy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rtltdszi.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gt2juenospl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2gxbooyqi.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2uxyvvcwv.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gt2uuckturl.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljjioard.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2sarfrvvq.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gt2zangdprd.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2qypfvaux.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gt2hpvbyoqk.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gt2ecpcwllm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gt2njmukfng.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2dskagjhl.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gt2pmpkyvch.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gt2lafhekwb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2zsrknhow.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2ngadsuxc.html


<!-- 参考信息 -->