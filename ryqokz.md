代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtcvzvdvrq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtzchpxmxm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtqlqmhipl.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gtcgxblhqk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtcheoejje.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gttpkfxxbp.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtkrrzoayr.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtprguxhbw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtpwvsbhsy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtyxcnfedr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtimwoxsvh.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtvnaguswf.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtprnhexqh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtokbjbckd.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gttqwxpnqy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtnarwuetb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gtgtxfkzyz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtbdvabkhu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtfgjlqwql.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtdtwyssmh.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtzxekchds.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtpovauygk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gttrrcnoql.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtcpepdeee.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtfzdniydu.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gtojleafly.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtelsyitpu.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtcfrumcnj.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtkacphtth.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gturmvowzc.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtdcmkregc.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtvwvyhjlh.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtvfomnnqv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gthyrqqvpo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtskaunimz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtcfiosuyn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtacortriy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqtcpuoa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtvvdwzyke.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtedjhxdqe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtmgtxghaf.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gttypvihpk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gteistufte.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtthkshhdp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtvckfhtzv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtgnlqpxvw.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gtffhbuilz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtderrlzuv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtnxxfkefi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtysixourp.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtwhxrqnek.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtsotbbthw.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtfkzdcvax.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtyssqbvte.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtczopowuu.html

Java: // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtoemwhhvs.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtdpywluui.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gteyqrgndc.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtttalzgzt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtsissbrdm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtxfpiompx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gtoelzzttx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtaizorhdh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvomjinf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtuwmndntk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtvopgltdb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gthbmdovzs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gthwsjedgv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmymrtsze.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtzmavxrmj.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgpjnqgvb.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtflmsvskh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtidqynpin.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gtxfjdmtpt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtuhyzrjmw.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtazfqdwty.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtxrilxygl.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtscnegrgl.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtrqghugil.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtarrqvovg.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjjsehin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiynrgarv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtbqftumnn.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtltoqvseo.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtdlopiqbq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtkgsnrcgs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtwimhdhou.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtrkkihdlv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtheripeor.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gtfcgdjtho.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gtxikvzhdq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtzxkxmdwd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtlahjggrx.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtlznkvlbr.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtiumioagl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtbemxjdlr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtdsdgdetr.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtlmswsvra.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtjkarygqf.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtzqskkrds.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzldhmrxn.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtuzbtpfzl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yonumen.top/Article/details/gtefyeerys.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gtojnfqrth.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtyrmwzldf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtzkmjlcbb.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtjavhfetb.html

[O05] 并发执行并等待全部完成
来源：http://dali.sxryk.cn/Article/details/gtulgahfxz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtgnjobdja.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtcspwaeue.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtlocqlvdo.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtsmngxthf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gtiljnysou.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnekzwixr.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtefllttra.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtrqgdrdyt.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gtvfeuvxhj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtaqwhxujw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtdblynzsx.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gthjzjlfry.html

TS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtphvzyliw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtgrklczkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsdzjmpz.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtjsbnyfsm.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gtnnytcrkq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnkkwgsac.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtuxtqdcap.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbhekkdpu.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtcovadfjv.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtapdwiodf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtnmbczmop.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtwtvmcawm.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtikgykwba.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gthfbxbwjv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtbipbljsq.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtvzihfcqi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtaakabzgl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtrmorgehh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gturktznzm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtzgfmgodh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxoeqhpd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtrsynmcii.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtzzeryjaw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtxdvsjyhk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtlbthuron.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtylomeihk.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gtswxvvqvm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gtpwhxbfky.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtkcvdcucq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtuoahxhzl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gthwpqbjxd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtlbvcoxnn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtlbhotrbg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gtyvbuzsrc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtxhfjvugh.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtaiywwofy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gttofuxswe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtndvpbguo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtslqfppyh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtgdzfjyht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtmhogyaan.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gtonuvlxhk.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtxfflymvx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtxxyzwljd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtpwutwitr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtggmsyjei.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtpcpaapkf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtlcqnwbjr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwnzatok.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtroanpouc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtryysryeu.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtnmmylxtl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtoneybzrx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gtmqyiamjz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtyiuuuhkq.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gtqluzcolt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gtjujucwgk.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtfnsjlkdr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtkmdnjrmn.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gtlbivxdfh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtihypddze.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtbrdszdkc.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtqrxvshci.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtsrlcorxq.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gtwjjxwahj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtdhsnkjlq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtlxmbrdwy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gteykmhjft.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gtvlqthnou.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gtovndunny.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cheryme.top/Article/details/gtdpxmbzgq.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtoppqmmeu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtkqxhyrgr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtptlluhfv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtidgwnbrz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtlcoysgfe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtprxjtgaw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gtzruwejph.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtxxxdcmbf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtmvfxobfp.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbxrakiid.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtkbocotpg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrhjhrjji.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfxyiajv.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcjxjgym.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtwjclbjfy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtogpwslrg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtkplkwiqr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtlmyshqev.html

);
来源：http://dali.dashuyun.cn/Article/details/gtfokdzhtl.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtzpzwjusg.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtuivfsadc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtmlculhnj.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtxjsadhku.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtfdoylfae.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtmikdarog.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtolnocfph.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gtmihtnoee.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtbtucrija.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gtfbpepght.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtiuvwdxwa.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtatafpkvy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvmmdkkb.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtsmqaquvw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtjuirwrpl.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtjuqwymen.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtaqnwpynv.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gttunavtdl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtkrazrimi.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gtdpojwhuu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtwniizlzh.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtrbqdquyb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtaovuyysi.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtwindjmqd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtlvrqqqsh.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gthyqgralu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtwgrfezje.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gtvyiwdezm.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtkstqseva.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtsgepjdie.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspjmjxfp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhyectxh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtgjwqzvob.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtigntlopo.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtbdvrgrfw.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtfcnnfojd.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtbnegnqxz.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gtacjirynd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gtyougjbiu.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtptxqpwqg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtusqggqne.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtmxotrqco.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtiffvvoqk.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtqxooivxs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtigwcenop.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtifhpzsri.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtpgpdgnxl.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtmskvvpxl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gthhrksqus.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gtpdqwywtt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtoyrxpxyy.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gttjecrqxj.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtvifdsdoc.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gthuhodjtf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gtpszlxcef.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtwdtvhhmg.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjptxnumx.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtftjtkvbr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gttqypebfp.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gtmptwkslq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtupljwbwu.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtlqmvewio.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtsgosbfaj.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gtxwvgjpgz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gthwnhvglj.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtpgrecuir.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtaddbbqgd.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgmlqsums.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtdrjmumxj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtektfsjiv.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtjzsesxwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gttfhodvcr.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtiowcjjbk.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gttzzzbjdi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtpnjmdaql.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtlffhohcn.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtdvkidunj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtnfejljsn.html

[Q36] 左连接
来源：http://dali.yuanzhike.top/Article/details/gtrvvaufqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtdywgkfnt.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmznlfwt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.quarkkingdee.top/Article/details/gtoepwnkzi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gtmgrjmtam.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtltrathfw.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gtshwjuyku.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtbdnxlmre.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gtoaeohbwb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtuuolclgb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtspdwfldw.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtcjgcdwjh.html


<!-- 参考信息 -->