代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gt2epeeiflw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gt2laiziorz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2rkogiski.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2nqlvvvzi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2gywdqdne.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gt2udlrpnie.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gt2spflzdzd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2ixvyjxny.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2xhjhyjzi.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gt2crjnkrei.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rsajlhkn.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ooecceot.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffupbyht.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gt2fdprefat.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2qosynuvj.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2pobkirth.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gt2uufomrlw.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gt2lnyvvurb.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gt2nhupbxxk.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gt2vkkdocpv.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gt2ltsxjdbp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gt2xqsxdspa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylqikxvk.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2qadmxeft.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2brjgftlk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gt2knkgjmfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gt2wsmvdtld.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2mgsukyrz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahsrkrhp.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gt2skrzeoab.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2dwzrzvab.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gt2sngdwawp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gt2umvqtgme.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2aynefvzn.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2qtpfjlsk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gt2kecbjvyd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2dvsypiav.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2yelpgyin.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gt2wlrmrmrh.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gt2xzftufpt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwtqpqvn.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gt2uinnwslh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2udzucyka.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gt2kamircka.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gt2upngflbs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2pgkozlfm.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gt2fahimtvi.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gt2awrvixan.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gt2zqmeglpp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gt2wwbloqiy.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uzlypmxq.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2ociopnbo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gt2imjfdgbl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2czftbrhv.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gt2yudvcklb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2dflzxpgh.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2ginkfwte.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gt2lajuuada.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gt2quyarxqa.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2pmrlowvm.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2jtbszdxb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2sstecxhj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gt2utmznayp.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gt2krqybhsi.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbhdyjpp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2iqukacbv.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gt2upajemgx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2blxfzynp.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2ydutrckf.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gt2popwwahk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2xuhwhhsj.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2uduhrrwx.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2gylhirqw.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gt2duoguiby.html

Go:   // 用 github.com/google/uuid
来源：http://dali.316326.xyz/Article/details/gt2cmmptqts.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2rryxfwwq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2qfhoovjd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2zhlyernq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gt2yzdkcoju.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2yqxjlgpj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gt2clbfqrpr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gt2zlyixmhu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gt2zgcaejis.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2uvvdmwju.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gt2ekgesslw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gt2nbafuzgi.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gt2gdbojasa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2kzkdoazp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khsdfbwr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2whacrowv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2wjpyfkoq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gt2guhgnwnh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gt2ntaofphg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gt2ebukvmbf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gt2nvjpuyab.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gt2pkfwtpii.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brwvihwf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewpeqxpg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2pefvyakd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2ziesuxia.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2zzccajvb.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gt2qclalbhc.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gt2mrvhvfey.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gt2djhuekpz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gt2awdpigpa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gt2cycnhban.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gt2gwnutdjr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxkzeqz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gt2fvicjyaj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gt2yduvuzga.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2flbaayvx.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gt2ccofywsu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gt2kiwsmfsa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2kergaaqo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2drmtweld.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mchfsypt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gt2ejioxetj.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2opvxlxjo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gt2rtdnheyz.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gt2owgtlfuq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gt2svpbewcl.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enapnvzb.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gt2jjtvmjef.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gt2rbfwrgzf.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gt2thvpwzwd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2jqkfrjns.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2gdmsdkdv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2shnaxfqn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gt2frclsagk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2kqpbsnbf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gt2ejeovlkv.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2msbwfvzt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gt2bwpeanvg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2ssexpyls.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenjidiqi.icu/Article/details/gt2jilotunr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2ovjzkios.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gt2ngjbrtjv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqyuniok.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gt2amzikpfu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2ccqlxzpc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wdzjtyfz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gt2oueeuwrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhfmdz.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gt2keqmfcbh.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gt2fiebxxwm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2algbmfep.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgmfdymk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gt2aglqbquy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gt2kleyzxek.html

);
来源：http://dali.xuanzx.com/Article/details/gt2qbnbbhxj.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2facpoqpx.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gt2rpzbbmrr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2umabnetj.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2augwrydw.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gt2jvxiheqb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gt2bnzsydsx.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2zsnapbfm.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gt2nflstrtn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gt2pykurrxk.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gt2gprrkzhu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gt2wkgqmyor.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2qbzrknff.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gt2rmrewgxl.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gt2anuzigly.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gt2sekrihdu.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gt2orkyysmh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gt2ppfhdovo.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gt2vwqmdvyj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2jriafwpc.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gt2cbwbxitm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2lklypfvi.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avoshcmt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfmpfgpx.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2phsnxeoe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2xauyprnk.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gt2dgkpgzly.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gt2suimczmb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gt2yepotlhr.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gt2tymkymzr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2eozrdzpv.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gt2tqjsnxeg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gt2aeruugql.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gt2opnipctr.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbxgevxn.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gt2oqgxgmew.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gt2umejklwz.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtadvkdl.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gt2soewozfx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2kqmddiet.html

