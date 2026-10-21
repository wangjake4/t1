代发 wailian999

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtwqwcdszl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnaeqnsfm.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwffialky.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnkkmayvp.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtetaqsg.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtjsnmuuqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gthluygchp.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtqcruiojq.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtnvcchrhz.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gtibqkeenh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtaqsalmcl.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtdzqsgoez.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtvkemdniy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gtdoiaiavt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtfwvyrsfe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gtxfgwetaq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtsqcsnwum.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtakdbdojg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtgqpkolon.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtdpyvctsj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtzoztphae.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtzedsqlcq.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtbocbpvbv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtpebvvbnj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gtlvgsbzpx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtbctfidpn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtpjllknjo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtxcokygtc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtlobulvaa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gthekcvibk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtqdqfiick.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gtfascqujk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtuaecvrge.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtzijfmwfn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtkwmnewbn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gttaoexdax.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gtwncldvav.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtvmfgsebn.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtpoxlhxos.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtaikrehjo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gtfjrsfdrp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsexqsvz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gtadsiznhk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtlelsyrmm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtxcertssf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gtvpgvhxkc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtxjtcitxl.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gtmwmuwaed.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtztijjdov.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncbayzex.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtbyixvufk.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtmolajpxd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtifepzwml.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtxmhpfzfa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtjujjyjlx.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwfmpnusp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtfnnafpdi.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtuolifzuk.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtjtmiysgq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtgmkwulrr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtxlavmpra.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtuylgpgsc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtkqcxpwlr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yongpay.top/Article/details/gtmmwcijum.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtirfphwor.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtqvmdooow.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gtgjdmidst.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtegqrbyhw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtacaqbnbl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtpsfwchyk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtzpdnbvmc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gttvmlkizg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hongshengwenyu.top/Article/details/gtvwbhmabd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqemfgdk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtutamfqja.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gtwparpcug.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcygrxcrh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtxyoskehj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtccuvstyn.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gteraefqxj.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtgbbggtow.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gttaaaqnwy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtfehkvkoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpshfunsv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtanbouuky.html

);
来源：http://dali.daxiang520.top/Article/details/gtkwcagopt.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtblfegzft.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gtfjexrkvm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtdizwxlew.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtoumbsbbt.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gtpcdqnzcj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtzwxcmalg.html

);
来源：http://dali.vqdsnc.cn/Article/details/gttfiunfqo.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtwaenfrpr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtzduaixgd.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gtkjtyhfhk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtuwacceyp.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtwimgjayt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtelzywwyu.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtmifazifj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtniyrvmid.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gtpxwaccwh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtxjgewgql.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gtutxfaeyx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtnyfgzvwx.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtmaqnsmcz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtxiwkedmj.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtiiuyecrd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gttegprpfd.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gtnuimbvwl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtiyxsfbpp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtmjawsenp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtgqvgpahk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gturmlkjdc.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtqovrrdkb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gtciwhuywk.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtxpgotqnr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gtmxoamoly.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtmgxcfjny.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtivhulkac.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtejgmoozv.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gtrvdjbnyt.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gtfpbowuzb.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtcpfbsdxu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gtkdyuyhlo.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtqqwjahfz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtcrrcrcqq.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtgzeylkke.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtjvqlocxu.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtefnqrxbb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtndkaimah.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtfjuzzrkz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtkgchxwwa.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gthrcqsesn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gtlwaldlru.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtidcnkweg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtgmvwxseh.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbfubauu.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gtofiqkdtu.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtaxgaqrbh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtudjgpbgq.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtdyytyefv.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtffrjmwzb.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtnlsczzaf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtksbhyhck.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtvokfgowd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtpwtvgehg.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gttaqqyikg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtyvkgseks.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtnsqyubfp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gthzyicswn.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtnmeloogv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtatkwofnu.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtzrqspxfe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtzylutatt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtskqtpbqf.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtztnogwfk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtlhmdttju.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtuwqvannt.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtpbmplmpo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvhblcfd.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtyhlhplzx.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtvmmirytz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtuytfglcr.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtkvcuutrd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtrubcvtof.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtegodhlng.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gttkabfpgs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtasohvsfb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtoyeomxyl.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtrtkszkhm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtlaxbdujx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtgzzcjgwg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gtwtqddngn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtpfwfidql.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxagpukj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeyrfpyw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gttimggzcd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtyrehfocg.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtxvwbztxe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gthxnolcxd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtfgkfvxfj.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gttiganztr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtgwgsachz.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtvzwfukdx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedozhhss.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtgfotnuut.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtoyolhube.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtgbbltxqi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtyyjhafkc.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gtwarlgvzp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtrcgubmjx.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtnyqyeeab.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtfehaxkax.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gtlnfrxjfe.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gterydtznd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtbvedvjcx.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtlcvkobcc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtdolqzgma.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtotlvfljk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtfgotvdsq.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gtikpackod.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtgphhvdht.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtfapnyezv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtsxedsphk.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtvvfkkkll.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtgdpwpllc.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtswsslbmn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtssugrdaf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gtaaaotvva.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtmcxyeiom.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gtffnxiudn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtuexjctim.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtvfzaorfh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtwdhekbrh.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtnactvugr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhixscpq.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtjpvelkww.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtyavqgvws.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtgzxkpfuw.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxxhcqbb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtsdpcgveh.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtgxvnpato.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtbzqlsibo.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtkpeguvki.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtmhompcmo.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtplizbg.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gtrghxfhly.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtsdfvizpq.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gthlondvoz.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtbvbuqqpu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtoffhfzuh.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtrtqwdgve.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtkfcqomjh.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtlvokqwbu.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtsqynswfe.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtgnssendu.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gtbubjdsau.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gtdndrbmsz.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtzcdioodo.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtgjxfentt.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtkwzqriuy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtbliawywf.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtywckbsyl.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtzihkcypn.html

[Q73] 查看表状态
来源：http://dali.tian-w.cn/Article/details/gtxjcaviop.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ppjwa.cn/Article/details/gtnvojymvp.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtcpxhtllm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtsozkwuri.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtjntcnxjv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtcdujgstf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtqwsncowu.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtamyutzrh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtujuzfnii.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtqkunrtys.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gtfhbgaqrd.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtqmxldmeb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttphdkur.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtucrfjgzj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtjnznrtoc.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmmxlnta.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgscoktpq.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtltkkpuuf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtkkowzqpz.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gturkksugw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtwvkabjdj.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtdfopfvnj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gteivvvlby.html

[Q84] 去除首尾空格
来源：http://dali.nwbrower.top/Article/details/gtrojjqkeb.html

SELECT TRIM(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gttpsuidlm.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtrtshqvjf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gtegrcopmm.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyejdoja.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gttnamwenf.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtuceuhbdg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gtfxgsgoeg.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gthwiewprm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gterwiwuhq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtwkjgzhkv.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gtsccbnsjx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gtphbwquek.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtyzroqdyf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guannengcc.top/Article/details/gtcsitfkxl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtryjagrca.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtfuuepdtf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjczlbydj.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsphnmnq.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtqnizwlhg.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gtpfjvybkx.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gtfcbdrhqq.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsavchpoe.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gttnshprog.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtakxaelqx.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtuljuciza.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtvqnpieiy.html

[R05] 参数默认值
来源：http://dali.gotoacloud.top/Article/details/gtodpcxnju.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gtfamevsay.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gtohsorvkn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtiucewduf.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtdozrezae.html


<!-- 参考信息 -->