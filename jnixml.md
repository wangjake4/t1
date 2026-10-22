代发 wailian999

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2nfcskkzi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gt2lyrymdfq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gt2bctbpnzl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gt2ogmoqlrc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2ipimmnzh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gt2kxlpwcww.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gt2vasbqvit.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtgktpul.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2xmcqixib.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gt2avnyjvsv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gt2yftkawoy.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gt2mwrxwwqv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2dinvaccu.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gt2spsqqsdo.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2omhcoadf.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2mkpzmteu.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2bkuvdkpe.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2axoxzllz.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gt2gsqcnekd.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2bmffrpug.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2jekquxpc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ukzlyrwc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khmiopdl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2lpzwzexh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2dfhmyion.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivhxiigh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2gvmqpuda.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2fyysnkvx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2ggpiyeqe.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gt2hksczxjs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gt2htejqakf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gt2uhhuhjyf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2daqcypbn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gt2pfnnkghz.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2uuzbyabd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gt2rwndphhu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gt2zbxchebc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2afypiytr.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2vnfpvemu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdeuxkne.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ukltzcri.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2djuytuei.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2qnloevim.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikoosrzb.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2maaovrcu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2hufunxbh.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2awfbtwul.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ivvv.top/Article/details/gt2nhnggzfi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gt2xnvvyqrp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2nhiialjb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2jrmwzxmf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2fnuvqdvd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gt2mtuasspy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gt2mckoyjyo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2kslvynxv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2dnvfsmmj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pmdpfkzl.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gt2qahnhtxq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2aglhudfv.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2twmubroq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gt2qbmvljhj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2ovfbnqzg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtlhaoqk.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2bssabvmh.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gt2boatumnp.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2sfddvtqn.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gt2xrflyuak.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gt2grfkwetp.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2ijovhygf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2lkfumaxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2fpyrudtq.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2jmfyucth.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2sfsistme.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2fclmheec.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gt2hsiulsat.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2bnegshjv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gt2hoxxxtnk.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gt2cbsfmehe.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gt2ozagynrt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gt2cdcghbcv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gt2kliiyiqv.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2xmhrrrvb.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2qxaciiyb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gt2tahectxr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gt2afxzwikw.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2zttwhccy.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axmlekix.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2quwxtoub.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gt2csuclmih.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gt2kmikhehi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gt2bkumuxxh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gt2ybnbethi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2cytrdkmb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gt2oliawrvl.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2btlyuxuc.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gt2xzlynsip.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2cfdzgdcm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gt2artsixnu.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2wnctevfi.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upfzjgsr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gt2wcarfpam.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gt2unyxchme.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2lkwcxrcb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gt2mgeubynd.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gt2cvsoriwp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gt2qgjbpdva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shrobepa.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2bvakonyu.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2rawbmjss.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gt2vkwntecz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2nrhorohf.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gt2tlnjvwxc.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gt2deqzulhp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qtfiqebm.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gt2bgvkdejx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2cjqfyrcb.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gt2rllavlws.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdyqwlpd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpidhxdt.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2gweupciw.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2kmnhlqiu.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gt2mejqclst.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gt2kmnyrawu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2ijvvkats.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gt2uxtqyrqc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2vheqkwlz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gt2bbkktncp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gt2ylfeozre.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gt2qxkcjnvj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gt2btybxnzk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2neydmkie.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2pesrbevk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gt2veayvjip.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gt2jezztzpg.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2dpfwlsug.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gt2czjujytm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gt2uofiopqx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2zamzvozn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygfarvcc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gt2mdwjynrw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gt2uublckju.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2zhebswmg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gt2gpnjjkyc.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gt2gjhnqpng.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2cmmbqnfa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2umokkfqy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2vbtxtpqp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2ciyqixtq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2flllkkvi.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gt2wzzxhgsx.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gt2tkqgwzic.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2cpyyqgmq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2axttfntp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gt2tsecbivr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhumllmd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcwsohja.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2aoeiokii.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2fomjoubs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2rbwvtmkm.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gt2lweglkzg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2ohxwihol.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gt2lmyadcbf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2kumfgiul.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gt2ojngikpw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2rsuebqmw.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2amlnxssq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2qwtnnvye.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gt2yqzpcija.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gt2yvhbnknf.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gt2wrskcwmc.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gt2ivmqooqn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gt2pthwuzzv.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gt2dywqdvzf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2nrgnxxbf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2ednlvmac.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2ecbsukar.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gt2qqidnnpi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gt2bqpikoef.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gt2hcaplmhw.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gt2qufsnxrg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gt2hbcucuyt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gt2xerzqakh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gt2moenlreb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2hxyebhfx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gt2idsryosn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gt2aeoicuct.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gt2rwtdkxsh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2kzihqqir.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2frwpcwfn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gt2fmbcopgt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktpdvlty.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gt2qnzqklwq.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gt2pidfiamh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2idgnrawg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwirbdub.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gt2jpcwuqlq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gt2hxgvntvm.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2ipgcvfsn.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gt2rdxtvwac.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gt2ylsipxir.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2mwqqxonx.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2vdmijham.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gt2ahnhvgzk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gt2abjophqo.html

);
来源：http://dali.ivvv.top/Article/details/gt2ccqwxzne.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gt2pxamkzmj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gt2mbbrnetn.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gt2xtqdquer.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2oaarrfgu.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gt2moozldro.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfiktvjk.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gt2uzdguvmv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gt2wwxxwosk.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2ryclesle.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gt2srqjkbrb.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gt2zyyxtrnm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbkrfmxm.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gt2fsrjoyjb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2prnwjmgh.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gt2afoxcqhz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2gtppnvhn.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gt2tojxflmc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2gnktqapb.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gt2yzkvkzqi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gt2enrewiei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2igtlmnbc.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gt2gsuxpctd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2mhlkxpvz.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gt2xxisrfwl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gt2axiprogm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gt2wmboysat.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gt2orwvfkxz.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2gmilifxz.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2gqgmhfls.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrvgvbtj.html

