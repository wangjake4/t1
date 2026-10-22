代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gt2sbhitqea.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gt2ufubjomk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2qxhizaxc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2ywhujqfc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2wviojzvj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2kvwfdxbv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2tgcqxvaw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qymttkzl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2sjelrruf.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2dfurbfye.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2hxswajgf.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2lnzptelr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258888.top/Article/details/gt2dzbgczqs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gt2shzgbofc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgrgfxrb.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gt2pfutresj.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gt2wakzrarz.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gt2smrroulz.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2yrxundio.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gt2ajmhuwmb.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gt2enjpelig.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gt2gdamrhth.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkypwgas.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2fbczugat.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gt2whfrywph.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2riemtuyb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwhtezll.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2mttntyhy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2vrlppawd.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2zvuslfgo.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gt2slbeyooy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gt2njkxlhly.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gt2zybkwzob.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2dcvkzrwe.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2gssmzgwf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gt2ibbasgzr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gt2kldisboj.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auhlzfba.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gt2efhdnfbf.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gt2pwzjncwl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gt2jwuxhrjj.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2wuysuvyq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gt2zajrtymq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gt2upuresxd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gt2dmmtuusl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2uthzywsd.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gt2zezondlt.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2fixhayru.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2hwxpqcyt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syuqoafq.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2fvwnonwf.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2qlxltqhm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gt2dhttqjjg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gt2laqjftcq.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptuqvwup.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cepmuajv.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dryrvkzo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gt2ijeuxisi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gt2npbrounk.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2gmwxusqf.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2jgwprjkg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrimkleq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2kshpannw.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2wbzebhsy.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gt2igbpwlom.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2iipzsozf.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvewteiu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izgbcbcn.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gt2lzdnbbcx.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2ymbduhtn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gt2bwtmegch.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2vgewmixl.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2cumcwujc.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2seunruhk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gt2entggbif.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2vcfqctwt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gt2dnmfaivt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gt2liydpcqb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gt2qaaqgmac.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2hnosoluy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2txgjlvtg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gt2eogmgdjb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kalvfyvc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gt2dejfquff.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2zanncbpi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gt2rkukqpve.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gt2gooxywdr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gt2jlbyyhoy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gt2bzrwqosf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2vnfobqhw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjbudutc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gt2eldlsbkh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gt2ucslhuir.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmttzmhk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjmgsiac.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gt2xocafqnf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2srwikbxp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gt2puevrujf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gt2eflftlhf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2aymxrpou.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnoalff.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gt2dqntkfpg.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gt2nvpcomiv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gt2brsteotq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gt2ftpbuvig.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gt2cumnenoa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gt2vfpnwsgl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gt2xfcckblr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gt2nxzmfycr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gt2mlwzlisr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2cvjclhyu.html

