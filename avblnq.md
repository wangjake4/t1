代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tbponrix.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwgtqxn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2diwvfbmg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmuofqq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlevkvpf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gszshtih.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjukajcr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uigooxfy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmklsgsl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2svrnbdvp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymuxofy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvmtzxv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfgolkz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhdvonw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfsaalx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ioetyrwn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnkgekw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ligdzpgq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgwkdat.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaanatc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlwcrjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdohdvos.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvncndp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agrhcafm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsvtwkk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2smosqydt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tntskpod.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaqbjwq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzejlqhk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvenivh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgawvyb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2satmpmio.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjmbcvi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvkepcr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wusomhkk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpechcd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoercvf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2roziyqjm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2eimtfjds.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oweoxxrg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2evrmznqj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpqfnzr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkakvxq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcitslxf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuvssdm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2saujzqcx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhzhptd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqztlmxy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jwumfgnt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbojyuj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eeknwkvx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfekwhx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrfhchd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvmkigm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2owgqdsrp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jivzdods.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnznlmr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkewbxr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgctbcu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2moqditqe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2caxvqcbs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkubwte.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2brhpgnig.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cibdtqpy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cagfiaxj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2whtzgmzj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtctwmkq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpnfnbb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2razsbssr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvoujhz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cakaqnza.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjftyqi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqbdcxp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmltkul.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmqedwm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jubczmfq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofssqoxb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvpoace.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2imkcmsfg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmgoyvl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyduugk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2utxqkvri.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdwyigx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvgyjch.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxduuyt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2odnyketd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zojswhfy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2abrssmcx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qasynmgn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzubmhbz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zupijtnh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrrfyon.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjjdvvv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxwedfl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoirbop.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbiwhai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clepexjv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhaiglm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwfjzsl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jsovtyjd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuhlwcz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ejufgpup.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxxlbkv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdspdsw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yiawrxze.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgvfyxu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lapnfwjm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxebfzb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ucizwjbx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaopenr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpqbvxi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhnwmww.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wglcuxps.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjzakhn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2odhnqntx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwagvmi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oliprwsd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2agecrshk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbngpaa.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2auadjpad.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zouuunew.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2oiblsknn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsaxudz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yoodtnad.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iobfqcts.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhcjcpn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbqmmry.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuojmhi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fquwytgq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jpugptfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hltoohed.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhjranc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kclwzrcb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xuloqgly.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzdwnao.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qodyxcuh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qambjedt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfdkuwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpgsbse.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvujmxg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvzlago.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iemtmivl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enfmhrzo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yakbykvh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvogasz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmmzusi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyodjyq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xwllsroo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iviycyqe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaflvtz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xudyrnla.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2guzuhnxo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuzrcjx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cehuylwx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxchnwx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jixhqswj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qntlzpze.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hsexglxp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdxuyyb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzlqxjh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzsefns.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdysdkoy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdeukbm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjwdiww.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrqvuxb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhwdfnk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyktvnpn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2txwhithw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktixmwzc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlblfks.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiqvugh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mallsvsb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rocuzslg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nluqzgpa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxppvtdw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzaxbvz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zmosswij.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozichudr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yirwcdys.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxjsapy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mnltvjog.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwskqcqe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvspbdm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbgsdyw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmcswmn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wivsbrpy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iejbhdyh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcximrt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyvsbdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqdgbcb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxamihr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzrsqpp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2blbtgpte.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2axhqzfnv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbiksgd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvgarda.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwgmxit.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kykbftko.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmjiydm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yftjdryc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlbjogs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2amursfcp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiueunf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkswngro.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2noqcfbar.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2erlfpenw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djqnfeko.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2plnarpqo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcslfhg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iujxdehn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ulunzqis.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlfqwpy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxzsfta.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmyfnfw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwphgsuc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bvequzmi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2stgguods.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjsclus.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2folkwfge.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mjixfzct.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jczxizzt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgadmeu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkefxpf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2meptcvtq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlgybra.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2elurnbqc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jecrenek.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyldpgkf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zguleqmw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjdzuet.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwikiqmj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2chfqyawi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xljpvvxs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aozcqpjh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopuebvk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzilzik.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhxpozo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwwkseo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzppkyo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tilbceyf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rmddgnrn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgfbwqa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkmpohd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2saydyyia.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ueluamdp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2trxhdmck.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzswlcn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2saxiwzkr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjxknxo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2orzunngr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2besqqcki.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmjzcho.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nauxpodr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2besccymv.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuctboq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwknztrh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqazsreh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrefiwc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mvadkngf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfeorfd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whpcgdnz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xlibykir.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhlzixj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgqsnhq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2paegkhai.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2finvaiag.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2raciuuxz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ongyysoi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdtkqva.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwdfgsf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhnxnlr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbtboid.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zqixgnnq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iekimobl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyhjeir.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwyknoo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqjrvji.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgpqnim.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2onkvtswh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgnrxst.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqexuua.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvymrahu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2htuchohr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnvghes.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2shlqlwaw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbbyjdj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnchqay.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gserxzjc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2thrdohkw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qegmkqmy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kwytwrma.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mklmuicv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vecuppmk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqvzqia.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqilvlpd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iajemywa.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhnbinc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdcovok.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjohxitj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwoucka.html


<!-- 参考信息 -->