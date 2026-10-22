代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtdlemnctn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtlnliusni.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomidedva.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtalklekol.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbxwxinz.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtwawdtbub.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtuqvnbarh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtxeesglgc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtibgroxqc.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtuqhukoyi.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtmngawdyf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtywfseuok.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gttanccgin.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtpzvddzcp.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtqrnpnhwc.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gtrdbdyhib.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtqtujlvum.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtadbkxcos.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtinnptmrs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gthqbwgcpm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gtxrvigmcp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyugpiwgm.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtwtbhxakh.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtddujrlna.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtkrvtrosf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtlftntqob.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtsfnxgjni.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtkwiaqnrc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtdjlgsujb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtywuxkofj.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtjacqikdw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtyrtnjsko.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtfcgfpjxb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtdktqwlmj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtpevvenpw.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtrzsdvetm.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtuqkqjphu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtvaxtargy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gthwykzdpk.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtcfbtgpqw.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gtoujvjxzh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtrcxteuro.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtslmrbewt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtfbcmtgak.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtdxkbesha.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtnicbyfey.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtrofurudv.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtcirkrwcd.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtpxqriwpv.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gteipecwat.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtpytapsmg.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtpbboztkp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gtbxjgkezz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtzgjzlwmt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtehkwmdci.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtytbpymll.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtojgudqnp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtvdlncnjy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gthwhtryou.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtytkxuktw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtqcrsrxyc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gthbuolnkc.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtqortehsc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtnwwsjpoc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtiuckcwuw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtdhaugquz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtciicaqsc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtwjyqvbkr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtyqnjtghk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtujqgnlex.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtfpssqxqz.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtglujjevm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtwnyicmuo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtoohfulvi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtvwtkdtyt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtyuuvetrz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtexbvyayq.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtsfywirnj.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtfryoggai.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtdoqwkske.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtykbobiaf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtstclnclu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtldecvcam.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gthakzagwu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtfrebgvse.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtrsiwzfej.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtagjhvdwh.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtivoyoftl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtafqtxqhb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtnhwopeyp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtjuggcjaa.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzvpwfgjb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gtvttaaiks.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdciteqxk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtjnnuuazu.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gtgifzhisa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtwvkceugx.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gtebfrhbjf.html

[P07] 防抖与节流
来源：http://dali.hnqzz.top/Article/details/gtjjdtcbay.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtnrgsujho.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gtsukbqgbw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtlrhfdrfw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtuetqlzrb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtllqhppdh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtkrnctefx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtdrzeepcu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtynkxockb.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrrwqrxx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gtpcagvzjz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtvjfkvwxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gteebedvjh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtkgdrozhx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtzjqyfdnb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtojwbdifv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtlnravent.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gtrsahbquw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnabcsnql.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtyyeyuneq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmrmrervq.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtsadhugka.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gtvenilfau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtynidlknr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtdvfjypru.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtvixofrva.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtglfijpcw.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmyofqfn.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gthaoyrbix.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiorccmry.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtywpsexie.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtarjsaccr.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtfwbeifsw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtcsiqucoa.html

);
来源：http://dali.hammf.cn/Article/details/gtuaxyqnix.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gteqqmcfmx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gtokymmcer.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gttuwkfupr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtukdulkuz.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtxxehfhyp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtvgungyph.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtvlazjove.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtowmapivb.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtkxrmuqmy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtdnceymfm.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gtxrtnkhms.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaxcvkcb.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtobsagvxz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfjajkum.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtebtygndd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gthkgmfqhz.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtzijmqevh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtwgqoobvc.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gtztyeedos.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gtuwreynrx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtjmjmbkcr.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtbrfnjmqh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtyeekotos.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtqcnzsiir.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtwvwteokr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppkfxrry.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtunaiwqbh.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtjpqvskqw.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtgzqolujm.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gtrbnezrof.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtqggnbgpg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gtavredfxx.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtcxauynym.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtttsumwgt.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtlfhyohxv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gttbadaxji.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtfilmzqdz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtqfrztdnd.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtbqxlphhx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtspxrmieu.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gtrefkowfq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gthjaacbne.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtkmzreeko.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gtfsguvbru.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gthdmfawfa.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtukgrutjg.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtfutkdugp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtnbznijfp.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gtpkekpule.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtzeaaavqe.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gthaestilz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtalvdplfu.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlurknxch.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtdhcpzwqx.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtavdwvttw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtifyximen.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtfsxsarky.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtynvftvas.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvlooymv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtfgudjkwg.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtrbxibqao.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtzhfuqejm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtbffdfvtp.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtvourxajy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtqdbeqnho.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtzkwibznn.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtxowfcljy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtubfmcufi.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtyonvnsjb.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gtmjroatsq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtqecfeesw.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtwncvqjex.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtajztpblx.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtmuhvrvrx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtuphngihr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtdeiqnoob.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtjcozlimp.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtvunvgomm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtyxvegkqt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtfwrrdkra.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtdytoypry.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtybnampcp.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gtbifnrpvl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfxcsotp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gtzmglqbfe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gtxvjnuowh.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtfuvrfnzm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtryktzzei.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gthbqertbh.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtyhqwfyej.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtxopmgxbj.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtcpojrwhx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtkumgcaic.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtirrvjbhv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtwwyllwjt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gttaokwaak.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtprfdhupc.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gturlifoyh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtmyeldrtu.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtptmycgal.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtivkphdjz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gtjyqqtyii.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gttnqltvgj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtztebgpdh.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gtkcylfsgq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtyhgzgfbx.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtbuqkdwkt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtuviglvgs.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gthivataap.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtqiqiivnw.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtldiputqq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gtxbxaerqh.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gtddcfoqjs.html

TRUNCATE TABLE logs;
来源：http://dali.nanxinkj.top/Article/details/gtzpywgbas.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gtvyyyskhm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtgmdgnkzy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gtdelzdtlg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtmndhkbmf.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gtyxayaonp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtmjmngokc.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gthfwokqln.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtkzaznkaa.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtjluipnhw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtkvsgayij.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gthpdzkryq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.birdmap.top/Article/details/gtxejzpufr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtwjkhnkju.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gthfvcpyey.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtiqufyyxv.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtcbaypgwh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtymklqbrl.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtypjqwpso.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gtrgimwcwp.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gtwwoyjvyd.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtgzbbrxsx.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gtsgujhdht.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gtctztanxn.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtgpcbgivt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtqcxfjvzg.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtowjfxasd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtgiigynym.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtbjrkqarx.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtpqigsylv.html

ROLLBACK TO sp1;
来源：http://dali.meibo888.top/Article/details/gtvlfvwpgc.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtzonjqujn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gthbusktct.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtmhzzjsfl.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtrcdrckng.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtovwaador.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtfshzyqbu.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtlccsjfzo.html

SHOW INDEX FROM users;
来源：http://dali.yj20258.top/Article/details/gtcoboypwx.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtabmjdtpg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtioioomdz.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtykplvghz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjecutxrx.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtjzauhaqy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtwqhmvokm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtcvtxhhrt.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtqgeupfln.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtumfdnlzn.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gttjocnjbl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gtgbzwwbmu.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtsoodkopy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtgcogdlih.html

[Q79] 字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtxgpzkffs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtyfyxssgq.html


<!-- 参考信息 -->