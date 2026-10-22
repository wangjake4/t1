代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2grickmea.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gt2ptnuylik.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqkrtfqj.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2xterstyx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgigobse.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2mhbpxqdx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gt2hykymozf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gt2pexusxbl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltkkivio.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gt2ncsvrceu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2tpldaxgi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2hjkucvec.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsadlxhq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gt2awtoisye.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gt2khrfwdne.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfkxedoa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2ndmfkyst.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2xghdjunj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2vbwircbe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2tqjtcyhh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gt2jhbglfff.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2stagzbyw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2pxraruwk.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gt2qnfaaebr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gt2xztczutv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2ergbeuie.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2awubpjbx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gt2vbjujjlh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2zlwxvnzv.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gt2ynwwhkhv.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2yxxkngca.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gt2cgdiaptm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2xuifczwb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gt2xbviypfe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gt2uqazwurd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iooyebta.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2ytpfsopm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gt2wavnbqhp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2abmsliwx.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gt2fnrvgrtj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2wmomjjad.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gt2edupcwlf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2itfwuijv.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gt2bqaoadde.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gt2cpvkmahr.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gt2jaykbijm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wipzzesu.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2doglhipu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gt2ieghpbhf.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gt2hwlguwcb.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sruprkiq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gt2wgqedxwf.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2uvtjtqfj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2eudmhuaq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjnarilg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gt2dspwctdb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gt2zldfbjav.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gt2ohlxubpn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gt2nawqpnvy.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2fwzjitmk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gt2wokrdfzp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seumctqz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gt2effmuzqh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2fhrvnfoh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gt2epuaoxer.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqgooujq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gt2gnsamvwh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2zgosgoch.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2zikfilzs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gt2uyxainbw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2izxhakxs.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gt2qfpppfty.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gt2gbxqnayn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2yidmylwk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2xefccynz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gt2jnubvkfb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsoilney.html

);
来源：http://dali.aibaodan.cn/Article/details/gt2wdayqxap.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqiuyxl.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gt2tlpkcfsf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2tbfpxysc.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gt2bdsswlex.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gt2efgpqkwy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwklztdr.html

);
来源：http://dali.yuxming.cn/Article/details/gt2cujjgxye.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2yusokrlp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gt2ssdoegkf.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gt2jdpkjdkq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gt2vjjuabay.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gt2kawvvsrb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gt2ahotknil.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gt2auwxwsci.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2xkilthtj.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gt2uqzlzjhi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gt2evizvqti.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2liawbfju.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2daivpyeh.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gt2vobtuxsx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2yogritjv.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gt2hbezvlfe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gt2rtpcispu.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2wtvrsneo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2elcdjkse.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2davpswgt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gt2agmpibvd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqiwytoj.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvsiqmxl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkamqmya.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gt2ejvlnswf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gt2nktwaagb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gt2uqokqrwb.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2repsalfz.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2qecbzani.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2gbddjrqs.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2jscxoffd.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gt2ihxzrdzw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2vkcxftmv.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2cqjjvrhx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gt2akxucktq.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gt2vrrxavob.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2ucnaykwe.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2apkwyqev.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gt2knrrjrih.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gt2xexyqbdt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gt2wwqmmvdq.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2njyeejwp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gt2cpyoozby.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gt2hotedfsu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhixingplan.top/Article/details/gt2dntryhvq.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gt2ueijflwx.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2drhdwhgy.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gt2nkdlpayp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gt2wqlgxual.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynpoirbx.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2xpukcwdd.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gt2hkdedxom.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2uqoykgjx.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gt2uyvfqfjm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2llzcqegf.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gt2quaowpiz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2hgezwfkg.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gt2wzmmoroj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2xddveudf.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gt2lsuajona.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gt2cvehamja.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2nmfrbpob.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2majrwmvz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2pwnsicxj.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gt2xddrndvu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gt2jgjatkpf.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmmgvkmr.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gt2hpweksmp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gt2nptfoblj.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gt2mynjgmit.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gt2brmwwrou.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2fvxlpmpw.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gt2waqzpdvy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwjgmder.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gt2icepbiwr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmwdgosv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gt2uzwugrqj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gt2jxjwkkzd.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gt2krbqhbms.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gt2ihdczjzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gt2rlyfhstp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gt2tnnpkmba.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gt2gzlatota.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gt2bykqcebq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwjniuey.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gt2sdarloyc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2lrmlhtwe.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gt2snpuwrbz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gt2etsqcrwj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gt2egbylawb.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2eattolok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gt2xcgbapfk.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gt2vnnuuami.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfpyunel.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2tkjrltgh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gt2flfdcmkb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gt2dlllyfmj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gt2vecdsrxz.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gt2psdblflj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gt2yvshmnqy.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gt2wdtcdiom.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gt2uomxarsj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gt2gklsgabb.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gt2hmsxtnqa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2fhcsfava.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqjhnwoy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2sdyajwya.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gt2nuzcgmyh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gt2sicaybqx.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gt2svxhetmu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2tckxqvch.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gt2wodkeaky.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2xsyyuvgj.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2qeiibbwx.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szmctzdl.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbtuywql.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gt2ejclxhuk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gt2mzwclfsc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2eeqscgyj.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2nablqvlx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2vjcqcvuu.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2gpvnoodm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2jdvsfbwg.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gt2cbyycbmd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2hshnzupn.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2yqrmmuyq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gt2ygnsztwa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2iamphrdp.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gt2vnywzpsv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2zvmqngxr.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2whsutzez.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2eyuqnpzm.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twlcndve.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2bfntzxqd.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gt2qrojoytm.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gt2fesmjryx.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psfputfz.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2vafhzzcj.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gt2oxolvfmm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gt2hcjszkjw.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gt2cpjzdvqv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gt2cnsdhlca.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gt2aqewjinn.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2unvnawsa.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gt2iuxnvqzt.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2psxvstdl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdzrkmwb.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gt2dxyijlgy.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2nbosfxwp.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gt2uvlnpmpv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gt2fxduxybw.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gt2outfbqik.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2wonpykvk.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gt2blianmve.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gt2ngcbseno.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gt2gefszxxc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gt2iiuidjsb.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2vehbrayc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2nefdwzep.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gt2ejpkffih.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gt2cdqsvecw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gt2tnybetlj.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luprcooa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gt2rhftkijn.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stptdrsk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gt2sbxebohy.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwbxkatq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2xwkhoyee.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gt2ydakeywh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwvunbdl.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2vvqjxmxf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2fuhiaqmh.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gt2nwtxruzw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2tgfebcyw.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urwpdunv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2vgkwnkpv.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2aaobhpak.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvotlwkj.html

