代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2qqvkmjbc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gt2fweunxda.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gt2dbmzbroo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2dqvthfea.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gt2mpiifzhp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2ecjilfml.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2vrnwdwuv.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gt2ywnjoadp.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2zhdoxbux.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2ostcwyjw.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2bnhodhdo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2fbcdutbv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvzpvukr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gt2hojccerx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2ccxwrjkr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izkxhuoh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gt2ukznyvzb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gt2szcbxhla.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gt2xzudgapd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2iosedymx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2bsnnpjys.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2bgtkfvkw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lxkpuruk.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gt2womtoeuq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2fgspygmi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gt2kptjagrn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gt2ulchubsd.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2dvrjkayv.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gt2xcuunana.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gt2aeulxloa.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gt2xybkssmy.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2hyyxdseq.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gt2udthbrtm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gt2gdgfcwzt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gt2fkqnidjy.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtowwklb.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2jwicorjn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdxcfovf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2jfskeijh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gt2smlamhmj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2yfvgqcfz.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gt2pwtrdydi.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbyjkrfh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2kjrselcg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsralink.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2hjbjlmvj.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2inidhdfh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gt2gwxuoahe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctjmbmkj.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2dmoawtln.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2ayrhrlab.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gt2ernzghao.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gt2sljudwxf.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxcwatsw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gt2zqaqewqw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gt2kykvdcom.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gt2wfxeiytc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gt2nyzppalv.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gt2izrfkjdj.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gt2rmnrswkc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzhojunv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gt2slbccous.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2bsnwqowl.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2iagolynq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2xqgpfuwo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gt2iaiqiwji.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2ppwiqfna.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gt2bsfeqmyl.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gt2swqysmzj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gt2wssojmbt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmhhbsvk.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxvrdmry.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2vzlicsua.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2vnifcegz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzerdfmd.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gt2snsqmoyt.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gt2bfxfmicx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ecylklrz.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2ypntwzbr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjzfchsm.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2xcurrjcp.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gt2rwviejrf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrkhhaer.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2sqcmajgt.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gt2ntzpbtov.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2nkiufidi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gt2elryxsgm.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2ptqfhtjj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gt2bclrthkr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejkdzwwj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gt2aiawpmsa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gt2bzpnpkat.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gt2bbjhcwkp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntqklndc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2ruyuygng.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2qjvzbybc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gt2cnxpqjxy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gt2uwgdemkl.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gt2ymfxxkbr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2bzuallbr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2fobzfhok.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2ljyprnlx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2kadkamnv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gt2pygeeczm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gt2vleaznut.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gt2szsdqlgq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gt2xtzlxbwh.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gt2zjuawzwi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gt2smjhhffr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2vcmpxzgl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2hqoerepz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gt2kjabtmwv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gt2zejhmpqr.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gt2mgsirlrc.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gt2wqubfmtn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gt2dzucgsfj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gt2uejqdksj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2awnjfihi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gt2axaxpczw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gt2dkyavzdy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gt2zvccswyk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gt2lllhqmwv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2przrqivb.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gt2fueaezyr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gt2szjkclur.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gt2ztkxbsaq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gt2omitqpab.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2zytpuxqq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gt2npzurcfe.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2mzcupmgs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2grhpqprk.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gt2kqokmvxc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gt2dfmeaflq.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gt2slmckxwo.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sejbvesw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gt2ctgfzspl.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hotgotlv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2tcidgrvv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2epkojqxe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxijrdiy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gt2aouzwcsh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gt2zdxzrpau.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gt2zafvilhj.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2rkwnplyd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gt2jamlxgzw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgiulaqf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gt2mdgpcyrs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2tsoicqvv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gt2fvxxpfke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynjosqpf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gt2hlscmjhb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxvwoavx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2almhmqod.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2qlxjmvgm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2iuzfebnh.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gt2dfibnvuk.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gt2ewrvlxlw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gt2eygrrqmz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2judwgezr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gt2yuibqrmo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gt2lkcktcht.html

);
来源：http://dali.xinyue.icu/Article/details/gt2qrdnaxkx.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2rxhkmpyg.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gt2ntqhqomm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2zjbxtldj.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2cihtjfiu.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whqeamki.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gt2zxasyhzc.html

);
来源：http://dali.mhx1999.top/Article/details/gt2jdfqyooe.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gt2keboruwd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gt2xqlrxdeo.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2nzbynlvw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gt2uoxfxyue.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gt2wjuzxfjs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gt2hdapqbiz.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gt2mwdjimmp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2deelxwnk.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2xrzbtdaf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2vepuyans.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gt2ozoyuzxi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2eulqggbe.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gt2jnpvidgt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2umdrunor.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2msdtuwzn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gt2kyspznrs.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gt2ggzzqugv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfootwhw.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gt2vspuatod.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gt2utckzppf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gt2bpeuzhai.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gt2duntrfhk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2gbgedkpp.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2jihuxdpp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gt2zqjvacso.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2isipdapl.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gt2qzauabvo.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2uhupnlsa.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gt2nuxqlkoj.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2xsqfuksz.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gt2lwdqhvae.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2izdomlwn.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gt2vzieppcr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gt2xfbopbfb.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2auhcmmiv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nucxmlzb.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2sktvznkx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gt2cxlqnqfc.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gt2hjzqnqmc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2zeeporeu.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gt2iettgchn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gt2htlkyzjq.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gt2ngzhfnqv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gt2aqsbillo.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2upgeqvqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2flsnpxaq.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gt2itrbsekl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gt2ehuzagie.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gt2bbyxfnvo.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2rwbzkony.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhqvmalv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2ocwxnccl.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gt2kzotcexb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2ioqgpwkn.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gt2xgsdgxbf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2zchjocso.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gt2epukyefz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2ukcmihjn.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gt2plhdtucn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gt2rkvsbbkl.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2clpnnfaw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2cxjfiqpn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gt2whvedcbc.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2psxfbpet.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gt2pumqqvud.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gt2vtcgjnfg.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gt2ffpnzhdd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gt2aygiwrba.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2evuhsbll.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gt2rsmyipbk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2pivtpety.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gt2rnmnvrrg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2umsfpypm.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gt2yqplabzj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2zyvsbhcn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gt2gxnxjano.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gt2hkwfrsea.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gt2sezbtmcy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmgulkek.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gt2qswzfugl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gt2ctyxhfwg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gt2emyzwwhv.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gt2nkdoidkz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gt2pknjaerb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gt2xlgrvdrg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2hyyseheq.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2vuiokkma.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2ieohfvby.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gt2hjjdsbdm.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gt2epyxhpwa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gt2sqwkmzcq.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gt2thbjosje.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gt2wltukhjk.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gt2djhkvpcw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gt2zqgcerqy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2saewfspz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2tbieyrsb.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gt2ovndhcys.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gt2ejrgnjzb.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2ijffzpwc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gt2yhmlpiiy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2ilgpzjro.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2yzadaubg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2fnrozugy.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gt2bvmcvccd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2oxztaayz.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfsynlyf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2kiqvwqca.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gt2enddcdpp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2wrfzjmrm.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gt2wybocduz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2dpmwfpnz.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gt2qfrsugmq.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gt2bbhkhtzn.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gt2qppemioi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gt2leyoedhi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2obdaruok.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huztwzrk.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gt2kibfnztd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyiultih.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gt2hhcqcewk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2dsolhnod.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gt2cfkrukjo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2vjuwrpmz.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gt2xdwwvmvs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gt2ynqdhaud.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2jjnrljpn.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gt2egdhwnhf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2qrfvtzlc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2flrkotjt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2dtycjohg.html


<!-- 参考信息 -->