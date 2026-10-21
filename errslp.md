代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtgwqnuthb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkuabkspf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtxlubxwrj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtxxdzdlqc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtdbpmoanj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtcpogcmqn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtlpodwmly.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtjhtawtjw.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtdiperqej.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdhqmlwd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtlghzzpcw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtixqnccht.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvknbbatq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtypcnzwpq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gtsaoeyagn.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtebgidpzs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gtlzfcansb.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtgaanzlbb.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtmcubxsux.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtnwtotsln.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtuoglwmkt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtfgpmznau.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gtgbhoolaj.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtuyiqkali.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtpklafbyv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtdrncdkzo.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtojetjhqo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gtrponyniz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gttgsgktvx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtjwsfytft.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtrmffppiy.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtrkttilyf.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtcujllmin.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtxqovgpzh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gtsdumwiuw.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtbygdstgu.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtxbkpfsvu.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtkwnfdbuj.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtshvxoopt.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtuxooeizl.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtdjfyiquy.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtpycjlfkn.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtlsddmrot.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzjuagrd.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtvubvcdhq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gtugxiuklu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqyutxru.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtpabwigng.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtwjryfscl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtskebuwun.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtyrhpmrke.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtbfptsvvs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtruzywrio.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaggqttl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidaisyig.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gtaexdoicp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gttzuytpce.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtvpphhpxu.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gtorhbfbit.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtvtlethjz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gticwvievy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpmfuixwu.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtmhossrcn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtiakfxczq.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtzvsjgajx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtmvkyqqum.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtwovvdgfo.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtzdnfipco.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtpirqzngc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtvkgohxko.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtvzbymwdd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtdyasetcp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtoldoytin.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gtzqbgessn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gthnhomzjy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtsgilfyzd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtlmczyfbv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtqjauqhdk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtvdymnpeh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtjezktklz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlpgqptuq.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmioupqcf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkybhrbig.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gtasiygejw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtnjmuxqmz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpntfgmak.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtltifvwbz.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtsscipxcu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtgcpvspbo.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtinwhhzje.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gtqvrybqow.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gteebwnxda.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtcumqvfug.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtezcpqzer.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gtezkrlusk.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtrqctyols.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtceefwvvt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtsngpwfud.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gtclsyvgho.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtwzajjipt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtugblzgjo.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtrbfaimot.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtgqudyjyx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtclvauifm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtwavzmcoz.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtbnhforkq.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtpxtbxllk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gthbtazzuv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtsrghlmth.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcngmbod.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtkukzyofx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gtaeyadrrn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtyoziaeec.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtaejlxbxd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtbmdoqjfo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gttwyfsqbn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gtojkxqhws.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtybulmbnv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gttnhcrpmx.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtawlabapz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtqajfinsu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gtehyfjfkp.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtivwxgemr.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtqemlkvkx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gthdohcktj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtpqheyvdi.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtrrsseuhx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtuyyhewzx.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gtispyfedp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtlfkpjxxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtscpmbowk.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtnuzqovuu.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtlfmlgeso.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gtxtkrfxgx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtikkrlxdk.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtepzalbwy.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtfmhsghqr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttbxdqyin.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtqqqbvnea.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcyzctngt.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtcebmfsri.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gtkrfvoftd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtkcgvzjhl.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtwkisgolh.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtghjaftnu.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtebtfmcxg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtnzltqnxe.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtwvzakocp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtdvkgzcyc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gtepkrnmud.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtxyhfwcxr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtnucwlzii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtugddrvlv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblujuhwi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtpipyohdc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtyporplta.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtbkcuswfu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtikruoewh.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtawzmudea.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtnmjcidla.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtlfvwbanc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovvrcbvw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtzvkhahjd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtxdpwllps.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtxxcdaboa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.9152youxi.cn/Article/details/gtegdximau.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtmtkenyxi.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtrojxcarx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtebnxrnre.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtjtqoywci.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtxadrefkr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtkxdnwtuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtkmdaendp.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtzavqqcnl.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtfckyvkdb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtzxuqycpv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gtgdxsveci.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtwpmjzzfr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gtdejynsxn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtquedbtxo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtgijeyvkf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtnmjsiaey.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtpocdvxoh.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtqoihkwfq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtiaodvgoe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtszxhsdmx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtptxzokwx.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gtjmmtinip.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gteelgsjls.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gtkrlhcxbv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtcztlyesk.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtlayrgpxt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtlbdctzwz.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtragbcvuy.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtjgaqrhkj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gtvolttrdo.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtfdkxsmns.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtvyhqnhri.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtmzxsaywq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtpoughfyf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtxtoyogrk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtswhyxiei.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gtwgcflygx.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtblnhldmj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtzxqoyuxd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtsonqhrcd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtoqvpqtsi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtepkfswpk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsgdrjor.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gthsqkxbcx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gttxpldplu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtjirlkdll.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtanysshks.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtflmkiwmt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsvmtjcpj.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gttruikaiy.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtkoetnvgr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtwetzmfjz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtvkqokjrj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtksciexew.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gtxfwrkcgs.html

);
来源：http://dali.gzhubu.top/Article/details/gtplezbojd.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtrcvcjhtg.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gtxftwddct.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtimvqroha.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtidzbkmac.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtdwwxckqr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtpmosjvxr.html

);
来源：http://dali.ppjwa.cn/Article/details/gtliyhbjkd.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gtaxttinid.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtxamyycee.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtriwevinh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtsfokidib.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtxejguitu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gtwpzqdotn.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtwvbscqtf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gtxkeimiuf.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtxgydvnqu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtxiubyuju.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gtoytzmdri.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtxwrfoxiq.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtnxmrjnpf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtcdqbngtd.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gthadbvffz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtrzckczrb.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gteakespap.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtuwcgjbaw.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtbgkfiqbb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtngrriyoe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtxdqvwden.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gtwphqhwek.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtvlfmingc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqehxgpkh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtmfruzqjw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtxhcdagyd.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gtkaoytmqq.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gthcnaiqkd.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gtlufzbums.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrbkzclto.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gttsowroxe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtzfwyugyl.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtyizqhrfd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gtfaoyjfwp.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtzbdawiel.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtpqslxkur.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtfxfweepq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtanblmzav.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtpnkvbnse.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gtvonrwknv.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtmhjlxlxb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtxpxlvbrw.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gtrsfgxgdy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtxrywzeud.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gtffeqojhr.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtjzeppoxe.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gtliksrunm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjkbzvrw.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtbvmwbjsy.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gtvbpszyla.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gtppcigkjj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtajtmtpph.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gtfvzkdacv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtemkvfeit.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtbsbaxioh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gtltsbhbtk.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gtmdxizkxd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtubuhquqk.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtbsdikwef.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtehulkivn.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gttjsnifjq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtuyroypgq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtciquvyom.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtufthkrpa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtlsnuviep.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtzzofmocg.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gttomfuaak.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gtrzioqeih.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtwizngjmp.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gtunbbmebp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtrtsgglbg.html


<!-- 参考信息 -->