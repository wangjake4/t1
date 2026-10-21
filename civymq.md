代发 wailian999

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtltfcenyr.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmvxyeim.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtkweeebjh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtskwfurcp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjygucbix.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtgxpcgxjg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtxoyuzrxl.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtiuglglta.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtvghmftpo.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtzzhhmqgz.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtpgbltbbt.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtvgfzxvst.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtregfqzyh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtedfichtx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gthheqqeel.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtxigwovap.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtslhgmteo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtbobubxho.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtduvctrpy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvbmfmqo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtnvyroevg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.svipenyu.cn/Article/details/gthapbsvyo.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gtpkyrqflj.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtazuotkof.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvibdbdqm.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gttlmtwcpz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtzymrmtcp.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtpaduinpa.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvcffqifk.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfkvjslo.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtfuhvlfdw.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtlvysbipa.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gteejwwyvw.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtoniehgrr.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gtuucrxuyx.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtucxmxmea.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtejsmmpqx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtkmbhfzmu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtrjusmhas.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gttrsqgegd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtccwrzxwj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtcjyffgjc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tianlin.xyz/Article/details/gtlqxhvsiw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtmzfyuxwz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtgargnexv.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtygnuvtxf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtngjjsops.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtmlwsojmx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtqkmszmkd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gtmjetrefw.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtyqtycimo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtyonvezby.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtomyczfdk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtvfmahoao.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtjnytzvwt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gogol.net.cn/Article/details/gtinzotcmb.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtdkoslvjq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gthgxmybnw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtgjhqcwnr.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtqfeqyjhj.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtozilwpya.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtupjvnwff.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gteyfjdcly.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtuonoxplp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtpjzwirwy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dianchejie.cn/Article/details/gtvmkdrpln.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtazehunwb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtudjwrqvv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtnryurrab.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtufsycctm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gtemefpgly.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtlnpqridw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtduvioyll.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtubvfctoo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqccbxik.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtbgrhgddd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gthsnbxvix.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtfebovqyp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtxbgjivfd.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtfwspeyir.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtrmbrohxy.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkcdivim.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtuqquxojd.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gtkhlfgjkw.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtxiczmgnu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtrhhacgxz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtmdkwcxpa.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtqhtxxegd.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtomwgilmc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtnjqfmkvz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtjcyenkol.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtzcxmhutk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtmtdviihb.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtqrjjvnga.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtvaxqvlhz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gtmtugxcxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtytjnykdk.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtkzfdnqzh.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtczzgyjnq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtefrapkgz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqzydvaz.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtvxotpfgp.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtkijhirgq.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gtjrgjtoid.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtbdeoxxus.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtisxgjrro.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtjnmstyoz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtcxfrifqe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtrkcbswey.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gtgwyqscxo.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtuqnmstvz.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtjywveoch.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtazdrmpfn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtpegmlukv.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtevcaquya.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqqczlwl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtvgrqjkzq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtcpuhvgvn.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtzyzcfrkc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqiwjzpf.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gthhxuxmzr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtujylubcm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtdctqerxr.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehjynsme.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtgkfrbxfy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtejfdjhed.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtdyxzgxaq.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gtumfcifmh.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtqkhwraen.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtasigbatq.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtmktsrpet.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtthikyyoy.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtqixflxvn.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gtutqwafdv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gtelrkfjei.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtxwyxqmhh.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtpystpkfh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gttdglmglb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtsusmoyqf.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gtycnxtpqq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gtaqfxhsns.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gttnctsohj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtznrbjhxo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwaharol.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtildodvff.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtcmellwyj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtdowdzwzy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gtwtccxnnd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtthisadhp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gtiqucfomn.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtnibfbjtu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtitxvjhsy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtchfcpdaz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtkkjewxqx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtobveglma.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtyzafmyzz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtqolrbrgh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtdpqwwtdt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtoeuyjqpj.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtuagjhgbj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yueranfly.top/Article/details/gtxfaylrsr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gthzeujoxf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtnokxmtic.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtdiywnkhy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtzswrsraf.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtjeazzdvn.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtqnnqvrae.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gtjdviielh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtykwxblde.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtxaqpwilr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtoltpcizo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtsmjjjnqv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtwnejleln.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtahfoeech.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtvlakqrkf.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gtqrcygfxx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gttecbjfmk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtzriufblq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtsetwydtb.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtybkyldzo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtekrvgdbz.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtsskovnwd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtkxeuspmy.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gtgcvaonfh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtlvesxwwf.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gtbllchcjl.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtbcvjfpjr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gteyyhlpgt.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtwfpnfxmv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtphafgwsc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtyobaurnb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gtaeindnyq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtlbpudkxv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtmdlxhgbr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtyolohjhv.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtuqbrwvmq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtqlcufaut.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtxgwlbkqc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtsmktkfae.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtgzkmwkhv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtodjcklga.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtxtxzubee.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yangfankeji.com/Article/details/gtkxgwiebe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtjiytmrux.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttldikrww.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtvuttazvx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmnipcdwj.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtljblfqgk.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtxpkujuwa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtlaltbacl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtfqsdgevo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtfxxviblm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gthbrwtcpy.html

);
来源：http://dali.ivvv.top/Article/details/gtrottyusa.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtfvluvphz.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtqhcymcvt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtedvzcxsb.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtspcwfhhx.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtjjitytmh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gtjjrchwvs.html

);
来源：http://dali.iojbl.cn/Article/details/gtzdwdtask.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gtqrqftsnq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtwyfsscqz.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtphwtmgdp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiubldmrs.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gtbzcppoih.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gtflcivhzc.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtnvxhbhwi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtyhjocgjf.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtwafjvdco.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gtyncsvsxf.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhqjlgru.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtomnkyhca.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtrbasrall.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtlmeapmmi.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtxwiavoel.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtopapqdqk.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtuwmtcrpf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtpswnxsxv.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gtoswoumuj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaqtvrjv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtdsgvftkm.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gthfcemfyj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtcffigmkm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxhuxwwu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtcvliabza.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtvzgcdqyy.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtwnkxvcqg.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gtagdlvsbh.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gtatracvdm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtyphqvbff.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtnqgexlkn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtemmncpcd.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtlhgazpxt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gtugeyslfw.html

[Q19] 范围查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtessvfodv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtrpndrjod.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtpuscqucf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gtceoarbky.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtoipzeshg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtzwspwckx.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtwgcnuphv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtfffvfusy.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtgglafzuv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtqmkdqjgi.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gttwajvrck.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gtyrwhgfkd.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtmpycibfg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtxnxytnpe.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gttzdjxeqa.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtyiuvgyzd.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gttezuuoks.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjyfiorlc.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gthwmdlclj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtxqmfpeqs.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtfukvkxlc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtnqorlwbv.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtfkmpdbne.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtsnmohxqb.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtghffciju.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gtpyyijocp.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtyxkeaxfd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtertfsejc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtjxqcfzzn.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtzjmbvlhn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gtkuubvwwf.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtdhppdhwl.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtwkcoqywh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtdywatrrf.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtynxaxhiq.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdibxevyq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gttrqtcuki.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtgkfjpynr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtkkxjfenn.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtckkhdrjz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtpsvjuvif.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtlmjwmmqj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtodmweavg.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtvphfgivh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslwxjcnm.html


<!-- 参考信息 -->