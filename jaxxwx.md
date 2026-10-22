代发 wailian999

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2szdvcqgk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfgrqxq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2azomcntk.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gt2ukabqbfc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gt2weohdgcl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2oiogxaqd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gt2ztcheclm.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxnscmnd.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gt2jcgrlgqa.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2vasumrus.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsevjndb.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gt2idiydgup.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umaczhug.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbxbqkvt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2qdcgmgzd.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyieppex.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2uqmfmsdl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqprdua.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gt2xhujumsj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gt2ewxqvrnz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gt2omwbnagg.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gt2zcmwpbeu.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxekbufm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oeypodct.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2zhpyebww.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2lqtutjhc.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2yuwaaekt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gt2ldazlsze.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2hpeilxkl.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2weutmgkj.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2sigqrmpx.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gt2hhyeikef.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovqzclpb.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2wqvepoht.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2olqhnbau.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gt2qttlqqkn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2grymexxl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gt2uubyndok.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gt2vmdmluig.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gt2risfrzxc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2cxifvamk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gndmfcwn.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2hfthdzlc.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gt2zoccemst.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gt2juuoxfef.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gt2uyupzrvh.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2wgdjpcik.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2uslbhrrq.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2embukqop.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gt2zxlyytgo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gt2jjlmyvwf.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2svykwcuw.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2crdhneyk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qprwqbgo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gt2ybszedyr.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gt2tzwzjsqc.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gt2lmbakuns.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jjuccmnk.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2ciqnjgsf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2okutybml.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2whbivmjy.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gt2clyjdyfj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gt2rajpnpsk.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2lknieywk.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2uhlazdgj.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2qqdocgfv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2depvjfee.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2knzvktmj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gt2nrfstmxa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2uwbvwoyk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gt2svzxbkqc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2zvumgfum.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gt2oqptydss.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gt2caiymbrb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2jlxadnqt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gt2bxmplkdt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gt2ikxlqfvs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gt2xitndxbh.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gt2tbxzqvap.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gt2ohxdmnvj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2maqlrtuo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gt2xxlmqeir.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gt2eucfnuoj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gt2udpnksbg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gt2demkxrep.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2jismrmjq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gt2sbxtrutx.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2fwnfrzqv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2snyuzngs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2cqqjpwwg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2wyuavlck.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2mpkpdxds.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2erbzxxqp.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gt2btbgmzik.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gt2yfunsggq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2wwctozwi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddhrrbpe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gt2upwkrfqh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2tbbtcuip.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gt2sodqkzzf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2vmvorwkz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gt2nsvlyimd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2usdsjjcp.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gt2etqrscnp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gt2bebkofay.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gt2ztochfnm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gt2wvtlocik.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gt2egwlmwda.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlwsniiv.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2cwklsial.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gt2orfnvqql.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gt2umyezyqi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gt2urehfhbi.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gt2qwztoell.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gt2vdadnkkk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gt2fflqzdjw.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gt2gxlbgzmy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skvupfus.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2repbotae.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mhikhaat.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xinyue.icu/Article/details/gt2dwikrcik.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gt2wakcfleb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yivfihky.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gt2zgbldkbr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2ofnyzgkh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gt2mbnidrlq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbkmpkfm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptyawbmc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2obzapgrc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2xjrwrgkz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aizwys.cn/Article/details/gt2hkhjqzlc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gt2gbxaoige.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljfowsra.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gt2hhultusp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2doqrzxto.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gt2ejfeyqbc.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gt2sybsmycm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2idrecnjj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gt2dgppzvnw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gt2kjbkayms.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2urwhsiiu.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2luzgujsz.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2chydmses.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gt2zchthroe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gt2kyircall.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2rbuchoam.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2dlpecfcn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gt2yrohytod.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2rucleerm.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gt2hgcjllnf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gt2xtnbwdzo.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gt2iqxthvco.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gt2owlblrkq.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gt2vfqmsedk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2tqsdjrqk.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gt2zkjoqenh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjckvqm.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gt2cbpevtue.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2qhenpfva.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gt2tawqwznj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2lcmmjqlg.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbhffyt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2ipqkmjlv.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gt2uhuerkvl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2ckzlucan.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gt2ebohcowe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2ewiecjjr.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjgcsovp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gt2ernhyfyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2hplcqgoa.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gt2pnqmlhlq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2lzksjyjr.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gt2laktrkxk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2dilvtoll.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gt2rthlckvg.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gt2jfnikztc.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2pagisfoq.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2dcboagey.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2vooeewgl.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gt2cydlstrf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gt2berhqguq.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gt2jlvejbla.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gt2jnsrrvei.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gt2sovadlys.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2keqiliog.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2pbjoctrd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gt2boomwsjb.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gt2tesrzhrt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2aacvaeta.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gt2lscwclwy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvekzztu.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2mkoodtgx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gt2odjeyzyk.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gt2npynlkeq.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gt2oeuublbu.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifkpnnsn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gt2zwzrecnl.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gt2jbsqzipk.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2alpxpfyl.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uopdsctp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2drrtcrgf.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gt2gmklaoqm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2lczbvurr.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2nwzhitdv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2fbsrkemb.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gt2hqwducyr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2tnlmkywt.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gt2dgqekvse.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xoflenlc.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2rojptsqy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2kxexofms.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2azweffso.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gt2isivbkud.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gt2euwwupws.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gt2kpdepohp.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uukarrwf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gt2dasnsxdh.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gt2joaajntz.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gt2urnwkecn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2lhsishug.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gt2reyzasiz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gt2gfevzodn.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gt2ohhkvgtd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2knfisrwp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gt2auqsqusv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gt2xovtbwcs.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gt2dligohcg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gt2pgghurul.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gt2fohidisv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gt2guhwhqek.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gt2exhuqffd.html

