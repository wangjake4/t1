代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnljehyke.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtjzoarotc.html

Ruby: Thread.new { f }
来源：http://dali.zhixingplan.top/Article/details/gtyynjfwab.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtyoukilat.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtfibbzprt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gtditmfpxy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtsavjpjbz.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtbfcysnwk.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtivpccxlp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtzbybhcqd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gteqtxvogf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtuxuifczf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtyyfgajmy.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtymsxlwte.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtkcsibkrr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gthfjepdqp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtisoteinb.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtqyxndkzp.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtvjrejioe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gtfgrdukyn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtngbnhvmb.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtljnwajtt.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtupyllyee.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtjqizlnvr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtgxhxfrgo.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtkopalpgr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtuwtmazrt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtmeyqnget.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtsswrszws.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gtfyhvygzp.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtnfchbkkd.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtctbfxikm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtmyskqsmh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtyfacjfdg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttipoxbvt.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtlfzzwwgk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtnqbyopxd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtpyhyychc.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtlmylzcsz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtswlszxpr.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gtejtvqwfb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gtfhjtjcrb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtocaledmx.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtulrvuuwd.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtkbrbvgrt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtmqgqfktc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gtegxudjcn.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gtpfwsjjso.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtgcquplbw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvwemwohs.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtlejuwtoe.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gteqevdlmo.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtuplzhysh.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtlljhfcym.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtziqbhovx.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtwlfxmyad.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtjmdawepm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtfkkhbntc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gttdmvnrhr.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtwifbioeg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtpgfqvqai.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtbangljgq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtopcjcoxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtlyvqszwp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkcnmtlg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gtywgiydhi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtcqwmbsqy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtigcdbghr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtdaxadppt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtjherjlnr.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gtofisraeb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gtbaksyyff.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtynjxklwo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtvhawmvps.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtsmarqyyx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwpfnvsc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gtaebwxalt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtswbhoune.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gtlbwdkdhp.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtlvcubmcc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtbmetvhgf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtqrmaqzmk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtxmvfjjba.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtxujjyvjn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtkqvykydu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtlnukrdns.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gtizafsqfx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtxlqneleh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtcwuixibj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtnlwjuebt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtwmgzgskk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtpnlpbqyz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gttgyyuztq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtifypddne.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtbciqilty.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gttcwofrzp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gtymxiljtb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtwuntsctk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtbiererhn.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpulnkyqw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gtamsrynfj.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gtcncmtkhg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtzeshuxva.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtvvclzyhj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gtkkpmrpds.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtuueigcob.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gtzihgmxiq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gtfarmkwgr.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gtijcvhjjn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gttouuzwxb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtywzefltp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtbiwlugub.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtzylnrvit.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtgwaznupk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtxptuvwwh.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtoewgwdyb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtcmimoqhq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gtibjxwqsw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtccjteryf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtpvfhkyrk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtuudbtnul.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtpztyhuyv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtqzzobypr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtzolmongm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlwagrazv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtewpxaagp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtggoipfak.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtrhxmwrcs.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtzpzypwdv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtduzkqscg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtotvasekp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuepqbkw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gtxrqvyhzo.html

);
来源：http://dali.sxryk.cn/Article/details/gtvvwbnaqm.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gtnqbtedet.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtmpqglnku.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtcfmqbyuz.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtjssekoce.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiehbctl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcofbrcvz.html

);
来源：http://dali.cdnleiting.top/Article/details/gtdvzvdtpi.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gtxjtqlcrh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gtvdiowbpy.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gttfbgjhln.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtgvrwggqx.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gtgolfpbul.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gtmasjwbip.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtgqgvvcoo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtfozauzxr.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvwthmns.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqecnuzez.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtxculuzcj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtdihhzocz.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtyvhmicwy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtodotlgnz.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtdvrvftxk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtmjyfdcbq.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gtcoijrumr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptrrsjob.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtmphxqlhc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtwhclpzxe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gtaclnglvg.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaskimpou.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtafrqdwif.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtolbzjosi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gttbjqifmb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtorghrhei.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtvuiapykq.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthsthagfi.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gtooiynwxg.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtotejbzlu.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gtqrspycka.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtnaloqfdn.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtcraojcws.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtrbmydmpy.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtcblgkray.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtroiweveb.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtzgemlzcb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gtzddsbary.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gtytmamitp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtmpuloena.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtfnmjqvuu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gtoiivvmku.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtmtenuqws.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gtzfhasqzx.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gtulnfnpbq.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtgcymxarn.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtffdfxkpn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtmzyrbqbu.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtzchwfile.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtldvldjsj.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtyidwtidm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtmrdydtty.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtgklntzpi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtoeyyojiw.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gttfkoidpf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtgncofeqm.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gtukpzufcw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtihioofjk.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gtwhwkievp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtmmlwkowz.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtpmagvyis.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtrgzxrhot.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtvvtwzgbi.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtsgspiwja.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbmjwhvu.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtspvkcmxe.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtnvaqhetw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtpdnmhwyf.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtlmnlklqo.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtggekugtl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtvtkeulng.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtgatulgih.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtbmepztpl.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtjtqwqvpp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtytulieej.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtbglbuuzf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtiwjvsxub.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtkqeeavgg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gtjhkqwtuj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtjtamacpj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtnergqtws.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtcqslglyt.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtrcevpubh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtdhahbnmj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtlulnltpf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtoapidwrd.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gttqkjhkfw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtcgjjepuc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtvwdxghxw.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtoieupjwb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfvgfacb.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtwxovjsnw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtoxlcxyxb.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtomshoiid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtvtfkinpe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtrmavvkbw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtjcqosldh.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gtozgsocbf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gtnkyrorfl.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gtkdbpmwlm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtbdrmqbkb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtwwbvqzrb.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtpsfxtish.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtsepwrvhu.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gteqedlysq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtbrjbkgyd.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gthdgkmuoq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtfdqljoob.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtfedcpwob.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtjiopdnwy.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtumbeevuk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtmxhoegeq.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gtziwpqosf.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtohyzyqco.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtgtczaoam.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyiieune.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenarizdr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtvdwoiyif.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtjirxmmer.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtisdtkmxf.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gtgxcirtin.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwanoblo.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gtjvefnqhl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtnrmvlote.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gtvfxvgdyw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtwpswmvoq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtkhybljwx.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gtblngrhjs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtolcjghzj.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtzpiwtnfi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtdgxgvzpl.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtrlltmpao.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtcyliunob.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtgqrmjukf.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtocsuaeqa.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gtajbakbao.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtcsrrkoyx.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtfykfzrxh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtduyjnezm.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxiuowvx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtkyijuiwm.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gteedrtzqv.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtkgocpefu.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtidebahks.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gtfmxsbpfj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gtjgpyxbgp.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtsyetoplf.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gthfgffwbq.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtsmmxbnln.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gthvjbntaj.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtdrwglphu.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtdseoncpa.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtgsjwrrcp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtgrvluhce.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtcprubzja.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gtplxybvzv.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtubvhtcyp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gterwswzna.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gtsmrokcgd.html


<!-- 参考信息 -->