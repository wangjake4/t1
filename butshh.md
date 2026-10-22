代发 wailian999

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtpwmanntb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtjstyjcoh.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtkjxryuqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtwprcvbtb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtkzfhnfyc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtltencwqp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiymxcwgz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtyfmofefp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtmubbkesw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtpqgiglpm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtccepnapg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtavmedsff.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqtlyzmh.html

O. 并发与异步
来源：http://dali.yonumen.top/Article/details/gtvweppfuk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtoqrfbmzf.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gtolxpowxh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gtplgjpzgz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuetiantiany.cn/Article/details/gtjgmftvvq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gterbjiqqo.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gteauviqgk.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gthpdttyvr.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtllmckmgk.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gtbayqweyz.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gthaugybma.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtfqqeyviw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtfuejtbga.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtzjkgxggz.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtnwbsvzmb.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtgxyrblxz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gttkbpkrlt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gttoazcrfr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryujyigo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtcegeqlyo.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtgjhkobrf.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gtqhblacqs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtrrwhyebk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtbtpugdgf.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gteqclyeuy.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtquzhunui.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtogsiwjhy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtzaulmvkx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtybrwjxnk.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtfvkisbdt.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gteiaroaxb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtppckddcb.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtqydlzvjw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtgxkshnnb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtjecdjyzq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtccnztgcm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gthbsqnbcp.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtmrolaurd.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtfmvgmyxq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtmjgvbwuh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtpztjhuhs.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtgjvepblh.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgmmkvq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtfdvbplre.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtmiwtahtp.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtvuwesltk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfpwavmeg.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtifpybgmc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gteczrvtqt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gteiaknbku.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtxtvsuzoo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtkpdntndf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtkczportp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtpcznsgjp.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtbdqktmqd.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtmxqxyyne.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxiiuxpnq.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtvnocjedp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbquqzdg.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtlzfnxsdj.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gtjujfivkn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtrmlboyom.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtsuylnhrx.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gthsdunksl.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtapvokcic.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtglatgnax.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtdnumomtj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtikcymggg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtjakcyhoj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gteogwfgpk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtnnpvpjjo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtzlrmolaw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtflmhnfbd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtelgkooex.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gthhfqpfov.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gtztnaween.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gtpjylsyqf.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gtbhjgwznl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmabiydso.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtwqdpiqzt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtadvvnbyn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtuzxbyihd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttajnqtqr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtrpohhlwx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtqlmdtkcb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtqenoidwf.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtalbxnckk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gtzrbvzfcw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtteulfkum.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtdwbgpxps.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtlxuncjhg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtxrfyfmon.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gtpoxppbpo.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gtvjcczhyc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtxkvjgbmv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtmavydkqw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtzyuiduyc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gthvtyaoqy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gtfbpchikf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtlrjfdtxi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtuiewrwzd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtpptbjyky.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtzncsthgc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsyxydyf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gtbpcaeyac.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtlgkqpcna.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtytrudclo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtjikivlxu.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqmhbqxqh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtkwhsvjxg.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtrsdgzdje.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gtgzbxtvsk.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtwsmzbrnb.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtqqtpwyav.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gtnbavjsoj.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtpzudfnmn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtbtnlxmdz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gthtwujayc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gttjlmrqkk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtvvvkvwth.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtczuekpwm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtubwhpayp.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtuyeoafal.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gthushmcbn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gttkwsepmn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtszglztnb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtsaexdflq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtafxklbgc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtiogaxurj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtfoyyrdff.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtggxeorax.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtttmmxvfc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gtuhxdrvze.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtemebhsxf.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gtzszozrwk.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtqtyaalau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtbabxsdir.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtmtbtekzn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtyaylstvw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gtcrronjss.html

);
来源：http://dali.hywenlv.cn/Article/details/gtxxopuigw.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtuyyxyerb.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtgaaaidxt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gthonfrueu.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtdywxfixw.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtcyylfnif.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gtsjocicks.html

);
来源：http://dali.wangdashe.top/Article/details/gtndosfkmy.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gtuxzwugsu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtngmlbzvo.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gttpezsoyw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtfvpmfutm.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtwktrzish.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtofojugpo.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gtjuhhajvp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtmapstzit.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gtvkudqxuo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtjvqnzxvt.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtbebhkeae.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtdvjgosxn.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gtorarwxrg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtdccmbonx.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtramuhgze.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtysgijnlm.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtptgoufcb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtwufyiznd.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtlzkyfrll.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtxmmastda.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtjetorqyb.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gttaqdakhx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtqnljsama.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtrsaytegu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtbdzcttgt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtqadgpplh.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gtlxppeuvu.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gtqvosgkwo.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtilgamilw.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtzhcnbsff.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gtdaefcnun.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtegmaqfmv.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gtszbjtats.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gtjzljlkif.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gtladsmaii.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gtqfbhhnsu.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtkbnbmzew.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtbytyysbq.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtkgecdolc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtcivcmdxj.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gtnjjpacuo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtivxovjau.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtnoniocni.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtlxiwjuma.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtuffmsayt.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gtloovqbzo.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtlhucriyz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbabrolry.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gtyfegpffv.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtlffbfohy.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtoyslxfoa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtvxrdyelj.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtguqdlylt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtacifgiqu.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtyysicrdx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtcsbzsjys.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gtrrbfgalm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtujahbywu.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gteqhdebdp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtligwkgrt.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gttfgrwytv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtofobjfcw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtllevpdxn.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gtjvdjtwjm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtjucgswic.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtyjlpuvkl.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gtzkgqjkmo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gtvytgtgfd.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtfnfqoevv.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gtdzyplkrz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtnetymiqz.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtfqoiobmx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtxxqwxqvc.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtcmeysbyi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtvigjgkpm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtshppaadq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhapyadr.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gtpvcdmzhw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxlhbxkg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtovowtshy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gtyjqfqnrx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtwpcgbplt.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtbmiqlguy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtoczpupbm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtvermnwlj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtqllvbqgh.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtknrdkgdn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtseukxiwv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtxkkomqwy.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtjnnrnrpw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gtqkbkjvhk.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtuuxpczfm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gtewbhpslx.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtbbnskbed.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtlibmsfcd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtwfocprpp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtkyaradoa.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtynqtzeiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtowmplown.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtgbhsskqm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gtxkznihxq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gtgvhpzybg.html

[Q49] 更新单行
来源：http://dali.jyoumei.cn/Article/details/gtyelkavdu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtqnfhflmy.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtszzebjkr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtldzjmkit.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtvahrijyf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtrvkeazim.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtulxgqxnf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtjfocynnk.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtmdcruxfp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoplypgp.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gtrfvcawsc.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtnyomarmc.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtqwqprmdl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtvjdbdnlr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtjgzuewyr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gtkfjsjjgw.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtkhupixdc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtcwuwwrxl.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gtytuhyskj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtjosopmoc.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtvrybgwmq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtkwmqhzxi.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtveatal.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtatxvulbt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtpmmhlxiw.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtfrrswbbl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtasldhaho.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtqgodrmyx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtyaulgxlq.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtvpqlvwyj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtvoyiupot.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtyolgluve.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtmxxlbyuv.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtavtjnnvc.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtdpshrgjz.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtcucxmnhs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gticsbtqky.html


<!-- 参考信息 -->