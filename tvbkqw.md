代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtzmxjuapj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtzlqlxiow.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywmcoria.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmgoiohd.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtvtxrlokv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtzrzekwsx.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtuiyrjvxy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtrgtnlpdh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtmgjurkha.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gtkghygcmx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gteqbzvpjs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtuiistyvt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtaqjdpkxg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gtkzqbovqu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtsgpwuoia.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtzgtujxql.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnpnnioth.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtqmxhytzs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzigpjilb.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtgfekikza.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtlbixgtta.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtuobpwsyb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtfdlvvzst.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtkauyeiuj.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsmxomkn.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtwogcqnaa.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtwvfmhgun.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtlhdljrth.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtiizpdakn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtiirgjiep.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtbnumpfdm.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtrbrhzpac.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtwegbcpvb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtyrqeajhv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtzxgegctp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtzxjqhudr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtfonkunke.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gtxrwfldwc.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtyscfshdd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtypwwjejz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtfpdsmvbo.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gthcirixfo.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtczorkduz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtugskedok.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gtdwnxbwoj.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtrmjwgjyr.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtgymbnguu.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtinttdjsg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gtwdpwgiei.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtmfwsxfpz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtqgskjokz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtwfxtxzrn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtehhgcodt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gtnzlqjezi.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gteusyounq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtyhbpkcui.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gthgzlwdys.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtdgjpcpvf.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtsgkujgoh.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtphngppig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtjbhezylq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtrzahorrp.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtdxtftzwh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtiwbpvgut.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtsoozfwtb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gtjdglnvjo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtdzwsyefe.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtyrqyhtxj.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayaxhacm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtoniobgny.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtaytgzeku.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtozxitknh.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtcwfbhcmj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxdypfeya.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gthvukwchv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxmhdyeti.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtrgnvstwe.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtvlmdxric.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtuntwoefk.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gttgljtlov.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gttozylnhe.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtvyhrcbua.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsovsxhqi.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtjiwpmorg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtkrdmnwsw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtvdfydnpe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtlzakujzl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtomvlasgu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqemtnheb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtifmvbmwu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtsvanyove.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gtyfqhnqcc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtiqsoacej.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtteuskazq.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtegaqhtsg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gtuhjbnmih.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gttozqhxjl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtihaelcee.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtbjvhqubv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlbkadtg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtpwhgfyjc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtmkszigtj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtlvtrlfcf.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtemyowqgz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtswszvwtg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtviodsfdj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtqfsmgsoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtdofxxoqt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtvsevgmfw.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gtzagttbsu.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gtjxglvcdj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtzivxbktd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtrvxutucr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtkytuleyh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gtphkhhwvu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtljjybadg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtbhttlrzi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtuphvvxsg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtfteumyfi.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtcwbizryf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtfwrnkbrq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtagantqeq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtsgoyxmit.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtqrhcthet.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvcvhvpl.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtnnpqjzbr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtxmrusbtv.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtzroyuvyn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtapmpkzcs.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtzktqxijd.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gtydkdizav.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtuxfjupks.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtasexkjpl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtzuspexwv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtngqdtnnj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtcajzypgf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtcvuhmdjq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtbmjblomt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gthsweibuv.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtudbtziyt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtjdielcin.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtgrpoddey.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtrbdepnaw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvadwvegl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtoctgyjiy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gthqfcelea.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gtypeororf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtqmbhpokh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtiawuvbhd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtngptkbom.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcwstzav.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtvidlbdem.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtdvdbpsvt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtmqfxiqlb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gttcvxxtki.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtqccvnwvt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtgolpedpf.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtygnllffr.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtdlycjdaw.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtyltdoprm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtpfujugnr.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtddhpngyj.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtxeidvrog.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtmktxayjt.html

);
来源：http://dali.ybcxt.top/Article/details/gtuqkqadsx.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtkcuejngj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gtmdkbrbqf.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtokhrarej.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtaxeajzut.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtapnxkocv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtviirfjaa.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gtgbjindkz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtlkfrospe.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gtfyjuakie.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtwrivguph.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gtxgjkfxcu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtrksbhsnn.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvebvvsx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtxisxsrla.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtwgsqgxbd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtzqjebdwr.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtbxgjkrdd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtbsymqife.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtmilasxjy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtnezctzcx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gtoyjfclcr.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtlnmgntah.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gthicfjznk.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtyuynymkr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhycjuqo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gthpdnolpo.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gtspctlgvz.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtdadpujeb.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gttkwxnlzo.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtgycgmveo.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtjyuyjaqw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtvicjvgyt.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gttqxlxfjb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gtyyoibode.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtdmbrciyy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtblueosky.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtndtroiph.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gtqyhkwuve.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtzmwuesqp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gtreyrfujd.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtiuezyaqg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtulojmutd.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtvixmbmdm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtiogcfahs.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtjcdlejyq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtcippoolr.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gtvaiejgub.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtwomctutf.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtdvpmhhfc.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtirrnrsis.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtximaqsze.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gttelbcahm.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtygfvmttl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtwvrmfqas.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gtrrxjxuqf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtnxkmnazh.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gtplsbexpb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtcdrdkygm.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gtubnctcac.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtyjmdcgng.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtczsuxgch.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnfekwey.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtohqbmesu.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gttoessrhb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtreopmbnf.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtzopbekmt.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtatcnpzwd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gticvwdihf.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtlowxnbgb.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtvyqfmgoi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtacykcjhd.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtsgunqvmz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtmlcbfuyj.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtuurrbvbe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtfmwoobzq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnjsiwbe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtilwjlgri.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtkqpdgkte.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtjsjgplel.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtbptefrsb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtbecjwdyv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtfkfpnrpg.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtxumuoilb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gtfpqfaidj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtrmrgbfbb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtcwahbpgi.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gtwxpbqnua.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gtljtneriz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtjjfhndsh.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtpuqdcbpp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtlxlnwdey.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtilyrccno.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtknrjykab.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtlglfgasr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gthevskwth.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtbqqfiihg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtovakexgy.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtjagaejru.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gtxyozjhqd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukuxsrek.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gtprzzvcbp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtlacqkskz.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gttkuffmqf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtwrnlaixs.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gttqyzhbnv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtilxlgeti.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtvzaeacnm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtdywsaedb.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtelqsbqkf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtrrposbxx.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtmlyffsih.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtgaoxzthv.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gtrachdagv.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gtbkjtcqig.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtqxfzdtkf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtchuubwwf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtmnafznbu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtslijrzmu.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtitofxrfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtcphavwov.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtjywrrpla.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gteyugbvlb.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtkcsdckmf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtjulzdfaa.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtmkiifpxu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtevyawhyc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtzjkkhzrb.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gttmfhkpwx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtvosrnuyo.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtjjgutlnv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtfnnshmuk.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtydcrhuwn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtldqjsfia.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtcpiyqxij.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gtnkdkgkhm.html


<!-- 参考信息 -->