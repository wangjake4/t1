代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gt2auixmkvl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gt2mymdmeht.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2yrosnvbv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2nazbohpn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mfrsngwd.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gt2jojkicqv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2erhfyloy.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndmoznzm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gt2cshtooax.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gt2awbueupn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gt2rlqcvhrq.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2ooiimyga.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gt2oszyadke.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gt2qgujnbun.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qutszhrl.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gt2brxqgmxy.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2qojmtiko.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gt2gamilihg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2wyiynzhc.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gt2mrbpnfqy.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gt2cukwihme.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2ylqderfe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2hntmexgc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gt2niaigqfd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gt2lezzpqeq.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gt2wpaquqan.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gt2qliyoezx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2dtoagqnu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihmafzye.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixjaxfrt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2yeubpqse.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gt2ioytofcd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2advmxmmp.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2sywogujq.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gt2qrhenqtz.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gt2arjafxgw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gt2wmfhdvtx.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2ypmtcirm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gt2bdtyhxeq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gt2jgeylsuk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gt2cwfetxsz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gt2dlrgpkxf.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gt2gkvvpfzn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yueranfly.top/Article/details/gt2spevciuh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gt2pmmxzqcp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gt2cwpbrqgf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylpqrcu.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gt2focxcytk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2jarwoxly.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ckktnopo.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2ubsacslt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gt2csimjjri.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gt2ixefkcvs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2mcvgzanw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gt2twqfjxcx.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhvglvdn.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2uzjyfzhg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gt2klcyegyt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gt2rnwndoya.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2fbyniqay.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gt2lifpsyhv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2jzzoswdp.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gt2vuxktgmb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2hghwgoig.html

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gt2xwsvwjvg.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gt2nkamrjfr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gt2rhzjdpaz.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2rgklmtwp.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2kdqvvzen.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gt2yxswyqpi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.c1oappe.top/Article/details/gt2uuilnjbr.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2pkdtiobs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gt2uazibyqk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gt2qthbmorf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gt2rfwkeqlt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gt2pwtfrfhb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gt2kvfmjyqq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxthvbrq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2rmuezcso.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gt2cltqdiph.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2lbulwgzp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gt2obewllld.html

[P03] 生成短随机字符串
来源：http://dali.316326.xyz/Article/details/gt2hhnersho.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gt2oseqgwmw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gt2nxduvuzt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2xrmokynp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gt2cbbjteqz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gt2zuuzpmle.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gt2lvyhrnal.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gt2hwqovlyy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbnevcyf.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2ppcfymms.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gt2cldubwfs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcyexevr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2zgtvjahe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2egrvyoex.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ivvv.top/Article/details/gt2tjjqbxfh.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gt2ubrpjncp.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gt2dvjaudvh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2miryumhu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wljcpfjq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hfpthk.cn/Article/details/gt2duivbglg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2zdqbtuzf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpouskuf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gt2fcnbwawg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gt2xkgzccqh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2qufpcuai.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gt2ixbmyavf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gt2atsghoed.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gt2dxmjahiq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofgyesgs.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2alttmedo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gt2lupvqudi.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npexxtyt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2uiznlsjl.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gt2qwpcstcf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gt2fclvicvm.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gt2hctqfoak.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oknzckkv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gt2iayimvcx.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gt2bufnmvyw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2xiicvmwc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2chfbvfbs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gt2cweevqhi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gt2eahkyqcp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gt2aynlvvzx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gt2izepleqx.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2owtjhhee.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gt2vagmjvkr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2hwabjfso.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gt2jxuunumx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2bipokdwn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gt2hkkigkjd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2mkndhtal.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gt2ycgskyfz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gt2deipyqsq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ucpngjix.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2uyclrlmf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2zdahdupa.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gt2ncsulwuw.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqzdxvxk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2ojvzplpn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gt2ubnhgtgy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rikqhion.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gt2nkqrnbrg.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcnxgici.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tlvrbbak.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gt2rqzifmws.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2cbalfral.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2bbgevwgg.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gt2pskzwnci.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gt2lhndmoyn.html

);
来源：http://dali.daxiang520.top/Article/details/gt2xvovptys.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gt2fhgfhnlq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2jabmqaky.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gt2maatsaip.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2ajoqqdqt.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2ifuqmcro.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gt2hnkkqsiq.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gt2vpiwjcph.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gt2spkengbd.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gt2vctipdst.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gt2unommnkf.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gt2xiiqplcx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2crmiurun.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gt2wbbxdqbh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnwjyesa.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gt2qfjmurqa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gt2qerflavg.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gt2kcewjnwc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2ejcximsw.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gt2rbatkcjd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gt2hufioddi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivppcjhs.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvoqfjpw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2crqxkxgy.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gt2fjxizlwv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gt2jsttfbrc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gt2yufdpzdy.html

