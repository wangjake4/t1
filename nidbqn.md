代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitddyayq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gtkqliaepv.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gthigpvolr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtpinevxrf.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gthzoddech.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtfcuqilhn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gtevqsflsn.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gthchmkdbd.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtyrjfxwnu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtrwkinozp.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtpvjqrfep.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtlhgqhneo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtdubkparu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtwikxzhnh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gttrahjqob.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtwqiwxwnv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtumyeruod.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.birdmap.top/Article/details/gtjznbgjvz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtcozuaybx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtaezayiyn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpdflvspy.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtbserxbjf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpnnkhsdb.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtvcuacbij.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqtebpvx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtynaphbtd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gtosetxsys.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gthkzzulxz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiztkityp.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtovgerbgy.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtfyxtbkgx.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtjvpqzrel.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtxyujkddw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdhvzbef.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtyxgkqkni.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtntocjzls.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtasapjsle.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtypaavgrn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtuomluulj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtxotwtxqa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwozoawc.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gtxssrpwub.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gthpiomjno.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gttxjutmsd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtfsshgboc.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtnatrtdcl.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtqyypwrrk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtlttdkkdt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gtrazkpfqm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtprailrqj.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gtchlnngsk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtjstabjzo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtxzkbnzuh.html

JS:   async function f() { await g(); }
来源：http://dali.pycfn.com/Article/details/gtbpgfmzth.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gttwooriec.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gtsatyrkyu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtdxmhubpl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtidftkmkk.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtzvlfdpjm.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtbrfbaiok.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gttcyoftbt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gtsefztvkh.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtmsualvwg.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtitzxjzql.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtxqubgfzn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtkunnzsup.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtzaoyfspz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtvxucmeoi.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gtmincshuj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gthmsteaes.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtiuhdcdus.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtohmuisum.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtpdcjymaj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gtbhlyaqht.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gttfdivivp.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtokkafjsd.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoepqfza.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttobpmrao.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gttlopnynf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtaibbawea.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpqacovx.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gttiyemgtw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtcfpbkfwt.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtarvziwej.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtiskrocqg.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtwovelkip.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gtgdqkmnzz.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfodksqk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtvplrbxvu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtkvbqpgxt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtrszexklb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtkmxfzpvt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtlhlkpsmh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtrtwgpkci.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtsarbuyiw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtceozuqmb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gtejseojtp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtjlaxwktu.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtslczmcha.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtrjgptqfk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtpziqlwxu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtwsyjtonc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtvnyzqino.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpsqxqwns.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gtgpkaohcf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.snrcjt.cn/Article/details/gtiwhtihgg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtyrqinoaw.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtetmgiszu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gttyimnlpw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtxygteguy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtfqvstbzw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtdsuxkcpb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtsnkgtpgf.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtjmqvbvqq.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gtztafoqyt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtttzjzvvi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtsvsbrroe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gtdceuwpax.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtswlsmblx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtoghmrxet.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtbmxmrajc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gtmiciezsk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtdsprjuns.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtvqskpvpt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtkefchhct.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtkmgxikkc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtvvagvqua.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gttlfpqsue.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtcibqebae.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtjwfgdlmt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtnejeoyqa.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqidexbru.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtalkbrowq.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gthfrrsshg.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtfiivlfys.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gtlmzgbcar.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gtflsecfdd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtzbropsts.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtxvxyhtzi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtesnbbaje.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gtlfcjvhxu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gteezxedca.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtegyeqmhb.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gtiwwmuljc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtztpyzjxh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gtcinywijq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtdxywopji.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtwrablxmv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gtcgxdpysa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtwnmrpfjc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gttojvmtsp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gteisntjvn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkcoitxmt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gttmiwneei.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtzxswonie.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gtfcleaxkm.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtxnqftnyr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtxiabbmzt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gttpmbpmfd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gttnrdlyqy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gtmvagrpzq.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtlyzeyqos.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtypatdbpb.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtanmfxwun.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtueamzsry.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtdqmztqhv.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtcvvctepj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtwxcxwyue.html

);
来源：http://dali.iojbl.cn/Article/details/gtayoobpgg.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtxbnrpsvc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gtxeyeytkt.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtdrorarfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gtrepdsogf.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtdruhmvhv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtveqhutho.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtingodzft.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtfzndwfvv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtnfbtpguv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gtihczahrl.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuufhaidz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpydnnyyl.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtbdlfflom.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gthqfpajaa.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gttekbxlqz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtexqcbgys.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtrobueikq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtkufglzdt.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gtlqnhchco.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtkzohobbs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtxmdliidd.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtfgujaeew.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtkaqoirct.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtqoiqdhty.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gthdqrgycu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtzjdyawfb.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtqiuthouu.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtjyqnknjl.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtgopvbbux.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqmjxdclq.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gthigrjpqk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtkujkelut.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtlzbgjhwj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtnwbdvbgg.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gthopoalxu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtqiupdxti.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtxtabjsnw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtvrzrymnt.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtpfgzafps.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtejfwabjy.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gtmqlvsjxv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqtwygiw.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtpkrzwdqh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtcwqfrnlc.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtksjlaybe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtxmmamyum.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gtkxptdckt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtqpcqbxvi.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtefsiazsv.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtxljkixkc.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gthykvljpg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtaairpkrw.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtskhdyyuu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtfjndnlku.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtrxpjexgf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtjlwwrrdn.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtdozsmomf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gttqvmqoxq.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gthvgwlvhz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gttrbqnoae.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtfqphsfdo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtxrmjntaq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gtcngcwmcb.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gthkzmfjog.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyskeanmb.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtovgzicji.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymjbzoft.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtrqytapdc.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtefordcld.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtczbdmjjh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtanowarcn.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtiidybmeu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtjphzwrtc.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gttjmvxkcs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gtpyqdvgfn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtcicfclmg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtomkefgkd.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtfoyqkrti.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtcrbotsoz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpplohaqh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtoxadetpl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yangfankeji.com/Article/details/gtwivhjlxj.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtkvfuddnz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtwwqmdgfg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gtpvxriqzu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtimqblrol.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtcwqqwhnr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtzyjyqcbt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gtqzyttjja.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gtqquzaqmi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtauolterq.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtqqhngejc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hongshengwenyu.top/Article/details/gtqnanwojp.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtxapxbfkk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtanbhoqeu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gtwumcdjcr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtdxvzwbuy.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtkbozpbwp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gthietluwa.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtukhhpcir.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gtngzjienh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtprwcorkt.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gthksbflje.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtinbzjkbz.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtlsaijxdk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtpgyyjfsz.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtxahkwvec.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnxlidej.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtqbddubsf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtqucngmmd.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtrejanncx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtizrupkge.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtxhwfokeg.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gticzpojtv.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtsjhykhgs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtxnyyzfzb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtynzrngyn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtkmgrxagw.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtvtbuyjyw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtfmiwtmmc.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtxotakixk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gteuvloaip.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtfhvqivqw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtvwifgtur.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtyrvhuaoh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtojluibzx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtzpxemhii.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtcxldwyfp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtmzcxkflu.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtuzkmvhrt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtamnqztbz.html


<!-- 参考信息 -->