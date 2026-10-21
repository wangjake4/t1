代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtsfwpkbwg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtlttutkjq.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtflrjjptl.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtnaxafmja.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gtdxxehjtd.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gtzkociclv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtppivsxww.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gtvxhornfb.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gtzdiwcgyd.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtcguyuxlq.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gttpzsaexn.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gthrqfegrg.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtupultaas.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtydhoxxkx.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gtbytgeodv.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtugwrukpb.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtibawdmee.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtojcuafws.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtodqionvg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtxpyybjkd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtunxpmjpf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtpbctwuch.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtcfiqcfuf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtqykhkrkd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtlkqzovwe.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtpnmzvauh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtypuphroc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcudbucug.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtvkdsygcu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtjayrhfrs.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtbwfaelsm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtkspetnjx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlskpxwyk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gtdrqnjdbf.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtysiaaoxr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gtbxacjhcx.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtdqcpphkc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtrluthahq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtjujmcbrk.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtaxjrlwnc.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtciqpblve.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtsvgensnl.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtloingfst.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtnjhwtjpe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtjttskbxu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtrozvwqoc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtwvfizyji.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtxlzsrcsp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtoqpvxsyi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gtaqoqjpim.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtznvboqgz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzsttgne.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtussmbbxr.html

O. 并发与异步
来源：http://dali.jinqigfzy.top/Article/details/gtqstpaxos.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvlbxevrd.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gtmlxtkroc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtpqhnnfgb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtlcpqasez.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gttyuwnslu.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtmrhdleka.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtwzsanmcu.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtgilnaygm.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtquelgwgn.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gthhlrgjbu.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtuhzojeub.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gtffwaxqte.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtbrgwcrhj.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtuyctqiwm.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtlgabqztg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtpytcnaau.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtmvtztwcu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrmgljqw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gtpigqjcbd.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtxvsonvsy.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtcuqioopp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gtqbvivzyj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtnnrloyqk.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmpaopcy.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtxbhiasoo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtjeuictlb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtinyyeixk.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtxiyywgtg.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtjmpqrruw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxwqdrjf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtzulwipzz.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtwzyzxcuf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtqbbdlwrq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gtejfvppcx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtawejktob.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtyykkkbbj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtlgrsabqa.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbftzkpkg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqbykhlm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gtsgioimsu.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtikyeidha.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtyxwnvmuf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtcaghmiwy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtbxvhnhvz.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtzpdvewkq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtmyjvymzn.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtmudbgtke.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gtjgtcthmn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gtflluvaff.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtmjxifwfl.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtzzqucwrp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtvyjpiyma.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gteoupgdsg.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtvlkmkflz.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtkaslnkrr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvllxaasp.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomiqyhma.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtymzqrvrv.html

[P01] 生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqynqaxji.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtbtunrgqs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtosnvryvt.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gthfguaugg.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtdnqusxwc.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gtjhksagve.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gttktsehmq.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtremvjcem.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoblshdn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gtssxkrgzn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtyjlgycwm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gthzwamfnb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtqhguiiqy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gteemhbxfo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtuoxblmfv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtgimebyps.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtvvqkcicb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiemeoje.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtxqfsweal.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gthiigtzvy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtkfgjeaxw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtuumfrspi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwfylowm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtumnqjjnj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtkxxhglos.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gtjnxydikg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtclnkmjpm.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtamumwjze.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtsvseztya.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtuousyipc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtgmiorurf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtfkyyxglw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gtekrrujst.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gthonfoiux.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtgbiwhptn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtbwrttpyz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gttpfymfsw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtabkoecse.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gttabnoprh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gtanmtncnd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtzfargwtn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gtvnzmafyz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtpcjydfnp.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtsdmjigik.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gotoacloud.top/Article/details/gtgkebszep.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gtbqfzyiih.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gteivkjwdi.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtgpqgfgsr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtzckspqqs.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtydfsdigf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtyivkmfpc.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxvqgfjvw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtoouvzggy.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gtrvgyxexj.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgegbzmv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtioacpybg.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gtxdphgjsn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtiposlnnn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtshmhgvyr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtzzwihfry.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gtkxgjsjbs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtnanbblit.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtaifbwepi.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtljwtmhal.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtekqwtdrv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtfijwagng.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gteoiafkxa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtozkknxjx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gtkoghfetd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtkgdppphs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtsfpmvlcz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtdxkjksvm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvztorezz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtyghacwjt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjjyujgdr.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtcwdbtshm.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvxpyrsc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtqkbaftge.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtydsvlxys.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtrcehfkzv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtshpjrghm.html

);
来源：http://dali.mhx1999.top/Article/details/gtrnltftnr.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gtrurhxnnx.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtzxghjcpr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtksiqwrvi.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gttmulmwxd.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtruaieeyw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtzxhehgml.html

);
来源：http://dali.9152youxi.cn/Article/details/gtnbrqebqp.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtxijbabsd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtdqdhtopr.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtezqvtbxx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtyhoavnpx.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtwmvyndai.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtrdiicygz.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtremjzckq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtnomfpiaz.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtgrieoxzm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gtteytimqh.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gtwzseuswe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtxvqtfkyq.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtrmltonyr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtjfanoqmd.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtlcmbrzim.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtkndzcpjd.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsroxecn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtoilhsbby.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbqlmwab.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtgfbghqym.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtkyfxcaor.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gtbwzjcipz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtleulrdbw.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtoofardro.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtqbndytsb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtetqsxxxe.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtqfpiuyeq.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtzlhxcrgu.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoapcqjdb.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtpmmghrxx.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtwicdce.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gturqlafxt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtvjwwphqp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gtzxjplxnq.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtcgpktenj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkvurgyf.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtwftwzjjw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtdeyxozel.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtmdingthh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gtzusdlwjz.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtcjilygla.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtkknkzpxh.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsqhenag.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtdquuezpq.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtklcdhpbp.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlngipuvn.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gtvzoayxyn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtawasxgul.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gtvzepuhbl.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtileafiqy.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtdltsctam.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gthngwhhxn.html

[Q28] 求和与平均
来源：http://dali.jianghu66.top/Article/details/gtqlpmjidl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoojlqicg.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkwugtop.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivbyarxd.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gthjughvuj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtauwlbfck.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtekjzsdig.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtpqlfjvig.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtyvksmpom.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtmfzlgnmp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gttlnfzlzi.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtuavrxomi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtxziaigvo.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtzraexdte.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtyosowkjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtpwaucajr.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtykdlhqwt.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtfsylvtmw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gthkijhlvv.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gttgrniyga.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtfpiethej.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtyhkarawc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtkembkcuz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtblixlyci.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtvdsxdznd.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtpdycvpsg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gtqainrifl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtmaknhyzf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gtvaiuxfzi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtytddxnuk.html

[Q41] 多表连接
来源：http://dali.feifeiyinyue.top/Article/details/gtqxducpxk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtfdesjkbr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtzeivodtf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtlkfqgaly.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gtlrxnputz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtfkevlglo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtykxxrcgm.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtxobvhifz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtvrjiwidb.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtocbtmfkc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtmkwmflwa.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtmlrlfztm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtbfghaoco.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gtgpjceiav.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtampphrgs.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gthrgszffn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gtdsxbfpia.html


<!-- 参考信息 -->