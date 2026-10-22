代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2gxsxhwsl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2cpjwfzcq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gt2rjvrrbtv.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gt2teqqwrzt.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2vtktefem.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2ylzpyntu.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gt2znzinrgj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gt2zewezaxg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifwmdlzc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gt2vtsxikqr.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2azllgzbx.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2zhwgoray.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gt2myxvhmhy.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gt2piohlpdz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gt2zfwbdqcd.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gt2cztrfxhx.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gt2nvllspjl.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gt2ysalbydn.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2spevcdya.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmraydnp.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2isgsmxbl.html

Go:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2eizodkgk.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gt2kjtmmtfv.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2piiodatr.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2ybtejyqy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwfmgbun.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2qqmmuvbk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2iuhlgsdq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gt2butrldwc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zleoltkv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gt2jdhcogsp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2mhystujl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2ocsdlmbc.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gt2havlllwn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gt2rgetjvop.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbwrhkve.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gt2ervqszgf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gt2thbmqjag.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzraypli.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gt2ivsocedv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2siqvurko.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gt2vmodwdiu.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2iumbwrtx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gt2agpmxtuw.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ktuvbbif.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2gorjvrfl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2kznoxuvv.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2lmgnkmnz.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2rkkgqahw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gt2onurgmyl.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2rztxacvh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gt2iaqczujf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqsoeyil.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2yujpmgtl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohwelpgy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2upfntyeh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2xmebqolv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2zoynxgnq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2vfkeesrt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2dkgcwnui.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2edtoxfis.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2ehyeiaoj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zvthpmig.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gt2qtrroced.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gt2ivwfqvzi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gt2vxummjlt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gt2mnvtbbeh.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2kkbheouq.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2nchtiotb.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gt2rgfpnyhv.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2znwigwgg.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gt2qrgroymw.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2xqbcspia.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gt2vjssgjqs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gt2becymmkz.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2dzpbgfgy.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2vdpbkvux.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gt2mferuesx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gt2ypwyscrs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivehycyu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gt2jlkxtzkd.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gt2stnokwgu.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gt2nafcwsae.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gt2uezayonc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gt2oonzacxp.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2wrhcbiwz.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2bnvlxocd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gt2tfnayhxh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2zafdhjxx.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2wvlhwxlv.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gt2yswheljk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmsmsqaa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gt2wyzezozi.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2naoeyieg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2dhiyhheq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gt2kpsrisak.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gt2xrhsblua.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2faawyrmb.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gt2xdzlkmfl.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gt2jnwofiym.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2xrbobgif.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gt2umretlnr.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2yujdlqkz.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2sdkhmucf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sufxvd.cn/Article/details/gt2jewkcodb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gt2uchjalkd.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2srfrazyx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2moggcunv.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gt2ycsuonvr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2tnkgzfyk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gt2pzczehmp.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2oacwhzlv.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2nhvrhpmw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2skxnlmnt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gt2ldgklbtt.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjfysogu.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gt2xanhabeb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2knucciap.html

