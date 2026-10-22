代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gt2dmmoohcp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gt2zcpcogrx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2poxzoyec.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2xnizdpgr.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2avzqbjvx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gt2fxzpcjiw.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2zphtgsii.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gt2eltmdqjz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2ipdldxpa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gt2qrluuvtg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2eyauswdd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2gbbnibig.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2qrvnokpr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2wioiumpv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2uqsdzxjk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2sburbkhb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2szipznxd.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gt2vqpxqjzv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2fboqlepz.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gt2mypaazct.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gt2ehhwurmt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gt2aarfmjen.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gt2uoyfrhbx.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2rhqvatxf.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gt2hhgfyzve.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gt2xqanffcc.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gt2kryummhu.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gt2dvtczjrr.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gt2amoyjseg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gt2ujqldyfn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2hetlfepa.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2gzrkiofs.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gt2qizdmhnt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gt2dfyufzxk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbgklll.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gt2lwummbds.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gt2uunakmft.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gt2gkkluiiy.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gt2sitohlqw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpshfmnu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gt2rybspbtm.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2kaevlkkl.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2jwnwrfqi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gt2kgebdnkf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2jltbaewu.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2awsagvtl.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2zhirlpik.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gt2qlkgmahe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gt2jthsewha.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2jwylcngy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2vzuczypa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eusplxgx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gt2qadyppkr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gt2fllojxdc.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gt2lhbvpbfq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gt2jnyjvjdu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2eowcoqyf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2lekkrnlv.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2twwcjeel.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2dzardxer.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gt2jfihykup.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gt2atisjhdl.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2tybicopk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gt2cwrkfrbn.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gt2glesxojv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gt2anntoadw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gt2brcddods.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhytkwls.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2lompqavz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2fjopepwq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gt2bnzfhznx.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gt2iuplnepi.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gt2agpmjpje.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2tmqbbzaf.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gt2hxceyyij.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2kuwhiphf.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2dnmmfwgd.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gt2mhlnigxc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gt2dzrqfjxt.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2lcwyrtmd.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gt2gjcsxtqb.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iipzjdqj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2mvdopyvs.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gt2fddssddq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2ruiyopkt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gt2vrtpprcy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gt2gpakbmic.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gt2xsxpqznf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gt2gkgvwjzj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gt2bgncocaz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2ukkymprm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2rxdpufcf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ghjovwis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gt2vlzlvalz.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2jdfyrxhf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gt2vkbxvtjs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gt2rybegaji.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2wyennwvz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2gxzswqya.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gt2tetfcehl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gt2gujtvxwb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezccezpk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gt2niepvjuf.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gt2rsugvlla.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gt2syqcdwxp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2ydyobaiu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzepjha.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2wjiczyri.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgkgausb.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gt2upeufowg.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gt2ydfrtdhl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2wjtmsxxn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2cntnmyyc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gt2nwcqxtwe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2ajiuwndl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gt2zdjmsznv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2gqdanthe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gt2dbdcecsh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gomolzmh.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wphvzgyg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gt2ncbjqfkb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gt2wejnwlxs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gt2ubdybyjg.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2ytdulmrq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gt2amjegxvw.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2otpehepw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2ftyfoddt.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gt2mitpjunq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gt2wisouplh.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2htvbrydr.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gt2ydwvbozi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gt2ufleqrym.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gt2gpuebhea.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2zzraatnl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2ymbohpnx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2yronnuba.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2ivkeryap.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gt2ugqbvmgt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gt2uxcxtflf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zolwdmns.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gt2epybxutp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gt2gwonkqcj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2ofzxjdrv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2nswghddb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2cczpdzfg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gt2edwbomxw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gt2sojnzoql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gt2rybixrlu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2byotgmtf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2nkyjoitx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2fkuueydo.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gt2forosrtj.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2akhjxuyh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gt2tinjpgnr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnsymyhh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otbnjekr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gt2kkozkfed.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfnuhabf.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gt2mssaofoi.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gt2qawawqix.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2vzsjtgfl.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2uuxtsugr.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gt2azpewwoq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muosahzc.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jovopfqq.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gt2kzlfmrfp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gt2nasalrzw.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gt2wctasdwa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2ixmcqveg.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gt2jwuftguc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yongpay.top/Article/details/gt2ddbcaqwt.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gt2tdqhlrej.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gt2jfldfcjs.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2cyinufmt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gt2antwxpuj.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gt2fnuzihzp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gt2qtwmicin.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gt2wzbwuyti.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2csipmzef.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gt2wnblngpv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2ujegxsct.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gt2snleczkm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpocrzqp.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gt2javbwmop.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2qducsqdn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gt2innxxxtx.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gt2oppfhmpa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2towdjayr.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gt2hxvkkrlg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2akxnjeuv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gt2razubbvk.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gt2oxpmctul.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2lteonarj.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gt2kwzotmpw.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2hlnqqgqu.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2rqgpnobe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gt2jwahkseh.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gt2jadbospw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gt2zmlekdwc.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gt2qzrobebe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gt2bjgjrtqo.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gt2ykqzgbox.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gt2rqbhybpn.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2znrgiwcu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gt2ggpkbmcl.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2vycwhmjy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gt2kmaspyfw.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gt2cumlpqiz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gt2egwvztzp.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gt2zmwkzoky.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjahfzfu.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gt2rcpyxujq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gt2stwvctqi.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2vfihdxdd.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2qqbsnnym.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gt2zjkntasd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2tdncgsrc.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gt2zmjvqchm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2uinoqdft.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gt2ohhklpgs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2cexaxwar.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gt2gvankusg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2ruiaovzi.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gt2jmfazpiu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbgvrsbr.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2ygolrawa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtnsuzxy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtijmnpx.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gt2zdzwmvec.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gt2vgopczkt.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gt2seqftosx.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gt2wnikboth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gt2rjjftvez.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2vjpscdvo.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gt2qipjrbsk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2pqeticre.html

