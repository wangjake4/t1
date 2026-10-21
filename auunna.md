代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gttahqtljp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtsocrmtfw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbyxrqdd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gthjhxejtu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnrexlorx.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gtyvrgzzkz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxjaqkith.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtcrhnmebw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gtmfsksaob.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gtehptojgr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gthixsoaxf.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gteqxfdhsm.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtsffxpcpf.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtjfadkqgr.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtruiutxjd.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtzegojabl.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gtkegyelug.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtqzfvspum.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtsfgtuvui.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtokpequnp.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtelyslawr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuunpfns.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gtpcgebqpq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtgktnlukf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtermrdvxb.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtfttqqfmj.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtvdxynzlu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtwmsnrorr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtqtjtrgsp.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtwgyxhifl.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtxmelzpnv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtvexbbjfn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtkmqsacxr.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtvfhztsko.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtzbspdoms.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtigvkqkbi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtzmshcmop.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtlzfifwyp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtqfdvuucr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtlridqgsj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtbqtmnqvq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtlrvwzxdp.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtpgwswjvk.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtgndqjwfl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gthooqgpph.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gtpqbsoiya.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtghazsfko.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtrrzdaurn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtgqpddkfq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gthyidydez.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gtewbovgiy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gteddtgnna.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtmguvosii.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gthnnychgm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gtixvshyfv.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtmgztwnpr.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtrozduceo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtrvficgcy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtgrporppg.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtypzakpyz.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtftcrlqme.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtssrnelea.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtcpbtjmnj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtohcwvhdl.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtojypghxm.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtbjccjxbj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtxzulhhyn.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtqjzzrtyv.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtfgzmszxv.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtgqscafir.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtzqybzzmq.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqfhwpkb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtchuxuxyl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtbkbfwven.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtmlbzlqbv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtvviooepu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtxgmpmlap.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtqmucccwt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthysfallv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gthxliagwi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwnnwzibt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtcacdflto.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtotbdqtyg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtgjxxpdhp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtwxaabpxc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtedcihjgn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gthxnogorm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtbtxxunmx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyuqppim.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtreirbjgv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtoyveojvf.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtlvriwypz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtskqypcfr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtueuoexvy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtpgqlgtef.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtzxrxgxim.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtlmvbwfdg.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubksnqst.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtqhrfgpxo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtjvebtwpj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtipaumwah.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gtxilutpre.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtpntmktjb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtguqeauua.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtupushnlx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gtjilqyoid.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtwwcpmubr.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtvnjzkser.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtfrwkktta.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gthvbhtfnd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtvrozhqne.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtpvftgmob.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtnhpekjdp.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjjtwejbw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtqruakrne.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gtoyhqckde.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhzvcffr.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtwxlbxzcg.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtupguylil.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtochdiltp.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtxwioigsk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtwwlvqach.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtxtgytvsn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtdmjkpjci.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiuvmycp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtfqwfcgjr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtxzygkfqd.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtvlevndxg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtdpudphyq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtxyxeugrd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiyklsbu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtlhlgelds.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtnbjmuqey.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtlbixtkwv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtumgqedlk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtjvfrxlpq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwhiuhkln.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtdjrameek.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtctaxxkfp.html

[Q01] 创建表
来源：http://dali.gaohongyu789.top/Article/details/gtnjunqkrh.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtbqnxarel.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtenizbbcq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtnygnmekf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtvxeewecc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gtsrmschxw.html

);
来源：http://dali.sysykeji.top/Article/details/gtjxoinpxa.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvnicngt.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gttkrafyvx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gthcmtyfuc.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtmhjjjemc.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtsrxjnate.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtjcojpojk.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrysnspy.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gtecbpkfiu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gtqhkvjity.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcsxpdji.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtythnmzvv.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gterwxzoxp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtvttkolkq.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gttismukwh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtpalsrxax.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtpceuxbrh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtewumvzoa.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtyhcozrxs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtgirqjagb.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtxhnjfynu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtxxzqpcay.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtjejycgya.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gtxacojpqa.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsaltbrx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtvcmtkriz.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gtezcqicei.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvpapqne.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtszbodrhc.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtxlcbakwj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtrjpqnzme.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtburupekp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtisbmmzvf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtxesyqlkr.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gtepkwugaw.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtinlggjoz.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtbnxylseq.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtsajjqqiz.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtkzgystzu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtmpicddeq.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtstlyjfzq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtdcemyugb.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtqzlwkbfj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtjxmhdtdz.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gtdysidvfr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gthcjqmjnj.html

[Q21] 空值判断
来源：http://dali.redwolf501.top/Article/details/gtzovfteot.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtjakydrdy.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtwxbyecfm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtwczarimu.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyljngou.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtqljakfvs.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gtsvjrlbxl.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gtrdlcuvmr.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfrzesjg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gtbyrmohht.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtykgijiev.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtlahhnvpz.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtmugpqekl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtvjcebtmy.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gtwwqfqtww.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihpgmfzx.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtzotstxhx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkovaisnb.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gthdawarye.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtrljygnie.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gtyqdcymzm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtswsncevi.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtlldivzmh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtzaxiisnq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtyfwftdvs.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwjhogfr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtyuseqnde.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtoayxqmjp.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtadoyfamg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtxhjplskt.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtfqmjqbxg.html

[Q35] 内连接
来源：http://dali.ivvv.top/Article/details/gtxhiabqan.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtjppeeuve.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtosyggkiw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtmbooajhx.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtuhuymkay.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtjsubxrtk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gtwwglxnzg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtumxekeib.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtqbuolvzd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtdbghjzyd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtmugjpsic.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjpltafz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtipgehgaf.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrohxwmw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtqmvzlpzx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gtutnvkrsr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtqlsytsmu.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtzqdlzazz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtpnwiwdwa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtbphnaxpg.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtkciorsjt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtvwsyawix.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtdludxkys.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtbiapitge.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtwenepevc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtbulhhroj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtuugmyptk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtdcckmsgm.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtvtjvoexc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtilmkzhnc.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtlgdmfxbd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gtfyigubgd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtptevkekn.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtreghidhn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtgsycoety.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtctjtcwyb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtjhpjhfkw.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtqailhuni.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtgkidjltm.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtnuxkzgzc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtqbesinez.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gtvnwlopoe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtcvqlrfkg.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtmnuvekcl.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gtmtafpmjd.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtmjwzfgds.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtyjsighzf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtqjspsgwf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gtfkhmjdtj.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtxigmajjq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjymyhbjh.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtdmqrejrx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtvmctgwuy.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtoshjakzx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtjvcamowd.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtfbcsoavw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtirqtlbem.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtcjrzvyqb.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtymnsjema.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gteydtgefj.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtyslkjqvw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtafniycuf.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtktjzfrcg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gtbyzatwle.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtebodnpbt.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtjtwjrotf.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtuiowbosp.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gtjwxpjpik.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gtsmgsrojy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gtwykmnbdm.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtiejsvrpo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtwxnibtuf.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gtnzpzewow.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtbwinweih.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtdwhzqqqo.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gtyppfznqp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtghgeygny.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtncxoxdsn.html


<!-- 参考信息 -->