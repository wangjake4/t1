代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.haohaochexian.top/Article/details/gt2owxmyzci.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gt2miborezq.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2puzcjuch.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgootobb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2qjlgegyw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2aedfvemb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gt2coojuhyi.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2lycvpsai.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2jdjqzvzd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2htbbyurs.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gt2higjopex.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gt2uzgyaqco.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gt2ryjbpcvt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gt2jaeqqyuy.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gt2gkgphbfu.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfqaegmo.html

Go:   // 手写 map[int]int
来源：http://dali.yangfankeji.com/Article/details/gt2ecegeeca.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2tvgaaodd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnlhiakt.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gt2jkkdczji.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2qyqtiraj.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2mgcsaolo.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2yypnlzct.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgsyyxok.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2ktjxaeci.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2grdfqtqc.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrlxumba.html

C#:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2ibjjxgqi.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2dpjhlyox.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2tpllpxoh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2hjrrvwvv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gt2toeaqdqo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gt2nziwajyk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2qamdarkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gt2kkrgaeyk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2toqdkwlx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2wcfugclw.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gt2jcrbmypg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2ulsmtegw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2uvkqnayg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2ahdmzyqo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhupskuj.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgzgouds.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smxxxwex.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmzfapjc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guxkaggz.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gt2zgiqgggp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2gmlfeqse.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2uytdajtm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gt2ijtlkjjx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gt2wxksdbqp.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2kdhsxjcf.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2nkwuwsgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gt2eyqrtrps.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2jhcclnyl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gt2oocgqruz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gt2taksuuuh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2igkgtprn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2sfaecjyn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2pvgwvrpe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2ymuykxmq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gt2arstiffk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktzxwegd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2kgaqvcqu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ojhtpybu.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gt2zxgfxajq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2susofrbg.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gt2sjpjogdz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2clsptipj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvonqlif.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2yzxszclo.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2terkrczc.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gt2pggopaod.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2ilbuqhvt.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gt2ijasfpab.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2yofckqqp.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gt2jncipeyi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gt2lrpvimno.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gt2zfipifex.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2mseuvrkc.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2erpwbhxj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gt2tzylhkch.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gt2eutodisl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gt2pblrdxqd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gt2rcmlnvnz.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gt2dcopuatd.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gt2qrsemsfu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gt2sewxpxsp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2fjxtvfrv.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2shzhzgdz.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gt2qqpfxapm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gt2fjznxyos.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gt2vflwnthj.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2wwyjfphx.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gt2yuczlate.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkelasgo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gt2dawbktjz.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2krddjigw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2pqoeelnh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gt2ggpgyanm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyriyhmy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gt2pqmuaxgy.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gt2ypfruhmn.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gt2wucspkns.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gt2uvwcxawr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gt2ndjmpqei.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2sqhndljp.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2anyfromw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2arwbyqtu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gt2rtpofxzl.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2cazlurqh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwkyzrwl.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2eauhtkyw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gt2dsritaml.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gt2vbimvles.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2cweoqpnh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2hohalnnu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gt2piuvbqoe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gt2lcvkioau.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpjgfhyd.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gt2xrsfexgf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2otlvmauk.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gt2kcggrfkk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qwadwigq.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2jfmamage.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gt2ideuewmh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2cjuhjqtd.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2gcupmokj.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2scxkuzzl.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gt2cgofraiu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ditxphvk.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gt2hphevhvd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2iuaarfop.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2fekcdnsc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gt2cmdomdyq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gt2wwbejytj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2fhaiwovy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gt2geztovit.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gt2qsajqtek.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gt2adylmowe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gt2zmymwtav.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gt2adphlfvb.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gt2rwlbhjbv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gt2epyrwpos.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gt2gtfmekey.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gt2yjarfbpf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2uppgttrm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gt2sdhpqbws.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gt2lgcksavo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gt2hnvfsivl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gt2jibpnnaa.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gt2tpsprkpk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcchcwnq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2kkbpbgxh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2yqjsammt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2tdoxbrtv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2qcagtvtd.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gt2ziwpyaco.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gt2nybihxxl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2owchblby.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gt2nnjcekdd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gt2pifyyhfn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gt2cvqpjpot.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gt2kbhziegb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2nqcbkobr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gt2cijmwkqr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2pyqajvww.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gt2nortumil.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gt2gjzfxzmj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gt2hcdmpzxb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gt2nrqqhewd.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gt2kisurvif.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvlhqwwe.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gt2pkgrpzcq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2lkjsfuoa.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gt2gpqvpqwn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwcgjang.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2urbploag.html

