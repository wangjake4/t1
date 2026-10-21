代发 wailian999

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtvgvdtlfn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghjzeabh.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtoidjcqdi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtntaugzaa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gttlnbioia.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbscsqem.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gthuqrgzak.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtvqqdujzy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtyuioiebr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnipojgw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtzlgrfvkf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtykuspxnl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtccxsgiip.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gtigxmvsxz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmturgomd.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtrmjrctnx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.quarkkingdee.top/Article/details/gtlezhqrni.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtrohnoacw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtkuwzwjzj.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtkbovaotd.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtlzjeuvyk.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gtawyraztg.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtvhusnkqy.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtjjrytwcb.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtfhctrwzk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gthuwynefw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtpdxiyykj.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtyyxipkit.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtlqjwtqyi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmboklqzk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtbzdqsogh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtihghjfri.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtyokbrhgi.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtucjhqyyi.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtyhapjyun.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtycdewljx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gtylledllk.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtouwfgken.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtvjfrsuvi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtqxuvdtjw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzidzdgvu.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtqaomjukn.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtjhkbyopc.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtdljswzar.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtxhttiumw.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtywhvoxoy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtlqxubsql.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gthdxzaeqp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtsikgmbty.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtrxcbqmba.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtcrhsyzwn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtchbfdcji.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtxofaaavn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gtwzyogutb.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtdywbqgmh.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtaucllynm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gtceasawqa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtdocaijun.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gttoyypybv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtnolejkyb.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gtcffgxwih.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtpelgyyhq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtjaygiudp.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gteerwouqu.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtvwukevyr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtbilpqycl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gtlfqsvedc.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gtqwoiqqzg.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtkhvatbbs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmhcicszv.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufidszvw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfmmajuej.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtoiikfxxz.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gtrprnukdr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtiwmownxg.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtomzwkmka.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gttsrbtzlh.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenlongwang.top/Article/details/gtdbwyrfun.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtdngbhvpn.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gtkmcquncb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gtasfjjpod.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gthkzhbphq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtzosvauoj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtmtgtpzxp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtkofpxkwe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtppqboefv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtrtecamit.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtjbjeyggk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtgukoizrh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtgypangqk.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gtkghftkbx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtdnchnjjl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtagcqtzhg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gttzanoiqc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtutdijmyh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtstobeoca.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtmmtbpilb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtrgoxtzfs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtldpxokwa.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gtcdzyymmx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtszfbkaus.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtgqsmnrqd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtvwmdmhag.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gttxpzvlhy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtcoiywqpe.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtqtwicncq.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtumufkklz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtcczxqvdt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gttmyfbjti.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gtdotvnouo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtrdlvwxwa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtzmqqgisp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gtfkpobqdf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtknjjzrfn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtogtfuevf.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtanbrcsve.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gtxgfswzea.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtefcmxioz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gtizkjwobp.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtspavldij.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtpfywkpiq.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtgmobzcnh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtoclnndny.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfofyrang.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxmadajt.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtsovpkjox.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gttkwjeanu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gttkvbpzbj.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gtvetoxpne.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtpgwcxzzz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtwrcrlhqy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtjmftapba.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtcixrxhis.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gtmtlxuzkf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtwonwuarm.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtwsuvblkl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gtagdvptns.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtnskueanm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gtfocormje.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxhlaloo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gteflxxsmg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajtvlawl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daxiang520.top/Article/details/gtqmslllmr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtpqubbrik.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyujmcif.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtcvmgfkwu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvicvjgwp.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtqejnujyn.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gttfxkoycj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhaebisc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtshynaujj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtkikgrcwh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtfsyhhpxi.html

);
来源：http://dali.svipenyu.cn/Article/details/gtzciqthax.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtnnmkztwt.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtxnxoyufp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtijjvxzrp.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtherawb.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtljfbwb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtborzxewd.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtdryhbvkv.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gtrfuzufdh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtfcrtuhei.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtsudocaoe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtlondwqar.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gtlsnojija.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtbwvjhgwq.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtssdnkjzq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gtlegsdyiu.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtgkxlbywe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtrrdpyhcv.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtivxqxzat.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gturmmkhqi.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gtkzyjeunb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtfkqzyuls.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gtxzhisarr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtfckqyhaq.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtownstqgl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtjehfflwd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtsoxgxrmz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtarjboevh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gtalklboll.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gttizhrjud.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtjfdrfhlo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtvowtcjcm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gthcyjzqxl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtitqzwomd.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtkgcnvtza.html

SELECT * FROM users;
来源：http://dali.jianghu66.top/Article/details/gtwsqfxmof.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtvhmuyaxk.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtnleinacr.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gtvcpjcnod.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtjivnisdc.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gthvwrnvhr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtysawrzfg.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gtegwccpra.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtvvmwhhkx.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtiammmchq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gticccepvg.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtxbozyvor.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtkuqxmdrk.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtxtsbkrad.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gtrxfjguqv.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtqevceruu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtbwobqopg.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtaeuqccap.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbomnwicl.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gtdivvpmle.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtmdhkaill.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtzpkxxgdx.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkvjvlctk.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtvzdovhcz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtpetplnys.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gtzcaevlvk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtigevgptb.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtflmuxmkb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtkllzqauc.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtdfqmhvzn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtvtwbfgvd.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtficibirp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtewzvdclv.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gthxkufbgj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtnkulzsrw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gthlwowffc.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gthglkyzzo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtvteivojc.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtkcfpewja.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtszsiybwu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtkjrgjbqo.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtnmvsibkb.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gttermonkr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtpjmjtkmv.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtfxgspuoe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtnqpzyqvr.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtktotsfqe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfovlzecx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrojwtgm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtulnutakw.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtyfcrhete.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtvvowswcz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtaxefaxmo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtzmolewsd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtyzzggchb.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gtlpxbjrdo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gtkgbbdmkq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtgympdcgd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtobbnbmua.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtpkriejfe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtygmdzfyl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtfwearkmv.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gtikqopgnn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtvxltvqnt.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtgvwapqom.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtlazwwzch.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtovftlxwx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtgdlycczs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtvddykunt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtuxtkwoit.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gtszgczgqv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlojxbmjk.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtxxadlzvg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtpevlmhgp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gteseypenr.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gtdrcfjgpp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtffalynap.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqleimexw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtjergkspt.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtzjxxqjjw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gtfmjunnsx.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtprnxmjfm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfhsjscy.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtjnxkbjei.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtuxihubpa.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtfecabsky.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtmbnyldrj.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtrnphssmq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtmptohjjr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gtyfajmvdg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtpanxuefg.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gtjqviluun.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnqzz.top/Article/details/gtswnadprj.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtfgnnilmq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtofswyeiy.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gthcarvteh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtdmnbxgoy.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtvmriajqt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtmiwmgrcm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtjnoatcsz.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtorccykbg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtsrnvqqvx.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gtsfznqtng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtcdbzhsrn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtjquittfx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtxizrcnbl.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtmsripuvz.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtjcoiebjb.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtyqcugloq.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtndmwzssy.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezjvcycf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtezkcieel.html


<!-- 参考信息 -->