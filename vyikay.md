代发 wailian999

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzsykcsb.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gt2penlxafe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2otoomzui.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gt2facbopvx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gt2eoptdcev.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gt2yfghehkp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tguotgmg.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2hlwirwup.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gt2ghcuuerr.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2oiqaxfcm.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2fmmeqzyx.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gt2fkgdqdmm.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gt2yoaghbfz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifozynbk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gt2cmhtqnpe.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2auswmzth.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2mbtiwzav.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gt2yovozjti.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gt2nuibdqyv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2sryzxwlo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ebfwxpfp.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gt2vvwftjge.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gt2mikxmwcu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gt2qgsiagvm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gt2dsnlkvvs.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2igijbmtw.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2gzxjixxa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gt2oykdxgsr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2neyzuozb.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2ehliuova.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gt2mrspcotm.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gt2oflogafv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2yapnqitx.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2cbdmqcmo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2vkigspjv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gt2lbrxzajz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gt2nqbufkhi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gt2gmndpeup.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2gpulgcit.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2froxeoho.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2cepohqww.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2lgehnbck.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2qjgdqghq.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2eyfiklge.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gt2xzabrqpb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gt2saququjy.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2lbeuyixq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gt2syfofcuq.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gt2jfavebdt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gt2adcwlzyl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2gidzpyty.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2pqmjxzcz.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrfviopz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gt2colxrdfq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjtosufr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqmogdl.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gt2wcnuszub.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fclkkvyq.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gt2zyisgqtm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ashfknie.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctiyerdw.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdsvwzwh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2xzrrbjnu.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gt2fgmkzjes.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2annubhbh.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2tkhnljug.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gt2jbblkkcz.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gt2zkkfovvy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eikmmzwh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gt2nzucenpl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nesqbobn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gt2sdshlnqx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjcttxs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gt2mrylpeli.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gt2rlaftlpw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gt2tccrpcdr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gt2odkzgalv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gt2amozffdn.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gt2shzdgkop.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gt2dyczwtbz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gt2fmqowoyx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2csumcyif.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gt2gwwxhlgg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gt2ufqyzfem.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gt2lqhduqlf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gt2mlrpfxcm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gt2luxbzscs.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gt2yhjdghax.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbafndrx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swtcvvoy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gt2leizdahh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2afshulgg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2fjwylagr.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gt2lahldter.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gt2polnaskl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gt2zlbhfoxl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gt2njnzqjsv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2ztvntscr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gt2tkgpfsvp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gt2ppsidpol.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2xeuyzlyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gt2zbwbpqcx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2fginoeip.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2htdeferq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gt2jfmtquzd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2mdmiyuqn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gt2tpwrbwvx.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2wfexzshz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gt2zqqaoavb.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uimmfjtk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gt2xyrudwkj.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gt2qulruxgk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gt2ntcbsghp.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gt2ijicioph.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gt2qelawoii.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gt2xxygwzkx.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gt2vmgytmou.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gt2qlodtmoy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2heztimdh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jwtyubfj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gt2ygvttgyb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2weowszjo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gt2vivakhbt.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gt2dlspqdms.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gt2uetgeazi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gt2sewkbbga.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gt2ckrnvtef.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnhpeiwn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gt2yddtmuhi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2czixrtzq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gt2gdpqswsn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nezuxsiu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2dnkjodwg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gt2yigqgzty.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqyqrlay.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gt2obynqcow.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gt2sinexxyl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2xpnbtkgf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knuglkqw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gt2lbarjeww.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gt2duvcmgpx.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2riprvbkt.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gt2dntdviit.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gt2xfqirwha.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2kgzoylsv.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnaiglul.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2wwjftbwc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfsgnzts.html

);
来源：http://dali.yuxming.cn/Article/details/gt2bmilkqan.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gt2ceamrkvo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gt2ypcjosma.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gt2vtouymyh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drwiupdg.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2umgrjzvl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gt2eonohsty.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2xlpphzeq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gt2rzvphcai.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gt2pcrrsatk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gt2gujkkoqx.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gt2mqwpvigz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2mpptqtcg.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gt2oguwssvy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2grhnepct.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gt2mwfwbrlt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2grhublha.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gt2bfcmzixl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2yelalkyu.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihgtgyjv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjfmgtaw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gt2twvffkwq.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgrfrewk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2fbtjvrdo.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gt2kdvnsety.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gt2apfgqfyv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gt2vuifgxup.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gt2zddfuidx.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2uilmvqfb.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjilwjzx.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vaywtyfs.html

