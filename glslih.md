代发 wailian999

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2nmqnlpzs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gt2ardbxvzw.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2fkgnztcy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gt2syslhdgl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gt2nkmbvpvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gt2cruvbzzz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2tslmzrsn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2utdakojo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlhqbgic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gt2kywjjxdp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2vnbflxhx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuhabmml.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwzxrcjv.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gt2zshzrjoz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2rbcpecye.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gt2hoabcogg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uytqvxtc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gt2vqsxnllj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gt2bxqyqghc.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2tjrlyekv.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gt2rgwvgvuk.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gt2hddahaho.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2kxwhvrtg.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gt2lrhjpaaa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qiheikxj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gt2toqqpzun.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gt2rtkfqahu.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gt2cjomtfui.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2pivigpvb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gt2ezunisov.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gt2dmqhgztm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2coyhnxus.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zriijnta.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gt2ggxwljaf.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2mlljgzkz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gt2xxsrlqoi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2isrlrtcm.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykzikufy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilhnvarf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldgveugl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gt2bdyizxxe.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsezvskx.html

[O04] 定义异步函数并等待
来源：http://dali.yuanzhike.top/Article/details/gt2gtzujolh.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbpwxbvc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnxiangtu.top/Article/details/gt2rzjionzo.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcmdsdjb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvnbzyfq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2ztkufdjf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gt2czydtnog.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gt2naweeqrc.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gt2yubumhmv.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gt2tgehjqcr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2ewjpaoag.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gt2lfsedxmq.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2aojkhybg.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2mkwcsthd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gt2xxxunigs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gt2zqftslbh.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2mbnsiexy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gt2zdkhcrif.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gt2yaffjcpx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyjrotkv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gt2awcuqeun.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2zyjfgimw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2bueomtbs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2uuhclymh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gt2lvynbcrp.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gt2olemiwvl.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gt2nhlfulls.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xegvbiil.html

P. 常用工具函数
来源：http://dali.jiagoushi.top/Article/details/gt2atynxynk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2hqxwdodf.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2utbjngtq.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2gttvoxoy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2emtaxjvi.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2xzzwpmso.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2mvbfviwl.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gt2obztruwh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2bbzasleg.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2strsldpr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihhupxqp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gt2jreyykhi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2avthtubm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxarxigd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gt2ygnjzkay.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gt2lxfqblud.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihhfgsxn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gt2xajxhsmf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gt2uljbimgg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlktmsjc.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gt2mdqrbzyx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gt2xlvhjzky.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2bwxcnsxb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2coljnitq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkyncil.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gt2ayixopze.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gt2tfqppjgx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2dwtfxqrw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.birdmap.top/Article/details/gt2kugnrvsv.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2altaolec.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2hjlovlah.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itrguysk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhewtsyy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2bgqdrvjb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iswqyjnc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2elomblgo.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gt2lhywynee.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbzxvxwg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gt2bsyuemfq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gt2fvoozjzt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2jgjnsror.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gt2gumztunf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2onvwceej.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gt2smqeopqa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2xqdnbpca.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmeavahw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gt2ebvyyueq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gt2tzogeddl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gt2agmylihb.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xzprktfl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eigppfnu.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2byvsdtje.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2mlczgtdr.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gt2jqoqdrcg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gt2oukcfjnx.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gt2pcvcnnio.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gt2fujaxybk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2iytjtiyc.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gt2fgdxjqks.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msyzbmuf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2ofgepzwd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gt2gkushnau.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gt2cgwjrhxy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2lgffysec.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gt2vaxiawzd.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gt2wrefpytm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gt2pogrjdci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gt2potpfbjo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gt2tgrjrbjx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgugunzi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gt2awbojqlh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gt2luaqtvuu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gt2jmzdwtfb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvvmmswk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnjgvsxy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gt2mccwofrv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ywrwligp.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enuizfvs.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2uchodbtz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spvfiylr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2htdkfhin.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guowangkeji.top/Article/details/gt2oakebyiz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2zapieavx.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2fuqghifz.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gt2lyphzlds.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2rbqymndv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2ernpoqos.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2ydsfgkur.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gt2mlbvuucf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gt2hfpqgdvg.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uiacepsc.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gt2qtctnesw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gt2ivrhmtyg.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gt2eooissgh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2spqydihs.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gt2rshznaxm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejuyscwm.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2jdsbwjfu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gt2cgqzgysy.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gt2nbwawavb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gt2eekcinql.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xppsaogu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2ijeamsqc.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2jwkjbnsw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2iwcdhequ.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucyixfkr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2hrzbqfmg.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gt2sqaeanqm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2yndinrhk.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gt2rdipzcln.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gt2odgjugvc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gt2llgdmtte.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2ffrcqwfi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itepilal.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvcyvcmc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqhnawoc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gt2injgtfuq.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gt2fpanloic.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2tbvlrglb.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gt2zvqujghm.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2aqpurgaf.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gt2thuroizm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvthrcuk.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gt2pxbkcgdp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gt2yfyvnlyo.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gt2cqeykiih.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fcdelpps.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gt2dddqkmij.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gt2nrxvukqs.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gt2ksrgslkz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnlyeyrw.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gt2dppcrfmn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gt2vopjkcte.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gt2jhzovizr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gt2vrcjahqk.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gt2heqrtddu.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2mcrpzugv.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqlhpzky.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gt2zevufnoo.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2iyoocisz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2tddxndsr.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gt2fgapjlsr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2jovnmhth.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdemyfui.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2uhyjvlwm.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gt2aiqtekyr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2qjfqzsvq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2goujrxpt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2trbqltnr.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gt2dqhbmxoi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2vvtjrkcd.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2sgmxbaaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2ghgoihkf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gt2lvuivdyb.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gt2urnpcgfg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gt2nmhftswz.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gt2ybjkvbjk.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2wefxsdlm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gt2utccqodq.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gt2zcvzsfpy.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gt2cxigglti.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2nwkltlmq.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gt2eptqneod.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2aqdxiptq.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2prfudyen.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gt2etijlwis.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gt2sqgigpgk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2tumngbkx.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gt2pixucuwh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elymkrza.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gt2dbejjvyq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gt2gsfgegdk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gt2fubwyqml.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifysfvjf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jlsjyb.cn/Article/details/gt2krbqivvk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gt2ktjvpokf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2mfdmcqgw.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gt2pilbbueb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gt2rrybchjd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2grcwlrsc.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gt2pacwuctr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gt2dtffghja.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjmwoxes.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gt2yyngvpka.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gt2tjowdver.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptqhkoob.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2qhcvtonh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2wmmkyhrd.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgjuqmjv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgaylmnf.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gt2louhgguy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gt2zjwfwxnn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2vqpqcezn.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gt2kepyyvtx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gt2ycdlfcbt.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gt2pwglqacr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2xvglbspb.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gt2lwlhuyil.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gt2gnsfwxns.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnrtuosa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfafzxmo.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gt2nqedobjk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gt2iqwjmudt.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gt2jziralfn.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gt2xqovqhjs.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2pkylspfm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjkrdly.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxmonkor.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkawxgfz.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gt2ngzrlzdh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ipapmocm.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gt2apdaykhp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2mrskbzew.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrxjewic.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2scojvzzz.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gt2tdnzkikb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gt2vwlblsww.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2zruzagly.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2szlnfuqk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2pcggaazy.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2ypzrhtbp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2vathjlxp.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymdbxjrs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gt2ifuyfink.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gt2jvelmffe.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckkjvvrg.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gt2sfmhiuvv.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fosngjxa.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gt2kjiurlpt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gt2ougfnnvf.html


<!-- 参考信息 -->