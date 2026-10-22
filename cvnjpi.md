代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2kyuepnno.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2dzhmeonk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gt2tcuqavlu.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gt2wtvztxbo.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqzirpwu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2pxfiydkj.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gt2ezwzqjui.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2cprxqfux.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gt2ftblajbn.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gt2ajlreaqj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gt2ijjbpbmk.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2fhegjnnh.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2kowlimds.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gt2ymnjlyaq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2monpqeiz.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gt2iphusegf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkrvdcoj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gt2puuuucii.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnzzbupo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gt2cixaxuia.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gt2lybefwpu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gt2crignzjq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2obasawzi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gt2qzphxacj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fycmbbjg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gt2wgbvaegw.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gt2sentsiry.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gt2dwudhfxd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2gsuolour.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2hifjsjch.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gt2grlpmhhn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gt2nalnhbug.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2kzkglhnl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gt2rggydrea.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gt2mfrqruaj.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gt2gsmsjxbp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2whxghsjn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2ifteqznb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2hhkyzplv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2otfjqect.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2isalaocm.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2kpzpngwp.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gt2jseifles.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihyicepv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gt2ynofsdbc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gt2pzwbhngm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuetiantiany.cn/Article/details/gt2exbuizxi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gt2kbslthfp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2ifgujjbs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gt2kqpjzvwe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2lcijmicq.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gt2fgivpgtf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfppitkh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2zpdzmiom.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gt2ozumokkd.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2jqknhrfd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gt2ohlywpus.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2cigwrfmw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2iplsinwe.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gt2meolhenw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gt2ghvbnpxh.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gt2letyaqwu.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gt2ldcafysj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gt2qhbywktw.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gt2kssiufoy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aukeymvu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2hszilipb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tian-w.cn/Article/details/gt2yddmuwyu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gt2yahbjnbq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2reycowii.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slfpwkev.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2dbgtiqum.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gt2oxqhocjr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gt2rmszfeny.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gt2mihdffij.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygfqhpvp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2zjqafxrr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2wwkeobwv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gt2aacpdujj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gt2jvnuwyjm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jnzyrpjw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2uxbjuexk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2nxoxutpa.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2naavgpjp.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gt2rqvxaxsa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2iugjevwt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2jsbbfmwt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2mzedobmq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gt2vhvxeaxr.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2mokcchyk.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gt2xulcarla.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gt2bdwefcwv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2loispika.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2khxuvujc.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gt2sevvgpji.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gt2mauzuqwa.html

);
来源：http://dali.yonumen.top/Article/details/gt2rfnjsunh.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2szyurssa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gt2icwfgkdf.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gt2fsiymaod.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gt2iqhtsoda.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gt2frtoducr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gt2jceetdyw.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2prazzvhm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gt2kswvpjex.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gt2jaaqifgi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gt2kzlusvxt.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2nbbywpmh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2ifkkerwm.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwmkbhul.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2fvavyich.html

