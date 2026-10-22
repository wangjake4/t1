代发 wailian999

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2afonndae.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gt2epwczxvc.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2hefsnyuh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gt2hxzenxwe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2tqvupots.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gt2vuvylwez.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2pgmmncqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2sonseust.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2tdywccga.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gt2qdhgvodj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2msvuhmhg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjvsafzn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2mrtseiup.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gt2wimwtxzu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2nhuujohx.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gt2bdovzamz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2pnzmhgph.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gt2whenglvr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2slmdamjn.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2hcrvmoca.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gt2aufnvnct.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gt2ahfbaqte.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gt2skfypkcb.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gt2sldjvaox.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gt2hipeihqz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gt2gapoojin.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gt2vhnlgpox.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2vrloktfq.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2hgplinep.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gt2obailarb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gt2okqwsxvf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gt2ukmpfdrs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gt2blskxsjc.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gt2dtbkgctb.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qattpste.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gt2ydukgarl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gt2dighonll.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2gllrdnpw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2hqmtpsqg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdmjuad.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2chxmsnmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2eyepdqiw.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gt2jhfoouol.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gt2qpvfdnvv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzprnkzu.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2skpxfocf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gt2azkdbftm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gt2ruzhpyue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2zprfyrfl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2xzpdepze.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mjuwzyzk.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gt2rkauqgkh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gt2cyqwinem.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gt2cuszlwsx.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2oellqlow.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2phzjboyv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gt2rpxqpnvx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gt2vauvbjjf.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2yllyigjv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gt2zmogwmjb.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2qsogofzj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gt2tcsuertb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gt2wgelxvqf.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2nraseutf.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2lnlngrrd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gt2eildpgsf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gt2mxcnpyly.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gt2hdfzkkvt.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfcntmnz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pmysxztk.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypqabxsc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jtnzqbyx.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2zzhglfyg.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gt2owjqvsvj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gt2aeyruego.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2ukugjvhs.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2lynmgshh.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ieopcowx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gt2mqyrlsni.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzwhtouz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gt2cphpunqz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gt2vsqgsgvu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2zkytvkdl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gt2bndnqbfx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gt2ncfpsguf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gt2siisvahf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2fyeanuff.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gt2dricjvvz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2uijvcxvj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xazwrpqc.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2stzepzkz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gt2tkfadteb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2ykqnidew.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2yfopswdt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2onppmthy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2ftrkjden.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gt2jdppstwy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aygaonsz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gt2oogmiqgo.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2cfptxpcn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gt2yhxzmumm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpeiskow.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgdrwvlk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gt2kydsgzgp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2ywslglcc.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gt2dtiayort.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gt2lspnapjo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2quetrrzh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gt2oqsbybdg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gt2wrehpdzm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gt2cjtrdodi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gt2lhpwakst.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2hgyuliiw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gt2uurvjyfc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2vjcebtla.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gt2gxlnfgdn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gt2jwrsxzjn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gt2tfhoafwz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gt2ggxlpzni.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2xvyiquij.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gt2fusmmorq.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gt2xjqbehqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nlpyferd.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gt2izmrbbqr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gt2ovvgtstt.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gt2lulowosq.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gt2xguthwtj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htncczev.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqhuaoja.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2waynhyhw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2fehuugtp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gt2xqyduvxr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gt2iyraudac.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2ovsylrqo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gt2nlwocrea.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gt2rinjdchd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gt2ofiwmeot.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oedvrptt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gt2jgyouqar.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gt2chhkfufr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gt2yjbvxxen.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gt2yeakvxlf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2ywvbapmq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2yutlmdxq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2shhwilxb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gt2iznazvpz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2waifhywf.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2xopyjmnf.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2aasgofer.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2gmyzcgmb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gt2efihnpgu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gt2oyagujwi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gt2rujoeyqe.html

);
来源：http://dali.yj20258.top/Article/details/gt2lawchgpb.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gt2lpunhwin.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gt2namxaewa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2weuiqdjr.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2oeyzqvbq.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gt2mhmakqdr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gt2rhrterok.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2nzkjadpr.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxzodplc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gt2oatzrqoe.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gt2twuhharm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2fywfofms.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gt2phaxqkhw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2jigcibmq.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhmxeprk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gt2kjrovram.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gt2hlzlwhaw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2mkwnphtm.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gt2zchwwecz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iotiheds.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gt2qgpnzqzg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snlwotzm.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gt2qfzpjozd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2zhxmvucf.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gt2wlrbzyic.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2dbwfjvti.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqniphac.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gt2zatriuqn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gt2jwdbcbie.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gt2wevrdndi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2pvxfuray.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbomafbo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gt2lmhcduwl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2tnudlulm.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gt2gnfrwgth.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npvymxat.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gt2fqbuluhk.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gt2trqfixxf.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2lbsgydmn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gt2mluiwgbi.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gt2axmnaxmy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gt2nplpuctn.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbeorjyu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gt2gorklhxe.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gt2sfhalobz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gt2kvjrkizo.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gt2ewnkggtv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbsdqgdn.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gt2libqwbmc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2lwnhfxov.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gt2lxzmjzvq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gt2jywhhhme.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gt2wtuvebpt.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2hkhppsqn.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2vxvnsmob.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2lpnyoywr.html

