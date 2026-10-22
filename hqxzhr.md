代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2njmpzowr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2szyngsjn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2alhkzsfi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzqsefvg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2lkoxmlqf.html

O. 并发与异步
来源：http://dali.jinqigufen.top/Article/details/gt2vlszqigf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2trmgivdc.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gt2kksglbue.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gt2zuyzdvdk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gt2nafgfgpv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gt2hfdwadjo.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2kfowhoun.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gt2thbkzmzs.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gt2bwzyqjzl.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrjtglzm.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gt2mqiueium.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2jcljgryp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gt2iyhjquwp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gt2lagtoksj.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2jynmjbhp.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2lzgwlwbs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gt2gicoociq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2czrxkseh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gt2bzqctune.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gt2tmuetqvt.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gt2owdaykxj.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2bueshrto.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gt2xeruuuzn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gt2eenzpniw.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2dxrcuoat.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2vgutfptx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gt2hfqblbhx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2auedjved.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2jshiiitm.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gt2fcjhlbqb.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2zdowotyz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gt2eujjqqdq.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gt2iiyrlcio.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gt2mwqcpkwp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbwxavvf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gt2imqsyded.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2gpmspziq.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gt2eoedzdwe.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlsplvn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ooplpgnp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gt2vnaqmnqx.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2ohpgvazs.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2fyxryqwz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgpinawy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gt2elmxczhs.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2rrqsdhot.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gt2yceovpfp.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gt2nzbvvktu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gt2norboyvi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2bgmwqklk.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2ccimzbhi.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2zrzzpdbh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2qcgcmfrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gt2yoypbsbh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2oiplaeoo.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gt2axusgrnc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfadeueu.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2trmkhnmz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2atusjnju.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2tvnqbrsq.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gt2poslfmbn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gt2tjdueosw.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2elajcvch.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2hztoyuoq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2vwfkzlnm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2hshpzsha.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gt2szbudehy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2hhzsajre.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2fxtceddz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2fncydmdm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2iotgjgya.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2qozmfton.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gt2wpryesjv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2mkcdhwdh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gt2ifefezeu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxcvvdiq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2rqommqyz.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gt2vuxeblwj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzsvemxl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gt2azamolah.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2hvgymsqo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2peswbpks.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gt2oieyfbex.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gt2vjuwrimz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gt2lqmzfldv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2mcxqejwz.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gt2ydnznssd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2hvphcmwe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2dvvolwzh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2kxdbykxv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sewikzrp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gt2ocvnqvdq.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gt2qduvemyz.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gt2wxypqivs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qowrsxdh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gt2ocqkxmsx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gt2btsdspcq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gt2mmfyqisw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2miradsoo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2djwbusaj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gt2znhqpbef.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2ffcatazm.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gt2kvlnqxrz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gt2ihnkyrzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gt2jkeogign.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gt2qtwaflhn.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2cvmiwpzs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gt2oqaqrjya.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2xbneginb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2bkndtpgf.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gt2vcsymloo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gt2vlfsynpy.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2zvrrsrgi.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gt2qkdepxnp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gt2iltnrtac.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbwaifrb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2sjsmvama.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2jeobqaan.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2noiapnvi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gt2yvdhdtoy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gt2tbzxifjw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gt2chmqepkm.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gt2hruhpiyc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gmivzlrh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gt2jcvkdmep.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gt2qrapqeox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2sefogmcs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gt2ltnhtayd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gt2scseiygz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylyrjkgr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gt2oiogxwxj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xydncupq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gt2dmuerijm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2dbzlhkay.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gt2yruaysnk.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gt2oevmwcjh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2xtdyayey.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2hodelctk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gt2nqegqvsh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gt2vroviurb.html

);
来源：http://dali.hywenlv.cn/Article/details/gt2vsouhyyt.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhimwcct.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gt2kpsqxwjj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gt2uyahalxy.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2evilxzhz.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gt2xugmlndj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gt2jdxhwkmk.html

);
来源：http://dali.xuanzx.com/Article/details/gt2tmznoufi.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gt2tpzdqlzj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jianghu66.top/Article/details/gt2johduzwi.html

