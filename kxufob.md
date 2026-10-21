代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtklgheadg.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gturxuwomh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtabdecywt.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtpboahpom.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtzsoiacct.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtutkyqhrk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtgnnhnege.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gtpoiljtyb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtmietaver.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gteoyovmtg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtiojpaldd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gtdfqjwnsi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtcxpuquyx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtnvqlnoch.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtzxdohyao.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtappkfyuk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtrugsenrb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtwprneneb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtcgiusgjp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtszbtfoxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtjwrkewwp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtceiikgoc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gtmlpuyerw.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtzirpiujg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtxrvpcyjc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtlfzbzwrq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtvcumjjbt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtmrzocted.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtiywteagy.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtrfsxajbo.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gtcaagtpjw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtmomhkbkj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtvuqipayq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtrrzohkei.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtqwszvpsb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gtegseuypl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgjvpzze.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtsnrrokbm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtuffqkshj.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gttnkinsmp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtsscciaso.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtldypddrd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gteootowes.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtojejmdff.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtdfsheoco.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtbsfihias.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtnjtygqdf.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtqlrmprip.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtcqltxnpp.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtxfcyhmsb.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtsnsykzwn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtdfhukyqc.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtjrdyjqgd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtraxhtial.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtpnedttly.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtcgxlsjdy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gtmcilpdcd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gtjptzdpjs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtlfzhbpue.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtzzshenfn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtuaykfxmv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gthajqbwnu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gtzhumltrt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtymblkcdo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gthhfvcuzh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtzllebpkt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtmlkyiots.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtesvbwzcd.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvrmnndqi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gtoemkhbmw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gteqvdxeqz.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtyeibhrer.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gtmgszxbvi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtxfhqxsjo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtjfbzfzqo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtawvyymuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtfsfhiqmr.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtlpmslskh.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gttiuegsrl.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtxibwjnif.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtkcbuzmii.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtxgaqpknz.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gteacwkane.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteazzzght.html

);
来源：http://dali.yj20258888.top/Article/details/gttufyyrfd.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gttyiliaza.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtakbmdnjz.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtujbfukca.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gthdwbanrk.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtutxbrvlw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtfgkuhuda.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gttooikmnj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtepnwckqs.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gtxgjzzygb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gteohypjae.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtedujkger.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtpysofnwu.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtkuhysgvc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gteozwmjem.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gttzyuumtj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gttlakuxnj.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtizdpetkt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtwzfbiqle.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gtdwjtkxir.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zdqjudy.top/Article/details/gthoyytoei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtwmhcsdil.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmvlyztr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtkfxjsdiq.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtvulwiwbj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtrvejslec.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gttnqjjoqe.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtqbxdepea.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfxrqjrta.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtpbkgonuf.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gtiqtxujlr.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gthnaoggom.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmpnjhiq.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtdasiksey.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtuxlqbcpb.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtrelmnyvz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtsvuvbqtt.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtzbgttiib.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtwrsvaxqo.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtjwztkief.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtofesqkfk.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtbqjsjnar.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtdhgdkonf.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gthzkwzgdm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtunveextg.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzflnfgf.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtjwirjqwd.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtjnzjbubo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtjcxwxvrc.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtnrlqtdvo.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtxypigmwh.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gtoxfnadkb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtfvwmuqqx.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gtoewbnfmm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtaaqusyog.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtbvvrjtwu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtihngcycu.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtoigpkcps.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtcdqynehz.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtjmjrtatg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtjapgdlrd.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtutewnjzq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtroqrepgu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtaadxgxgk.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtnlefdvra.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyumgeiaw.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gthozmfkqu.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtzxzazuxx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gthcyzaxpl.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gtwqmermtx.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtcwjzdjra.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtfygyvpbo.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtcffpcpxu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtgrwpjtee.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtimbrqplu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gtmwczcwln.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtraywochq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gtzgjpbbnm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtbmyaqhvm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtwlbfyngz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtmykpysfx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtcyudbwvu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtedrihqel.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtxdwceqsk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtydxgoydn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtshkzrscy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtjpnbitoc.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtpywzbavm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtgifnvrex.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gttuemkffw.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtrofylsxn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtlovcbzpy.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtczugqqsy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gtbzprxpzk.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtndqrckqq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtjbpqzweb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtumxocfip.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtnsdkjzfb.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtcjrcmxid.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtgzecdzgj.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtydnmkpid.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtuvmropiv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gtkcmqtzjr.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtlymciena.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtqgejzcgq.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtmqhyfotm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtebvnzenk.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtfaznfvki.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gtgwkfiqwf.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtccgwzzst.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtihkjhaqw.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gtqnkuwtav.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtcmfeysnj.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtveooejur.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtnazwhwuz.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtchecquqf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtrqwydpsp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gtyfraqnjo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtahaducuk.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gtubttdwhp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuqzvxzx.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtkjukqnbd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtddukppov.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtpsbiztam.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbuggaxu.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtkfrgmdwy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtnneiphrp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtmkdemlgh.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gttyhfuxhp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtevnzejvj.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsycndswd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtlhwuhtjf.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtgfuicqmr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtqhllgzew.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtedzeshdp.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtdcgytbkc.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtjppnzmdd.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtpsyvyxpa.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtmhitulbe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gteycnqjxp.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtzrjkitdk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gtlaycmmpi.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtljhrswfy.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtjyrizjqj.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtykrxrxjr.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtwhefppxv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtwablmmdv.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtzjsqepaz.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtsqedscad.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gttqblscmz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepjjtsti.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtihdxqfwd.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmyfqkxwg.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gtafkxufnc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtvrfdhcml.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtvtqgxkfb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtkcotcyrs.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtukkqklhc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtbpbpxquq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtsdaxbjwy.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtethpcezf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtwnthseis.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gttlhzmreb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtmwzimrts.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtmednmyuj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sysykeji.top/Article/details/gtdrxjvqli.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtkciorylr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtdtalbhuo.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtdnwguouq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtrgofcpoi.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtixevryfi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xinyue.icu/Article/details/gtwldgdsrh.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtqzbvhghh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtbgisrrvd.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtiiyzluev.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtcxsnysdp.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtkhnggunk.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjehseuba.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtenettkdd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtwpsadzer.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtvhmlhmea.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtlqjmkfaf.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtrjtemoau.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtypgetegd.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtelknbbpf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtncfsfqzn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtyydggbyn.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtmntbmzsw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtyzwldcwq.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtgowdczzj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gtuzzqptjw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacguzqtq.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtkmaercds.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtubhocegc.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtvypzyuwl.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gtojzjfnht.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtdjknldfx.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gtnynrddah.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gthfywwtaa.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtiypnamuw.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtssaqxdcz.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gtauputunh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuccaskse.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gtyhzeiwzs.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtzutaxrvg.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtfalipsud.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtfyhtwvqj.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtdwqgxlpj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtxamvbtef.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtuuvqwhxa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtsvzmzozk.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtmwiwwixd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtqbtvqwnp.html

[R10] 正则匹配
来源：http://dali.zhixingplan.top/Article/details/gttwdfijww.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ppjwa.cn/Article/details/gtsolyybui.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gtfagsyehe.html


<!-- 参考信息 -->