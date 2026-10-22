代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdysxwoj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2srokvlsj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmfsuph.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgehixxl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiikill.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2prmdybfb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvobdqjn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nooxmuhe.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtgmjfl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nznlpsbb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqiqdbx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jenbxkaf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2csimuxnm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuvvfnq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tesjoyzq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsijaya.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdkuulo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnscueet.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsytpxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cahfufaz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pqucbnug.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxyuncd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcgrgra.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpaqjaz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvmnnrh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jldrqljs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrybtdt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjszlfb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnrzyos.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuypkur.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppafmues.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfqmrif.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ouslpzhr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrvobup.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bplbledq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysexpkgl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjxxxuh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjwacoo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twsmyhky.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwfxyuh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyafdasl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsduppg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvuhfdr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqznnajj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yteukqdp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2creakzqb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xzespfdj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnhpawe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyjsgdn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxghgsd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaigujj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2thjeibeg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2onqjaqwo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvznhmab.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2buxwepjj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2muajcnkj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsnitwx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2koixhlyj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhypawa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vynntael.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpirrxk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2abtwxsfd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2crbhknne.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoncyln.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oguqowuw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcuotmj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rfonoydo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuylhfwz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqmfdgz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lirhwzji.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etorhmtr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnawrqvk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uynmnwrj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sewkztpm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ystxtjrj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tsghzsvx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gopoalpr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2quricngi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mdulkvkv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lduetkqd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pslitljb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdczuro.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xszslmuh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbjutfx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bglqxcqc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvexoqn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wtforrwt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fleuivfp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlubxbz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oiltbnth.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2neovcjqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtjclgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znlbodlb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2eddunmkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fouxsetz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzoylcw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2weerhodl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgopgwgp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eoafhhgk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgbqtgs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2whwincks.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrihahq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bplmeiww.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmhhlto.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2keofkkde.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2brzzbcpx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ankxemsv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2juejgsvf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zphjyiei.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhnzeld.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhmamzi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyygary.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhmspwp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2btnhverk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvyjzpt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aandgzwg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2szxkpuxn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvypwzu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwqhbzd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxhwkju.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqiiafo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2prwerdtb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlooqejy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzkrlht.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eqojdsde.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2whpcxlai.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2drexzeaz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdthtpn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2afppfjmp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnzvxtx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxnaunf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmqrqim.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeegjqd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxvloei.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2usvbzkru.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2saurxypi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2deygspdd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoydtnr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrerlsn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqhghym.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtislya.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiskazc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrrajel.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkcuimb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqktcta.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxftldtc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkhnpnu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2taijvpsf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcvoqcr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qytcyevf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wprojowf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hdquavqo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcnyxoe.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgoftdi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdlmsdu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cozppoid.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uunnrjfk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnmjivd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzdibgf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvmqkor.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kymsoboz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nbanwfwt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmghsyzt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tezoqwaz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfshazqj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mivfaczd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2antgjaon.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrivwfx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rypotcmp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkbjhtd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiflpuxq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkalgbe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnassan.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhotodeu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbyuyee.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqiizjv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dqevdfpx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uftvoihn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqufuqgo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtewkfd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaatpqy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiysqjdm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dneyyabt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eizsgvpk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsdtetc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbvlsoq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rucuwppr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2enophsoi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwqmzeq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjsgwjb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuuyvug.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ofilpnzy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cycvepsc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2igysbvtf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajehwskb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdgzbfz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mwezknff.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtxbaor.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yximmmwi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxqoedx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nknqosfu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2meuarbwm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lblbyoyt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bggmiqev.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2miqybsnq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mivhwxpa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grjrkfej.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tszjgngy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcdvbqe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsftmcg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2icpdmeby.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkabcek.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2feonxrwl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzmsxzb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmpomqs.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyxomua.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyzeeix.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrafwdd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyhmgev.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2foyqrngv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ganfhdyg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwfvicq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlillqhz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxojzcaf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2spalefub.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbamvlj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2igvnyidt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jjquptef.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwkydqr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gsylpqsa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjctfxzz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2swbfmykc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2elrfyatb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbkcwnf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bajxayed.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgycgxj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2owprozlw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlteocuq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iefqckvj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuuvhiz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmgcglq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ttokibms.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzqofah.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcseaqj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiaqleo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjrauxc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcclujy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtbvkna.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2inppimyr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwrjrfg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ihucztuh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2moshjxrg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utwdyyte.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbvsnlj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaloeyn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2araovwff.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyggpcn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2shjsgptr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2oanvhngr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2duaoslnk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2melkddlm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqjhdfu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrwxpws.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlfjmrl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2uhslhxun.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdoxdyg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwygvctg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwdfbfc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqawwra.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzggoxpc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmlgbtq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cepsydyi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpgdmze.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqdlzha.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2buhdmeob.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2audqpbtj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kzobpnse.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjayffp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bibpyhzt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cszdzybm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjubswm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iktomcak.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdwdbyz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsvsuof.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbloauv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qscuilxg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2njzdwpvp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dotvvvyq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzsxexr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrjyfkt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkjmdql.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2anpczndi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbmxidb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzuiyxq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqmpbxz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hycxdyxm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuhoblb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgxhipv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dydqztbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szrevjmy.html


<!-- 参考信息 -->