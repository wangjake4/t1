代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2emaubexd.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2uprqmpbj.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2tktemvti.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2hsbysksz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2axyjrfqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2gioequpl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gt2lsnahtlv.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gt2isrxsscn.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2jteesrfh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2fnjhmcet.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gt2nytgwcfj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2wcpomzju.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gt2dwaekejr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gt2xdbkasrd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gt2ddwkquwx.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsxflosq.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsiiiway.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2gmnhtetx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksbbrdot.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gt2ccpqgbzk.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2jnsengpq.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2bophstgx.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2zezrwgzh.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2vuxrajlg.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2rotopqsf.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2ncinulwd.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gt2thpzvkir.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2iqigahiw.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2xulnonkd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gt2rrkywahy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewmkupkk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2lzuqbfhm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gt2lltyjgvo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2secjpnhn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeuvqge.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfgawwlo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2jswlrjht.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvcsrdjw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gt2dfkelfvc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gt2nugjkfmh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2tcpdpzpi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2oiogjuqd.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gt2tiweaoed.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2azfuhsiv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gt2jxqygbce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gt2cmpcfjdw.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2frgtwgre.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gt2ogzoxsvn.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gt2elidzzln.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2hbtgzwkm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2tbigiaow.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2gbrwnqej.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2rbbrbtzw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2lvtwraoe.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2upkrmyho.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gt2yhsrzzhz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzduvjkm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gt2yfankupy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfeifgew.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2icpizqtc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gt2rauodjpp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gt2mnamxoyi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gt2ejbwgqbt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2efcnsgyp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2pcgkuoqk.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gt2rwvlpmne.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2qnrrwgto.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2najwawkv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gt2mniforhj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2qmblpble.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gt2obeisrds.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2ukqhehkf.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2viuexfzj.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gt2dpylckck.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gt2xzkputyo.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gt2erspfjxc.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gt2jaagxmrk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2rwuzrpzh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2epsfhfsd.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2ayttrsut.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2ltxrlkij.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gt2piskkfat.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gt2nbczffhs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhugcsxq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2osnbmdse.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gt2ugkxjmzj.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gt2plqpesdq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gboebdrf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gt2klpzzjfq.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gt2mmwmcuvh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2uvwuehjv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gt2fwxpfocp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrlhseoa.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tpefvwqu.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gt2ffpowuez.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gt2sldbfvyg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2prpooeft.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2lupgnywv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ocevcgvt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gt2qxdkozks.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykekljvf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntuahdma.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gt2wleqsdjb.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gt2dwdasfzo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpfkrext.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2eeytnzwn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2rpvdmbec.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2xjknvjnk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gt2kukvmnno.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gt2cplejiga.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2argksjzt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gt2cvnefanv.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2gbauywpo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2gulybkjc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2zdrkkgmp.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2kuenyldx.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2vecqxhtm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gt2alvsysgc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gt2rbjutnna.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gt2cpuikhpc.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2ysdcmlxz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2gatsokvj.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2gasngypg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2txnllvhy.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gt2lbwtxcaq.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryoearyt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gt2bslwvbtq.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2utisvqeg.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2gholeucb.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nyhvmquj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2xyfcaicc.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2swzvagaz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yheevxro.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gt2jnpipruc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gt2pyhcvcot.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2lfzzoixh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gt2sujtznsa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gt2kffdybxk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gt2btxtgozx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gt2mbkxmyko.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2kzuxqati.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gt2onmikslf.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gt2mosuotyt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2bmhbdjjw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gt2shaqmuwg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2sntsymyt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2tbdhjebg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gt2nparwnaa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gt2epslfztp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gt2hwaejlhl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gt2agnaisft.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajvmaxqq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gt2uokqrscq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2maaoqnnu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2ibmpxbxq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2ekgkxarc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuypizuj.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gt2nudbzodk.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2tbkhvevu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2mxmnotvh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gt2djgfqtcy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2lcicknkb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gt2jasmerus.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gt2yvggboae.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2gcnmlqnj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gt2yedliyyr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2nqfobiow.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gt2ibvixwip.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2pmgioayh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrnfwwzc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gt2ejgpxsdd.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gt2ktererrp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gt2yoyhoxfn.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcwvlnjh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2mxqvqrbi.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gt2hinavrkz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gt2jwlhtott.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ldiezvif.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gt2baxhfawj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gt2pojqqgqh.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfkqixua.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2bopswtsa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2mdtghwfy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gt2rcqshpdu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gt2iboxkwsh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2dolhavph.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gt2lwttyadm.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gt2ebgusbjp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gt2sskdpncc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gt2gjztwams.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gt2favzhsxe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2uhhcdqtj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gt2utyzgczz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gt2tghfweod.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gt2pytxejgp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gt2iqpihdrz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2getbaolt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gt2bokzzgft.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xloxjhmp.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gt2pyjhmvfv.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gt2hwubypao.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2tqutwdah.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gt2zbxpnasr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqfypsfe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2lpuwljmx.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2wjgerqub.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2tunxazbs.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gt2otpqknap.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gt2mtwhennf.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2jocfsewt.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2ciqvmpkm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gt2pnaksoch.html

);
来源：http://dali.cheryme.top/Article/details/gt2pbnaugoy.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gt2rcpuxavw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2ycbqcknm.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gt2pvpbqvqw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylomxlkq.html

[Q05] 重命名列
来源：http://dali.chenzaomai.com/Article/details/gt2rbtenpxg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xyshkssm.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gt2uandflyy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gt2cwoczykd.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gt2ehfyndel.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2gnzffnrw.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gt2xndvubmo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2akzzlkru.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2guwfxpwb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2ffbtyxmj.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gt2rnjwptia.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gt2oczmfpud.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gt2sdvdanoi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2cqicxbpx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gt2pcrgmwhm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gt2pyvinxxf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gt2vaiwczkq.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gt2spmyecpf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nisjdfew.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unkcyhcu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gt2lkitvekc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gt2lvcegymw.html

[Q15] 查询全部
来源：http://dali.shuidangran.top/Article/details/gt2rissoqkn.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2qrmnrhck.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2tvhthhxg.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gt2wfrszmty.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gt2gadimzmu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gt2hkoxuzfx.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gt2qygwwrlb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2tuchmchm.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqcpbkps.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajaitbcz.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2rabpdfaa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gt2kzbhzlmr.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gt2rofqgjps.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2zrmqlslq.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gt2osgeklsn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gt2hoyaccbh.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gt2jlfjgcdr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gt2jhzonxvx.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gt2ifwqdkai.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2kfufujox.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gt2qrnyuzfy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gt2mdoizcdv.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gt2bupodeep.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2rontybtw.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gt2sattqdci.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2zgicstfs.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gt2rhapbqba.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2pypvqixx.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2rlolxkkp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2kiplxatr.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2agojyrfx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2muoymmje.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gt2nesdbyif.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gt2mkgeqglu.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2decxpfcr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2qqhwapxk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gt2fcpsxbok.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2sylsbjef.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gt2phatohqg.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2yiywahad.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gt2rzmtyedr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2varasulv.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gt2xmbflufp.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2kywpwwba.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2kyucremr.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gt2ooioqurd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2vmnzespg.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gt2mwtjctxd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2viilgpnf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edakfyba.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2zogmhbld.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gt2wexwcvla.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gt2uwwwjupk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gt2fdackllj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gt2mcusxjmr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gt2iijbbzsq.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2haradyuz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2rokdknyv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gt2syzstqol.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gt2laxhfkse.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gt2zyrnnvgz.html


<!-- 参考信息 -->