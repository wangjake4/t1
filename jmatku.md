代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtvwrrfqcp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtvrxingcs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtlbztuoyk.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtkeujnupk.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtnrpjzyfr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtozyibkaf.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtummjejti.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtikcftovh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtlzbqtufb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtujqkricn.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtexkvolor.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gtkcevcdbt.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtplnmgutv.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtrvquouct.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtjtufeodr.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtqsuhvrrq.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtzmdicube.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtaiduuetg.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtgheozvet.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtospnkyvp.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtgqozkzdh.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtnlhwkntf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtyitisphj.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtyrmotouv.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtlcwnzieq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwigacda.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukrgumqr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtgsfbkxcf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gthcexmjdd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.andypj.xyz/Article/details/gtsjgubxxz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtdjkxmetn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtpovkyvmm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtnspnaaxd.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gtuoosjiyq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtdjfjwkwx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtgwcighxb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.c1oappe.top/Article/details/gtbbdjreca.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtxsafdzol.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gteocpjklv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtkppdrtuy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntfdlmww.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gtwqbvsvnn.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtqaejclst.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtowqwgtvt.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gtcsouhrfn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtpwsnwmva.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtyqzpvbwr.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtxookmabu.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtskatmgxs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gteaexmnss.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gthlhfxmiv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtvfjlyqso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtwbylrmqc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtdlkuiphn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtgluedxjo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtrzlukyfb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtbbqwznum.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gtsmcbcbne.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtunjyxtqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtookhmzcf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthqlsyufq.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gthpmwwrdf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthfabhtkc.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtbnuykcle.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvnloutz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtsibhdhzr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.svipenyu.cn/Article/details/gtecsbofdr.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtwaxxnbgh.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtqdgxmkjr.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtwkeylwqx.html

Ruby: Thread.new { f }
来源：http://dali.xuetiantiany.cn/Article/details/gtajtwndmt.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtwizzchqv.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gtqoktucau.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptokhknx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtavudivnl.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtzishrkha.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gttpwyshae.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtpvaynxnj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtfkpfvpyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtptilkiml.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtujwjvgpw.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtpmvsveyv.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtyczvsfft.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtxusfzxiw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtcvpfwfgl.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtokgfcpcp.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtpzfzelww.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtdolhszmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtpsqaoaqx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtwaycsywk.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtdjghavgz.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtxvwqfbha.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gthfqbkcej.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfdtzagvc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtpamaewkc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtppzgbver.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtnonhewfs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtqprnxndk.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbjzsflo.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtieftumsk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtmkqjxxwv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtnmgnpbxu.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtvmsswsen.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gthtrobien.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtrgaedvrt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtdurgedhu.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gtqxiwxabw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtcwwvuksn.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtrmyuceqr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtcwkfstbw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gttvmaiysp.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtxngypshg.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtdlnqxddk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtopfpdgge.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtpqqcthgl.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gtzpyzuktr.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtatzygppp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtavwmkldr.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtojpeghqo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtacpzegbo.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtryrvsetb.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtfjoimmjb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtfkayfory.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtgubzfqis.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gthapbtgtq.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdflrtekv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtogjkbuff.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gtdfwnedkj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtzkpmysgt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtzlceopti.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtlwugngrb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtzxsymikq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtwhbfojbv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtxjrvhaxi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtwxllgykv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtuhhsdmpv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtxwlxnpyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtjmkmiobk.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtikpubkyt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtxadzksdq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gtpkvigbla.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtnwhnyqrx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtxvzafrny.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gthfwyoaid.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtinztfmpd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtxhwvtisj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtniwrgudu.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gttxztxzaa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gtdyyeaigm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gthyiedvrb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtxmgasolq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtgajrcjhy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gtkkxvyksz.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtocokmiiy.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrfoyraa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtwzehjkkc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtcqgzcxgk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsstzwdj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtuenliqnd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gtaqistznp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gttkqiqjkg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtyvjiawqg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtacnzwaqn.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtbozappry.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtwgznrach.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gtlqqighyn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljlimvgj.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gttioejaqz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtylrdjptf.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gtvirxbwoh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtxmnznnlh.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytqsjhwe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gthlpsclji.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtafwjqrwy.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnecposeu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gtzllwaesc.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gtdizqqifz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtakonttme.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtiyvojnky.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gtkuurxssn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gtgnvcifry.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtoyokaubj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtyrgvvfbo.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtcpgfmwqc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtzpwszlxd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtofnnesbp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtrpmujmrj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtdywicvdo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtmrszvrby.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtkjfqfhzf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gteywqdiko.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gtqjwganfu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmyijihic.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gthjmchqfe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzgywtxfu.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtbhfyjjnc.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtzczolrox.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtamwkxurf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtrbwrxocg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtacmcbkwa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtrhycxucr.html

);
来源：http://dali.hysaishi.cn/Article/details/gtxbjtrywe.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gtlaljycfx.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtuwpfjanh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtwdazdsyc.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtizsnylvl.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtyntbydnf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxrsfbaj.html

);
来源：http://dali.dianchejie.cn/Article/details/gtckqxwzob.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtpvytgcrx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtgfzbzoof.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtliqtvbtq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gtqpuyohaj.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtqygyvtxk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtbngrplfk.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtaywvzdyw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gttzhhvzrf.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtqpjdjsqy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtsktokytl.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtcendblml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtzdqpnnqq.html

[Q09] 创建唯一索引
来源：http://dali.yvedp.cn/Article/details/gtrtkqkllj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtlwybignd.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gtknjpqpyg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtycivmpru.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtpcoxkvzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtksudzyop.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gtfldjwpok.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtstzyjogg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyqslrgj.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtxyjeyilp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtrdmvxcoj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtfhvyejvj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtwtymzhom.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gtxjapvoqr.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtkqshxnxb.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gttvuyorjb.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtkjxganrg.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtcgjxhvwx.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtrlczsthi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtnzgapmdw.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtmspfeton.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtvuggfinw.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtcnieinwm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtynswcque.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxiqdplv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtqitjkvny.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtwzhikrby.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtejyosnqx.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gtpdpblrla.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtuzybbabh.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtlyiiiwky.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtvckgooqq.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtaxsangib.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtcevfbykc.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gtfuydtogc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtqgiipwjl.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gthysfymbj.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtsehkfpqy.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gtspzdlqbn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtkduozykp.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtoaonnqbw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtsxsgqzfe.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtwhlzbtyk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkvkzhvi.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtiowhhwqv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtqcejaadg.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtwexonvjp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtuczluley.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtcppbjlyr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gthxbmutph.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtaoyllvac.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gtdvmajjsa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqukwdewy.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtedwisahc.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gtgnvirodz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtolgdjfxg.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtsfgfvvyt.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gtjmfrplya.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtxbowyaxp.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtwjazdchn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtnibmddif.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtnigjempj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gtucsroqtv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gtibqeuewa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtvhhxzplu.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtckigcifv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gtvgevybut.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtibturnfc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtkzdvpnrk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtznjkwgte.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gtpioptwto.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtzjdngfdq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtenwgneyw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtqsfcyrof.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gtxijetqwx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtkqmhwfly.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtkatjvyfo.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtvaedyktc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtemeispyd.html


<!-- 参考信息 -->