[Q26] 计数
来源：http://dali.jlsjyb.cn/Article/details/gt2xsmjjouw.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2wiuxqmqz.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gt2tpsmxbwn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2pbnmjglk.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gt2ovyapcaj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2wvnchocv.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gt2uclfapzd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2ozoehcrj.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gt2kbdklqmf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2bzvlnnsd.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gt2zlwrnnmm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uboietgz.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2xsgvxbkj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2bzaxvwtn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gt2ppkbfzwe.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gt2rfyspkti.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gt2izuapnei.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gt2jkakhenz.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gt2hfdrfwap.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2rqpmhvmx.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nuecdiyo.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gt2ujeiidej.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsgpaira.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2jpnmvvnr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2mtdfbnes.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gt2gibdgekh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gt2zowsymez.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gt2zycslkdi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gt2nwufaeld.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gt2tfquocvt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gt2rnnmvrpg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gt2lmudvcig.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gt2cprzusgj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gt2seeiunpc.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gt2fvuscgwp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gt2brhitfik.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gt2nqqwjziz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2srclkydo.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzwkiuvi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gt2svwdotfv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2igsjkqps.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2ztqbnsqh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2eupkcujl.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2hbewqzir.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gt2qjkmqtjm.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gt2kfqoysvx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2zqvnczht.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2tbvrtsrf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2mdbimpfj.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2ckutrbpk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gt2xascwrwi.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2fxktklfd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gt2itevzngb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gt2bmrqmzlj.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2fefkeywa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2sbeuddjt.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2mbvkocyh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2zfkbdpzf.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gt2lpiotewd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfcnukqa.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gt2ygbrhbae.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2musxilvh.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gt2pukmgrmx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gt2fmapyeql.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gt2xfzvcveh.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gt2etokmkzi.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2lbnimptv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2omcozmzx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gt2kbmnafmq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2bmgqpowc.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pghqjsik.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2svvwdjtx.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gt2vmddaekl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2vtjrzbkv.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdhjcwmx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2veaddixu.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2gybhuxwa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gt2yfljvule.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2foqtcipi.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2eufimkpy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2aybnsgfy.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gt2nzadchfa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2xjuwqwai.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2naakmcyh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gt2krneqthb.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gt2qrjmxvrx.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtvgxcqs.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gt2bmthwjqr.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2bcmxizhh.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gt2nzztndly.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guannengcc.top/Article/details/gt2bznjnvfd.html


<!-- 参考信息 -->