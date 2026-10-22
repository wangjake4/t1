代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtqkspwvbe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtxlgkcgbk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtnaholsjz.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gtppvrpvbz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtducotbvw.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtcsnmvfak.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtkwkswwys.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtqcmdnfac.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtuhimwcvm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtkmofdmfc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtxnbyeobw.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gthrzlvljt.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtcefjeufi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtoeodrdhx.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtlaawqbif.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gtsorpgskv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtjjeodjbn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gtyvykurfx.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtzijohwse.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gtmjvxbrnh.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gttfckjstf.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtlxmorika.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtstuhcdyn.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtffxmkwnk.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtoxovvtiv.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gtnexqtoxp.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtkbcptfsh.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtssihtoll.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtfrvurkaj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtxmsgwmbo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtuviuotiy.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtqcbkseer.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtixciynvm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtbolbbcxf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtysvgayem.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtfanzlzij.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtevpysyip.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtdpjmavla.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtlkmorpln.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtgwjjtldb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtlfozffik.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtmyfdpfcl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gtzuirmzbk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gttzrdiyre.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtlhecfeob.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtibmmctdp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtxmopcftd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtgmlffmqf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gtukjupygt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtbaslhywx.html

[N11] 二叉树中序遍历
来源：http://dali.wangdashe.top/Article/details/gtwakjovvj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtrcqvitdm.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtlcbchibn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtdfktvnyl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtyhejkpjd.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gttctryhix.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtwnypvoet.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtnwfrzdmw.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvmvsshv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gthccwvyvb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gtfmkssvjc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtxlcjraqu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtvsmtgzan.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gturrrhagr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtjeukihgb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gttkzbkbor.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtmrzgdsyd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtrmiclity.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfpsxahpz.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtlwxtxuns.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtkagjkgsd.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gtjrlitfdr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtziiwqztr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtfhoitlrb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtqfqaazag.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gttihtvvja.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbntypppy.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtxqrcmpaq.html

Ruby: Thread.new { f }
来源：http://dali.nanxuanxn.top/Article/details/gtieqagtqb.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtvrsuonod.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtkywjpyvp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtjqydnpre.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtcomknkup.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtwbjtgmaw.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtkipcazrd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gtzvqpgupy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtotzqjveb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtshzmxrsh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gtcvauodty.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtecsxjpox.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzqevawb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtuaukalkc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtbicayson.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtzfxzosko.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtvaxlwasr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtsfuuenhx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtmzzennyv.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtvxhchstx.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtsipjnzyv.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtzfhxajff.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtprhqkksa.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gtbeksorxr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtilcttbho.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtkjrgzodc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtzrvmurxe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtuupoairc.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytktyygj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtbnfcnqit.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gtyeqenmdv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtugzawxzz.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtobduttzl.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfejwied.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgfzy.top/Article/details/gtproqrwld.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbputzoi.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtyrfvrhsm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtsrwzyolb.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtmfazbvnk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtjpqgendj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtgkiuqkjm.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtospfluyi.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gttqqlwrsc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtpktybgam.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtgfpwerbb.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gtypuqnjeo.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtwtojrklo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsmuvzlpj.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutawsymz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmlyndvxa.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtgcnfwhcf.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gtwidkboez.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gterxoayyp.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtvhmwghsh.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtkfwnzimu.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtjavvjubt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtegxxeuqg.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gtqhblbpoh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gtykycsics.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtimjnvoub.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gtmnzrvpci.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gthsqnmyie.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtvxsqdgah.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtlqzaudnd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtmoroxogw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtlcrqqtpf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtukoojemq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gttoiruzqj.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtgeryzdka.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtcnkjtojt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtcoanokys.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtxaddcblx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtfysnalbx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gttoezsevi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtefqenpmt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gtkxgguhad.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtnjleabfl.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gtzipwzjep.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gtjmewkkxh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtfjrxrnmd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtluxmlecd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtwyjojnta.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtnipbqtjm.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtcunjzrwx.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gtfwfozpzn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtuayvnddi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtocjxhymy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtxtotzbko.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdekpglgq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtrmnerfdc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtdcazlora.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gtcdylggwv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtvcsbuxfl.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gtfaipwwwk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gtblvvqzmr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtkplwfyez.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfehslnq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtgxlqbkme.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtccvscksf.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtutzjuiwi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtzbpltbsd.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtiovurnvy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtkiovkzqy.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqlivjnd.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtwzvxszpo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtjhvcpjjb.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtpwxhvttc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtygnzvzez.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtomcuknnu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttcfviwde.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtfqfsmfuc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtaznfwqol.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtkzwzssdw.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtrjwbltaj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtqvvvvcie.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtyjqsmngl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtnrubvnll.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtaqppfksn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwwcqvys.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtbjjnbcjg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtdsqfmhfm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gthrsgkaqk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtedkhtwry.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gtrfwizkjv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthwliwhqo.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gtzvkqvxry.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gtbvcdzoql.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtuvamvcln.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtnbhuyztz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtdeomdoev.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gtlxszphag.html

);
来源：http://dali.gotoacloud.top/Article/details/gtkqmigccs.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gteqgbfnxv.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gttppskmur.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtiqqafbaf.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtrgjohfne.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtuodhjhlg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtpuoeobna.html

);
来源：http://dali.sufxvd.cn/Article/details/gtwotwgbse.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtycwziyex.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtygmwfscj.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtrentpidd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtkyinfrib.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gtoflxmukt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gtnlioywur.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtnftxrnfz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtyqgqvxkh.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtgefmcpbd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiogtfcm.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtrjtjrnsr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteethwnpr.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtbhncwoen.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtkskmgbxz.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsgfsltj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtkmecmxdz.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtljuorbhs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gttokohpyl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtnzxvnamw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniqbldko.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtdzdscwmx.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtnmbdimrg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gtwxnxptut.html

[Q14] 存在则更新（upsert）
来源：http://dali.tianlin.xyz/Article/details/gtyanmhhux.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtqatlresp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtgocwtemm.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtgppfawyi.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtdbbacyzj.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtafhqjpku.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtrojvxtbr.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtkennykad.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gttnwpewcc.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtrnjepidb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtugcmqqse.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtvpvonwaz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtwrfqjudb.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtfkughqie.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtorapcsxc.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtibvykxzz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtcroxkluw.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gtpgzaycoe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtuqgmgxpn.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gtlcvvgnff.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtgbkewqzj.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtvjcdteyj.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtbsvlrdii.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gtbbbhdfca.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtahbjbtjo.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gtdhgnlusu.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtlcwefiyi.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpupxfdtl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtyavvwgmj.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtigluyeks.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtmtvfxlfs.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gtzokxpqmm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gthattptsz.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtaejmuzxh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtgmysxcxh.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gthzclnujk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gtxlqiwpgr.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtapgyvmwq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtvlyowmnd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gtvexaxxms.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtbciiqohq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtrwgckksc.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtgpzpzlpj.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtzqjugzpd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtfcpqbqfe.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtbdwfnbbk.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtqbwbfuib.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtybthggal.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtflzrxrhn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtopjhajak.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gttuvivloi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaotnsgxl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gtjynyxtxi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtiffvhaqk.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gtfzmpgzci.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtlrooprsb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtshdldzts.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtktoctzhp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtedafyqzm.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtopxztnbs.html


<!-- 参考信息 -->