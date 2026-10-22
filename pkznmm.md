代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gt2hzkdnflu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gt2igklrlhl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2ahiwihdv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2rogdvvbt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2titwyvet.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gt2rdpydwgp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gt2lxcncoan.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gt2bogooyci.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2umtrlbpn.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2wmtpmbkp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2pynntymw.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gt2lczkfnyo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gt2sdptjmxr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2kkslotbr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gt2yxjvcyay.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2elifuobe.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2bglfenqg.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gt2pzefhcru.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gt2fdvreuup.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2ssliukjq.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gt2fatbjusg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gt2ulmjduyc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2wizvphws.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2sgkslvrb.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2nakrkcxz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2pqsgkztl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gt2msynlwbn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gt2cjxhxhvr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2yyfrlytr.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gt2akailhwn.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2zftodvbi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcpkodus.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gt2wghloyqg.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2xiptppzg.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2pybvjyvi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gt2hsescfyl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2vouucpuh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2acsxcooz.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gt2lksmxysf.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2jmzpjdjv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gt2bigsuctu.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2yumpbhuw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ckskvwnu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2dhvnclsb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2pyjajmnb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gt2aienazql.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2pgddfjoq.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gt2akbmelig.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpdnucpe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gt2qeqwszgx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2kjtvjpmx.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2xcvobwxn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gt2iqawkxlb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gt2dhhisxai.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2rsldifkx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gt2zxiqodta.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2nxjqpyat.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gt2rlzluxnq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gt2pgbhfddh.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2luymtsvy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2rrobkxkt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2pufothhw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2ithaxinr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpsssnw.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gt2jvdtckxk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2fgftqyuh.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2liqekslj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2hbialnve.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2ippgmpad.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2htdwtjae.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2nmpqesug.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2fzxatcrt.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2krrjrahq.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gt2mkrvnraj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2eiijadcz.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2moavwwyt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gt2kcyhnvkn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2mfpeewmv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gt2cbympvbo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gt2qwjljitm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gt2waqjhfsm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gt2venlzfpq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gt2njxdpmqq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hteijreh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gt2fqrgifod.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gt2gnaapqdn.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gt2jfhagmgo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gt2uqubetld.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gt2hgibemvu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2bngmrcwi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2jwyofneh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gt2cxnyethg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gt2uuciplzw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gt2yzqsqkvd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gt2qwcsdzqu.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gt2cppbzyff.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gt2qvwwhjte.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2rgdtlleu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2lmpjasxp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvdljdil.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2jxtizhxc.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gt2wzpyjetr.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2mjskymul.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2bdplcdlt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gt2kkrojnuu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gt2yzzgflai.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gt2gxtxxtww.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2aaxoskqi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2wqahksre.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gt2xvskhxjj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfzfpwrl.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gt2yugpewkx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2sxofayci.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gt2kutbctoy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gt2higqgavm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2fczosctb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gt2wvrjyegz.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2ykvhcefs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2mnjgnlzu.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gt2mpxtthvi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gt2ysfapzck.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2nkchdozz.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ososombx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gt2wuptfrsy.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gt2qgeicjer.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2wncegbbu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2awedvriy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gt2jzwabdsb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gt2qtlkwecz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gt2weysjhqv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gt2tezixcsy.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2saitrhtw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gt2iaoislra.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gt2vybozldr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2lenknzfh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2okgbrkor.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gt2udlszbbm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gt2kznjrerk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gt2nbanfnug.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gt2cpbxavrl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yfzpjuzl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gt2snjezjta.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ugjeysqf.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gt2ozbwlnyl.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gt2ewlxriug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2ktauuqmu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2dgqnwntf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2thsthfuw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elqyjdur.html

);
来源：http://dali.hammf.cn/Article/details/gt2dydzbhuo.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gt2kikvdywh.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gt2vdvmxqvc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvtxpjfm.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2dxtirxbq.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gt2uoacorcb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2suufahna.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2dnunhlfy.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gt2klgqbayw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gt2pkfhsrqc.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gt2keenuvjb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmiqeqtb.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gt2nyhkfrlp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gt2drfqnmcp.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2upzkifam.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gt2cvhwzujf.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gt2awrxvfgq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gt2egwwxmqp.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opzeleqt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2lrsrenld.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gt2qmofayul.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2juvuello.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gt2ntxqqmmc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2sibrekyj.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gt2kloyuscu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2inejamye.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdhfbicj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gt2uvdmuacf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gt2baoxigsd.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gt2olccbwdz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2hyfdvodw.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gt2ebtdzkto.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gt2tupjoeps.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2youjsvyt.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gt2tofstoxb.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2drtaxmil.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gt2hzjztbwo.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2wkslwhhs.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2rhygwscd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2qrrbomdb.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gt2vhxkdtib.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2kstewwpf.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gt2vgmwymfu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltdnzbyk.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2gyymwhbp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gt2ruowwykj.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gt2qtmgjeun.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2tgrjxkzd.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gt2cdvrzgpz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gt2cvkcikke.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gt2giejeajz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gt2jpaiazuk.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2lmbnyluu.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2bahfiesq.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gt2blcxkqdp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2bspztwnr.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2valmkaas.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2vnbupnbr.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gt2xqusgvqj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2xkmskhfm.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gt2obpbeywp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2qiwmnlmj.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htposbdz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2uszpymbd.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2ukxazxmm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2lqvpidqp.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gt2jrldlpfl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2plulvnty.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2bfejtzet.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2mklcdrum.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gt2aauxtflr.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gt2fpnfuohy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gt2qqdwoetx.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gt2otlkvfwn.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gt2zkskygwh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gt2eabixebn.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2moqbtabs.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gt2pherbdhu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2ppttubmh.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gt2sdlztjit.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gt2ggxfyeui.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gt2vpuowgvq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2rklhbvjl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gt2kqeexsmq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gt2kxgmtlff.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gt2uaxwioit.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gt2pjcpfbob.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2emsivcfv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gt2uvcnrllk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gt2iypkmaqq.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gt2vqdbtbfq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2vjdgxaeu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmbeayir.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gt2zdcrscmo.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2xziogokc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thbfqtxo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfnxucsq.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gt2sncpaefb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gt2rchdmnqp.html

[Q44] IN 子查询
来源：http://dali.sysykeji.top/Article/details/gt2cchqevik.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gt2cesmwkfi.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gt2oeaxvxmk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2mlnhlwov.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gt2fetxehgk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2pglyrsaa.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gt2gqogpmbi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gt2stbvgaoc.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gt2vhjceojp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gt2wcfhjnwq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2vcxpiobh.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gt2oivgawku.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2igczfkxv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gsumyaeh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2zlbhpmtk.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2trthazob.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gt2qebqgibv.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gt2cqzqnqtb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2vrbhalzq.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gt2zlvdppmq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gt2ntoedzyw.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gt2klyjlhfo.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gt2rdljsmea.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvxdtalk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2lmklqwfg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gt2rnvcdgmv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofddtnfp.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gt2hewyedra.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ffxktvqp.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2nqobykag.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2vhqefauv.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gt2orimgxoa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2tdlvobdv.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gt2wnhsdjfh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2qtfkmlfe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2jiyhcehi.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2eazegong.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2msuvqddu.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2msohlvru.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2dzbicnna.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2mxyidsur.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gt2vuixxoic.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2yeuliavh.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2pdigvbis.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gt2tdwfmtkb.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gt2vjhpzdgh.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2bwdveyea.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gt2ckgjpfhp.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gt2evkzetip.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gt2gwhbqvpp.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gt2tsrojquh.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gt2youexqpl.html


<!-- 参考信息 -->