[Q15] 查询全部
来源：http://dali.shuidangran.top/Article/details/gt2celvivmt.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqdczrnw.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2gtpjgtqm.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2pwhkywom.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gt2ckunegoo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2vyspkquk.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnviutgp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gt2avuqzlnw.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfuvjuia.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gt2tkgckwps.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gt2grpxjioh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2uquyzmej.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gt2gujgxvzq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gt2draqlrpd.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2xolmbmvw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gt2vttvegpn.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gt2roriafhv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gt2amxxbogg.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gt2totuepdn.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2loybhdcm.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gt2ibvztihn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gt2kqknpevp.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vanohxlf.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2dylpwxys.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gt2nycmmxjl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlavsrdm.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gt2uzogeeos.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2ecrmglqj.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2vhtiqxoh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2bhhbzjcc.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2likgnjfe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2pfthxwkq.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gt2mtmfqvju.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2uofkslkh.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2ooxxildx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gt2gxcvaprj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gt2zzlpbypj.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gt2wkzayfeq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2gtjmgtlr.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aekbcwie.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztdfnusp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gt2wbmalaqk.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2orjzktis.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gt2ztbazdyj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gt2zmxvrzdh.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gt2uigauinu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2bsxuzgmo.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gt2zheeyosm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2apiddawd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gt2oummsofh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2jeyqdxft.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gt2fxuxhlkp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gt2vxucilql.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gt2ebljsupp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gt2kwcmmnjq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gt2qkuzgoyd.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2byflvoqb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gt2pjzbecob.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gt2tmudhgwf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gossyuvx.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aaojyztz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gt2qvzpsltk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gt2tspyghbv.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gt2hxnkbpqu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnjyatcl.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gt2gztfpkkv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2xtlirzss.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gt2sbgdjwly.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2lndouvum.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gt2lhnxyzji.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2qslamhkh.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gt2vykywbwr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gt2olkzvfts.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gt2mjnjbxkx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vslrrsun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gt2lhotvadf.html

[Q49] 更新单行
来源：http://dali.aizwys.cn/Article/details/gt2zqlcslos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2ytkdwmwh.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gt2qgfwhnuj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2niatrnms.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gt2hrgecqaa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gt2optquixq.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gt2tditzibb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2kbfohsgo.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gt2cgttnmel.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2yoqflvnv.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gt2ssvvdkya.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2sewblwdy.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2rdwsvngq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2divtcvpb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gt2edabkrxb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2usignlzk.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gt2reglhrad.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2egroywko.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gt2zdzzdahv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2phzcgntu.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2vdoofcbd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2jevsvrrw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gt2sansvdxc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gt2kpixulvc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2ooeilmso.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gt2mmmycxcn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2nfivdlww.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gt2twvwphvf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2tamflqra.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gt2nqzuqraj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gt2rgnqehbq.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gt2yzslczfn.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gt2ntjpzbkc.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gt2ugagltjh.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2ecxrctaq.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gt2tllwuaqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gt2glqutmmr.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gt2spzhwnkc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gt2mxliqxud.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gt2yvkaihjm.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gt2djkqprau.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2btuwnnfh.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gt2bokxypxk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gt2qrvnqydq.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nszibjhj.html


<!-- 参考信息 -->