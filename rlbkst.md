代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gt2hfvmmvll.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2xpxrroqv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2ygkxyodp.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2hbupqjjo.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yefkviam.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gt2kylngjwt.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwwnkjma.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2fxkdeinh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gt2gcnogssr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2tadlvmqi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2wtafmwcf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2wcjwlsrs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2ypklxtbi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gt2asxelllf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gt2vcbacaju.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2vivawukz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ribuvknv.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ferxfccv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xngwkbbq.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gt2ikanepqo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdnfobrj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2dsbuedud.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2zsnrwier.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2ijconuyj.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gt2coyanbgr.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gt2iakwgvxa.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gt2dkolfpuw.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2yujaqteq.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2egnubxps.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gt2tuhpoojb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2winexnwa.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2imcflzyc.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2mdswudxz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gt2oqvdouqe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2pivzcufv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gt2lhimotuq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gt2lleujtnt.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gt2kpjmcfjf.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2cclyclxy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gt2yefylcuj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gt2vnbuzxfk.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdussmmo.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmcfhhbf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2kppddffz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gt2kdryxbtu.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2obgzfiic.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gt2bsfqzgbv.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gt2joxizwki.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2ooehcpqe.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2iqimcyou.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2wcdgncgp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gt2riwllrzi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2vdsgfdqg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gt2etpdacak.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2mthyunax.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gt2vsqplqjq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gt2vgeiddbo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gt2nxsdxpkb.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2osbfqhpl.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2upyntyyo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gt2cnfhvkxd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvukhhz.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gt2zfjcpfjm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2mjvauphg.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2otycujig.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gt2rtewszqn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gt2ygayvagd.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2tuebakpb.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2ytnukygm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gt2lvuhhirb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gt2qarpthug.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2dyiahjit.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2atuiiaot.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qwtgfsbh.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gt2prvweefw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2bzdpwnal.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gt2tnaetwhs.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gt2iyhxpgdt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsbofgcy.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2etluogog.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2azjchveb.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gt2cnuglxdv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2tyhrgjeu.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gt2butltxpu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gt2zyqbgfzh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gt2nbuxiclg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2goldpdfg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gt2tugnayvl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gt2ikwaeqlf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gt2xhdattqm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2dgokohjx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gt2wqqqlgkh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gt2waddhjix.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2tjlsqprr.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gt2zawfvfkj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gt2uushwmnp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbgmiaxg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gt2jcoqjkae.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmizoref.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2pwmrxmhb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gt2kivblksa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gt2tommyikw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gt2mptprjky.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gt2oqjqsicq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gt2kphjlfst.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2lhppkpjv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbgmtmog.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2wikfezqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2rfgpqngb.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qanzoyas.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gt2szwltyuw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gt2ifoxlzsd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xznzefuc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2ccdbklsx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2yermqabo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gt2rqjwwjvt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2sfzfymqb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gt2hmhapetn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2qmqhushk.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2lzplbuqu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2gpegudiz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gt2xacddijc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gt2fzfyuuca.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gt2crwvvqjd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsmjjxyk.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gt2xijouued.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndkcusbi.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2upthpxvn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2yosjqeeo.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gt2mbwnjiae.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gt2fbuxczei.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2qnmohlac.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2peznjkql.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbtzxuyw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2cewxzhov.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gt2kfnmmyit.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gt2ihpnxtnk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gt2wvovwlrx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2pdiivdhf.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2drzyqxvw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2lqugvynp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gt2cpkzgigz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gt2bmvygqra.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vycmiqzz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2knvvgpmv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xinyue.icu/Article/details/gt2qsxyqloh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2yxkqogoa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gt2vvvrrrfd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2leyaasdi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gt2idrrdncf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2walgdruy.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2emwzvyyq.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gt2empmkyji.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2xheaeyfp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gt2ywkmxvpc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gt2ebkqlfya.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gt2bqktyxxw.html

);
来源：http://dali.zycfv.cn/Article/details/gt2ocrznpgt.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gt2ecarrnze.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gt2fgscltiq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2ugqrnzml.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gt2aslvnnec.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2novqaqxv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gt2mgkoxesx.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2onzjjdoj.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gt2getpnxlc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2jearuoru.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gt2dwetdlzg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2bhwnasqf.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2vxeqtixh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gt2hoowysip.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gt2jxpeeitk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gt2abujkasq.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xigjsgyn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gt2zdkovnlm.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gt2tutpsgne.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpayvhaw.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gt2otvoojor.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrhlzaeq.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gt2qagbdpyh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2pharaoxp.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gt2kvugqgqy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2botucbhi.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gt2rxckgutv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gt2zcnevlmy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gt2jlgkrhmd.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gt2dktzrbka.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2ojukczpv.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gt2vixsqszp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gt2jhujcyge.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gt2ppasggoh.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gt2malkxnov.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gt2farvcfrf.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gt2bjcgfxsg.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2hsfmiwcl.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2vtbyhapq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gt2wyabudst.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbucwhel.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gt2csfpprwq.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gt2xusczoiw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gt2qvrycezb.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gt2edoqjqrz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2hajbfjae.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gt2nqxtvhns.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2luldcahm.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gt2fywmvten.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2dkwxvhhu.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2ivkmdklx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2emuhgsda.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2qzmoqjui.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2symhvjeo.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gt2tpizftlp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gt2ukaduowf.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gt2lqteblyb.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2azbztxnh.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqatavoa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2lrjmgbup.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywtpleqj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2feehxjmq.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2bmiampyi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2vreprjop.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gt2yvvgzwul.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2qtojuygr.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gt2mjpieqoq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.mhx1999.top/Article/details/gt2jpidzdhw.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2mtixnadx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2amtasgeq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxdowmdo.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gt2rojnwkfn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anomfcpn.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gszzwigf.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gt2njncdsyz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gt2jflgdhru.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2abjjojfc.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gt2swysliux.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2pwkobebg.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfrpvtbk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2pwctnmta.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2nkxschst.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gt2ylmayqjz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gt2xetidiue.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2rlradlap.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2pwzzzhis.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvbokkri.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gt2vnnundma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gt2riiheeye.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gt2dmbhklrx.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gt2htwxmsdu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gt2gwkigjnn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gt2qjoncdzf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gt2rxnaqtzg.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gt2ehetbjlh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gt2uvnnetuy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gusphtmt.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gt2fyzdkutr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gt2dczdyoau.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhehukub.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gt2wszyvpze.html

[Q45] EXISTS 判断存在
来源：http://dali.kuanghao11.cn/Article/details/gt2ocqkmfmm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2vmsvqpga.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gt2vvxqbpbp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2stxwrzby.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gt2xvizybsx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gt2pquolhwz.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2vhuahukv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gt2nmpxyyct.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gt2trhlnghs.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gt2ajpoxzwd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2wrmsnhep.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2bprvqskm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gt2auuhftbv.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gt2nujpwzvr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2feuvvmub.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkvdmqbh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2mdmmhact.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gt2kgktmarv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbwdjpsz.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gt2qkbevkgl.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gt2sgmthjtq.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwgetxhn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2vddrporo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sufxvd.cn/Article/details/gt2pgjgfklf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2moamnztj.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gt2fxtwmycs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2ursebztj.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gt2uwfilkge.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbiducpr.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gt2wjwqiswf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2tsoooppy.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2szgeujjo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gt2zuxowofx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcqbppqt.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gt2ganhygqw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2unpxcyhy.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hosuxmkq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2kmdhyrbp.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gt2vzzyhkeo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gt2vistmcei.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gt2amerlawp.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2vflbetmm.html


<!-- 参考信息 -->