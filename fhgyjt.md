代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytbycgqe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gt2nkbrfwvv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecgrsbqy.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gt2pscxuhkf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2xurzsfml.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2edtfblje.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2djojiuaf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2wltyetby.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2zcvfjhsw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gt2ojglxjnz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2golpugop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2bmqbjync.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gt2wubfdxow.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2cgzsvpdl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gt2nuaknamu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2jufhbmvi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2rgbjbjxn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gt2tcuclgzo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gt2ilxekead.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gt2vjcfbdgl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gt2eggbqegj.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gt2rcddamxg.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2gqslvede.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifrfbufh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gt2uwwtuqfb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2aycglhso.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2pidhgazu.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gt2qzbpzlfh.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2odelfvie.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2edardfid.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2pjutvihc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sctmgsgq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gt2vldsqvea.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gt2kysgznfo.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gt2dsqlzwtn.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gt2kassxsso.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hblberwg.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gt2wfsmnqcp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuugeezy.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gt2wftxpzyr.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyihzlba.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gt2qfcnjbny.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2lwfngakp.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2qtebenlk.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2jmaatpbf.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2euvtjnbl.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gt2yzlzkiug.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2dlojkcpi.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2leyhlaub.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2bpjhomdo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnpsngzc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2phfwcswj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvloszbp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2mvrcbzzu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2bmhshcpb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2woaaatpk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gt2ccbfsaai.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gt2mdfwpzgg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gt2hkpamcse.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gt2uvwydriq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gt2vfojobyr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2ehgozvmm.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gt2ehdwhivh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kghuxtsc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2rcksablk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2cdsxvjiq.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gt2ukhnjegk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gt2hbpocyhp.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2whtcgdcj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2udpcggcu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2mafndskg.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2hmploznp.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkchpwnw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gt2ojxovtmt.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2malfdhcv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gt2dmmqhkju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gt2iaudfvjs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2vvlvqehp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoyhxduc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2tdswvgay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2fhoarrso.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gt2wemeczxt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gt2byxoswzw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gt2fiwuyoht.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2uoewwabr.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gt2eplbyqfi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wfterbph.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gt2hwisqtip.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gt2aplpgfkk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2esurhwja.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2gkzcpglv.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2dstfmmew.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gt2xniscsup.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2mocqgavb.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gt2rbsssmqf.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gt2vkigkujr.html

[O02] 使用线程池
来源：http://dali.yvedp.cn/Article/details/gt2tzvnpicu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfxiyjxe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gt2drrhhftp.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2hojsmpmy.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2yfzylljp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gt2zfwsnzwm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gt2xjmqywod.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gt2catjkjdf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2yarxmxbo.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gt2uymxejij.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2clbjpujo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaukxmk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gt2pkqfwoef.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2ewhyfxwf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2ctuejsaq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gt2xldlmlua.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2pkvzzsge.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdidgosp.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gt2ngfgwzhh.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gt2mwbyovhd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlwozgps.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hgqluzzp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2kmhtsfvn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2svctvjsv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyyegjys.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gt2deucqrgt.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gt2kmwhdila.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gt2qfxcwbhs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2fahjefbw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clxgopwr.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhlapfbq.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2ljtnufmr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gt2pqykrtcc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxcivxei.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2awaeyzjj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gt2grqzgrwp.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gt2ooztnrtn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gt2hkembgky.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gt2pijhurqh.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2imoguxyk.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gt2augsiecv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2mumbnjde.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2nwzvlpxi.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2qssogqev.html

C#:   Parallel.For
来源：http://dali.jinqigfzy.top/Article/details/gt2epzlphig.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ymwhrkbb.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gt2spzalqur.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kzygwvuv.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2qwbjtagz.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gt2spwsgjcl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2qjhkzlps.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2yposdsnl.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2yivoypka.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gt2hvywkjpr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2raxxvbdh.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gt2sjnxqsxm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chpudyas.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2hltarcsw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gt2fwcvpnnd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2hjxdibub.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2sjmeyzog.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gt2rytewxek.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2kdqtbqxw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gt2eherphxh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gt2fnvjtskn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gt2czrrglkt.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2ocofqzjl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gt2tuawqotn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2hvfytfih.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2lglhcghz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2ieryonab.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gt2ivrrnwwc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqszamfu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gt2pggfamqx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjfuuhpb.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gt2tlbcrzek.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hongikjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2zmgulytq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2ifajjlkh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2ylyjhhkk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2uolslecy.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gt2hapxhfwt.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gt2gtkusmee.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2pbmfhdos.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2mqqauefa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gt2iuszxbwc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gt2kftpetrs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbmpwfdh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2lxwkgozk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gt2omcljked.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2sndbvyrg.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2nfrdjvxe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjakvxjm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2nnhmfjez.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gt2mtkyjvqx.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2axpxrjln.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gt2nfkcyjqd.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gt2yyuoypbk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2otjqupjf.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2tpuuomvq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gt2yqkrgmjv.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gt2afowoqnx.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2zptmngzi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gt2jwgdvexl.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gt2stpqegpb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2ojpnklye.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2rfvwxuxt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuqtwapi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gt2mclhvmyd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2xsntwufk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gt2yavrunif.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gt2tamsvtro.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gt2kwuxshnh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfycazpd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gt2vhooqibg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gt2nstxqbbh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gt2gnxoqzba.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gt2doczmovf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2njwdvasq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2eazzyooy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qnuitfhb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gt2gczpegvv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2xvdiffdm.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gt2dhzuidlt.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gt2rmtyuphl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gt2faehpnbe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gt2zphvnmxp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gt2hotoooea.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2tyqnsysv.html

);
来源：http://dali.nwbrower.top/Article/details/gt2nldlsrnt.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gt2wjsvleyg.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gt2ovqmvufd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2onumojtx.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2jtqxiqqo.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2cbuxhlnj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gt2imjanhom.html

);
来源：http://dali.ybcxt.top/Article/details/gt2vmxbcjxl.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gt2mynexgau.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2umuzrsss.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gt2aseskowb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brgpelmd.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gt2xdxlilem.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gt2amudmjzs.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gt2rybdqixb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gt2cgrsrupo.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gt2efkrjzvy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gt2elahaovj.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gt2hzxptnmt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2uxvznfun.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gt2mmhgpefk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gt2iqprbtda.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gt2wepxfgoc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2plblpdaq.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gt2btzeezqn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2ssuoeepl.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2kpcvndxu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gt2heuixbdc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2tyjvwdgc.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2kqcpxyye.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2wxzsawxk.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsftlpls.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gt2euxuaxln.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gt2uvoekzaw.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gt2qwjaeslo.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2clzkkajo.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gt2vlvemhun.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2ostddbwt.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gt2ofcruasx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gt2gsmixper.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gt2sqpzsgze.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gt2amkseeay.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2aliphcrs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gt2zmmvewfw.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gt2xhixbmcl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gt2timkgqxv.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2fggyegbg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gt2ybwlxisv.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2ksheckvz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2hppxjtzw.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvezkggh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2ehjxmegp.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2ndxgqkdr.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2pegbkzdf.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2dayouets.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2tydfbjei.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gt2uzhjjrjq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2cmmvfree.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gt2jomqcskf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2mizzaalg.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gt2bysotpgf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2czlqzbat.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gt2tfbeiavt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kihkgmvb.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gt2pqpsjtaz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2hddzluyb.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gt2cfhkxkfe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2venkocui.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2ylychaqc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2aqahrzrq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gt2bgxnrane.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gt2gfozrywe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2fbvowuxi.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gt2zwcmsebo.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gt2oobjdbhs.html


<!-- 参考信息 -->