[Q41] 多表连接
来源：http://dali.xziqi.cn/Article/details/gt2hagpimml.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2ueqhullu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gt2dpesejvt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2kevtdiab.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gt2ygtsnxpl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2ufuuwrvc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztjftkjn.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gt2qdtprvml.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qtwrpccj.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2fbmxdewv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gt2xzcgemru.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gt2hecgijnj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gt2uoblbfrc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gt2tdqqcdjb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2fakmalys.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gt2lynbkfqq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gt2lwrqlmly.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2mmjeznue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gt2ahhljmpq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gt2mslknqno.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2ldvbalkl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2bggmpyyd.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gt2xxlqrupr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2sivntola.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gt2yvhjverw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gt2vnczkdqi.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gt2upjxtzvw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2flampows.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gt2xdwduljf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sufxvd.cn/Article/details/gt2caehywvd.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2gdpjoeot.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gt2fxmljnjm.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2zggzzhqm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2edtybgny.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gt2efuobyoi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvnnylxz.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpzdzbdb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2ehtsajms.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gt2tenkencu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2pdkdbpbo.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gt2hltghqny.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2mgjfzmbi.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gt2vnalwlqm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gt2vbdpqima.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2rvszuyok.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gt2uddmfduk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2iyknrwtr.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gt2gjoauthx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2vpduoxjq.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gt2pmafgdbs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfkyfwbo.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqacwjsc.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gt2rqinofhr.html

[Q65] 回滚事务
来源：http://dali.svipenyu.cn/Article/details/gt2osxewakq.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2mopcsdig.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gt2dhkbqhwc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gt2rujxiscd.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gt2iqfrserm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gt2gjkaxubp.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gt2scvuemvh.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gt2mxotibox.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gt2tdvxgrfz.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gt2waaoommk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2hnlidgnr.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gt2ndykwfpu.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gt2oobvwlfx.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gt2ujjowlyu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gt2gkimjsnx.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gt2rokgddev.html


<!-- 参考信息 -->