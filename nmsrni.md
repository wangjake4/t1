代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gt2qkmoyyvw.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gt2ezhqrdaw.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkynkvph.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2atnxkcxn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2diqhxiqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2vzrctthv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2vmqxakkc.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gt2qcpyqdvl.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2adfhqykb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2kaoavnuo.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gt2lsgcrcsw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gt2dcmqzjrs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gt2vqvfxtii.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gt2pusmvxob.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2iperbsgz.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouotvmvj.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gt2vgbzlpvd.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gt2endboskr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gt2pwnepnjc.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gt2fqjpmxet.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otpgsidi.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gt2evmnogxo.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2njcrovxh.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2oelmdfly.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2xodxkpyz.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2jrshkipu.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2rinulodc.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2qrapdhbz.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2sjeivyic.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2ozxjebha.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2pyjlkmpb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2vhrlsvdc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gt2rbcjrgjx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2xobcokyo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gt2iixtvcrt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2qzikzeot.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gt2jyirweaf.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gt2lxsnvzdw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2avymhbxa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gt2bnlkbnvx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gt2zjrxojar.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gt2rvbymicv.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gt2avvhkylz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gt2vsntleka.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2striznfb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bffjmqpc.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2hqhixedf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gt2npuexrna.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2rvisxwpz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2cydqbhjd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2yypwjxvf.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unubsbaa.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2apwoomss.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gt2qobqfvnp.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2xiojircv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gt2fquleybb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gt2rvckrnkl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gt2ufbgkcgc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2ojwknapb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2afeiwxke.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2lbzevekt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gt2vgxyecps.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gt2xxhyjgre.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2cmbuglnb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cisiifiw.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmwptpxw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wresoxvs.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gt2nexcmvdn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrmrbmmo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2fooethcs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gt2evuhojdh.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2efkhgxeo.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2pqkanoke.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gt2mjkuccsd.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gt2vilucupz.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gt2jccxbgni.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gt2auwkbaya.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2abewugac.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gt2njmredhe.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2syhqyngl.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2cdbgmxey.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfzffpez.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcuhqnon.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gt2oqphwzka.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gt2ueyrkyck.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gt2olgyhsxk.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2adabplmc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2qpbziahs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gt2gednhmkm.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2ajgbjwmp.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2qhzrujbl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gt2vdtahrmk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gt2wthctrfy.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2ksxylxov.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gt2mtaokvec.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2tofprchy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfwaedcg.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2yglqhmty.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2skzpzrqx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gt2ycemjjpw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gt2zviectgm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gt2pjgncqsy.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gt2zaswllou.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gt2zgigbuvr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gt2qawpgmrb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtnmgjbf.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2idavapey.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2vskbfylh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mohqbfsa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2jxwsxmii.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jobibsfi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2qdhdwfuw.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2hcffpbja.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gt2zcmhqzcs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gt2vrtqsdme.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2rslkkhzq.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gt2zhhuygkb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gt2bhskbufz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2xqbeolem.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gt2xolfntul.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gt2bvjptlzk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2qqelieif.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gt2kaaymuva.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2xgyztxee.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2ddttbmua.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2omdlvyaj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gt2jjbrdrwq.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2smaybnjt.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2zzzmeflm.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdxzwiob.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2zcbmsebi.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2uxumkdvn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gt2buwymoex.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gt2kqvyvdvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqmjvpap.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2acgvuqol.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2wxlbbkad.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gt2qjqqyymc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifejycqc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gt2vhwgwssq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gt2zelvifby.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gt2mdkxwfgz.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2igjnmzbl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gt2nkejmawd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gt2eubczucm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2oxaqsbqu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gt2ojejexul.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gt2jckvqime.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gt2upuuwdov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gt2fzfjdvfm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gt2jigmznco.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gt2jrlxdwxg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2vovezdzc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgixcams.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gt2pfvufkmr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2oiyheiej.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrxkefyu.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gt2xassdvkc.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gt2heuvobrh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2yqedfxnj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2moftmdmy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gt2lfnowzof.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gt2vuldhhjk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gt2swjwolww.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gt2phoajuzh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gt2vpvqutxt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2nitnhakb.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gt2ghbdrpbk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gt2zcuwgmzz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gt2wzhgzsor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2valfyqmh.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gt2ofceseod.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gt2rbwoewcu.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gt2hnppuaya.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2efqwmfxn.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gt2tnjdrysy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gt2bzeduwuf.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zyskhnxp.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyvrqywx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gt2mekplhjf.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gt2cipkacxt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2kxqbzncy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkeausnd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gt2bodxsqzo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gt2pmkjyrhr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gt2hgcnwpyf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2bmhanecn.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2cszqphcy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwqiyrmb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gt2wuqrtcyl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnxiangtu.top/Article/details/gt2zknkitjg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyildfmq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gt2uweclwrm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gt2igjfbnnm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gt2btvzgrzl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2rcojafrf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2uudgfepr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gt2erbeynbf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2pyxqwfys.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2zxirxlbk.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gt2dqkubdio.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2fkpuqlzv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gt2ulxhhzms.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emgdxmne.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gt2lryutweb.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2fcuecpqr.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gt2hyguzygi.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gt2etsmldex.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2orwjdipr.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2ncftpang.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gt2uargwjtf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gt2ecbvckww.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2dyqdrwse.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcvgfzyx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyoevjad.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nkugqhye.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2fccgqfrb.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gt2aukplvpz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gt2zprvdmnm.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gt2yphbalyh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2felazzxg.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2sukozuea.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gt2xhubdntp.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gt2gjvcakcy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2mtfimdnx.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gt2trkfadio.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2kdtzohuc.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gt2jrscpzsq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2wijzgify.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gt2unpasejm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gt2cdovvncs.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2mjmuxpol.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vuqmladq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gt2edjfexre.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gt2vjnxjsbx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2caegnhat.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gt2mejdmsau.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gt2emxkemot.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gt2bnkpqyko.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2epkhmszm.html

SELECT * FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2scdzuabc.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gt2hocmtnno.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2fymgkqxs.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2iklpkjnk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnuvvtpc.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2gwaofbsd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhmkmikt.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcgkocsz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2exrnfvkc.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gt2xbwofauf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2pudxwyne.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gt2ejvraaqr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2dtuueouw.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2izrxbyue.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gt2wkfatbsh.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gt2eqjgieyk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gt2ehvjdepr.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2edearelo.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2rvixmgxb.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gt2elfayesr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gt2bfafjdni.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gt2ikijgaww.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2segkcvzt.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gt2wcpnlzdv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2htrbejio.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmxzktix.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2yhoerslr.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2jirrnyzs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2kebqhtcs.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gt2qkkuuzjc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gt2ahjnvupv.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2rywchghc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2wwzprkcj.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2soyuygyl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpyhazmn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gt2xzijreub.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gt2pwskycbg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gt2czllaadw.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gt2biaoynji.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gt2robiyjfb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gt2pkiwyocl.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gt2nnilzdew.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gt2pclzefaj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvpcwvlh.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gt2xkyezist.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gt2xqqplvma.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2qikgpzlu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfmcnxik.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2kivwpkhy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gt2mgijfgcw.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffgzuzlb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gt2beloflfq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gt2yuruidjw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gt2ngdpkodb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umxcnuyj.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2ehztruno.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2bpruftfs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmztnnaq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gt2njbdfeaf.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gt2laxmvqwz.html


<!-- 参考信息 -->