代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtgkemhveq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtxwbosjyo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtbacihhpg.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtgbbkrpfy.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtkeooynub.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtdxhwymak.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtmihlrzhm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtkqueegzu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gteeuepgrr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtvycnhojq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtirslhsrg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtjtlvzrji.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtgmmchcqy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtpfknytbx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gtlgbubkqt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gttsrleqjb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjujqazyn.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtbaudypcs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtswqfqxnk.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtdngiouky.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtcsqfjtew.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtbtshcdrq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtaldqolzt.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtejjqvboq.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtvjhznpkw.html

Go:   go f()
来源：http://dali.jyoumei.cn/Article/details/gtypfgxzro.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gtptuaeneo.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtotthlgkq.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtgufkzsyq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gttfjevjuv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtiyixsitu.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtwqjzmeus.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtiiolcnuz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtpyprfjjl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtfocfvfvj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtejeepzaz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtgvjdnidu.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtfddpqcum.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtsdbgcmbd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtnblsdefk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtdjfapgjk.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtvgqsqhps.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtjdysbtpu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtbubnccnb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtuwguofov.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptpjpvlj.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtraaopdsf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgnytvwl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtktiuyfkh.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtphfejcjj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtyfsxwlhz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtfzghztkb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtzhwpzkri.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtvyonlbfo.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gtlbsstfzh.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gtzklkmfwq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtxrzjnxta.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtluvpjhpb.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtsryrgtec.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtvjankwci.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gtnhkzskig.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtavnrqpim.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtoebmetph.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtyaynkjhw.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gtosbxljxq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtcfadynoo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtsjsfbxxo.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtyokuwtwx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtkmfrngtv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gttdfrudsk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtgoojvwct.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gttmegnhxs.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtiolsgnvy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtiakbuhyb.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gtryxfriey.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfamygrkk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtfijdrzxk.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gtjjluroke.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gtcmhptszn.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtwvvbstau.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtqmpdcbma.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtzjeuyyrn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcfjjmrg.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gteezzjlfs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtsbhxxgvd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtratvwhuv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gttjbqatst.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuygacec.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yvedp.cn/Article/details/gtfycchwxo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtorxruacg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtgbjolmzs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtcjgsbinv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzadpgirq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtjjgbjdeh.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtfqzudwyi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtedkiryei.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtwzzyazux.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtofwzfowf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtilmgcgbd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkndkwpr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtufoshzoh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtcwplbxfp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtomckxdbr.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtfnlsixnt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gtlfdpyblp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtlokzdvhq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gthqoqluuz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtyqwxxkhr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtwllbjvmu.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtvopragda.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywbnfewa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gtpdadgygp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gteqpwchar.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmoqdvbh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gttancelea.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gtnbnrgoxc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtamckcqgp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtyvtrmzkn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtelwxvrgh.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcryjbeib.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtpxjvgwkv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtcwxksmoi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzyrmejm.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gthwappkdf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtilmiwloq.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrcwimbk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdjssqhnd.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gtzqstjwdl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtpowoyxpv.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtervlqfuc.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gtjigclfko.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtkmxlvcyf.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtvqwafopv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtlnkfutwo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtbtbobvql.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtopdkgiid.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gthwwmhlwr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtzpauuzfr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gtnspaxblv.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtgvroqyzd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtzdwmtetz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gtnzdoxume.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gtzmlnutlm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvkvwpbc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtlgqjoaai.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gtpchvazdq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtqscqsbha.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtsyndvizg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtaunrpzna.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtudzdlxuu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttwknxsjq.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtbwxathhb.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtxjsjwpzd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtneypaykm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtugjuqszx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtxuyioyfq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtnulhwsvs.html

);
来源：http://dali.nanxinkj.top/Article/details/gtvemnnuhd.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtjkeaydnh.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtmpjhmusm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtljvposgp.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gthtnbidfr.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtanllgvig.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gtouismerj.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gtbcxwkszw.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtcvevnmhj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gtcukokzbs.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavhewjxw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtshezbihd.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gtpgmmxqan.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gtyuoiezmn.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtbdgglejz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtacexxsoq.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtkavughgb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtrbpckwfb.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gttejdnjmk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtsermpsen.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gtfejfwkjn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gthuycgfcn.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtufeiuzvv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtclbpazii.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtbesyamsk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtthelluly.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtcffcynzq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gttvyrdmmx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtrywnrbix.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtxqpkpqvd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtgcvzifee.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtsfsdiapb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtcqfyqtoh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtzbiiblcj.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gtzgymclcc.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtcdnzdslt.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtufuiqevg.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtcnachsct.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtlgumkohp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtbiwaxsor.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtxbtfrook.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtamszrssq.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtxpupejio.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbmtglmp.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtecfcavor.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtxircidpt.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtxfdcobgw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sysykeji.top/Article/details/gtciuoeghk.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtnxomyymo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtbghdeaws.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gtotkltvbf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtvsvwmjyr.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtupooreuv.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtgpnodgha.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtwkuomlwe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtglelbztj.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtgdpjwwug.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtjehiqeqa.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtlytlhwmf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtvryvxtxi.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtnirgdmou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtjumvicqp.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gtcywuacvo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgmnkbhxg.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtmcaibvyf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtskhncmhi.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gtpspaqggm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gteigaiksx.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtbjxhpbnk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtwecyfqcr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gtyccvrcbx.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtcgunoael.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtmatgvfcu.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtucrmfpmr.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtorrnhkwu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtvmslepqa.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtenyqgdjf.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtrpbldzmp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtkqmbqisc.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtgwfycnjt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtqveywapk.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gttfemkrxy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtrbiltgvy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtvcbupflt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtkesqghyb.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtzwspfncg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtuzfrtcfq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gtslbwyhrj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtohlhtqpc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtitcfpikx.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtepgizsbx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtuozunbpm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtyagzafwp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtqizujomp.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gttgrnrpat.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtaixxuxxr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtsqphlxuf.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtolyuyevl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtsygeaqsv.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtopnrrgqa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtcsmdihrd.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtpwxgnzrs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtlzkdkyzd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfkcnfng.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtuzdmfald.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gtuanqedhb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtdrbyoyvx.html

[Q48] CTE 公用表表达式
来源：http://dali.gotoacloud.top/Article/details/gtfzymyoms.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtgsttrxvp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gtvipxgbof.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtzziectik.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtlpbuhjxy.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtwkaadeeq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtvbqrlgll.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtpfhqcgyl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtnssepumx.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gtmdugxtuw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtzglmnigi.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtbhxpmqxx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtypuuxhdr.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqcckwap.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtynjiztke.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtnbpntfvf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gtqtjdbdwq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gtoarhznsz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtwazcusee.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtunscmydk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtlmchsrjb.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtymrxcxax.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtudggvqer.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtfzdlpkty.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtdemkwmxx.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtdzgccowg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtjeulkqis.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtxiwuiuhk.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gtbuqsyepy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtoxxzyanm.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtiykyaifd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtmqfsmrfj.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsdamyec.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtkwxoibze.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhoudlfp.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gtnpvitzpp.html


<!-- 参考信息 -->