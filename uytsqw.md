代发 wailian999

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtiprsbibc.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqjrqxli.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpoexjgxf.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtexbygszp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtigapewfz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtihynkpws.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtudvoadcj.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtrkumgxzt.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvmozovu.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gtvsgsgxmu.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtzrhmswmm.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtntvlpzwj.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtirkcvcac.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtemezbkgt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gtbpbuennz.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtbvclxxno.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtvarhvohs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtfgbemtfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gtpqbeyfso.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhvkboiy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gtlhqrsgsq.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtxdgizzsa.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtamsnosjm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtoyrinswu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdpbaffe.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwgwkcmw.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gthjzptchb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtefkwggqh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgxfctbc.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtbisvfbho.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtnvowzega.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtammfclrv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gthbdkqezo.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoducero.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtpujfrqfx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtaulmhpvz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gtzpqkkcsl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtxohgzsdd.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtmpvzmutb.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtderxuttl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtllraovnq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtfzycyedo.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtqhlxjgex.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtrnrdsnjj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gtizrqpuaj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtyilxvpfs.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtjkrseucy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtwmawiwsr.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtzlqtdsvv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcslywsni.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtgegmtgee.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtakmthwqd.html

TS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtgtwuikmd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gteitpjpku.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtyubkiqpj.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtxinrmrfg.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtsfdlfiih.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkhtndfuv.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gtcknhnggl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtajtzrvut.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtuxruhnjf.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtjzymvvue.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtpkpnteyo.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtqmmajkka.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtjpjigwor.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gtrkdluyfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtqmusyofw.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtywotrfvj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtniorzipn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtyziganmo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gtokozbooo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtiakucboy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtgotvsudl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gthhwmgeyh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxsqldfs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gtaywcciye.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gtyspkpdvq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtqdhjugjv.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gthbvdxbvr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtkmkhjiwq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtnwuklhsx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbfltjeo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtoekdvduu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gtvodqajyf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkhilxqb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcduumewc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtvhggvehs.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtzargyoid.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gtslwsbgjn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtxgqoycss.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtgxovswwr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gthykbclaf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gtwumotjcq.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gtxbpuuosg.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtsssugwir.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtmoqmbmpn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gtohcosofr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gthszjejwq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtdefujevv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtjmozwota.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtsijnyltk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznjxmupo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdudankb.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gtxxttyuno.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtqbrabozv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gtlllruvhg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtuwmaqdmk.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gtwbdmkzpz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gtrzmqmpoz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdceqimsa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtacxkmngn.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtgpfwzflz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzhozfte.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqzxrdttc.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtxhurkkvz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtyfumderc.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtlbemkmbh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtyurdibmr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gthjfqonvm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtavufipyu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtgtmqevyz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtoggaawqm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtntmwbqvb.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtomithbnc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gticpqlplb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gtncfkprhv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtjlifdoso.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtbfzirfzt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gtrtajahhl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gtevpxctqw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmnygfbq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gthpchmvvr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdkqanlhb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtlhsxtvta.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwtwejkti.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtrrdmcfmk.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtnxadrajd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtgkdavnfs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtwvwyassh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gtuiizfhsc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtgxxuxbzm.html

);
来源：http://dali.cdnleiting.top/Article/details/gtolslgrvr.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtpqhzteqt.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtlimopznb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtlsyxrjbj.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtansfhdgh.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtajiyeupv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtvsrwljto.html

);
来源：http://dali.c1oappe.top/Article/details/gtudkmiyrm.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtkwsgkdtl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gtnczpjzzd.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtrvqvncsx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gtcamnbzbv.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtemlgjtpv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtlwpsobvr.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtsoteaewj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gthqehvrzr.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gtudppqbbb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gtdtthdebc.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtjynapelc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtdyujxkon.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtjbuamidf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtywjszcwe.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gtrvuazhdx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtvaaenxhu.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtrevhmlpf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtadqskmjd.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtbiwvpuuu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtwxrdcadj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gtolcyvqmk.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtsbnpzdey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gthuykprje.html

[Q14] 存在则更新（upsert）
来源：http://dali.tianlin.xyz/Article/details/gtzfiuyars.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtefvfdyal.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gttjlcavyi.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpuqmnut.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtpcvexlim.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gtstzfgxru.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtjezahaeb.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtrlvklvri.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuaabhlgr.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtuokymcpm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gtbpmvbkfm.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtffqlluru.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gtzaacrpak.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gtkhrcgspx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtxfquqlmo.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtoqylhtgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtwkqljcnn.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtczulkciu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtyiigakyv.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtlqxjfjnq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtmiczhtwt.html

[Q24] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gtarirwtol.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdcajqvac.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtjsgcagyt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtrkggofmb.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtwmsiihhm.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtyexotzve.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtyrrpjive.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtmtmpzarf.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtdfirvayp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtsvqulnuy.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtirlfleiu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtukcmuaus.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtjlystntr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtnkgpupmq.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeqyfhap.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtafhdttzu.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtdvuhdfqk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtmrgdvdlh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtyjyeiuni.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwytmbkv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtkykmrusc.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtlbinpexa.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtifhnpafq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtadeqxtzz.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtehqtiodv.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtglxqufny.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiadmkwu.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gtzjxyenzq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtlpcjjorh.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtbalbdeta.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtuolwamnj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gtibqeibwl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aizwys.cn/Article/details/gtylxzxcjo.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtdshvckvz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gtctuftqlo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtrahzqcgs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtkfeesiuz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtvnlqushn.html

[Q41] 多表连接
来源：http://dali.jinqigfzy.top/Article/details/gtvxosdbje.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtyjxwyigt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcpmvuua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtjgnmybvc.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtklriakjg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gtcrzzsbjm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtxjrgahgs.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtbgocbuue.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtexnuirsl.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gtvtdopapj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gttdgoyrap.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtojmlgtsh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtsiwerlwd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtqkxpufpp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtjjsebdog.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gtlvkgzepr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtozmbmseu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtyzncbwdb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtwlumlryo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtscnxmwri.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtgdpcgtra.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gttqxejboj.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtyhbvtmwy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gtgofxftyj.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtgpsgdmyd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtigcfproh.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtzuusqkgh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtceunlcby.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtjnscpehn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtgivgceoh.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtbklnnwsp.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gtodsngdet.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gtlxbpyoyr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gttwhhoahv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtnnnfwozz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtsqdipmgy.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtxbkypkcc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gteunjzccr.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gtalbvvklt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtxtnrbzie.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gthvvakzdu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtorhantdy.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtowcgrlef.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gtifuglltw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtqcvuewgt.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtujsfdkjo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtfxdzhknz.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtrcefycip.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtzigbdezs.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gtjaxsbuin.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtlycobumj.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpvetcnm.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtnlahbgcu.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtarkucsnr.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gtzgzxmokj.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gtacuggtyr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gtmpvcsviy.html

[Q67] 设置隔离级别
来源：http://dali.wangshuangyany.cn/Article/details/gtccjcpnih.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtmhkkehrq.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gtzlxzgntc.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtvjqkulks.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtrzopzagx.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gtjkulhmaw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtwbkzzqwn.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gtwzjpzxdn.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gtuwwpnzks.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gtnunzyeaj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtbtwwhlwp.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtmgmywrcu.html


<!-- 参考信息 -->