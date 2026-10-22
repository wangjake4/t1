代发 wailian999

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2wqfxuhjs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gt2tkdvynav.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2eevjwopc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gt2bmszusql.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gt2vparbivr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gt2olcxlcrt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2voreqigj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdbiaisl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nryqpzzh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzroggqt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2qubdgsep.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gt2iyrsdhif.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2kggaatgl.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gt2ufdvqyik.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2rrblmtgw.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gt2ncwxanjy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezibrpgm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gt2sflqvkqm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gt2kzmduppt.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2rsqugygf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2cjfztqoo.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gt2ivelkyym.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2wdktxifw.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gt2qipzekoe.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gt2tnfkctwc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gt2fvrgrkkj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gt2ubigtpwg.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2wnzqhdpu.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2tcxaiges.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2rbkfplky.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gt2tyfhbvei.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gt2gldovgbt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzgkrjhz.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gt2ndjqcpym.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gt2sihdwmik.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gt2grjybaez.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gt2irgodwcv.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2thkrejyw.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnolohjw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2gqogrqoh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2tjlqoiuw.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sksaknbp.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gt2mbagzumk.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gt2xdmvmklz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gt2ofydgfqc.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2zodfxzgk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gt2zhdtftxy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2kvvooeql.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gt2xmfbvinn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wisiciuk.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yedjlyaz.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2olxyuupb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2emdretat.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gt2sopyhqgn.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wasniobv.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2kurtruqa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gt2lgsfrtab.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gt2xgkwqvmj.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2niutkknw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gt2cztyhyla.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gt2xnzbfqst.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghfakcdz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gt2bwzjqftn.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrldphvp.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2xhazsuts.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2kubktstk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2zhzofoti.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gt2zadpvrzn.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gt2gnclokrg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2eoecckkc.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gt2vulmynms.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2hvewerzt.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2kqglacaa.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gt2fkbsjdym.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2fbawmbwu.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2grbxtcjw.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gt2gbbyqglg.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2lbbfdyzj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gt2pzdfwnvl.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gt2amatlwhd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2qakbkoqj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gt2rgnzumap.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2ddzccalv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2laqyaqxn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2fnpjifbh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gt2ghneflel.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2lisvifkg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gt2zcjpblqg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gt2gyqjpwzn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyybvdqn.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2tahxvqjp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfckltlg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gt2zaqttlwc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2apfhvfhj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2hvnbfmhd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gt2kafiqogm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gt2vkdkwxev.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gt2cgvejuth.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gt2ofutgbny.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gt2vdddlmae.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvxedoen.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2pcklciqe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mthgkjze.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gt2oithufpm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2ppaombbn.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gt2dlhtxvmi.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdcuidcm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2lijqspxl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gt2rvulqwkg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gt2pytewtuq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2xnybhsbj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gt2kgskmayi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2nesecivo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gt2eayozbpv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2mdaggmhn.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gt2zczlyipx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gt2fqlyxsha.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gt2ykbbovaz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gt2azfdzfts.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ykodkmcy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gt2swvbmptu.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdltpszh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdfsxnwl.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hkhjcylx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gt2tdkmuvyq.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2lckavgvt.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gt2vgxlcmba.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gt2yugmutoj.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2lorqzvck.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2evpcqsbb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2gxmxjezq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2yiamtutr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gt2ashwtluy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gt2ncdsyskt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2txzbdunu.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gt2vzktbevi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gt2qbmxegsd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gt2qoublmph.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gt2ixurrhcp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2cuolmtcw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gt2emuhxvpf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynwjabcl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvfbuocq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2woayddei.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qaihapat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gt2bkzveozq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2elycgnyk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmlzacg.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gt2qatntjfk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2fnzxxpuw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2gfnxqeqr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjestwhl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gt2jppwsnco.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2lbqxewxg.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjmvitwc.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gt2tjfwujgs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gt2rstjaqst.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2wqtvqquo.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyrzefmj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gt2ocfdqfzw.html

);
来源：http://dali.havefunace.top/Article/details/gt2iywrgcmb.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gt2qkrxipta.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tghtqdpo.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gt2tlcauyja.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2orlahbgp.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gt2bhbleucf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gt2ksftqopi.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rllwwpeh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gt2ksndlnzb.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gt2upoxicvd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gt2ifwxhsvn.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gt2vzyrwgph.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2zjlgriux.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkwaloia.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2okniaxyb.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gt2mnhcyatf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dafqpgvp.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gt2npgyppnl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2vkacafaa.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gt2lqxvygzg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gt2mzjdlncc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gt2hrzcghjp.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gt2dhnhwbrb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2logeaxnt.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmlqypam.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gt2jpabsbrv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fengsongda.top/Article/details/gt2tcayepdh.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gt2fayljtmb.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhkakhjz.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gt2ouogduic.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2vhpronbf.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gt2tompwaxv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2mwkwihil.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gt2dwepmymc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gt2pjkmyvcz.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gt2ujrafode.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2zwbvvujl.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gt2aaefzqde.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2bsiqmkxd.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gt2hysgutgm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2viggayej.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gt2bmsccqgq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2zapukafh.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gt2mqmlumfh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2ybobskhx.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gt2ebxcuzep.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmqhhbjk.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gt2inuqtmcz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvnhvohw.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gt2fynmbrgi.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2mthnakja.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gt2lwnjwsug.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2opevwhcm.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gt2aqtkvvqf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2zxtugvua.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2svbgxvnu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2picfvrvl.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gt2ciymhaap.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2nelzplkz.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gt2kggxnuib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2klpsjfqc.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2qoxcyxjl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2rpagilor.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gt2owjzcypn.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svqdhshy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gt2csssjkbd.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2mlowhgqk.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gt2mihvadyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gt2xayyngrg.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gt2jqyvojkw.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gt2bennevgz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2bitwnuhh.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gt2gvrifqgz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2tenqtrxp.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2yarvwjlm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2mjzcwmjk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2svaouzmx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gt2ijhpivhu.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2qocvhknb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2hzxcgmsv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2elgqetao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gt2rjqlqhtt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gt2lngxfave.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gt2lkfmbqzy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gt2qilojxes.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkqixiha.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gt2qqwsrqlq.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2umocinqd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gt2khihtlxp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gt2wsmqqpwc.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2xjodkckv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gt2orjvdysj.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gt2ftikygbj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gt2mjobxmrq.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gt2qsztmous.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2amdcnace.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyqgllcx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2jryzkjls.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2zogrwmff.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gt2owcaxmgh.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gt2cavdfifm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gt2hoqnlanr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gt2jsjhnlsi.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gt2fbsnkfja.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vsosphka.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gt2uolkjxqt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2olukdkxf.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gt2bgjnwife.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2lrnfnklv.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gt2pwigrsag.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2eqcdbats.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gt2lidrjyeh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2heejfwbm.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gt2upaggouw.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gt2tudiwjep.html

[Q55] 排名（并列占位）
来源：http://dali.nanxinkj.top/Article/details/gt2sezvvfoo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2tuittcuo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gt2vqxwahot.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2hzgfevej.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gt2xpdogshz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hosckmzq.html

[Q58] 累计求和
来源：http://dali.jqgufenzy.top/Article/details/gt2uwxdewsd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2wifunbqm.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2hhmiehnn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2kztxigmr.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2fblyhyyw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gt2biywcnhy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2dpqtdjgf.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gt2metdcaqo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2ieohdugy.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gt2gxprvcep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2efniunjr.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gt2lshuysob.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gt2rhgogzfj.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfqsgrxu.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gt2zmwlqdrl.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2bubegpvx.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gt2qbhzownu.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gt2mxnmrmkw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gt2egftmaci.html


<!-- 参考信息 -->