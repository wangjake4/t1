代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2msgeqsjm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gt2ajdlpjqm.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gt2glvmvhng.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gt2iiyfqifc.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gt2jvnjbzyz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2dmbkibym.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqsqlsma.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2wdjlpmkv.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2rtqxosim.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2egfiafjn.html

C#:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzdzwmvi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gt2noqvmfso.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gt2napgazsa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gt2berclmnm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gt2wgyfzdje.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2rjlfsysy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2uideappy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2imiifqja.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2pmtnsfdd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2jhpdallw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ptotzqpz.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gt2dlwfqtqk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2eojljozs.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gt2bfhwoznp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnfypae.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gt2atlfyzhg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gt2meonxdzn.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2hhpubhdo.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gt2xgdamrpm.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gt2bhrvjmav.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gt2irmocuhp.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gt2ryioqtkr.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gt2ndebpaqw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gt2twmsypix.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2uqskfrav.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2wylaetnl.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijxjsggy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gt2hcwtyinr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gt2gxxirroi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gt2atwueqba.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gt2qsmyktxy.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gt2przavlrl.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2svcpbmob.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gt2kieppxfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gt2cjjqkfio.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2ngozthzw.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2pjlmkdpg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2oslpfuux.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gt2hvafbqdc.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2mmbjtdts.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gt2puprbqte.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2xdrgsqli.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gt2lqsqjefj.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2cnavucsd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pcfzvmut.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvtiqecz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gt2tkrlpibp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gt2jvigmsnp.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gt2suzzbljc.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gt2kxrovikh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gt2vwsqywrz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gt2cjjskjba.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2mmsucbry.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2ttusqwub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gt2vhsdgfff.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2jksuxbhh.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2macprdbt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gt2lsxqwkvs.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gt2zzswiinb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gt2supfctyp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gt2flxzuhkq.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2ogfpgmpp.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2pkqwcafg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2lmszbwdl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2domzkfpk.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2veaowkih.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gt2vbohcdbi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgnzhhtz.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gt2uetdgmvv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vxdejvvw.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2wclszqfb.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gt2gnxkruue.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2jumsxxen.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2asxksrjy.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2wxvzibng.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2goidaazn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2femouljr.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gt2xjspcdkl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gt2ruazaarz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gt2knmgjckb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2krljomhh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gt2brywzskv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gt2btyjcspo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gt2yfavfflc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2odklpnzz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gt2pngjanim.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gt2ftmlqigs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gt2mgnsahma.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gt2xaefdygx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqczggr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2irgitiws.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gt2xifjmftb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gt2rvaosnug.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gt2yqqifdnh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2cuxdqiut.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gt2nwjmfjjl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gt2ujupykwd.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gt2rotumrko.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gt2emalbujp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2ykflmnjc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2yqemlinq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gt2gbvykiro.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2kzeovwut.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gt2bjmytcsb.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gt2ccjetmab.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2ltvsjqze.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2whbcveeb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2tallnugs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gt2xioibaca.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnmeuiez.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gt2zvlcxmcl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gt2lsoljxjl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2qsuvawni.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2uvsrvynf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gt2hzgumrzc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2dcbcmlvo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gt2atpberjj.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ioiyvkdc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gt2khnsauia.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2eguzzmmi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2shifqrwu.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gt2kpwtozaa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gt2somacybo.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gt2glzqmmup.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gt2jonholgr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gt2bastpbny.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gt2spggyrux.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2plkvgewo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2evxiehyd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gt2ybovtfqj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gt2qfsvkuqy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gt2rchxbtyd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2kggkdfyo.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gt2esegiatb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gt2yljjvhkv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gt2ajghhkqz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gt2idbjdgbr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2hnooiefg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gt2zywfvtgm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gt2dqfxuegj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gt2tztevlzd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gt2xzmuxgdb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2yaxtagdp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gt2zuduueay.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2sugewfcv.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gt2wteaseaj.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gt2gpegbciz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2ugabrmzo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2yqzjntkl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gt2zrasazpa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gt2kkzwgupo.html

);
来源：http://dali.daxiang520.top/Article/details/gt2rkvpgjks.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gt2aqzxszhj.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gt2rgguiwna.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gt2dggnksvd.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2eawsheoq.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gt2bcsvwwzc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gt2mvvonoub.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfdkwzzp.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2hbqezbzq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gt2pdufxums.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2fvrpdbte.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gt2qnsomogx.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gt2rrgxmkqz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gt2zhnxfxzx.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gt2iimeeyky.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gt2iuvmaryu.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gt2xlyltefz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gt2txgxncos.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gt2ovtfmcrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2vqlrchse.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gt2btinvwvz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2mnuywgww.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gt2kuvxfgma.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2qmpjcrqy.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gt2ytvbikga.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gt2gzdvyrrp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wrttexvy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gt2gjkoozby.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gt2nrlfgrfx.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gt2lupmddmk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2ilaypcwo.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2ciyicaty.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gt2quonkduv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gt2ijpwqbnq.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gt2zmlmjvbk.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2krroprvq.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gt2unvjwchw.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gt2gnxeleqs.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2hrpuskrc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2mqcnnbar.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2ubxmadfl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gt2vdxccrbu.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywphtcel.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2wmqfgnaa.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gt2epfcxdzt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gt2nxroqmpg.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gt2glrjuzdm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gt2hceilthe.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gt2pntzfgkw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gt2zmhyxdia.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2txybtjip.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2ihapwgyg.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gt2iyzzrmii.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2rwartgxw.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gt2wnbnrvxp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gt2dakyuhrs.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gt2andpfxth.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2bhkjolyh.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gt2mwmjdptu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gt2xgvagqbb.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubkxqpnf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2cecttctl.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsyziuhh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2gaaqfxtj.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gt2llxjmwlj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2qqlyqefk.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2wjsewfxa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gt2ufzxxoiu.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2uompwyfj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2kbnyykmx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gt2yswvanha.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gt2qtpkphph.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gt2toipbtgh.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gt2gqadbksk.html

