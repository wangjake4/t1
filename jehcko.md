代发 wailian999

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2xflxbulz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2fdedmdhq.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gt2rsctqyau.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2eogeyhbp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfctluwd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gt2vicrqpot.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aayvlacw.html

Java: // 手写 HashMap
来源：http://dali.jqgfzy.top/Article/details/gt2uhpyjlpx.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gt2tcqcycpy.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvinvbmh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gt2syhxjghg.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gt2tqvooces.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gt2oteuugri.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gt2tutxhcne.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeaugsh.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2chrxoovc.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2qmzwavqr.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2jahxdulj.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2nawrljsa.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2ucbeyzkw.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gt2hwzqolwj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gt2bzymuffc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2mdbyxamc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2jhgdyacx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gt2fmnwggqv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2uowtfdzc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gasuxzng.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amejqkqg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2wsjkmidy.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gt2owmidqwt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gt2mskdscye.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gt2woxkqgyr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cctsqzvc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2rqoofytv.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2oavjqubp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gt2tkgmzqjj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqmjvivi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gt2jwsafelr.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gt2yrlvlyus.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2lkdmympd.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gt2jwwkfxgn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gt2srwhizrq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2qovueizx.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2yrviwiwi.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2lzicudlq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gt2iplrtiyg.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2lwlpdmji.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gt2stgfrzxl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gt2tuqsfztq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2tdtbdyhq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2sxofitnr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfihakph.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2wazpfcey.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gt2mxgaizal.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gt2xkohxtxv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gt2jzzpdhim.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2btdrshnm.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gt2aaeilmwj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hajbphat.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gt2lzbvsbfj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gt2wdgzpauz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gt2ctsnvbus.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.svipenyu.cn/Article/details/gt2kjnfmuva.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gt2eknatjyd.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gt2czxhfnrf.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gt2hnmfoxhz.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aywvvxym.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gt2qwadesbz.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gt2twlteoid.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odwqflum.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gt2trnbwhnt.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnrbheng.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2fzzlkpqf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2ofakllat.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvvboyec.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gt2pgosygcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2yugdqddq.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2upyuoiqv.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gt2llairxpk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gt2cbnlizwf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gt2vjbnpvjd.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2gxdltyln.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2vemuygrf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gt2lcekvmuo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2rwczitsw.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fijcsijk.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gt2lisrgpex.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gt2qelqbmnc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gt2ppywefiz.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2acjxcigg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2nblgwhqk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbhuzudh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibtfxrtk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gt2nkassruz.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gt2oqowlwmf.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gt2kxafyaqm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gt2kxktzcso.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gt2csuyndlg.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2cbkopufe.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2xozuzfou.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gt2aghiakfo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2tvrgknqf.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gt2hibpvikv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gt2agffzydy.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gt2dvgwlrhn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdttxth.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gt2pydlgodz.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2jswxqdgl.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2lztzdows.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkspwigd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gt2wbzyezzv.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2nmdqolbr.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2omhioxzn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lckbwgsg.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gt2trerasui.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2thddbrxc.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gt2pdlpgtve.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gt2stafqjzg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsxvimla.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2qztnkhqw.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2nqrccekb.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gt2mgxfgirn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gt2rczxzdxw.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2wtchgkpk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gt2knsczavz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gt2rqnyxhpl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2gebsysxh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2nlnpiqwu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhcyugus.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gt2vbuqvmij.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2rhlwwvpc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gt2ycsrkeou.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ltrzwqzh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gt2kehvflpm.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gt2qwocbxvg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gt2uqkhtlhi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gt2ssqxwzum.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2ppqfsgcs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2vfvokntl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gt2wslywdfd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gt2dujjyqev.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gt2onijfkts.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gt2digrjbbi.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2fnvwbjey.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytywwxco.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2znnriejw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2ugwaezsy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2oeqdmasu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2osrnjgog.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2kdxreqgr.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gt2vchklvrv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gt2vehqjokr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2lcbcduln.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2peeuzpqq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gt2enzhfxfr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gt2drkteoay.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2razemnrb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gt2jzcaarkn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gt2eebhyzki.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gt2xdxukjzc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zizboacu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gt2hphgvahp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gt2tmjkjpqz.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gt2uzmjhpek.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gt2bxpeutaw.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2frhjhurd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gt2lfnrckaz.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2zmmfngli.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gt2mrjrmybp.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kduacfuk.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwdfoiwm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywtdncgk.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2jddfziap.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2vnnosiaf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2wpglsrnd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gt2ziaofaui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gt2umyqzauf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2llmglhgb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2uwoudwxg.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gt2xotbovap.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gt2zvrglfjv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gt2szbjxrqy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gt2gwixozyl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2luwwpovr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfyhnmcp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gt2mzaxlniy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gt2prlsgnom.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rflpxxrg.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2cykandlz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gt2yapcwxrm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2yhvxsqmt.html

