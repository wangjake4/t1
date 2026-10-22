代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsyiszk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjwgzhe.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhaxwgs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyegxzy.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eenbyzci.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqvsgyl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgsvkvs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xkicrlmp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqnrgbz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtpchbb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wskicdoz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llehdphr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eohardaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaubtre.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhcefai.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cthuoccr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uopzlzwn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vggbjsnk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncicwxot.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkiifbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyyvbaq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2azwftkml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbdwwkn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pahwwynl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvgsqze.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxzuxpa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrddmmf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxvdvvm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnltblk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvewxkc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdxqxqj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlyeycm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxcotkl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eshaylla.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2drdcnxxc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdtizsp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtencpj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmudaip.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjatlygz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcejnun.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkfcqet.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjqtquj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2typtzmqh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2otpliuce.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bccyxire.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfruwjm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbimdbis.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlakdne.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjamvcbc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnflerpj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2czqwfbwe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqznvsio.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlmczea.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vigwowiw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkuvpgc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjgxdvx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iisklnek.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoavbhh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vebwmxen.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdpncpz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtsewte.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpnbtzp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckwxpom.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpmgkwu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtatnaq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvgijla.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kotbqpvu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsmwudz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rvljdtie.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2npcddhzm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zctjzmfk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdpqqcm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fgewisdv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fyogrgod.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lksydrhn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoetbej.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2szowmjcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmseaoz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npjfxwof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcwbfev.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iogzpcqg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jcguvlmd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwypdzq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjbjojw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcagligv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2orzfiozw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2buesccuu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aambwjco.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nocghgwt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2quczvnsh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2piymbptf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2buskgmty.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpkjwmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvajvgwt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmyewzy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbmwwjd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfemzwm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2sujzmphi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imbwikbv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwqpacx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmueouzc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgwrikj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrugzgw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaorucz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vehslpit.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2scbnuauv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjfnlry.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtznind.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpkcrkw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlluaob.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnnpwlm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvsopcu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjchuxfn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsihpxo.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqocjnw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnfkcin.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhcpuus.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2drkqougd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaldphb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdodjbz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbuuloa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kbugsrlw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsyiuja.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbqhcki.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2olrwwrby.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcuexyr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxbalut.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcijeuv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bownsqsj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwufyjfe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqxtbwn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyasups.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxrvbqy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chyfwxnc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuzmrzv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtlelnr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxlckta.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yuydutvb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzmuvku.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmvuexv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaijwnh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbkoukd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ououpbbs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcxwzqu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvwhsow.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2thcybdef.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzrssti.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quqlyxtz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2skcrhiyr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiaenki.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpeboyh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyooyfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omsssvgy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2aepepkpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qudrpiyj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbdtamj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dfclsgsq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2stizfkao.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhrlonr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbynoyp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsvidwc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjevhbr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuajuns.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2exvspuuz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfoqsst.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2idnnzrfp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdowfdk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpynshl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkytkzle.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgqysbe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxwihmd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lktqjpst.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiurffwz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2htrfbuwc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2phtwhquq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tazonbro.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tatlmwtu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeciwna.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzumekbp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtpylbm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmklzwa.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jebzxltb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhtornu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2swaxrlii.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgyyhnk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmixzso.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkjkwad.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzhkrkg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjmhpql.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrvvgxy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2eosnbice.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yatsfbdo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvelsgog.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsvaowu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkpiowd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2onrxhslh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaonxmg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxksjpv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeypnnl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcmkhww.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2izylenlu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmijxll.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kjccjwai.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuuvlvy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lurgdcwo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzkeqvd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtvadjw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kgktmueh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2chjqttpf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgocsug.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2siprfyhc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bkazsbpi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkveznwj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2khugequq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwegpwn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2onajbfwl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2veuiukea.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwlfnpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifphlhzp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2izkheqtl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stfkhyub.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2chpzjuac.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpycnmk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfloxvn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbnpkwg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zovcearr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qokeicvq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qewfrune.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2plbfrjun.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxsdrmn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vputmpie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2edczxnxf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2spoznsrp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2slqbljyz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjncosv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvuyegf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsalnsa.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqweqiw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2euozgpvl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nndmjmrl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmlkxdm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2geyprgin.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwmsec.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yridfamj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2irsfpvuz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlfwksi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vppzedrz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhafdre.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbkgrfh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfprojx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbgvhtr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxssskz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2toxhxrdm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2giyzmbis.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoycpzf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2exdlbqap.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpcvbty.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlggoon.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfewgzv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjspnbw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkxifbn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnchcrlr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ctikcuyg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtjbflo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oceakpyk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlluhep.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyhtpcn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bviocpog.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrisrpw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2djrlmuuf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbbxfyl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2labxmjco.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kagjjkou.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmqcynq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpscfxw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2brkwdjgm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzldhedd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2loxusyzp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzerxzit.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkvdopw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtqbrjf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2czedplyb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwmbhkg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfducey.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2omvewrcy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aclljehq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wggkujud.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2agcgfbtn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrlrmfu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdnlcxw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vewjwwzl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2okrhzcwk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2etbmrxnk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2stwbvvgv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrspejj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2viozazds.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqlqsqk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2quddtatd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfzmmli.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpjolvz.html


<!-- 参考信息 -->