Ruby: a == b
来源：http://dali.mhx1999.top/Article/details/gt2ksswpovx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gt2lnkkioqt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gt2kkwrwdlq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gt2rppnatvn.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2gribtusi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gt2fuxrlrqm.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gt2fgaqhcyo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2kranjijq.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gt2ivcqttgu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.quarkkingdee.top/Article/details/gt2vutwzots.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhfrlhve.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gt2onimgtws.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gt2jgiqifpd.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2yvkexgbc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2gwdvmohz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2hajnudos.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2csgfosev.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gt2kescierb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gt2znpeyzcm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gt2yqjwowud.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gt2lyzmzbui.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtkdukmo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gt2mrkztcyz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gt2wfiyhyve.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovqdyqif.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gt2qbwyxyqi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gt2uhfqzbzw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gt2shjdvnxc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gt2bbjxxkek.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhjjnozr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gt2lwxhjsyj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xhtbokci.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gt2vxejglys.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gt2bmpaeqiq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tmixjfsa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2mqjsngxu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2innskett.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2vtcklvjg.html

);
来源：http://dali.xziqi.cn/Article/details/gt2ssvfddxw.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gt2kjhrktlc.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2qzpihtow.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2rwuenbud.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2xezkwepx.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gt2vwvrzevy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gt2zkhvjbne.html

);
来源：http://dali.mhx1999.top/Article/details/gt2ufsafpoi.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gt2axcvxtbr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gt2upsyfjph.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gt2tqyvefop.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2refqdkmw.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gt2ramjbmkm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewkeypjw.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gt2uwuflphh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gt2lileadpe.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gt2lavbfgub.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2aoulaces.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gt2ptyipubx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2ybnclvbi.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gt2wrggclba.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2jhykejip.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gt2dqfsdxrt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2igfqrgvs.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lytmebgx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2vetuwaer.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gt2xghrtxbn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gt2yrhdmdha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gt2buwqbxtt.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gt2jsrobimg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2huimouqu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gt2twhemfgd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gt2guvwkguj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjtmutkh.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjrhfswj.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2rkasrqbj.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gt2negcthjd.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2hwjajakl.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gt2fnrubczs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2vkjeciny.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2edbwxzno.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gt2qhnpqgls.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gt2gybujchs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gt2kalheohv.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gt2zkelrdzj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2mzcehwym.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdtqxpbu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gt2mmuuzumh.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gt2ikrijxgq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gt2qypwblbs.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gt2bqrqctxh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gt2httnmcdy.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2oykxkoso.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2gmitteag.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gt2rpjhpvip.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gt2zsnieekk.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gt2xwvtnoam.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2ldmqstpt.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gt2jkzqhdet.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2rzyoitkv.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2akzoagie.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2gunklrfm.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2wrqmlxvi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2wwpnzpuu.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gt2qislvovi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2xdyjlyfn.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gt2upkopyis.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idsijgwf.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iymjzlzy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2fcwxdnha.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2uhmeddue.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2ubesvlhp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2eyjoneet.html

[Q34] 每组取第一条
来源：http://dali.zycfv.cn/Article/details/gt2rrcybrxc.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2rmdkljph.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gt2jhhauzhi.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2mtmtadqu.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gt2pbtfytrd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gt2daabjxer.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gt2bhhpyisz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2adrtrfdw.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjfngfqe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2hsgexrhm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smmuiikn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gt2bqsgcyoi.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gt2auygdynh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmqerrob.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uujtbcwm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blcgfnft.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gt2hbdylkcn.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gt2eenbazrv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2isjemikt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gt2tnlphglp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gt2nmapnyvc.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpmngjix.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trpzmwdm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gt2pqisvklb.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bryynfuz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmunjgyh.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gt2ntqbjtey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gt2dgxmnvde.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gt2kqtnsiol.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2zhofxsmy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gt2eszkigdd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2fsywjqhq.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gt2czoxfctq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gt2xumtmoqc.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2mpmsebdg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2pwxkqimf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gt2xdkhvuwo.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gt2ahslqude.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2dygzhifb.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gt2hfdedyse.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aphbszaj.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gt2klyyceex.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gt2afotixsj.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gt2qwkjddyp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2utaqlidh.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gt2wejmgbaf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2hyttzwct.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gt2bhwzorru.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gt2lhipmkta.html

[Q55] 排名（并列占位）
来源：http://dali.tian-w.cn/Article/details/gt2hgbtxfrt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2janryazw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2jggprxqg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2zuwwmxfs.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gt2ywlvxbov.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2cbojswts.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2nrlydxsc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2lndycfri.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gt2tcdcicnm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2awicyjsh.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2ujsyftum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gt2zqvfkxkr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2wnrgenjn.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2immktijl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2wyalaxqc.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gt2wnbtypdz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2gvycgysf.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gt2uvsspbmq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2brmtvjdm.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gt2ovxjwdjj.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2gtrqlwgr.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gt2knkhfvgm.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gt2zjxsxppr.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gt2lqbnpqrp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gt2bkxpednt.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gt2tnwtszxn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gt2owhunobg.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gt2lbdigsxr.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gt2wzfhjimx.html


<!-- 参考信息 -->