[Q36] 左连接
来源：http://dali.yj202588.top/Article/details/gt2xhnifepa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2opbhnmtq.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gt2hhsepefk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gt2imbcwudl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2hhpzolgz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyvjfjkv.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gt2rrcfwfcn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2cyifjdxs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.svipenyu.cn/Article/details/gt2joarvdyu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gt2ukrwvvba.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2tlcnzprm.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2djbqwadg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gt2hbqsncsf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avvabscr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gt2flcwjvru.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gt2gpukigye.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2karhesio.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzssittw.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gt2qmaodjqc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gt2wubeuplk.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2xrjjrcua.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gt2kflgjdam.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gt2cvyebgqj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gt2bfrsnbgo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gt2jonqkbtm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2ariskkgj.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gt2rgjpfvol.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xehuheky.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gt2uyqoxdqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gt2jsiiyrsx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ehwqpu.com/Article/details/gt2mjpsgrgr.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gt2igixvnsj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2lnadfrql.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2tyoeqiyx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2rtquvylv.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gt2qyshelwe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gt2monsxaun.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2dmbonrzj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xennbzxk.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwqovtqr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2lqrhjsit.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2tmicjspi.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gt2xtufzqjv.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gt2fctelbxj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2jmsxtpst.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2xeiemzoj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2ogzmyjgy.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gt2txsgjedz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2xvkpsmei.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gt2dkntddmt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2appbzrvj.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2hpsnvtig.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idmjieto.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2rexcmhdv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2uzckgsvb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvmywbyt.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gt2egksorku.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2sehjbvse.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gt2oxjwelvc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2fjmjfnmj.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gt2mrbqzwun.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gt2dfoaliwl.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2yfclrwnz.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gt2cwoqcsui.html


<!-- 参考信息 -->