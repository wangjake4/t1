代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2mvgoojnu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gt2sqhlsfbl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2mgiulxpu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2ghpgslsh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuixvddh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2aasgkqon.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gt2zcwvbmjz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2bofocjhw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xpgbqtco.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gt2aueioakn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2otbzxzql.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gt2pwikyxjv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2niwwmnwv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gt2qoguatst.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gt2frtwcvsn.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2xworghgi.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gt2tljyoips.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gt2vrtloqpz.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gt2ewkcxmcj.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gt2iqimfxkq.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gt2bqkdtiwl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucltplad.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rblaytlk.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gt2dxzsqrgh.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2jyjknxmv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gt2sbkckdok.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gt2kovfkzyy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2sxhyvobt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gt2qmbbeqff.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gt2kolwpzmm.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gt2nmmhdgpb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gt2rucrrrxp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gt2xbdtqqnh.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2slndrunr.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2vhlxrkqp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gt2yvafoyor.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2csbtwzxv.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hidvwgke.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gt2yknsuvag.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2kxnqjoum.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2czsrtvtn.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2aibgdlwd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2hrhuxxof.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gt2ekyxvvdw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gt2heqeshce.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2blxqjaks.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gt2kriulrbo.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gt2rvlvrewq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gt2mfslhlxs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gt2vjubphxv.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2tlnbhner.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wecdxllo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2bbarvojy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gt2phmewslt.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2akozgldv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gt2sicbhzmv.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gt2oapfvkty.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gt2anqtsidz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gt2lmiiajiv.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2szwdccwh.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2ydwmrqcq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qasxzrit.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2uncgavav.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gt2ubblieoa.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gt2akddltgx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vjgrtzpd.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gt2madfypfk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ymanagfb.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2caaejbuf.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gt2kpypxngp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjxvynwn.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2tunyziwb.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2knzwxckz.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2mscwggmn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2baekfmgm.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpofynln.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gt2idwjgvzf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gt2fkrgfiod.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gt2msvtvjxq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2tccfdopn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gt2qdwzaooy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gt2pqjirrlg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2lpveebcp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xchswpbo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2gejrlcys.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gt2qpdbexzj.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gt2itxaewmz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2matvgpvs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2iqfypgkb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2ldyxgnuv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2nprylcho.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gt2wycjypjz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2bwdfzxbx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2jgjeymmy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gt2nkzlcwke.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2aompqpjy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gt2uvqgxrle.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2otqaenvc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2xqmmakjn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2uilnbarx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2yrueqqcd.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gt2ejidxltm.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gt2gtwyfxem.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2jbubdlrn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2gksxeeca.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gt2jjabkven.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gt2dmedxkct.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gt2owolkwyu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gt2kvrtlqhr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhmvhew.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2yizqedzk.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gt2umipvyky.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gt2kszdsusa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gt2iornnhim.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gt2ycaepdfj.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gt2ceuisdmm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gt2tmbrwvve.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2sswtmmzw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2kbcjrcer.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izhncmrt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gt2bfcxkmxt.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gt2pllwkwar.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2qvsrlibb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2sjufjeak.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2lrahqrco.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2eiloseaq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtqzccuu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2tfelpobp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gt2chhjzbim.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gt2edeewesr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gt2lpnenvlp.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gt2ghddfvos.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2jqejcgec.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2qodaksnh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gt2pwgphcbj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2oetkgtlc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gt2nirrugrw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfcwgrep.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gt2kezmmypg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2kgfbaufx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2sdyudbwf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2zkycplam.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2yrxwzwoi.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gt2ttkdwjgd.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gt2zipvrceb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2uamldtpf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctuufrqs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gt2yzfajpni.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gt2axknbhgd.html

);
来源：http://dali.xziqi.cn/Article/details/gt2lvgsxvfy.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqtuuldj.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gt2xjlgovbj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imfbeonb.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gt2pqukdxum.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gt2dkxpcola.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gt2rkpzclpb.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2fznfsonc.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gt2zlfepync.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2ingxeawy.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gt2ncrevxtf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2skxurqrx.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gt2xqkgbweo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gt2lxmqbwck.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2hlltqslw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gt2hokvzbab.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gt2btsmscaa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gt2ddcxoygc.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gt2njyofgnv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2xmyzfzzr.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gt2eqdygofy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2pplzwhfe.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gt2pyrysycp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2bpobffbw.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2jbqfbqyr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2kdrzukpy.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gt2gatfgjci.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2daizokuw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2nrrsezof.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gt2dbdhvpjg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2olxttuma.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gt2tiztujzt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gt2ceutbxhm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxvfscwg.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gt2ikcoebvn.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2ktmsbpfs.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gt2gbbnoqil.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2bpqhktux.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gt2vvbdthip.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxdmlfwy.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gt2xefryydn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gt2wilslluk.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gt2ederfyzg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xceuceqi.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gt2bwfnlxbv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2yybgugto.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gt2ubbvxfcl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gt2qpkxrncg.html

