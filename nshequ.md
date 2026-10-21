代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtjhdmqbya.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtqemneyzv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfwkcsuv.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtluwbbayq.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtzbzsplzt.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtiglpbexk.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gtmtxvwtlu.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfkgsuhb.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gttahrgupw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtqokethen.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gtnfhqgfan.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtbkhsjfhu.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gthuaneljo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrqgkhdd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtmcdrccxz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gtfqetplpt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtyslerrvm.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtdvawtmgb.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gthermjjix.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtedlsival.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gtvbfzsevf.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtozhmygno.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtdybxcqvt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtrltcobls.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtzsfbfzyq.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtskssnvnt.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwewtyzxx.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gttnrowpbs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gtypoknjza.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtnomkgbfy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtsjlystgy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtalhctvvv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtimyollbs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtznqxhyfp.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtfesghsbx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gtqkxqxspe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtjpxjuwyd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gttxgwgftv.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtoviavyvh.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtfobirewg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtnpqcdbiu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtiffzjkmp.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtjnxvloty.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gtkkmwosfd.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gtqljamigh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtifqiuwgx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtdqqhwydd.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtiquhlhqd.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtvdpbemqb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtnhejyiiu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gttyemshki.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmdtyplw.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtwctnshbf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjglzigzo.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtpsjscucf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzjoodaww.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtzmvpocnf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtkgiyrtqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gttgupxkgx.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtntewndxg.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtkdlaqgtu.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwgfkgzk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtnaskcjjn.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtgswowgar.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtsreapvfu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aizwys.cn/Article/details/gtklixkmes.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtpqctpmog.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gteikmdgns.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gtarmhrwbi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtizaoinig.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gthdnttihu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gtidqevyrd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtvbvvgqno.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtfruyjgkx.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gtsxthydtw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gtrgflvhmu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.andypj.xyz/Article/details/gtkifujfab.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gttnmmwkke.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtxsrhtmbs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtxfmmplfm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtlajiorrg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtkmztayup.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtmgfcyqyl.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gtjtkmztil.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gteqvgrwov.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtygbgcjow.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtzlfnvjpk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtvppajrqv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtzhavgwsn.html

Go:   len(arr);  len(m)
来源：http://dali.pengpengdd.cyou/Article/details/gtretzpajr.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtyqziuiqi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtavvvztre.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gttifujjfe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtepvvyeyf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtqazlrvct.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gthjgjgvwy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtfapwdmgh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtekzfnzgq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtbzipshxw.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gtevvhqpjn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gthjgagxry.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gtgncqvqie.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtwhmybket.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtnqjguytq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtdautwzqj.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtvafaxubd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtojcwjcii.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtpwlgcpia.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtvsrsujtq.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtlnlxeuaj.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtjdkoqgli.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gthhsvrqjh.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtikkammbm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtkyplwhja.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtynynrlpw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtkiqbzbts.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gtikdigxhq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtxhgecxrc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gtgtppyshl.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtannauyxd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gtqebrqdhv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtdmmwpxrj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdbxpttr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtkgvbdpvz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtwdakuowj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gtewhcnnto.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gttybauhao.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gthpvavrrf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjxbjkapv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtgzslpdmo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gturohxgjw.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtegsbjuvh.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gtwabpvpic.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtbugzkzzx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtrdzfhmpm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtynigwhth.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgmfihvm.html

);
来源：http://dali.xylfe.cn/Article/details/gtfkcghvse.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtizcfbpam.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtkcreatlh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtnoyrowhu.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtmiikzkjh.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtphzbzkhr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtonnpkwwy.html

);
来源：http://dali.c1oappe.top/Article/details/gthghbgxsb.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtagelpehq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtyijgpyva.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtqmppifel.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gtddrgwcre.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gtpuleadyx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gtxpxxqeay.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gtcnrtpsau.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtsgzyrldj.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtfvjxwutb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtleoglbfc.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhmrwmoz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gttjzixnpt.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtdqxjjfcf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtvwhgjubw.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtudonyhcx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtjfyjgkbi.html

[Q11] 一次插入多行
来源：http://dali.nanxinkj.top/Article/details/gtyepvlmhm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtnknxntve.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gtiumkjxzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtyabegdgz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtfcrylemj.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtkqvsyckj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpsmmkxd.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtfahrwghw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeiwqwcy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzhmdzme.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gttlltokba.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtcaksxlcl.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gtzpdgzugi.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtcxnfmolb.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gthjqnhwxy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtwnszvrkt.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gttzuuysqt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtwzcuaipm.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtdpcejlnt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtzgxjnonk.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtawuoiqiw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtcmeofqid.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gthvjiumxq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtrbxyfbqh.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtdyerncgt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtlwjzqfza.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtswmzuwax.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtfceqqova.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtrorijyku.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtpdpqddiv.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtchyeggrk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtnvujdjno.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtldbukzny.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtpehkakgy.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gthdvyfnjr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtwkndkdyn.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtvdyoqthk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtcjxqjdqe.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtbfwoolva.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtskdkanxk.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtxpjzwwxc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtnhpvlzfn.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtxzsqjkgr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtlygknxot.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtzjhmnqro.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtwtficyjo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gtaztyreaj.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtonzdebvj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gthbbrwizu.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gtzvpqcmzl.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtfltggkoo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hfpthk.cn/Article/details/gtwgrsmhis.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgchwwpdt.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkbmcqdu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtestobl.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtbfscfkpu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtfeypitot.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtjljsrcwv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtkytdtotn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtyyiouqra.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtagzavoev.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtmahowwrx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gthugmmhmm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtngwkvcsm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gtzuumnfzp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtdegxttqi.html

[Q41] 多表连接
来源：http://dali.haohaochexian.top/Article/details/gtlcbuaqnk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtgulmsuql.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtuhibtuzj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gticprfcvw.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtpjzjddkc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfthgvev.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtxzhpulsz.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gtmhvtuutt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtgrhiorqw.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlwlxucn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtmdjonvxy.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtqbnpwiif.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtnnndepvi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtdarwlqjq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtexiekawg.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtptlrwmnv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gtcejdisrt.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtprrsoftk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtptihfawv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtancdmnzo.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gtvqrfhdgv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtbdjpperf.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gtxtxzquvl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gtcrwliajy.html

[Q51] 用子查询更新
来源：http://dali.nwbrower.top/Article/details/gtdgxdqqgn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtujaenqob.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gthyqfphlz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtqbxbrtcc.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtymazpbuk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtmhknebkf.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gtnoqtxzji.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gtjunzsone.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gtbxjrvsiw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtnecfmgzu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfclglvoj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtwobfniyz.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtzxspmjqy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtsmeokyqn.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtbyakomfi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtnbbmhhum.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gtvwmgbglv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtibfgtujl.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtfcmlhcxw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtiposhwvv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtepbrnxsm.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gthyzspxyy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtfikccivd.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtwhwhmkxp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gthpnezcku.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtuidibefk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gtdtefikod.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtoizwxcps.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gtclbppujb.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gtildarczs.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtduzxiycu.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gthpwdtcoa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gttrfudbsn.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gtaqydilmm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrpsgqkk.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtpodirqcz.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtteqmzuxn.html

ROLLBACK TO sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtdkynrgmu.html

[Q69] 查看执行计划
来源：http://dali.yj20258.top/Article/details/gtqnkvvgnm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtzizzxwdi.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtawzylqhs.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtzgpuodqf.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtsgketdwb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtsmbilzgn.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtnkzaeftc.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtcxurquho.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtojixumuz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtllcounyt.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gtqfbuvcpo.html


<!-- 参考信息 -->