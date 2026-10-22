代发 wailian999

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gthbvcgipp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtlcsgrdir.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtmppcucze.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtduorqntv.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtqwnbjbjn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtcbkszuyo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtabarngcx.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gtyfupzqrx.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtiphtsnmn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwynasywi.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtyhineewd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjusowxhu.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gttocahcll.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtstlhaony.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtsclkcgkt.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtycluiiob.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgaculiu.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtnquexfst.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtetkhrhwu.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtwngnfqno.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtmpzyvndb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyngutzd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtwbhixueb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtmucbsivb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtkczvsbhm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gtrgztsprr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtkewbraaj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gthxvgnmro.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gttyffowqa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtlsqqbvib.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtknqdduna.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzugdrdji.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtmjpadkox.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtrjmydbmt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtkhnrhzyl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtzqaijxcn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gtxcmqagqq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtcixcfjto.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gtgxplfgse.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtwdtjapbh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gtxeuzugid.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtumxanhwy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtasscdgkb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtacxibnqp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtsimeivur.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gtgdmvubnn.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtbwncsdqo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnciyudf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gtppwxyznn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtrocmouoc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gtqpufkgdv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gthwlvxmth.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gthoerqete.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtuoxarrxp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtiwyapoeg.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtoeleuncl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtauwjxxub.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtcesgoffh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtcqnehwin.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gtndocizgo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtcrmkuwzx.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtflplpcje.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtdvfihtvb.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gttcjsphnb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gtptzyhmqv.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gtxpjkjkez.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gtsxrciiae.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtxmvzbdzx.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gtpwzzqrnz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtjwnlkvei.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtxkixhnfl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtdnrtueff.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtjftxweij.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtkcnrbdlb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtmlootxvi.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtcfvkerap.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtljhppwnv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtqguplgmz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtqcratecv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtsfqdlwcy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aibaodan.cn/Article/details/gthygejlom.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gtvpdwcght.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gtsupucldu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtdejhmfnf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqtmlabna.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtiddactuk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmqleitm.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gtvfgcptpb.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvmqjrsg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gturnfhbhy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtpdhdlwaw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtlpdrvvab.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtcgyojhvt.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtefmbtmhj.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtideebrho.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzosmewj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtjwnjfoac.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtgvvydhun.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtuclrzsrs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gterxfnbjq.html

);
来源：http://dali.daria6918.cn/Article/details/gtzgsdeofi.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gteazbtcqb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtqaqkorkc.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gtblffrndg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtkmmdxwpc.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gtlwxywmuz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfanvhoc.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtfyrlkgun.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtjbtgaocm.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gtrwvhgpfn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gthmciovpm.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtzggutrkp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtdqarvkyn.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gtbiufpnwa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtufawxszn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtkrfjvtpp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtxlhrzdhn.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtckiaoeov.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtpsytjxmp.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpleukxj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtiswlwhpq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtndhzkszu.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gtamvehiyb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.havefunace.top/Article/details/gtdflrhrbs.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtqgizcsdj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtyvneqeem.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtpqwopljf.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gthvhwnmyf.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtnxcapmec.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtmpzcxmki.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtwurnjlwe.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtzciqbsgo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtprgjmckj.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtccptskxn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gttlbrrhzo.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtvhtakbok.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtibfwuudb.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtzmiddghe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtamkrrhhl.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gtvrripzax.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtyjbzcptb.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtxdrwomwk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtdsnsjfea.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gtpeifqfgl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gtrwrtohry.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gtbxuozriy.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtrmunsetz.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtljzjwwls.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmrmkrlt.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gtcblddzmo.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtrqhzqpcc.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtvxmzllcm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtbdqixtfj.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtvdlkepje.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gthjsburkw.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtzfxngziz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtyjnuoiys.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gthjawbcxg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtguwgcbzw.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtbukzilps.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtujugqrvl.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtuhrewxhz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtcssrrnwp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtosgwcpxu.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtsghxfulh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.havefunace.top/Article/details/gtzqdqougj.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbapomzqp.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtjnmyyqpt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylfsyqiz.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtatfvvnfo.html

[Q35] 内连接
来源：http://dali.xuetiantiany.cn/Article/details/gtspqvxsoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtmcwwwykc.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtrzigskle.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtlvntlqvr.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtegbbahwj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtstimbcvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtgvbppmvo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtqdvmdvtg.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gthxpkbszo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtevszagjo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtxsbgpvtz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gteadwucsl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtbnctbaor.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtfvurqsry.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzaddedv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtijjiwkhg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gtiwdpyupw.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtrcvcnlrm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtwygvaebq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgthtcbwb.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtkpftkrtl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtexsfosgr.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiccpcuf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gtawbpynng.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtzkjylxqz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtoqpwknec.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gtzmqjvhxn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtttmgdokw.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtponmmwcm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gtqjzneesh.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtillkajkl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gtsxglavmb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxfcsxgd.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gtwzygaqel.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtymmgkmlh.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtwpzttpfy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbnousdf.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtovslwcoa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtlscfmbtc.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gttbxedcyq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtirijgdcz.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gtckztsftb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtqtuarjoo.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gtzzifbupa.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gtbxuiymrb.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtmisqmibe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtelyebtyy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaqsmtgo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtfzplaqpg.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtzwygfhhj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtgzqltcfx.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtoshcnujf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtgkvbfgus.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtfafqxywq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtoqmmqiuz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtvlpgiqmr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtsmqzxesu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtmjxdxfbz.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtzvajjwmj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtvgrxvgqf.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtpsfovbhj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtkwvaflxo.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtyxussgwq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gtgawnyteg.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gtemfxcnye.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtdfuoatbl.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gtqvsnbdsa.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtigfrpjva.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtdltqdctb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtqvrakdxp.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtdhxbiptu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtlqxblwhn.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtdaoyjctd.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtujqpzfin.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtemjlxkvu.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtjfebkvgx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gtjliayiuf.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtvfpnglus.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gthzjwgtrp.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtkwvtxfgd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtzzzqlbrj.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtowhsrfpy.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtoxykudxh.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtyockdose.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gthtwotchk.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtvecvegcq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtecyciczk.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtipjkmhpl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtikvlrwex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gteplrivre.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtvinpjvck.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gtcwivrfky.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtjlmetwca.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrjdowyg.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtlxzfxxbw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtswkrpfuc.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtnvymtwqu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxylsfjs.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtwysnevso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtvisfhbfj.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtxxyzsibs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtivhxltgl.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtdorgiwnj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfihidzox.html

[Q83] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtqlxrjrei.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfltlwhwf.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtfvodwiil.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtccnkoweg.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmktgcxe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtjrkyubkm.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtvswwwsdl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gtjlkiaieg.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtcpcgphwc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gttiofijlt.html

[Q88] 行转列（条件聚合）
来源：http://dali.cheryme.top/Article/details/gtbxstfgta.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gtnyauemjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtslokkpbz.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gteqtdchak.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtthjwstzt.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtxoqeothy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtuojbufhe.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtaqnepbgr.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gtrgnpdvvv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvzcyuuul.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtyrbnwepf.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gtniwdwtzp.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtkugqqozg.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gthgkspnrp.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtwbbrszdk.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtqjlbazip.html


<!-- 参考信息 -->