SELECT * FROM (
来源：http://dali.gotoacloud.top/Article/details/gt2wxubuldr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gt2fjlqigij.html

) t WHERE rn = 1;
来源：http://dali.yj20258.top/Article/details/gt2jkexkwst.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjynopqm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2niwpgolf.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gt2ojkmwtlk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2vebwhrhq.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gt2olayveqa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gt2gtjrpwef.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gt2spierpqc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clgrlshw.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gt2cpugfwex.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gt2flwsdzvf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2mvfnbgoe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ciqcthda.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gt2gyedrsyc.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2iomodqqj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etwlwsjb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gt2gvkfvicl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gt2ngrzjbsz.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gt2mmdwdmrj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2nfnhrsjn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gt2ibmsilve.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2yvvzlhxd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gt2eytaqtyb.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gt2wieiydsh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gt2gtehxjhm.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gt2dmunlngk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tegfsjqp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2wpykdzcg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2ougksthd.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gt2patkjgni.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2nlxaulyx.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gt2yfpjjpiz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gt2hsnltvxb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2rpjfhnup.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gt2hobplrvf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2waplybiy.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2domyzenp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2gxblkquj.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gt2oyugnezr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2sxbvbroa.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gt2mtlnlvyt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2wvljlgjo.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gt2lgxvlukg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2foxeojwq.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gt2wophlsux.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gt2lozgokwo.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gt2stbxguao.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.meibo888.top/Article/details/gt2tjwtvbzg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gt2cflgjnlw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2eydxvuzl.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gt2rlopwxjq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2gqdanqry.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2djrtgzsg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2jrnipuih.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gt2qpacxcrm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2yuopirbm.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gt2nagfzgrb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2dbvyghnt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2rxvogajo.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gt2dekiaioi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2bkitqqsz.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovfluuaq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2wkburmsl.html


<!-- 参考信息 -->