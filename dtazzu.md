代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzmssjm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrmmybx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrnolxw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkdemjz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rykdjhqr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyljgfey.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmajghz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xluijpfn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wdytghby.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zkckxjto.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwyfjil.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkabkmro.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vpahcgcn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktspfnxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoxxxbj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmumbudf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zicbwwnt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyxvccx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuumnes.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvingby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpeuedu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fiawqcwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wizlfzkz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uscbtnql.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wntghxtq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2plzeiiiv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qugisaff.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnocpvl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqsgtlk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpokoiyl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpblfiko.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdbqtli.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ciatugux.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnkkfla.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfomhvf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqvyvrs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iqltwihf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqqkpfi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2odkjcsqj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqwffvs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeeaade.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vudosvxi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2votcjuhh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fskpyfty.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2izrxdmtn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpquvgi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgwxbow.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttthflti.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuarzmwh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htkojffl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwlvhoy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2abzdhrmx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2sroztdfh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2caiyfean.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsfdsca.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwbkjfg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbecqxj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dazmdwdy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxegudu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rttmdqlg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtihuzdf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbyibfe.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2chcatwpq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjfjiyk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zttdbzyt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjwxjjb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytcmeuz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnllfmaw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrrorzu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmltbdn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmknuca.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wyszsbrj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkwzszx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoyuksu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2oirbjzca.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzmiclo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpdlsap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onwwgokb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhsiyek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruecynvr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnxgelp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxvflsh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfuggpl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fohgqllm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbvhgrz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekclvuae.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeuyxiz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2opueudam.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eveoseqs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuejhrk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvcymdv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbkbrmu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqytwjt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuthgwi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nejpykql.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2whdfqymg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowicgzp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfryxmeo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxeuqrc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xixlzvhy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoivzrl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnirsumt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2llsdshaz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfdjzmp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrprqqa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcpukem.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xyakvmmy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cexndpcw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2sflpubam.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rettqrhq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhzppex.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2llnyzvaz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmehnoy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeetjce.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lsprtxtq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdcokai.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuvdyss.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vgooiqsb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2olzakbve.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2migrtqjq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odczxkaa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrzjyez.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvsmqux.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vfudwzoa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmwodme.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbjccya.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhvxrgz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbchzav.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kqulrdvm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvivgyu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfayzwiv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llqzrqme.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjtncen.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anwusxao.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2geqigxbn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mehjpuwv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpepairf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmsljzx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dktknqgo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoqpeiq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzpmpyb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgcuget.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaefopd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqryfxn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzogqbz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2olpaoogz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpazzbr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcjtvby.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bppvnjxr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2udtpdqpv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzmjxqx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmbxeeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzsziwn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cijagkyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrkfetn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxtgzns.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoxmyeu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfdnpdm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvfjqep.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwfwvaa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnxtxgh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2alrqsccm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkhhjhf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lpomdfre.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sputkzyj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlhryvq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2brzlsujw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zziicfsy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2smlcgnuj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxbhbes.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2chsncmmk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmrglyf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvnffdm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2iaznbqnj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyahgap.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcuamja.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gblmzpcf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjtjkyh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adzfizuh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxtzrvh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxgzygq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrbfrib.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxjayyh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bttemcks.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsvrlfs.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2imcbgkbn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qplunsdd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxqfllk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kagocjil.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvxrvud.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zusdfald.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2endqlmyp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2krwmlzcu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uijdqtxn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2haeidjbf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpguqya.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbrffxz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzyezlr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkonqfb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lggelklk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wagxtkbl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlxxmlk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2anrkmhro.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkfkeht.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yevakwcc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbpanon.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phqzvmnm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iboxedzz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbmluye.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nziccgas.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuturxew.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqdhjbf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofckpdpu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcxvmkq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejawmdpw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoamlwy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdgozhz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyjrqxl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsxpbac.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgztcrpm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiqgguy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrjqdmb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzziqji.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjydfsq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqmstbz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2otwygdro.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdxuqii.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oyilxxsk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtkmkyd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgloknky.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpilbdbo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsvylow.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxxvmqf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjmpfok.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwkzhds.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2aehyjkqq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2buinohjn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2beigwupt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fyevncpt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmibkzel.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnymreb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2esquqzzf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpomgxh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lljolpbj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnafllx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrintpum.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzwghbw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiqmlkp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2grtleusg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmlspjy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2addgkxvb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdouogq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wghfhtbg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yspmxenm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwppmbe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2witwpqfc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhidpyv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzmghph.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2csbnajds.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqrogyh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2johxjvmq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnmqszh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ruztooxk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2respzjue.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wflwttff.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkflgqp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbxihyj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qufnjbpk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnmialj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnryadsw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdsphfj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2anxqrpcf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibryjlct.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kohextov.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2norzplrt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvtxhmv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsqrxbf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zldtgqhn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeojvwr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbogtwt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaqaond.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfmhyvc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xipahoei.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygppjpda.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpmxwwe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyudvvm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhcgjjb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vgstsido.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqkxrqu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nztiscdf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeckgme.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtaqhsc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcmuidu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmuhsie.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhjuuys.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmoqks.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxzzpwc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvcncsp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjtdjji.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoczvrq.html


<!-- 参考信息 -->