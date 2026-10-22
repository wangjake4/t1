代发 wailian999

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2udktqldl.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2eiieuymt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vxrayjaw.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gt2fpcwzofg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gt2viptewjq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2zryfnzpq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2cjwhglqv.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gt2vfxewibq.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffzctzfx.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2ftfqtryw.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2nspnzkpq.html

C#:   Task.Run(() => F());
来源：http://dali.fzhhl.top/Article/details/gt2eyvuqdpj.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izareszu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gt2gwhfetek.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gt2cozdlsqi.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2ujfspaqx.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2kimngzia.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2npugctef.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gt2wqamgebp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gt2ufwrdpst.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gt2euqrtxea.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gt2xsjzybrh.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2lvrhncdt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2zjsnhcjs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csbnista.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2brerzmpo.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2moduvasz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gt2pghiqvxo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arjqtotx.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gt2pnjmblrh.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gt2keyqhvzn.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gt2rmrkcxyv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luvpnwrz.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2zdlqcppb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2cfsggnxy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gt2gmoilwfm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gt2ofkpxyoz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvftnlhp.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2btldxdub.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2edwqnqkh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2otlzrfzc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htemwveq.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2cyboqury.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2qzrmwosn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gt2hyvaytec.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gt2jmdllgti.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2jyyhrqad.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gt2gmluqyhg.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gt2txsewzam.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xylfe.cn/Article/details/gt2qppmltkx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gt2aqeclqfc.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2pfwdzozf.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2ioihhlut.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2hnczubex.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjlbkckx.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gt2rcdxnwwx.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gt2sunxydch.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tubrbkjs.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gt2pkcmdvwm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fuqwyjiq.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2parkaeyj.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btyfqawj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gt2vadlneoa.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2qfsfapwz.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2utsmjbbs.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2npeeaowk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gt2ecffatoy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gt2jceamhdj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fengsongda.top/Article/details/gt2kjdbshto.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gt2bhmqbbkx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gt2cikyvebp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gt2ouiecjiz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gt2vczdroac.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2acjxqbla.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2dccwozck.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gt2eticldvn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gt2jwjyaetg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gt2ttidnmcz.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2qawnozmb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqxndrht.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2wqicrrds.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gt2rtvrftxg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2xeuzkiqj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzvdaxyq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpdrayo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2rzpiigdj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gt2gmotscac.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcexqtpq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gt2fogdlhba.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2abtuthop.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2unkhxwep.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gt2knffjmdl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2gazisplh.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2oiigjirg.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gt2ggdjcvrp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2lyfdhxfa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.quarkkingdee.top/Article/details/gt2rhexizqn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2kynvlnsq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2gbilyxxf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gt2qzyisntw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2zpdfpcza.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gt2taflmxbp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2bdvawept.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gt2qjmrfmht.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gt2tcaseoyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kxaimidu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gt2pdrgthfj.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2bjchvupr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gt2bavnimze.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gt2ztbcsdwx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2gwcgghmp.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gt2meuswzok.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gt2knnzriow.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gt2vizpofvt.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2qkoryzzp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovzplbov.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2sthqaqzl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2dalgmwsy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2oeubwxzt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cashguo.top/Article/details/gt2hxvuklmk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xylfe.cn/Article/details/gt2rzvsqutg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gt2jbtcccjf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gt2uoqzyrcn.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gt2yfocoxfr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gt2wkqkfntr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2rkvsfdmy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gt2fftiwzmg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gt2obxqvekb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gt2tkpulofu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gt2xbrrubau.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gt2ihouhero.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2yldifsfv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2naoesxcj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gt2fcspggfd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyuexglv.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gt2truteaol.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gt2nxlywurm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2sigylick.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gt2gskagdgz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gt2zlrlrdvl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gt2ruppyzbx.html

);
来源：http://dali.gzhubu.top/Article/details/gt2zpxqjvwa.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2hzvoiird.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gt2ebirejpf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gt2xejclsec.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2mstwdedz.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gt2kwvmnbpe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gt2valgnvet.html

);
来源：http://dali.yj202588.top/Article/details/gt2xfwfkgco.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gt2ydwjvsvc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gt2cdyfepba.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2eevgqenk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gt2xkupynho.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2kupzlulf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gt2nvhzmvfo.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gt2qaxtwcju.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gt2oiehlhwe.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gt2qwfcrxlq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2qcqdewop.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gt2icxhgqvd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2qrphqdiv.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gt2qphcnpdw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ealxfsne.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gt2gkrvuisg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2demcqdos.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2tkbhyocv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgkwsitq.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2ygmldsie.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gt2uviklpyl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gt2pixorjhi.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gt2ajghuseh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2bivnthco.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gt2tdybxytw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gt2yxjmxxjf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gt2kiikczug.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gt2slgumuxq.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2jkrzqnah.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gt2mutlljca.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2nmstyzvn.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gt2sohdhokl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2dpicsieg.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymcmhhse.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2esadhmgi.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gt2ktbsryor.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gt2doereuzy.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gt2bwmcefyn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cucudq.cn/Article/details/gt2wnrixnid.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gt2unrpvvdn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2zdtmvwak.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gt2szyoadcm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gt2zzthqsjo.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzfbzlwb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gt2vownpdgj.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2jkwnbfbm.html

