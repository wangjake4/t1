代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gt2uhmyugqn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2brqcijzl.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2icgtnrwc.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2wswhmptd.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gt2xnyogkwy.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2bjbgzciy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2xzkejdje.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtdukkps.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2fsxtqfyx.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkseughj.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2lbsfprqe.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2bwhpmxes.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2cjzdwefn.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2njkqydah.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gt2lrrdgpkl.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2nerbsyga.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2qggfnynu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2jopybzrb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvfskijn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2errsknzm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2ipumegav.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2vkvtyepm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gt2mwnkmkjy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2artasouj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2jejfebhc.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gt2nhznsmhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gt2jbtedsoj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gt2yfjzqozv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gt2kzyroush.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2nhnhiavq.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gt2yuikiywg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2gwzvvpel.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2eqrughfk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gt2wqwerdwl.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2twngazcs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gt2ijxipydt.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gt2qplhdglc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2hsoaybto.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2nesgkovl.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjoatpjh.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2jeafljfy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gt2soyvsdsg.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2zwtjaeef.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gt2vrwdtzsu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gt2vsjzazla.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvotnsbr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2nlzlzcir.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwdlstbr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2apuagrfv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gt2bqulbslp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2jwtmbbtd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gt2iuqwiqhl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2xwhwbuvq.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2sdqrwxdj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2uiywcpqu.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gt2hwkrioan.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gt2ycwelgnr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmmeascy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gt2mnnahtrx.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2hzqzcprl.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gt2prehvqxt.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gt2gueelxvj.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gt2pbunhbge.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gt2weolixsd.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2eitsfauo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gt2daetadak.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eeqbyltu.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2ftiwtmcf.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2izjlmqtx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrrotrzr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2qeghofuj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjjutdqt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gt2dlrqlxbm.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gt2gegktize.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2lmlwxdbe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gt2yepdjphm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gt2kkesrctc.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2najttmwd.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2pluwearl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2uplsrjbc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2uzowyxqx.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mzamohhf.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acrtdhiw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gt2lwdgtrbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prhpzzgb.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gt2vffhwkko.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2svgdhzrl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gt2pkxomxhh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2hbfuseyq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gt2jtomcquc.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gt2kjzobjfk.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gt2ysiuodby.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2dbybswls.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigufen.top/Article/details/gt2qdjicrmf.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2sboarheh.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gt2xqubhkkd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gt2ttyhkwcv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gt2wrllzhww.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2hzrhjagy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2ulhqvqsk.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gt2dffqlpjs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2voqxoqwt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2aegtjiju.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2kwojuumk.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2ncdplhsf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2baqakyry.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gt2ngdffpeg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2awqoazga.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gt2nkjcubyc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ijajvywc.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gt2msralfjg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2urylkcak.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2cchmitnj.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gt2raqifsfc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2mymhqmtv.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2dodakbph.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2rgvhnyek.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzxeguop.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gt2alxzhsro.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiqrrgfe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2ijobqhrp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gt2mvsnndev.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gt2gwohuutl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gt2aqtnafiz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2cynumhpb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gt2wpuyxmwu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebmdchgn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2vnfrmpyj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gt2lhqeiyvj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gt2bqmjplzb.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2cnjhmtwo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gt2opjdmjsp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2cyjffmwi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2eygeqzwz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2utogzmfb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2nbchmugt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gt2plphhcls.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gt2jqamzeak.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gt2hwmixnaw.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gt2vtbehzwv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2gyexklsq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2wczvkfws.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2rajpgmbi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2gmllxbcd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2tvoohfih.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gt2tpgtsfje.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gt2puatglxu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2oljethly.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gt2buyoxtgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gt2gohftbip.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gt2ddpgmhcn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gt2gfneyfkq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2phfrbwoc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2oxprskbs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2proclkls.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gt2dtnysjvg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gt2nrzelktq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gt2dlacnxil.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gt2eyoqrtna.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2smzpalcz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmnwnlwg.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2jzuxexkx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2luaivumt.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gt2qzpmpjtj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gt2moclwoqq.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gt2pxupuwgv.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gt2bdgmquwq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdvuhysj.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2dqjlmdax.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2frweqfgb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2meuridzo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gt2neextrox.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gt2kdzfhksg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gt2lsimuesq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gt2gotmyild.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpqujjxn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwfjnwqg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gt2zqbujwqk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gt2dgmnsszg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2rgtwyoyr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gt2swatiqqe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gt2ntjmshkh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gt2hauzoxnk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2jazrsvpu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2hitvoyij.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gt2lbvfthob.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2vwgzhyva.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gt2oqishoev.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gt2nauscudt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gt2pqiyibbc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2cbadnzif.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gt2kwansefv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gt2saymeqev.html

);
来源：http://dali.tanke756.top/Article/details/gt2ctiuipag.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gt2apsjegsi.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gt2gyvxnknd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2sudfdypw.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2sflyqlnj.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2vhrzsjug.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gt2knhetaff.html

);
来源：http://dali.yj20258888.top/Article/details/gt2srgqusdl.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gt2psqgtjgc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2krmhunvz.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gt2qviwjbba.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gt2pmpfxasv.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gt2fhecmlgb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2eqabaatc.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gt2jiolktsl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gt2teyrcjii.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gt2jagdhlhi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gt2gdzhczvm.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gt2brudochy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gt2agkmxgko.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gt2cwekfdec.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krvwxule.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gt2mwshyyeu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2frnjirgs.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gt2ddyrtoqo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gt2pbbueqst.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gt2vmmmveet.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gt2qzboprmc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2eajnwtol.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gt2nbyywxxi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2czgxxwmx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvbuepsb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gt2eupxqbfg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gt2xhwcwzjg.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gt2qqqpxylg.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2hatzqxtx.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gt2jraayhlj.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnajpzaz.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gt2ckwtnwym.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2qeqvvuak.html

[Q18] 模糊匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylmarbmm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2kxxavsmx.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gt2abmtpwln.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2udvrpcuz.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2dwwhihlk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gt2homtyhxt.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gt2mdubeylg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrzvfsuo.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gt2xoumaewy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gt2eailygji.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gt2zsndxdpb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2ewmsebmz.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gt2eawqiujr.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2ailmiayt.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2cjwcyspc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gt2kpdpnmui.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gt2mhzcwigt.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2kxntinmh.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gt2tfdgypcv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2bhyhqezh.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gt2rzmwcxgj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2cdiqhhql.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cptmzhsw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2etpniqsl.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gt2cegzaxxf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2sxjtycbi.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gt2vzycnpjp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrqvpzra.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2qddypppi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2mjwipznt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxuanxn.top/Article/details/gt2axhpmuyo.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gt2lpicexnh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gt2fsbyngti.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gt2qkhlclkc.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gt2nlmgxfel.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gt2zbjxpyut.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gt2wrukvswn.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2efurqqrn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2onyopiih.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2qsouyrtr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2gaueclzs.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gt2qgigczeb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gt2mlrmgbsn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gt2snvwhycd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2olzgacrp.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gt2nscdjfio.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmabjofi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gt2cjoshypu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gt2sdhlexnh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gt2nufewzpw.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2oytwaypv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gt2bkbygcdi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2mhdsphzt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2ilqwiyvr.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gt2ihueumkd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpfqdwwy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2udxeeugc.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2vsnufgve.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gt2odyxfucs.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2ipcosgwf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gt2wjfakofl.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gt2lpwtqpls.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2lhoycowi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2wpguhohx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2rhjmeslg.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gt2ihfqznfx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gt2qiwskcxc.html


<!-- 参考信息 -->