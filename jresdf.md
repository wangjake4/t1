代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gt2ujxslwxt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2mvpualtn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcinwslo.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gt2llorutfn.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2udldeawc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gt2ybfvalmx.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2weutzoyi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gt2dfsdnicj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2baujcyps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gt2dbaqrjoj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2omjgvsqr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwwrxzez.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2jrawgxur.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svjdzrpw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gt2iupsubva.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2kycxgrtt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2forqrneg.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gt2gxzwlbtj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyqllelg.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gt2pqufakik.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvjujytg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2mbpzccod.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gt2lbfunill.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhnoxxgn.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gt2kzdflers.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gt2lfsabapg.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gt2uygulrpf.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gt2sgvbtvhe.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gt2xljwvinx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gt2froqeiih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzlqapgb.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2ixqnupsf.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2luvywsse.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvkakkor.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gt2rnqespbt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gt2lxjjluhj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vzonczkb.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2defslnuf.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gt2pafexsxv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyluavyx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mazhjfkx.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2bjwhednf.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gt2btraowha.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gt2hcpqvaze.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gt2lslknfnc.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2yncesdny.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gt2kjarjmia.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gt2pvwjsftv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gt2ildyeqlx.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2fbqphcmd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2ickxitym.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2rvlwhwlm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gt2xnbpmnum.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gt2aqfcbvou.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aixigfbl.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gt2comekvfm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2pzldrhtb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gt2ejpgsccu.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2lusnboud.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2ompivnmh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxjphecd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gt2cmthigli.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2thkekkcc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcnosgas.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gt2ogmhlzfh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ectojoka.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gt2vxbstlma.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dialmoar.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2chkeipky.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqvoraul.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2jczhcxnb.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gt2hrxcyjhc.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2rztyedqj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2wikisyue.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfpbaohc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwoyszot.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2cvsqglyn.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2iqgkhhlz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2obhmkhsx.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdsvdwmz.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywerivjb.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2rqxbnvok.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2gzmwicmn.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gt2tkmrisfz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2fkbvftdx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gt2xtyxejcr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gt2skyynxwc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gt2cowqdxza.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2vqsmfipj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gt2cisfxcqo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2olppmrvg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gt2cbtqhtnd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gt2lqiobqpn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gt2idhiflgw.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2nfsmhjwt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gt2vqjpehmf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gt2eyrqdjkp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gt2stgagjha.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2qofqczry.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtbewyer.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gt2ivyrorbr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gt2fyxayrri.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gt2qlyosevj.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2ytdhgcti.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwglofon.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2rcuiayyu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2gzimuuad.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2klacrgyo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2udgplmlu.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gt2prfyqulj.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gt2httycrxi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2yclvvxme.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gt2cajbhayg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjqqvoog.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gt2ghfjcogf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gt2urlgniav.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2wnsnqbkq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gt2zdifxbzd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2cpsjaama.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gt2lemidonh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gt2zpwqkvvs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkvvglsr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gt2kulkkdyy.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2nlybjzsa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gt2jewucnch.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2nfmumhmm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gt2cfolweqk.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dqclareb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gt2zwhoabba.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2puxtgwcc.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gt2khdhuspg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gt2vosbtzdx.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gt2krrarsdz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2ayzefbjd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2itujdvnh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ifanptio.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gt2jqrxetdp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gt2oijdbjoy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2svstwhqz.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gt2ixtxqexy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhpeaso.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2arkakgla.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gt2rcqardvn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gt2nctvsgxt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gt2epoczyth.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gt2mcoauncq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gt2gfscigha.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpbpiweb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zejsasku.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gt2eajezxwg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2eriwpemt.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gt2srsstdbw.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gt2tyzjqpii.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idrxnzcv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2jkowbejy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gt2mufhgbkk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gt2qilagrgv.html

);
来源：http://dali.tian-w.cn/Article/details/gt2nckefwqb.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2nyosrowx.html

