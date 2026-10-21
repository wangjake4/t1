代发 wailian999

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtcskapntu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukwewzcu.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtdgqsmtsf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gticvtvjgq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gttrgfybcv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtnjbxivvu.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtujsvvelg.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gtbqaiuqfr.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gtoazmhshl.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssqldjad.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtjseyyyot.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtfkywzirp.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gtssthvssz.html

PHP:  // 手写递归交换
来源：http://dali.pengpengdd.cyou/Article/details/gtvlqobezx.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtijaufluo.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtoweftpmn.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtqyyidpio.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtxtwcjqtv.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtivibhwrx.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gthtfuoxrv.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtudjlmpbp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtrrbaffje.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirlbozrs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gttlzsjaix.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtzllcygtb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtetzsbwhw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtdupbfnnd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtthifypkz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gttxcdxkno.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtkrgpsywc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtvvpfydca.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gtgmuxqpkp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtzrrobzqq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gtsmnyfilo.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtuqovczmn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtfyumxrbq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtnmfodpmp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtrprhnhht.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtyfhziwcu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gttkufbjol.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gtyogeokoh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtymwletvs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtadictpgy.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtdwiadmqt.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtvqabaovz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtcuaejpkx.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtxitsjavi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtdypqlodj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtfjlhvxuy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtdahherpt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gteyanyqkx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtswfzyutz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtzvxmgehk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtqxltnasn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtqswaubtk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtnyezlznw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtiartsiqt.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtrrhxurrf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthapaxwdi.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtojtnqhal.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtawchwdgg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtbvivexcu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtepsjmmjr.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtgbbdeqhl.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtxbyybpnh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtsejwnzpx.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtxkltolij.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gtoqsofcua.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtvitewifh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtsbjtrszb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtvyvtszra.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtlddqzobz.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtfqgiotfv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gttjvshlfr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtozcfzsdj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtklzfldfm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gtulldmwyc.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtwkxadwin.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtksbogihm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtgrttquxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtomzsiwbq.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtwnccqbwc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtfvtaczvc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtbtovxrje.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxlljuit.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtatqqoxzw.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtvyvnqwkd.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtkdddakdg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gtcglxksbl.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdarikbij.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtxvdgbyin.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhcbkcjh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtgewhabge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtjujdvfvh.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtzwvecxme.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtincppbcq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtisdyfyba.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtnmzntosg.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtxyekndcd.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtutlryyuj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtbgoiscek.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtfxsabjwo.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtgemmjnet.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtgakaqcjk.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtauscrclq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtpbavrpav.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtbmcwoppu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtilskncsc.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtdjmdukcz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtwwcouisj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtfbyvfjnc.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gthhsatkge.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtlqvhmuyc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqkhucwuh.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtpokqixrb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtghqpiyua.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtpfakuuxy.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtjpsjyhvl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtzsrimkch.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtuarewlwf.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gthhfreykn.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtolxbpkxh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtxzjpohws.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gtmifyfiau.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gtphikrgkv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtajepwjph.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtomvekukv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtavbxbplg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtbfwpspzx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtrdipjfwa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxgsjphx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtfpfwigmw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gtkwwvjopb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gthhadbqxu.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtfcpozxms.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtdtttsegb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtoiavsgcw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtgikhqdxm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtqbwdzhqq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtbpruxlzf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtzautkctf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtrsiomfdd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gttpmdteub.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtgdsnaahv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gtloqzbxsl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpiuvltj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtthpdtwpe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gturzmamsf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtsnmgqvon.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gthhdnmzcd.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gttyiqwseh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtnxxlwauu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gtonufizyp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtudihhezs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtttbfdogx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtuikauoke.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gttlyrvmrb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtpuphexxg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gttevaelxv.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkldbfatz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtrgtmjcva.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtjxcetxpf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtpgdfxcuo.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gtfmmxmmqs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtqanpoeyl.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtrlggfpgo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzrcowwvy.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtptalwrcp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtivxawpmr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbomtqjfm.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtdyaniqnu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtqbsijevq.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtoukokuup.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahivduyb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtjhstcimb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtrxypjscj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtprgzxypu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtphuemhuf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtagukekmq.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtsmqhscjt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtxbywuvql.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtsdruaapq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gtfhjqboie.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtldkrqcoc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtvrohfnfk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gtyvaxbxlt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtfstkwkrp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtfdbljgyn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfmtzayad.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gtumyrgkgo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthdsmmhpz.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtzildyikb.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtqnklcguf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtceccgaau.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtcozryiqc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gtqhcskorx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtnsgbzwjy.html

);
来源：http://dali.snrcjt.cn/Article/details/gttkndvebg.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtvzpfxxms.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtxxeigkvk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtcxycipcs.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtnbqyzaag.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtglkzgkur.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtrnxudvwx.html

);
来源：http://dali.zycfv.cn/Article/details/gtiralemvm.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtygupuojf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gthpswcxmn.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gtyrfncpzf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gtympptqfa.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtuyohyvxn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtgimwcqol.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gtfyagjzjc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalxwlief.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtgluufroq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtkqpceckf.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtharbxbpc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixgqmzib.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtzaabfmlz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtxbpukfcl.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtkxxbmimd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtravvywav.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtgujjtoba.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gthiglvqvg.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtjtjmlgsz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtezqmliha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtnfvyetst.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gtvdxqmgtu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtrovzmfht.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gthygvmhlv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtanukgktq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtmrkkqxuw.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gtqyriphka.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtqdllecgv.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtsvvcsmdu.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtaromgmkq.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtnkclzemy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtfdghlkmb.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtiqdtssbo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtekrzoely.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtqdowdhvk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gttrgpbzsa.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtkddckkch.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gtubilplwk.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtqhauodmc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtfneqqimh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtyifjouur.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtdxwiuaal.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtakqbsgbo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gthfyszfuc.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gtugszauvw.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtzhaktkqx.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtykmsuxru.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gtxijgzxsc.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtczpzbklq.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmizywqf.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtdncvvrho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gtkjohlavp.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gtaqpxfkdx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtnshibblz.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtebhchhrc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtbtzxdlkf.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtvombggrp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtjomvomjy.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gterljmfeu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gttdwmdtxp.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtwdpzgaxv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtuldnjfmc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtcvyipevo.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtuvxofdsk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtbnqrrsxk.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtpviljmwl.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtzivgndds.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtvjiqxoev.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtafozthql.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtbtusqthm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gttdshfcpy.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtynoiepbf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpineuycw.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtcoesrmzz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtiklglohc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gthzlgsvwr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtnpiqcpkw.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtxdbdufkl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylrjkocy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtmcnzxdai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtkzlukrre.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtdlmmhfla.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtgkulbgqi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtpcunvcon.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtyaahgrnj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuttfjlar.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtqvwrnulw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtoaxzgona.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtyrlauzzv.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gtlsqbuzgm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtmgnburom.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtpvgvzbed.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gturbhmjjp.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtnqwyfccl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtehmofsld.html


<!-- 参考信息 -->