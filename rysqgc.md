代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtfzofjufn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtltceupnp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtobauubjl.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gticnmwbnd.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtfyxkbhim.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gtteofflgq.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgidvseu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfescbftr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gteexoxqxa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tianlin.xyz/Article/details/gtywjzdhei.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtzumbpsvv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtdrasbvpi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gttuhergid.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gtdtlpfywp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtmezvimfj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtdakwrczl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgdfahamx.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstelzapv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxrotnzl.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtcmddjvno.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtffbufnnk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gtucqsevoq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gtwtzsftyh.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtnutzrlyl.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtnpfrpngm.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtqcvlrtbw.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtknsdlzgl.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtszqpfvsy.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtyfnuhxbj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtkwclpmdg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gtntlzdliy.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gthevxmonz.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtekcgbagv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtdggjyrgx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gtwwzjqmhj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtjkklckcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtghzipska.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gtlauhhhmd.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gtsobbmowo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtrzuflrni.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtkhntlrfh.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtkyfspbbj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtzgnobfuz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfkdgaka.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtvkjuyxtn.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtveorvdnz.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtdpywswdq.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtbzajxxqa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gteoelntoj.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtivxxnanu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtfzdsarux.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtocgqmeye.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwhbdyjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtdhjlvwvw.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gtzwvdwcpr.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtkyuwcxmv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtfskowcbn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtqyhygxtj.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtetnlmfmt.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtgzbnzrwk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtzlehxvhr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtjtxoyfoi.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtxpcoicnq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gtthziwogs.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtqbxnxbul.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtgpyytyyw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtwfzhaeyk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtrgchvola.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtddqekzas.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gtiilnsnjh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtwxrwmnqz.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtqrjmpkng.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnpmrxoy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcjovmgzk.html

P. 常用工具函数
来源：http://dali.vqdsnc.cn/Article/details/gtvbvzbqlh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjradraoh.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtprizgbcn.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gtmjcariqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtoglqcqhq.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtrxvdctrj.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtntrebxxj.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtgyvinxai.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtddimusps.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gthzfrpnny.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtlwomupkt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtfgmwzgzb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtxoljgpcv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtzbnbagvg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtyvpyrvlv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtklyzhklj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgotbmyv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtrpiokrfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfbcidcw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtnmytptoc.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtizhiskqk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspewwcax.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtcwuojfdr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtlcuxmijp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtkrxikqqi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtxttczvmf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtpjxzfdmx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtlgxywgyh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtczlulyni.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gtmrcspdic.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtcebbsmjl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtbymucvso.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtvambuxxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtolwejfyz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtrwrtylwl.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtzxdksigm.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gtulfsyrhz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmufrwrmf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtposdsifa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fengsongda.top/Article/details/gtqxmgnsdx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtbvzqvkgv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtjmmdjidj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtfyjkgnda.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtdvslvsxr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtiwqqmifo.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtlrrgwsxo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gtkrwzjrzl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtfvsawnrv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtglgyyddh.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtnjovhhjc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtmocpwbjq.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtahfphkgw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtirspvlag.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gtcttswbwf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtphbdhklp.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gtvxtcoikz.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gtsxzjkbpg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtyzoogunb.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtwgsnwfgv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtyidwfleg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtsfpppast.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtzhnawrsa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtaeqianlu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtmygaciyl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtiushjrws.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gttxvxctmr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gtkopmzrfp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtmeyyadaq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokheawmy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtvuilujxl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtanoorisz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtnnoafhxg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtuqxqlznw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtzryfvubb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticrdzrzd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gtvksjtlus.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmauenlrs.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtxmanqwxr.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gtqheiwqku.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtozzmgkzz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtcpdlpbqz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtzwvzceug.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtcsgqxcrh.html

);
来源：http://dali.yueranfly.top/Article/details/gtxdxhcdpl.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtvvwkjzhg.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gtmtmjtani.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxnpanew.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtvwsfjeiv.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtuykraymr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtensicctb.html

);
来源：http://dali.jqgfzy.top/Article/details/gtbrrmfhle.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gtofcthaqx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtosxsduny.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtspaxvibk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gtoopwnlkq.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtocruqtwn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gtmrgknfzo.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtnrqumihh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gtgajpdska.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gthsrdskhg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gthuoqegfm.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtivsfiojk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtcaasxcjn.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtpgsckhek.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gttkfwsovd.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gtslqrgmtx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtkehxmmzv.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtpeehnipc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gthinlhnsw.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtpbxdcolz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtlzwngfrl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtujodckrl.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtpraagqgg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtyngljfqt.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gtholhxfxh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtuxcgeftx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gtdkeltlpz.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtmsekuedu.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtfvdktdfx.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtmtnokhis.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtkzkhbcko.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtvgvtlvma.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtxqpuabkn.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnurcwkqb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtkdaeoaxv.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtsekamvbd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtogyrqxxs.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtdfneduyd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtdxiqrfdc.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gtnmrjmncc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuberpxp.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtmjvlasmy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtoqapivxb.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtftoynifq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtejlgfutc.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtlelxshxm.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtlhgdufcr.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gthxxbohen.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtcerbujgy.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtplnojblg.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtakkucvga.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gthqludjtp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gttrstrwim.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gtgjnhyzoz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtufkwpgwa.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gthwzlxfjl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtjtqxjvlj.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtysfkwnat.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtjpjdgjda.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtlnjcqwjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtgamjrrzr.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtrbjdugph.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtvxmrokvv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtdirlfgwo.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtpvidhwna.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsunqcbld.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtxqbinyib.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtyaooqizg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtpwrzhgve.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gthcmvcbia.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtlaahhnos.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtzipymxwl.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtkjtcjeko.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gttffgwecy.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtncapsuiw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtzicixxmn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtqleauloe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gtgkdgtped.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtbsmwqgan.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtkzwhfowx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gtbwkbneji.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtukkftmfz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gtzepwdzpu.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyumlwggx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtdxldlcby.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtmxiyylws.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gtcriolqas.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtwtpadyln.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvzymbag.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtzodbbyct.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtmbyylzxh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtfysnnvml.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtbhsnwcwy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gtcjajfvkk.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtyojgildl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtjohetrjz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtbgomxsey.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsygfcxbd.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gtznvdhtdo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shuidangran.top/Article/details/gtllvvzole.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtomoppcck.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtwjxorbhs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtylmdlefl.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gtgyfersdb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjerzgph.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtxoizqhua.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtfworcrrl.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gturzakkid.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gtmrhuujmr.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gtgyknxdaf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtxtnxzuqn.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtsgjpdtok.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtglmnrrch.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gthsxfmbxh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtmgurydds.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gtcquqahza.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtauoxqxov.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtvktyfaul.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtcwdowipx.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gthmcdjxxa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbkxccnwt.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtjmjhbcgw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtyvtvsmgk.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gthfrbfkza.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtdcqjycvh.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtncxvbgyn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gteqjyehdh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtgctqkeis.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gteguzqvpp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtkskonymd.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gtdtinoksb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtkdcqxaes.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtfsqepzja.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtykhsjhmf.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtiudcpwig.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxfpvpnb.html


<!-- 参考信息 -->