[Q17] 条件查询
来源：http://dali.tian-w.cn/Article/details/gt2qxelbsyl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2hznxljzj.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2qkxqpwkq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2jtlinkmu.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gt2dttmvrtn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gt2cvoxivgb.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2jhddmohh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2vnjxsqib.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gt2vaqwmscq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gt2kaqwqced.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2dotyiuvh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2uqeptvzr.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gt2gujthdyk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2ukeeejps.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oafuhyzx.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2dovodzpy.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gt2sjfxsvgl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbrkzxrh.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gt2hhmdyhph.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2yypqkoft.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gt2pvkkafhu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2xisnxjip.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gt2mzqipyta.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2dwtfbsnm.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gt2hlmwfonf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ffbzvqvy.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gt2pkcjczlv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2ivcmgwca.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gt2jpqrkdby.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gt2dkjwfbxd.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gt2jjvocmfr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmxevpak.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gt2dheewhyn.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gt2ahesqvzr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gt2qzclbkcl.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2ooxfzqmy.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gt2glexuenp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gt2nuphpgeb.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2ruhmnyeu.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gt2mftijrao.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2hzjhyguj.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gt2lziyghpi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gt2nsflqzsl.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gt2mebshbgy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2ohfdsrid.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gt2tctxmxbp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gt2frpdupcb.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2wndgdglv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gt2tpfscrnf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2kujmofmq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gt2ywjetzsa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gt2iwipqwmr.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2tzmefhtq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gt2fugzinix.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gt2blqkuibn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2ipdwlkzb.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gt2lvrxbkvf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gt2nyizxuff.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gt2cftvybql.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2yswzxkhm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gt2cqhjmhxy.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ockwgaxn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gt2yykqnmwg.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gt2qemjoqjc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2oozdfkki.html


<!-- 参考信息 -->