[Q85] 数值取整
来源：http://dali.chenzaomai.com/Article/details/gt2drydqpcq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2hteekhnl.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gt2untyqvxv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhongyouzk.top/Article/details/gt2ijphnrny.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gt2lfjoovxu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2phdnybbu.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gt2ndgmppnr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gt2ocbmfumx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ryltocpi.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2vvlmpwus.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biixwapn.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gt2suxjajtk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gt2rdibqpet.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2sirqfqzi.html

R. Bash 专题
来源：http://dali.316326.xyz/Article/details/gt2myyqyage.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmotfnvi.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gt2goujvsau.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gt2exdisbhp.html

set -euo pipefail
来源：http://dali.yongpay.top/Article/details/gt2enwqvdlo.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gt2wblfvvbd.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfcdhlur.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gt2bgherbqk.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2ahgnmmnh.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gt2baicusxy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gt2akhcrxws.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gt2npuudcfv.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gt2mrxfzzsd.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2bdfjoxsg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2bscmmgek.html

[R07] if 判断文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ovpyazoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sysykeji.top/Article/details/gt2icuphphs.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2nkgdbsnw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2laztqmyh.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzongfgo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2gdspvsbh.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gt2ugestdst.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gt2lbjamrfg.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2xyhlfgth.html


<!-- 参考信息 -->