代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gt2gidqttkz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gt2xzgfnuov.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gt2poeyhxvn.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2tfmzviyk.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2rfhkuboz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gt2gieupjes.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2mqkubdag.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gt2sbjurnoo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gt2fruragda.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gt2xfdnljvq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2nztyepin.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2yqamibdv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2szeufbyw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gt2optgmguw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rekubqvi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2vjulcvpp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2iztepbzh.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gt2cbyhewhj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycbregve.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gt2tbkwzgej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gt2iuluxvdy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gt2perrxkwo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gt2bhtneqro.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2nfvfkuld.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxfmykfh.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwwrkahx.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2absmxqem.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gt2aubuygyo.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gt2waftuymp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gt2mhewxmtl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gt2xdqusyht.html

JS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2realezed.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gt2xkgypszj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gt2oxauxbuy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gt2tjghiyhj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2jzbmbejh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gt2qgcvcsct.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auvuobxz.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gt2qnkottgo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gt2vprypjyw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gt2amglfqdg.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2wbkmswrd.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gt2pvyhiayh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kppeuetm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gt2usatudms.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2iilgbrqa.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gt2vwsouzxf.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2ecaziqlt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awzemtgr.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2xmzefjrc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2hckojvax.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gt2xmtuyxfn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gt2aujyvklt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gt2zpnqlces.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2eeisgreg.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gt2txqmwowx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2aqundcpf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gt2vgvsmcmq.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2ukqfjyyn.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihglfqzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2oljtfysv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2aynpgnam.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gt2hcgfpgya.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gt2fdtnpobn.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbhqskeg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gt2mljqymqe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gt2aeoslatd.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2iyyodjrr.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2wodiusrp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjonxjss.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2bfbsjrbp.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gt2itnsejof.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gt2meaxermf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2wbmbkany.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gt2fbuungkx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fltlqinl.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gt2jiqdzlmk.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2wuhonudh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gt2ocueuwvb.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2taiamhyh.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2uttfkxqf.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2wbefoqjv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2fakveppz.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gt2eihvqcwx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2tzgashfn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gt2sjlsojaf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gt2nfspploa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gt2rvoxduch.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdjunpjw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2cnxwbbfl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2zytkubpq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gt2olszlstx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daxiang520.top/Article/details/gt2ecrqozsx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2pdeqnmxh.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2ljjwlfze.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gt2yavdmozd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gt2omjodzun.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxwrkymg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2xthrqvjx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2vvascbwg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gt2yeumihgx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gt2dudnfrrp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gt2gngcxprp.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gt2pdekytqa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2ysejogoq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2wykvqjiy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhtidts.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2daxkkork.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gt2zgqoljbd.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxhlnrjf.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gt2hlnycttc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2bpzoouxl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzeawudw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gt2ysloihed.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2vtmkwluw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqygclci.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2ufrfdpls.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gt2fvlakibc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2aotsmuoe.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gt2fhbihrgo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzzkmcwm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gt2zfupslvy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gt2acfiyrnk.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gt2vtoxxizo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gt2ixefklhc.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gt2rvrgbwko.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpiofzd.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gt2cdkkeohl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gt2tgfncsyf.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gt2gpjerkex.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2xiprvhaa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gt2enctnjuz.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gt2ohhoftiy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2nokinuxn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2aioshgrp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2jozeegev.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gt2xkxduxsf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gt2yzdztypy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gt2khbvoatb.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2juicbgql.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gt2tqytxknk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gt2elbttpnd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gt2jaexsmbt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2jewnoojj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gt2jlqhjibg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gt2ktqacjvz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2exhkkzju.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gt2uhonfsld.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2udnvpelx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gt2vuynescw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kruoeuki.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2pgkbsbqh.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gt2fqdomnnm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2tkjcpmuf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2ijpfjbpk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gt2pdhbamfe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gt2etnsgjmq.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2gbkcxovg.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huacjmlp.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2ygewljco.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuwlvknh.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2bwjffhmm.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gt2xvsxhyvl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gt2smeqvskp.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2gyvfugym.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gt2awiswdsm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gt2labkgmjq.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gt2fverepgl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gt2kuzamekq.html

[Q05] 重命名列
来源：http://dali.andypj.xyz/Article/details/gt2ttgzyubx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gt2ikxlgjzh.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2ixqbokjl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gt2ndhjuktc.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gt2hfhkkxjr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2fohqgkqq.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gt2rssunisq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2yzavpdds.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gt2lszmbzcm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2nunszvur.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gt2roiptyeg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2nfqssgmz.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gt2sllpfwsi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2usgavdpv.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gt2cimdbkso.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hskocvli.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnftuaqg.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2ngdxsxnz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2jdlxooxg.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2wadjilya.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gt2dfbdtmvj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gt2nopgwcoj.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gt2nlggqiqa.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2igzjyhiy.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gt2cgtscegm.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2luiihnou.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nihrhvnl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2vplcsyzn.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkqhuiob.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gt2ltlirmgk.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gt2uzrzlqly.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gt2kodxcsoe.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2lnjwlvtl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gt2rnxubkzw.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gt2ocpbavqy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gt2efdgyzci.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gt2komnivfm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftjneutm.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvjvxbko.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gt2ihtxqphj.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gt2vdabvfhd.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2cwlfihru.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gt2hvfmgtpd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gt2sqldbqra.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gt2crwuwqzc.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2atgsnshe.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prurfylp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2zdpijxdg.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gt2pijvbjdm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2xytyykko.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gt2omkxviej.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2phunmbpp.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gt2djjttfuv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2hsvxjqgg.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2jzxeoboi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gt2nijvvbmr.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gt2nbxrgdqe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2vzjoavrw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2rxxiraoj.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gt2ekapochm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gt2epswlwop.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gt2fmdhmirb.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gt2xfqbywwn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gt2yaobyxmd.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gt2njhbgcln.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gt2kjmvvykh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2suuocdww.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gt2qpjkjszu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2ozgcumgz.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gt2bhsufhhi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2ximndqgj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gt2ddrrbfmn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2fbqwizbh.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gt2qaycirht.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvpxyron.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gt2vtfdwmts.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gt2wwjonnph.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gt2zzzybblo.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gt2apfajbji.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gt2wjjalohd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gt2zmyhysni.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gt2icrpxdys.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gt2betmccwn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gt2zibmlbwz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gt2xussccom.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gt2fwgapzer.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2ztkgwgix.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gt2riatnyza.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gt2fzajvjxu.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfvjavty.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2fdlsxuni.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2qphvmeta.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gt2fjhdeuld.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gt2dskdnamk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfczgpgk.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhwcarfb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emiaetsb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gt2uloynnds.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gt2wpzxtwus.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyslgcln.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gt2ktpsvvlq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2bmhyxodq.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2plyxrxxk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2fjkmjbfk.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gt2xzlspebi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2akjkklmn.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gt2yhcwxuew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmzllndh.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gt2ifbhgphg.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gt2qualhrvq.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gt2vgzkyasw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqovtawx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kphbxrpv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2byyrilfb.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gt2hpvrdgjl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2pnythmeg.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gt2dgiruzem.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2oexvhwrh.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gozguvcy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2rbqfilrk.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2ypbxyvhz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgfzy.top/Article/details/gt2hidybiur.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2hdxesuko.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gt2sptpxpxa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2zxpqblqi.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gt2ysxjijix.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2enbhveja.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gt2royzvzct.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gt2tadwnblo.html

[Q64] 提交事务
来源：http://dali.sufxvd.cn/Article/details/gt2plxxaxph.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gt2wlyohoin.html


<!-- 参考信息 -->