[Q22] 排序
来源：http://dali.yonumen.top/Article/details/gt2isalmbyq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gt2ffwuitea.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2xhybdvub.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gt2gzkcjlwr.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gt2wocguktv.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ytzfiaeo.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2gupeosgw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhzinnou.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gt2nnnkkbwk.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2fmxzgxvr.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2pckfugxu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2ewnhqlrs.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gt2umulblnv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2vtizidyv.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gt2wsnzkefh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2pdtwrfee.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gt2vispyidb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2htemidgo.html

[Q31] 分组后过滤
来源：http://dali.wangdashe.top/Article/details/gt2zdpqckxo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gt2qssaemin.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gt2muimcdrp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2guxcfarf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yalxrwui.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gt2ymjkfgqj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gt2mashxgug.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gt2aethzylr.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2ziwmsykk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gt2zkyehouq.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvjxksdo.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2pukhbzau.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gt2kskocmkn.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2toyiwbfe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gt2fucobwul.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2recvjzcg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gt2polqxcwy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gt2tfqrdpky.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2sipjzxtq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gt2efkwwiix.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gt2qsitkzye.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gt2ynavqmky.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gt2vujvgjni.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2dpenhuhh.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2jkkycoae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbuzmtoz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gt2cngiwmew.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gt2hcfmckrj.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2jgctekxo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigufen.top/Article/details/gt2kddisiqz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gt2zicxjweu.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gt2rkllbhab.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gt2rbtnswzd.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gt2dyyrbiid.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gt2ekityety.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gt2atvjdgtr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2elssveja.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gt2dcisvndt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2ghnpkivd.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gt2bwnfunru.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2wfknuuak.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2iuqhstun.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2bmvfmsai.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gt2hsnxyeql.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2xlwmyynw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gt2zhoswwik.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gt2jnuwjeag.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2syxwsjvb.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msfvutjp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gt2ipbztpzs.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gt2npenkmxs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2ztldqxqn.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gt2yirbjmuc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gt2pdfkvcmt.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gt2bflgmcpg.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gt2bfyvkozr.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gt2ikjseqxz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cslnbbpe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gt2erhucwrc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2fweajhjq.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gt2ralcocud.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2zmmlnwhs.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gt2rijvrfla.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2ncthhpgd.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gt2gxzhcyuj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2zqnzorrg.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gt2dtwoeewm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gt2uicpoogb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2cazamhve.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gt2dgylfyug.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lucunudj.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gt2hkwoistx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2uvlgoegt.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2exxxxjoe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydcjraep.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gt2ooaswrqg.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gt2ojbdatjg.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gt2ajszeqvj.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gt2qeqzpaxt.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gt2gxmfzuqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gt2zdhapwab.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwmjcbbd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2fahaqgjx.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2bayotijt.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2mmsqwbyc.html


<!-- 参考信息 -->