代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fagjvriv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2akyfaees.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqqvmdx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfmeaid.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhusrjyh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxlpmgw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmgcmjw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbztalbi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ccykgjdf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2igmxopli.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgepzsn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqcgjmf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sviceogj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdrprsf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xxubasns.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2eobnzunm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2syvryrpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjwphlg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiqmvjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdxmeel.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pvftydgp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmiadmv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vctpzquh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhwhawh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxbfoyv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkenygyw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2clferlxg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpckbrt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2inccmtgm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nwujemvi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnifxlu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrqfsuh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkmlagz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkqrked.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfvqobq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2upmodbva.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvitkfb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vobxgnav.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2niztjtyn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmixwml.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubohewec.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pevshsrb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnrwbda.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwfqjps.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pchxokxq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbrqygf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ffozqxtv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2napngriu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2smnhtpoe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sekzdrer.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdmizzf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rpspgqhc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2evwjccpt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoqienh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2awmkalvh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjpfyfx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mduasnby.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgcmcss.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuaydxp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jifqenly.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoxavvz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uqroaree.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafjjoys.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2azoguykl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zwplfcil.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsvwxmd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sexscwda.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgigvudt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwkgsuu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kepnmgom.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rovvpjgt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwiusqi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrhesdg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwfslzd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dudpyfvx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdbkuq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjscsuba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiblbgo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrhaazb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2revmbkwj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jntqklsk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtfdcdz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjryiei.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2samwtqae.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfiqpyx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcxwisd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hayvyuph.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgzuddv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjivlgx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwtgitl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2scqhnrty.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zenckqok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbxhzjt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlhydpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmtxxkh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkejfihi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfxkmmi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuuobtn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwiepnw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhsfkpb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sllcekaw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsqnseo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyfgvwb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnelzgn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hihsrryb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzexggax.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsegmhg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2sakbrlmv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwojzcpy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2srfvmdjg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuxpctj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exkvahbw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbbwpuf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2autovehr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lookilov.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrawjht.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vicjpnkt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2whxhjvqg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvwrel.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbittgr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2izvfxrxj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvbeoac.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjmabuj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxbfiua.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpqaccc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jetpssjm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2npqbibql.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2frwamarj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfufhtt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vpabahld.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jvonmhme.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sndaeuei.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcjuoya.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2alptqymq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gokwbcad.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ouukvwzz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eapfnsyk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pumsapdq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgriovio.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2udhwhseq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkmoxtq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2albusskj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfidslt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrgdvrh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwfscui.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oduwluyl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpkctsx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2morqikrg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2grdeekoz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qetyfmgm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrsdscm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vubmzuvy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2luhallgq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fapjkrlg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uodpgqoz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ipowyywt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsjmocb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2syfelpks.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpigdkur.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhmjiio.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elpzjlvb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eurhphfw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acinbqzg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqulrdi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpiwuba.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcpjigt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvekpuor.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdweaqj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kupcyhnh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrcygwc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqksevh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsbqnar.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sysxvumb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aytccqtk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxdmfen.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbsniqf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2owpzgqki.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzvcdfr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnrqog.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rokiaomk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzifckj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvldggl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ciybnrqb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vddkyidv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhevwtmg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfigfwdq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jivkrdgl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2aheqpzwb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aburqnxz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2spxlmtdm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmzoxea.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbgdhkp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mckrkegl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbggjkz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqxeyua.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzdlaxe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgivjbu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmtjmwg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdxsjqb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsghgldg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zteltefi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsppawup.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2roxrttgj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vszuakkf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqcbigy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2spphwahz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhxlheq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdjfdyi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2maxnndkw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfmrrik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zembifus.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdygvnci.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwlfmri.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuhubmz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwqittr.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvoadq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrubqmo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2njseywgr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2znghopla.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwqdtuc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwbjmsx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlqvtri.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vprhstji.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmzpnwf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sttfnwoh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bahlonzj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdodvli.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdqvkhn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjedycf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqxtdhf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzaiewz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcjccrc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqdzsdk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2csytrszd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2etugvguh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqylvqa.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiwnuth.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2reqoqqij.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoybvxy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrjpztk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbscpxgf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiaiqsm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxezbzt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaipmpg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cunruruc.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2flecfsos.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2chqmqgxd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2opxvmbuy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhrqame.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uidagadr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjupodw.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smotkubk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrhhcdc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kilyfptr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2djsaggla.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzyrihl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmgbsuj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xajykjdf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tgapsknt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2forxusqx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdyxhgy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eptvagyx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2crngjrlm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oeznljse.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpgqpdq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbslipg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygtuzhb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ckatnnou.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrltxtm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2veznfsoc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpihfbt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2amoxcshv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsrzrui.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkyqoeg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2trtofgvr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbwcnux.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2woxjwdnp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvsugyl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iirqnusd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbplzat.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqvgfuu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmjhjbu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smmmwwia.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzhkwsq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmymhlf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsolgvd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xadatgoe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nregykrp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgyezed.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdarsqp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiuiaff.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2saommnuy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2endsqvxm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2amhsqyfw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvaepkp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyvmyyl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ppriahlw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dehfadfv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxcmqal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vksihgqb.html


<!-- 参考信息 -->