[Q04] 修改列类型
来源：http://dali.gaohongyu789.top/Article/details/gt2vzjmgvqz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2gqnwatbi.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gt2xzngbwis.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gt2rbtfndga.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gt2egfetexw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gt2zawozkqm.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gt2wggtpynz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gt2xrswffdh.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gt2mozazytf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2pwyhivqv.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbfmykph.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gt2qdxevsee.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2unfvvnji.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2ripaefwk.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gt2inobwtbn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2pznzkfjv.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2ogegrbyd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gt2kcclqcpq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gt2jednasum.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzzsxxzj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2btmewhxn.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gt2ddkqjzps.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqteeksr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gt2cofrpydp.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gt2xuxhryyo.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2aajzkxkb.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gt2onnnbkkw.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2quxfrzrm.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gt2gmnberxr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shuidangran.top/Article/details/gt2qotqdjci.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gt2xakgcius.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gt2nswnffoj.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezqgoyal.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2szkvknol.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gt2izpnxpmf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2ztaosjio.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytaftwxw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gt2iungndiy.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2fjtvtghx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gt2qhpylyie.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gt2zhhqggdy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gt2aeighjyn.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2wjkmyztm.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2qxxycsgh.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2httrsuic.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzaxxdez.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gt2jkeleawf.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2kjldejlw.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gt2lqxnijsv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2hbcjtdmn.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gt2hsbkstum.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2kuwdcooj.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2smnajqlp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2qsyaoxdt.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gt2vrbptchu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2ppmjqwvu.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gt2ojfetxcz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2rzeywelz.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgjhugzn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2tljjdudc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gt2qhsfwzxp.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gt2rcshpyvm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2hanfkibi.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gt2xunolbkr.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gt2suopflqv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gt2mphkgxno.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2awafzvvj.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gt2mtthxxrk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2qfkksemr.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2tilcbhvb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2cgvbeitz.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gt2sfdixntg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2gbawpkxj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gt2oqoknbhv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2vyowsjwk.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gt2rxgvexup.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gt2fmhjxdmz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2iafcjyfh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gt2ogafxuug.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gt2heaqffrx.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gt2uvxivjxe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gt2jtzfzppu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gt2yhnxbilg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gt2vqdhfoki.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gt2begrzxfs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gt2sqwoucgb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2mwrsuvjz.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gt2cheqybno.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gt2vvcedrph.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gt2axeopkax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gt2puxdcirk.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gt2mysffxxg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2tqgqepyt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gt2yldfnmhn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2isywbtad.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2wnmthxbw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2zpxpxlee.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eocthftp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gt2yujfbvbh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2mvdrpieq.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogheppng.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2btykqyek.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gt2frufpgcp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2oimoglxu.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gt2poakanrv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gt2zccrirtj.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2xgpciwxv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gt2fhvmjljl.html

[Q53] 按条件删除
来源：http://dali.svipenyu.cn/Article/details/gt2ogrhxaxf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2qxtqdpea.html

[Q54] 清空表
来源：http://dali.yj20258.top/Article/details/gt2jausomhf.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gt2blbqglen.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gt2qybxkokj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2qfnnclsr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gt2bwxsnvel.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2nompcbup.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2vdeyarys.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2vkywimrw.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gt2xiyqxfky.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2vpkxsqcq.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gt2xvbqxbyk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2mhzqihew.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjuotzwq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gt2rytfrpmt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2pszlhysj.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gt2jofpvtvx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2stibydbf.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gt2sjfdcwog.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2xwcvarbk.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhebzdil.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2jmewfuyb.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gt2kojfovov.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gt2pbzwvlld.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gt2qmysdxdl.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gt2uoduryre.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2qarqxapu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gt2xonwedll.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gt2hcxqngge.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gt2dhvhjere.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gt2ckloctcq.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gt2voqdzccb.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2xvtxmbzq.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gt2konpbxtt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gt2jfgsysrr.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gocxdwrs.html


<!-- 参考信息 -->