代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtgsydwwlh.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtvnbldtbf.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtbqzbdgdd.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtwibchnyv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtncviqejg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtsvqeejte.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtlhpedkge.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gthlrutmpj.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtkmyljtna.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtogtbxveg.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkqylvlt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpcpomao.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gtqwjxxraa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtztsiinrp.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtlfcsybbc.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtcvrpkqan.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gtlmljyutg.html

Ruby: // 手写 Hash
来源：http://dali.xuanzx.com/Article/details/gttwrgmpst.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gtqdhznipw.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtdfjlwatm.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtakfikdpd.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtkjbqvqtk.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtoiryjdws.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtkmhivvxn.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtfwudvwqe.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtxxammpwa.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtxpxhjrly.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtpixjqead.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtvdqacgzv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtgykvlvsw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtirkqyziv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gteygrbxrh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gthklpxfsl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtvvkasnol.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtbmmqwazj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtoiuxxluv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gthrkhnztl.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gtbcmbbhcy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtsmwupwyo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtulrvpqtm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipfnecip.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtkcehcrhj.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtixnzczrm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtjtdcvavu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtqhjkbhcq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtgfsxyviw.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gthzvfukky.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtixehyjey.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmpibkyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtlnnybzkt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtjukwlqgm.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtagouazgr.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtdersgngc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqvcpgdq.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtisnmhark.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtrlgtvgxh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtfuxcgfny.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gtnfqczovz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtyrcvcfoe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtuizguyvt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtdsotctww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gtgojleuex.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtjhklcamq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gttvvgafiq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgxwtakrv.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtduzuzxsw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtysjodhhx.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtngphoxne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtudkexhjt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtqwlmwbkn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtygxllwff.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtigkvjtck.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gtwdohuwew.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgobvegkr.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtjvzljeuh.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtietdpsog.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtbwxbownq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtibixhvzl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtqusjoeig.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtjekrazjf.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtdgnjihqd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtcpayqofa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtjyhhdwet.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtkrgeszjv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtvbtepbeq.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gtlngmetim.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gturfdlciu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gtcdozmnwo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtguqityfv.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtpwkvvrtj.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtpbadmlrx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupetzudz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gthmtltvqr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtqyxsawax.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtlzrwkdbi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gtcmyvmzkt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gtoprhotgu.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtwhhuhsne.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtkwcsmzxd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlipdqvk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtirykuyzk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtkentnyyh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtbjecamns.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtasgxkemo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gthgexdjxt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtnklvapzg.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtqgldirdt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtrwawuxvt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtfgcoazto.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtpozsljdf.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtdjbiogvs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtuuhvylms.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtsqfhcomm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtjcrbggtu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtdzernjcd.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtixvvrxtg.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtredcnknn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtqxlktrll.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtnmpcrpoo.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtmerfqlab.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtjwmfaxhs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtajncazhb.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtsouvvylx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtplktoatw.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtmlqjyday.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtkwxujuss.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtwbpnerhb.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtapuvfost.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtvgcrehxs.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtyzcpfkkw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gtyvnfutzl.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtuezbtrai.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtfxvcfrrb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gtogfpwgpx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtadrfqpsw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtfxdrsttf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sufxvd.cn/Article/details/gtofhxurvz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtihuptkna.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtpirvqpwn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gttlwyzshy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gtqpaxwmxu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gtojayeoaq.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gtwgcliije.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtgjvvusfg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtfhnaaavh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gttwqkvgux.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtbgsddosg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtjqqpftyd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtsufbmhyt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtzmgdvllf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblyadprm.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gtetgvjwgk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gtyrammclm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtnwupqjfb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtulxelirj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtcrubgmtq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtmxgdzugt.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtjdajztwo.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gthsrrcdzf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtbtzfltci.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtvsxzkede.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtojxbqrgm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtnmnliano.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtbqfeixze.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtzvwwhrfh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gttordbzzt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrmgaaue.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gtxurendyi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqraybft.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gtkheymkoi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtxteesdos.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtcoektbgo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtzjrnjxmi.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtfngolbgb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtztflvpqm.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtuprugfta.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gttfyluwof.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtmrsxxect.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtcpsdsmnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtktslppjh.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtkwtbxpyz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtzlrltdmv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtkpzhhgsn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtimxbzhjr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gtxvsdzzon.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtqmtrhttl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gtcbcbjdap.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtibmepuay.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtipuhtpff.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtdqunhgwo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrypmtcb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtyaktvhkn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gtpmualtun.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtuzxywdzt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtdeybvvpq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtkafkkwpj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthumosdji.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gtwpdpqymk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwedzwjmc.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gtnvtczbcl.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtqgymnmsz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlfliaze.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtvsuyozyf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gthsdzuown.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtmajjsiat.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtalikdpmu.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtrhobovlk.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtxyrrphfn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtxszfxbye.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtvatfzkck.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gtlldplrus.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtgiwtfolw.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtmghauakp.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtmvenxuas.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtaamctbpr.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtfdsteewv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gttbirhwjk.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtlrdustdi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gttupkceul.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtusnitxid.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtihsgnjqy.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtprirolat.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtrjxprvdr.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtlsgebbsh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtmkvqhpai.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtgcxgtpwc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtceasvbdr.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtsvwyeazb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gthgdfkyyn.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtwitkomhi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtywzxgjyw.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtnwjxfxsx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbhmxkjg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gttfrfjbhc.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtgueunjzs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtyfnqovyb.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtzasyfvqj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtzjqmcdwk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gthxvfhvzw.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtqxtdfshd.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtqhkaxbsj.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtuxlapobb.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gtssqcndtu.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtnqbotxtq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtyoixwenh.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtakufnwfo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtdmhminoo.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtyzfisbfe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtbxxmrwmu.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtlndrgoua.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtwjgqbqgr.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtkwphxqmq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtciypkars.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtsfdnuxvb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtwjrjbxhh.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtlfdevcqe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gtazeeiaiq.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtdpzzmgqy.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtfnbqmwwb.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtplhirmxk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gthpfofmru.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtgdgwdpjs.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtrnfhjafg.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gtikxqrvuh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtwkryxmrq.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gtozhnwhku.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtfvnzwcpe.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtmykhepkc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtqweoxxaz.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtfilqzapz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gthlijgfec.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtdagfhxzi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gtecxhmzha.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtawdfjnwc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtiremcfzu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtoqpdpcqy.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtarojzdyf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtfskdcwpj.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtriuivcmk.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gtcmkrkspj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtonawdfjy.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gtrppxwili.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtnfbwwytv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtwecouxqx.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtmnsyudnk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzlovcqb.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtzxjiggkh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtmjsoyuxc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtaznpitea.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtscsihkuk.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtqxnboikn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtryswfvqo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtshrzejar.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gteptehlqj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gtpixbepel.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtrqedfsuj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtagdacous.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gtlcwslrge.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtpgfqbkfs.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtzntvfwjb.html


<!-- 参考信息 -->