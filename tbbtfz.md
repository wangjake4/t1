代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gt2pmbdfbuw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gt2voyxoizg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gt2dgrutmdu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkacefts.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2cqryejcm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gt2icpfonxb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gt2otjeohjj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gctnbqnt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ayrboyug.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gt2pzwcyegh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ugimfens.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gt2bbfgqbat.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gt2hghgcyuh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gt2ubsyobpr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gt2hpjqpaxh.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2edooagcc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gt2rbwvgwyv.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gt2tpmhdkqg.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gt2wrmnwmms.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2fzathzcg.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqjwlfch.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gt2lmdfqwxg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gt2pcrluakw.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gt2azkukpla.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gt2nvlnukvo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2modcljmh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gt2fhqrmkub.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gt2mwavwspp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gt2wjilyvoh.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gt2fstgohoq.html

Py:   with lock: shared += 1
来源：http://dali.zhixingplan.top/Article/details/gt2uwscgrkz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gt2omexavux.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gt2axlozdvv.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2ckbjfifn.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gt2igaeiqsc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gt2wgwliqmw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2ziirpgdm.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rhzgllaq.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gt2jpptlxan.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2flbclvdx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2ckgmcrnj.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxwxzqyh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2goeimgtp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2zvxpozvo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gt2hfwsqbhu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gt2rvjzvvch.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gt2afisizcv.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2ywdupbxn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gt2oyjqujpw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gt2onyupsgp.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihrzuyiz.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2hhsvnzyl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qthyeemf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gt2cpnaypfq.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2swuhwoyd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gt2gqvzsddc.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2zhoknrsm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gt2itkylpqj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gt2dqsvnvyv.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2pyagaivc.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2lhckgfac.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdlvvsel.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gt2dcttedju.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gt2ydnpwgym.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2rgnigwhu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yfyjtgzb.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggwcvggj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2uuvfunxx.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2kguxsoxr.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gt2kidvmxng.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2keztckyb.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2vhjbvoje.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2sisowypp.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2lkjpbgoi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2lqvkeaqa.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2altyqidq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gt2wosfnjem.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2pzmelnbn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2cihmmwvx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gt2lecmqhyk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gt2kxemxjmr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gt2twcjeeic.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gt2ddxyzdqy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2qukjtcbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eappujsq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2lhayxcwm.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gt2mrmchmby.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gt2skgbgaup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmhzjfvw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2yhqjzplt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2icjkkbgx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmkyyigf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gt2akaowalm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gt2vpsawxbf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gt2juhpodtt.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gt2gptjyzng.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gt2tknjxpbs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2rzjejxag.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2lnaaeylo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2ffjmqbmo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gt2ghojsgac.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jadjruet.html

Ruby: x.length;  x.size
来源：http://dali.smart0.xyz/Article/details/gt2hiwraybg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2wlsdmfbh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gt2qfqstjli.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gt2flnaezba.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gt2ugmlvhdl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gt2banwkngz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwggairv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gt2csopbqpo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gt2lwsjvlrn.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gt2mydkrdkb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gt2yzrxgcai.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gt2sothdgkm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2hyxcfbaw.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gt2hiwfdzwr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gt2mrawoyps.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2peixvvvi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2omvdqyll.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gt2ytcorprd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gt2uojbwoqq.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gt2kywiysij.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2iwjyjnvn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gt2xvteyoar.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vonlkbdu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2hxduhrzh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2iphoscvd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gt2spbodswc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gt2sbccudcl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkmnalhi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2ynpgnjft.html