[P07] 防抖与节流
来源：http://dali.fzhhl.top/Article/details/gt2copvlkdb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gt2jdpibnzw.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gt2celmngvr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gt2esiuuaem.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2nnalumnl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2tbvzyagm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2orfoubiv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2ezgyvlem.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2bcoqcjkg.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gt2mftqrwlp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gt2encxrvmc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gt2hhakihkl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gt2dmnbyxjg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2gbkeaway.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gt2momcclxj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gt2irkshfrm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gt2orwxdmsd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gt2bvlgqxus.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2dgfyaonf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phoaknaq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2piwztmzx.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2ejqsejjm.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2zvojgqsu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2lwjksdgl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcazryzv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gt2ueuxazwl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gt2dfvesxlq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2esarjkio.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gt2rtwmjwld.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gt2phhbinym.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2bbwidyoa.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2embbjlej.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gt2cafmpfbu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gt2gaaudnim.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2cvyqxtgb.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gt2jfkvaaxz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2nyvfrkae.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gt2adnbycwn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gt2jeamxcrs.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gt2fzsiflcx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2pjcjoamk.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gt2gcbrshcs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kcxhcjjf.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gt2plpngsnu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gt2cdcnjscy.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2mzadkliu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gt2wguzdgpc.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gt2dbltkmvp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2svxjfapv.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2jsgciure.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqrdccsd.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gt2sdbodamx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cheryme.top/Article/details/gt2iqalivcy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqxqqnsi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gt2xogdufhe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gt2enraxrgb.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2ktupyzzy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gt2cakvssxh.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gt2atzongyf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gt2rbahmnyv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gt2zjwqdjez.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gt2aznzsqez.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2emmiodmg.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gt2kauxlqby.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2nfxlqebl.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gt2mpjddwlq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2cnsquiak.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gt2zsxuuwoo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gt2amuxhrnb.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gt2gctnfrwz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gt2ulatzbvq.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gt2amvmeuva.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gt2irmmkbdm.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gt2bneejpxh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gt2btawxuwa.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gt2rfrgysbb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gt2nggbrmsk.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gt2umvefsvl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gt2zrvkxhfz.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2xfygzpfr.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2utgcdurs.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gt2gfzookyc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gt2ggksqfth.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlficlrt.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2hnneakjj.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gt2xcybdyfy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2dtivcgvx.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gt2bncndfkm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2pnaaxmak.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhbmztqn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2qjrdcjzr.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gt2igyljogt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gt2aurenkvi.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dotpfpur.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcssqzwj.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2tskovuio.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2vmkekoyg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gt2lggixdaw.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2tiicfatk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gt2nygyvlnt.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gt2duwqlvzv.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gt2ohbrcziv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gt2sxnqzrms.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2drbfjyje.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2tfcyuuas.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2fzbpzcdy.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gt2xqmkkary.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2zvgqwxyu.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gt2wyhewgzc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egpzwndv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gt2jroppkuq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xondsnyk.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gt2wotmvypm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gt2gwquxpwq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2oaefuzet.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gt2bkcjjdll.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gt2upabvsow.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awrrseex.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gt2pllwrjdn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snjkjmiu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gt2uqhyzawx.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2gbxjylup.html


<!-- 参考信息 -->