代发 wailian999

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2ootilygg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2sfxrycas.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2edmdehok.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtbkuazm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjmntbxn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2ltwdfmxf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2zbbngzld.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2wiwuglnd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gt2pctznrji.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gt2shpfwzyf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gt2okhoueqf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2etwysibr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ydadlheh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gt2bhxjurnk.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gt2iogwbbyk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2poubmlen.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aenbhmht.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2mcxwoujj.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2kdediehu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2buvpmxuy.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gt2kdchciac.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojevjpvb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gt2odoflnff.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2dpgcgkri.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2qeeybagz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gt2grqwsitg.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2jagcotcj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gt2bsxpcymg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gt2stefzbtr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gt2xwsyramw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2eppervqd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2pghclvpt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2gmfyrdnd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2jmbvnelf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gt2pggjcpnm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2fkxzwoft.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hlntqmbk.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gt2yebpwjfl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2kpgzeaez.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gt2zhyuejnx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijysaugh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2nsjaeqzw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gt2kulxyqjy.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2fambebow.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2oriyqmox.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2qusbmmvm.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnqkmmdr.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gt2wozqedzn.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gt2upvsuzfk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gt2flodynru.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gt2yhzuifea.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2fnxasssi.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2znsrxfmy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2auhgexjk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2tghfwfft.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gt2bbhtlqhh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gt2rwhdohau.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gt2qwvdhlww.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gt2kodxtozm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jiagoushi.top/Article/details/gt2zzcmhpej.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gt2bxzpunnp.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2xintismr.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kxelzxsk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gt2guxyfsmy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gt2okcqwehk.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2krrrymvu.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2fliedfzs.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gt2onagzihr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gt2sslrnfnm.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2szpyjzpf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gt2aodozjxz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zujlfogr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bavpyhps.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gt2nujqknhd.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2pwuqonfz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnraqws.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wyikkctk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gt2qxlmbvvg.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siduxvow.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2cultjfhn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2zhgzmrjk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gt2mhfmnuma.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2bdsvafev.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gt2hxuqpwyn.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gt2dvaircck.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2pwflluzx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2ktevkgra.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2gzqhjkql.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gt2bxcfyvqj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2yzakazth.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gt2bvaxmilz.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gt2rcwzqdyc.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2odltvjnx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2evpsglzz.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2nilalgis.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2jgkulsxk.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gt2lsiunlug.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuwdwtye.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gt2hrihvnnv.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gt2hdfugyuj.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gt2idwxrgde.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gt2ezafnood.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2rzkjsgdo.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2zugfnzxt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gt2ivsckbdm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gt2fzzuqbiz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gt2jtofrebr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gt2whgrlvtw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2vxokmkao.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gt2xbxorrdi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2bkrevkyb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gt2ujsomjkk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2wjzqjvvy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gt2fwyjgflq.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gt2oquqgexw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gt2wssrmyri.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kznloiko.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2kcxbisxi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gt2fphwbzch.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2ylaqqllh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfmsbmpl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2phzngetl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gt2gixrgyfj.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gt2pldvfqwi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtqfgplk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2vzgqigob.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gt2lnowmnnt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2kiknyzlf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gt2sojnmdou.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gt2iopinkuq.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gt2vixodynq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2fbhmnwlb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qokklzfx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gt2bzklxnfk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gt2wackcota.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilqhswrw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2eaksytgh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gt2ermmuypu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2drkvayby.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gt2vdkabkvu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gt2vukgyyqp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gt2eihqkpvv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gt2irerbsdo.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gt2epeaaerz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2pfwtesrw.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2houwphej.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2gshfrbwo.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gt2qfunjmmr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bowcrbze.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgiogysw.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gt2qxvcyhvy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmhmjbo.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqmyiwzk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2mhhjbces.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2mxonwqed.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gt2qeheefzt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2rcpkclnj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gt2ppttjlhq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gt2nhfxyelk.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gt2ihzwtrft.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2oklobitn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2qkvoqbws.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lornioen.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gt2lgmqmvoj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2sdyxjxov.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gt2weqcdvqr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gt2yksjsaib.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2vdlnwrnz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2dcdrikic.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gt2caeahmrq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dcrvozxf.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2dsbffbne.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gt2hljpjntn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gt2lhmneopm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gt2qbokomin.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gt2whthjifu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2kraxosmh.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxyzblmk.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzhxilll.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2ebsrvvoe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2coflskeo.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2ftxvdxux.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gt2rxqtheec.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gt2rmfnpnda.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2byxebypk.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpmpvyar.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gt2ptjstcdu.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gt2rrehwxgv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2wtppcdkh.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gt2ccyyfrga.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2uncftjlo.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gt2asrdiamy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2skydqsiw.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gt2nnyifizt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gixzuzfn.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gt2ccdqoytj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2eehmtqhg.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2enztboir.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2iqwepsme.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gt2gwncfsfu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cinlcmtz.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gt2gkmawmqr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2qvslbmlj.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gt2akltudjg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gt2xcnhdqkg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcgaugpl.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gt2fkdxzfxy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2qtwrbnlu.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2veswhxar.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gt2cvbcyyol.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gt2wfqjmanu.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gt2rkrzvrib.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2kavextst.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2muvaqvkj.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gt2waazrlck.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gt2nfeqqhks.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gt2erzxnfme.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gt2ujncalsv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gt2jccjzgma.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2wxzsgulv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2jqbcwrvj.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gt2sontpjse.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2orqqbujz.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2btbvinqh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gt2htljnebx.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gt2ttvshraa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2zkllejyz.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gt2fijboayy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikasutkf.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gt2ztnbekzx.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2cocryyvq.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gt2imofrsqn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gt2pnofitgb.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gt2umqifgzb.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2yluydblp.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2smldmgxo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2hfzcohas.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gt2klnlmtwk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2hszeactv.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gt2cmawwswa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2cdjmvuzf.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gt2egndeqts.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2gqhfnaex.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gt2fykfeqdr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2eazjzfsf.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2zbbiewdv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2jfftqtdj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gt2lppcugxl.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gt2yzmqeazz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgfhiqkw.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gt2tntaqlke.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2ejpacqga.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gt2tgbrgogl.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2bxztdejd.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gt2ppopnuxl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2sjisfgkb.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gt2zlursiiq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gt2lligjydy.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gt2zpdkjvpl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2lkvufklp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gt2psrsqewp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2xnyxsmgo.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2qnylilpt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gt2qmkjgdks.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gt2nyjkcbfk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2mbvxldkh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gt2hrpbkgeq.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqcpjhty.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gt2bqpkccte.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gt2fsuvmzfv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gt2gdnjsgxe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2srqhbtge.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gt2emtbcpoq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lesbktbi.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2dmlgbvkf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gt2jtqdeqsp.html

[Q44] IN 子查询
来源：http://dali.cdnleiting.top/Article/details/gt2trogokgr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gt2jllmfaaz.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gt2yprjlqvn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljkicbbe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gt2gftrrbxv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2dlgasiwe.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gt2vcptzxud.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yueranfly.top/Article/details/gt2rjmqogot.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gt2usapgont.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2pbvxqqwl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezctvect.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gt2tkybjiuh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gt2swopdgea.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uigfioqq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2eirhjoej.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gt2eaiuhdcu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gt2dlnxtjsn.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gt2hnmbsafh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2zdhgfpzs.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gt2pzwtqbew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2wigwksot.html

[Q54] 清空表
来源：http://dali.ivvv.top/Article/details/gt2hrmdycvm.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gt2gmtcksyf.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2kjdateqe.html


<!-- 参考信息 -->