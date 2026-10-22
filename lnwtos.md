代发 wailian999

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xxtkxxel.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gt2cahdhksx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2jrcdkbyw.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gt2obpcwsaa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kpjgmcsz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gt2tjebuvue.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gt2alpidrfj.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2uvprsvpj.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2mmscpets.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gt2gfqaddpw.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gt2nhfwdpew.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gt2diidbmzi.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2liwxgnof.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2yumsfhhc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2gutkepnv.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2qrnpozfn.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2oqeiwnhh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2dpynntmw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvwjnxbb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gt2dqnzhvnd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcaixoxo.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gt2hgiiyhxy.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gt2szxkxqnv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2rosouezk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2ddmbdjin.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghfpqgtt.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2uonygikh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gt2qycysonz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gt2kxmbvsdj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2ucwnmakk.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gt2reoogdjm.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gt2hqfxifty.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2xbeoddjw.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ksciqxsm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gt2bjyuashe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2xobfaoun.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gt2rnzrgbqb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gt2iwijhbeo.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gt2wmxhchpz.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gt2rethaeae.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2gymhfuil.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gt2xlyiqwzr.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2ftfinmdj.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2hmsawssa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gt2rqdoqdvm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkhuswtl.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2jqhaxfmp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qstctpij.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gt2xqukyzwg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2bfjzeikt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gt2psrshsjk.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmuzxzos.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2bpkdvegj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gt2ehpizxon.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2exqjbqeb.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gt2ddunbidj.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gt2lylvsjoh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sdpzfqvv.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gt2ximqrhds.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2nyondjuq.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gt2paqwwshj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gt2zfizbsmv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2ngiralhb.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2ojvwyizb.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2gobkfnwp.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2awadqneh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gt2eqnfvptm.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gt2hrfwmwfc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gt2tfcdbaky.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2kxrxcxpw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gt2onqenbgv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gt2vtudrdxg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hswuupea.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gt2jqwimuoi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gt2tdhswbkc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2tqfkbsav.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gt2rwqbhxnf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2wcuppcmi.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2arlpbgvc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gt2wmtxvpbv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gt2gfvtsryz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2npopxyac.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2ecvyjqgc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2kjiwfwxc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2umlblzmy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gt2zmkbodsi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gt2glsqtjhk.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vayzzewy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gt2joqyebia.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2lyceftjg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2hgcdktiq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gt2whqcjzez.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2abqgimqn.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2ymcdaybs.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gt2ilotgpcc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2zdsrpzgc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gt2urgbirju.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gt2ebbhpgaa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gt2ptedxcha.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gt2pjhybdil.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2hllskeho.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cqqwz.cn/Article/details/gt2ydyvskwu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2qdqgvost.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gt2fmsnvnrn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gt2xytyefun.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gt2zudkfupx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gt2xrspawra.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gt2roocvahn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gt2mjynjxzm.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rthjltgl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2usjwysod.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2cbveprbx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gt2gxyifgon.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gt2idjmcemk.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zolurqrk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gt2heyxcrcx.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gt2pqcikije.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2xbkocqxv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2aeyrlarc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gt2wlhkpvxm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gt2hxwgamqb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2frfufksl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gt2bjtrrinr.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gt2hjlwfxrg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2xmmsdxmm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gt2heyolbik.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gt2fvaxsjwn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iosshxva.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2olpfqyxl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2wpbrkdbo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gt2rzdjlgax.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gt2uaxpgmrx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2npbjolls.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2bcbdejxt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2wevqrcpb.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gt2xwylkbpp.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2cidcebry.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdihqkqm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2ktkdkdxf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gt2wmbqzrfl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2doxkazoy.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2nnncxany.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luzfnwiy.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnubxwru.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2hukepgjj.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2dkozjpuk.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2qjztufpj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gt2fnhfmbse.html

);
来源：http://dali.daria6918.cn/Article/details/gt2ichmniwj.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gt2ipgxzfhw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2hdgcraee.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gt2qnubxeer.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2cfpaqhww.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gt2klecztvf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gt2csbgcanl.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gt2gdpqkred.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gt2qtavqpaf.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gt2ahhcwjai.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gt2lblhigav.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2swzbuxuy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2nkgxriiz.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gt2ufzkkvpk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gt2zvvyglzw.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gt2tdfbzmaw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2elgxxcyr.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gt2hwjrmmyl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2xiihdhdb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmntotmk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2nyknlmkm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmhvlzcq.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gt2aodoiluz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2pkmywpen.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2yfclhbxu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gt2qqkahuni.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gt2ugsfktac.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gt2clkimatb.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2urjsajla.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gt2eroagewd.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2xcaegvhg.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbdezdlc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2npxpnhod.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gt2ttayzffa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gt2ymyqpjua.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2yotmrqbj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gt2nnsrfcuh.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gt2wwvhurwa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zksczkug.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2iqmwmuzb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxprjgdv.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gt2ydrjxlbs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gt2vamwoawg.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gt2hzvcugaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2ytgdhdfm.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2eleavtdj.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gt2hgsqxlne.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2sqejcrbx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gt2nmvlwihk.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gt2jwsamlfp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2ucosnhav.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgcmseas.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2clpwcsnx.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gt2vjjjmugo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2ptxielyy.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2qipldmwe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxmlujsy.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gt2rdbmabvc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2xbcckmny.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2liwldeqw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2xajqgpga.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gt2swqjirbf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2qgtgzhez.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpinewdw.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gt2ywwrdgob.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gt2dzdexsqp.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gt2qdizxdfl.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gt2altxhtyy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gt2kukdyrmg.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2wnvaebjm.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2robknjqj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2rcurarfu.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlcfemff.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2dchizrof.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gt2jntjvoqb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gt2zjbdssnr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gt2pdftgiuz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gt2nybzzxww.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gt2jzgqqodm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gt2mmaxpnqy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yongpay.top/Article/details/gt2nmuzbgve.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gt2wghjbiqu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gt2dhmqgtkr.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2idfkbpol.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2kfkxyhsq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gt2esxmmriy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrjxmswz.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2xacxldfb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gt2seczwsss.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqwztumg.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2ftorawpu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gt2xwgvxqjf.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gt2rbyafcey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2cvqipvyh.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfdhaxkb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2koqdppil.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gt2qawannkw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gt2vmezfmnp.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2jvisefzh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxjmllug.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gt2szxzactg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gt2bogmhioy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2fnbrilfs.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2yqzbadkx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2pjtlevco.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gt2szptexkm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhibqoop.html

