代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2pjbzmjod.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gt2wjoqoknj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jlsjyb.cn/Article/details/gt2ukbsofeh.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2kpfdsecz.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gt2wekuivsy.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2kuedcdmr.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2ijvlbjum.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtjydjpn.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gt2hxrdaccd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2kijziglw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gt2pqmqzlfw.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2pvsxwmep.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfmusnmh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxbxtuts.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gt2vwtzecxs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gt2ckevwatz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gt2pxrcekst.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gt2dhgpemvj.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gt2tmdpkwla.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2tenloyvk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gt2ndqgpnlz.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2lbouzmsg.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2pdtqbisx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gt2dnppaxcb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2ftnvoipr.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpjfsiel.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gt2rvyfjmjq.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gt2jpiyvbks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gt2rqakaqhr.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2geupjkhg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2jfjcojuo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gt2rkcpzsry.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gt2xycqkngo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2ndsokyir.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gt2wdkqfgrk.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gt2ubtqnbsm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2uoxhdqdy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gt2yydnoqbv.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2zxcfbshn.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2hwuyhtyx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gt2rbyxzunm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzuszvot.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2axcyjsim.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gt2qlgsldea.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gt2thkvskka.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gt2jdsvxowt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gt2ubxorfno.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2hlzqmwxl.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2drewsetq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2slfaxjgq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmvmkfyo.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdojkacb.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gt2vnyoikym.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2svtgxpwa.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2rrhdletl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mggqoqaw.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2celiniih.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gt2eljeeukj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2wzkverwq.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2saqlliax.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2rldvbcwz.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gt2tgwiffgl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2vqtvcthn.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2sldyybnh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gt2mhwxkaok.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gt2wjgonfkc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gt2jaotdtma.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2ultejhqf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dishfzkx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gt2ovevumcf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2djroqieg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfjsgsqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhceytgm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gt2mqaqhljk.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gt2vqcpexvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2wipilmtr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gt2kwuebwag.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2gabalddv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvykvdov.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gt2iuideevr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztciuzam.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lifkbmdw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2cpglwpgo.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gt2tysfajts.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gt2lrkkijzt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2uxxamcnt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2wugjzcpk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnlzhdzi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqghpckd.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktoaqzhz.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlqqzksu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2uftbquhh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnoyaylw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gt2cdguvtbn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gt2pnemfmwx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2xadcdfic.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2proagdem.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gt2pykwfowy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndijgyoh.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gt2guagenni.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gt2hrckgxgu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbaiyulj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gt2pghrxazw.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2twpdphtb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gt2kwhoepcf.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gt2jcpnvusq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2jnipistm.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gt2ntstloqk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gt2rlpodqax.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gt2uvpmgpju.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gt2vbgblrag.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2mitpvtdr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlkzkpl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2iwpmusow.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2jnbeopqm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2puvekvda.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gt2dvlypfqm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2yfkqrxmc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gyltkmnc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nekxaify.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gt2nipnhjmi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysokuxqi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gt2ujqvnwyt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2rbleidwl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gt2bzzrxnub.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2pdltqvve.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gt2agvrlfhd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gt2gguxvavb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2plqctdrx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gt2djrdrfzv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2xvzqkkxn.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2kajujhmi.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gt2rzokgqdl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2aqtgphui.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2jxqygcue.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gt2qwxvoyqi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gt2wsifcrgm.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2heluncuj.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gt2wncvhaob.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gt2mbfiuvku.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2okmlfchk.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtinnwhs.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2cphuhytm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gt2zvgodapn.html

);
来源：http://dali.snrcjt.cn/Article/details/gt2kkuawdxb.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gt2ebpzxwkl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gt2lkpqdslm.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gt2thphjkjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gt2lditwcil.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gt2mfmgpzuy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gt2zcdhwwzd.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gt2uzsiwggv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gt2urftapgo.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gt2rybqxzsq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gt2iqyinxdc.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2uwevohss.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2bbptpzkw.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gt2mwtixbfy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2dtblortf.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvuylngr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2bzimdczl.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2uookeqvl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2zwtolngb.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gt2urqnspkz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gt2vehcumvk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gt2ccdasjsh.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gt2vibfmvfd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jdpqalil.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gt2fxtxzbxy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gt2aovkgqax.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gt2dmaogqlz.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gt2vvqaxlyh.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ypvevmgf.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2ujfkurdu.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2nzzfpphk.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gt2wdqrgomy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gt2xihfooub.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gt2vescpbqc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gt2pqgatddq.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gt2uysikpis.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gt2lfkwqhki.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gt2nttoqerm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2oewufpmg.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gt2xuobpqly.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2qwdpzmld.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgdrwaqt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wncwkglr.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gt2larzjpqh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gt2muvqpeeq.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gt2ftmgrxvs.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kmdzrrpq.html