[Q01] 创建表
来源：http://dali.jianghu66.top/Article/details/gt2ryyopnwo.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2adonbxwr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2rrnxzwwy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2gjvtgply.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gt2aiuhsubr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgrkhfsc.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksghxkfh.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvhpjhue.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gt2sxyfiuvt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2dfcwqubk.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2ggmsgqyf.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gt2weqeomwj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gt2uvkaclvo.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2jjbhtgsa.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gt2zmfqbhff.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwbqllxz.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2fielgkii.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gt2dqzangee.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gt2foprpbev.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gt2ycankrav.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2uviwnbyn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gt2dziptmgo.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gt2uieexchl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gt2haenkgcu.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gt2xdymldod.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2jwoagfkb.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gt2umtdqbau.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2ibnxpcdw.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gt2gxsqqrbh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2yyzxfavl.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2inxqpixh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2taqmznql.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbkazytv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gt2ythqahxp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2ozwfbdct.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gt2cncudefc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2qfdosqzf.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvluadux.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpmsizoq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gt2lqipqoao.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gt2wvphelnu.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2sathwjzf.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2bybzvqep.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2xgnfpdho.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gt2ebksgprp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2zpmqsbkn.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gt2plowdynp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gt2vtyasjxg.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfeoapsz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gt2kuocedyv.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gt2ovdmmiyq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gt2axyhrajw.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gt2vnyhdhox.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcieaegs.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gt2qgrnsimr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2xiryapan.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gt2exdxcfub.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gt2rundjtdx.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvibnyov.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2fzsdhvhq.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyelywkl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gt2evsappbv.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gt2gzcdevza.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2pfdoazmq.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gt2qaqrolty.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2bfqmafqg.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gt2urehjhnc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efgxrclj.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjnhrqmp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2orzheoto.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gt2eptzvvbm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2sebtbmev.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gt2accjqosg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gt2hydyierk.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2abjhswnn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2ncyujhjz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gt2isfhhjmp.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gt2kwaeqgtj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gt2bivobowy.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zekyeyqo.html

SELECT * FROM (
来源：http://dali.ydzc1.top/Article/details/gt2pxgpzhyy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2ekjxqplx.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gt2xpqvvzuk.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gt2wqzfebkl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2vwflwlhe.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gt2zaifqdhd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2tuqkvqaj.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gt2djsiwatv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gt2kihlzhug.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gt2ojpytnoo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbusqiyz.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gt2sswvceoq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lsbwdrvd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlirofzp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gt2elosajlm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2twqckwfh.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2nrzikhul.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gt2skeybjis.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gt2ikgqjhii.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2rzknthle.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gt2wzghrltk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gt2zaolzroa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2edhtdeyg.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gt2ldyifisx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gt2wirgoxmd.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efscyfhv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gt2ouriwolt.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2cotukcnc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gt2ykbfhkgs.html


<!-- 参考信息 -->