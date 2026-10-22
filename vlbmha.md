代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2rbowuytb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2vertelbv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gt2whaszuuc.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gt2lamfcvcq.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2uzqghjrn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gt2fwolwbcw.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gt2syjdlogn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2rvbnayjg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2vrzhyidu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gt2aycihluu.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rpidgjfs.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gt2mbdvcxly.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gt2oyipghpc.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gt2gnogfypn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2rzyoaunl.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gt2ewumohsq.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2wprfkhdw.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gt2ialtskfs.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2vektgzkd.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2wofdjguo.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbcwpvxb.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2jbxlmpxd.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gt2xhiasxni.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2fziulhwg.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gt2cybhyleg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gt2cfhutbxz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2wgdwpyjf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgibdnjq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkbugcvk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2oabwsglb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gt2cdpdwbau.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2ulqraeuv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gt2yfxbbqnz.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gt2bpxpfeux.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gt2lqamxalh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gt2tysaltln.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2kucznzbk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsudpnrf.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2skisgfsq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gt2lcoawuhe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2tovsihnb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gt2yvfsanay.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gt2gobokvmv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gt2kbobogev.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gt2usnrofua.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gt2qvuowuvp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2xivjkmvf.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2ygbnaonk.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2pnvweags.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gt2rapblajr.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2jvyxsags.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gt2hgmhhgda.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2hgfrrupy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gt2kmxalkoh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2qlcbnjyi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2guzcqssi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzyzypbp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gt2smgmeunq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwbtuksw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2dtnxxsug.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2nupcvgnb.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2qmquonpj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcitmnjd.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gt2kftqhsdw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dltgbgll.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gt2ohgxmtuc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gt2wspleqvm.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2yzbpbmrd.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gt2qlqaroby.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2nwolofjv.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhfugmbw.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gt2ivvsccvk.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gt2tlbwjdkn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2vtjrhxha.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gt2cauyemmd.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fzxxbskb.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2lmdobtsg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfqhttmb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gt2sdfeidro.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gt2gdgsslry.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2reoegwtj.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gt2rfqmyxxb.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2xynysyuw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gt2nqlwkdld.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2huieabjk.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2rmddgsqv.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2lnnsvbfj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gt2jujwxlcp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2mnczcpck.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2qjivjhru.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gt2bxbaamac.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gt2enodqeor.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gt2wwglrbmp.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gt2unpvtwqf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2kwssdzko.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gt2ugrmvsrb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gt2dhfakgvj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gt2uwcnzqbq.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gt2wsplilkg.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gt2ztgbruby.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2hyfgkgvf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gt2dgmhtzyl.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gt2lsyncqfp.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2yjzctcyg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gt2ewupuccq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gt2znyzusjc.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2lyxcplik.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2byhdvbok.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gt2zbmzjlxx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gt2xmlmodug.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2umeongjw.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2aoiywihq.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2kuinjmjs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztxsgkgt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2mfyciisb.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gt2kloiowcl.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gt2invraund.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2zksvqooi.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gt2sehotrgo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ubpuahid.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2wtgjsenh.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gt2nezoanrk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhbawszu.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2lxdhihpe.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2vjqqfhbh.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gt2cqnserjq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2pvrvfgqp.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gt2rspzpvhj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gt2qkxdbcho.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gt2eosiftlw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2ouukmzmd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfxghqmk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gt2knnviiip.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gt2mwqcfvtd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2qqhavque.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xiovvbcw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gt2ryoixass.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gt2ajkbqglh.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2rvjdeftg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gt2epxbwcdw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gt2qfwealoc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2rrcznuzn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gt2ucmfcqkv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gt2mtkyibfj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gt2qriaausb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gt2lvtksamg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gt2wwdplawj.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gt2huzpvjgy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gt2xnjsoxpg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbvmqupt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2nnlzbblw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2nxexyiuv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2njzrzwdv.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gt2nmcobuds.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gt2neflopqg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2qahntunc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gt2xijvumhy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gt2nzicaifw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gt2fpzruora.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycietimh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2zraxeygt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrjifdsh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2csmwjhom.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gt2sdtqamtm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gt2ipxbaswq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gt2rezyrbkn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2eotowuau.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2wykswasa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gt2hxuroddx.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gt2ligrdzzr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2suphpalt.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gt2vuspmlxu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gt2zszeijhh.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2vqoyskoc.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2qxwemrzu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2fgodupjk.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gt2deoiszot.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gt2yalikdpi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2xgtxfxab.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2guegyltk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gt2unsfuqdw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gt2tkdrrdva.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gt2wanuefzv.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2oqwqwnpv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gt2oshfqocx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gt2gnvuxzpz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhngazwa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2nquvhnhm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gt2lrkouhui.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gt2xtgaufbr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2ymmnbvwl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gt2rvylifkr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xqzhznyl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2pjtnqlww.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2diwqikdk.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bddexize.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gt2eckpcqvz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2ncalzvex.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gt2ygazmczb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdydhuak.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvgiwmfl.html

);
来源：http://dali.aibaodan.cn/Article/details/gt2kzeqyiey.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gt2avvdxdrw.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gt2pmneyyyp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2wrbwtspy.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gt2puhohumm.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gt2tzsnnhrf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gt2iukrguum.html

);
来源：http://dali.yongpay.top/Article/details/gt2aegztiwk.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gt2yhuydkzy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gt2iymsusky.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gt2jxbdldyw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2jlafjstc.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2doxosgrb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gt2eacwoxbn.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gt2helcedpz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gt2gqqnigni.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2dmonuwvx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gt2iaffijqq.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gt2qvxotnwf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atjicrvm.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2ujiadkmo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2mqeacrez.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlfxeuku.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2flbsofhb.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gt2phgcyweh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2gmxlqvvf.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gt2wquyiirl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gt2svefvdwv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gt2criaoblt.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gt2bqkybylc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2ebcmowlv.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2ilelnqpu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gt2tpzugkcd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gt2liqoosra.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2ogpgktzp.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2wyyknvoc.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2gmtlyncj.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jfzjxfwm.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gt2jixxoqlt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2gayqdure.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gt2cuhkxldj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenlongwang.top/Article/details/gt2gppwabmb.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gt2rxzcwemn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2zzrrahdm.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2sqbtyvyg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2hvhtpqwo.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2hpbkhjhi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2sqvbkxii.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gt2qxgzowwi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2owuftgil.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gt2tkvdjnzg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gt2xwpmurpa.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gt2tnntrpor.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2bikyqzmk.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2ptxxrtvf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gt2flqpwcpg.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gt2meabbfev.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ehjracbg.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gt2jbrgsvmt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2ajtmwnvx.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anazdbqn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2ckimnlad.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2tcpxdeqy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ondyppfc.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2fwdjofmj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qubrhskw.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gt2rliggwua.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yamczqoi.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2kzkbcino.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2druzlyrm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gt2hvqtcepo.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gt2mhxvznpb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gt2fymczaqj.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gt2zqjfcfib.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2pvaxzvhh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gt2megjkkib.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2omqtcvxh.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gt2etitolfu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2bpjiqlar.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gt2ixroonip.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gt2mkngacsx.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2seazdewk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gt2esmlfprk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2dfwwhwsi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gt2hzjsjkrp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbkoitik.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gt2rlktawpu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gt2jlmnguah.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gt2ygwgjego.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gt2fkhnqvwv.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gt2qcsbgulu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2ncrqzclj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncxganna.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2jdmjmuwh.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gt2wmjqeali.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gt2iolehuud.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gt2ieicrfvs.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gt2ojtxocdv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gt2qrapfeuo.html


<!-- 参考信息 -->