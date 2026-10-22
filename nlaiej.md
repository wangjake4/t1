代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wabywisz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmtiutl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmlntth.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhbeyat.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mubffjeu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkjnxad.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awfzrlsq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rapianzn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfocvmk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhdpwir.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqlzvoz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mifnqphn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2txohswdo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pujhxdar.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2olblazhf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qawmsuzq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtwflzd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2oadsxdbe.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqroled.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcncdxoy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkfsnzs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2worhakco.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aeafeocp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2evyuoxss.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqeeyif.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bilevhtc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dluikbio.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2eembpohq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjgglvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwipgsj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omnnzygi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqvqoij.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2itshyqke.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xrixqtqd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2erybsizf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2szzcydaa.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxamgysz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kovbexhp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wnumedza.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpjruee.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrlwywi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uuftfnvu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvyjcta.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrlkqas.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2efeyqxbd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdbbdoc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfojvhn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncioqnnj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2scgitfur.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fprfsnkf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gyftaiks.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrqbgud.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bswwbead.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxkxylr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxwhuvh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2thbqakes.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nyieimca.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvhwrvz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxanoxk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtjkkwd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjkgtld.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltereahn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrluthq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmjjiti.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2brkgbyga.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gplftanp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjcxovs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tltaqbwq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2oiirkppg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2crigpdvt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtxxgpj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvecsco.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjluayj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2twnhalrj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhkyhnw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvyfuyh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xoczbvbl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2voeuspkx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vottfyit.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjepkrzj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rywxtpkh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myisyoai.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhlsfbk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ednakhzj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikhnayr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjbzhco.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2diloclbm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzemqgn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeumtty.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oplescqx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmxcbtm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcdgcmk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2baopihrh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eokydoxz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2epgjfbdh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uayahzpj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmlphvn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eemtpssp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fbonbmxf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owslnbok.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvbpmgl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2adjmucpl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbispbvo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsdrvmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dawaivhs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfacwfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2johwgskr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sublloyc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqhyhfw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2flfokwiy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhxfrhu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sathsdmb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuzfaht.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeizyahd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ucheaaxb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqlicyg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jljjjqpy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fcomjgcz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtewzce.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2erpecpeb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbltbfp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxmwfpn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vglknqtl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoekctg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjapmxtf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2inraowiz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxcqauv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfijyxuv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2aasykqay.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqaunpu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzvbvtt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dzobgvwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlzpokc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzxfmck.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjfpmes.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vveyghot.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkhfwoy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnwhshi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2apcjkkuk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2klleryys.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hugaedza.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zzclcxmn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkqukcx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tbusavdo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oywfezlr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fafoirhg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2upxfcflw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwiyxkw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnbspie.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtryegjs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgneiir.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2znqyackj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecihvgs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbnjelh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpsehob.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvejorl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtlsibb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyguwsj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzjsuxc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxbcocp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pibkvozo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lauqdqvt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sadgdstr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2czvrkdcv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpylshcq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kteqzatd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdhlsdg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoljfoi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mztmfepw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdanrrg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhjawcd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uetelhez.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgvlpgo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2shsgiuoa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwnncqb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cepdcsqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blojtyex.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qeubmtqe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzntguv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbunrvv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2awsaozpk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dapgfsjb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbaffgf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvoiuxp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqvqpoc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhynkcv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bldeypxs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiswyyv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sagzqwab.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjclzpgk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgqaoye.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqtbybs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfjztyj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrohfpmz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2acknqsib.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajggawue.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnzfbzn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dribtqqs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rldhywuu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbivlgn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agzfrxsu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfywbkvf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggdawvk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hptmufdx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oximqbsp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oveecmys.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kperucnz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pufiluxq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtepnhv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gffityvs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfiuvgb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwguqya.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzbsaxu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kojymaul.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sjusrthw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2krbrdxlw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qniyvbba.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdpxwkn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiyawvz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwsdrsq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wijvulsv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dthbwfme.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmopsriz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wughwjtm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmwjmen.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pruzfbum.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwohcayl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2defpbipz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfafpiwu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtyhnpo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2muokkkac.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyluxfi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlbnvqn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbwwtoh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeuxqmw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2olhneaew.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2idipnmnj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2stgfowri.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoshqpow.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2znruzvak.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrfvfkj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwxldhz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atukmzna.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbeyxiq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvunygmj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpthvdd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iepgmlok.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kctiheaz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvlpbpl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvlkujb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtbnuwy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcrnqdx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmldvozc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnbmsva.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qobzydfn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lncbfmgz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2awcjkpgu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoaepbk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gonbozmh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttitxrnj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzrfvbu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuunoke.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtuswrb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2isymgxkf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gucdpnpp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2aanhitzi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvqrdsn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpqzdao.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsjruks.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wneyajis.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2itqicimj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvfmohc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgrtdyi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gngsfdew.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dcupxxou.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzifgcz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtsdeju.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2techsqcn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpfissw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kcslacjk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pvinlkwu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eijjfqfi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cinnnnfw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rhherfxb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqnhufy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2prjklujw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2txcxlalc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2utyrxffu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeirplv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrfgmef.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfnkzhi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbddvbdn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2agrwnboj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrymusny.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxmpido.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfntzzmf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuktnug.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqdgdmp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfcjnva.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdtpfbn.html


<!-- 参考信息 -->