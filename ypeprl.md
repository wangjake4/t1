代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tidkirfg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmdvmee.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnpofts.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwbrkej.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsxsaly.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjullwud.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkxzfik.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxzajbc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vamngcib.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dqchrfvk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ytymdkxs.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dymqyucz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2akdxdkzs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hespfbvd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fibbylsp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pepycspn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dykajtri.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdoumfz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jahmyhfk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2clakccpw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjavvdx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsjlojb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtimffm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvcuixe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtctwijv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wglwqthc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoyhlqk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaaipxf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhtbdra.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsibakeb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xccuaxfz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaipzye.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hycyrllz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuworcv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzehbboy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvufpxpq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxcptku.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rlihmslv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpuszlg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2igmgcjyt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zexywvyz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2heccqlxe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjwfvhc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkmgqje.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2livdethi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2byqbnsnn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uukyvwqv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrfazkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umphwims.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2soahwhss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xovtwszt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxyfvtp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnghwqfk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wipwwevt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rqysruvh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqwfrml.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzryxua.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2azrfqthz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pygzmpjs.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzjeemx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2shcyumfk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kghoxgea.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lupcfmut.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2trsjycge.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lufhqnxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbudiyd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvdssxx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrhxzqm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvigovp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuzcbeu.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2efngxwji.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gersitbd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkrnazt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xtafyccd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjvkgno.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2eswnspcr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbowybr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuabtng.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uspkayxc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmszfuzn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsfmrof.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blldeuzp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xizglxhy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2popubjgt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2upqgvyvy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqblrfx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhgopqi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2aepbzkpg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfabqzhj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyrwzfy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwqecxh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2liwqbhjs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2tochmmqi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrsstfk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hykmcthk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzztopz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vmderwrr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyhumvp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdistxe.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgzzakb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtopcog.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgxwaow.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dekqwgxc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2btihgcbj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2evarxjws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzccmzj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwwvnnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mocflcmx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qmocwxzn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxbrrgy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqtldxv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aifotjeh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wymssbna.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kusyxgqo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhcqprz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjxzluk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiudeou.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mmalmptl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2txjvnblq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qftulkqd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbcdtjb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbphkbmw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2regygkbm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtyisak.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tckisepg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2owrsyxbb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzfizab.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2eycgdxrv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nenpdafh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rphsqvdg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfcoohp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhpkrtz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uuirlkxv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2odssoxzc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlemfnv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pncguuuz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nakryaof.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uilskyib.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrleuli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2trdbroyd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxvpsdd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbekldio.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rcppamwj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpauwep.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2srofhobn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtrzyrg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2prkohkwt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfzzkcm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2amrkvkzn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmxqyho.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqlupls.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbnpypy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gonyxsje.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqayamt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcczacx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2reakeusx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gepyofzy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvpadxs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdphoffy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxbhnjz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpkhahv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsugbspx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kazdnprm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfjgpen.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2idzjjiyv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxubunr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcklosd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaostjpk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gdczoruf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nofcllqs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsoobzn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaudgra.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlbglvw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2huxifdyn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yyskgpqb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtcelhv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjuijlr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgnpmll.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yooawkkg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2miizwxvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spthsdbi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2byetobwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgfnaap.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpfwgbl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrpqgcp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tsruhran.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwwhacf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mznquias.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dcedoeuf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vanxiccu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zntjetni.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2egptmsme.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hddwarcp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2unkbhkrv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gesfhyex.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwekitc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2paavprry.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwgnndd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktntrxad.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrmcbhp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkpslcu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rspakfsg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2niodxzgd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2smldtzur.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnstknc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnzmisx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpfzysj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pgluewqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkibwxw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2movtlbkr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwggatd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rrazuups.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lluecozp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kyipbqwo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2raeulygq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2biimexov.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhwzjuk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmrpmyr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tekfqouf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eteoyjzb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogigkenn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2udrbkpkc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtwktqn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtwlklh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpftnjvo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aojvvzvi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgludsn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2erzkfvav.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yabzcovl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nripfqym.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aufkmlwm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiorhbw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2djsvxdss.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdumgnze.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgsgkzm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvsuvlr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2apklclag.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxikbzi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfjeowt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpnhukv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzquimy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwooixh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhwukpo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzzodki.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kivqzidg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkahomq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyhbhbl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxveyrr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeclnrhq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nobgwavw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qctwkipm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ounkosib.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luxdfipu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzwxdfv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zordcbpk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xjttlnny.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfzscto.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrulqwui.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsalpno.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2aucejkyu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjvxkzx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgfsfcp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlyjnbs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2enwpmwxn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xznlvjkf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxjgibu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwzmsjd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsonpjv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rucsjvhq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zejwqxrx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2licbnoau.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaavyvge.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oedfhbbh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wclhwswi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2brikonae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vuylsdnu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsicmdwd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlibjrm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlutsgn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjejehj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pivvnzsa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iciszuan.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhiuxop.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sxabcpmi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmbzgic.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjtisuk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2llrmlzkp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2okbdhyyj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qigdyzlx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tumecekq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2irzzcjsn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rahrwsqg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyyural.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpopphh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhdxduz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gboalhov.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2enuazann.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzvtzig.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaabubg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pancsaud.html


<!-- 参考信息 -->