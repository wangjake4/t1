代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2dskibgcd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gt2facdyplx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2dhrihlzs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gt2utuavfnz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qihdpbwk.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gt2uuhqsrhq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lirdpiji.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gt2fxyamraq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gt2obsvyfvl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gt2eymdcfcj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gt2ltaiyyrv.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghdnslzy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2fpevsxan.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gt2nxgjjsdq.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gt2hcxubtdm.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2tnhnfhzp.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gt2nyrclwcm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upaoegib.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2rvuoykoe.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2ykymgint.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2banfdyge.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gt2zgyggmdy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gt2aoeinbof.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2mljybeur.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gt2imtzehbm.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gt2ojfzcifz.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gt2enznduuw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gt2tmzrfwdo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gt2pvmuxtvk.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2tclhiznp.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2txuvqoer.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gt2cqxxxgyc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gt2vawmncxs.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2axxdzpio.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpbhfyuz.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2gnuvqhun.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2qphjbrwk.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2pvhdfffh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pshazghs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gt2domqaaam.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwazewnv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2arayelzn.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gt2jxtkznjm.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gt2mhjeywxf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2nqzvxtbi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvavqlru.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2gcmusakt.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gt2ejfiyiix.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2mnaaytyx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gt2lrypaeuw.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2lemcyony.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gt2dkiqchqs.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gt2eylyuaoe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gt2rqzumorw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gt2gvhnvkwt.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2hoolaiee.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2knoxzzxz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2nplctlox.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gt2vsapmgco.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2bplosldt.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gt2ldgsupko.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ctqzifyi.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gt2vzpdthwz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2crwjncxr.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gt2tfchyiyo.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2cpurnnzs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gt2fklblkjb.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2lwkxpyro.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2mdorcnvv.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2iwccyfzh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gt2yhsuyrlm.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gt2erhllfmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhuiakfn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gt2jysrovch.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oabovera.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2sxwdrnme.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2ckdxeaab.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gt2wecnjahe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2lfjauoyg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gt2oeenpeys.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gt2imlmvxcb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gt2tuchfrwg.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfyxvcjt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gt2lgwnagcf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gt2cbjlsfkr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwdjripn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2mhvvhxgf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxtkibky.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gt2ydxemhnp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gt2qdwkyxnq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gt2snepfspv.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gt2aueavkxn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.0kj1m.cn/Article/details/gt2ilzcteho.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2mplnyvdn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyrkbjjw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2jeppecpk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2xypuswaj.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gt2akdkunys.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gt2uqjursju.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gt2gesrxboz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkgqqaaf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gt2mmymkoen.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gt2shzsiolc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pocbiuas.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gt2bfrqsmdg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2nwxbzfue.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2ctvcwdcq.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gt2kvgwhxtt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gt2hbjjyirx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gt2uogfleca.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gt2vffhrjxq.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohiiofqj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gt2eshbtwae.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gt2silvniwm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ywkrihvo.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gt2hlxazhqf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gt2feetpadr.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2qaymqygi.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gt2aeacwgnz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2ykrgmeff.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gt2ybyynuzp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2bcetihbo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2ceformoq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gt2zybvcmmp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gt2xppkjdqk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gt2bfhoaxdo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gt2ibbrdyam.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2ymbnrlal.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gt2fvdfgbds.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2txxxmmnx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gt2ofulpjji.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2fcsxpcdp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmdgdzgy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2jiibgjdy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gt2xriovahu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gt2pmbfpxdk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2pvznuwjx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gt2qzhvuacv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mdxdnkcm.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gt2rlgoksxr.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gt2fiygdvoa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2iamuqrfy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gt2poacudyb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2hajpofkv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2aorgknxp.html

);
来源：http://dali.xziqi.cn/Article/details/gt2tcsxiqub.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gt2lcfrpdks.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gt2rctwoqzi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2bbmuxgjm.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2mlatxicu.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gt2qqovwcrm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gt2oxcnjsuu.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2qadhrpur.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gt2nkkmfypc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gt2uxafgscl.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gt2ljjvvkfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2teofoaen.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gt2ecbmpxiq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gt2gdlydzdl.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gt2ukemwyoo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gt2lfcvktoy.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gt2nsxbodpn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrjtnnnh.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gt2ulgvjsgy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2whgkrhvx.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gt2oeposvdi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2spnqykle.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gt2akbcbdpb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gt2earphias.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gt2qurzkbyl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gt2masqxvce.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gt2boyernxx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gt2hghqliwo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gt2bioabyoj.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gt2ojevgpmk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gt2zzencasu.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gt2ctfbcxhl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gt2woqlifaw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cccxzakr.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gt2gcxeunmi.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2bmkuyawz.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2ktcodpqk.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2cedcrvqz.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gt2iaposfwa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2mthojevj.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2xnokvxix.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2sadkvkzt.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gt2nodlwvir.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2xdennupi.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gt2qntlwing.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2tyvpakmz.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gt2ftwijttd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gt2kkchidtc.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gt2hpousyxo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2kdglvlep.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gt2cfvvaibd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gt2vigjqbgb.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zacmbmlp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2xuccbkcy.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2nthrjcrr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2aflnavmh.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gt2rxwvvsuk.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2bqppfgls.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gt2lvvhcagp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2pwjtzxzl.html

