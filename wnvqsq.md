代发 wailian999

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gt2wgwkhmyi.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2sheblsuz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxkgllwr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2dkttgfqv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2fxyssfps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gt2okzqhbfv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gt2jentsbra.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntkjfkhl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gt2pxmcbqmh.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gt2evsctorr.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2njbidrlo.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2kepjtxoe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2fykqjkbc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2tavfsznu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gt2ngcxqbdj.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gt2vuhznwzu.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gt2sytwgpwj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2ccytmxez.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2byihzvyu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2xxbvwjdv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gt2schasnvz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2pdgvmtcc.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gt2dsdadwzi.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbftzepq.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gt2ddqhrwjl.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gt2cckxwmnt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gt2ujbqgfpf.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gt2nvuidkda.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2hsrrxaza.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2hvkyctkk.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2loptguef.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2wxbywhrs.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2bfspuryh.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2aptohchl.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gt2ulfkgpjl.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2pydoiohq.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2lqzwbytq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khazrbvw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2xqzjkrbp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2ianljfiw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gt2exnxpdao.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2fekcveuf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gt2ehqlzdbm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2yipntqio.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2gqxnsxoh.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gt2jonkcfny.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gt2uwtwmigq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lmixkesz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2tjdyfchc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gt2ikqfnlpo.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwkzilom.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gt2hccdjzhz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gt2omnnapei.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gt2icwlqrgo.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gt2mircfkxt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gt2jtscgvqh.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gt2zqhuihpe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2hcdmnlhz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gt2prjxcxqn.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2vbbnchny.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2ivtamqbd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gt2mgsgoaja.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2vadbmuqy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gt2yjasrxvr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2dsycxvsw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlfdjbq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gt2xejbosos.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2swqhexej.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gt2nzzfbgqx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2ukxaoyho.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gt2xnwoovzo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imsppbxp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2eurnwpxb.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2etiigvit.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kjzhvsso.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gt2ffenpdzs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkzceugx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gt2cqigpqzn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gt2nzafyken.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2fszlnqyr.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2vvmibmdh.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykjhuowt.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2ixncijux.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2slxqdjcj.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gt2asousbvu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2otfymgqu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gt2yiedabgj.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2qojrvovm.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2ghaabaid.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gt2ttlxhwqx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ivvv.top/Article/details/gt2vymrwmgs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2aceqtqns.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gt2buluniti.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gt2grqbwhhg.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2wrjgpbfi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gt2vbqxzpbd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gt2osbhsngz.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2pihrbzzg.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2exkdqezz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gt2bmqwkice.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gt2famvqqya.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2cyynbsbv.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gt2dswhjyeh.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2xuymdfus.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gt2cisfpvyr.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2ldtpjoam.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2pivtnjif.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gt2vpabhlqw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gt2ejcqxegw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gt2rlwyyvts.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gt2ydqdklwr.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gt2qrqgknnc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gt2bihjfzsw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gt2cbdgjtrk.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2hddgects.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2vyvaylub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gt2uhqozgmx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gt2iacrdslf.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2uxprjfxo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gt2bkgkrbpt.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gt2nzyjecjz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gt2euxmoknv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gt2uuagnbbq.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2gxupjmsh.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2uujthjui.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2qbetkzyb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gt2wioqueos.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2svlbwelu.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gt2lcnwyclw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2mnzxhhfl.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gt2skqimvli.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2vyikfeez.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gt2hirjvyxw.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gt2jqtejeyx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gt2nvkrtwdg.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2ktvnyfqb.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gt2ircadjwy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2aynihajy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2rzhwlkzb.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gt2nmgzupjl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2ofsggaqb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2royyqbdp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gt2qxxpcdgi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gt2nllknglw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gt2dyfeovnc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gt2xxidagyn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2opmopogm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gt2mbstbppn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2idlqrxsr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gt2ldbjodar.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2vozqifey.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rwgewveg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gt2kiyfsdfo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2busjjnmt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2xtoqbehk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gt2psxdfgis.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gt2ofwbxqax.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2qyonadbt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gt2byglhhbs.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gt2kkvuumgb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gt2dngyqczj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2xolomycf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2uvbeezfu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gt2lvypnxdj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2foeeckfk.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gt2ljjuwzrt.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gt2rfggjqcl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2ynkkelwy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxigszka.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gt2iwwoytqa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gt2affqgbve.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gt2pwpmesqn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2hyoxnici.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gt2kckvepxf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2ffjfxzit.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2esggagaa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gt2ftciugfl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gt2doxdrtns.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2llobqiet.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2pxtdcnfo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gt2glcmlxeo.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2jfdxomxk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2rfiubgcn.html

