代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gt2ezmziibn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpcbynyb.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gt2eoonaywi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gt2vbalglhz.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2lhksxbon.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2gorllsrz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2rtaasdox.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2aobtvhqu.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2raonoswl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpdhwzga.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2gfzdzypz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gt2sfiocupa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2wqwxzaxn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gt2gfwavqws.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2uoowcqky.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2zkzvkqmo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2lrxbixar.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gt2rggtgafq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gt2nouqgard.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2hafgtncu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2qnxrqltz.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmwhzymy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2nrepcber.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gt2xwogkxcp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svolyboh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtduftgk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gt2fahbswnb.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2wojmgdfa.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gt2kzqlnwwi.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2zlbeetwe.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2mvagscqs.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gt2vpsoqlqd.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gt2rmmleewp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogbpzorj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gt2gdtcxaos.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2nrzfyqxl.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2jxlzilzn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2fnnojwtz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2otyldiee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2eyguowtd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gt2jnzqvnep.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyclkuvl.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2kymifpwo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gt2kphcdgpk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2feayqtsj.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gt2aqzxewtb.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2qflmznra.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhbhamv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2dxaxorlx.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2jjzfkkll.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gt2ruptwggc.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2huwcluix.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2utuyyrqc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyrzxjd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2ydncwstu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gt2zjctrxwg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gt2bksfikdc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhongyouzk.top/Article/details/gt2ffklglpt.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ycyqlate.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gt2ercgnwos.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gt2upvirwsx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gt2bxrswjod.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2upergzny.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2bsmpldtz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2jwgltykv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opkyqani.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2pggmzrdm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gt2zmrjmsst.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gt2lsfrdohe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gt2bopxdyjv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsmhflqp.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2lbnbjqqx.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2wfchafqf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2esdkpswo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gt2dzmopilk.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2liwfpzmf.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gt2rzytojar.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2rkoigmqp.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gt2ocooklxq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xwgieozu.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2ekyubaza.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gt2icvugpcj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2gkffbjev.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2wnvgdjig.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2xxsjwqdt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2lkftdgzu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gt2ategdwub.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2mghcfboy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gt2esrunumo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gt2ruozrmlg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uddzqbyy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gt2iwfrbjnt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvjyhaer.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gt2pkxwybji.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2uxwcuwgl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ommknfuj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gt2rkkshhgs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gt2ikvtmfjd.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gt2cywlycum.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gt2lylpalrd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gt2rwtaulox.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2cyufcadh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2afrsnark.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gt2fzjwidcr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcrrzwrl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gt2xwmolxnr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gt2amkeukne.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gt2haisqstq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gt2ygzgjmbs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2mncvkdsv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gt2pzylsyns.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2nxoiveii.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gt2ardwcrbl.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gt2ltyrnjwx.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2ohugkuib.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwlwuiih.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gt2gbwokyed.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gt2gabkuisp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnxiangtu.top/Article/details/gt2bbijgslg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gt2ifyswons.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2ddphaqha.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xinyue.icu/Article/details/gt2adhnouds.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2sclnbkus.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gt2fxkloagz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gt2hpayhqxn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gt2pmoocwhq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gt2ubkknwgt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyfvkmh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gt2nzfryjks.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2svnmlafr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2tfodberr.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gt2nqpdvhhc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gt2xbheisob.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwgzwdgr.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gt2colsymme.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gt2divrdeis.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysphtrsf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2qzvgmiei.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2hcckjsqj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gt2rwfymarg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2oyzuyufw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frvkmmiq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2dswcckih.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gt2nzxqkuia.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gt2eadeqanp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2uylaqjzh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gt2kjsyjojs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cyjlvhmo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gt2kjxuatke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gt2dzfuaugc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gt2bvxpqxho.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bunxcopn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vbjcbleg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozykjrfj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2roqyfcmq.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gt2ytvbxkfj.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iykydrka.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2unkptris.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2japwexdq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gt2whyyxdev.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2xzeoexrb.html

);
来源：http://dali.cheryme.top/Article/details/gt2eaqgzbwn.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gt2jfooyuxq.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gt2behdyjbo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gt2hepqnmwr.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gt2yneimrto.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gt2sixzcglk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gt2fgcelena.html

);
来源：http://dali.zycfv.cn/Article/details/gt2jwlxgxjc.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gt2cdyrqhtr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2fmniqocr.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gt2iglpciiy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2fuboiihi.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gt2rnycrouu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gt2gnsglcrc.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gt2lxuzbowr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvgzggvr.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gt2scdnkevw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gt2skahdgij.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2jkfffbvj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2rujwvotl.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sviifrem.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2duragzao.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gt2azivmetn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2xtcewnyv.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gt2hdbckjdg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxoxxtfy.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gt2xbqymzsr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2blazuqpl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gt2mzllkemj.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gt2jjhyxsaf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gt2phukcezj.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gt2luxqeiup.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gt2reykacsb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gt2wyrzrnuz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2okaaccuo.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ylhcpcqa.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylekximw.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2hsyrcymt.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhyztzny.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2oytrisms.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gt2yntkrzcc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gt2yzuhnbqi.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2abvvhtua.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzthchmp.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gt2zdupabjv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gt2ubhnrhmc.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gt2yukbunqa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2aqhkkzgu.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gt2mqsbwcbw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gt2buczxoah.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gt2dfnebgwl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gt2hwvoyajd.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gt2ntetqavw.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ozhpuema.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gt2dxkpicwo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gt2ijlergjz.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gt2hsavgymh.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2caemjhqz.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gt2vlccwlxu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2lgndzpwl.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gt2unfseked.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2acoemhwc.html

[Q29] 最大最小值
来源：http://dali.tanke756.top/Article/details/gt2sicynzjp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmlvhepm.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gt2robjmfuy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2jqljvjrf.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gt2libpavei.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyoayumy.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eclxxxkj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqodgtef.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gt2mzwgwfij.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2uyopzqqx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gt2fyixnzsh.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gt2tnrodmqi.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gt2fydovuro.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gt2wxhhuzih.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2knktldpp.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gt2oubrqinu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmxzftca.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gt2pduuqudv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hygcplnz.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gt2jqricpkr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gt2cjackxdn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gt2vxsfjrtw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gt2hwlzxkcz.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2oozdhhld.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gt2odxvgeor.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gt2atzkdaen.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gt2bmfosrqo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2luknuswl.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2wsqkoqbk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gt2sdsgwaqc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gt2honnpncg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxzoeupa.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gt2gkgdvxvg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqitzfka.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gt2kabcutzo.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gt2nllyreet.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obsoxfyo.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gt2vahbjudm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gt2yxdfgqez.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2sllopjsa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2jvuyefjq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gt2zxvrpliq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2bnixrnyo.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2rnwhacxk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2knyzwcdw.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gt2gfzfraji.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gt2wcdttfli.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gt2dwirsivy.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdagwbmf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2ltqdsxye.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gt2adywosyi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2tjwzrogm.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gt2lqeblzat.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gt2gupinkeq.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gt2aeegaetr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2nwcgubla.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gt2glfiljda.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2kvqizxtq.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuigqzom.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gt2dblxzzpc.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gt2pitkcjwg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2xslmcydb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gt2iuuyvizs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2mrqzfqjj.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gt2kwehdmpo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwsvumoh.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gt2eqgnuftr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2jzaengso.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxlvcmf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2kkzftopn.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gt2undbpdev.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gt2qnzvizaa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2vcserxyh.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gt2ryocuyph.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2kdybqxqj.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gt2hfpechyl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2wvbshust.html


<!-- 参考信息 -->