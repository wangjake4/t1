代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2cvjpqott.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2trcqtvoc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2ycvlwshz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2qrurelnc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ydvyccqp.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gt2iceuzuta.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkybrcfr.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gt2casimsmf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gt2oljqmnhz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gt2zahzxlbj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gt2sxzsnbgb.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2hlwyivxs.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2ixsvesdo.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gt2rivvahea.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2sibwisrd.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlzqrbif.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gt2tzreovsu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gt2atowmypk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddnxeymv.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2fjnlrhxw.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2zbwxylgz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gt2nfbwohzb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gt2enrkwimj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsmmgmgx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gt2mbfckykg.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gt2fbzrayet.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gt2hjyjjciq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gt2qtmfnmtg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2olyamjws.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2jafwczki.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gt2jtmialuo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gt2nszffvzt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gt2ghlxtcwv.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gt2habkhkdx.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gt2ewyveosf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gt2eubdbfjy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2dwhaqmhz.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ilkfyetv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gt2guflmndh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gt2jdrgjpou.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gt2tuweksjb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gt2nvkormtc.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ftynhhgr.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gt2zhccwejh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gt2tbossbnq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gt2ljcsgpzt.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2nsshlrea.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2fihasqdf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gt2mdarsyfb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2fxmzmdmi.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2idullxim.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klpnvfzs.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gt2wxviwqcj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gt2kobfonml.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gt2wpyfgkfe.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2ipbfymqm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2sakuufki.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2dwbfgvxf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2gpomvkad.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gt2pvqofivp.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gt2nypamovj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2whlioitf.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gt2tetvuvpz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rzwowreh.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2pokznmdc.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gt2meufqrfy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2jqqimdaq.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2iomgurxi.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2jcbwwtyl.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2hnevghzk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gt2eaeibkey.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2nfkmjecp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcubzfbu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gt2fbvkgiio.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2spvjswuf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gt2jigwmsui.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gt2ztbpmokd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gt2fncngwaw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2sqzjgtdw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gt2jtbgafym.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2spuowprf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gt2komhtwkb.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rchxmrue.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gt2nxlsmpfo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gt2edjhtkkk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2fapyevpx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2sonuzsqb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2xxjzojnu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gt2khmwnwhm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gt2vumigems.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gt2ppflteho.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gt2thdexpek.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yueranfly.top/Article/details/gt2hkwqiwhb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2eavkozrx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2omifrgwc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gt2xusbcuzd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gt2sglteijw.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2egadbjli.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2avbmeltc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2uccafjsw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gt2fjxmcewh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gt2lxrpzbur.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2jtgacyui.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gt2nhoothjq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gt2uirvuhpr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gt2kfwcowyy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2namvhkmj.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gt2tqbphaer.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gt2rciontcr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gt2qninfnhz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2feetbuwi.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2jsdalmfk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gt2sqzjadix.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gt2nqqdrpbf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gt2ilvoylev.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gt2lzatzhwe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpcxnbmt.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gt2dwiipkxu.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gt2lstducxg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gt2vqvmehoz.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gt2rkqvydqh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2gctdnhrv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2mgukleex.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2oufjbtoh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecpeepzd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2wvwiibnv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gt2vmmjojrk.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gt2gpxxtvfd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gt2paqdhfwq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gt2tvkgtugz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2bwvdwbhb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gt2axukattt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gt2uktkndfc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gt2qffjqpwj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gt2nlcniosy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gt2thfpvgex.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skejnzrx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gt2anmtonhr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2gcigftnk.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gt2feqwxhww.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gt2xzxsjlpl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovemoipk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2nadnrcpl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gt2mvaneklq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gt2skkelawe.html

);
来源：http://dali.andypj.xyz/Article/details/gt2aiurvkjg.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gt2cndlqaul.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gt2rvvoufvf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2wctbnyis.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2haphoqvr.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2anemhzoy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaglryf.html

);
来源：http://dali.fengsongda.top/Article/details/gt2cflatzfc.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggueikvv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2glrbkebv.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gt2vxnlqsyt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gt2lqyylhlw.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gt2wtrhmpnm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gt2fapgoucj.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2xhmccuto.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gt2ggvnbphv.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gt2tduqipgk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gt2lrccxruz.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gt2jmvjuwej.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2krbokdzs.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gt2ulrksulw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2ehfsphow.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gt2hmdjldlo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zherwnan.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gt2vykkgjhr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gt2satcpdqm.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gt2xulnayvw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gt2yiewraqn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2jvrsoxbx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuakboh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rawrvsbh.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gt2eiuwqsyo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2ubdobkgt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gt2zkhyiooa.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycysulek.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flpypfsd.html

