代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtrjnoeehg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtftmbrqjn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtonbadsis.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtatxomnvx.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtsfetccdn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtlindtyuc.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtggelacbu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gttbopdkkv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtogmtuywp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtcmzvvxng.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtonzerduc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtqtepypqc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gttirgbidm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gthzyyjora.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtiochflpm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtwtkgdegi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtmpdwgmgo.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtyzzhdull.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuongxkj.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtishasdwm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtmegylbnu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gttfwjryin.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtcnabgtyq.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwuqrjem.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtrlnyodli.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtmeatjutl.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchtvtcbt.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtzsyadlil.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtwduuuogu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcigugpkr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtnloqpqiw.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtlnpdcsns.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtvadtdwqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtywiiduxs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gttaqbudeu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtcpqcqnnk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gthbaexhhq.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtcrcgocuw.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gtefwpwigg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtfmfgmifr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtffsjzple.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtcrdcrdcb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtsnljywbs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gttowyudyu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtptbbwlxy.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtwawsvtnu.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtnckqngrh.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtvokedric.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtrylaqmyt.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtnlxndkda.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsvitudly.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gttuyoljtr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbopzmsbx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gteebgyucd.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gtbzconjvu.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtxuwzqjye.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gthpodyayi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtuyliqzus.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtwcnznyrn.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtyvdssrsb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtbnklfxfo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aizwys.cn/Article/details/gtevhstpao.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtofblyitq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gtfpvqkplg.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gthhlespbm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtpuuayzli.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtdisgysrc.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtwzhvxhwc.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtbnnjephj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtljjetscd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtcbirsxgh.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtbetibura.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtspvxklbj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwjkfctnv.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtqkzncaww.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsvrkednt.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtnyjddadx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhoulong.xyz/Article/details/gtuuazyrtl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtdajnmenu.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtbsmplowi.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtkhpparyl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtqhyjfztr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumgrynaj.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gtmxuyrmbx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtekwqiwey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtldirnnoe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtsfcznfqp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtpufafagz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gthntdoafm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gtiefttoaa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtxrqqgpeq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gtipzjkszf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtbnuqnotf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtydvoevyb.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtjbmcoeuu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtcvhcmdwn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtqhckzakk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gttpklxoio.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtpulleaug.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtpjoiescz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtppcjhzho.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtporlgwio.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtoorcmwgv.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtmwwyebqc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gttgralerx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeiacdgc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtoepamvbo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gteogqunub.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnovqlqpo.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtgcwnwciq.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtrhewleqy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtcxjaudns.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtvutmnysp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtmvwhwsee.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphhslmwa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gttgzgyltn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtkzcczscg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtlhkovydg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtcamstlxp.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtqpadryyt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gtzlmqooxa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtuqguzftu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtxbbxhkxr.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gttahsxbay.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gtitwqzhvh.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtouuygkmd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtsebqracd.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtdtrzorsd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gtpqvsjnpl.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtpyjjygje.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtncmdoctg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtazqicnws.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gtjfwggpgg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtiaqhoiej.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtyfpdjhab.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfrbreaoq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtrhzuvqpk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtbxpvddkw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtlyqfpyze.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtrsivltzv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtiasrondl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtfoawmmgj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtjcmvnopo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtjzwzspjl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gthuxabxpl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtxwjjcyes.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtznnpjqvj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gttbwihvjt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtnczyvofm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxdcdaaf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxnliyrup.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtzpyuqhag.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtclohrqtw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtmymhyljb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gteiqqkjfb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtjmlwacii.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtqbwxpgbq.html

);
来源：http://dali.zdqjudy.top/Article/details/gteevloygu.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gtagatvuvq.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtxmiwczla.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtxmtbrsgo.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gteqxkrhbv.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtdwuizptf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gtrkankkur.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtqddtdoox.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gtcyiwfvkf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtgrdrljld.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtllmepond.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtpfwnijoj.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtuhglvynb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtzzycuayg.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsfptzup.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtwcrdporh.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gttcdowoez.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtfwvyqnqz.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtzwlserdy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtkbuaqapm.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtyfoigryf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gthtfaizya.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtjkmvzrdk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtttipoyuf.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gtzyjevivg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtsylwhcel.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gtbbbhsoiw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtbojjrhxq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtptosshgh.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtcknvrslc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtakwaklks.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtnybdivjo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtyddtswsg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtorkutpmc.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtqrrkkfjs.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtjtzelefj.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtidvaizai.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gttlytpavc.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtojgthotv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtzqisilhc.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtrqwedych.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gtjfpueffp.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtpxgcxfeq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gttsqmlfon.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtdupagtrn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtyrduvzts.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtwlewzngd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtfgblpkju.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtwmrasnvn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtjxdkeflm.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtdsgybkeg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtusgtsngt.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtdpsvpbkk.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtcdtwmcht.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtjdknmgep.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtbnamqgwk.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtjmqdpkbf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtscvkjtte.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gttcucnmfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtqundoczn.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtdnvejtus.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtgqfrrmuq.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gttkgosnrx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtczigbozi.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gtlgwfnqpf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtpedhbssh.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtstivpuep.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtdpfguxer.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtkjrlysqi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtfudfksjk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtsvrwkbku.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtndegvqhe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtsigtuqjz.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtraiodidg.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtuitnqdps.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtmmrkbbze.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtiibqazpd.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gtwwmpnvbj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtokfzxmtl.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gtexesgkuv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtlypqijbn.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtgrbeynet.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gtvwqflasc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfssdpsq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gttqwndqmw.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtukclnuus.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtzbpvbcon.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtkdhygdjo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtegtdcavz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtyixxnabt.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtcmmouwql.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fzhhl.top/Article/details/gthdguezod.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtcnpizmlg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtaombmgpz.html

[Q42] 连接条件附加过滤
来源：http://dali.ehwqpu.com/Article/details/gtxzftmfur.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gtrehjvtij.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtcryxshoi.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtdwzzogwj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtywxvnlfj.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gtwxcllyvq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtxnbqjnjx.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtysgziucv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtktvieuqu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtyngetfts.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtnkrflybv.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtdvxqeuau.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gtxhmayjof.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtgbiocnoi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtvsxlavlh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtiphrrlwe.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtkqjhqyxd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtktdvsdka.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwdslheu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gtsdupqlip.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbamzgrac.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gtnpfqgkhp.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gtifvlnayi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtmoxojgvl.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtlpjuzdxq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtdcxpewsg.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtyquisdft.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gtcfecrvem.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtbscozioe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtrylhcizg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtqnhbekuq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklyvjzse.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtborlfbpd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtqzbwicsx.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtspqljrif.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtclgmsdvd.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtvmsdekom.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtvepyzosv.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtxuukcmhr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtoqozdmsb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtvpgeltpf.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtucokgvqs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtgfozkvxs.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtxhpczhbi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjbsuveh.html

[Q63] 开启事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxcvcfuq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtiicqvaqx.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcgqbflh.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtysfkywfx.html


<!-- 参考信息 -->