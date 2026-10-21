代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtpwzeplug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gthaklbpnn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbxyhlnv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtqbbbpppu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtkgqtsckw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gtawyawwhr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gtkytcnlxe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtyodnejim.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmrgqjnwk.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gttzganebl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbsigvsrk.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtxpyymomq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gtvuwahltv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtysmbvevc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtkpnjavuq.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtzenotrax.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtkglkgnwj.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtiqxgtunh.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtwgeyztuu.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtjnlefzlm.html

[O02] 使用线程池
来源：http://dali.yvedp.cn/Article/details/gtlfryjsva.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtiopgcoth.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gtlgcdroxm.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gticfoplul.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtwfhwrwhv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtcpveyaix.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtsjxgnkki.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtvkhhtvrb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gtczebtsjd.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtsbknpual.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpirticq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtgcmbhjfy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gtijjozhwf.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtcqdqhory.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtbghlyaud.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtgbvnajyg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtkgjpptut.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtssrmpsqi.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtgtmiqtll.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtmwudtwxl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtuxmmuzkk.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtcicfccso.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtguoknkwx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtereqwbhi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnxqaayp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtlivozprk.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtuwseezhu.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtalfxeubh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtlnxjwnsa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtbvmlhcxm.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtfkyludjw.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtmhsmtnss.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtzfetqdkk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtntghsfwm.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtlthbxiey.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtondaaohx.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtqxstnldx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtunmgnmof.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtfndbjmzn.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtkolvvkyo.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtpdumzqwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtogvjnaha.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtnbtqctmm.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gtwjsphgpq.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtxifbgjgq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrausrszf.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gtulqidcag.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxgxavsp.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtrhglvqea.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtmsbogjgv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gttkzrszgz.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtagsyshgv.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtdyxffalr.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtivqttggi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupthrdso.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtbisxgnog.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtcawtavfs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtgvhnouur.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtstwinywu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtlyttjlrd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtnddnwugt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtaoppvoxm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gttzkizrme.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtnkogqljl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtgdwzadzx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtpryiszvt.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtckcsoqln.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gtvpuqpdlc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtndccnvwf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtebjxlulh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtvjcsuyph.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtylvfuniy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtytdykqoa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtuxwprfeu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtlqyvgipl.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gttsugjrfb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtqffjczms.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtaninwvpe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtlbgjjjua.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtfmvdmouw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtjjgimvhl.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtprxwkjik.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtafyphtgz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtjjrgypne.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllietchl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtrxmtapne.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtiuubctdj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcebbmgsb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtyluflpsv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtozgotfek.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gtwarewtgs.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtmstzycuj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gtvhdnkwyf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuanzx.com/Article/details/gtvicgkcun.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtoopefhud.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtwnedzqru.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtcytsulay.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtorsiyhvm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtccimqvbm.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdodixzv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtbsauizfh.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtxaisdvin.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtlfyojfle.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtorrddoqj.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtrceqldrn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtljeielqp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gthakimfpo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtcsotsaej.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrwtwppb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtbjkikost.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtveamvtoi.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtvsatqnml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtyrccvecw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtnqffmprk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gtrnuthrvg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtxceislup.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtkxdqwqkv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtflyjiafg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtvbwbtfcs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gtnonwrakf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtigfooyne.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtnbcbfnoa.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gteofudjcd.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gthkgwsuhn.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtyxjqmeip.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtuejzeogh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtnmrrioqe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtystisjiu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gteobtoaoe.html

);
来源：http://dali.hywenlv.cn/Article/details/gtlbpselqi.html

[Q02] 创建带外键的表
来源：http://dali.nanxinkj.top/Article/details/gtpxzfesvj.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gtybpogpcq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtajtpfkxl.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtqysvrchk.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtbxfvtwvm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtepftucxr.html

);
来源：http://dali.sufxvd.cn/Article/details/gtrsexzfic.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtziuekwtt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtlkuwykle.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtvvmvtpks.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtnznfwfdf.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtszquccsl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtvlxtncpn.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtadzczqok.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtenldhnyw.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtcvwbhpof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtnfqcytwf.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gtisijtoio.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtjrfejyfw.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gttysubmww.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtcqsvctxk.html

[Q10] 插入单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbuctdph.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtcdgntotf.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtypjymjdt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtqkfqslic.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gtnagcgfrw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtfzapuvoz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtqllpmhkg.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gtndrsmttf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtrebakjjp.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtpmgylpzy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtkwtsowmk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyaofzue.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtlvcmnjkb.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtqgrxbwlx.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtleilclqq.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtawsuqrcd.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gteqliskmg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtamrrgwbd.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtzsoljfol.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtljxrvnxt.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtmxzrtasv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtrorgyejl.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdzisnvi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gtlicypsov.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtrmswawtc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtchxphyka.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtlnglheaa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gteeciytzw.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtgghskzda.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtusmfpvdj.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtxehcmsoa.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoswtcixu.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtzjymslex.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtkdflvqae.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gtgwqclppj.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtooywpful.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gtgpqmcwho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtwgfmzjcl.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gttedoiusg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gthcqrtthj.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohbpqxtt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtiieuynjv.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtisfibhqt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtpqwylzta.html

[Q31] 分组后过滤
来源：http://dali.tianlin.xyz/Article/details/gtwlmypeql.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gtduogyfxe.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtcubqmopy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtqbtvwgts.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gtuqsjxuwq.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtliclhzwb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtwuigwhto.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtrktzaled.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gtdcysbdjp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gtfyefllrs.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtlnyguwsi.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtmrjnyvrh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtoxxvctvj.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtxvqfpcyf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtwvqcndnt.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gtxylffduk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtpryxwjry.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtujtavfen.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtkqptgsln.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtzrxjsmls.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovopfhtr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtgnquggey.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtjktyvmam.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtkikaxqnp.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtcgvshpbr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gtpxpekfzs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtzyeonnsg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gtulltwita.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gteslkvkkc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtghedqxdd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtjjzvqfyb.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtyurewsih.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtpqrwqysj.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvbnefeh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtfthwekaw.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtwpqspxox.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtiqxmqkbh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gtasggapyo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtydhxhslh.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gttpfdrlmw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtkhbertwj.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtpncrennu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtjvrbubmq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtkirlaoij.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gtfmguesdq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtkixwxxzb.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gttrhypibc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gtembqgkbt.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtwpzacvcy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtxorgvuui.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtqxxcksic.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtsmkgsyvq.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtlulkfkuj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtrebhqmfj.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtmeacpyfa.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuqoctvx.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtsepawntn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gttigmizqa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtfwwxjorj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gttwprumwi.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtavyuclhh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqpisrvq.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtsyhbvcev.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtutquazqq.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtihlhsivf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtfesnmico.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gttgpxmerz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtkbavgkry.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtpkadplar.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtewfqomtz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtdjglallj.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtxrckxkqv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtystevqah.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtuovchicq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtdtmrdufk.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtwqywkfws.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gteoccqgps.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtnpnnbxsx.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhkyobpe.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gtiuvxldcd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtuumdahig.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtdfaagnxu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtqhtdabhm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gtkmrjgkes.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtioxwxmhz.html


<!-- 参考信息 -->