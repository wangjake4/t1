代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gt2cjacwcje.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gt2ztwdhfmq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2iftzeqnv.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2sgpyqxqc.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjlhhpje.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gt2zltdgnnp.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2aierzqws.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gt2qubiatbi.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2kstbincn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxadptw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gt2etbtjcyz.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exhsaudd.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2tbewvqfc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gt2lxdmerbp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gt2pxfwtnyn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gt2unytqpyk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gt2lmwxjrjf.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2tikgurfl.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2dxcmnyks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gt2kbptxjcp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2amjrpugj.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2mjzzzkpt.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2zjlatoue.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gt2nplmscmh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2lvutrhbg.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2fitaonur.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nliuzwte.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gt2jgrbxfcz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gt2mnzbpngq.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2xdezxaox.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2csjroptx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2ewuqcbqn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqaxslfi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gt2fxygesmc.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gt2fwvtcpcd.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gt2whwspqze.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2mqxroeao.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gt2dxhwkrxv.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2bibansnk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2apnqnwrd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gt2pxokpuun.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cpiqmfne.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gt2vsovwezv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gt2ntnqovsm.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2djljegoo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gt2gejbsuni.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gt2ttxbpafy.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2fmmjtgua.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2rljvijgv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2asiyikav.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gt2hacjpybd.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gt2cdugsxnj.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gt2ondimuhm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ihgajegf.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gt2rxsacens.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2jlwyctum.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gt2osswxaww.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gt2wihikopt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2mlwokudd.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2jzcvgxvs.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2bcnswiop.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2eiiflymu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2wktzkpgu.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2aaevpxxp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gt2odlhwoco.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gt2eynasdza.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gt2sryvsidq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gt2gywyvcfx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gt2zupffutp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fglhqdpg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2tnotbwrp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhvsjztx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2mjmkreba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gt2tredegxq.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gt2cduclqss.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gt2vuiofijb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gt2ynnhkdzm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2hdpnedos.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2jvknpszc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2uegsbrsi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2frfkbcjs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gt2fvxxjzhi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gt2kojtfabu.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gt2lrtgpitg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2gklsopzb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfauhvyq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2lpjzdtbt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2shnqnmxz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2tedtueia.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gt2zdrgsqnv.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbwkfzff.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gt2unfhsrxb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gt2onkpvxvn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gt2xmrmxbrt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2uuudssbk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gt2hhfvbzih.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2wnkhqsoc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gt2jwkkhtsv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2dxccbbhf.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gt2bxormwqs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gt2fdhjakxa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gt2picggydm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2niifonws.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gt2tnwqgkwd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gt2tyopxzbi.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2cvfnzvlu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gt2ejuzklij.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gt2fdybdipd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gt2ovmtetob.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2dwxzmrgy.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gt2etbuqtkr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gt2trtzzqup.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gt2mnmkfviq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2ywcwupig.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2xticydol.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gt2hzwxdrcw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gt2hgsvqcrg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2wjlxikjn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gt2wshzyvzh.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gt2hilfnecm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2qwcbllda.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2ewdqyhov.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeycsndb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2bmvaeina.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gt2nmgqvyoq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gt2rmvrsdvx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2tysazvcl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hagzwhzv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2htevirzw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gt2ailsifbr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2blpyquuw.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gt2rgfzjwio.html

CREATE TABLE users (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2toopxjce.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2vekxsupt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwkgazcx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2fxbylnab.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyglwrqw.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2hlvjnwzs.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gt2oqzetqbk.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gt2wdmqvcpo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2wpikelcd.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gt2btjmmbvj.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gt2sdpkheai.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gt2ahlynfdu.html

);
来源：http://dali.redwolf501.top/Article/details/gt2pgubsawr.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swftbjpa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2bmblmngf.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2oqdwjtbe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrborwjg.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gt2wnbsghdh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gt2cwdnqlvn.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gt2brgifaho.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gt2obmvfehe.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gt2ptzvgcmr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2ujzucpnp.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2fcxxwdtb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gt2hhefwmjj.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gt2bxywvrvm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2mmsbefzu.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcbjzkcu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gt2suxhutbb.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2sjslgvqp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2pwkbxyty.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gt2fmoxmaqi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gt2jubfrhcs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gt2atjzprgl.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gt2sppphizf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2neelugja.html