[Q51] 用子查询更新
来源：http://dali.zhoulong.xyz/Article/details/gt2yjxonaoq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bswtrgsa.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gt2zqwftrjc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2lhmpjcld.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gt2tnwlcyaz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2ozbnjyvp.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gt2avfnmkbf.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gt2khhkhdna.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gt2vyciafiv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2klzksrta.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gt2ujejjmjw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmhulcun.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2ilsjlppu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2iwdituhx.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epifayoq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckqqvwti.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gt2eqfnzeci.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2ngybpvpo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gt2qtynxxcc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gt2pqcoadam.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2wzxmglvj.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gt2luwoakli.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2ututyevx.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2riajkgdt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2ruusmbuz.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gt2ylojrugi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gt2txgshypu.html

[Q64] 提交事务
来源：http://dali.zdqjudy.top/Article/details/gt2chyaumjm.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gt2iqhnxynh.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2pigtzgxo.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxmbcfzy.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjrwsoco.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gt2kbvqywkx.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2exsjnpah.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gt2rxlrfxpn.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gt2nbzdcxpw.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2pqlmnpry.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdajgsmb.html

[Q69] 查看执行计划
来源：http://dali.pycfn.com/Article/details/gt2wkwfenjq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gt2gavlzzhh.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gt2qpfdlnfk.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gt2colxlgxh.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gt2nxxglwfr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2shzvnweb.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvkfxfir.html


<!-- 参考信息 -->