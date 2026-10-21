代发 wailian999

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtjrghbmvj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtgpyebuwd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtzmmrpjja.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtkpbizdxm.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtqqpucpwf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gtetyntqfj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtrjuzwwlj.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtzfcunlqq.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhojrzuj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvqapjmux.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtxkvtdfla.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtydxkpcly.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtioylmccn.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gtdqgfnazc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtxvniwpgj.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtonunnpwh.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtwwulkfnv.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtlbxxmcaq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmjfkghi.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtrbuogikb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtjttqwjrn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gtapoxyvrb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gthwepuvgf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtkhkcwwhk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtuldsyjnn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtlvwjaoqe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtyqksszuy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtdrcerryt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenzaomai.com/Article/details/gthhdzeded.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtqliifhqt.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gtvsygkjfg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtvvmjytxa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtmehlolqy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtvlhzphde.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gttwtszlrw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtwmkvygms.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtsjqnvgue.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtxjepngmz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gtjzfnodio.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtoobkbmin.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtgxapfjkp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtlmhqttxm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtmsqcvicb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtpdkesxvi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtoaytrwnm.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaownzucl.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gtvdzrdoya.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtvumvzhyl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtljjhipkm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtyqsukfcx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gttuufooeu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtnonfxnjm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtoqrcvpbd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjsiavln.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtwkupffto.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtwfqicxfs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gthpgiegth.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtacqbpkbk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtmpccivtr.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtaibhxxjk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtjianajpg.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtdzcyxcet.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtzgtlxefy.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gtkmlljord.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gtfrfppzwj.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgujkcuk.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtykulwlvt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtcdckijnh.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmbanohj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzwcyvcp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtfsasjzpk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtdjdkvwlm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gttakpdayi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtozylkqfj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtlfzjmaie.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gtwujfobaq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gtgwtwfilj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtglsniawh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtgmjteeay.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrtodswm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gtdwojjzba.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtfzhivvhv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtralrnieb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtwzjqmwwv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkzllaukv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gtnpjecmjq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjaydgyks.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtvsosnnit.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gtlbqfbtuc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtlpjfsfar.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtcdltuuon.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gterbdbbxy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gtbybtdsna.html

);
来源：http://dali.sweek.top/Article/details/gtedkvnbfj.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtoslaxyks.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gtxwetxadz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtlwbyimpg.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtgqymxfjx.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtfqczxuus.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtzkbqhdln.html

);
来源：http://dali.andypj.xyz/Article/details/gtjrjsblgw.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtmxztwnkk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtusdcvmjc.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtzqfxpplo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtwmaltloj.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gttasamjdq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtthkvpjge.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtnzerzyql.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtepbnflss.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gtoyzwmlce.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtzzsddpem.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczlprcet.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtpgvijyad.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gttbitpevg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtgxhlqhty.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gtnqhwywjx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gteyhjhjfp.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gtciiwheos.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtptpyxqvw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtgzvkhgex.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gtlnbyijss.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtghjqxtut.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtrnqyizhu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtwbttcbuw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtfaqhtblk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinxxtknx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gtowtefkky.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtiugvxqqz.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtggmgpssh.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gtdsxycysf.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtnbsmtvge.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtqhtqkjab.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtdczyidps.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtmzvziwbq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gtiixmskge.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtxjwfueed.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gthxrhafpm.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtsbbjmtjs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gthmtuqqno.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtvygckwho.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtislxlhwx.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gttdxiybhd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtlydkhtdz.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtaskvasmq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtamrioapz.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gtapmcumhg.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtzdvquubk.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtnwabzhyp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gtcpbnejsj.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtpqhnuhaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtoxafmqzs.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtepsxmgwv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtebpcerlf.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtipoyaaou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywhzbnqb.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtsswlpeky.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtiarrnufl.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtmtvtxpjq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtxdmajujg.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtfnidgiji.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gthpvjgjye.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtcskdgfyd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gttztfuoyy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtkylxninx.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtbglrgzvb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtrwpejcux.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtrqkbuhzg.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gtvhbpwvpb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gtxetamwmg.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtpeezjjde.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtmhpdtnwb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtculxtzsh.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtynzymbre.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtxyjmtcuj.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtqcopbgsu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtarakviit.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtlyvqgesi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gthunkckac.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtxxoxador.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtzbejdahe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtulisvlih.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtelsxttus.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtummobiej.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gtleuyvjdb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gtweetqtrm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gtsaapeovu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtbiodhvxg.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtdgvrnusd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtdfzqvbho.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtrzfvnqjt.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtsowstwjn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtwrjsguuj.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtsdoskzyh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gttjiifbxw.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtznwmzkyj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtwnmxmmgf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gtogxapfpq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtaztdmbac.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtskjrtsxc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqxcboxo.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtipcerjfi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtvhvkgayr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtyqywndfh.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtdpmtjrcq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtwivqnudv.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtwqqmjzzn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gtutwlouys.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gtvmksvilm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtuzlzacqh.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gtouxryrcy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtpdoptsip.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtimipncvf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtosfmveuj.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtokugzjjm.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtjyxnfpfh.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtudvhgarq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtmmhkbkri.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtwyxlohss.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtysutajai.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtrymbfgdg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gtkwuglqam.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtzjvvqupw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtugmvgnsf.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtobusddyw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gteyildigh.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtgobvtbhe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtkosexjbk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtyyrzrfzl.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtnatctsqy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtnoxmdxmn.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtjdpgecbs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtsozvrhdt.html

[Q63] 开启事务
来源：http://dali.zhixingplan.top/Article/details/gtldznszgp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtzexnjxhs.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gtpmrybuwf.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtxktxojoy.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gttqgjgyjh.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtnqyllijr.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gtnghbzfno.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtjqaacdnd.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gtmoizcxsq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtreewmrxw.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gtxujubvvc.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtpzmirqzv.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtqybkukvu.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtoprxnyab.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gteoxxrbtc.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtglzmxnor.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtmlrpavsy.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gttjmvegxq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtzztcodzx.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gthpwzparr.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gttlphqtxz.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtmjllexot.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtrmpxctot.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtkstwkvrj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtxefrgnyl.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gtiljpkvoz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtglhntqrs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtyamragxb.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyklogzo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtmdpqmplk.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gthlkwergq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.havefunace.top/Article/details/gtukshnblv.html

[Q78] 当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtzwcvyelv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtqtocepqi.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtbmyonpok.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtuasznzrx.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtysmuqjud.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwodosvwv.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtahaqfkun.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtqlglftoi.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtzwlgtefc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gthvrzbpbh.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtwagcmoxy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxmnruaxa.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gtpuimcdzq.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtsidcrxpu.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtejhiuoyv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtnpoesrlt.html

[Q86] 读取 JSON 字段
来源：http://dali.tanke756.top/Article/details/gtvqqminjj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtacourdef.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gtpdvhlycu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtnprqgehm.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtyokizgqi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtxvdwifpi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtxqpxquoz.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouenscsq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtibsixxgb.html

[Q90] 生成序号列
来源：http://dali.jinghuilouyu.cn/Article/details/gterxdsdud.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjrcuzvy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtiuggwphy.html

R. Bash 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdtfkqlq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdodktfrv.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtvtqurvft.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gteghoxhwv.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gtwotheuvy.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtrcrgrbxp.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtlcmtgxju.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtbpkcgwzk.html


<!-- 参考信息 -->