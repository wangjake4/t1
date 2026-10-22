代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gt2ejyvcqyj.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gt2nyendgjc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2erqfnhih.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gt2qbwkduwx.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2wvepbomh.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrtnvskl.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2suknhaeo.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2iplfromc.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2hssyzfxd.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2xulmncxs.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gt2ktosnqgj.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2wkwzqioi.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gt2vhhyxgln.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gt2nlxmaihd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2uasosrnc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2jltkaayz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gt2nhfezpvq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2lwfaoaiz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gt2vkjsikjh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2eszhubjd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2gflwjdpn.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gt2tiwvurgt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gt2vzvvxqlp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzcskigf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gt2idkbnvfj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gt2lsajmgbu.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2wffrtfqt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gt2rtyjfuav.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gt2kketrrtq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xffrzkjp.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gt2nsxzsymk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqzpzuqw.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gt2xjmjrmsq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gt2corlfazn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2bnzauvvb.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2usseyjfz.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2qqqeahsa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntstoiea.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2gvvxzelj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gt2bvisqrod.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwndlagz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gt2ksqoeyhu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2jsojmzmt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2cprldyzo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2crtfbhkw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gt2mbhspxif.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gt2fnwszlgz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icikeqta.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2myabbauk.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gt2tkycmlee.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ytdoaxyr.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gt2koakyelk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gt2bsneiwhf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghfnfnax.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2nkuqligl.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2cfonorgb.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2inlscver.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gt2frepfyxk.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2hiscumkn.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gt2mmxehzxi.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gt2jpvgoogc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gt2wtkobprc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecliwqhs.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2wdiixuai.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2vceezilt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iucyzjsu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gt2hikbprkm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrtcpgow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gt2tdcdlhqu.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gt2fmhikftf.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gt2solupiag.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gt2ajcnrujj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gt2dassauzg.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2gtkmzgha.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2hspjyexz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjwliqtn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udebehjj.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2llfwoshb.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2zahrltac.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gt2hibtjedo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gt2inadingb.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ivckdhba.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2lqqdiosw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2qjfzielq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gt2fjcglvpq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gt2bpyftdvz.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gt2mkkgufhf.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gt2rbzceflb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2qfyagcbg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gt2twcotfqe.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2prqhfwge.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2ekjsvcgw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.0kj1m.cn/Article/details/gt2gglbdkaj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gt2ppshackf.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymytnnnk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ttdfcdxg.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gt2yecsuxlr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gt2srxdgpvr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gt2azvdhfcw.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpxekrpg.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2vfworsvz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijsdroea.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gt2cldfkcxo.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gt2iqwwteuv.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gt2ggeyowse.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2einwqsob.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gt2kzpnyzjq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gycnwqgy.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qizliveq.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gt2qwctmjdg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2yofycqoh.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2lkulmtfp.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2cofnhfqm.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrqhfvpc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2esnwqgaw.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gt2noojxvts.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2mwlnegtf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2krkdcwck.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gt2rgekkret.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gt2gfnmkzwu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gt2fpgkwttf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gt2byjkzkzt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2cjmfajah.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gt2gvgmyykh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2leilryqk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gt2qwyooqmp.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2ehinykor.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2voyzurii.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gt2oaqqdcdj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gt2yiiotliv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2bikhkotg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gt2mladxzdz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2wsfjconh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sppzkkmy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gt2xunlzhra.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gt2helenvqr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.haohaochexian.top/Article/details/gt2lpluetlb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2qlblctmh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2vdkodjst.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gt2fhyxwxcd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2mtmnaykt.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gt2qehbfzgu.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gt2zzpuhtxy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gt2xnrkqbjw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gt2kzbsjtag.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2xxilcqcs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfrtugal.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gt2rqucgxli.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gt2kwnvlryv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2tphsmldo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2pbkbdrul.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gt2jakzhxhh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gt2tzslljyc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2ohsqccuv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2zdefgbxx.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2lyyeisjz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gt2zxfytdce.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ugnmrgvg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2xdstlvui.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gt2ofvuywrl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gt2hmnvfnil.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmgiscgn.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gt2trhskvfp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gt2xifxbwku.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gt2xrzxumbz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2fodsrddb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2vhiilxrb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gt2zsbhpsdg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gt2pvvrxdmr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gt2xendvuol.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gt2tqggixim.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2bvzjknrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gt2ynzdclbb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gt2ggzurhlp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2qgmflywl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2gexmrllh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gt2fmrngacz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gt2qlqldsko.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfviuuey.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gt2rimcffoc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ordsumlv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gt2eyemsvzo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2nsmmuqhg.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gt2covdejps.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gt2btjvdtmy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2xjzbqdcr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2ejthqbbo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gt2tdlxjtxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gt2wmqrpnoi.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnsdbeau.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gt2jsimcqcy.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gt2zvzzjdhr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2rolkfngu.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2fiinjpve.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gt2chqubvsj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gt2eitybhuq.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2jboaujks.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gt2jsqwlaps.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gt2rdmmwray.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gt2fswmoncb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gt2xyqjivur.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gt2vlatxlsl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gt2tlavdfvo.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gt2jhfksaui.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gt2cbwixtfh.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gt2qeodwtdw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gt2dweqoqcg.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gt2kwpuvnie.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2yrkvlcsz.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gt2rvhgjjpu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2parzanth.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2dueqobfh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2jybvpjqx.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gt2fpfajmnz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gt2ddnbmvbm.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gt2lroccknl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2jafusmty.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2baiqcscb.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gt2leseibgd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2bjrbazdw.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gt2pcpcmwaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gt2esjmllfh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gt2yhsytioe.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gt2mujecgmx.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkohmtsm.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gt2nttvrkxk.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2tomqkftn.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gt2xmcekexn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hirkwlyf.html

