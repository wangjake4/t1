代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjvspdx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2sadcigsn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzavvco.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhspqje.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxjpima.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2esghwggu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzxwkoi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilenyrny.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziizkknt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnllrakg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2szcwytkr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cugwgkre.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwrfhrc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwtptap.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiysgjlu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pooljech.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2driyqnyh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrnqgjz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tysxlfye.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2grfnrgoe.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mphnbpvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igllzflg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybezawqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmsyydp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ammfolhz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zocslnna.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2psddgmdx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwurwxu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvgzqgw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoylebv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ngddxtcz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzwhnkx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ondywxfj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwmxzfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqdwgpc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkkmins.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sxylqxxh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmknqeve.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pifmdyvl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lldusake.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nadvjzjb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbsscfj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzcjboz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmlhxme.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gceuwqjm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzeywxq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuujmapf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbfxoyc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2izabgobg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnvqkli.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlrwzpo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlgautq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvinzwp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mozpafgq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzimgl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vomvdihf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqifjkv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nttvuzqm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgqkoco.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfetedem.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2srvmnfus.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpffnsg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2isiraebp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gamoklqf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oupxfzrd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2aeofkwxt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfiwgpk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaqyyvc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2edxmtebf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiirmkb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iekrhmlo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbvpiwg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbbfkyx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldywsjry.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sscwsnwg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zaukcoey.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhlvgmz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoafolb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pijnhcvx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbclfeu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obpsdxda.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoyyzhn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnwllng.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkavecvi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzlaruv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gycybtiu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fzobiheb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwscucx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwgjmgh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2slkbxmwi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpvlwpo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvndgswb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2phvidebj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2arivtvlx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jciyrpvm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2afxvqwvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nixnjdzb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2omgxypdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjgaqmc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfpielb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xeleivsy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2krunshac.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fswujxsw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuvemil.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fliiyite.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjicuao.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvtdkau.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuvfclf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfbvxbs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzybqps.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yozwlpwe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnqzdyz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tstsnucv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2edolnvih.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgessft.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jztysarh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmarhjcw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2etwkznra.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rskqcpdo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kneiyqcn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2onhybewo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ditqmhyz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dossnkns.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zexbpicc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2edlnlgwo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxghgyg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2likgprdu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjyuepp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dnonawhr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyqqbah.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jebiduae.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2iydcaklf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdqvcro.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiddvje.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pufagstq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwsmzgm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdggvvf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uehbzrmd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxgwfne.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwtrlsi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceouthyf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdblqzb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2doywrgan.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iurwywju.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snutwjar.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqsfyxj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwanwwee.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2knweocfa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyddiae.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnsdiva.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeogjnyb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmirklp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjscpyc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdbkogi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmarvim.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqxxnii.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2voxfgtit.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpmkosf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvtfhae.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zoojwxrj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ickhvzbw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ausfcdlp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hogfhzgo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aovpudkk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcglievw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2unqidhzr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2izvyknvo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqrvkad.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyvlosz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqorwok.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhwjety.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfcbbbq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jybhyezr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzdzczj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpoxfwl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnowuiy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zzybngbw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ittpvzlb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsjokey.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqtefny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qprllphh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuehmfxm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uinouzaf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyehjup.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnvsjqb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdrsyss.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiacbxk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gumyhdnd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoqjxhz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiutnhm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlqkvyk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rjokwwbx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjeyqky.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygguvejv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2meggheod.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eldxkqlp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lepfvesh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqhlfke.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyirqngc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xijqwgel.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2njknbxbl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oasztmzs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpgcoro.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xszopqfw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyumtqu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiicesng.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bejojwjf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujokpb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtjmvhj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2urmcyeyk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ndktuege.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsiuxzf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oawwqpel.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylagdax.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gssovkck.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2opbfifcf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgkcyfs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqxdfua.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnajtsfz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqtcthk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jopuxkpr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhyhvrq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwewblyc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjkaozd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jeevcmgn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pidgaina.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvuyabb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwqatbu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfykdord.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vghjdxgg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxqneqv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kleaqcis.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxncare.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdirthmr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqobmqtl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhpcsbo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnndseel.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfbzdjb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufetahdl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbhjjfd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdraehy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hopjorfz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtgnvvw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcwodmj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmnmgph.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oipmtzvq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bpucnxwr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvszyil.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yktjpgto.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlauuoed.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2llchmoso.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrwoqtk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yqycqbjm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgtkalq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbmuvcu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpehiss.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kijsbosq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfmntfi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjjwapu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rvapdntu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxscbcgk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2saqmiysc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ijohpraw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qownqpkt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgywqsjh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzzlalx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wumegcvw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyexoce.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tamzxmev.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhnxppw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzivmctm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2idwrrhay.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eynqcmrp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudururt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kpihhcas.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqevjgm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkovkbp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqlcqbx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ztabqwzi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2meqauhui.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsavgiu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chuedsfh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2voanwfig.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnylxaxf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmcexep.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lepgwvlv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sybiqprn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkditjsz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zrejkyie.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddratqvb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rzppfain.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgfewup.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xzflyhtr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2khwysgto.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sttpszim.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkhrued.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuizmyd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uxszidgm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pavpcbyf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtfgegv.html


<!-- 参考信息 -->