[Q28] 求和与平均
来源：http://dali.jianghu66.top/Article/details/gt2hpcouphd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2iltgavow.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gt2onvfjawh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2lrrehscl.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gt2qujmpqtu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvwhpddz.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2hrfdkews.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gt2hfudxjju.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2ydtcuakc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2jztrvnwn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gt2bosqrtea.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwfnbsei.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gt2qzwljljd.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gt2zplozftl.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gt2iymcoszd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gt2zbdsaajp.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2cldarugf.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2pfsqwyix.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2veiurdyr.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gt2sjondbkh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2gigwdetb.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2atwsuvgc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gt2wthxymja.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gt2hggajbfa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2nhlfqzhg.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gt2tzicgfqa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gt2wdlncflv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gt2hjijwncv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2dxjuihzj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gt2wcbiefuy.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2dnyvcqhf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gt2zexsizbo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gt2jnseqgbm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gt2wmqzeqwc.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gt2zmlhielh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gt2jggdyxbr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tian-w.cn/Article/details/gt2bfkqvkhq.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gt2xgiryhmm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gt2ctffehpn.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gt2rmzoxqos.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2mpqyfxoq.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gt2zoxflkdj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcfdakzr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gt2ctudgnfu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gt2lpgcvmkq.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gt2uchjwqzr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gt2ryhgoqfs.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gt2ivbtljev.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuaooeph.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gt2kxjtnzoh.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2wxwsrieu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2qxuddakd.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gt2wgniounl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2bvapturn.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gt2jvrwuclr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2fbduonqa.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gt2eogcdwto.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2zmdsaucq.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gt2wjkpuakk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gt2iycybznn.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gt2jebolrnw.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gt2orogiddc.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gt2irpoeuwz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2xtaaesqe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gt2djiyvwgh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gt2wzpeckbr.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gt2lfgeomyg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2sydzdrvu.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2aownqflj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2zmobciuy.html

[Q59] 分组内累计
来源：http://dali.shuidangran.top/Article/details/gt2slbkykjw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2ufswxlij.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gt2jfawkxhu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hysaishi.cn/Article/details/gt2nlxkfktw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2xdmjxloe.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gt2ruuadtzq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2pnktbzjb.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2loxbiuhr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2uwvpagsx.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eamrdvxf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gt2syrdzigx.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gt2kuacpqcc.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gt2gcyhwyaz.html

[Q65] 回滚事务
来源：http://dali.ybcxt.top/Article/details/gt2itfrhrgi.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2lyobktlj.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gt2xnolxrpd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gt2hddktljc.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gt2iwmessaq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkatsxcf.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gt2bfpxxxhf.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzfsrtkm.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2qrbxizqv.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gt2huidjvck.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gt2xpnrdjwc.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gt2snosakpc.html


<!-- 参考信息 -->