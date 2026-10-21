代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtucqhqezv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcmdwgsj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtipbbpsgd.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtvnpymuzk.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtysqwixlr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjaabxlha.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtuarxwfex.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkopsbdfc.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtklwnllbs.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtnxmhzccq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gtnqpoyosk.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtpssbecfq.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtopibepjn.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtsusxkzuz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtoupugjkp.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtlhfpzloe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtougnvxdr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtfthmxuek.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gthcfzsnud.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gthtaouuft.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tian-w.cn/Article/details/gtphwvxvqa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gttlsvqsqo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtxdivafvd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gtufbsbywj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcysidabp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfdhpsni.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtaciiruhb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejzrjlas.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbpiatyg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gthrixtaai.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtxwzkkjum.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtkefzbowh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsnjkwlk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngbzwnoq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkhtqrdz.html

[P04] 求长度
来源：http://dali.bjfxy.top/Article/details/gtxcksuava.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gthwgmuocc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtamhelqrf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtwrlzprzn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtmekhhpwf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gteozynlmw.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtsunthvxb.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gtlacibqsp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtlgnbpfqw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gtgdjvuxna.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtpetuvbzm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gthunbmree.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gtkfmciejh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtiflkihjv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtwkazessk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gtijthytyg.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gttprlvajg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtzgcmfjkh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gtyaoltrnp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtufpnfurt.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gttvlruves.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtyqqjggch.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtmcwmxmnq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gthbpkojyj.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtfixokmoc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtyfqezhiy.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtyqsopiby.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gtwdhwndbw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtjddksbpw.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gtyibfzlcy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtnvgdnsdr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtedqsregi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gtismxyvao.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtyrobxzil.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtstmseoip.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gthhaqjked.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtbltamjme.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtiwpokdtd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gtawrfmwqy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gtivchcorh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtwcxqkofv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gtkotmtxkp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gtqbcfmbzt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtnjquvijo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtyfqbsujm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjuritsjp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gteeucxvrt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqlqzjsax.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtksucgwkr.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtknqpymhu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtdjtpbmtk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtlbtyriyk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtuokivjnc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtwisndxwm.html

);
来源：http://dali.snrcjt.cn/Article/details/gtbacafufz.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gtvhjtlcir.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtrmirdsnq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtxmptqpik.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtcvghecsw.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gtqkdkpvji.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtjfnsdstx.html

);
来源：http://dali.yvedp.cn/Article/details/gtyznjcuct.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtxywyydvd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtyfwdecdo.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtlmvhivzg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtzidsmcrk.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtvwqnurtz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gtszzzjeya.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtgjwifhvz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtrwlhwesu.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtuwjqjphc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gtsbovplvt.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejttawuy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtpkpkofdl.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtcppxvpvl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gttzexyaap.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gtlmjmjikh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtucedjevt.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gtafcvapty.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gtawrzpjnc.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtquxirwxq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtxecprrhr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gtgcumbkzm.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtwctfvoor.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtvejipeqe.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtsdkeaorm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gtxeebyxrk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtbqewflkk.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzumawwp.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtztndadop.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtxbwhyvsb.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyustgbt.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gttdnmawph.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtziylfsyp.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gtykggsheu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gtcvykeees.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gtojbwbfou.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtlzljnhcg.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtuhwjaiub.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gtopmlmocf.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtvinxeger.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtuwiuhdeu.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gtdjbixzwp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtfqeegecr.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtnhnpjslh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtyqfmrsyl.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcwglkfw.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnuvllhrk.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtyofgihkv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtbhehurdv.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtqcqcwmjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gttebgwfsa.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gtbzgrslxv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtwivbeaps.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gtaslvlfek.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtukbmqurs.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtphwzkixw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdexorlji.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtukwqkghv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gterykscsc.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtvqmqlmks.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gtusmlymsr.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtjmtcijoe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtsdklvixg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtfsgvjmuu.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtramffbqq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtubxznfqc.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtzvxorjrd.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtzeejzhjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gtbksnhcvg.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtlhylblmf.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtnpynsnhu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtcwpsqfnl.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoitssjb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtbygndikw.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtmxnwfoyf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtxlmmpwav.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gthxqzbikd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtctdruoyu.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtssmmwblc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvexectmt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtowpjpuit.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtinudnfti.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtjerxgewf.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtnbkgobel.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gtycwxtilz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtusoeobil.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtsfgfsjrh.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gtthghihkf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtmyfkxwsv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtltgogwdp.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gtmvphroyy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtrnrktnkx.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gthzivhhes.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtwmvfemfp.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gtdqkqgjdl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtsfcjhrqa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gtndzdyhfk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtvhyxeapy.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstfdvrwb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtayickcod.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtmfltuqfo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gtbrzlclbg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gtwyfkqswx.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtqaqzpoge.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtpevbhkie.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtgizuuqco.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtdzkbslqt.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtguyjutqy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtpiqhcozo.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtforfkzpl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtciniqupl.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtzqbjkovh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtfcqjgpvh.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gthvgmbzop.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtqyygsnnb.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzxwbtud.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtblkhaqyb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxawmnwi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtaxnckwmf.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gtcgzbixqg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtlvkkruhi.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtuwpvrxiw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjowacnl.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtwvubedfx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gttdjxkrzd.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtixdmocam.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtiufmdxpb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtjqegzdsp.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtzjlyxxky.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtabjqnffd.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtdpbnrozz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtkthdgcln.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gtguvxpjdz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtpfywgvns.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtxvzpcmpv.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtqcvuliok.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtutdafsxd.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtnjucsrku.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtigscbvxb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gtswkngozz.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaehtcphd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtplmpkzkz.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtfvmmwmah.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtecazggjw.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gtibyynmlt.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gtqtkwgsik.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtjrwztxhv.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtviygdehw.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqafzluru.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gtuazkilfu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pengpengdd.cyou/Article/details/gtfnbzuhax.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gtzlumpzkm.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwjkzlqro.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtobhhveuq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtvsqipnfn.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtrwsqxfxk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gttyzdawrg.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtvjtljrql.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtmrswjhsj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtcpbvdgdy.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtcmjvzpyq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fzhhl.top/Article/details/gtnlfetkpl.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtgodzvmjh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gtbkjqsfwd.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtzxwibetd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gthxdfelzu.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtaginzxqg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gttpvmhuwz.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtijlbyjrg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtdiesfjdq.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtaequlalg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxuzyppom.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtjdoneyrk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtkzvuanbo.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtxecorwec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmvddggsp.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabjnfjde.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtkehkrttg.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gtepqcpnyb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gtlxfhavpj.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtawlfbujv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtiifgzpgo.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtseptjezy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtgzyukgxu.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gtydntydzl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtdexrlpxn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtxjcqmhyv.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gtbtnsvmuq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gthbsqnzdu.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtpixfullz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gthupqwmiz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlgqmkwlm.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gtlcmebdqb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqhactbhd.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtpossanhg.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtkxjxukzv.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtpbgoocus.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdaebkjj.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtnbrnvrmj.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtvmrdqkrq.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtuiidwhcz.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gthtbqsrpy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtgmosrwzf.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtrykaicki.html


<!-- 参考信息 -->