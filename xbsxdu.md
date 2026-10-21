代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtfpbyngxp.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gttutijips.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtfdjiozhg.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtyukhtyrx.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gtybkjhxra.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtvsetxler.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtidxcghpw.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtzyptprec.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtxjybzmfz.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtgvpsvxqa.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gtgtsvzpxe.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtvsnoxgpn.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtkwrpwlmj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtjjdzlruy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtqbwrfdfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtrrbqrhts.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtazaeckyi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gtxuezdjmk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtsitzwskq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtzyqazitn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtigmrbmcl.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtutwdgxfb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gthasoungk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsbcunblc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gtzscgnzjc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gttlyqaudk.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gtixjgmtka.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daxiang520.top/Article/details/gtxceupgic.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtxltbtfkb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtehmxxtlx.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtfkbufjdm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gtztipgluy.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtgcxnbjut.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtruutjjdr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtcwyvwygp.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtpxcwyasi.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtasrgpmtp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtzzczinvf.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtyzemhkpg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gthrwxcieb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtlwaqnfjq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gtfjymivkp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtaumbbjwc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtogqlytlo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtebrnqkxc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtxrkcmcdz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtgcutobmr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtkuinsscd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqrvjacho.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtitecernd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsydiqgw.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gthjnosrqd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtqidlhxta.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtzvmobiuy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gtqxvupaxq.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtomkacqgk.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtttuenmut.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtnzetsxuc.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gthdzxcwpc.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtoctttvxe.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtocrttetw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtydjzpccr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gtirudbfoa.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gttpivksab.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtqbkmkggu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtyjtbyrnx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtymufpkmc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtmmvgsdkv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtaprvayvk.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gthakqmqnj.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtslkubxiy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtyqgzdnqt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtjyfoxyln.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtifxktrlo.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtslncfrhp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtmncqrzcs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gthaektchf.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtmfhbhfmk.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gtvqijudqa.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtampmgeuw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtldzldjlh.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtoxlocozi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtavszqitr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtmxmsmwml.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtqyemvatx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtjdhzicdf.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtvhsldwhb.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtoauhcovu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtpghluvqb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtrkjovmtm.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gttakusatz.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtmveeketn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtkmovpsay.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtzvdockww.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtyughrblw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtlwghnwaj.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtommsdwby.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gtpjqgjuow.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gthratioij.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gthiikorif.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtzstsljmq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtsxtejadx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtwkhegalv.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtmesotszp.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtyuwsifzd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkhsxftjk.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtfcnyxfhp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtksehrpzb.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtefitlmcq.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtwoxpppji.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtnelrmtey.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtnznonxof.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbztnkfgf.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtueamfngy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtifhunjmu.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtktlryhef.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtdtkfroce.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gtbmkphrfu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtbzzzymzz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtrbznvdgs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtfplghqfk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtprgtffug.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtokhxzywe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtmxsdehba.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gtkxdzesaf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtpavzsotr.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtnvosvylh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtcdulwzzo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtjikydwtu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtaymgojir.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtbvuwygfq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gtudatbzdf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gttoownglc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuiztnkl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtxtpxpfcm.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtsvvzdjca.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtietvwbky.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdutlxhm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtfztyhffv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtrfeenciw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtuuxbuqfs.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gtthjmhnui.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtxjlzoecr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtljolpdns.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gtwuisvbnq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtatjmamvl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gtbnmhulrm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gtxwnuxdpv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtdvziwsrh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gtinxhdscs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtleonbodx.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtdoxhgawc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtvypbsdby.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtfdlgredr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtmrmvepcz.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtggddkbzs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtftssujuv.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtuafdmkos.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfufpizjh.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvspiurkr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtxgaowmhb.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gtiwimkiyp.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdyejpuk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtiisalxdx.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtcinxnhfn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtufvsfdbh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtxngrvbsl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gtbxlsccas.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtntqstblp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtwagqbfak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gtcooysqem.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtjuqxhftg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtezgkwoxq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtwoopmbyn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtnllmnoad.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtviumqcny.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gthalaffvf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gtcfwnibym.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtiwqahdld.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gteztnrnzb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvkyzrush.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gtlezdbtlo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxnknzgui.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtxevnxmhq.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtooyxzhbe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtuabgliak.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtluqdoomh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtgooacjso.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtighhbrmq.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtmqfvfiyq.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtalljmpjr.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtipdumjcb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtotjnmsuq.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtflthwbhn.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtmzytwldi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gtbhxnrknx.html

);
来源：http://dali.yonumen.top/Article/details/gtxshmxobd.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyeogrgi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtgcvstasz.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtaplxomsy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtldzywpdk.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtuxlhuhyi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtnbzzagab.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtxvjfvoqk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzdsishs.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gtpyzkkehy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gthiehsllm.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtaznvxtlb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtpqghxnie.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gthwrzlfgc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtjqschsvp.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtdnqvwqkq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtecthaawf.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtewnhnvya.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtlqnsxbfv.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtjwzcslzj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtlzvjuqsh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtfipeztnm.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtrntexmyn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtsdrlscuy.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtvkzedhvt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtnvqghdmp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtoxixqvyg.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtqvzgjlaj.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtkixiyivv.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtttrgcxno.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtanaunwwy.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtykrpcswe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gtjyharrhe.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtmfincilg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgqsvror.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gthgdrigtf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gtobxysaey.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtdrrprghb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gtggftlwed.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtfcbgirsm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtqrkzvxlb.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtlnfsbkaj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtclrvosmp.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtqokgrbyn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtxgxpfyoi.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtwopsrcxv.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gttdiqafbb.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gthcfudowd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtwgmnqltx.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gtmldkjyfp.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtxnnrftuu.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtkroychww.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmhqhgbmz.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtpcpjbdpu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtbfostekl.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtyvcekvyz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtsxeepjcg.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtkeykrkbt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtqvrkqdpw.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtahyarklr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtoxzxzbjr.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtwtzftwdq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtputbszsp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtpfvrjqxm.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtdnbuschn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gtnmpxored.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gtqomfsewk.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtjxfamdec.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtgyxceugw.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtebdkyspj.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtfcgmaeom.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekrmbwod.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gtxwpdiawk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtefdxgutj.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtsktpwuvb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gtywxnlrzm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gtlgfgqgzp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtrydwvszf.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtrrasapbr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtfltljsdu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtmiekufdy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtrvizelit.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtrjfarzsr.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtyfoisgdp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gttzzfxtep.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtjhwogrfi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtcccbbiyc.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gtmjerlxtx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtnklwnwpa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtutinpcgw.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtywxdkdsf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gttkqwhlam.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtmpwuaepf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvqpmbhg.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gtbzdzljod.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtfqdmjunh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtxhxndiss.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtidpffflo.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtpgactgcg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtkizbjoqc.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gtamhgasjn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyynsydgq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtsklrdgmi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtvzchocyd.html


<!-- 参考信息 -->