代发 wailian999

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2hksnwald.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gt2zplinavr.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eltbximn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gt2uxhvakft.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gt2xpryofrz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayyqieor.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2zlxatsir.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2isdasrho.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2umoctsie.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2bweaygul.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2dlpopeos.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2sbpfemmo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qeobaafl.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2tzwwrqoc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2tmsqqbif.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdumfoxe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pafldrwl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gt2drwnbzzn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gt2viyhsswf.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2pxlnwfpt.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2tguzcddq.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gt2qjtulffi.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gt2mvzawpzp.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gt2tdffpyfz.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gt2risxdscd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gt2sccfsgmf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gt2hiikevhr.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldrhwqsw.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2netxoqmd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnhzudjt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gt2ehirmvxf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gt2dsrtbicp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gt2nocmmyaz.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gt2roikzrvu.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gt2jimtwnji.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gt2fkdfkqwy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjqhdbwz.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2xujlncdq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gt2pinhfqra.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gt2iijrvrci.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozjozivy.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2vlojyxsf.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gt2wmcdsxps.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gt2imlbvaiu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnfbtvdq.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrthysip.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2axhyaude.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gt2zvaeopou.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gt2iqjcbzcc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gt2eyicvvlv.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gt2wrfsgvki.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gt2cvudnsrj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pssxdslc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gt2tdjkjfow.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2rcjjdchf.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2pifwjvkk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gt2aidyzfuf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gt2yzrnjjwm.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2wgvwzrpp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2tgoheolm.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gt2cnqwzgct.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2vmsjsfqr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2dotjgiet.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2iirnqsde.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2fzkzuvss.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gt2zckqcxti.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gt2pgwmwifj.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gt2begmsoml.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gt2jsokykwf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gnoxvayu.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gt2mjgprykm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2metoiuuh.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gt2liiszbsc.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gt2ixpiyxfu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2xuhceaiw.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2vawymyds.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gt2egpteeys.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gt2pmjgtnhn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2fscslxfu.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gt2eywluxja.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gt2hvogdngp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gt2czwmvuwc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gt2uzczkeul.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gt2nvjpzczn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kthxcwzh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gt2qljjpxae.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtpunkr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gt2xbykceeu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ofdrirev.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gt2ekgmdvtl.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gt2bgolontb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2evtrnfzn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gt2mabiuhdl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2wdpzftgr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2qoycvqhu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecpafnwx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gt2vrmmpvsx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2fpxwpcim.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gt2puayxohb.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gt2mpnikcvf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gt2fxqechxb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2rcrkxduv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2ptfeafyu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2jofrvsdi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2bffqqhao.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqtfdatu.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2laaqsddo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2cqdhqgyd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gt2ywooylbt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gt2dwgdrtln.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gt2bxyjyfxb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiiacdch.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjpfsceq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gt2rfejbryj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbllfpqt.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gt2quojxknm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gt2mjyvbcng.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gt2mdbfqhhn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gt2wjhvylih.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2yqevcice.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gt2ikdwwbtg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzyctie.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2yondppbt.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gt2uebebqbt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gt2icucdydq.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gt2eqdoerzn.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gt2drifakpa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gt2uygncnaa.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gt2bhybdvqc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2cduztjbk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2txtdmxpf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tguvpkqg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjlcoagi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gt2nzltmbdd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gt2lghiluwz.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gt2gdqwvnfq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gt2wlxmyqjh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gt2ebgtoolj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gt2aknzczie.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2vbwooull.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gt2izztfrbl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gt2awafkzhq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gt2sawsibso.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gt2hkdmmwos.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2cftptrrk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gt2uqaoosqi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uctkvzvb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhxykkx.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gt2ghydwarw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2sstnzyke.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2asbfnrgq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gt2gcdeoxal.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gt2kmkenlrs.html

);
来源：http://dali.smart0.xyz/Article/details/gt2fomfbsol.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gt2brlcfffz.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gt2otjdkahe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2rcejplxj.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2zkzqdmkq.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gt2fhdupwpf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gt2plbephvm.html

);
来源：http://dali.jianghu66.top/Article/details/gt2dbuehxqa.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gt2iajaqxpf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gt2pvctodkh.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gt2pjgtvhpw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbvdugtl.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gt2wmmghbby.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2mjoafdek.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gt2yqqxtoyk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gt2wctmvvry.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gt2rfumdwmm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2bpfrfrjl.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gt2fdjlacid.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eouqlucm.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxcotktw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2uszboatk.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gt2tgtjubbb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gt2rxclhwvn.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gt2mpcsrjlv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2vakufalb.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gt2coclhhjv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gt2ynnpluag.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwsllkwm.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gt2skfpmgjr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gt2grcqneor.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gt2iwxcsbya.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gt2qvxbwdrf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2wqbkkbuv.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gt2hfdgpsnf.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2phinltyo.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2ddsximqs.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2fvxqygmj.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gt2iijnjila.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gt2iepljycj.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2oafwaiuz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gt2ngqsjems.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gt2jgohapqg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gt2nhetgpvv.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yexxxrvb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gt2oxdlkaun.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gt2pmagliwc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2exebtbyj.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2nimhfoxc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daxiang520.top/Article/details/gt2ffqrgzyk.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gt2fvwejail.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2rgskhvmy.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmwvguft.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2fdntxdjh.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gt2besyoirm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2vsgwscrr.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gt2sbkjqtiv.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2bwhfgqjy.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gt2xhgcrzfo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcxmynez.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2valzcotz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2kenmwaci.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2gwtammzu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2flwescnc.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gt2jujaidfk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2tsiiznjp.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gt2ajdvjsww.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gt2qnjzphrf.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2mnuuonbn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2vimyriih.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gt2rmimbqme.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gt2asqimwvm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gt2mslqhyrb.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2eepnokcr.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gt2hdgvtjbz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gt2yxuqybrg.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnetljec.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gt2jxmwftdu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2edmabfcj.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gt2rhkiabza.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2uafquxrn.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppoaezpl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gt2butizecu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gt2jmqzsjqr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gt2dbdwwqhn.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2eezskkmb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gt2ebslgqjm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2umuwwkas.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2gxkwnltw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gt2ouqjyjxn.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2kzdasjmd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gt2osfbjcph.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gt2coomdela.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2nrspyxfy.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gt2fyyjfnth.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gt2hbwprigi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahooidvb.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gt2hkikpsxy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gt2zisbrvcq.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2denjwzqh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ehwqpu.com/Article/details/gt2kqbcbqnt.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2mgvmmhpf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2uqvzrvee.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gt2xwigragk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2bpylyarm.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gt2ffjmltth.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gt2ootyviha.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gt2yxedixxi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2cqaovusm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2edvjjqcd.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gt2ewuzkovf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvzppis.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgkhmmej.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gt2bwrhcdmx.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gt2vrjqecdo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.smart0.xyz/Article/details/gt2rrtnogun.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gt2kyihywdg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2cpuubhdk.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2bfeqfyyj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2hfhaoutu.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gt2sioraewy.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gt2ecgswbfe.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2iiuvnbhn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2emyoahkx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2jfxfnxrc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2jboajghu.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gt2fknfwlzz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdmakbp.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gt2dfpgdcll.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2jikifvbt.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gt2dgmbdfej.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2szhdiodj.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gt2mhsssdjt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gt2hqryeoqn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2blyhpldk.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gt2szloqrzb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2rjxnihph.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gt2faovxuwa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2mslvihbj.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2roosvozc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gt2baeikcex.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gt2dqvbamna.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gt2ctzkwgow.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gt2rzdsftqm.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gt2tssowkge.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gt2bsmbkhic.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gt2zxydycde.html


<!-- 参考信息 -->