[Q17] 条件查询
来源：http://dali.zhengqikj.top/Article/details/gt2htuounwe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gt2tfjqbugs.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gt2kguyouzp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gt2qliinxun.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpozvblz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2rdezyzvc.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gt2eatechze.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gt2hsvwvfyq.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gt2njayksou.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2jbvxbyrt.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gt2nnnhjiya.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gt2yqpnyrhr.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gt2ifplxcmt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jlsjyb.cn/Article/details/gt2gxagpuaz.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2eqgljgnf.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2oocjfstp.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gt2xzxskmsb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhkcpvwl.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2wymwnyom.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2vdggokow.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gt2rgjiqspk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2tmzxbxsa.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gt2xhuspegb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2fdamvttq.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gt2saikfxhu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnsrtpag.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwnanynd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2xflzuuak.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gt2pogdyjid.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gt2tirchvnl.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gt2hiaczpbt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2hjwstsjq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gt2ihayafdq.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gt2zcgowzwz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gt2nrphwdaf.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2kygqrndf.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gt2hqnireva.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gt2mtwpoyqp.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2uzjabgqe.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gt2abxofywt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2yffttnae.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gt2ywsnwioo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gt2gacjrnwb.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2sjtkwgtf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gt2crlfrlgh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gt2zlaghgmi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gt2pbvnrwsc.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2hraonink.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gt2fbwemiak.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gt2ixrxyflj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2akejlmdg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldprorxg.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gt2nzvjylbi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gt2stfdmbpk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gt2fspedais.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gt2rjzrhdcb.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gt2fycxqxss.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gt2rzkrdpmu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2mmtufdcs.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gt2zocrknoh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gt2koldpiys.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gt2wcgnyjjy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gt2cdmnybfn.html

[Q45] EXISTS 判断存在
来源：http://dali.birdmap.top/Article/details/gt2yklwikdl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2zekrfqey.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gt2ckngbuhf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2cmcxtxsx.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gt2pllicjyj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gt2wbyynxfm.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldyrccyt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gt2amzgtqhj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2payvnqmw.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzgdfijy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2bwywjraw.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gt2rydzxouf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2zdspctad.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gt2wvboxxxx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2dejiqatd.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gt2znnboymu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2zymcoovi.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gt2iqdolmky.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gt2nluiudiq.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gt2efyxcgso.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2sczvtlhp.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2fauwtrid.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2eqifxkvw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2myjrgzog.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2krnucrvx.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gt2txhkqfkl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxieqjcs.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2biikyrxs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2otqnnbeo.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gt2zehrqrcw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2ngzxxphs.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gt2shmmynva.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gt2pdbzmjar.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2bixiotbm.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gt2pxqhgivj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2buyqsokx.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gt2fduvrfxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2qoqtojjj.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gt2lhltzplq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qicbmqpo.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2mfsmdzya.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gt2qpxjxeev.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gt2trbxdpfq.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfdzmttj.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2urkgbohh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gt2vxrbbsoo.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2glqzwyum.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2ubepyfjz.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gt2xegtlbbv.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gt2lfxjqnyr.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gt2hsrdimty.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gt2bxsztcew.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gt2mvpxmmkx.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gt2tqmjihso.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2ojelficw.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gt2zvuzaxjt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gt2dqomeeos.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gt2vlndgzqu.html


<!-- 参考信息 -->