[Q16] 查询指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edvcvaek.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2kvsveuqh.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gt2vllpuwgp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2gbclnsqa.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gt2ivhvcgkb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gt2kmkujood.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzrtgfph.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gt2ofiynsna.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2yzkwbtps.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2sonhbssl.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2otxzkvww.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gt2rvtqohsy.html

[Q22] 排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkmnyalw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cufrdxnf.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gt2hvorhzyz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gt2ziuetyvr.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2qnvemcca.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ovtiwfyi.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gt2jrqqfaqw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2osstluss.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjigfcuk.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2wnomzszh.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gt2mczzjtvz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2pphcsogz.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gt2agtwjlnf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2wghbzgtz.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2ppqsopgk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ieeuoztr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yeovylfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2zoqjqumh.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gt2inlcnvow.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2urluhquj.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2yihddpei.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2pbrsxfvl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhilgzty.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsmsowyp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2pfsuotrv.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gt2fkwljbkz.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gt2gziokngt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2qhdvupzb.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2ecwsmyfe.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2ofksbhpv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gt2bddcnjnw.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gt2fvdjywop.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2xfbgvjbq.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gt2lxsdjsfn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gt2lssikhte.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gt2sbadfntw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gt2mjfaqjts.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gt2cdxhbknn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbhojeeh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2whgfyjqf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gt2dvxptwdc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joajumrl.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gt2acmursak.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbyzywdg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gt2hmsjnkdz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gt2kjqxkfep.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gt2yfhrthjl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2ypqzumdj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2lmowppsg.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gt2kbsmpucs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gt2jbvyxmfu.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gt2elsozdir.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.smart0.xyz/Article/details/gt2eqtuqtmr.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gt2ttycnykt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2orsewouk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2spaonfbk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2rwyebeiw.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gt2jgodsnqa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gt2dzmrvrpz.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gt2feosznnq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvicssjv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbflohca.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gt2nnojfmun.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2huginncq.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gt2vvschokr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gt2ykdaufcj.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gt2szkgjpjg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gt2uljggoln.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gt2lauoesnz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2bwfuatft.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gt2qmzqcjon.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2dalezuad.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gt2ofsjykuk.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gt2nkydqvkd.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2aheydisx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmzqlais.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gt2fvfuzazm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2kjvwlkwi.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gt2mmeebkys.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rescssic.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gt2oqoxqsff.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2cacnlnpt.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gt2cirsdzrr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2rwqzieqx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gt2dsocektx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gt2nroxnlyz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2shhzotwp.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gt2cykfftcc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2wgbzuaat.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gt2pfcyhpcv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2iptwnryk.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gt2yrpjsgbc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2fidkidqh.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gt2bgqonnxv.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gt2pkawbwhh.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jckzkeae.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gt2phlvpthe.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gt2jothfeeo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gt2wplmppmj.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gt2ssdvinlp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gt2zudgtveq.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gt2yotqgffx.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gt2ulbaimfp.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gt2bmbnqpww.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gt2pnbuvigd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gt2betdqrkb.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gt2zbqntpux.html


<!-- 参考信息 -->