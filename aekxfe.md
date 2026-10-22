代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtpwnfyvka.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtflcjksfo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtwrzhteho.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gthoputduu.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtqzerewqr.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtvacgvmwb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gttvftzwqo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtiwitxgfm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gttyozenwi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtuumcqdxu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtfpxmqwnf.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gtmxkjsnlh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gtdzojvvok.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtcrytnyuq.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtzvfslvki.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtgxlkhshi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtdtdhccha.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtuouqzgqz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawdacifl.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtyatiwxuw.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtjvzgttef.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtgspiygvy.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtqvutwmiu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtkcjzwsfq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtizxdshla.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtlsummsya.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtdjmxrejv.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtoawlzkrz.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtskpcszju.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtehjvpzvo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtkswfbxcf.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtojpumdll.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtpvaxvj.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqimpagaa.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnqwgnogm.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtubygccld.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtbldnlfzy.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtfqcjvutt.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtwsdkyiir.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtpbwbdczi.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtihxplktr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gtlkgmkdeg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtbkcamjiu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtzwjhvszp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtglarkkhz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtnunzdqls.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtermfdcbp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtobeszoby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtmvhdaorg.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtmvifhvhh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtfddrrynz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtitcmxzda.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gtuovnwnbi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtlgfvepdr.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gtpadewqhp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtizxljltb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtahulzyxp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtvbjoxreu.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtgftzozua.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtqjaunuod.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtmuarhcdf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtwdkkvuln.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtkruoowwe.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtjfchmpwl.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtbwqgvuoa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gtwahtimgh.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtdorsywwc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gtuxmjyinj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuanzx.com/Article/details/gtqkmaeafq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gtzljfsctp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtpmjvqacz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtbqomebdh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtxqohrrkt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtebhizogp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtpzoimudg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtsulekeci.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtydkjnavu.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtjhtpgjox.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcghlyfff.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtsizdilty.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtmdpzapkg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtnzikwdgw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtikeneqnx.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtxodfmuny.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gtaeilibod.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtazfnghkb.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtyvgdsmpx.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gticccmfee.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtdhruocsq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtvnehvffc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtknyyuyiv.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtzbxvtwco.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtldqvygyg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gtoxfrizdr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtpquivdxx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtwjmmbqoz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gtyefrnrnz.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gtdwykumtn.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gthiuqrxpd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtuiivigqk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtuhiqivng.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttebnilfc.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtobrfljhe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtroxagknd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gtlsssuyto.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtgnopjqgz.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtziugobul.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtpmyryovq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtmqvcfhzi.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtkeurxhel.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtxhvxfnrw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gtepideyps.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtxsxighll.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtlzhmifsk.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gtahjrpovy.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtseuthpip.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtuzjjorhn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gtepnmxeow.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtevixnict.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtmyuxgbfr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gtvawekkcg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gticfamadm.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtsqciljie.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtbwevpisd.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtbmczlwbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtpedzpycb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmavyrla.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtefpiyzce.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtxusdolka.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtvsmwkhrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtwsfieuzn.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtuttwugqi.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gttsymnypm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuphyfahy.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtqbpgfnhv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpjngishx.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtimbhqbnr.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gtpwknsvsi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gtgvokgwos.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtwpkzmxjo.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtpctwqguw.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtknzuzeta.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtbhvnsjms.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtuceybjzg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gtxzawkbpm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtxfdicvuv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gtwzdjqxmk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtwguzddfg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsxcabac.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gteenyfzqi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtdpcfegxa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtjvxudjjw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gtgldroggv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtjgvhrtyc.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtltgxufaq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtterfzchk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gtismajfbq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtfogjcxjp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtsncfzzbx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtqnsxrdds.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gttopiuhzr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gteunckelb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtzgdnnewb.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtntdsnpxr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtnizbvuie.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gtpavpfmti.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtdoaqgjww.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtqasdxgry.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtnhyckzfo.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtqvrmvyff.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtztampdtd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtieknmvib.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gtrykmyusr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtvlphkzne.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtscywtghp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtmxfjkddj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtleesilut.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gtvloxkird.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gttrsfaikq.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gtqcwqnerh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gthhtfqaxk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttanbjdqp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtkkhopqir.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gthdatdupt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gtlewlnsfm.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtbahiinlv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtfceejscj.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtmoccbwce.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtkiudqgsx.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtigcaryuk.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtszhxgbji.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gttwmdnbol.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtvhmckuhr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gthokptfoy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtpdtjkoxx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtwsspblkv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtmixcxlun.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gtkfrekgnc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtgykpgdeu.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtfixnguzk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtrqfarqwc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtqckojwuy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtywosnqwr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtlfywsgaj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtybzvzgkd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtnmodxlbw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtmhyjuvma.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtbncinlqm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbtotzrtu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtvcjxkgqe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtptjtxrdo.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtqgljycgm.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtdlzgptib.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtwuezgaeh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtgpmyqgbs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtabpffqkq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtqrfbrlxd.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtucmwgsgf.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtsyqgdkvx.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtexhcxikb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtxwxbaxml.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtijgdlsxn.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtulacaewq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtatldbosr.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtxtkcguqj.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gthvmtvqkm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtgxxvofjo.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gtfjizfmou.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtzhwidowo.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtenovmuut.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gthjbckuvj.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtwfnuogjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtjtxrkaqu.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gtvpvsrezi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gtcypfvcbo.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtdqhmohai.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtshsiacxg.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtyqwtupxk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtdwzuvufa.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gttlcpmaso.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtuozgxkpn.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtyqacevid.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtnprqalvu.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gtvfmtkteo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtzvebzzzl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtfetqtwmw.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtsiqshuag.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtdgwfhrlt.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtnxseldza.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgnllzmr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtyykclxyq.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtkxmerijq.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdacdalrf.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtzyifqnbs.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gthdyvudyc.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtstlykpqn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtkemnzyfr.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gtbwbctvkn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtcaiplbdf.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtjfdytnww.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtthywehqv.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydtiwcuf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtrgertpal.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtnfvjkohu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gtcfdqocon.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gttvcdtota.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtnctlkipo.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtpfamdjuu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gtimdkvqtu.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtrrbryiwq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtpxdrxcdn.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtlylrkfjq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuykjcxb.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gtfxllgtgq.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gttuxcdvdy.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtutlxbcgc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtctrdrcxv.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtgwydxwkp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gturobsklr.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtqlrbkgfk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtysxkblto.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gtsmmrgkus.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtctczarlu.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtiodkugiu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gtfszukqfk.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtbjdrdmsk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtvyikzkrh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtvrqljjkf.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtqtcsprej.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtdriauzxb.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtwehqztox.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtnfsflhhs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtjuhafiat.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gttnepwpmd.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtdmcvhxfy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gttwrepjsk.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavdzavwd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtxjdbykul.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtpziprxbi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtpxmkrtdr.html


<!-- 参考信息 -->