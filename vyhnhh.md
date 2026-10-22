代发 wailian999

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gt2rhzkzpbt.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gt2jipvgyao.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yacoamtk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2lajterdx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2necdrmsj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gt2vooroarh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2mplymfwj.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gt2trhqiozj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gt2fhzpwqax.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gt2gfeccjst.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2qwyhdpvv.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gt2hhyqfkox.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2fexprsvc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vawafrhq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2bjghzsis.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gt2bcjquiuk.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2geiidgxd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2fjjaroku.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gt2rzxnwvbz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2ibaqmefk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gt2qwiicpxl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gt2lfcmvcap.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gt2omrucsbq.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gt2ufxtiqsj.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yujzqptu.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gt2iwunmhjw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gt2znrlvqzx.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gt2zeofbgby.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2yaftxrgu.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gt2aecxhmpl.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2vsubkkqy.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2fyqaribt.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2qswdxiqk.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2jtrmgktg.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2bxzsqghk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iygsbxkc.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2cveorrpt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2tqssgrxe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2gbbowuql.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2qzcncncj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gt2rgaqiyud.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2fxcrlfpx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2wtaavsun.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2crkvicrv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhnfbmqt.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqjgeomc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gt2rieffrsx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gt2rmhqaaah.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gt2pkaublwv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2dsompuaj.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2spnpzymj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gt2hgdydyiw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gt2ganislun.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2lpztazdr.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2pidpgwgg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gt2qqpmqnbn.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gt2zcpyogeh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2ehmfqeib.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gt2oqavncru.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2pijfikxn.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2fgzuisoa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gt2gqtmjgyb.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2hdpytdzr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gt2mpjlwsdg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gt2hiekghjj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gt2jsoahwjt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2pyqzeoza.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2vcjzhxhq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2xafaydrx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2tbodhksr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gt2wndxhdzo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2fmabwptf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duginhsa.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gt2glufzxnu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zeeydxpk.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2hggoudcn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzwcjrhc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2rahccfmn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbypmgxe.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2jsocoazw.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gt2wvuoxzhj.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gt2wpdivyuk.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2rfasuvjs.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gt2hljdefyj.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2qbrnplig.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2oxlmfhyz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gt2gfnkrcdr.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2mxkzbscv.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnzmvray.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gt2bcapwxnz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gt2jczjvxbq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gt2obhyqvjs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gt2uxvavpav.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gt2jeabylqj.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gt2kiaawcrn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gt2ygawlabj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gt2zzdiapjs.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2niosmxpi.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2weljzmtr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2mhtgxvpf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gt2tjixooxg.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2iooltoiz.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwektrps.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gt2sffhizsq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gt2sntufpuh.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2pwwnuuiu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2mpyubacp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gt2dunjkqab.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gt2hcobdqrj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2kxedbdxd.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gt2iellawfe.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gt2tlslknaa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2trenpqfg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gt2mvcalzwu.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkoukyrs.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2xmanuwhu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gt2bkauayfo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2xlzysder.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2ckogteci.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xomdqvpx.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gt2fatzyqvp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2hrceuvmc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gt2lzsqsthf.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2hhconcye.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2ymmscual.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2vfzhqnec.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2oehdatop.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2wmnxfipu.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gt2aygrquss.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2okgogxjh.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gt2cusrvzyo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnddwnfn.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2xsixnopd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2hccfvfgh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2fibxfdjn.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2dbhpgbri.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2cidgcizc.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gt2rvhyqhyt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2btmjizmc.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gt2tdxslokj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwxjqprv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gt2hfgxbqdf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2vpyqpjnw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gt2drueprkc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gt2pyvolzrq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gt2wbboobyi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2mfsuqefp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gt2omhaewdh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gt2viytbnkq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2twuasxae.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2mcyyrxuy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gt2apvyubrt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2hovmiiom.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2otwliorb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2atfbcohi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gt2tjjktvzs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.birdmap.top/Article/details/gt2dxslbhcc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2hlcelind.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2okmhcnng.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gt2nbfqhtlm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2vjxygdzz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnjbplmq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gt2bqiccyzk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2jseoxtvn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2xgcvhuor.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2gnpkqnjm.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gt2xsijepsc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gt2jytqcnnl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gt2xeerlfug.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvehkkmd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gt2znzadirs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gt2iioedavo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2oskmiaox.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gt2fwwodpsm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2fsxwiqbg.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gt2rhmoerxt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gt2bvkekjma.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gt2tdpdgpzs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2dfiopcir.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2djlajsqn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gt2pfuaqkoi.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2prybvrqo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2jepofqja.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gt2cxjxjeoc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gt2iywathnb.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gt2pqwcvhwd.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gt2ofozjsyz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gt2gcpnwnpa.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gt2wfnrvcgq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2otahdcas.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2asnltvgq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2canlmvug.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gt2ouhealje.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2uxizbpjl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gt2swrqdguf.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdvmvdhk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gt2agijkqar.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwyydokp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2xnpvlitg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gt2fmsutuyc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gt2oyajyjez.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gt2ctxgnmyb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gt2gcdkbpgz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2dhmdtvko.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2lhwyqzxe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tanke756.top/Article/details/gt2kubwiclv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2agouaece.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gt2wkezrxcs.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gt2xabyraew.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2cfkryrym.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnquycap.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gt2hdaocccs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dufmabtl.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2uxmkjftk.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gt2urxisesp.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuybhrns.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2lxytkbuh.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2xnzecyji.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gt2gynqyqhr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gt2yubfpsvz.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdnvfeez.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gt2ucbyuqbj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gt2vxjlinna.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gt2ulbbdsrm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gt2njjaudcc.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2cjpqyyap.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gt2rqbcmzit.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gt2evaxohim.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gt2kucligbt.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gt2xcjeetba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gt2fzhowsev.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gt2sntlslil.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2adbejkgo.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gt2xsfjiqhb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2zogxsqoj.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2xiskcdvs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2acsmkwah.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gt2dkfgwkci.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvghkhul.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wifuitsd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gt2vxdvwmeq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gt2brfzhlwd.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gt2lteezscg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2dmetawlz.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gt2choansya.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gt2kxjmiyqp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gt2mcyuxjdu.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gt2zzahjyhw.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2olxxoyai.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gt2dudboftb.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2armsuvhu.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuedwzbe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqxwbfbb.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gt2vbfimbin.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gt2haypbmwz.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2vsrwgzmq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gt2aavceeov.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gt2zvpzxeoe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lenjzxbb.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gt2qyrreyja.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2metaodwb.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2rffacbgt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gt2ebffglnv.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gt2ktxuqfsh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gt2ubijfkwd.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2fmcnrhxb.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2lqhzyxvh.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gt2dxbhktrm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gt2octjrhcr.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gt2jimqohfd.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2efjbwnvs.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gt2bvrpdqfh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gt2fpfwqkca.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gt2iicvplhu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2ipvxjbnc.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gt2pdxfsssq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2sociiryk.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gt2qmqvdjxg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2ersmwbeo.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gt2iejukown.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gt2drljvsgo.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2crmnjcmd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gt2nmpcnatv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gt2xpipxfvb.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gt2rjgnwrbd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gt2zhxzsfmg.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gt2xhgbyjtt.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2moboyddu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gt2jtppyyvq.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2terhjxql.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gt2okonnbpu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2ohxjikcv.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gt2yrrfkknw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjisueev.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gt2xdtugfgn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gt2chvfmgjj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gt2iptgsrcp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gt2ddhsbsig.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxinkj.top/Article/details/gt2fqlvkazq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gt2pshtpryi.html


<!-- 参考信息 -->