CREATE TABLE orders (
来源：http://dali.cqqwz.cn/Article/details/gt2qsdkurmh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rltxgklc.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2empcxbch.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gt2vtypvfqh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gt2qzzaeqcl.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnmjyumi.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2jzgacojc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2qwjxheqi.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gt2minmorph.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gt2uzofifpx.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gt2fedxvukf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2mgdadjyu.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2srybukaz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gt2nhtlcewh.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gt2onswizdc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gt2cdfcyymh.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gt2bumflubg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2hggwdadc.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2xdfgepzm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2qdkgryie.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gt2bvjwzfhj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2bnmpqqgq.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gt2atwaawko.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gt2ujvlgjle.html

[Q12] 插入后取自增 ID
来源：http://dali.gzhubu.top/Article/details/gt2hapznlpb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gt2idndojql.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gt2ppcvyzmq.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gt2ffphzzrj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zskcsyqx.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2dkbfnzur.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjqpugl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gt2eieuegms.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gt2qzwhfeaf.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2zivsehps.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2cfsgbnmu.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2kzrtsjxs.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gt2idpkdayx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2vpvherxe.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsqqselk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohxdcpql.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gt2xmlhlnux.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gt2eyupbqpm.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gt2migycvld.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2urwvpnzl.html

[Q21] 空值判断
来源：http://dali.ehwqpu.com/Article/details/gt2ojddkppr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gt2cmuwemyn.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gt2itidbdhy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gt2mgdjxxre.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2vtivcirf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gt2hidcazkn.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gt2iqvtpafq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2gmckuvmn.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2qscoykwy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gt2nlkifjwo.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gt2zzwvhdlc.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2ynbpmcvc.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gt2gvtbfoee.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2cotrpzpm.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrbphsiy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2nsnceeei.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2xkewowhl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2ejeqessi.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gt2olilqusn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2efoflavr.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2zrqqtyzb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2craqkxtb.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2uaibdehi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2ykzrgfkw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2fvfceigr.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gt2hiocdojq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2bjkezxhq.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gt2mfnbzmbl.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gt2lcpygojy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gt2xyezwizu.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enxajhdj.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gt2wedlmvxj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2iqkppwib.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gt2xmxxuhcl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2pggqknxx.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2egyllcbn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2vbsuktgv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gt2kvanrxva.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2npxacufk.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2dgcdalpu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gt2dudgzahh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gt2ngnthrrr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gt2ipovynqf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gt2yztaeyin.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2zjpiteyx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gt2gtwcnsgl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2izqdbxzl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gt2zovklmzj.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gt2sithkspg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gt2rgdjloho.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isaxcfsj.html

[Q43] 标量子查询
来源：http://dali.jqgufenzy.top/Article/details/gt2yudlhxko.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gt2hluinqqt.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2rfeuysbd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2qssoyyxk.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gt2iofltczx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gt2ddforvtb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqamtfal.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2bankcuja.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gt2kzcznktp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gt2nxsiddwj.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gt2helpxiyh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gt2zzwqsphw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gt2tolqtrmp.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwxtqbpk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2tvdukwes.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gt2sivvxacl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2nuucpdhj.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjmjiesa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2shhykapq.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvvdtyya.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2vgmbbnsn.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2hrkccdhz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2olzfjegp.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2obgnlcvp.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gt2pgglgqpp.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myhkasxe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2yglngxyr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gt2pnztnydw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sweek.top/Article/details/gt2cxybscjs.html

[Q57] 行号
来源：http://dali.jqgufenzy.top/Article/details/gt2khlnkcut.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2rmqoanwm.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gt2hdfdhtfy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2ybvhfzdz.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gt2sfyshayl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2vlyybosj.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2vpsudisz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gt2fepmodjw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2xpquwvbm.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gt2zlomymax.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2adnydqwz.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gt2wtindskw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2kdvzdtge.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gt2lpdokoeu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gt2klsuzfjr.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gt2duxsrgjw.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gt2uihspazt.html


<!-- 参考信息 -->