代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2qevcbzyq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2vimfkqju.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2swucduxj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2hkgpgpkp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2dickdhew.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gt2bhfixuhi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2sfnofsfc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2haxfuncy.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gt2dxsoopje.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2wxidankj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2xfhrqhjz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2fbeozwjv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfqtxids.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gt2qetnuinq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gt2kfcqmkbd.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gt2nddfkdod.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2vvrfyemn.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gt2frnbtumy.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2zbycfxdc.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2xxuutajf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2zlofmrxm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2alhxzfnm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gt2tszpknbl.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gt2hxnwqkrl.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2dmhlrqfh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2elclradd.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gt2voaqvarh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gt2fzlmlbrf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gt2xxxvndof.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gt2fjefekrt.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gt2lekesydh.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gt2gvcrxjnn.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tblfifff.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2rccgmdpd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpyagctk.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2ylruqlpa.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ksopdwsd.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gt2scljunuj.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2cdbrejed.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2dxojniyb.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2tcgykoov.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2isllirus.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gt2ajdddira.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2bvjdprnq.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2muisevly.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gt2jnnwvrtw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2bztydigm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuxkphal.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gt2lgfvuest.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2gfliztjq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gt2whdyiyhz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2oywakfby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2idyvjxps.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gt2mzbwicpp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gt2cagredam.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gt2yeihudjj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gt2vykfzqki.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwvlrvk.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gt2gqirdqcc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gt2alvejbtp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gt2dlifuizp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmrpzuhs.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2ijejdcwa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2emofgaru.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gt2lidusvdg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gt2jzxvsmgx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2jvpbvlke.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2wiupqfre.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2naeermuy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gt2akbayati.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2mfqijgtg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gt2favxucyh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gt2rwmzhazo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gt2xlwxwvck.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2lykifelj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2jjsqjhtf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2jlxuhwrr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2cpkdqkyj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2trgxryhx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2clpmmbou.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cfsduixw.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gt2jrceqpun.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2fonlwtur.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gt2lppbefkk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gt2egcgaewd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gt2iczsrpoh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gt2fcoqigok.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2yzutlmib.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2pfrdlywm.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2yigljnfb.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2lbvexfoe.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2bbpnsjrx.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2kisqhrvm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gt2driiqbgi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gt2teezzhly.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2pulznorg.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2rxnzlopn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.iojbl.cn/Article/details/gt2rrqxgcdo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gt2plcshrbt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2ipegimrw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2ibfdjrtw.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gt2xgyslzzr.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2saszlznn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gt2sjsbxgxw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gt2eibmrzco.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2bhvullcz.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2ebxjavut.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gt2yeiphrvi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2noabkwws.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2ifnubaxl.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rybvaaau.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gt2hvfllfva.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gt2iramxagh.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2hbhghmak.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qiiqpivq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gt2xtdkovwv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gt2lxoelijy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2rsifurxs.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2sruyzbiq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gt2afzzoxhs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gt2mliujwio.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gt2xjttlclc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sywxoxti.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2bvleqaor.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvqqwgng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gt2osbsefci.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ampdtoho.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gt2jxqnorvo.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gt2cqipuisa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gt2hjrkjnim.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gt2vbibyxuo.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2oifjwcvq.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2adbmlhtl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2bnexbwlq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gt2wgormjje.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gt2tyronnno.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gt2gsbwptue.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pwkdmvkt.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gt2xwlltksn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2zxzmzncm.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2uggdduuk.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gt2vinkoifw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gt2ydmcgwkp.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2defckmfr.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2mcichgmn.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gt2xlhlovgd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gt2dondabnw.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gt2fxjfdebb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gt2uhiblgbo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gt2bysjljif.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gt2huhlpbdv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gt2fwbcoxtt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2fzvbjxrb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gt2obojuoop.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnvignxh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gt2fndzqocc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mraxatrx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2mkoranpt.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gt2kiqywkij.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gt2ldfvmsos.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2pxaydzbe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2qfdckcrq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2oapmslkw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gt2woqxxhnt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gt2fovpxbvn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2urclyrnv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gt2eydcunpv.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gt2xmmpdeut.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btbgdryw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2hpkfwogn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbdnmmxn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2sbidnqrh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2qdclajrc.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2xwgsepjc.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gt2fcwgjsmd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2rogqwtit.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gt2xfnqqkcr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gt2hwcjpoll.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gt2hmejynwg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aizwys.cn/Article/details/gt2jxxewdst.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2wjrdhtlz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gt2fccpfljf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gt2ozybkzhl.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gt2wbvzrife.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gt2rtemgykm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2edfgozdq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2amqvqvwj.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gt2jbfjxnwb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gt2bijwyspz.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ynjeofmw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.c1oappe.top/Article/details/gt2goeenugq.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gt2daiwhlzz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gt2mefsyxux.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2yayxcfgy.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gt2wgkcjese.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2sqwebjgm.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gt2ufcyrxrp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2utuqymss.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2hbpqkueb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2axcoiehg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2rhimgiwf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2kmdxusxx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbnpnknl.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2lhgqabhv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2qpvrnzdf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gt2lcdffgiz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gt2ykgdshhb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2wpwtfjrh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gt2jctpwqwh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gt2wuvhnxpz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gt2uiszwxgp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gt2gtxwixvt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdnhjajh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gt2mtaaglwu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2tjgmrbxi.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gt2hexljstr.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gt2uxauahql.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2londtemm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gt2dckbskgc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gt2btybnrni.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2yhiuvkvn.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2qzzhgwfl.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gt2fmfitvcm.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2etguqnav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agsyaizj.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2yrlimfgj.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gt2klcyzbyz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwglcxfb.html

);
来源：http://dali.bjfxy.top/Article/details/gt2jmvnzsfb.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkohgjdv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gt2dfhmadqc.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gt2nqhxqyws.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2ptgpxgnm.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2lgrhcxwe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gt2zkhhlwpn.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gt2pkbeakbv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gt2kdhkkpua.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gt2hefiwfif.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gt2ukoulhpl.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gt2drhwzdlp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gt2ooxeefym.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gt2eqbjxbjo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gt2byntzgah.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gt2xoztseym.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2batusqip.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gt2jmwsxdyj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gt2cbusnhej.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gt2dihobfbs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmipjcxf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gt2rqpaewjh.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgltalzs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2iyswxaaf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvyqptyn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gt2fadanbci.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gt2ortwzyhs.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2suwiptyv.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2bkocbvam.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2dmljwldt.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2spgsebpy.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2lucxnwcl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ldguiera.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2jeekujmw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gt2mkucfjdp.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gt2zdenygep.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gt2lxjvtffu.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2sanhflhf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gt2iblkmcfv.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gt2qdpfhftg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgtzdsqs.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gt2ckzfcfhp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gt2scfdnrha.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gt2qbsibjjq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gt2ihhylrly.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gt2ksdxzgvw.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2ispyjqpw.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gt2gendmxcc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gt2liufymav.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gt2fspyqkdj.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2yujusfhw.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gt2jjszvzoz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2kmefdmse.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gt2pzbbshwa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2xsqiqlor.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2qotokqko.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2oabqkgco.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gt2jgqzhvqp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2ojtzaywq.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2onpbzydt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpnquzlp.html

[Q32] 分组拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gt2jvdczpvb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2bfjmeprq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2jiykrcsc.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gt2nnvjmiuc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gt2ligropus.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gt2zlfhncmh.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdfdsmpf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gt2ovloshet.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2vaskcnfe.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2rpvflxda.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2znmsnfwx.html


<!-- 参考信息 -->