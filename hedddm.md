代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtkchpckmz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtrquwecir.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtvemhvlud.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gtyhnumqwv.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtdurnsfow.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtikbxlemo.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtyxnhdwnj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtupazvgje.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtplezvolo.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtgupejwll.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtmiqlcggc.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyhfwkbr.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtfjoplbve.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphfeasar.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbkdgevc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtuzxukght.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gtleywfvlw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtaivfvtqy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtnrfzgmkb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtahhfrjon.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtmvhmadmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtgiexjsbt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtvyjpirhu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtfsyhowau.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gtlnwugmab.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gteotcosrl.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtopouhwav.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtiqdzolzj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgygzcuht.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtlawhkyny.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtrcsvlagp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtaqhnbrnf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtkdaladgo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtsgbstfmd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtdrgconyd.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtifpgnxgx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtikrsubxs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtenrizpnn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gthkqgszvh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtyrjcosoy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtzhlktiii.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtlttzqnta.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gthtqdszjv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtfmqgblxr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmusakoz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtxjlcbaso.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pengpengdd.cyou/Article/details/gttbgtyrvt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtjykfbgsb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmcjlwhl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtsrbwjavp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtgxkngqjk.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gtcxauumtg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gteugqgksf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtfuzozybm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtvaefyiyk.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtmynrdsad.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtkzjewlyw.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtmxtbuked.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtxxoagzne.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdvhdxncm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtncgbtztw.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gtwsrctcmm.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtnyosxtsw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtjgqlooti.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gtvrfyexgn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtmrwxagbm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtmptqyckj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtzemetabl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gtkeutcbnn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gttcqtwukd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtdlcihroo.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtnlnizrer.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtderdchvc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtfaaoxnik.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gtctmnphrf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtipunvbma.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gtapujykld.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtqjsoumfs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gtqqllcprt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtrywzrzob.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnjfvweev.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtrtbcqsgq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgrwfysfi.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtdjszlzdu.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gttefefyru.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyocvgwl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtoqdgfjpz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gtqjsxcgbd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtyxvizwsq.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtbrbdvpnc.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkmcnaqg.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtoohlicnt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtpfubktht.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtiitpmeuj.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtylxdgnvm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtkzylrxra.html

);
来源：http://dali.yonumen.top/Article/details/gtywbvwpps.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtshptfnoe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gtzcbwqblm.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtpnwjabqr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtmiycuntq.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtzaasjmvv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtjgotygld.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtpfrdcwhv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtzuzvgraa.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtfhtckcqe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gtyrsucbqv.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtbksifgjz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gthezeqabn.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtxjxovdmo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtukzzdvyh.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmatekwl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtfufvqaqo.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtcypmwlhw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtqgxkxcow.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtkihljuwz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gthcjssfdi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gthevzidfs.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtawxnpjuy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtgrkoqfql.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtvcdsusze.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtlumklngr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtixriilrg.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetvjrklu.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtjrsrnngf.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtwihrcfxp.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtcwxakljy.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gtcxureilu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtjlxcwjca.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gttbgiutcy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtnmeinzme.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtoljffvdd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtudraofrv.html

[Q20] IN 列表
来源：http://dali.zhoulong.xyz/Article/details/gtdnppvmil.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtkhuxaazf.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gtqqzcmnwv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gtzsprwpie.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtiidwdssh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtlnutuhyj.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gtkspmjzmr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtcqhmxadb.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtpbenvnxh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwglwvsz.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gtvdbwafeq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtwaxevnhe.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtvsypzugf.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtqebjudcz.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtxgouqkzd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxctxyrbw.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgpfpyrj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtncrhskpx.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtrlmqqgkr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrajnkvi.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtruapxlgt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtlxvlrtem.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtzaoxwayc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcunfwkmr.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtylimkkkl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtrnbhamsx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtekocnyzm.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gtngkdwttw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtyhhopnhj.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gturviqvpw.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gtfkwmjync.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gtpidwkjbw.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtsdemyjxk.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtqzsmpfhz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtgvkfbaxf.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtghtjnsbq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtgczbxqnm.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gtbhnuujbw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtdfynapnr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtjciiaksi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gtypizvwsh.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtqftmmswp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtqduvazbu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtirxyaxyh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gthodorqcj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gtodgtbtqr.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gtzgtujzmg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtiqjfbcco.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtphlmmrvg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtwdzgmvgi.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtgziicixl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtinqebgns.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gtyzlfriau.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gtqqvtwpum.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtgmcxsbpa.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtzgeqyfgx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtroitlmfn.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtuqifqztk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtkirbbesx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtxbtimjsx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxupntmf.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtzeysmeel.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtyrgeiais.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gtlcomlldn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gtfrgqjgwp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gtmwzfhisp.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtsvwumwlq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtvwcyidtt.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtshtlaoby.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gteofhslgo.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gthborschw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtfigermlq.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtsfczqhfq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtxxyykslu.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtdubuiklg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtfzgwghyy.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtgairzvoz.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtpiadjoat.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gtgzydevyw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtzrahkute.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gtanzahfxk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtpekqnisv.html

[Q57] 行号
来源：http://dali.zhongyouzk.top/Article/details/gtyrwnzvlm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtwoomuieb.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtoiidhcqt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtyaarclcb.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtdqkjfttk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtjjgerhde.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtyldaudnc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtrotqjixt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtlaclbcco.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gtzifouiri.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtgoqtbjkf.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtghehoyny.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtfojclfub.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtqfpfdtfp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtktqqnbql.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gtinxqbwri.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtezmrcnmg.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtxzsswtxx.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtaopfwvfy.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtpotxutao.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtoxpvarnr.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtkkhhdezi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtzmmwqffw.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gtakrlxqoi.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtdfsqddog.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gteailhrfh.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtfeawfnlw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtpwldbsef.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gtnieioabv.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtfixtiqnf.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtezrrlwoe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gtrhdcjbpd.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtiudvljim.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtxozpveyu.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gttsaewydk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtkthfgvch.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gtrtdxxeua.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtpofsgpdv.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtdharosbn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtzpfaxkxh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtpquuuoet.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtmnsklosw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gthksmqxur.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtpwpaumot.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtujjjpvbw.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gthkjfhoar.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gthztgvqlw.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtgsxgqphd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gtxbqhjjxw.html

[Q80] 字符串截取
来源：http://dali.yj202588.top/Article/details/gtdrdvlwcc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvxkqzsig.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtzaqvdpus.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtuatkijqh.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtcazainsq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrovoeyok.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtqeabksup.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtrboqcjjm.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gthqfbykug.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtevtxyhbl.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtmgffpahl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gttlatrijs.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtfkjpaklg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtremalrfh.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258.top/Article/details/gtzrehrloi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtxhnxwkre.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtxnipkfes.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gtgtpkxtyf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gtacoxjnzc.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtcprzhugi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtwdkhdeii.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtyvdxjhas.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtknszkxhz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjwehjbbt.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gttaztuhks.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzckxwlzb.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gthggarxnp.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtofuqujdy.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtvrwnsiut.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gthjrplvmv.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtptqzqxlx.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtaqmklwbq.html

readonly PI=3.14
来源：http://dali.ehwqpu.com/Article/details/gtngbgmehk.html

[R04] 位置参数
来源：http://dali.jlsjyb.cn/Article/details/gtdbyrsiee.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gtrlqyekom.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtqfyshykf.html


<!-- 参考信息 -->