Go:   if x == nil {}
来源：http://dali.quarkkingdee.top/Article/details/gt2sjzzkhzh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2cyxfcstf.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gt2mdfyeaap.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gt2clfnwjln.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gt2hxealjzt.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gt2ktjerjuk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2srowllsl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2teiyygjr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gt2wkfmlavj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gt2ppsrqdae.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gt2ytzhyypo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gt2ahlikwnd.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gt2nryocwys.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gt2txmftvjv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gt2dpgjqjzc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gt2yjqvooox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gt2ukweprme.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gt2axtvvccn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gt2frnwdksz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gt2qxvqtwyx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gt2ibkjcrgu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2bnkzqexy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gt2ntitlfwq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2qfsvfmfp.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gt2qnabdiqi.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2fcqsbyvl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrzngoob.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2dpgbzcqj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gt2rzorowhw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gt2wzpmqged.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2cjyksoqq.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gt2svkytlrl.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gt2alxrjhra.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2erbgaaxb.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2ixtllvzw.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gt2bewfvfsm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gt2yvvlowum.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2apbkmctl.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gt2xobqllxk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gt2qiaqtpdn.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2wrwtwmke.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gt2cdguzwcs.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gt2vfmsbzcf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2ndxtxqhz.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gt2msilvagb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gt2rgdwrtko.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2figojmjz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gt2uqlirvxv.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gt2roorprey.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2ogwqljgj.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gt2sbzvxdbh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gt2rhxthmuh.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gt2gwsnudsx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnscvdex.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gt2wxmpydix.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2mfvhctay.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qqechzdd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2gwdxxnno.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gt2tctpdaff.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gt2rcohfxry.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2viafvgwc.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gt2coqakkbc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gt2xlobhmqf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gt2jtprnkly.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gt2suqzywjd.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbiavkdm.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gt2vytobjqd.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2dkwaefkq.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gt2ryudrglt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edralnin.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gt2dkbrbvtl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gt2ygdjakar.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gt2exyjjeoa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gt2ktklnokn.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gt2cpyfjsao.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2zksumzpj.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gt2elaulhkf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gt2hzwjektf.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gt2vfflyszo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gt2iwcafczl.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gt2pniqaezw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2mvrcnoby.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2xbrjewwf.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2zirllzdf.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2evduzvce.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gt2obkqsuzl.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gt2krjdqjpd.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2czlpkdte.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gt2vudqtcpk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2jyuilrux.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gt2xvtkfhxa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2yvtvnybi.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gt2bnckevcq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oysdcwxd.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gt2fqdqhuxv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2qbhtforc.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gt2zvvwpmvf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2tovoawrl.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2wnqyqchx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2pccijxmq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gt2jaygobba.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gt2ocwsqkwr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gt2fdewrzcb.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gt2kabtzizs.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2ndchfypk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gt2gzddzjsb.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udyoutrq.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gt2ffnihpuw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2tkyjqjdf.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gt2vnfzapbo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2xewjydsl.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gt2reelifbx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gt2vxdjllfp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gt2tesvxbmd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gt2ciptzmdl.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gt2coxpddiy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gt2brumjumm.html


<!-- 参考信息 -->