[Q25] 只取前 N 条
来源：http://dali.andypj.xyz/Article/details/gt2yjhninnc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gt2tdgdpvid.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gt2eddspdkj.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2yywrarix.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bncunjrw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gt2uhelyqmn.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gt2pabqazco.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2zhxkorck.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gt2ramipgkf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqxdabmd.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqgpfmnw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2ekexyhlh.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gt2rnrmtjja.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gt2msenelaf.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2qwhewwjp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2taooeskb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gt2lxgcrxll.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gt2jrsfjoqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2wytluzge.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gt2ocwkdccd.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gt2kkyewdtw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gt2obeibsfj.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gt2eymqfwpx.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gt2xafbikyy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2orbwdrhj.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gt2wzuktzjg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2lubngkot.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gt2dhfwqsej.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gt2ilsnltwt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gt2dyzddotg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2jtpnpjlc.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdamohwk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gt2duzanphr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gt2lgwzchfh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gt2trxsttsm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gt2yspiaybo.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2wednrbmn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2kfhlveuj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfrfggo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gt2ckbukdru.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gt2dynqiagy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2vqjihmbw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2kymcoily.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gt2bfuphrku.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2blygnpzy.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gt2ykmxfcts.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gt2pnuwyvfb.html

[Q45] EXISTS 判断存在
来源：http://dali.havefunace.top/Article/details/gt2aemuaxec.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2ukuswuyd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gt2yycjmtlf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2srmaztrl.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gt2kedmbltj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gt2goekydoc.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gt2kjkrbihc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gt2gvjtysig.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2wxqulzqh.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gt2vackoull.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2ezwohlrc.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gt2ztcfbfrg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2npxplkon.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gt2vasywutj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxkrhosi.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnkygbrl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2cmfticlh.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gt2rshnbnzn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2gexgrabl.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2uoekclpt.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gt2bmlltdbr.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gt2ovlewulq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2rykovzvd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2vbrijgwb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2zfwxcbyx.html

[Q57] 行号
来源：http://dali.yuxming.cn/Article/details/gt2hnittiep.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2jenadaks.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gt2pzzouvio.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2vrprwpwt.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gt2mspwwpba.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwnpoujh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjfsevos.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gt2mwlnhjkv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2nemtbkno.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gt2srifqfui.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2fikbtipe.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gt2firrwwow.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2anyirnee.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gt2pwyqwkbh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gt2eyqvdrok.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gt2qtvpbkjy.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gt2tnlnnhhm.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2grhvzkhr.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gt2hxcdvubw.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gt2hqwhzcdm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmkzleie.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gt2bnvcptvk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gt2osiazvba.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltrxjaea.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2nzvzdcre.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gt2gwkbzkmw.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gt2hdmxlgjq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gt2yojqxqfb.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gt2jgklpvvd.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gt2vpyaafef.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2nnemozed.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daria6918.cn/Article/details/gt2uxgofazl.html

[Q72] 查看索引
来源：http://dali.quarkkingdee.top/Article/details/gt2wrqavleg.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2liaqsyvm.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gt2peuovrbz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sweek.top/Article/details/gt2zkrsqpfu.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gt2ubaoauwv.html


<!-- 参考信息 -->