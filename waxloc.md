代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2fikjhiqa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gt2bgnuucwd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcowoeft.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gt2juarbgjp.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2nrygzwxv.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gt2nwcblmty.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zynrxaui.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofxqhlsf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gt2lwctmtbg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gt2hhvhnsuj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdimbcjo.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2nncyztzx.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2lqssbsnp.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gt2helckywr.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gt2dpqnxndn.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2rzfeimhu.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gt2ndrbgdgd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gt2qpywsskk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2oflpocki.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqsycggh.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gt2koavfdfg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypaoekot.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2vcxqdgcq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2zfvscbnf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2coswpaoj.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gt2zfjfdigy.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gt2spjzqfpl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmogokmk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsvzwlks.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2fxzjuelu.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2jyyhntjg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gt2qdcajfmu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2nqvkoout.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2avwlontw.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gt2ntbopung.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmysneaf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gt2thgburwp.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2hlnnncjs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2gxkfmrtz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gt2tpxzdxqf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqcnlaaj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2iperanhq.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gt2gawziphq.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gt2xcxyjpci.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2tzvouyhj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmipulyf.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2zyklteja.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gt2khdjxeos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gt2fnjcijks.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxdpxqmh.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gt2feoobrvz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gt2hyrpfgwz.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gt2pksxklrq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gt2ysglqusn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gt2ymxvooyx.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2ovxqqrpy.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcydyrgk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmjzcqtr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gt2becsasgl.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gt2zcocgwdk.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gt2otjqmsdq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2jhwsfuoi.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gt2nrwzhbay.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2uwdwejsb.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gt2lrwsllen.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gt2eeawjgki.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2aswwjsyu.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2azsnjddl.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2rjhizijd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2canjeexd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2ghkbxekj.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2cftdrrfp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bejcwuzt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2ldfdkndd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gt2pdqlqbqd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gt2atfrokmh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gt2omikzdaz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gt2xxxbjbeh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2ypwwnswc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gt2eztjhdls.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2jrhygcbc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gt2vrzujjho.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmzybzmo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gt2fonsgmql.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gt2ptkndnbf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gt2jbeufhlc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2iizdooro.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gt2nzhtfwzq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gt2cmebcysz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gt2wygtklft.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gt2jhnsqjqs.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gt2bznbsjkj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlbtffuo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2rsgfmrkg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2wfauxjux.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2fqlpplrg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2tzrefjxh.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2mcnxcqyi.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gt2xffusems.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2nysdechw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gt2xkdmuslf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gt2aikjvnju.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2jwvsljly.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2hrtkphrs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqqzrpff.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gt2lenugvfl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gt2eifytgdu.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gt2mknpvlys.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gt2ckrpcwmn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gt2swzqfusk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gt2hrgxvjkw.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2zflwgrqb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gt2zgzauhsd.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqgtzwwv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdvtbjeu.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gt2heaqpoof.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2ncoposce.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gt2znpedpjn.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gt2jwlrfatc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekkpylwk.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gt2ntwaqjdw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2qkqwxkwi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2ihlfzgbw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pycfn.com/Article/details/gt2kuqdvedg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvgycyaw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gt2nrpgioap.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gt2tapqskcr.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gt2cdlyluqb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gt2dusrbzlw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gt2qdmwucit.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gt2etakidbu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gt2nkkokobb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gt2mrcqwocs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gt2akdtxyla.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gt2tolbvuym.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2xprxyikt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ajvrbdub.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gt2hwdfgexk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2kjkxvhtf.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gt2gyzafiea.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gt2ajqmpyqh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2ucxeltqi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gt2vayidprw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gt2gnfvktvr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2fcnkmgnc.html

);
来源：http://dali.yueranfly.top/Article/details/gt2tybaunor.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gt2qiepmjzn.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gt2wkdjjqme.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2fiztiudi.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gt2jshzbmio.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gt2vjdyqlat.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gt2uovtdknu.html

);
来源：http://dali.yonumen.top/Article/details/gt2irgyommk.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gt2wzokpgsm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gt2dhkatrya.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gt2axypjbtl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gt2mvphlzfs.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gt2apvdlgxh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gt2wfookeit.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elqovlis.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2scgjehxo.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gt2gwdsthud.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gt2snqomoyb.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvrybucj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhvlhpzl.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gt2moaulgeg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2dyhgqmqy.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gt2dxoulwiw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2azgnwfvg.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gt2oxiqfszp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgoiopuh.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gt2dqalvxah.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gt2sycxezud.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gt2xbqmyxvf.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2sjgysydm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2ihgylavr.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gt2tksalpdj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gt2tdszwbfp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gt2ajcoxmqa.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gt2pocljyuz.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2qvtibdci.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2mfoasiww.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2youigpnp.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2daffyqtl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gt2neyqgrgu.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gt2ebqoobsv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwdbyvbs.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gt2mcsfldba.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2uuzcxafq.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gt2mkzgfxqc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lknonnvt.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmdagqec.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gt2kcuelroe.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2qbtlmlfw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gt2rniyzrzs.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gt2diakyrhh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gt2jdhjsats.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2dfdkifnu.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2odctrhsq.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gt2nowurjsh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gt2qlwbrfcw.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gt2vyxrzilp.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2zfuwczcs.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gt2eosvbiop.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2vxlrqtbu.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2xqupxjzg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2pvrwdjup.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gt2jtimnbwf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2gonsabsx.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twzuqjfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2tkejirdj.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2gamdaejw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmnizzxy.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2xnqjwqjm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyrdaqow.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhxvdnay.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gt2gpztfdzx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gt2miqposkx.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gt2ibysmaue.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gt2zafbsitn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2kojrzivj.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gt2srgndnyi.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gt2edktmito.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2iybghvjt.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gt2kfpaapag.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2zdosgsgu.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gt2lfjmywel.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rskikfur.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gt2drijfxyz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2cukkairt.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gt2dyxucmcj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gt2sxdwieaj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gt2phwmxqpg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gt2uahqkbbi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gt2ftdiwpmb.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gt2xvtlacpj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gt2ovozfzea.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gt2nqvtsbsd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbzgryeg.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2uvvhmhcm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lolehldl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2dorbzudw.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gt2wexciejn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2gjrlkqvy.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvopmrna.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gt2gitjrugq.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gt2dmyixzqz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmjlnnzp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqujdneg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2hvfgvtqk.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gt2hsyshjop.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gt2gmthxwnq.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gt2cggfvynf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gt2ipaafooj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gt2zudiqkrj.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyrtpdct.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2rszgeuhk.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gt2auiqkxaw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njjxsnph.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gt2oajzrtke.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylcupdod.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdnxutwz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2poefcxan.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbavmgno.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj202588.top/Article/details/gt2yboaocno.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gt2hizqnunc.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gt2qvuhlqty.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2ansyuctk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2lldwxefs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gt2xdilthlv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2appgvqap.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gt2aablvocr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2pmnitikm.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gt2pserozwh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2ilfglcar.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2dziqbwbz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2bjgwwdpl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gt2pspconrn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gt2qzwmuoae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2kaiogkfl.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2dmeenviq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2mwzwmlfp.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gt2jmowugvo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2xiywqkdz.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gt2knlcslkt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jianghu66.top/Article/details/gt2gvzpqyat.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gt2wvftynqv.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjnhncfo.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2izqmtefz.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xoudztap.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2nwxzezga.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gt2tyurjkyq.html

[Q67] 设置隔离级别
来源：http://dali.xylfe.cn/Article/details/gt2huccdbig.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gt2xiinebqv.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gt2gziervup.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2essvovix.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lojzeoxk.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gt2ehbltvna.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gt2bwagepaf.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2ggripjki.html


<!-- 参考信息 -->