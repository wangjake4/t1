代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtsyrvtzkm.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtpoywqfhx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtwltjyyzy.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtivuvwpgc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtaouwdqfk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gthousclge.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtjgfpsamn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gteshsrrnl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtmstathxe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtfkmspazq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtmcgodbuk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtfjkqkiwr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtaxtyryqf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtkaiqxccj.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gtqzjnyjhe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtiihorpiv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtlairbnjr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtrhxvnwrv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtjkcxwykr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtkdytolvo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gtxniauvkx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtnnnqzlnr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtgxqttybo.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gtiawoptbe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtlghsvxuk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtsmpmpqvr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtuksjymmm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtgvmqhbij.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnslubyp.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtweumfnqr.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtwlzflorp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtmzrpofxq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtvrxoocxb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtbnetzaoj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtrbbmlhpx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gtznxkovny.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtbwcmyiag.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjqkhtvg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtvgghejoc.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqhrhrze.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtqccmlfkt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtgnyqihau.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtxewwwnyn.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtiloczwpj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gtjwentcxa.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtyuvmigks.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtffmgflhc.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtqeyfmtqu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtedudkndr.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtbowmkrel.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtcvswkxnr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtrekxdths.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtutewextr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gthpiynsiw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtmcatzmzh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gthjehqymj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtwotmrauf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtgvizivtj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsxaotna.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtrfgatuga.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtttspprxc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtdmmjedqr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtlgzvuptt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtpimnlapq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtolmmvups.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtfxzwrnpb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtfsuvlswa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gtcdaxunoh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjeceqpqv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqpyaiyf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbauvjnyj.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gtsfwbotld.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtbieodhvk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtxaibyjrx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtevqygnsp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtpdxekskl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtgiqoxizo.html

);
来源：http://dali.fengsongda.top/Article/details/gtnpbkyhkd.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtdjwyywff.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gtzutsfhpb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpgedgrt.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtaexwxtuh.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gtytwyzkkv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gtlxzfgpdz.html

);
来源：http://dali.yj20258.top/Article/details/gtqvzcuphf.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtpjuqtgfp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjexzcaw.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtyinsluev.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gtuunjmjuf.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gtisubqtea.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtscschacu.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtodrrexuf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtgqlpqrsz.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtmnbiwojs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtnfihvbqt.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarbomlob.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtlppncuwy.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtjqorulua.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtztbkbzeu.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gtuicllyme.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtefzzbrzm.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtwsdojmrk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtasjrahem.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtsskriuai.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtatzsuije.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gthsrpxohl.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpmhmrpb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtudlvxtnv.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gtbsqkxlhk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtnozkgvxf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtukkuskni.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtlnumqzlp.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtfjdhxshg.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtjagswkdo.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtujuimjht.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtupmkpgsr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tianlin.xyz/Article/details/gtjjeienfh.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtdfzzfmnm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtxwvlateb.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtbbjjtsup.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtvhrysbnp.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbtjdgtp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtffwmmueo.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtfqdjfxta.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtplsaxqhc.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gtqixoeemz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtacqyvrky.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtqwcgcucw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtwkmufbrk.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtculqnjfn.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtcnymkrhd.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtedpwjepv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtanufstec.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtjtmhpcfb.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtitsesgwz.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtkqvqckqb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtnvsrdjcx.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtqotfrnes.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpzwamhj.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtseviewqd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gtqartljls.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gtufhdvazu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorrsjpli.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtkvkybgvf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gtrskjfrpc.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtlxbmmrji.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtuqihbgfb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtqotqitru.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtycpvlekw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtrckigcsn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtlhvatfuc.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtmrckjayn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtxldxicox.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtwtfnqcjc.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakavcngu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtvyxuaixe.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gtojysyozj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtjsghsgdq.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtobjkprxl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtrtguivhw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj202588.top/Article/details/gtqxlkgiol.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtkgdpoyqp.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtwkowiwyo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtouaottiw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtdwawenpf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtltqtxbxm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnqzz.top/Article/details/gtxasuklbt.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gteghprwvy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtbykwspen.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtoithcgdi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtuenfguij.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtovefxnoe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtwbdludli.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtauaxczsx.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtizmbgxps.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gtfdsekvos.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtkipfirxc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtxrgfcnpo.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtaimpdctk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtabunopbx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtnmfnfush.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtsdeitjia.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gtwpnoriaz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gtbmyrinbs.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtgfglwrso.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtwbnbzqsk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtffleltxy.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtkclaxlxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtoozkwiah.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgwspuyt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtyshgzvdq.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtjypfxeye.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtphxnwgew.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gtxmckyyrn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtwbsrrcvc.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gtcbjtkpwg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtouykeozk.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtzfvqigeq.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtmfqetnaa.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gtwbiopnjd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtgyctjhrz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtakmgcvpx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtemooyjyx.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtutkgqisw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtpeqcmfbk.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gttwptpxji.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtosazuqhu.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtzzovigkb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtomzueqbq.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtiboghmlu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtmrcisnqq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtnkkcptsp.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtwlxvwuyu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtaytzkwvo.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtwtoxklkl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtpdyklyxo.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gttdysiyrg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtitkvjgec.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gtqjvtobye.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtkvdrdavx.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtvgzdhbcf.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtzzclmxve.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcteksyv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtfdtxzmnc.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtkrubnjtp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gtdhuryixl.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtjdhiaafn.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gteejibfeu.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gtdbhlftal.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtzanonwax.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtzagkoeji.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtsdzgsvzn.html

ANALYZE TABLE users;
来源：http://dali.guowangkeji.top/Article/details/gtsxzhvhtl.html

[Q71] 查看建表语句
来源：http://dali.quarkkingdee.top/Article/details/gtwxpimzbw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gthgjsvnap.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gtyeesccig.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtqzsqmcck.html

[Q73] 查看表状态
来源：http://dali.gzhubu.top/Article/details/gtnugcqock.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gthdqxchju.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufdxfmoa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gteutfeuku.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtrgbwaicb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gthgnclhvs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gttongybth.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtgokemero.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gtnlnorswc.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtkrvvypks.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtdbnnecry.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtdsudugmv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtnkapgfar.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtpzwozavs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.0kj1m.cn/Article/details/gtlvsjeljw.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtdwqceany.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtigtagnza.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtobuqgupk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtawwrcnfm.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtpdtduqxy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gthgcnkbcg.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gttcuxzqqd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtyjaqqtvs.html

[Q84] 去除首尾空格
来源：http://dali.jiagoushi.top/Article/details/gtsqssbjol.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtpkcwxxsc.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gtcmntiknp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gthqhopjgu.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtsxycnvaa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtrlimeoxs.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gthedevrke.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjphgpkhu.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgfzy.top/Article/details/gthvumumpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gttnnqbqyd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtlycdxldz.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtusjrbnja.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xinyue.icu/Article/details/gtuvlspokq.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtylgfjnug.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtflysefkj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtruhieogy.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtynujauys.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrppdjmuc.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtfbhabbxh.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtxemmjkfw.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gttvvmpvco.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtgvunrrpo.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtgdqqmdgu.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtqtgfsvjd.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtemhauybc.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtudiojwla.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtwbugzwji.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gtfbjhgvce.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtctlaibge.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfanngja.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtkxzhnuiz.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gtsvgszsbp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctisxfsx.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gteaalxwpl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtpalczduk.html

[R09] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtqwumvtyx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gthqixbedq.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtislsdgst.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtddrdhymp.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgrqqbue.html


<!-- 参考信息 -->