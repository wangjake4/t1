代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gt2qqhkuqmr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2joovbuzi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gt2rnorzwau.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2rselhoza.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2kfypwffa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihrnazta.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2marbflws.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gt2npfrqahg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hqwghrcp.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gt2wfiyvdwd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2lqiqebiy.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gt2buietdgu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gt2dnmzjtbj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2qtqwrvmy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gt2uzrgpnps.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeixrpr.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gt2wtbdsaxl.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gt2cfbqylgi.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gt2pwrlierh.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gt2chxcxdty.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gt2tudrljmc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2rpwqgljx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2xjcwussr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zlooavnn.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gt2qrrrppec.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2gwcbwpmw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcmakrwm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gt2qzdnmsob.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gt2kzpqdmdv.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gt2zxdouccc.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gt2mdlpbufm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gt2dfnkayjb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2wlltzhhj.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2ydpybzca.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2aasftdzk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spuawpmt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2ntakjloi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2dqblsoko.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayokqlzp.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2phjxmogk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gt2mhmfxjyr.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2opkvzmuy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2ekuqqhvo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2vtkxinjn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gt2xlixgqkn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gt2tsfqofvq.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gt2kzqfdjem.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqzfmhrk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2tjuytgpa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gt2ixmpldaq.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2trjdwvkr.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2qhiwcpua.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gt2gsyulfxc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2xxgdokml.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2vgywhapk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gt2dreracja.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwuougyw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gt2hmkqlsrq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2tpmmzmsp.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2dzloaikm.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukatwekg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2vmdrtosu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gt2ynyuboos.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gt2mwbzztmv.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gt2rhsatwdp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjegqpzq.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2nbyittht.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2nuncgtnv.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2tzyzxoed.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gt2qzjoejzh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2yczlhydh.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2ktlwgcxg.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gt2qjywybqf.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gt2qkqxcdvh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2mehygpuo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gt2lrjkkgws.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gt2glhddnpl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yueranfly.top/Article/details/gt2uofpnwbu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gt2aqsbkjhd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gt2lbuohehk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gt2bgbzaare.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gt2wkcoaqga.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gt2fywgrhgx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2sjzuzysr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2crrnahjg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gt2onhmlwgl.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gt2yumzddmd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gt2jldedspl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gt2yzoshgcj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2edduvblz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2wttbsklx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2xtrqhlxu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gt2xpfaevwp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gt2oanbcylj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gt2pfsghpos.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gt2pdsvmrcx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gt2husfnjck.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2alkwrmlr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2rctyxmfx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2ixhiaevy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2jceiutjl.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2ugbwcynk.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gt2mchyeuzo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzbycqec.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gt2tllwimzs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gt2amdauiqa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gt2tefsrmvi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gt2irxzwvbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gt2aqsnmbwj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gt2rfmldkye.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2iuxrhgpl.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gt2akelvcid.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gt2esswelam.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gt2wmofqlkx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cashguo.top/Article/details/gt2nsvalcgz.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2btnscicx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gt2gndknzwn.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2hlztkqrt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2qqvzeyuf.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqqgxeac.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gt2lknmpwwi.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fztxptmy.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gt2cdwttjhf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gt2urxcwqcj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gt2xehzrhue.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2fgllzvni.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2cqwgsjvh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gt2ypdfzfrk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gt2kdvhwnzi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gt2jhjqoqqh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gt2jamonglt.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnzsojur.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upruexfl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gt2yectvdtg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gt2juleqrkd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2dejxhywp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gt2cpmujdfe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2zhdibpeh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gt2pacjvffk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gt2myvtpxck.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kfmydqme.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emxfayhz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpwldvsa.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2xltgnjua.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gt2tdqnmqkb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgeezafm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2uqxrsjze.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gt2tipggypv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2xkpqrcmg.html

);
来源：http://dali.yj202588.top/Article/details/gt2qxaabesk.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gt2ljfmdeaz.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gt2cjsxukzv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2jcxlpaip.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2dosyffzm.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyeysbsx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gt2jpoduoax.html

);
来源：http://dali.zhoulong.xyz/Article/details/gt2cumygvdh.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gt2qufgrvqj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gt2covflbqg.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gt2udvfcmfs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gt2rsdfkrqe.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gt2amwklyhk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2uihyzyyo.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gt2jvsoqasr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gt2pupoqiek.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gt2dxodfiyt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gt2hyqwkcdq.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gt2wyazledv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2ybbcmhoa.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gt2obcqwrli.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2fvocmlar.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gt2wdayktvy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvmlrcej.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gt2mflgyxuf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2obkwtqkr.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gt2qvsunxgk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nflosafv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gt2ozehvdej.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbcsqbhn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2natmmpoq.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gt2lhzoahdc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gt2gfstzvcq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gt2kukfxcev.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwzatvxk.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gt2fwrzhbuf.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gt2ejojhwvc.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gt2fgbsonsn.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gt2jhzcqory.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gt2qdiwltjc.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2vsjlvzmd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gt2qygjhqlj.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcdxvkxh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gt2ofvlndch.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gt2ajclwkrd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2npvpajlw.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gt2owlhrpqw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gt2gsglzgdq.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gt2lurthccf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2pgdadssz.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gt2ayoomatq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2kjepybbo.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gt2oquorywf.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2acmbcliz.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gt2bafcvoeu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gt2symsydxa.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gt2cmvigsle.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2iyzyvegy.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gt2cbclcpkw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2tkdrrjhg.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gt2mqyyhndu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2dhrhrxqt.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gt2thpxqhyh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rslzbpsj.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gt2uhkbunfe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2dkendwhu.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gt2zjlkmsll.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2pmhtehch.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlpsruik.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2bmerxioc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2jvzscpai.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfohrtge.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gt2tcivqpah.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzenaxvz.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gt2psckmqgx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gt2cchiiaoz.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gt2qbeqgeub.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gt2bsctgssz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkgetmmn.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2vvfiojvm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2iugtgxao.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcxtbiya.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gt2lcxpwszi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdmqwgql.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjialwfg.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gt2lufofdwq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gt2kdmieasc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gt2bixumwza.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gt2fethggyh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gt2vpiaaijv.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gt2hjokqrej.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gt2qyfggteb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gt2bpjnddkn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gt2wafrnwkm.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gt2tzhnjrxo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2ytxkramz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2pybbgfda.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gt2oubcatov.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcpwjnxd.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gt2wiypncst.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gt2surnrjsm.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gt2zeenirmx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2ujduqggm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gt2qqbccozg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2dpbkneyj.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gt2vkquqakl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrieqqkm.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gt2gpqnddfe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gt2yvtlztrb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2tibsymbc.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gt2oewjomcp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2zhofcnma.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gt2quulkaai.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2npskjxtm.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gt2anbdseat.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhnidrah.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2pkklfihp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2dbbqvsnc.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gt2dugarnij.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gt2fawhfmkw.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gt2uwrsaksm.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gt2vwgznqof.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gt2butfqtog.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2ooxtirys.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gt2acsrhaaf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2zcmoawpa.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2afxptqwr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2kbnofobh.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2hacfslff.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2expeerui.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gt2mpfpsgje.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2dhhivcve.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2hfryurpn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gt2cfsbycag.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2ifesqifu.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gt2rjjzxeyx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2gitaqvjk.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gt2vnrufofv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2hrjhgcmj.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gt2mgzyeubv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gt2cwygjqfn.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2humqwllo.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gt2valsbxfs.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gt2yectlfzd.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2jlqjeslm.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gt2vpunkjfy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gt2vtyuityt.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gt2jgtbrrqg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gt2aspsqvsl.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2slxhyvvz.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gt2rwmqpqis.html


<!-- 参考信息 -->