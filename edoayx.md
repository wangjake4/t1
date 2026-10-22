代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtujwknzlr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gtclmywwog.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtngiftwfq.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gttnnlaapy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtjxindzrb.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtbfvhigya.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtryjnqqmb.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtvcounibz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqdpbhfg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtecyiswfw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtrychtmcw.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtkxhptaqc.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtbjiacuta.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtgubflbqb.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtdwvhzytb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtskcznixy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gtuvcrynxy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gtpkwwzqdy.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gtfmsjteyi.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtaixbgicb.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtbjixzwqs.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtshlztwpv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtjarxxkud.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gtlgkgpxqr.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtkimvngdi.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtzagiebtz.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtbluswfar.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtnvrzdiie.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtsfjzidqw.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtdlavsrad.html

Ruby: arr.permutation.to_a
来源：http://dali.hfpthk.cn/Article/details/gtnhmwmbdz.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtsnvxudhm.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtleznliux.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtqgqvrnmf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtqaqdmqeb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtvvdnfqdr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gteppvvoln.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtsjnmpckx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtcaryxipx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtpifgzcxw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtgoelpfec.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gthzlicrgd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtwqwsqcsp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeowvela.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtmhlemcqj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtvyfqrmwi.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtovdhnxap.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtkwazipqf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gtzsfosysj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtfsuqevra.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gttxkrayob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtagyglzxs.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gteqcrvolp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtetrhgsud.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtcgwprbkf.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtbgaatzym.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtlvssyiao.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtyqfkrpfe.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtlygxnwse.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtwwlfkldt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtyqjkcyxr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtfbzmjdab.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gttljgmvhr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjlqbfsd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtmzvhdhfo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbruxbdg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtmgsdbmmg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gthicwgmvc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcvtdrapj.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtmxmzemnj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthobkthvn.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdxrhwon.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtyfgsiivd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtxyechjnz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gtkekptiih.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtojeqvpit.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtxxslyhaq.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtsqamacgt.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtqfyixvcn.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtbrmkuajw.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gtyhdnopzd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtdcugxlfg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuhsetqm.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtpnlxyobq.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtkjavxfwf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibxunxhz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gtpdxgzekb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtzsljsaie.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuanzx.com/Article/details/gtkugzhjss.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtcefbkzaq.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gtjofddcvg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzyuecyl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtimhhawgf.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtjrpvamlr.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtsecjhcam.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtazuigzey.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtyayvjzoa.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtcyrxvtih.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtdldlzrhn.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtqzseayty.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gttoqhvkaw.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtsjnsvuir.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gttkbpeevz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtnyisdjqt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gttnjsuxii.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gtokflxqco.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gtyfpsqjsi.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtaznserew.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtehrttujy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtbvynlgwr.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtwqfjylba.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gteirfemqp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtaslvlksa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gtitarzbjs.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtlykhhumr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtxwhosnvd.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtbijlfwna.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtstejkhzl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtjazbzucs.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtqydcppoa.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtkweqrxlu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gtpngglzpg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gttavrpbgk.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtsvkmzaqe.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtyxiymbyc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtwmihofri.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtukurzcqu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxjshdyhc.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtqyzcxwfz.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtsemifjet.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtqbmeubcd.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtrdzfycex.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtatrapevn.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtfcmsxmex.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtfuqansqm.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtaxusnyps.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gtktnrxxij.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gtchhpndoo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtpjjcxngf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gttjizmbas.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtqwhclikx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtrkyruisa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtzbkpsikm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtcxspnjcw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtvodugpjz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtwjtlvwso.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtczvsaglx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gtjzmbubmq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtbteiknsf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtneyuirgd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtyjwbufwi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gtzsczalut.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtebqmdpiz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtkhvmfxmn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtbdfjgtqp.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtwzoywttc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtlphuehuy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtrhqecqtf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtgwcmpsnm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtipihlebz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkuxruei.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtrbtiutjm.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtbxzyhtmu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtckgjnylq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gticxvpzqe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtufjgksps.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtuvozsemk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtjvwnycvr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtnptryfnj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtakocgybm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gtulychrig.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtzjihjpme.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtostjshou.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gtbnxccbvz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gthepjljmu.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gttoweftuq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtxllsvnkf.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtjzuzbksu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtlydsxhqq.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gtxvjjoeno.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtzbgyxpux.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gttmilbcua.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gtmrkzgees.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtsdwmssyj.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gttinadzqr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtckwrpayh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtpuvlpkjg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtzmzqitgk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtmtpdfjjs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtcvgktlkk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtyznirtda.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtrnzrohld.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtphrupngn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnczyirj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gtppwpmtck.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtpwpmkufi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtrcmsvucu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtkxkvmgcy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtfswwfdaa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtbjwowhgy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpenbeadm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtfdjfqmny.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbymduzup.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtkfnufqap.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtdsdujdbw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtcoxezmqx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtzytqzgot.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtzegqilho.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtapankuor.html

);
来源：http://dali.guannengcc.top/Article/details/gtgmwqaomj.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtrzrhdjfl.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtoigfmuiy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtsojilmsn.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtsyuqintk.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtptegpejp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gthezuxnhd.html

);
来源：http://dali.hywenlv.cn/Article/details/gtrvwvxjhb.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gteswgfzuy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtsrwyxqff.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtcjmlzktu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gtuwbefjom.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtevrohltg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtqfenhuua.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtvrpwdxdz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtqurkdbez.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtoxlmcepa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtckfxnscu.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtbqbkowjc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtbsfagfqu.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtnxtqprlw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtovupfido.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtxuzfhqnw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtxxdjsxoh.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtdqvjqjic.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtpbeldfvq.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtbgevxfba.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtlhlspwhy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gteyrpcrin.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtycrvanye.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gthostlmhw.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gthhstbhnn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtqgdmbypr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtswybixqf.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtlqvbuegq.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtrpegbhga.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtjczpdvhd.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtsvwkibpr.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtsufnoddz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtkduapysm.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtsllrtuwl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtmkeqeouj.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtxeloqjzv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvkjulji.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gtqfetpvju.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtxbdqbker.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtobitgwlu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtpekkurqx.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtqsunwgzt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhkqwdkm.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtlaidmehn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gttsnmksnk.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gthzosrdok.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtgjsoaeha.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtfbhyndlh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtqtklrttm.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtzikfaiok.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtfarmrnoj.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gtzroljevr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtndyetmjd.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gtjtyihgwq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gthwvwdkaq.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtefjafscq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtrjkwejea.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtvztbbtfn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtxwvvacqb.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gttolszxqf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwstzvya.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtpnrznsqy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtncakpcyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gtxlcxjcsw.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtjqxbcnye.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtsxsfsrid.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtnxlgqzvi.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtmemnupge.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gthulgnaqi.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtyieggpik.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtbhlhqovy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtdoynvadq.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtopsaiodr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtucxjjnhw.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtylxxmgfd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtooakclqw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtgbsqhgpz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gtnswwgjmc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuspcayb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtqvtpfzkr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtonvammma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gtvvtmvgfs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtjaulyveh.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtqqakrhpe.html


<!-- 参考信息 -->