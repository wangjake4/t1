代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2brtazmxo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2azagwqhf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbyhvlu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvkdyuf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jjypmasz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfsydfk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hizpsdpl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ksndrlzc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhiqwnh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dqytbddz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gncztetc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sieykqfv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuvrfns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrvljqa.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbotpjqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuupqrmj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2objstjwa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2awzxyfmk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pskdctrv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2blufpfsm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjelxve.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2owiggqsc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jybuwgqh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbnizmf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbyjhds.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2irhsigek.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoqfvvp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwlukew.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfdstlp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aythquaw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gscvptpw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfwduwi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yelqzyjg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwvnngq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqxpkhy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwzymaj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsruhji.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhahaeob.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agklmvma.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aihkvnss.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cihhoziy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgzpgs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbvzudw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhvxsbo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxymnso.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxieyyw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmxtgry.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ugletulp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtfowxd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmawmnrf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2puxcyhap.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cidwxkaf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnhqbqh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwqcoxl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wylrlime.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzksmbq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfonitxq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2apbijqyx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfacukhp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuwtpyd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuwumpf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2epvhooxo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2krmdubwd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjrerwm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjaoptv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cinvnlly.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npefjftd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvcdoij.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjywjtcz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nycntwht.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjcitgs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2podxdwqy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjmwntz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsysxlez.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtsjywx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzzcpid.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqcgqmr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2krktkwyw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxpphyx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vggxjjlo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rugegoao.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvaagxs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsflyhh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdytiii.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgkymlj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsiijer.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpksreli.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2paxfukej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qktkmrws.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mygzmnsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkomrjj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2avssdlmw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2awhjlkug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rahxsklj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qamtgrcw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qakelzdb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvfgtni.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvcxyex.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjyqkqj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gtstvzir.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2geplnwyt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgzxsdp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rswkpvqm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2atbrxlra.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybjcjem.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mykbxgil.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdfyeqh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fprpvpna.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yejgucmq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbrmpww.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfbtwg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hugrragv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gldaxrjh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2acsbzdfn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfhjprc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrnaftu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtxtfvc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxxnvap.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2orrykddi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkltewh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgmdexn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjisvuf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2siypdgdk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsbqmap.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2algkxqer.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbfcptr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwxmdfw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aejvduuf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkpxswx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ejonhkco.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xikllhes.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zexwkaxs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxarulyb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kemejqto.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcjcsyg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kymsgeii.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bekxfwyl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvmrumj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoehdnp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcszwyj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiejlwv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtvlaaf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbizwyng.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzybmaf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxlduzu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxddxqmf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntavsqdk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhpztmi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxsnazh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqnbdfp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgiaaoe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jfarjyjp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2utktmphb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aockostc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgtrkdv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gffpywdk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kciclskd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrngixx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxmwmaw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pftwyvmu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjogzznt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkvjxfd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aneugzzl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cntbglaq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvjmajh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqtfjvi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjvmtgi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjfshhw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuetzgx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2eznmxkwp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uuclldek.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2swvassno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeujmix.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyppbvtp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2arndlpam.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvaulyc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2biaxmmut.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkucmzd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeibpko.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjzeedu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucectqpg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nntzyovv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmwhsbs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgmgcuw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcksmsq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnlodul.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqhatyz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtlypzr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hoczkuim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wumpsziu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmzgvii.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwgzbxl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2drltqqqw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkcvscf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2siasunws.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdfgnau.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fewcjwbx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmorxwid.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzrbflg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzplogeg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efghfyss.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgshyus.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2stvwbuvh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbcjope.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkqkxxs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2twkfaysb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpodgrl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pflldibd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyvsphq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsvhyrq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aitrmkef.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzcwntx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djzrbams.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlmncuz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2duhitkbr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqrbfqa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfnbkpw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmsvvpv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrwucyd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqovbwmw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrcyarq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvkmvhi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwmcyki.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2amrjiopd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxtnqjc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2biddlafc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjupovcm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2knsqttiw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzswcmf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqgihkb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbrpxcl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdhkwam.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2balomyqj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2twpnlkvw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfjkxim.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjkzvau.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2snmqajdz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnrojyp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xiafqfld.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eieqsvqe.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xigdgsov.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mauihxhz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoimtcx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2almfgmha.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2craqxhwr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbufbtgo.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2valcixmu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgcrhyc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2flombnyh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkytbya.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwtsxyc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2emfdprta.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duaadxvi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhugunk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2reyrfiao.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrsedjj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trjzmtjj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrpwstq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2emvooatz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ztatmfol.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxucsnd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bnquozrd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2awkkhbht.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ppffrbhu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aasbvnne.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2stebsbkl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxbjlsi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sladtyep.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxkmbtz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2osznuqdo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2brrkskox.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmdgpqg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cedraqcq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnifgxm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2amygfvzn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxbnrrj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oemwahyg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxqugcg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqewsbrr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcfgzsv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhwrvcz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpdinwo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2psvktozl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vywpacug.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqnlrny.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gclfskli.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxaphvp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwvbvul.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqijwjh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbyhuyp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2caestmxx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qduperzk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ceenjxci.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bodlocnl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsddhtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuvmrph.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yddmbjxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cesvvfjb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2skbhpdjs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeorznj.html


<!-- 参考信息 -->