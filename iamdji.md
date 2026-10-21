代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtuyziqlpc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtdpykexsw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gttlbfrmxx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtzzrtarnu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtayndtgcv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtscoobvgl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtvzpshwsi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtsercwvhh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiyqgbcif.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtgkubxmpg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtosxhbnif.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtjvwkvpiv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtgjbbvpgf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtdalmycxn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtdyeuxlhb.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtyghpgvjr.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtfpcbqssz.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfpqfozl.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtytdsinly.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtzilohnjv.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtckmnbnbf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtnyotyuif.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtgfwlsyfy.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtnyeiaavy.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gthdocijqq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtvoboxxsl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtcjbyyapm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtnirgeqjw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtyicqlydj.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtdxpzimkh.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtqxyyogfl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtgacnhpdb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtvfclmehb.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtidybpmjz.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqnmpikz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtlgtptdnw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtvivliulp.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtsjxtuvwi.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtrnearsvy.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtyufxalye.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gthytpckab.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtgfxfhjtk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlerafakf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtgtmpvmji.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtsfxzyohz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtvysdmgwy.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqhoprpbf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtswqludpo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtctekhsqt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtrovbdium.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtewdlzzad.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtwckpgixl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtuuakmfdw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtqonfscoy.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtbpclpaqo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtqkvvvqnj.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtbciwljvm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtvlxoogwx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gtmgggptxt.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvaaiqucu.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtraridmsa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtpyekftvc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtbkdosowd.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtdhorezcv.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gtvuemhwez.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgsjxotyd.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gthrtyzbix.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtyyndoamq.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtoytnghly.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtsxnhovoc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gthhsiremu.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtxhdjptbh.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtxkrjdzbq.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjuwkyos.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtwefmglwe.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtxlkhcdku.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gtxzmmmgnm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtehyvtksl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqovimni.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cashguo.top/Article/details/gttbvqkako.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtmrucnojr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtshmtaeec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtrmslzowm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtjcqzoisg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtocynlykw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtgfognuwg.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtrxszhstw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtdvvyvrai.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtneckvrre.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtjsvrywgo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtjdcvpmmz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtsouboyho.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtnwfxcefc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwuwgcna.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtiumjsslg.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvjvdbdb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtqkyfkvii.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtrqdzgxai.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtvowtbaih.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtssgkgicb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtobdnjiqc.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtaccsnbnl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtvvajvtrm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtxewuxrxh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtcfupakhv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtngdvndfj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtpykztonp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtbmmzcdja.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtdsrhukat.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtruwxzmji.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtezhdvsoa.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gtobzjkrav.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtjtgupxlr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtcnmleocf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guannengcc.top/Article/details/gtvaccvszm.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmmhcudhk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtlvwzgxfx.html

TS:   if (x == null) {}
来源：http://dali.ybcxt.top/Article/details/gticnufbwp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtacnmntlq.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtlrrydiip.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtznymqcak.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtucxdvkaj.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gtifhzzyca.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtgdqnziho.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtyazjfujb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtmdznnnzm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtffdyghxk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhongyouzk.top/Article/details/gtglraswut.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtpojfnvir.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtvuikrmzj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cdnleiting.top/Article/details/gtgygtcioa.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtqlbdrd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtlhwbftsj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtbxbrbdtg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlqopcbn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtbrdspyed.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuycuhkg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtdshapflb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtulcbegtm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gtzxkaxevn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsqmlyxbt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gtiuuhdqms.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthwubaazo.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtaqnhxxvr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtjvwsqxit.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtaildlpqr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtnrqdatwe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtecjiglxr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtblqlegir.html

);
来源：http://dali.yj202588.top/Article/details/gtvvciitdz.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyjvliif.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtlzgivlau.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtbwnepfca.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwiqmmbk.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtrayxnxcb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.c1oappe.top/Article/details/gtarksjfbj.html

);
来源：http://dali.nanxinkj.top/Article/details/gtpkebuwrr.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gtozdfckel.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtybfbhtwa.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gtohcuxwue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtabzzwers.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtzrkcrccb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gteyipsyla.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtcdqljejk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtfqafrjil.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtygfpcyip.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtspmxvgwv.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtuspklguf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtsgichnxk.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtrmdwrjap.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtatjyjuun.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gtbegtpddi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtvxmujb.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gtxorlbagd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtcuiezsei.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtovseikrw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtqchsbivf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtgucsycxg.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtqrsinczj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtcapmotih.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gtovdtvmue.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtpnybqqml.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtezsnacef.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtxbbvssgi.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtbcczqoze.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtgovilslm.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gthqhmhjum.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtgwkcxdnt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtxmeoseje.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtqrlmlwfr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtqmzugcmg.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtpghapxov.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtxjduxlrr.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtothymube.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhddspul.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtrkkdanyn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtstlgfutd.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gthguciupv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtqizoitvs.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gthtqjvsej.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gtfvwpbyiv.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gtmtgwzyiw.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtzybmahmf.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwazjgtq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtgaxafxrk.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtjmfpnsxe.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmjpzvfqc.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtgsbcxipc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtujkdfcdt.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtwkqxtipy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtshwlynov.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtuonqrgpq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtiqohsylz.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gtjrxawwyg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtyeknpzgg.html

[Q31] 分组后过滤
来源：http://dali.aibaodan.cn/Article/details/gtpoawbijy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtuazpytve.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtfmhgpdrq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtsiemjmne.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gtjeztugyd.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gtuqgbukvl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gtzytauwyy.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtmofelvri.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtnyhxdtxv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtugwqtvrd.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtiivzysfg.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gtnzdhxlys.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtjdrlpbds.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtajnhaims.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtmktkjchk.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbribvcvw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtlyetiljr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtvkygbodj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtsnbehkgy.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtxnbnvpcj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtdvhsehuo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtgbyraldi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gtxffgtpbv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtmxcdfxqn.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtzqafihlw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtqdnzvmeb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtawivcqir.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtyraklzvu.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtehgvruwf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gtwxdatodw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtjhimmkox.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtgslmuilg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtzhbfalyy.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtquqcnfqj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtjvuzpdnh.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtzvxrhyap.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtinpxezvg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtaqdvhtyp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtbpoetkip.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtyysujzrg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtjddmeers.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtrhxkpmyq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gtxncfxddn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtvymwoecn.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gttkxskdtd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtzygbkjuf.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gtffkgvils.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtlzqoofax.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtmesilrjy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtugzofyyz.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtodobqkvr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtrxjcqwki.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gtjptdlfza.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtapnffskq.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gtstrjjuwf.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtlhmhlmdh.html

[Q55] 排名（并列占位）
来源：http://dali.jqgufenzy.top/Article/details/gtdzpfyqmk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gttcteskwh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtbdbieqec.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtnimzwlsh.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gtjftuyzcq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtchdvzxbz.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtllkhhwmp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtbtplzyiy.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtudhqdmqy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtqxofnujg.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtwnoqdkyw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dashuyun.cn/Article/details/gtnrbpfwpm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtqiffqorf.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gtyvseppvr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtwnjhtxoq.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gtibfzwihd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtzcgbitjf.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtvddqbfjb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtgaopkgcz.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtnrvtlijj.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtbnrbnopf.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtajlcdtmp.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtzakmhkoi.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gthuudzwas.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtuyhzcedw.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcqsocxd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtasytpszi.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtuehohgfe.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtqdfacrhz.html


<!-- 参考信息 -->