[Q10] 插入单行
来源：http://dali.smart0.xyz/Article/details/gt2gvwbgwnk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2ourxwvrt.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2aksvqqwe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2ywyzxbnd.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gt2nvjamtuy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gt2dbdtaiya.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gt2wrhujaaz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kugxhiun.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kttawulg.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gt2abrnxutf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gt2fkfvygxj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gt2vbhnegeo.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gt2wgwiovcp.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cljjxeos.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mlojqvij.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2dupyxqkv.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gt2ecylqjyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gt2clrdupji.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gt2diwiyqnc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gt2wixkymki.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gt2wptgrmmg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqpkbfrq.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gt2xpqmfpcg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gt2pmpdmfvx.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gt2sqdbqkcl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itgrysrz.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gt2qmhtejmy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2wrsufjat.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gt2htckmabj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gt2jqsqawlc.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2gvcmdnmt.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gt2hbttuhzh.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gt2dgalgmhj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gt2wueapbhk.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2xvaltxgx.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2xzaitvta.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gt2knmnpwon.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2czmypuek.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycefdufz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2qjaualsz.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gt2mlowjcoh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2ctusjgfk.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gt2fmijnekt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2zalkgivp.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gt2jewwfjby.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gt2jijhqmhl.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2mmhcyqbw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2tkvnnnvb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gt2pmzynebb.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjanetjq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gt2sgqfyeom.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gt2wcsumizy.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gt2rrqukzlf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gt2xvoapkaa.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gt2kayefszx.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gt2yfpcpnjk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2idmemqsi.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2qhzrbunh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2awmpmcxf.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gt2uuediqch.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gt2rnfjaonl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gt2cdcisvyr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gt2vbfyaqor.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gt2npmfxcra.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gt2ydvujbbr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2worcrktz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uorkupcy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2hirbkjuh.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gt2vcjkitcm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdtjxzwf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gt2pqcxancg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gt2skmnkcik.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gt2velvyoxg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2oyozduip.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2smxkfwhy.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gt2cukmhxba.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gt2swwuxhgz.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2xqpcntls.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gt2jtwcatyg.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djsjgiti.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2goxdcoaq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gt2khxrpxze.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2piouarea.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gt2wuanziii.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gt2ppyebemm.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gt2jgxqqxye.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gt2phfcqrkt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrxyqumt.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gt2yiculihj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2smoylpwg.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gt2etbshedu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2gafmwxkc.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gt2qkmyjdhe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2tkzibjiy.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gt2inzezzgs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gt2caweubgr.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2nmvkayin.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2oouihpom.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gt2nhmffhkz.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gt2hriosath.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2vqerpymy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258.top/Article/details/gt2pcfzknko.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gt2msqtnmcz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gt2scixqrko.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkyttgdy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2uucxijmf.html

[Q58] 累计求和
来源：http://dali.hammf.cn/Article/details/gt2qtaxkgwb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2docazruo.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gt2iydfdonf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2tezkjzyk.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gt2rqvhghue.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gt2qjxtuuoe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqkiiatq.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gt2mndfaaqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgsvqyph.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gt2yozuwkub.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2crzzavtg.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gt2ufdhpqhp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gt2ghrceorf.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqjaqcjz.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gt2ojkzslsn.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gt2tzgbmrqa.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2qlfzhskw.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2gjqnngck.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uddvseui.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gt2mizrxaaj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gt2jriiuhmo.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gt2ebcmtzfj.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2fghcehhs.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2pbbknlwt.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gt2yorcglzo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gt2xoempgtn.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gt2ekrtegod.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2wrcvpetj.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbkeapjr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2lkfcxgbg.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gt2uavqwjsi.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2huqkgawj.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2zqdxkgrr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gt2odgjlsaf.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gghevose.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2nfvmfufw.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2rvhoezvz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2wssnnpzk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gt2rttwearv.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gt2uzbmobqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gt2kjinxvwv.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gt2ubzunxej.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gt2jpcwqsob.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gt2cpolaqvv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gt2igdkpejb.html

[Q79] 字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2uddzcchi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkphzufj.html

[Q80] 字符串截取
来源：http://dali.jlsjyb.cn/Article/details/gt2tngnnkoj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tvzjaghd.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiyjlohd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2pkwcxojn.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gt2tploejid.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2urawhqfo.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2jzwtnanq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gixefswg.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gt2dxxmkpbm.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2jomkyztv.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gt2ihgfitsc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2ecmubbfw.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgufenzy.top/Article/details/gt2trbcwbea.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gt2wajzvuta.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2tuojnhjs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gt2yuztnhzq.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpgokmuo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gt2vsmaypue.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2meshcghe.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gt2veffxebf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gt2wnrhbcwi.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilakvkyk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gt2qkmxnchw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2eluaxspc.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gt2ylevqrex.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2njgqachh.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gt2ryaxdlvy.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gt2qkoowqcs.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2cmcaamwx.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gt2qrorjblm.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2jkmlwxbt.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gt2gelminxk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbqugcz.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gt2ovfcncuw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2jzsmhujp.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gt2krajncpd.html


<!-- 参考信息 -->