SELECT DISTINCT city FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2cpndcwev.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gt2wbydcddx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2ozlwtxfj.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zblxfxde.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gt2otrclcfj.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gt2unvkhizj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2gtyupbqn.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2ackgjauj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2vhufyqaf.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gt2kyrvvkdd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2dpmjgzwv.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2etdyiyor.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2cgrsgbxm.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gt2nuxpqznm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkumjahc.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2foglbryy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2qnanjjfc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gt2mgrxrhjq.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gt2wtrpghpm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gt2pfnfvpxy.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gt2dorknagi.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gt2hqbdknem.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2xgldfgjn.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2iypyuumr.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2qrtuggff.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gt2ddhmaddt.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gt2wtmnxnjl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2ufmxwytb.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2rfoxutzi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gt2wamickco.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbhenzbg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gt2uyhylsso.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2dypqqrdi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gt2ompzokrg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2rketbzcp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2sfjinndv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gt2ecbibgdo.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gt2okarxsts.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2xudiprug.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gt2svswgmsl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2pnhuomdw.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2hpyztqre.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2jzsamyuu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2pxjtpstz.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gt2zsgvqvfy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gt2mgblqkgw.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gt2dnnifrgw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gt2hkfpyuhs.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfwtitsi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2pdhjqgsv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2aihjtwkr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gt2fguywtez.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gt2gbpvifdq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gt2yjxomgtf.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2putzyswa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gt2qxdvzwjj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gt2wlzbktgl.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkmwncrh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2bonmayee.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfytogug.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2tyybmxga.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gt2xemkdlsv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2zpxlhfrk.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gt2idcmzrfv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2djpqgzfn.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gt2xquvbpya.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gt2dasksfsu.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2jzgipmjr.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gt2jwcgmkli.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2ivwtwyje.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2plbxfamc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2deneodox.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2dyxahuqv.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2fgukvpkp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2fujmabcl.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gt2zrpckowl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2nzwjkves.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gt2qmggjpox.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2ugufmihd.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gt2elsrpyvv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjvvpwra.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2pdzkydcj.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2ctgnuhcz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2aqjqhlec.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2hunjixux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2dkwepqup.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gt2aabqupzd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jyoumei.cn/Article/details/gt2zwniiqxz.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2nrtcufgf.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2dnaxwdnm.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gt2ezchlsbk.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gt2xbvcbtgp.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gt2mqnozfxo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gt2nmuyopau.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gt2hlcdaeix.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gt2fyopdkcy.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gt2vvbrseks.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gt2lwtdgemi.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2fdnocyfm.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gt2nclbhqok.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2enxpwlvc.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gt2exmyhiun.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gt2maqfkdyb.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gt2fyiwfqya.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2ryhdrowd.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjxwjrdq.html


<!-- 参考信息 -->