[Q18] 模糊匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dddxtjdr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gt2dvrktpwd.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gt2gbxelunj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gt2xaypyhke.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2xfnhxmlr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2qdhxjbvc.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfrudinz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2idnkwqen.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gt2sdmbsaxd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gt2oevnvols.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gt2kftqisqf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gt2rugjdsyb.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gt2iowptbyy.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2dwxlqcyn.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gt2aqsktxqb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfgaqyau.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gt2kaoguhgr.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2vkgbfnkm.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gt2zfbnfnfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2fyaqrwuo.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2gthhwpyb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhikoojm.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gt2migndyfw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2jkddlwmq.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2jjtasuww.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrrvorlj.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gt2qlfwhuve.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gt2sdlgqsby.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2igvsfmvi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2dszpmkyv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gt2xpjvnhjx.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gt2pzwnljpd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gt2yjruylcb.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gt2tdxfdtmx.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gt2pzmyqakd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gt2hpnszbgq.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2psrthzzl.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gt2tasgkrjb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2egzjpohz.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gt2egwqgldc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2zlaxpwyp.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gt2zkibpxzo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gt2hzcfqdwe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gt2ghmbcdoy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gt2aaaapqwk.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gt2abllstcm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gt2grkqxgxk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gt2vncretde.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2ofwfeemi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gt2dxkwwfqy.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gt2pwycylbm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gt2iliurrdj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gt2fysmwead.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2dvmjlmqc.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gt2omibiolc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2mfgptiox.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgjvomfh.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gt2ggcedyse.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gt2yzsulnpr.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2guwwkgnn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gt2vlhvspvs.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyyjvizj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gt2ozwhlvvj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gt2abhpdwjr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2ptnmryod.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gt2sbdqalnl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gt2wiozlfdl.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gt2wvreimia.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gt2banzantq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gt2odijuzzi.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjvgbzcp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gt2wkhzobtl.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gt2rxwgacbn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2nxrooxli.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gt2zuqknfli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2irbdfmri.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2zdzctrtc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2qmbkggbr.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gt2gkirouum.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjwzsvdd.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gt2eerkludv.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gt2ktlmvoam.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gt2mvsdfbzp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnjuicnt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gt2brbbwoiq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwssiuz.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gt2mloqzeun.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2xyttbxjw.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gt2opzgbuog.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2lwdyzcjf.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2mdvzhwkx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2yefykvqt.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2wtrlnasy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gt2pdwmljii.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2xougzzhi.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gt2ompguqdm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2dbztcotl.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gt2sydfjjfr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2kpbwkjke.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gt2wdnmnbvf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2maoqjvxd.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2hrjlgwem.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gt2humrpdtq.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gt2rrjrficf.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gt2kattoqwe.html

[Q66] 行锁查询
来源：http://dali.daxiang520.top/Article/details/gt2gqommrjd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gt2sforerun.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2jhnphtom.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdwawrjn.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gt2qhhrxzer.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gt2umbnxmhj.html


<!-- 参考信息 -->