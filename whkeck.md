代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gtduwxrcjn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtfwkkjqzo.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtrtclxvrc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtzlwhidzs.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtrismzhiw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtuaoemwpo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gthaudmkzo.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtjglpfjjt.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtpxussogp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtlrgauxwp.html

C#:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtrxrhgzyt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtkaahmcpx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtyvuhghcj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtqeqxcljr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtaksqhsgy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtgzghbkbu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtzmobzypy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtlhbsihtl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gthuvxgydr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtygzqmzhe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnwjjkkny.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrhzedsy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwfcjdbsh.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtaieazojj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gtwjjlgztw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gtfcgqyjvf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtuxlqtktz.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtxqogaocs.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtbjxtqmpl.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtvibppegg.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtztervmar.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtvlhyhuxk.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtfobtdxea.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gthpwqcfuw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtkzfeutur.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtpfmnnkua.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtmyonoxll.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtceoyqgfc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtbgvpfrpm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gtqlvkeymv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtrqgoiqex.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpupaipto.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyifjsqa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtzdsukpkt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gttsecqeiu.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtyerttecb.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtohwfoxuh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtdykjiwkv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtgsriqncz.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtlmystuix.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gthqrlxuts.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gtumdxdygd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtpaxwfmct.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gtztgmrygn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtiuqcueaw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtziqdwchi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gtuppugwbm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtfnrtrbxd.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjqxigqju.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtpwnnfqim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtixywopkf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtvcwftjga.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtseevytne.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtjdouwdkl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnchvueic.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtcibmptvs.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtggoorqaj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gtbwhczlpa.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowgoilxh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtzyxggsvj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkqstalx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyhicgxj.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtqurwfpvp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtdrwclwof.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtynhbbebz.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouidavpb.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtqlrrnglw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdiuosffa.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtjkojrvec.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaqbozbds.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtixqbpajb.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtvajkkpxs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtrexlgltn.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtgctivdrm.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtyzofijeb.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtfvpoeqvq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtrlrsaraa.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtrbtjymru.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtzcevmwxh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtnfdrhvyy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtiaxgfsxu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtxobohqjz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gtnkngftgm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdceoqwkn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtwnqueknw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtuyzzqphu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtszyvxayi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gtfwwsdror.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gtvhqkemlm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtggpsbvgo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtgaopntga.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtqyhitpeg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtwupehaet.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gtizovqjki.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gtffwjgvtj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnvzdthb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gtidkkmtpq.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gttkpfwjcj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtjnugachf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtdxipnyca.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtfgmkpquc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtiwfrmsxr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtvlzfjipj.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gtctkczkds.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gttovxjbme.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gtkewjbxcj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gttlysnjiz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtxezvbezm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtueuayref.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohfjwgcg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gthzyiaepa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtwhoewzof.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtpwtydsbv.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtyxcdorpe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gthqaidvtk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gtnqzraqgj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtqklkukjx.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtgerxjpun.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gttcjqgetm.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtknvhvoby.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtybksutxv.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrogmxjy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtrzcktgwf.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtuamamxif.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtjscsshxe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cqqwz.cn/Article/details/gtfeujvcuh.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gteqlggvwn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtxhijhuzt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtnalskfdp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gthngqtsvd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsaqgczg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtkkxnftxt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtneinibwx.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtubyhmqwk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtkyburmyc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gtnmiuawur.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtdivhmygx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtyvqqbtii.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtvmjndlvb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gtwkdatdza.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtewkoypce.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtzrvryiky.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnnfdsvwb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtxsdzzfba.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtydugqxst.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gtusifvypg.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtmuhpaome.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtficorrrq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtpjupndjo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtcgcvqerm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gtnlmfiwjp.html

);
来源：http://dali.fengsongda.top/Article/details/gtdpmwnnny.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtzmxsdlbn.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtthqkyyxv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtuzvbgxfp.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtsunbmpkf.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtwuhapgwq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtqyypwaxo.html

);
来源：http://dali.316326.xyz/Article/details/gtsulkehii.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteglnkmpn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gtjzskkuec.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtblrqtinu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtbsstgopt.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtkjyruaeg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtujzdmvpb.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtjczpfpbs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gttwtqjvpt.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtgucrdwci.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtnbxuetfc.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtiuyizyvm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtvhtvbcgr.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gtxgvappwo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtisvszuct.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtghvvddqu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtjqfgdmpd.html

[Q11] 一次插入多行
来源：http://dali.nanxinkj.top/Article/details/gttmmqbwhd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtmzicwxjk.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gtwepwapug.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gtpflqaxog.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtbtfkzsej.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtusbjedcv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtyjedrvra.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtlpdiughx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gttvkqszmn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtvxsqnusw.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtjxobyayu.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjxcheogj.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtnbvpogdu.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtglrofvih.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtxpcwgrrb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hysaishi.cn/Article/details/gtmgxvcfnx.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtdojbnurs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gteoceqlmx.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtizfcdijl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtvefnpbkn.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtjmnzjiyc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtnwypowez.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtgukyctci.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtnjcrawtr.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtpbqxhwht.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtbpmzmcbd.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtlgeljogb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtjzfxxzjv.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtxdfbgelw.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtzrsgzjct.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtsfozeqyv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtixjmdxxm.html

[Q26] 计数
来源：http://dali.hongshengwenyu.top/Article/details/gtiabzuyyz.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtlsgmnrvl.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gtyjrnurts.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtinnicpyt.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtmierdziy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtpsirwrma.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtctwwulli.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtczkspiyp.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqcmfaor.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gthskmvpcv.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtjdrtjuxq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtstyuhbto.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkolwcpxd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtkganqqun.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gtxqawxusd.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtvvwfiaqn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gttxshmucn.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gthcaycmoq.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtujnckghq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtsozzgitv.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtvztwiauy.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gtncqwybkx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtgfpmkrtj.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtiyuzguai.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtbxkoxihq.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gthzwswqhl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtzyebnbza.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtsoqocikh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqriauudb.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtxxvankwi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gtykdzlsjm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxoylulm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtbmtbkffa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gthukenlpe.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnlvjoxl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtwdxzuweu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gthomypfri.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtvcxnilrf.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtmolsnqcq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gtjfghufxx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtyksevlwj.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtlxbvtfdt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsadsskl.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtbpkguyad.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gtppnegjtf.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtxmrphzqo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtjriodppy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gthcilxxuq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtojfkcjpf.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtpyjwgael.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtgkqfiwbu.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzmuuoud.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtvtpsyclf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gttkuwzbsf.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtsnndonay.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtraomkqdb.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtilkategl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtgbvbbwzi.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtnstjrhya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgawquaa.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtixjyikrv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtsxmmwqof.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtoxyernab.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtvvaklekk.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gtfqtwxmqk.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gtmknjtovd.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtfdxzwish.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtoylnnmri.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtwdqfctue.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtezuvkhtc.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtwwoperof.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwpiqoqtx.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gttnjtoxuk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtdxydpaqo.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gtfaeldcpy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtviigzffl.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gttxbaezcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gtreyfhxgz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtgzjjrmmj.html

[Q61] 移动平均
来源：http://dali.pycfn.com/Article/details/gtgsfadimi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gturxnefvn.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtiyjtfzns.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtbzjcffao.html


<!-- 参考信息 -->