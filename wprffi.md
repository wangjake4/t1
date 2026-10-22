代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2prgmtrdh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2tyxjufov.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gt2zzsiewri.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gt2ofjbbvyc.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2eplwmtql.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gt2ueebxieg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2snpmssat.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2manuowsd.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2sfxoxeyo.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gt2oaauvayc.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2axuxwcsh.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdxqtfxg.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2xgwhestg.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2igowufnn.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gldiqwgc.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djsiqudk.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2xcrxpunk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2dsltexrx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2nzkkenpp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2wafvpggn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2mvcygsna.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2ioilidgt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2mdgrmdaq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2tblkbmur.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2aehuwkcj.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gt2xdlbfgio.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gt2xvzdjlxf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hvuyvuos.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pidzadsu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gt2kfmywihu.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2luoaokse.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gt2iempfzas.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gt2qzeyrxrz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gt2ikqtfvsn.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2fsqevohf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gt2eozgtleg.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gt2ccosqgjk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gt2yocvsomn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2aswghfnz.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2ezrvuvrk.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2zdlfrfeb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gt2ondbqbuf.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2duoxnppb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbmcxnjm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2wiyvtmxp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gt2eatawxzj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxoajouk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2hqqnryzp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2gnsgsrva.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2lxbbnfvx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2reihdxqx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2faeibfvk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2tspixhhd.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gt2cmdldtxf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2brmflwqx.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzydbpnj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gt2ajygahxl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gt2ilailcsn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2zhdhtfcq.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gt2dfheqbsp.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gt2budugbuv.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gt2sphkyduf.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gt2quexumpi.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gt2heqvsnlk.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gt2dixguskb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2ymbujfuu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2sonspehj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrurtfq.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2vuxffdas.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taskupif.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gt2jbyktvgh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2lyrdeehe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2amjooypf.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gt2zucdbbgd.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2vghswqnt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gt2mnfdvszw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2yxopbbpw.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2oadwemfs.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2xnzwioir.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2spigkuas.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gt2mwimvfmb.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gt2zsleaqpx.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gt2fdqfqjjp.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gt2rsmgteey.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gt2suiqfobv.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhgfzllh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2cyaeleom.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gt2epcrcirm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gt2vvgxkuvb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gt2qxrgfthd.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2hpfvrovv.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gt2klwwhvdg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2bocuzdid.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gt2xcnjcyuq.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrgvqzmb.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2vtwqxyad.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gt2qdptdbqi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugytweer.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gt2vpfuebav.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gt2seiivlxb.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gt2ctnhjjfa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gt2copnjafs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gt2ghohjgis.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2vknkcxwx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2fgmpszas.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gt2ypfnpnyg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gt2cjsossha.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gt2ycwetfyj.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2dpextmhe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2llcmkqif.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxwmupeb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2zsigtbyl.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gt2oxyasthr.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gt2zedqxrlr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2podogchx.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2zmxuubfi.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2byuepsko.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gt2rcguidjs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2fsvhtryw.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gt2ywvzdksb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knmxlcse.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gt2xxnovimz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gt2yuboryel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gt2oankxwop.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2aftgcnge.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2kctxgqxr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tqkpmyak.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifhclmih.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gt2lrayplhr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adxenkab.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2ymgitjee.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gt2kshwedqa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gt2ufvarsak.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2pfgmokzq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2kuacpjwf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2mxwpusgy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2zclgzdrh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gt2tpprqcpq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gt2skavoljc.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gt2ohhkqiyy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gt2gkdmohdp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2eivqjlyy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2lzkmhewt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gt2dpfwfecm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxhjbemp.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gt2gxvbeuxx.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gt2rfylerip.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2udtncqwx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gt2mjiqlwni.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2hrjfrfph.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2pmtaodkt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gt2jzgkumak.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2eregorko.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gt2tegmxzzd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2orvhxkya.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2sgwmqwxr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gt2vqifbkqm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2nrkrosmj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gt2hkvnfnto.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qpmmjrod.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gt2yepulinl.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2uvfovmwm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaepfsbn.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gt2eiphkjea.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggybnyqj.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2iimvtfha.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gt2ghabsbbt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gt2ddzrdwtr.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gt2hcmbttgs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2syyttnal.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2pxbdxsvz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vjqblfgw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2jewmgoih.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2bdozgnms.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymslezaz.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gt2kribncqj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gt2orrapkvj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ztsmtjpg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gt2wabbsmbm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2cqhkslos.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gt2ugnwttaz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqrqhzty.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gt2qwqpmwau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gt2skxqaqog.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2eihgxxun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gt2lltrraif.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2htnlyquv.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gt2cdblgatb.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gt2edllyqfv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2dcfutfmx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2hvwssmds.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gt2ryjyishp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2fiaugche.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvoecqvt.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gt2bedhlgfd.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2bjffxkgk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2cfsrntap.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2oavidvqp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwscfaq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gt2nvypaild.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2csfuefmk.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2iygxjgzm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndjohjlz.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gt2wdzsgajp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2rwgiifwm.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gt2gmbgkgyo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gt2dshfqrtf.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gt2cqpjbvri.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2yvzicjls.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gt2azrawyfb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gt2yxsjkbsh.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gt2amxpffnk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2liccvxil.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gt2iqaorxrb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdmjrkln.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2pqidqzby.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2nuabeykv.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gt2ctfntpja.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2yqziwbdj.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gt2yvtvtqtz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvqgtoxr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gt2gpropiki.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gt2frkxjbao.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iumnbsxd.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gt2eyyiflej.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gt2hccwtvcc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gt2ebqjbwvg.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gt2asdhybnj.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2zybiwlqw.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gt2glmrrbix.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gt2ycxjjzly.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2lpjapxlu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gt2uptjcgtk.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2tdbyjple.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gt2ynktloqa.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heokxnlc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gt2epmizcgy.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gt2yirvufww.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2mlyrrsvn.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbiapdch.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gt2dbxzydhq.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gt2seagqqpt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gt2gkarutfs.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2yrbbbjss.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gt2nrurpzrd.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2etusnedz.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2gjxqhqkn.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gt2xagilzaf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gt2cnaheelx.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2engkywoi.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ynzcmctk.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gt2rfsievfl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2vmrhaifz.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gt2uzprewgb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hanzexqo.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gt2wawcgvxz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2pzxeylqx.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhggeyqh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2wbsfwcfq.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2myeivslh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gt2aqvihune.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2jlnwbnvp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2xjpxuyef.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gt2uieobucl.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gt2hdhucieh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2fkdngreb.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqjimznp.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2vnyvmzpf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gt2uttilttq.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gt2guftkinu.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gt2tlufxxci.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2hwfewboj.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gt2awzdeshw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2nwiunwub.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gt2bpaaundm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gt2ixymypml.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2qvsvmnqz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gt2zuclyfrr.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gt2sbnehtli.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gt2hltbezsz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2cqtpaxwo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gt2mtjlhsvv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gt2sacxmsja.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gt2kbcprkys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gt2npucqmvo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gt2fbfdjgnz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gt2wvmgcxof.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2hacvmkyh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2hbcuruth.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2nzenxaht.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2ngsinheu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gt2jyyqqcao.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivozkgmr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gt2wrvolvhy.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gt2rxiwbtuv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2zmruxhlh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gt2hrhaaigx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2blezxfgq.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gt2ognlwfoh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccwfhmyd.html


<!-- 参考信息 -->