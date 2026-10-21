代发 wailian999

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtcawsvbnk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gtaaahjfpu.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmprgknk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtidwktvfz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gtjbmotxew.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gtyuaoqzug.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtsacsfmww.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtvsfcxyae.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtybqbiuci.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gtuzkdquwg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtdmpabtgo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtlqwotifa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbnedlxif.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtwecfcwyn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpifhqmpc.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtieqbpbpg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtgjuskhov.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtenfqeded.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtjaxgyvie.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtopgfabuq.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtmdgystia.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtmutbgzrk.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtcrwrcykw.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtihmdhkuc.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtqtctnfbs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtgnjkdhii.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtdbslbkvb.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtkmkxrfmf.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtogdppzbj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gthtkvkuoi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gtqrtsmvee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gtnffrggpf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtrzletfzz.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gtgqfsbvpy.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtfuoedfyt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtowpmxclf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtytgtwcwm.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtmpxtcxae.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtnurmbkvm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtrtglgepj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtyzwymcrm.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtmcqypxnw.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gthymnltjr.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtdwoccumh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtdpjivnji.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmuogkkz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtxgahaxcf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtyswohoqe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtqlgrcfkj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtyzxsmxxo.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtlbpcezdi.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtlbtspvse.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtedqaqqoq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xylfe.cn/Article/details/gtrbuxldtg.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvyqucyn.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtlwedgqqz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtpimrpyow.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvivyusqb.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtrbyrmtjo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtlphxrbwp.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtpaimjozy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gttnvjczbh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtrmexacdh.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtornfgboz.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtseaphjzv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtqhlaslyq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtzarvrdei.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gtdyhlqjwi.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtmgpzpops.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpaoxqukj.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtorarvjgb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbzqrglwj.html

[P01] 生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxyjzhuh.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gtiprfqhsx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtetbxhqdt.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtazwsbgnc.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtyyiovtlo.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gtggvwyqvu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.316326.xyz/Article/details/gtuiedidfp.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gtlagtbvjb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtjrhjyrgq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gtavfpzsqa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtzvpxrljo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gthuctliyw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtshfedqmj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteryfsjri.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtdwhvnaqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtflpagwzv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtslwlgcyq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtxamzzxnm.html

[P03] 生成短随机字符串
来源：http://dali.316326.xyz/Article/details/gttqfldbzh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtjgizejkq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtksjlhgdi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtymcuqfoe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtujtycszf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtnqgrfdqc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtlcljvlvw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtufphoiad.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtluadruva.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtptbxpwuk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtntwsvgqd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtinmykutv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtyhgtyrnh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtgwrynkgn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtxznlnjbe.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtytryvbsa.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtmckiyxoc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gtngmgkgcc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtzhbqckhm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gtdvzwmowi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtkgdwvscx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtujukmkzi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtrjecysyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtshbznrts.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtolmkqzpz.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtjbgnkitg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtjcshmjuk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtubkaizaa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtuflckrpz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gttqmpqdgn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtkeqsiiml.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtttgpyinh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtgfavelet.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtrqiiajki.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gtpbzwnflx.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtepnqxhjq.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtmajitykr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gtkvuwqtzz.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtvejwqzio.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtiucnqyiw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtnylitqbh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtyfwubq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtytuomvbi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyvsyrfu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtqyvyasts.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gtvfhkrxne.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtwdrifjmz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtjbadelqu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtdirjaqhk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtrylpqzvh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gttasswxap.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtbhbkbbhu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gthyerwvve.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gtnplghemf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzytxqdfa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gtekdkwkog.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtztfwwrim.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtajegpwuz.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtfzemjegx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtdhzqdrbw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gteligbkaf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuquooyjc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gtuktmdlks.html

);
来源：http://dali.cashguo.top/Article/details/gtkilzjvmn.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtsfeufyxw.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtfhkbtewx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtxrgktebz.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtvheyibnc.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtngmzygxs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvemdmlz.html

);
来源：http://dali.yj20258.top/Article/details/gtejbhveap.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtfapcfckh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gttzdivmhx.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtqjzzxujh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtiscazdeb.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtyymsvmxh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtksfcpmvz.html

[Q06] 删除列
来源：http://dali.hnqzz.top/Article/details/gtqizhkirh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtofyzaiyo.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gtuvlnbbhd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gtaocdaatz.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtygwcpukq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gttxukwdkf.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtdatzioaa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtjpceynvs.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtjubwkuyc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtmdkzqmxf.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjzyqjqu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtgfncgcoj.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtjkojivqb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gtpslowoho.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtyhzvkgnu.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtzsvemfzm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtrktykzcr.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gthplklsko.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtqbnxrquh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtxrgtlntt.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gtjlyhzrnj.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtwbkpdews.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtvluhpgor.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtyvsgfsrl.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtszyvezas.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtkdiuqpiu.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtbroohizp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjubgsvf.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfupopwsz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtijfwsxzi.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtavuxfuts.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyevjzeso.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtegspflzr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtxifvttpc.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtphwjamgz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtuenhqmmc.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gtydmfsbhs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtwbiznuah.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gtwhoqtuxd.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvywypbbf.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtukyhxhzz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtnobuwzkb.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gtfdykzbpq.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtztpeevtc.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtonxdqwnz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtjvghhqbm.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtglmztcxg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtaxncvlme.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gteotlldtf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwsevkede.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gteuavnyta.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtkmgswuhk.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtnmhwmjoa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnjemckj.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gtzslwxatt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gthepmszpr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gtfivgnemf.html

[Q33] 多列分组
来源：http://dali.hnqzz.top/Article/details/gtndlyzqqc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtlegudqvp.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtrrjwhpyf.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtbrqsbpzg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtnwuiswly.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtupeiwsfl.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtompjnyxm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtqfidsbvc.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtjgjbfffl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtpzffbbbl.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gtptbefhfd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtvxdyrxdv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqnqpqeu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqlgzgsc.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtomfjphvo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtyllsdjjk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtnejnxwky.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gtlfewhcya.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gtmmfvtvey.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gttuneqsrd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtxenzxaxl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gttnbjcend.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtchxyniaj.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtobhgwqhf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtrawmpvib.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtwfwuzjxw.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtnkqiozxg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtolxgztpd.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtggwlsvkl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcggtdtym.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtjtaewzvo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gthymwlzvx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtichrqvww.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfxcppce.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gteuexbotp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gtmegfxspv.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgufenzy.top/Article/details/gtoyaxkale.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtebkjjtlg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtqqidgynd.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gttokilyng.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtskkcdoyh.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtslwtpkwd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtlzohabvm.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gtshyxfieg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtshvymysz.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwepamezc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtpovpllwa.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtifywxnvx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtsckiinjt.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtwkicnqkx.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtsbcyjsxh.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gtakbjmwxp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtaommxwhc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtcoswcjso.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtxpxsudvu.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gthausfgbu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gttdtgnbwe.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gtgatmkanj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtavkluvuy.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtxuysmycc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtzwsuzgog.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtlxvqbmvp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtgvbjkgdz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtqvkegmst.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtawcuxwao.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtzwofmzzs.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolsbfiqc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtykqodehr.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtdmieourq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zycfv.cn/Article/details/gtaywzscws.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtxqrygukz.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtuunuytju.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtpgkvpfhm.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqrtrhfg.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtqukfvuzl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gttdmsunsb.html


<!-- 参考信息 -->