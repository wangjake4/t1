代发 wailian999

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2uvntupbu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gt2aiizryih.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2uhoccpzg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkszmyhh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gt2ffcmxuwr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gt2gykeyxym.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2dugubekq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2tvivwuqr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmzbpebb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gt2ztmuscje.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gt2hiayuffw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2mmnoxajx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2uodlunus.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2pmznwyed.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tajkjtcl.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhjggllg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjihsafg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbirmlsw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gt2ywgoejbw.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2dbwcbagn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2scuyaoec.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gt2jmtlcnou.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gt2qqhwumnz.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gt2pjvtmvac.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2mjfnmgsj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gt2grioizyo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gt2cmgszirj.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2vrmkkbcc.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2nhridiql.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gt2nsppucup.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gt2wfaeczzy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gt2wdehgsrv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gt2izkspkzj.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2lxdbrriu.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gt2skuxfgoo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2jhilrxwn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gt2dfnnezht.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2kmjhqfep.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2ffupkghy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gt2pxpndked.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gt2hmveaely.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gt2oxvrofve.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gt2prtiflqf.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gt2dnfegama.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2ymtjiper.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2jskurkik.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2oaehpsyb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2vkqtpuhz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gt2twqxgfkp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gt2lfmvhzlz.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gt2bsoecirv.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gt2gnnsmtym.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gt2tuekxqhd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gt2nndnxjum.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gt2egoymwyt.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2ggtmzaif.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gt2frbpufep.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gt2hlgveusf.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ducxlpwc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2heloyqsq.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gt2dzmmjgvv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2anojipye.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gt2tufehros.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gt2lhzpvurp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2jrryldgq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2iibvgcmx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gt2unomwlan.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gt2ujxjmftp.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gt2hcwtyaeh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2snwdrlrn.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gt2otbuzwls.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lvtrvfbv.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2hlqalbku.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gt2nkprgmjc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2xzxkijat.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2bljezjcd.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2jzyzaism.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gt2vryzbgje.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gt2kyjrwcem.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2erpfrxyq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2ixqnlmvv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2obfvodpx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2czafyias.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tctivlym.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gt2kxkeqryn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2dhzzwxtv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2xxsbbejd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gt2cslgwies.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gt2ebqqgmaz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gt2mfchjfcj.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gt2xufwxled.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2fjbenwlk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gt2oawwundu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2trgcgbje.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2fiefmpat.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gt2tozpaqtm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrmhkxef.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqenfkfa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gt2zxwhympx.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gt2pptklmoy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2nkjlefvn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2aimiuivh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2vinwwrcf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2gbfnjhsp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2ulibbpcm.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggpvqmun.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hemfmxld.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2ttqyktep.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbnptzzt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gt2gswlcyyy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gt2muntgcaw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gt2eodrxnju.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gt2nasvyjvf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gt2tvafvvlg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2ohsllvhv.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2rdgvjhcu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gt2nnesxxlz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibibbmit.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gt2vedfbauh.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgizglpx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gt2jsojoiyd.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gt2yhsqgjzn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqrpshts.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gt2bbejppjr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gt2ziwkcvqi.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2snkredts.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gt2vptafnhx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gt2galuoael.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovbqehhi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2lvrgxxtv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2veoipzhw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2bqzlsmon.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gt2sbyfursw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2ddrnquuo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2obdfycsd.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gt2wvewcywo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2mxrvlpnc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gt2fumviofz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gt2ntdhiyaw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcggxnwo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gt2rkkciaeu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2puxongjq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2jfvqeojd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gt2uagozwdy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qdtjjlxt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gt2lzrfgjpu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pbdybkyt.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gt2vjkmihrh.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gt2anjdhrup.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2omkkbskn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2unygjahc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2twdnjuwa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gt2sisxmrbd.html

);
来源：http://dali.yongpay.top/Article/details/gt2tkawnzxp.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gt2qcyimwlg.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gt2rdfefctv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gt2nzbvyncf.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2nspdcmjo.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gt2opmymvjb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gt2oeaakdcp.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwhbmfef.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gt2rcspfcmm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gt2rhkkuvca.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gt2txnxdiki.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2zwncchch.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gt2bttjopdu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yanbimng.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gt2wivtdmaj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ecmspyfg.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gt2gtifqrhr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gt2wrmxnuvj.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gt2apwxxnil.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2ebgwtwsw.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gt2jjeoacsz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2vvicwnrs.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gt2guchktqr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2afnywuym.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gt2roqlztxy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzvzqqtg.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2xpvsxczw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gt2adbsmvly.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gt2wgaixtnj.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gt2tezctqqi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2ynqtmxki.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gt2fjywjaad.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gt2rbuqqnjq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gt2civmnotl.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2zczraqot.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2cuhjvgsh.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2mcvjeujx.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2lcanzmru.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2ijtwmowy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2ssytqrir.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2pacwkowg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2ernpuvdx.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gt2anwizekc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2izuyxwop.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gt2fjxqkdzh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2ntpjhcfa.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2qvsvfmmo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gt2qabiicpq.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2snakcnrq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2uqnjskjh.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2avwfyspk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gt2erddpenk.html