[P08] 处理浮点精度问题
来源：http://dali.sysykeji.top/Article/details/gt2agcaaecm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkaswpsn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gt2rcixgeve.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gt2ghctdgsu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gt2lryuxglr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gt2qbiiclac.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gt2zfcbjizn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gt2lwyswkgi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gt2cktzdhii.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2alvfrnuz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gt2wrwjyxoj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgxcpsth.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsmachxf.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gt2wwfejffo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2yudhazxb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gt2prdpwoof.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gt2hagwzuoa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gt2jiiztmoe.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2cxxgivdf.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gt2tozbtksp.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gt2xmjftune.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2xqdjtalc.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2ejgohmwr.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gt2sumomyzq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsfsagpp.html

);
来源：http://dali.guannengcc.top/Article/details/gt2fpdwmpot.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gt2mvaqmdpa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2evxqxkxo.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gt2eddfzopa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gt2aqfhydqu.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gt2sobtrogm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptzjzqqx.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdkpgaco.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gt2nylytvzr.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktoyigdd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gt2orpmimzw.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gt2vdosonnt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2qewepvfe.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gt2abfgwxfa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2cddkgxgo.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbtliksl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2kjwwnkoc.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gt2ompeunvo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gt2fhtmwhvk.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gt2obhhvypc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.mhx1999.top/Article/details/gt2uxskfbzl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2dyjtrgvd.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gt2rogtaofb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eipoeesw.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2prsddnif.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gt2vbnouomc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gt2ffnblltd.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gt2jijgqqpj.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2qgbrmkrs.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gt2byerqsbl.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gt2kjmxfmrz.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gt2dxlpopin.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gt2wvggisda.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2kdmzpcly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gt2lwazuoxc.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gt2nolwuceg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gt2xiinxpmn.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gt2gnlybpcc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gt2ddvsxgdw.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gt2apuhlpfc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2fnpjhyjj.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gt2ffdjovdp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gt2kzzpmuzu.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gt2tjfsvowp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgbooucn.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gt2spkbxkdb.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crdouows.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2wpbrvnjv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gt2oixbbwms.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gt2anzyvqig.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2mcugdegv.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gt2bbggltzc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2hyxzyhko.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqczetb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwxcjckf.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gt2ojioxzzt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2svjmycme.html

[Q30] 分组统计
来源：http://dali.yvedp.cn/Article/details/gt2jytrqxll.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2pgvfiznq.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqkotpsn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vniomkcv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbfwore.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2nerjjzqz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gt2aieacfhn.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2pnjevagd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2xgifhoto.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2kdroproj.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gt2cucxxpka.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gt2zsqzvnoo.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2ohlqjaxd.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gt2blydrool.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gt2ghwpmcqo.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2wzvbiqox.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2ukienhbk.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btysqblx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2wwfkefmy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gt2zdybkpsz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gt2vtoqnljf.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gt2tnqrkbsu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2uyxjbpsg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gt2equhrnow.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gt2shirwvwu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gt2ovjdykid.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2xsqanoep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gt2fnbjfsqu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnbytik.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2uocrgkfb.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2iujajnyu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gt2kikyklaw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2ouaagqml.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2yqpvtmrv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gt2dpvuoaxx.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gt2tabschcu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gt2oyzinyyy.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2uhvgxcoe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2nvphgcow.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gt2wyhjdeaq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gt2pdjfjhex.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciplnjyn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elfcgazp.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gt2chzomayb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sryhfmjy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gt2dgmughjp.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gt2hsrqhwiz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2zzzvhijf.html

[Q50] 批量更新
来源：http://dali.c1oappe.top/Article/details/gt2ggjaonhj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2clpyjlpq.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gt2ikaxraya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2tkrtctps.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gt2xicgtkvy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2jqksrzfa.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncnvqexs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gt2vnujmbys.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gt2mezagzfa.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gt2thyvndpd.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gt2ampnfocd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2auzdsixj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gt2fplnsodv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gt2ppyduurh.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2gcilijjo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2khcfuolm.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gt2kfcmeeez.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2hwvvtxdu.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2kzrouwxz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2cdpvpfhz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xunspmnd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gt2btbovyob.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2ulwxtgti.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gt2qwyyclqf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2kteeabtt.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gt2qwzkeffp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qysgesfg.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gt2cybzlfck.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gt2seqdkwab.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gt2vvcdopta.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmxyhjyj.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gt2mhkeqana.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gt2bbrvkbch.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gt2sqvybodt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjaoubcx.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2awvnpyiz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gt2kivaommr.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gt2cojlcysd.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gt2idaztuhb.html


<!-- 参考信息 -->