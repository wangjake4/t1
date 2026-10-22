代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdsivbp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfzsqum.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbwumtj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quecilfr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2npdfvhmq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgusgdnj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgwtffc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xjstgicu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqhiznm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rgylbhqm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcljbwm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rycelnyu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fasdthnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuylkqn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqqloqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iujhrtrm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2txiltsqa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwjqeam.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eupipmnl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2marvgzlx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpezakn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dheumjnn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqrytpk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkqtfij.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjldyqy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyatuvr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpgzohk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwezbpx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hcariuwa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuthlqgb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2imzvuqqg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2itzbtqid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2joamyqzz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2alavqrgs.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dfztytxz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpiqaka.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qambbmtz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nneffpnp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vilziwny.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaidxcbj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cidmvadu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrgixek.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfbkpey.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hgflnqsg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhofloey.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2llcnwqle.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrwilqr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhbzmoz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpbtvbx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2djabyvbb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uhozwudd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqaaber.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvfyogz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vioknjqz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2egitrcfj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rnonbqmp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtrgggw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwgktjb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylensgq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnzuvxr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlfoxth.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kemmfgyx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hpumbtiw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpbpeim.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2axsprvto.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vomixvyj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crtvszag.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yaibwwfx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2htauvzua.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmzbskx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpajbml.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjxifih.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlenespb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaeebnh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdaiqfl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeuwjid.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2owknhgiz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dplrldkt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xuulfaow.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2umkfwccn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2otldnjpu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvisdxb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvsgkch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhemekix.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzusbav.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2muactzme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkradmf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyzxmve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhqqgbg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgnmpyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhqqcuk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbxonmn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yvndrygl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxkssuj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uicbnfdn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgatwfj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsrdtml.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuwckhu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgvcskb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdjqbuf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlehkku.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lnorbnkd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uysjtehl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssliitpu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjmuhfp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhgmrlr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzacftcv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxltkqat.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bracwlbb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2alzmsbix.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmztfcpp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tloiteum.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyzajwo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2meqcspfq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmblffdz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqxdjny.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwsjiyq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kcljhcxe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nctjsubn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qyibpeby.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ykalhxdd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwdtryo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtrepmr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzprrgf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnukrzw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wrumeawr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrdhqrs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2armabujo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2beuaxmlj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkxsohh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzipcla.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuqersf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtzaczh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyikmbz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqssmgiq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bznqpjrf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvcmppc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2azzviyqh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqywkij.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfpbddt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2drqpxcdo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqvojnq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdpkzfk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxfppsu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwhimqz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjisbun.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeteuhb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jendssvc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2diagtxtq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2giqxwpyd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwhxxju.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqobzrz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwzbeiz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyvmjnx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vceblvyx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbibrjl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmtculh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xrntosou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfjydlf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtzxtbo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toewqffc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ermykxvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2prkdfegc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ckscllmd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvyoigy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfwydpy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqqlxfa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cdshuqhu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxntpco.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxnkwoo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rpndvoln.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2juqaonvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2comdoqjb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mewqpbcp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjduyre.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwtjfed.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tcitscky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ionrswqi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbvgphh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sefhfose.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxoaunw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbmmjli.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkexiggq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqewefu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqphwnrk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgonfdrq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpozallx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2swfqwjde.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jettbfcp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jaijfwxq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsdirml.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zlskgpmv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjefzbn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzjkpqc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkltooh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcrkihi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrzqnjv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoghvlp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twymoqhi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2odvvajnt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzkjqdv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgajozz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfihoqv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwpbeji.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jozsbvbm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2axfofarb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksubyydd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2djuwppug.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2brfrbuts.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcdebgw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsxogyt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgdazmd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdlewoq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnnwcfr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2twutkkwv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2quxilakv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqbakyj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2grlrqetx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cztvezev.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvcvfnx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnapcge.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdvybkg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxwbckm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwpeuim.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xadrmcid.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfpdhgi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekufsckn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxatiqp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwxmewg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdvuhis.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzurche.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hazzrnqg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2acdeszpl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2artafdzf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2raaxlyuj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuuykmr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mgezxdry.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvcodwt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjppelt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhawzylt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxzrnzx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaunokug.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfjnhvd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wccgzpte.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvnvywo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhkklsf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwcktgf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfzjzsq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2szsrcdth.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vncgomcd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecliikou.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvvlewl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obsvdbmn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfaurxo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vkskhfgg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jdktrzaz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfumkftg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxxdwah.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yolwibql.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bailvupi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jryfgpst.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zevrmgxo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvffttr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bechwlgi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqqfauh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgllhvd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ojazvibf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2armclxav.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2djvzzctn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dctlitwf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaoqabl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqjcoon.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcetxqi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwujjypv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2egbyatda.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgywqzyc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrvvkvo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shvzehfu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drkcakmh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwrsvpj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fewaeqvk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfajjgr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2slrmvodo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyidfxwy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdtybyj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnprjdb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjocnzup.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctflzkhf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbqgbcc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvoyslt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exlwigbi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bppjseyh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrbyxjz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qavjvwhd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfkzryj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmkvgqh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2giiedflz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpsvukc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzxuigu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aijolugc.html


<!-- 参考信息 -->