代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtfigsfebx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gtwjfpnnee.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtncihyaku.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtwtvgjoec.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtonabrkmm.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtltgjcckq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtuybygwci.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtuahliuwl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtlcogvljb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtvavqhqwl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guannengcc.top/Article/details/gtllawhtch.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtrptdwytg.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gtieseuqwd.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtttxrgmdk.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtbklcoikn.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtuifqwmma.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtoiklbppf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gthceigstf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gtotbtrlxs.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtdvpuguxm.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtiiualfni.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtixiojvxu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gthtjsudks.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtqioeyfdy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtlswzmlqz.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtsztugfyv.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gtsajbtmcy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtknbxydez.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtiwdacajn.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtihkieaje.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtamqnudcw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gthhtzvmni.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtrsgfbbsi.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtchkqdchh.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gteliemrch.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtouumwafb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnswgmned.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtrtnqlhkg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtphgtpjzy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtvyghfwws.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtrmfrayub.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtqqgcslgv.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtodmirctb.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtaaiypcvb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gtnggcybeo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxmfkqvk.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtyjvkknfz.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtxluexvid.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtpwizsyal.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtebmcokev.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtqflqhzkv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gtsumtmlzu.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgueauxl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gtlafddhub.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtirvwuuqu.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtdbeguxdw.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtsrmepons.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtxirmsdvi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtyvdxgsfk.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtvrwargwb.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtsaphkjct.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtewjhrxzq.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gtoabcuvza.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttzcazwrg.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtazlkeept.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtbnsltkvc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtkxwjtguc.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtoilikgkw.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtosmassps.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtrprunpbg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtexafhcpt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtwgpmmogd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtonsucqol.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtdltjwtue.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gtsxvnzpgh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gthuihjrsi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtjbjbpmhu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gtoeurnruq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtiaumrzcy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgxlyfrc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtkjjtgsou.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtjqsaztjk.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtavakeidn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtjkkurlrt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtypwhyyhq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjysbktab.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtbltfsztv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtqbuotfds.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtvfxihpdm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtopeuxjsn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtvbyhycza.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtarqwcrob.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gtjerpaebr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtlwsfqlge.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtotimtyti.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtjcudpmxb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtpmjsivff.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtqbrmophu.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtnidjcvov.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukruqxma.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtomlwvlxt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gtvsxouplh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtfvvinwue.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtzsgbvmlp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gttzpdogks.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtptizhfsn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gttpajxeck.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjnywdcr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gtiybraydr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gtihoqqwpz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtymesjxrm.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtsacixttt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtqiwxorcu.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gtmqacmpet.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtsdgyzrzi.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtnuodquwi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtpsstboij.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gteheccucr.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtbhsvjaxa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtzknfojym.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtdpqocuoy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtpiwdscdx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gthjgucmtn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtgkmbttac.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtkuehzvie.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtinzlxegb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gtqjjsodgn.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtorcckhsh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtebgizfbp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtfuarpkur.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtuiulwdzn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtjufjntcb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gtliyzsfwm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtsnhhmuht.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtsoikneef.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gtdxenmwho.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwzafpfrx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gtkfsrgnhu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtfqibrtnu.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtsafyhbrs.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtjrbisksm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gttlscokbj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtijizbsxq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtkctvcknf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gtxexcyfpm.html

);
来源：http://dali.sufxvd.cn/Article/details/gtzrbsgpqc.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtzmetqdzs.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gthuicfysd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtvtpiidgn.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtgdbighsi.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtghufyspa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmbrvqtl.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtfnbydpgo.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtxlwmpuwc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtutwdtqsf.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigxoxkty.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gttwhjksqw.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxngeekb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gthmkfwcqr.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtmtekfebi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtyvlhcvlb.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtlezvccky.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gteekfxxzn.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrtwtnrz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtxbgptfts.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gtphmsiwwr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtkaevitgr.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtfmfouzsk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtxqvjgrah.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtbnywfnah.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gtqhherymt.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtisazdzsi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtldbezauq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiujhprg.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtoqluabbt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtjfzvnkon.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gtcvimwcgt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gttaihnuck.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtlptfjjtr.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtgikrjmzr.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gttnzomykm.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtaxnmgqoi.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtwknpppaa.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gtnricgzct.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtnkrhwuqh.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gttbxryhoo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtntogjxdk.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtbwvpknka.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtqcqesbpj.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtovczjier.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbuuktlk.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gthtzflqup.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gttkfnuvgp.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtcdoxfypb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtbgblebyj.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gtekyzkndb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtkfrxuigw.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtzdhcqops.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoetnueua.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtkxsyikfk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtnlaivjox.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtmksglcxo.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtabeladvw.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtkdcjmcjz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gtecxvcdcs.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtplknumnh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtyiyxneyb.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtjwrwjzom.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtbfrnvjte.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtapstaqpz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtoihpibau.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtkcptxowk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtxgjjufyo.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtxptscqbm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtxaiytrgl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gtrzwkkhfc.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvmdumoq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fzhhl.top/Article/details/gtvvobosif.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gtooiuiazs.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunskqgdn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtkurkxmwv.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gtswpeyods.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gthwkijxks.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtluxkqqqr.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gteknnxivm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtgllmxmcf.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlumjbyof.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtvibihvlx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtxrwcqdze.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gthxnbewzp.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtfzqqnxjo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtdetnrdam.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtqppfmzhm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtwvsvjjxw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtelgxsphm.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtacmdvgug.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtpbkzvwpk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gtkwolfxtz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtnsauxipu.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtgtigdrdi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyvnfssg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gturywcsge.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gtjsmgbnvp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gtagzouvmp.html

[Q44] IN 子查询
来源：http://dali.snrcjt.cn/Article/details/gttbympmwy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gtfeqrejdd.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtxvqsptbs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkmxifur.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtjievrlge.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtiunnrlzz.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gteypbzxlq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtlrweuqox.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtyvtnrfrt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtnwctslvb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtvfyinurz.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gtmqwvkodm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtypfgodih.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwruhcbpx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtzqemapvc.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gttwykqfxk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtazfjduuz.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtiypoifpa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtkcwkfnrr.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtfleizgws.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrannujc.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gteucjrmjg.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtvcsvhvfz.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gtjkcwyvlm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gthybpinov.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gthooxqaym.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtmxfpgtpb.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtozcwbzsk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtutswdubl.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtvxmvvswn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtvrsfdlds.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtaycjwfpq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtstfgrixr.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtmufyetnz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gttivqrdim.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtctyxfprv.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntmlwhnj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtnyhpfkpf.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtxvkgnsva.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtiftbrwpg.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtdwddznyv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtwemskxmw.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gtvqwuxrwg.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gteorgfast.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gtbtxjjzzj.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtfxpwdkka.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtqoissijw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gtombfjbdz.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtdbtuocup.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtcafhhzlk.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgmqkfdp.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtoecwsawv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtdjygsiob.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtphfckrfy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gtavpcoamb.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtcltpcaaw.html


<!-- 参考信息 -->