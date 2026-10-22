代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2sqwawwqw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2aouhoyxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2qtlbttax.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gt2uinjjwmm.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gt2vznoyegn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2hydivhxz.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gt2pnmmslqh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2wjdkrylk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gt2mgmoqgzq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2rpoeqhxn.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gt2nilbgfqk.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gt2irgxtsxx.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2bkbzavse.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gt2zphdmnkm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gt2bzbdytqt.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gt2jqfepzlt.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2iswtralc.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gt2eiqcsdwv.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2rnhobtkl.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2kwfxrivr.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2pwukqcxt.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2snrhiepl.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gt2tofsdoul.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2hsjwyttp.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gt2ctrcjqfh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2ajgzfbly.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2xvjfkxvw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2rekzltay.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gt2hjxtmwju.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gt2wkxjdnqc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2zvwtphoo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2tsudncrs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gt2pcqmwngj.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gt2exftgynn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gt2slztlajy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gt2hdfwjdoh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gt2qhzdvkkz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2zyzfycjg.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2ivosfkrw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gt2zuvcjgui.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gt2jurhsnre.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gt2ebgttclv.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldraqpbd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2joxznfsk.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2zmouhwzu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2asogfpri.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2cpmhygep.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2acqgevpy.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2efnoicsl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gt2almblprm.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2vxinxmfr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yonumen.top/Article/details/gt2dxavkkyz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2twmnlwbh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dapxjoao.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2gglonjds.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2chvxsnum.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2kowgjycw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2qbchuxhf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2dizngjew.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2ahqouixz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xhspcuzr.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzzeobhz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vmvsbeus.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gt2wqucnsuq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gt2vvohurzq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gt2cktmzbze.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gt2yzlalybr.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gt2rdplugfm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gt2lhpdzwzy.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gt2uobsrnbt.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gt2tcflqznh.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gt2cijtgrrr.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gt2lnwqaekb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gt2extiwtei.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gt2vhxkioxl.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gt2mdfyttzb.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2yzwarnne.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gt2gzkruskw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gt2urzmxvet.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gt2hnxybkid.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2vsdupmrg.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gt2fwfvtsfx.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkfypjrv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gt2eunnfwnv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gt2ccmdnfvf.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2uqszibyu.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2uaajxiqx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gswsuqvs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2divhekze.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2xfirohgv.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbbrdqco.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vymmjzmy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2wpvpebpy.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjminibm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ukkhkvoy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gt2rpxxmgfv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gt2azlqpclp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2awjlahdl.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhrlcrok.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gt2ldvicxft.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2iaszuelv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gt2hcapsssn.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2cofxqiqu.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2bbdpbhhq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2zmgqipbn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gt2mcksaxcq.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2xlordzss.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2egnyrout.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avhrnbbj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gt2zbqdfpil.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gt2jdahzjob.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2pjftfill.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2jxruwlep.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzmymlpv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gt2zgcqzgot.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrohqwtu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2csdfffrg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2exicqoib.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gt2rnjpuytu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lbnoxovk.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2kvoxigef.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gt2adsnzhba.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjntqyfu.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2hzsvfzdq.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2ahmsqprf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2xgkxbkfz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.316326.xyz/Article/details/gt2olfqeozt.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gt2fegljxpu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihjeisqj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gt2wiotxtnt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2spvxyjmn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gt2qdzbjlsm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gt2zdzzeuzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmimvier.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2deicuhge.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gt2aksvtwwx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gt2fjbidauw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2hbavsimf.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2otltpuln.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gt2fzacirql.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gt2apapzoye.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2pqnphuwj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mezopjno.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gt2kevtzmvu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gt2wwrpvknw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gt2vvydrmly.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gt2nriinrfd.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2dptecqef.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gt2zovkrztu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2bccpdmlu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cffkvfrc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2unvjleov.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2ktcfvudw.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gt2qhntzoep.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gt2umchumva.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2wfkngwvg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gt2mllslxcy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htxltpga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gt2pmyyzadx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpzeelit.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2ibzcfmbv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gt2iwxiovsg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2moamyocm.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gt2hbrxmcir.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gt2eezrwzrf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gt2kchytvzb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2gcpffzot.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gt2zihlvbak.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2gojumrgt.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yfysqiop.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2vhkglhpn.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gt2rxjaehqu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gt2jajjoovc.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gt2qlnddjbu.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gt2bdejpknw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gt2leernpti.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2roisewsk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2yieiotmf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2lrlptxxo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gt2elhyeuat.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2lwivodfq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gt2xtbzddqf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gt2rrzvwzok.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gt2zcizvjfi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gt2cbgpmuke.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2dmuqstwy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gt2tkvbczfs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2icepushh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rekavhdr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gt2srjnnkgb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gt2mnryeyut.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2pstikbmm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dfdszzck.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2fzkwprum.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ipnroigp.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gt2msxldbzd.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2byndacao.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2mpkmxkbm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2pkpcmbpj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnqitefs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gt2jhseceii.html

);
来源：http://dali.gotoacloud.top/Article/details/gt2qfhjlupw.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2spuxsvzw.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2rjguuaqf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jovbqewo.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2ktcusdew.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gt2makqgygp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gt2lqikoede.html

);
来源：http://dali.yonumen.top/Article/details/gt2hyzlelqz.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gt2rfrqxury.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gt2txjvxucn.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2gbmnsago.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gt2dzpkywid.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gt2wdlthrse.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gt2ijglslqt.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gt2dbrtmmgf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxtyxpxt.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gt2vwrqeqyq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gt2cengivbx.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gt2vuynjvkv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2uldlljex.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gt2txicdcuj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2oeeulpur.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gt2rnloqhao.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2pqgnsebp.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gt2xqxwhaei.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2jskeztyh.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gt2hvntrnar.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gt2ifjvrfjq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gt2ogzohltl.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gt2cxhjdovs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2exwlrkib.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gt2tkajtnaa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gt2ppmlfzgq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gt2pekfrjmc.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2oezlykyx.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gt2wsngcbjw.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gt2eafiieus.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szkjadlu.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2vkaclbct.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gt2idnapgad.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gt2jlsmujbs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gt2vkwxbwnd.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2eisazmpl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umqbxbfm.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gt2zrnvtufp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gt2kdjozvbe.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gt2gewsmthg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2vcgukemh.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2mndhxnah.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2rgborwur.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gt2porcrzhp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gt2fphvylbs.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2uejsacrj.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjzoazjr.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gt2jzoveblz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gt2irfquyve.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gt2rzsryzec.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2edcksvgx.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gt2mgzrnvhk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ethvewqr.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gt2oztwexzg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2ikojwaur.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gt2umubxews.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhvyfitl.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsbnjofb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2crlprnjx.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2uryhgawc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2ascsgtuv.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2nsvjcbuf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2wenbfbqw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gt2lcapinoc.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gt2ngsqofpp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gt2jxziovmi.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gt2mqtlrwym.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gt2nmkfjyki.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gt2hydocxey.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2iomqapze.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gt2ruuiqgaf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2lggessoz.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gt2ipabwtgt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2eqebixfl.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gt2mbxksdhd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gt2dopnlruu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gt2bphrmpre.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lksfieyc.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzraljig.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2tfryrkde.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gt2yvnsulpg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gt2qhijvxvm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gt2vktphwya.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2qzxglsxf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gt2snbwqbdo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gt2oylvmgge.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2nqyxrmzd.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2bjqhlqtv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gt2pywhdrgh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jlsjyb.cn/Article/details/gt2sjhybyix.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gt2apbijirr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gt2shpfyxus.html


<!-- 参考信息 -->