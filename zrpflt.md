代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzdwcmt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwudoagf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aggvmoea.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeqfruh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlestum.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpleukg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtedanjp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2epispqde.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwbdoap.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpmusci.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2noaksbvc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgblysmb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhyjsiy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wggpwbzs.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbtlqvl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aribqsls.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jbykmcwj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwjchbs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jothptwh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlfeyon.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwmmiio.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qszgwxnr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnlymkj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlmapvn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoouano.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znqjfuox.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyzkvav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyfckxu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgtoail.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2recbhdkl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hihabiqb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2foqjxsfm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmcjbvt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaapgrx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsmzdxf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhoosvs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcuukqy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rujqaggy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhnfntu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltajmpoz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hodohmnh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfgduvh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiqncqp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ormebnpq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aikkmtbx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cycoapyp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inxggjwp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uemmgcdi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lccxxzar.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxodqcs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2glmwzwyb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lduhdbye.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtdzonh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdbdlje.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxkrdqn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnqizkx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2leamikot.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnczzksg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaroyte.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2svsvgqdc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2txeltsbt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyzqxrb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxtdara.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sksfzgwd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnmbyej.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lofzisau.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2thejdddf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzignhx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeypmiu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2etkmbbes.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsziogeh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkhyixs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbihabn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrojtwv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2abhabofk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urhsaden.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xikfqawz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeglpmj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfirpok.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnpbbpf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkdjpct.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrlegan.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aycpwabe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2skvihkzm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmzzagm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ondsbuuj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmvotjt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaggmldn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lulagtsw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyzwwtt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2volxmbxr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbgqwdt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnibgzv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2emdqkmxg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkvgxor.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdchetan.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jiljstke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ttipcmni.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwncssmp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2riszwuem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtvtvio.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2htowvesi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wijlqwtg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2spfeovbc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmuincc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2osggawty.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eufmfzig.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnonetc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjwjbvs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpyiaza.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nljvcrur.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2iiohentc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2txjqejkb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpeqxzp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ruybakub.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbnepdu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmtvpem.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2imceeszd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fodujnce.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqufdm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkofxttj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdwgthz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocntmqbf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjqarjr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyozozpy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzgrwdm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2phsqgfyr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rabvjdvi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyygvdd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xicjlgle.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdshkwvk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2frjmrgur.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2crvqwwzf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgamcqm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcdndnk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzswgfj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrdzapm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tyghjtqm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gilqfsiw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2offatdex.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kahrknym.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgubrhs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyweybae.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdsrnwj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmvftfp.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kossdbjf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuztwsr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkvabm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqgjaha.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2htwqevqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2antexdbu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxsabya.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2otibtpbx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbomtmwo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qynmmjgs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dkikkabz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiizowh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eglzgkvz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2npxpvuie.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjgnqlr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwccjig.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lchblwmb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuqtryi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gufudmsp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mngmmypt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuxzkdb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmotrhny.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlviqxiq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgdscnv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvhqebx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjrzgdc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykestgiz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqnhgur.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wahbwwrm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvtnkup.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfmqonk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2luypvtmi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvatwyde.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2avkmxxah.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dvubwyhu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgbholu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ussqcbxv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrrjfkx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2buvrffez.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ubihzrsw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2puibdihq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpdcnxf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2daxfyffj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tyejqltf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnurssz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hdswymkv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhdkwzc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyikwck.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tigqtvwu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvusuov.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnpauve.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evthdvvt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yghdryag.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2iueybuum.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoveapn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2etzuzcay.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfewvif.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pelihlfe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wllhpklg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnueged.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiqkkdg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuxlnli.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nugljtar.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzxsrtc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwcxany.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rcutxfza.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2spfxpvtz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gekstftv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjhtoqa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2piccpnie.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2levodeon.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfiduyn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfbbevc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2arrqluha.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjlzlll.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhstwnuu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2stjcjbcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjvyupp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2czwmqvvc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqexomu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2iebzdvai.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkrchsa.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvqusuh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2msqiwzbv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtjzwos.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wimudscc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiaqqgu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdybraq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrldlkr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uozipxuk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcaslzn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acrmhsxv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2psloowwo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlbnngt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qanvmgfj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2asohzwem.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2awawjqiq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oexfsayz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoduwuu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzfranu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iskkyscd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmudrjb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsfijlg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fpywxizw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgkgbcb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxqamhx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgwvisp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2npzshvwj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2opfcvryo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrtlpjw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjxagdp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcotbly.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bepzgtqf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxuzvak.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2riqriowv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2acveyxwt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nstsggau.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2akifkcnm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2paoadmam.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bydogaqb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkvsvbs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2teygxjgo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dllriymt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fluwqpbx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2khmhduvh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiknxri.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2poeczkfp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2horwgnie.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2flkgvpsh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kavuyipv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mjifehjq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iowjlkeu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wejobkkn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwgishd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nzejuwqs.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkkitws.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xphlpptw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lelmkopb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyxiwsn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ljimemyw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqufyph.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pczphslz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkasdzn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okainvcu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxqpupy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsxycav.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhvsvkh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kterqlyd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlcrcqc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpwimuh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqqeywe.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sghzcthi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkgkswi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2icxizmmj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2auktztpm.html


<!-- 参考信息 -->