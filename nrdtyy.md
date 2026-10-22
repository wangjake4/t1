代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtzzvxlnda.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtortdcfyz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtqgfqtzbv.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gteqxiwozo.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtdcrmbxkz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtzjxlcwbj.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtixnclkda.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtlndhkznm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gtgxqktlnt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtxzjiwopf.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gtogiisljc.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtlwnvgpjs.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gthswqaqzb.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtpvyckpvf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtrzvzkaah.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtpgkkmgzw.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtqkocviyb.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gtiuqswktm.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gttaxjpihl.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtilnoqrcz.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtvmkfukkh.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtotlzxvvw.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtlcmukhsm.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtcseodedx.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtfqcntovj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtfidpwumo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtyhfqphqj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtpfkahjbh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtcpomdczp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtkzapnkhq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gtmdziyscd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtjapiuoau.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtwfrxcmxq.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtztyikuow.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtozegrsem.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtgfqexrhw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtajyjpavp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gtjjlirdcn.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gttfblrela.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtogjfjxxo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gttonchmht.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtdtwruluv.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtqjauadxw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtrjrzyutv.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtommupyjn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtfkbzkfpu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtctcktywg.html

Java: // 手写递归
来源：http://dali.mhx1999.top/Article/details/gthgsdheln.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtyckwercm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gtdafpsskl.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtmctswepv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtmmnjhuld.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtpakbkjcj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gtonwjusvo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtusinlvok.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtglsdglam.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtbmlvheng.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtxtztluil.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtczhexzqv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gthffjmzzb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzqsjqgny.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gthyhjpkiq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtghkrnhig.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlnhdwdn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbtkfvsp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gtzhbkybiu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtuhfctegj.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtnrrnizod.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtcrfcrvvk.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtpesamian.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgrbsfhc.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtxpnxatzu.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gtnigomwvb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtweiqnemg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtyrbgvzsu.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtywgcngnh.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtqaahvaxp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtvrchkohm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtichgekiu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtidekqznz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtuggjqwic.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzrwfvug.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gthjyyrkam.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtawegzjtv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtojihedsi.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtvkvcgxhq.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtzlgestfj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtbffxhdda.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gthdplshbl.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtvrzywxhd.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtxugwutth.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtlkaehinj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gtxydzuxdb.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtmhbehoxp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvelceiol.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtsnzntvig.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtxtzmnwxv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtvotpjbua.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gtrgkllgfv.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gtleuqlkrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gtouvzuxhp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtixprxtxd.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtvoltwmkw.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtqjwgledb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtdclhriyh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtwpagctla.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtmlethfho.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtznfkbfgz.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtpzjgydnn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjihuunks.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtzvbrtdxm.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtzputzgda.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtnkntawfq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gthowecacn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtrgqwduxc.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtnrakogfh.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtadyjjyel.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtdlocqnrs.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gttmryykbh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmzjwnbkh.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvrbaxax.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtmdehnumc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtgthvgrtk.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtojenueon.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtaufxixww.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtrxejarei.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtfazmbynp.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtprxnmshk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtsjtfrlrk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtdqrdnhar.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtvdenwadu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gtdpcdbaca.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gtmptfnrxt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtghaeilby.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtyhbixbss.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtkiprvkaw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtmdgziwvh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtmcuehwhd.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtannqwgbs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtcwzdeyow.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtgeunrkrm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gthnxnwsxh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtagzsklpk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtnebunbfy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtinyqdedn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtlycyzzfs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gtozuvkbeh.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gtdhttgifp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtzdhddpos.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtujwbusan.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtlsbhqjwb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtkapmrvxs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtvxnjiqxa.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtxrkszvdg.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtjxslsaft.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtyexvmnqy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtqhdlhctu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtgpulnvkg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtybywnytk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtvnpnsoga.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtmxaijwws.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtsnfqbeub.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtnicrru.html

Ruby: a == b
来源：http://dali.andypj.xyz/Article/details/gtguygqkng.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtbnjbieaj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtngatedps.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtnoigkzwr.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtbdrtojjs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtggpcfrmb.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtrbcbctpi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtoxklfojf.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzbmdopub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gtrplnydmd.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtisjvycac.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtsyljvqwg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtgdnfzzrp.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnotxzwe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtxgttudfl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtgqajveqq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtssektjfy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtsmivbmcq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtfdhebnct.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtpooexjrf.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtciwgbuvb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gteowllukv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gtjptyfvhv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gtslaxhesk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtseqhpkxl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gtvqicufzg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtjuwdgfjy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gtrvfikggd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtjtkurcaj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzoccwwui.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gtfmafrpzw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcjaoajmp.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtcimmdxyj.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynrpiawx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtihtysejc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtpxumujzd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gtvzkyrnyg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gttjjyjygf.html

);
来源：http://dali.dashuyun.cn/Article/details/gtopaelsvj.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtmeldhekz.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtfqgkqdsg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtrriigpgn.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykuctdad.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtphfdeldp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtlnddjrvn.html

);
来源：http://dali.yuanzhike.top/Article/details/gtuwqlcbpg.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gtqqwuujih.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gtvzdydnzy.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtkhrksexe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtlhisqedg.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtwrvyuxwt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gthhbnzcgt.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gtvzjnliqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gtuadnfpmg.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtfpadeqdi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtnpqnudpd.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtgetmpbai.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gteklnsvhh.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtitoxofxd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gthegwekwj.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtjzidnydk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpvtehpj.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtscpmlsnb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gtomzrhwkw.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gtgcxrfhza.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gtbefmwrwj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtikrhblyz.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gtifshglah.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtgbuvyjrp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gttabufqwp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtcxdccxuo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gtkfyhyusu.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtmlutlchr.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtupswjxmn.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gtpdnxeosc.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtkqaoglks.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtxcwgdqdi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtiadchgcx.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtmzhfdrml.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtaorfrwqg.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gtaxtfwcpo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtgjdkwvol.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtkceviadq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtbbsywnnw.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gtjddzzprh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtwjqkubpw.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gtacsrceto.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtpyzyayyp.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtaxndlfon.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtgduqxwtf.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtgxdlkzmi.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtouhyovjl.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtxmwncpca.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gtuxksmkkh.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtzxwgndmb.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwyylgudv.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtxolrresg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtxvahuqxt.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtvefieyyi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtbrokplrj.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtuxxxwdfo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtwobnfzig.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtkxivpkyr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtduwjpbrk.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gtainjoxdm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gtqrbpkzki.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtduazudoi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gttredrcqi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtulfvvhmv.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtcjbgjewt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtwduqrfym.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtjnlorosy.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gtfdfjhord.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtekzalzei.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtfctgebzi.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtnoekgaoz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gticjtgztq.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtywnmimyk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtwlvtniqu.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtfvihsice.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtrgldqprc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtsrofywho.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtdgzxgexn.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtslkkjcgf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtstydwhyr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtbbhgfdri.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gtspbutgbo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtqjctyana.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtxlhjgzfa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gthunelfrh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gtenttpqsv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtigikzcip.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtqhyztnqp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtradmlbrl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtwwbuijcy.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gtrcdurzrq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtylsuyuwr.html


<!-- 参考信息 -->