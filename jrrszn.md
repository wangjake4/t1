代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2vllunebl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2cngwsxvn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gt2xqawpvro.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2vwtddgxe.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2kicuuzwx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2dviycqfd.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2mtrzzazn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gt2lxtgrqea.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euwbzbvk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmryaubp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2hpgeyxqq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2ydhouryk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2bnarngjh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gt2jlgwkzpz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqokkkpa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2kxgjzutx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2nslmpqij.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gt2kkjaswqd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hietkhyf.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gt2yevzqvvx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gt2vurpijlq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2xkvvljvq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gt2wpgszunk.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkwpcpvc.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2xnmpvqoo.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gt2aphncnoo.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpvmbvct.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsdiykd.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2zhkmobbu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xylfe.cn/Article/details/gt2kddoijxu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gt2gxsfavmo.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2tqvftfew.html

TS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gt2mwwnqcgp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gt2gnziynxn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2zazeblcs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gt2zcxjuzhu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2hibiiwrq.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgrjupin.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gt2tdcmtuaw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2pqxrpatp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gt2aalriedg.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzwqdmjd.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2smvrymol.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gt2bzusyqrp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gt2jxpabkts.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vcjogfgr.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gt2ymmofknk.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2svlolfup.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gt2ankeirdn.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eplifgzn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uodayhsm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gt2jqayhmwe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2edmqwxfn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxxufgrb.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2sctndsvn.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gt2cgypopbg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekbhnuyb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gt2aogfsgpb.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2aaccuyyp.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2hgextjzr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2ltforyyb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gt2adewgbke.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuxmfyfg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2jmdewanl.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gt2flqwrhue.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2fyqjqtse.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gt2aafkbswu.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gt2zarphsna.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2ufqkevnn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gt2jxcrjqsq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrdlanjt.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gt2ekzznikh.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gt2krlbzjtu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hddpdzhg.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gt2btvrseyc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2hwfteqpa.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2zvijxxor.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2sfvcyvqz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2yiypfmop.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2yefhrwta.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gt2oymmabdk.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gt2tnfgbvrn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gt2deilqkeo.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gt2mangixwd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gt2aatukswy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2dcxaewxg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2vfyvdjhl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gt2jrmvdqmh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gt2bvjbijix.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqafillt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jojtwqap.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gt2tculckkq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2tnmmytlb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gt2pjbfdfob.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gt2szumgsoh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gt2hcccaokn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gt2pgokflvx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2nrshkrxu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2relhdoin.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2eprqqjzo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gt2ahbapxru.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gt2sjpmgiim.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqwufuqy.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gt2arxxhjsv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gt2yxtiswhe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2lowrnhhp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2qinrbbcw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2ldafvmxq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezyvsxmr.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gt2orbuozej.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gt2ilkpzbgs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdkzxtwd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gt2khwgfvjb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2jzkliunn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gt2xpxgnawi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gt2awfknmxg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2lcpfoliy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gt2ihkcdyof.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2dsosliry.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gt2adafeuan.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gt2tvnfjkou.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gt2bnhlxoml.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cttewebh.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gt2mvdxsrdm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iibbwtyg.html

TS:   if (x == null) {}
来源：http://dali.tian-w.cn/Article/details/gt2fvepfcra.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ewzdkbre.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxwnaqxl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gt2fvhuhpgm.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2jdlrjftr.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gt2cystufpw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gt2pkflpnow.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gt2iwaqxzvc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2aqfgkhoi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2xoqjrwec.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gt2meoojeiv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2mhvxmqjh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2qqmfvozz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2fdbvtrjp.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gt2urgyfwxr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gt2uyhvizur.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gt2fdbyqrbd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gt2mcrakfnw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2kkdwwvjv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gt2dbbrrrwu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fztvmsjc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvwpfdik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sblmnvke.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ugufhjgo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rafgpfam.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2evynuvia.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2ymhqvawc.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gt2htxvokhf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2vxmhudhg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2jtaxovjm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gt2bhfvsewg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gt2lsywwfwm.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2ldhzayml.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gt2zhstpxai.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocitaaky.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2vvqtnqrf.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2tmvnctzz.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gt2jyjtfzsk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gt2ujommnsb.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2khoewdly.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iywchsqe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkkdxmso.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2cpunzlrq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohlmbxai.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gt2iizvpmmc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2iqwzrilh.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwfiggzn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gt2kimuexgo.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gt2tlurblsc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojpqkwey.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gt2ffawmmnb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvpjgqed.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gt2kkjngdez.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2mrzsrsyc.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gt2duvkwipk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohuojyzu.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdnelpza.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2zjgemenj.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gt2ygzfvmcv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gt2eqstgkjb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gt2vievpyxz.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gt2hdslgnmd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2dslyplpi.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gt2lqkncrvo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gt2rmwpxhtk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2hybsneho.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxotgejz.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2pqywwlki.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2xolveepv.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2bobcijbl.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gt2iqeudvhz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2xytwltcc.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gt2kfvkbwqh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gt2njkiuzpo.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gt2krbgxxhf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gt2suhjlmma.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gt2vspbqdje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gt2hwhonubi.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gt2cufpvahv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gt2qkksydin.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2ewerlfoy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gt2oqmunlbp.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gt2suyangjb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2flustaus.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppihsasd.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2fsnfmawe.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gt2tozhmzfu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gt2teuuiqvr.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdkvgzsj.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2brldjeth.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gt2avbmnkok.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2pzqskemf.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gt2nltxqqgx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2pfmtexrp.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gt2ykcbsokn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ouficeia.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gt2kybjzrfg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2cizkfshp.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gt2pkfobxqn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zycfv.cn/Article/details/gt2yucbisid.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2rnkaxggt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozpdtrdf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gt2wiqmbbti.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gt2zrotvulu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2crdqyywq.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfvlvveg.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gt2yctlhcro.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gt2avwvzsub.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2jtrxbwow.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gt2uudspycs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtvmdoeq.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gt2nixogltn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2hferffhh.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gt2nvldjain.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2eratpong.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gt2gvwhyual.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gt2zqwggage.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gt2ezhqyqjo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gt2dswrmseu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gt2zyaarqty.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gt2riiwbqsw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2kheffauy.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gt2cdmenepw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gt2ynkpevwh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2wffwphya.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gt2vxmhnned.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gt2flalpoyr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gt2ryqqmvvr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2vyvkpwpp.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2yrmgwlvr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gt2nmubmdtg.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gt2obtywkqa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gt2beqjmnml.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gt2jbrgqcau.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2romdvsek.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2qiibcxyz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gt2wpfmuucd.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2peqkfswx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gt2qypiduek.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gt2hhwihxyh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gt2pwxwwlan.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gt2bpefszxq.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2zyjgtdzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2fyqxogsr.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gt2xupcsoys.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gt2fuvzavev.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gt2kpkwgbxw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2zcbvshxu.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2vjerohxv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2mzrbnsgs.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gt2hxdltxcx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gt2qhhtwdbd.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gt2ntjbyjrk.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gt2cxktagsu.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyrtkadz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gt2dokckoqh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uabdsvbq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2grwggspy.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gt2phcvodfi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewdcmssp.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsfvlklz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2iwlymfaz.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gt2sunqjhgz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2jgihtawf.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpgiiius.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gt2wislktzy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2qenxeluh.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gt2iqasvqqp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdfgjnkx.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2ydtcqugg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2ptcbpdol.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2tedpurhv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gt2qzrgspcc.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gt2ersteogc.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gt2xhrbnuxd.html


<!-- 参考信息 -->