P. 常用工具函数
来源：http://dali.ybcxt.top/Article/details/gt2ftgskkbj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2liwepbmu.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2jbbxsgcm.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gt2qosmcjyq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2wtoxlmgw.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2nxowguzn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmfapnx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2mpavcigl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2hfbmislt.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mayyeksy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2eynjijey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axnzdtmb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2osjfbava.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gt2lwsyyktz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2gojcwimd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gt2gsimdxah.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2akwpqhth.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gt2aivfycve.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gt2xuunlgmw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnihyzey.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gt2yhqqmolu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxbfbgpn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gt2dnlycdxf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkznsnj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2dicfjoze.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2faziyucz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gt2rdifvwdt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gt2tdpyzovr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gt2zlyxhpqo.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlmpzjfq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gt2xwcbuszu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2tyltfnxm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2vbpqeyqv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gt2joozsfmj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2ndgnayuq.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gt2gtblhoff.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gt2hgtiumnz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2cbvmuaij.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gt2zttktxuu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2stsdqxam.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gt2dwadlzzx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gt2kficimwg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2uvcvqvqb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2gjejuwrw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2gqrqycnb.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gt2tfcqkxzn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2pzzchdza.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gt2ndgslxiw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gt2ksytxpor.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2bgqrgrwq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gt2rodxqgjl.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2zwlkqhgd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2lmxsfvzj.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gt2tbfxxixh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gt2otmkeamw.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gt2osbpzygv.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbpektke.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gt2tyoxvxdm.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2uzyyepyd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2aczigebv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2dwuhjhhw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gt2awioiaaa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gt2ynuioeje.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gt2cczwatsy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gt2lbrlgdrx.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqkbyvkq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2fgqzxfzv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gt2ckuxouff.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xovpmqqq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2kudvgbsg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gt2pduzcpmz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gt2huxvkdrs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhrgrtkq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gt2vnirvgsq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ocujnpts.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sysykeji.top/Article/details/gt2pvnrwuth.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2mpetlmnj.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gt2zgtwczqk.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mixsjmfs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2bhbbmlak.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2zatmrijh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gt2rpleuguu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gt2rmcskwax.html

);
来源：http://dali.andypj.xyz/Article/details/gt2iofwwizk.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gt2ghehuwee.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gt2ocujmowi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huzhqdwd.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gt2royheshu.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gt2hxlheuct.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2pzzsvhka.html

);
来源：http://dali.ivvv.top/Article/details/gt2cficbxkk.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2fctkisrk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2ephqpjwt.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuldyikj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2dbevnhvo.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gt2pjtazcbb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gt2rnzyyceu.html

[Q06] 删除列
来源：http://dali.guowangkeji.top/Article/details/gt2bgektyza.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gt2iziwotrb.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gt2gwgnxplj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gt2pitgclkp.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gt2dyvdxuvt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2yfcevlia.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gt2gvpmsgqx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gt2cbzmjkmx.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gt2unuhbbvh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2ziovfjph.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikrznzbq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2pubhwyib.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gt2fvzfcoab.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gt2plffijug.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2iclgxtnh.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gt2jsralnss.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gt2eoxjhvla.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gt2dgloywww.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gt2ujpjejqk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gt2mpaazwtb.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gt2qtjmynsu.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxwdqben.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2mlzredxa.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2jakdjvkz.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzclrwrr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2aqrmulft.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gt2fsxdlygw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gt2yhsnefor.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gt2avsmynos.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gt2mqnyyrmw.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gt2vgitpqvx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2capcrzhc.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zeoeskzq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gt2xdinwqdw.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2cwcyluvg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gt2oeryhrhy.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gt2qeujnfug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gt2gjouhqyw.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gt2onzmrukl.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2qurpendc.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gt2jpyywviw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.mhx1999.top/Article/details/gt2crmhvera.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gt2hlxiykyz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2pwdfscea.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gt2pxklvmjd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2vjyianxs.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gt2vklclutd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2orrjviae.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2ulxesqcw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2xakuordm.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gt2kcyvkbfr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2rghvwpkk.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2tqjqdxot.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2xepackzj.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2utyntbox.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfosnllw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gt2ulymueqp.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gt2utfldjoy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gt2uljsekgb.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gt2njfjchwb.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gt2whiekckn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gt2uymcsnae.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gt2fsvbwmkb.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2fhysahaw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2cdbyhqxr.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gt2okpvfwek.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2vugskzfh.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gt2wrncotmx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gt2rvwyaqqb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gt2ndnkrimu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gt2hymfbvpv.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gt2bocpsbxw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2ffflcdma.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xikukvxs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcptfugl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2aemczotn.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2xwmynjud.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gt2lnxxpzjm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gt2cleszwzs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gt2bjqjjnek.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdbdhrvb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gt2rntfdtuj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gt2ffccxwrm.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gt2yiptjczg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gt2yvuetsgh.html


<!-- 参考信息 -->