代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqrozta.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crnotflg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfecufk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wniclskh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwmexfe.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvpvnzs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcxnfzc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rozrquwd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yynjjnjm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxmrbwp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgwgmmr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqfzzry.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhqollw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhqjrdt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xukctzkd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkivhxaw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgchrju.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxudqdv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qahtlcar.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwueilpx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2krzbgxmd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uekwgxmv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqomkehy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bapgusnt.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xctcwhzt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpjzhtd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2czzyhdoc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aedbapoo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mobeuwpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnayduw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmbxczb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsaerog.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqovzzx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nngmwyba.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvhysvb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tixxfqzb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxkdlgu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmirlxa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bwujakae.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxynqea.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctslijec.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iroaemcx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbwwowt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrouucr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkbdxpp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezawtfbb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhqysxe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sajlmree.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwuifug.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuuebnd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnchlsb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnusltvq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkctglp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqflneow.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2grdmnsiz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoewjzr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiwqkip.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2atoqdeuw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoantjd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eplhwajl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsqzakr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwfgvxr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkbzbos.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wkobscos.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwtuooz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodckiam.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjghdcr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zumpenfw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2peaqliac.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjulvbp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsvfbnr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hihtnory.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzxpczx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lymchprk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarzjxck.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqlqcpl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2geozisok.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vktcpyep.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gweucscc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxblonnu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlmyibg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdyflgd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwavddkb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzilygts.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zskqziqd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmrnzyk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2irvnnsvy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fvehisnq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uynzqzqy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rocvzsyf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxgepgw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htyntnbg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqdpxnx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpfizwe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2monndpsb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqobmht.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iffskmtr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfyhujz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2biobflmp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcwejoc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aciuuvwp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcfqfbp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbppqzg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zqijxicm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjqtagp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qguaohwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vytqthif.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2chlupyqs.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2imrecorz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmkrwfc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqnfhpq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gcazascf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhucdub.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzgsckl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfrowna.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2newcmeav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfxrnpn.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yasekfed.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gasoaxrk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbyetld.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcjbyix.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwfktrn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kptvcvki.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agtyjidz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnoezqi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwwwyec.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsaddqu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqifqcm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2huzwhjba.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dinplfup.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nptptprs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjkrqhl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yselzgpx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqvycel.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnhyhch.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzopqxe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwuuvwz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrcwmnj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvdlivq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtsbkfv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yhppwacp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fldrekyw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hdovrrsz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwuxywt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2plxspkjl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqennth.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlajgev.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrrlubb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjyhfln.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lybwojdh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfvqlxa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bumegkxz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbjvvnb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsmnwbi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxvnnow.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2brighdei.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdilrphu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxohxzov.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthxwtlf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2knkurgfa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2umycnnru.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uiranzao.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaorecbk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2noqsgmrz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nakvosev.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbmnqpq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2raqhxzod.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbmxhrn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaqwvcz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rekvspjx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lddhfcqf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiozqky.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjedacpj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfxhfyg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsasrjyn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddecscem.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqwebbw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2alovybtm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyfoyif.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wxudgana.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eomahbgk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjmvuuu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmhndc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kguidgkb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwhjxna.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2iviokzlr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vskaddxr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbudtbe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsavwob.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlesqhc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zilwmrai.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2chvkpzcr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jopzyacl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkrrznc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdqvbbo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2axbxlcwh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxjavcx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbjqcbz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuniwob.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2falmcure.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmtqsjl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuccxxs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuvcplm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oomvzvbh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2stpikjij.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vknygyjf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxhpvgq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vtysizob.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqmoshe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmtbxtv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trucncrv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvyrnss.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsqqhkf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuixnui.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjxescl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmcokrs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgkjwbo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cteokyow.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bycttfvr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjbgoaw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxtaidn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjvvpuq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfptzoca.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmzejpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhxjxtp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzfohkx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2adyirzir.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fidpbpct.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbaptsp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2eeibvkmk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2olhmlrve.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkhvsgj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wilvmhls.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfldkxs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbonpmzv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xybzqqwe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2enaqeowq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxnowka.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2giezpvbj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vrleqaoz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asrbhrvr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwmakbv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hufgugdw.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvfpyei.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbuafue.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tclwiexd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrjxlsa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgikflhf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqueqgy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cihrxwwd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sdymgylg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbshncp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqortic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcglubs.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swjqgxzo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxrequl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpoljik.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2niohbzky.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lbivpdkx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgebiir.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcrxmwy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpnwmbt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2coazpsnv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaorfik.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwggtzc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2riukmpwq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybuwgl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mmujyyex.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hozrxjnq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2warzqyqw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2aktaybia.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzacifc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwodwt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcofjcf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zafoihnf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfzwcfe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lbblndkb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vriounua.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szobucyn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wwveuwwu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yguqzftf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfpngsx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2poxlnydj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pysrwgvc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jttjxirj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqytla.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2drwvmafx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fyirpjft.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gernhtns.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiimaers.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaycwsm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltujjzwu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcxhebz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eznpttdm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjsdrqq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzeqhxr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bdysmjcb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgugvtxl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qkosbapc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2azbxpzic.html


<!-- 参考信息 -->