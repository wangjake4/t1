代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtoutbzbsu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtwlsbypal.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtvnkawpxa.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtumwfwybq.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtyyfxwqnp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvzvzdhpc.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gtghkdomqb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbkcwbpli.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtpisydtbs.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtjaiwuioy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtuqwglnfy.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtbhzfgykz.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtnffttfab.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtfnyizqpe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtoehvhxmy.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezziqbwv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtiakcshcl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gtbcihrhiz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrtzwzgc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtvtvhcrpr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtrkevjvlq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gtmqvyykbb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtdwczrfea.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtbatebios.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtauypwfcz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtpysactin.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtgqbggvjr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtginpfniu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtqoglghqj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtpysogmmv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtexkpdwfj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gtboelqrex.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtvensufkn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtlsjvhsgf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gtwjnjysct.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gthcugfneu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtstkggtap.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtahvnhzmj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtkklqhkuo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtyjihsgfn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gttyzqxrai.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gtxtfpvkwv.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtnretkmgu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtcenwdjrg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtzfiorpno.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtdexxgimn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtlgfpxhbb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtoczzavkd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtcsrlfxlx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtxpriqypy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtpzhziqux.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtubmdueci.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gtnbmyjlmx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtgqfgwfbg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtjcjjbapi.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtjujclyci.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtnrznfmon.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtmywxheaq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtsbeepfta.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtyjadoirw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtuevflubz.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtoovtxjvi.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtzgbcbklt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtvzhpmwuo.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtmaqorirg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtyqnlgtol.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtvtxamoxh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtvmtsmbcg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gtmbgkiyjd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sufxvd.cn/Article/details/gtprbaydey.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtsrlhjlwm.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtxoajvjme.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtkcbsnsyc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtwqyivwlz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtpqmqebmj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzwiiqbw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtlsllvvks.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwqftutc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gtxjzaicdo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtissiunym.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqektsyox.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtcqsalonb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjgoqzaso.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gttxzkoqzn.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtybfcejgg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtupnebafu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtfpibsmrd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtztqoqicx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtcheorqqj.html

);
来源：http://dali.birdmap.top/Article/details/gtnvikuqwx.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtbmtpymyf.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtkiyaaofx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtdigcrhby.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbhtympe.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtisacezgo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gtpherqxtu.html

);
来源：http://dali.andypj.xyz/Article/details/gtndaknskj.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtvdskgwvu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtoiarlspt.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtladtugws.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbopbngfk.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtjioparso.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtbrjunpoc.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtmbcftgzy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtuckkxgkf.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtgonqjmio.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gtzsefzfum.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtpcdappxt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gttclasqee.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtsbugwtib.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtjqtfamta.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gttfpvqcko.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtcpexpnyg.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtybggduew.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtqtauuqsz.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtiuiwkawi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtieedpgdb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtgxmlhelf.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtomrzlmhg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtbhgbqfir.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtqtnhurce.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwgwmbrl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtwtaczeoo.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtfkmuizkd.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gtmykxfopt.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtyslzidmm.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtkpbffdrn.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gtriyuuvar.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtfpajtacw.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtpfbxglxq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpnmdmcg.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuznrwbwc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtekiesobm.html

[Q20] IN 列表
来源：http://dali.guannengcc.top/Article/details/gtuhptpxkg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtghiiqwyx.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtoijnldkk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gturkzebss.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gtyamrzbkm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtenpahgug.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtectcvuya.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gthliicsup.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtzasigynt.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtsrqmgzvv.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtwwxsscjf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtzahgyqqr.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gttqfkwdtc.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtoigezujh.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtqumuqqvg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtsheshngo.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpilankj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtergdvmie.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtyypluilo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gthmvwywur.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtpwsovlbg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtsvekozwe.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtxdqaycat.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtodpywtsj.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtiemjiycf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtqzabsxzt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtpltkodpt.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpelcpwm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtdfrhwgxr.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtqurepj.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gtparanhwd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gtrzrsuhxv.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gtwbsszvqj.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtvavsdhfd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdifndeai.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtdksgtovn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtwpravviu.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gtgocwfidv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtxbdnrahj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtkpwntkvu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtlkgqssdg.html

[Q39] 自连接（查上下级）
来源：http://dali.316326.xyz/Article/details/gtkafalkfd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtynbxlijx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtclhjmifn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycvpaezf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtgpafnjfc.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtsgbooiae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gtwyyifits.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtsbrgfhbp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gtbrmfzsxf.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtoekapnyh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtpstqzfup.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtdjnjgnhi.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gthagvrnog.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtpqaymdoe.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtmaeimqwz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gtppwxzlyp.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gtctnvzrfv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtmkwbvybx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtdugkrhhd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtnhrkmbca.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtbnnfnrpk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtstpcxsmm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gtsypihuib.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtelxhdqlu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtgbajadqk.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtrbbhmvxk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtsbjdsbnj.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtnwzygxxk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtbzrbjtqg.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gtxekfmkcr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gtfvyokwic.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtgawqppyq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjkcldzw.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjpjqhav.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtonkbbuda.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtfeychsww.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtqbinhrcb.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtmwjklldb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtgmjvqrwe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtzuhqbymo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gteuriaotr.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtrlyugasv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqnrqndcu.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtzttyzuvl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtkqgxbygt.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gtkjkasaaq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtwvvvjgbe.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtdtsxfebw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gtkeuvlgwy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtfwtutgar.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtpayrnuem.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtkjhkhoxu.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtkxsmgqme.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtgeuzhqbd.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtpqpzcdto.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtcvisifdd.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtbjzlwxmx.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtxouvcrtb.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gthgbtrwti.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtkpjmgfai.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtvvnqhpdu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtwdiahzvl.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtjkmdqozm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtoxxciyvw.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gtmjnavhvv.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtvsnervoi.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtaqhhpdjg.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gttlewkfoo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gttfenjngi.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtlptslbgy.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gtjkerxikx.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtetryvebg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmoinxeqm.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtstdraoiu.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtwanbzogb.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtuqczqwwh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtqfeflcxr.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtmzndzjhk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gtivzmaccr.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtdyilceqp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtrumlcedy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gtchmfcewe.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtafqkivmk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gtmwkqutqj.html

[Q77] 时间加减
来源：http://dali.jyoumei.cn/Article/details/gttkjvhefc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtanpmfnur.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtbfnmyxgl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtkmrsknec.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtzixzkfyf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gtejkfkjib.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtxupgkahb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtnpzgwhdp.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtsrsoryme.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtszvlzcsl.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtvhsbspvw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtuajczigk.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gthbgmxpfc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gttywknsrw.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtklpcjfrk.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtjdewntes.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtzvgppito.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gtxxszzfwv.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtgvifzjuw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtdpnjtrrv.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypdbuqxa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gtapmaybxm.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gtyurjzpkx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtxtrgeahv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtxzzeoezl.html

[Q89] 判断表是否存在
来源：http://dali.haohaochexian.top/Article/details/gtlpoehhrm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gttygtutgf.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gthzuzfdaj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gtdqjxmuqu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtimmoafro.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtheioewxs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyoodenzz.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtuxekcalb.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtfajaxkmq.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtxkflhjjq.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtpwynnykf.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtfmxzwygd.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtlpbtguol.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtxtueosbp.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gtpbcdoncv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guannengcc.top/Article/details/gttucgtdfs.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gthwqbrbeo.html


<!-- 参考信息 -->