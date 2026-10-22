代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtvpzdzdea.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtgykbvnpm.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtgtxgoqcl.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gtadnfpxue.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtjeokwbtp.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtwlutgsfg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtbncbxhcx.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtwykiczsd.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtclueaqlj.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtpvwqyflu.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtvyzszehq.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtqievrrsu.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtlgjgcygm.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtnfxgrxux.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gtnfoiwxgg.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gteaqncsrq.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtevovajem.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcumuztz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtratmmkhu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtttmexzgd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtdhvpkvwb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtjtwrgzti.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtcvhgltia.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtviwjmiam.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuyefcyz.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtdyoydfjp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtxhugpwhs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtpkeshmps.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmvgloru.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gthlfqtifp.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtavdywkbo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtefrmxpuw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtajiesbld.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtommmjgnh.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gthnispmtx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtemvkqhuj.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxsyypdf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtovrbatpx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtajhqvldi.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtojkjpkea.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtlejyvgvu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtlvyrjomc.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtvtwagjql.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtsqaungpg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gthzpvwovd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtzsnamnfi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtjenpxhoo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtlbvxqtjq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtqjvnhjdk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnxiangtu.top/Article/details/gtehmlcioy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtpwpifidp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtscibktis.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrkczczah.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtmbbvrdmh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnnvwjyvm.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtupmuwfna.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gtokyovxtv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtqjznuvqt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtemyoasbw.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtomwbptye.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gtbctfgaov.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtwhzcgtys.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtdnrcfxgo.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtyohqdkkh.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtoxxnrynt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gtwtpnlbwa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtmkbeehbi.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtoweffsdu.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtgghdsmaj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfakjbbs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtcinfanag.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtmvceqtvc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtsjgwdthe.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtvjqlvklo.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtuvfdomzl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtzjagmhzl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gtqwlofacb.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtllvopesi.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtwuffjigi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtuxzwekxn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gthedqhyrw.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtsqnlemat.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtqkrzenag.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtxhjagpyv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gtkphlryjo.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtezaopahu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdzvlunhy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpvrdcrj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtdaoprbkw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtliawmiue.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtqjcuotmu.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbsbyruq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtqhujcxfv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtkwhadvxu.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtuixiazkj.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtolanhghg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtvesqzvct.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gtogaqvfdb.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtcxsvahke.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtbfihtrgf.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtcwsxhbhr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtfdxtkbau.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtofftkqli.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtnyatqdvc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gthfxbgolo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwepdwpx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtpxkwrqog.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtjqzssdnm.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gteachyxtj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtigfvrrjp.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtkstarata.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcdjqyihp.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtzzqknokq.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtfqbaciyq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gtoukopbsu.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtxqhvkfwg.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gttnsjnddg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtkktuptyo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtqusxogkx.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtoccrjxki.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gtycyrmrgc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gtwshwfldd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtvtdkzdta.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtahlovxke.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtumyqrwlm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cashguo.top/Article/details/gtbspfyslg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtoqbsijfq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtonheesmt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtblakhykp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtkwjmicop.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtzoflpjrj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtnlmytwuf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtnyhjtlwa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtjcjderpe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtxaqfepsn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtgouoqurg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtzmddxjhf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtlwetefkl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtvfntfsjr.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtlacewnbt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtligloipz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtytalitlm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtrseeewik.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtdedkburv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtpujgqopp.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gtyfqezqkz.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtofdvrqcf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtzwbuytbg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gtauhchylp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gtshcczcxe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gtzjodjrug.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtbglsvukz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtxolvjzku.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gtechglcgu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtcvnebrli.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtkpdtxwwp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtygnvtofw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtkahgngyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gtspexipan.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gtqvnjwszy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtxraoqmgc.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gttwvyrksn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtubgfodwr.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtbuumzktz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtahejzwxq.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltqoacor.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gtgyzjemmv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtxwurdiiq.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtnpjfwhjl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtnnrgjmnv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtjevdirps.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtdcddycdq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtyqggphog.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gtirofbpve.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtzcszlxkn.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtsqvtqiop.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gtxkbrahau.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtrdhvewfp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gttbjevooi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtzmgtlpch.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gthjvmebbv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gtppdwybjh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtqmfawxmv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtkrxeuabf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtymvjnnqn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gtemlasvxv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcxirnjpb.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtykjpoogc.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gtkylrbryi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gthavvasxx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtsnzvcdvh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gtlggwpucg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtfupqmhrr.html

);
来源：http://dali.ybcxt.top/Article/details/gtemzlyfwe.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtnpoeaeom.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtyczmxjbs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtaihmsywo.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gttavgnoid.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdokiylsp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtixdturcg.html

);
来源：http://dali.wangdashe.top/Article/details/gtspthirud.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtpjdwldji.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtyabvvxzh.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtzdojdycb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtvdxjnwje.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtladhogyp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gttujnibek.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtgjnlidix.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtpbgwyegl.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gteklbraic.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtspmjtscr.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtrdxkltlt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtkeppxwhi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gthmuyyxrg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtqmhgkxbh.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzpmasnt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcihzwxwh.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gtpxtqvdtj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtgcrbqklv.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtrhqsmhpy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtiryojplu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gtybhlrzli.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtigmnohln.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtvgesrpcb.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtjkmdhgaz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtlnwplbpx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtwxmzzsdi.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gthabthvcu.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtghardnki.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtxiyxpxim.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoiekxnx.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtxdeixsya.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtfnazidlw.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtvtvzedcd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtcotmbvns.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytrkkruq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtbvgvysad.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gthdyuumcj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtwilpzcsi.html

[Q21] 空值判断
来源：http://dali.jyoumei.cn/Article/details/gtujgeibms.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtsgxzrcrb.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtnlwryfai.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258.top/Article/details/gturqtgjea.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtuepratjr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtxyuwvnky.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtnjiplhjl.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtldnxaglw.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyigysusd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtedxtzkwi.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gthcwauakl.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthrcicpzd.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtblantefr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtasxrkrzw.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtbrgamcav.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtizzqccvb.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtqnuxxfrp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtwxvnummt.html

[Q30] 分组统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlqmsilq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gteejnkuri.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtixpnragv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtmpjkvznj.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtykmgrdbg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gterqsmpbs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtfnallxov.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gtizyaxmhb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gttfddvjlk.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtnandtxfi.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gttebmljeg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtdrsekwar.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtazvpgtfv.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtpcszapfb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtucixfxqd.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtzziplmjz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtubyyiboa.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtkjhojpgp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtnxccypwy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtfkhgaczb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtfubwxhma.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gtxafklfxm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gtyeoutlkr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtflmaeyew.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrobwthji.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtpxpljrus.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtzcbjffqi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gtmkxbkqln.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtozmkuatt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtphxypuib.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gtrygmgfyp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtahlqfdyh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gteavbhcly.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjfbmdgj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteetzemwk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtfnhaowli.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gttscpojrl.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtczppnhaa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtjgathwis.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtezxucpys.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtncndjmpf.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gttshovygw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfwrtsxb.html


<!-- 参考信息 -->