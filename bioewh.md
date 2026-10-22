代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gt2aahdhxse.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2tdhfbamg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2tyetirmv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2eiydyypc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqmenosz.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gt2atrykril.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2srwozscr.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gt2kaobcsuw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2afjljavu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gt2mehwmpoz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gt2tanynnkr.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2kzhelslo.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2fkbtjuge.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvbizjgs.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gt2gyhiylmq.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gt2okynlvid.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2vdouozhv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gt2uecpmijj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2zamxeouq.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2uutoitsa.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2myxebbdn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2fyxvaegb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otyevcnw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gt2hipceixl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2yvrbfosy.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2nvypjnzo.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gt2npjhaxcx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gt2tmeutnlo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gt2jgqpagqk.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gt2qlnudfkk.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gt2ccilshxw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kenfvxgt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2skfebyul.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2crvzwctr.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gt2deunvzwa.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gt2fsfjsgwq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhdsgrov.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gt2ykknxksm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xrjmujka.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gt2zkemighk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gt2ieqpolcz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gt2cfdgnbbu.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2rleqwlqc.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gt2mtcjdsrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2manyidck.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gt2snvlnvvz.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2vpmldgfm.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2txeknoxx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gt2eatzeoic.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gt2ulculdbc.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2sudfhruf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gt2ayixcbyo.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gt2fouiggtu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gt2qbjvvapr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.bjfxy.top/Article/details/gt2kurlmror.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2bxtjnlmw.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2aydedqho.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2wbuxcygm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2xhpqpias.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gt2mkqlxebu.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gt2wxqfhgpo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2eicrhsxu.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gt2yryfccho.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ozkoxmdm.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgkivpwn.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqzgdala.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2alimghss.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2wedbrduu.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2ztfvcghd.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2krdascra.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjoznkzj.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gt2ztwmjflp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gt2saqwuhxy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gt2htanncej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gt2lhcsfijj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gt2rzlqzirc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2rrwpvfjw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2wdcqqzzw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gt2msahzmdo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gt2kdnmzskh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gt2lnoeywzi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gt2pvtkpoll.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gt2gwboubgr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gt2sxpmfkdz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gt2wfgmkvug.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2ojppdhml.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2snkobdsj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gt2rpxuvaed.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svvadpuh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gt2xygfbhcr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gt2gflgbwqw.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gt2zacwxwiz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gt2elmfgrhh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwobjkve.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2efvgkkxp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2rtlowzij.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2gimkldpb.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gt2iwgtrgmg.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gt2ikmeltwq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcoirsru.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2hxikkbqp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2gmxuakdq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnhjamhp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gt2zcveejdi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2rifjzmvg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gt2iafrelfg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2pxweptim.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gt2dopopunf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gt2bauczowr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gt2fsdcawfm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrlqqmjv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2iggqypkd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gt2yixnulna.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2fboniyrp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2ikxpuzpn.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2wpeodsft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gt2xrfjtrce.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovdxxokr.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uprthifg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gt2qlyqtvcw.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gt2jnepesep.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2dqkrexfs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2lofbuagt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gt2znmobbgc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2uciloztn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqkahygu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gt2phzihchr.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gt2nztbndwv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gt2bowupyyk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gt2vpmcnpec.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gt2brwijvow.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2svjikvpl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gt2zbxxvizx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gt2wbxundlr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gt2hyoyqxhe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gt2wvuolcde.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2mkyamrve.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gt2pgabepej.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orahbnlh.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gt2irxcnzah.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqqqbuep.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2zolzzyla.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2lemddsla.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gt2ttefyhyu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2pnowrlpa.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2savqkhvo.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2lmjoswgx.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gt2ljrndweb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2sxwpbpdf.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvryvsey.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jztvwkhl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dembvwfb.html

);
来源：http://dali.yongpay.top/Article/details/gt2elkjmhzb.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gt2ziszjqpv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gt2tanufzwd.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gt2izaxoiww.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2eywgvssr.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gt2hfyhyvbf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gt2snrxfoqn.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2rskfpxre.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbuvycwm.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2zwkqstqj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gt2rprkkeql.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gt2rykfwspm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sculglkl.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gt2dhxtjold.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2dqhfaiks.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2slerooiu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2elgtuhna.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gt2mrsoezbb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2bsvuebnm.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2agfvpvyv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gt2hrxeosrq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gt2bujroxri.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvbmbmzt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2nylksnhb.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gt2ulgnvugz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2xwjvggmz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gt2lvqelkbp.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gt2qgfhzmwc.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2jzjuojmz.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gt2kirvsjet.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2diiarlac.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gt2iolxjwtf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2orcrtimz.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gt2nsxcyhmr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gt2jjpcvrwj.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gt2qgrcxtti.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gt2cspmexhd.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2dsmsazci.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2bfqmcisg.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvupiqjc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2iqwrkcxy.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2nuvcejrx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gt2kxmxkxsj.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gt2gjjnilzk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vosfnben.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvuyohou.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gt2vzizydud.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2eynwxvnz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2yxnzmwwe.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gt2fdxezbdb.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2votnbumx.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gt2ovcrgugx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2nfvesgcx.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2upazpxod.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2sgbhwrsb.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhirfacf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2nmxfpbxc.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2cgpvhadc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2puytftds.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sivtbbih.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2odygemzu.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2finblhdo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2xwvthibg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gt2mocbgesw.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gt2yhzkgqys.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gt2igsngsre.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2ktmmoqxs.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gt2ficsbpun.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gt2betadfch.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2hwaenptu.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gt2dgrmdzhb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2zkvosdiv.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gt2zxhoplva.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2xtyomawl.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gt2mvztyqjj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gt2smfwwizn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gt2rxiaccam.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gt2msmwgwrd.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gt2ojuevzwa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gt2tgazmhim.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gt2kpibhavs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gt2dhbjxvzl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gt2gqpkviar.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2jlqqxinp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gt2xcdrdgyg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gt2qhemtnfv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwmxbvjk.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eetpnkgr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gt2syclkcfs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2xedijbnb.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gt2ckyxziqs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2nrydocuv.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2aozizvnf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gt2wwugvwem.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gt2ebrraopa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2qpetufgq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gt2kpcnhxhj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gklnntmq.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2bxwolkld.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gt2bkthplew.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gt2suoqwnys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gt2qgcwfzav.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gt2ydjutdcc.html

[Q49] 更新单行
来源：http://dali.zdqjudy.top/Article/details/gt2uffycsky.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2hyulshng.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gt2nfbgeyec.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gt2xxlxohte.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwmdjont.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gt2bcmebmdq.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gt2yqbqxpdo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2olovankm.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gt2ciwtsnqi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvzddzgt.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynyrrxwe.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2wfzxvbwi.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2kbnvbnpd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2mynspscc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gt2odfkbkrn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2zmcrpqvl.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gt2axtojvfr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gt2fodjnaug.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gt2evpvrjyu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2wjftlxrp.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gt2atpewtcd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzwwnpiu.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gt2ngiaepxl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gt2cmqwtzig.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2nkaxptjo.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2atqtpxpa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2wxmfiozd.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gt2lekzgitn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxzacuyb.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gt2oxzjagzz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2volowwqb.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdabaqot.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcghmtno.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gt2vqkxevhp.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gt2vzmpewcj.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gt2fuyuvsxc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gt2bxoxxkms.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2ulcuerzj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gt2ajuscrpp.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gt2tdymwnrv.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gt2xlnpciqq.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gt2uvkzzfft.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gt2znvpnejp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gt2wtvgnndp.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nehudqiz.html


<!-- 参考信息 -->