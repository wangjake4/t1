代发 wailian999

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtdhkforig.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gtftfzoowq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtomaogauf.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtabxczdcb.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtzbkcviyh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtzrwisdui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtjpviwkho.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtzdakcpuf.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtcdwcxfen.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrreefkfq.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtchctnqoq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtatgdwiym.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtbbhwkgbf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtargbtnjj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtjmzsakwv.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtrnvwfiky.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtkalgfrwg.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtjqujcnao.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtkuiindfe.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtavhynfca.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtphqvpter.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtxcuuwzow.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtzrznvfha.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtflrxzbzs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gttqjhwqrq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsmizsri.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtkzhlpkgp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtevrgypcs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtfxdetonr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtqsnzouuz.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtyoussuay.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtvvdcpmzg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtrvppooah.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtmntmknjl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtfkryoebq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqulzbfu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtwnucsshv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtivetasmq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtuybsmxdi.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtehkznfxd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdtlaeox.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtdarfugbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gttufobnze.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtgggcjedh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtmmlikovo.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gtnxtqkptf.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtkudypxuk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtbuhbxfyr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtnsxjukil.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtsprdoeeq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtblrbbplp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtjmecsrwa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtihmlfbyp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtqtbpuysh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtjwchuptt.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtdtipfzgr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gtnbgnjmnr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtauckqajb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtopcuiuxy.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gtttdhadtd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gtmdzjjgea.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtjatmohuv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtteysrjah.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtutpksdkx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtbkzadhdo.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtyililpxv.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcybzolob.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gtcaiqxzjl.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gttcbswihc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtbpcqgxda.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtxhptpvnb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdgdezmy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtvxizflio.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtalfnvdqm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gttfryzewp.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtdrwxyrmb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gtxlrgcfpb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtijtecxgq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtgypxnpbv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtrngcjqta.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gttkirzumi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtbkfhuisb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtxcihhlbt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gtjfcqvouz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgpkftllh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtwaqvuziv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxcwyuyqb.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gtnploxhsw.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtnaduobnd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtpnferltr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtxsmqsilr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtlfmvvkim.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtqpusdsiv.html

);
来源：http://dali.yongpay.top/Article/details/gtsdvglwjh.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gttiaswqmx.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtfyjviyxe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtmthtknia.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gthfbhujyf.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gtswwjiiyu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtsitqwolr.html

);
来源：http://dali.xylfe.cn/Article/details/gthrebtoem.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrdlxkjk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtckcdfpsd.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtkcvazsqd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtsoosyglk.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtvzskyiwh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtvpvyzbcc.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtmppcfmta.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtsmjhfton.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gtzfqrfnbe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtjvowzzkt.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtyjackkfy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtvgayutkr.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtipiduszs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtiikddjoz.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtygvkbtol.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtgjpofpyc.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtfoigmopf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtaugfnhgc.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gtfzuscpia.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gtafrqjwnn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtjrlmgkdn.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtbgheervb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtrtrersin.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtwnawunpa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtntgudkml.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtvoidcils.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtftiixbug.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtaduxfnkt.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtlfdeqjwg.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtvnfuyzxz.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtyntwbvyj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gthhkjfzbs.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtgymnaajd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gtkzliwlwp.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtkfswhygc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtzqracokl.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtykgxpifh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtskropvqs.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtwkacpsct.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cucudq.cn/Article/details/gtfqmgfdbx.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtzgezxfct.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtxemrpevg.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gthnycvhjq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gtobcnuyvx.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gtyhgcmuwc.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtybyosjfr.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtztmitrpu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtnvsnhnzd.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtfprgunrn.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtiizdaqhk.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtbcbcvugm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gthsijksfn.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtdgmpkmgm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtclrtixjd.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtbmnjhrac.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtwnplzyfc.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtinfomhtf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtflnjtmrd.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtgmfqgizv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gtrjyvmsbt.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtjyogsanh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnwnrjba.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtzvytmhlv.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtjwcidpsy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gtxquxfebl.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gtqcbyplio.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gteicpnbvj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gtaqfuqxeq.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtuoticyyw.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gtgbbpsqmz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtkowpyagi.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gtpslphvcl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtwxkjqadu.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtfxqsotqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtbywxnhze.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gtxhapovmx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtlddcxcvy.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtufoolpgv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gtyobwsuun.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gtspymmltr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gtbmywklxr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gthsfbhjxa.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnqmselg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gtgidqvdah.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtodyvvbxw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtsfgqdpkk.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtxjtawncm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtqbkxzxav.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtivowjoav.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtoworwedg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtqscatvaw.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtiwsxmazj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gtbbksgddy.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtvxumkhjh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gthsnqobhe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gturdvkxwe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gthlkzgqzy.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtntxegsht.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtzbnhixwa.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gtzehmgiyr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtgelgaugj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtbvxkumnu.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtyxfxtmlh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtjyrhoukj.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmsohdkg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtghkkcnki.html

[Q51] 用子查询更新
来源：http://dali.c1oappe.top/Article/details/gthlyilens.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gthloosntc.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtbepfnzrp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtjthzvlvg.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtffhxbiph.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtlntjxwjg.html

[Q54] 清空表
来源：http://dali.ivvv.top/Article/details/gtnfxzwlnq.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtvfkemsbz.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gttsvqxxae.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtyvkxxvnx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gtyhrimesb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtqhrdndag.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gtuzgcwzby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtegevvodp.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtapofiesy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtbhozwwyk.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtjmjswblo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtneoaexho.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtuxdeacti.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtireuwzrk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gtjbeahrsi.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtcswtwqlo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gttyfwmmvz.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsebvtupu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtsmbihucg.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtasvmhsqc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gtwthegpik.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaspcqork.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtvwyvhcvw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtajfbcwqv.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gtuzbfvzti.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtgycczbdr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gtddpwojwl.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gtmhdvvdwc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtuuhthjvp.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtqwybswoy.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrfuehsc.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtoorrjrad.html

[Q69] 查看执行计划
来源：http://dali.chenzaomai.com/Article/details/gtmgomwpub.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gttutmwuox.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtuydsinrn.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtjqmpkiqw.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtemcmykjl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gttgynagtd.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtgmlzxwqm.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtewguvaqb.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gtigmnkfod.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gtngmjmcah.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtivlqrwir.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gttakzgbwk.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtgvsuesqh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtchdpuajd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtdoomuizd.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtjniaczgg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtnnroxkod.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gtycjhtlev.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gtbykvmlbb.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtqsspkvuw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtxxypopqe.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtdonvuiak.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtxwwoaqeb.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gthuviovlw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtobjwdlpj.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtdbnvtfsm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtrrokimfj.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gteidguuoy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gthjsducyd.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtdbxzyauv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsolcajbt.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtadglrkeb.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtnqzmljhu.html

[Q85] 数值取整
来源：http://dali.tian-w.cn/Article/details/gtrtigfggj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtpvrfppgb.html

[Q86] 读取 JSON 字段
来源：http://dali.guowangkeji.top/Article/details/gtpkybjasm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtfffhestq.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtfhtefgjb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gtlarldvlh.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtrrxcirdb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtohjctzsi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtnkqfjpod.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtkakuujoa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtykyichtw.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtyqrlgnqg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnkogxil.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gteynqmmxr.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtopjhqefe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdokxbjjz.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtguibrwql.html

#!/usr/bin/env bash
来源：http://dali.wangshuangyany.cn/Article/details/gtwddcpuoa.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gthqrhhfxj.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtgrycfgsp.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtpfphehjr.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gtvtfywbpl.html


<!-- 参考信息 -->