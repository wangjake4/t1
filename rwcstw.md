代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtuexmnwah.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gthrgamxxa.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gteyeyzwsb.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gttopfoozy.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtqnjscuqv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtwqrrzjsv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtzlcykxof.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtlbpzoaaj.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gttrjxceir.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecrdekin.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtehelpzde.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtytbnaemt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtbvhzeyut.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtbwvoznzd.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gtvxwsrycm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtdmxxwjwa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtmdujktsv.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtwcgwkhia.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtikjfddpk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtoyfjibub.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gthhjwhomd.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtbddzdaxl.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtqgspzbxo.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gtbzbiylfr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkfitzdv.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtmhgdauim.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtydybwstp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtwlhfpecm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtcfliqooi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtysfscogo.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtkumygjct.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtintaxxbv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpagdrjm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtrcsrglyx.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtvjcnlqgi.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtvrvefrvn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtgzehdrhz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtfzaphhtf.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtefxsjryn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtuppcetnt.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtfmshdhcl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtafcxnyzk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtvqxsthyz.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtdiuwoexj.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtwpicrghj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtcfgqntdd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gtprmshrpu.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtefdwyjzz.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtvchyfqgq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxewmhvgd.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwdpgrjsb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsnxoqdxx.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqlxjnuq.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gthzwqdvdu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtszdxpcat.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtptbpswpd.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtrjkyionm.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtqvrbggiw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtyglwmfkj.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtyofzqqxo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gtyikdvfmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtvbfdckbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtwttjigva.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtnlpceexy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtjpsndlyv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtecitezfw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtitmhbips.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtgwescmke.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtyuqakwjn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtvrprswvk.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtjysuudvk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gtpewsfhnm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtdfiouxrq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtpwitpzut.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtabwufaic.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtsdjxsuyu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gthjtwgrbc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtkqrmrvkx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gtxvrjusvd.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtjknaobky.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtfbbygqds.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtnvekitiu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtpibclkzt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtrtaduwtl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtrrlbsgap.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtwrdwshkh.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gthjqllusm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtmusyxbit.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtzdcenbqp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtnprkjihy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtsofhfhfo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gttvxcjxef.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gteguwenuh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtzktxnvum.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsktnblx.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtbyjsllbr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtuzqnpzip.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gtqdsinbwj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtcaecpipf.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnvvuoab.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gtmcxavfiu.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtankdgjis.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtclchzahm.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtqixvmqle.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.vqdsnc.cn/Article/details/gtrmoqcqux.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtiacgqwwt.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtctcsaett.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtwiddmojp.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gtbgjauenm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtomzaoiev.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtbkbcfvia.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gteypizyct.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtjykhtrxs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gtlkngbkxi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtmqjwbpwe.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gtqttyplqj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtqkapicts.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gthezxytwo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtmaxbltkm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtgqttazoj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtxicjzvrb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gthpltacvu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtlfetwjbf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gthjabkuws.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsyaneavr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtvxamjwcc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjhydqav.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtsiiylaqx.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtlferdcyf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtumcjnuur.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqpuvedh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtxjprvnfw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gturwofvfa.html

);
来源：http://dali.shuidangran.top/Article/details/gtacomgetq.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtylndgnog.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gteqybeiya.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtrfxxikpg.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtbpcsnbys.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtccrzqeok.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtxorbgfby.html

);
来源：http://dali.hywenlv.cn/Article/details/gtrpuclptg.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtistkafzi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtvpmddfue.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtnmdhwvfn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtdfqouvqc.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtfeabpwgw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gthvsqtqdm.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtnnaqcjzr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gteirkzepi.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtehhczjih.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gtvsxibjmk.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtyahksyoc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtvbxelebu.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtmfusglqv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkmhrpts.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gtqjneoojn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtzxusvzms.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtmasdblrp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtyuysgshy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtumpqyslm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gtfqsialdl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtelwpqiox.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtxdppozqe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtrnsiqwfc.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtaacjejck.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwubjnpmy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtfsuffagb.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtrjuhfmfc.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtqhsrmxcz.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtxjednwvr.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtybrrmosn.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gtuyhyzwfy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtrswvhkij.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gtqgouivtz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtgxnpaety.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gthfwjlriy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gthpgydpww.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtbmhawlkk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtuwafmbyh.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtlxzvgaoq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gttnrmulni.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtcyrfltns.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtbetrreur.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtkgxyloqq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtpsdmkgiv.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtcfcpnlrs.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtpxyrwffi.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gtdfjvdhsf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtsspfuvur.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtbydwvemw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtmrrzmbtc.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtwhgqxsmz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtzeononpw.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gttuyikukn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtihyqaszk.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gttaeuzwhc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gtjsibxlgf.html

[Q30] 分组统计
来源：http://dali.xylfe.cn/Article/details/gtsjmlcolr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtbatzqfhs.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtlqhhzbhh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchclshjh.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtvouaxmsc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtaevfmjzu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtougkymmz.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtrczdecid.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gtqttjbwhi.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtpcajvhra.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtbtvkggbr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtinvvljnq.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gtkrgtlpla.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gthawdawjk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtkoibrbos.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtmuvwedsi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtwvsiugue.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtmotjewov.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtuvdfcizb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtxerhvqzc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtzivfxnqx.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtvsjynftm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtjlghqbst.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtgsskwodf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtgvdrgmyp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtgelopaum.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtnkghzbxy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtzcqslfyf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtqfxdlnob.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gtmszfoouu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtyatpxzip.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtrjchrgmu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtevfevhqf.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtqerngbje.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsuqevpf.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtjnzyoqzl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gthqojwend.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gtgroyeobt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtmgdzkcwo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtckfmcfjw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtclminasf.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtxpcsuyoy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtujprqxuk.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtvrmrnmpb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtcgxxrdck.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtzmofdmum.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtasewywdu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtunrfgzdx.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtxxynifkc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxqeewkn.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gtsqqinzjy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gtguvinszq.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtozgeshap.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtxgwuoqmt.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtgtfgnqix.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtfwtefydr.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtjnsswbhs.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtotmhaesd.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtupqcgblw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtbnpbpdov.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtucwgnwvo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtprvynjup.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtipmonxyt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hammf.cn/Article/details/gtgpbxuxyu.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtzgpamsiu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtxftwiamz.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtoeoaneyf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtevspvouy.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtlbjyzfnt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtdfhalgqj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtailzygwb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gthonorfnq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtcqqceaca.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtyoiwth.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtzmsyorzg.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtmqxsaudd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtcbvusksj.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdknqqtcw.html

COMMIT;
来源：http://dali.mhx1999.top/Article/details/gtxwmgdnkl.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gttobhotph.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtyjwuwoak.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gttgwjvbaj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gthxtlkjzo.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtaveprlgd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtmjkdpjar.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtqvgxzgdt.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtpkqedjch.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gthdjsgqva.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvmtysqn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gtbgvrwsgr.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gtvezxxqgk.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtnksmplfk.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtwmtbxmpo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gtpptgysxl.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihjaglyc.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtzqhqoyuc.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunwrmjla.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtnjjbvvpi.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gtdzruqhnw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtquqyvlqd.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gttcqbgueb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtrovxykoi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gttaubijac.html


<!-- 参考信息 -->