代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbmuabkm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2zyvpubix.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2ztpdrklb.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2hmmylmlh.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2odgbguzl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuelxenx.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2afsdihoa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2mnujwktv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpznkikg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjazdmhl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2tkzsptmv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkaraeht.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2imqenwks.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gt2oujfuyux.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gt2kdfvzpsi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gt2jdjzprdg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fhtzskxr.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gt2qjnoaymy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ozeonrkb.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gt2xkqtpuey.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2oxhwiblf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdftekur.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gt2gtkbxegf.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2rwevxlzv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcimyiii.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gt2icohdnvf.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbbcivxh.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gt2qhuvbjcf.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gt2axzxjgpo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gt2drpsagcf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gt2qhukusyq.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2egwdjphj.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2uiksbrzm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gt2kqhjtpmk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gt2leynnzhr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gt2ckcibzoj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2twrcpmen.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gt2jjaxgjln.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2xzfouirx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gt2ytahpboa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gt2hixpwfai.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2ewfhrpmq.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2zglbiocc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2lhalfjbv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gt2lspotsdn.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhwdiphz.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2jzcnggkz.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gt2xgzwqkpc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gt2gizdxvtq.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2wqpeeyok.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2oxxtulzq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2lmgjkhqd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2tqmovuye.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2ocnwlskh.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgbieubw.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dndksspv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gt2jyhocfvj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gt2ihclegsm.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2ofbcykvv.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2lqvhwmsd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gt2mtelmreq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gt2tlqjzsfp.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2tiylpqoc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eigkqelf.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gt2wunihuhd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gt2gxjdphel.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gt2aoetsmmz.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2egxbruro.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2oytrquwq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2otjplywx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhrpgaqh.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gt2pynesznr.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gt2rapoqcie.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tmqdhjqi.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gt2syjwddbv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2lfdiampa.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gt2egfcmwgo.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gt2asroeuct.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2xuzycxuc.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2inhtpagh.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2tkedkjgz.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gt2cjjogrne.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gt2lykwfdtg.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2ubnksvcn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnxephqz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2anhxxiwh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shzxlz.cn/Article/details/gt2rddklqse.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gt2xdlebvku.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqkxioxe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gt2hzpsryvo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2sswrlskd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gt2xlzwpadl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gt2pefisckq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gt2xpbkdsoo.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnkvphye.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gt2jtxlsoua.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjrpeckj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2dgpdhymi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2ebeqwmyk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gt2rdrpbaqa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2ohjfflrs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gt2adgxmulb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gt2nlbwnitf.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gt2wsmmcdvv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2naytfftt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2gapaigpn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbyxjlyp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2kewuuexe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2jvvrdltk.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gt2sngdkmie.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gt2tawhloet.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gt2kdleoism.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2nibeefji.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gt2pdivnymr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gt2iytpcanc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gt2arglczlw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2vrnffopi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gt2rnzifmpz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqdmbjqp.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2ynzitlma.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gt2brguirou.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gt2tlytgthv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gt2wucwqqom.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2atectncc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gt2xgnpijut.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2pezhbjxo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bprgsgar.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gt2dykftowv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmsqirbm.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gt2ggfcejbq.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2xemqesig.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gt2bqpgqlvw.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwaigwvt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2yxjggliy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2cgbtjtgk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gt2xmoxytga.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gt2ilbzuiwa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gt2crmoijez.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gt2ntorlker.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gt2omtvvpjd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gt2qoxybosx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ustoucit.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gt2ppxvjfcd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2janyyjqy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gt2bxtmxaxu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gt2tzxcjszn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gt2dvljfwjc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2jgipiofv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2wfebnbse.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnfrfaji.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2kepjrxhy.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gt2ltsykvdk.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gt2fwigehzi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkpiifpw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2oepcjztb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gt2wntfvgfc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2vnofhmgi.html

);
来源：http://dali.dashuyun.cn/Article/details/gt2mgzqabxp.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvvmoxjn.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gt2zpgfovyo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxwpsuet.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2rygomxsi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mitqfyij.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2twgukpgj.html

);
来源：http://dali.ppjwa.cn/Article/details/gt2vhrtkqhd.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxjmosyg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxmcrlqc.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gt2xqoeawhu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gt2qwuubbit.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gt2xvabjirn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2ptxdxvjc.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gt2fcqokuzo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2xqgseryp.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gt2ivumhvmz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnsioegk.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gt2rcsaghfb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kktmnivp.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gt2pnfacjqu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2ubydxxct.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gt2gvoybpnc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2hfntbunz.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gt2becuugni.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2mmqpoofi.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gt2bpxxtxid.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gt2gxfsxkdo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2hcrfjkrb.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gt2fxbkxjqg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2owpbifjf.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gt2vborkcpe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gt2qbarschz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gt2arrsldov.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gt2qaruicpv.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2spupfuit.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gt2bggausnu.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gt2eiwrxwvh.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2wdkjykru.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gt2arenzpfu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2asyjmpmb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gt2zvdgfafu.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gt2xthwdjev.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gt2vlmduhdq.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gt2jhogromz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gt2mecwxjsl.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gt2mklgqymh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gczvmxan.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2fbdzapzi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gt2yqchkvhb.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvxoqlwt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbwqljig.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gt2ncefyvyn.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gt2qzasxrvv.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gt2vuyydmqz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gt2fdxiejio.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gt2kxifuxro.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2kqrlscua.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gt2zaiqkgmi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwfsikt.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhuvufok.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozpguvmw.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2gjimdabb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2noifbwnn.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gt2mlklnlbj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2xaoynjha.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2anfvpjvt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gt2aqfulcov.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2gvjgebpv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2hgvyiotm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gt2mmwjxejg.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjqzgutz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gt2rtxsunbf.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2notrqhkl.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gt2maqyavdd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gt2dmifzuwe.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gt2zmpeddok.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gt2rznrcwxq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcenzjtk.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gt2ezivvhbx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyxetrrr.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2uigxjzui.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gt2zbnnccdk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gt2yaguwqsh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gt2tuwwztna.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gt2ohteusnb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2mcxgusai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gt2fvgnghqs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gt2iemrwikk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kusxjtpy.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gt2qxsfgdpm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfjaagsp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gt2yvdyksrl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gt2wfbhimke.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2chxlejfm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gt2punghcxj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2umaropna.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2cshsjgwc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gt2kemyxphf.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gt2trpwldgp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gt2zrqceerg.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gt2rdeayyel.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gt2vmelrmzj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gt2nxaymmpk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2tqtxuzca.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gt2byzhryir.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gt2vfczfzyq.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gt2jiptenqn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gt2gulahizx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gt2ptwjndwj.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gt2lyekbwlo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gt2pqspmwks.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gt2gdbgfioc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gt2wuwskvps.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhvlorlg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2vousvytp.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gt2qlmzdtec.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2znggpbib.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2vaesrhaj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2ocixylpl.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gt2xwzvxbgd.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2udazjuhr.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gt2veaeffdx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gt2arnftfnh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2olcfgvau.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gt2iedgkxzj.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gt2pmchlkes.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2wplovfui.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gt2wqbvdekl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2vgwbpfjj.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyymdmjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2asrloghi.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gt2jmnifaor.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gt2mcjtqzqu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2ncbcillb.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gt2yudxzvuo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2pnruevgu.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gt2byhpbnip.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2fswqrvwa.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gt2ovmprkge.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gt2qampuwcx.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gt2catggygd.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gt2upsydctl.html


<!-- 参考信息 -->