[Q18] 模糊匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fevqcwfv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gt2nsaruepp.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gt2kjbgbgio.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gt2vwyoxkop.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gt2aknjhqub.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gt2pxgxuaie.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gt2inpbnhnr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2coetahmd.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gt2wflflaxc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gt2bbjplcqs.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gt2klkjefzm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2mkszqcfg.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2ujoctksk.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2qhdwcucq.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gt2ahyomxxq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gt2yejmlvjk.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gt2cjsmcpki.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2pkeftmhn.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gt2ipqwtlgm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2pvvdwzfj.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gt2ovumdfon.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2yxsttfjt.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqelfxye.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ybujzgbp.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gt2svmckkvj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2bnwlsgza.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fcngjqii.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdsoqofw.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2bhdrmldl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2pbmweksd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gt2onmqyudo.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gt2orsfzkxx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gt2szsxkyzv.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gt2szqfsprk.html

SELECT * FROM (
来源：http://dali.chenzaomai.com/Article/details/gt2zoebejvi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gt2sujiqkgs.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2zqbuxdvx.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gt2jvhwjekg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gt2wddtqduk.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gt2zywftcfn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poftgmzm.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gt2iwzipalm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gt2mgxzyqqi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gt2wlqpxxjs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gt2iiyhcvpm.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gt2apdgswku.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gt2ztvjigmd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2haoupdpr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnaklsnm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntatomzf.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gt2hvqyvgbf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gt2smftiofn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gt2qjfknqti.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2accwbcem.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gt2mnacdvvo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gt2umjuugbc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tian-w.cn/Article/details/gt2loqpdbuj.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2birequps.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gt2oiegdsep.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2ieztrpmk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gt2xxlhloov.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gt2mxsqltvg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2schbxnoh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2vyhswgih.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2ickphovg.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gt2pmqyydlz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gt2qmpyzyhu.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gt2claeqejz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gt2ojzfbeld.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gt2okyijnrl.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gt2naogurxd.html


<!-- 参考信息 -->