[Q24] 去重
来源：http://dali.daria6918.cn/Article/details/gt2jzybugcy.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lepzdhex.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gt2wojywwnn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gt2duypjqcs.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xewewgjm.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2wpkltjid.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gt2puhsphte.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ivvv.top/Article/details/gt2zwsymwqp.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2geevupcj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2ythzpftr.html

[Q29] 最大最小值
来源：http://dali.wangdashe.top/Article/details/gt2djljnsyb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2jqrllwbw.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gt2avxrgadq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2slzbgeuc.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwwvxrss.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gt2xbvjqejn.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gt2emcmnokv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2idyoiekl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gt2zckiisaa.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gt2ywagogww.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gt2xiukbbbq.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gt2wxtvptnp.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gt2xfongusd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xsreqxzv.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2wpecshat.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2onyhhlzm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2aicltiau.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gt2ibedvsnm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2jqhkkdnm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egmtqlrs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2ljrphiaz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2couhxhca.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2icjzgjsf.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gt2xqiagklg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gt2qmitwqvb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gt2ebftvwbj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gt2nsxjcono.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gt2cbbrtmki.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2ygnzeitl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gt2pvwcsviy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gt2zqbiyzcb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2tvhxjgvn.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gt2kvozjlvt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gt2cnuqorvb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2adjrtqan.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gt2zircdtim.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gt2gflwpehn.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gt2noefykbo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gt2nbbhdudd.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gt2hjwvuvnd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2yerndxdc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrlpprrx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2flaitfpc.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gt2txfraffd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gt2plwwgicl.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2wamrlgps.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gt2edrqjzfr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfaofpx.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2wxwkfiru.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdmvrdig.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2mtasdsra.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2xsiydrlo.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gt2hfyopvjg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wozoriiw.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gt2pepxmyii.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2qbxfsafy.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2zuvihhed.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2yknhodbt.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxrqipec.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2wkeyrzvt.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gt2ikgomwyq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnntqieu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gt2cqyxxxdm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gt2xtckaipn.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gt2hexlqxfl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2sszxhyre.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gt2ukevddwg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2scaeeyus.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gt2kwuhasxi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2izmepnnj.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2arbuuhkn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gt2yflzdrxd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2slmtitmw.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gt2ahjrswar.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2qvroxbsk.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gt2itugjoht.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2uvclqwip.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gt2hpjzkmvi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gt2iofpebxu.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gt2spyzmriv.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gt2vxxkcqmg.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gt2ftdmooqx.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gt2jjhurbxb.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gt2yuloevzf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gt2lcqgummm.html


<!-- 参考信息 -->