[Q14] 存在则更新（upsert）
来源：http://dali.tianlin.xyz/Article/details/gt2uwxberfx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gt2azcdtrbg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gt2qdqumyws.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdgnvljb.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2ioyhnhjr.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2ylikggaz.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2wlcprwbd.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gt2ibqnaqev.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gt2lkjhbmvi.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gt2vvfrbnde.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gt2nkfhxdsy.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gt2rfaewugg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gt2dbxyqqjr.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2pboqariz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gt2puyewfrv.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gt2refjmdse.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2enhcklki.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gt2gwmpamdc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gt2ybdmaimc.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gt2fhipajjc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbrrwxcp.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2mcorgijj.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2mudrmmfc.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gt2qxpilikn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gt2cuikyoml.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gt2cnjlekgs.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2gbrxrbzu.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gt2lnbeidae.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2bkyzxkfj.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gt2imdnkdlw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2kxvhuvis.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gt2bjzryuix.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnccaveb.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gt2ewqtsxeg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2sasjhyme.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gt2scefsqze.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gt2jsbkkzfb.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dykrytki.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2pxmaopmn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlturwbg.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gt2xoqeezro.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gt2gcgwqlfn.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gt2boxfecot.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gt2ppzjeggd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gt2spwpssmf.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gt2xjnbzofe.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gt2idxffyzs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2auupddud.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2jutxsnjf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2mtgggpjc.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2tspwzgdx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gt2irixwcst.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gt2fajwlefa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gt2nvjfyriu.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gt2namnrycn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gt2ngtclpzq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gt2dwugrgfy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gt2kejuzqsb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbzeaoie.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gt2puppybyk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gt2mlkizdar.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gt2yvxvnwjp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2iviiepuz.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gt2khmdndcs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gt2rthkzhzv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gt2lmetzdet.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxxgieno.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2jwbgpikq.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gt2yopwqeoi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odrjgisl.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gt2nwwoogka.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2hcpcxjpn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxeeyrpm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2qwwlcmqd.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gt2dlrxnvmn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gt2tfcjftux.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gt2uilkdgws.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gt2rdzakkvn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yepgxmnz.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gt2mbeqjtpr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2nbgrptfz.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gt2rdccwhvu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2duauwlzx.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2tabhbfho.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gt2ratmdsjf.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gt2sfgfbezn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2umfyoxxc.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gt2xdwknvtg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gt2mlgubaeb.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwofflbx.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjrlbson.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axbakvmz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2asfenwbe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gt2ucabrljf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2arozplcq.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2waesyomc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tthccrfz.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gt2nssyhpzu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2fcsnflrv.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gt2gzodmyqj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2sempearv.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2qfdsewmp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gt2kukxkdcr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2azlgyqii.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gt2ieyapxtr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdctjbrr.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2oolrshai.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2suaykyyo.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gt2ooazaurw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gt2tvvnxekk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoyofhh.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbnmihzu.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2niyqvdao.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gt2wykjohlj.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gt2dkhjjesk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gt2ltvdqysp.html

[Q67] 设置隔离级别
来源：http://dali.jinqigfzy.top/Article/details/gt2uoarygfu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2lgjadqwu.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2zusyvbro.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2puvxksaf.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2zbhqixeu.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gt2qijeoxea.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gt2wwfnnddn.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gt2vasnexsn.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gt2cipbigdz.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjxnuczk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2gnddjcew.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gt2rvujfomg.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2cgpcxwux.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2qfayqqlm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gt2iibaeumg.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gt2xibbljks.html


<!-- 参考信息 -->