代发 wailian999

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtvlrmifju.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gthnpzkles.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtlskmccyo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtwoacuvzd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtejegdkgz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gtdlcfgbdu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtawwlvnzz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtbobkiazy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttciqriuf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtypevggii.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gtryeyssuj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtrvwmiptg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrduexper.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtkhwnkjli.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvklmkhpv.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtwlolwdvk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtsbzlazzw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gthcvmzecb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtycarnaqd.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtoigauhbk.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gthvfpfsfq.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gtvdpkifce.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtxqecgueo.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gtstpgcwny.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzutwsbsg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtqqalfqtd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtnwfofvss.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtxxhirfra.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtzjwbpftp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtdmbaepti.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtzugrtqoe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtcxezwcru.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtyafunfdx.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtyecebfne.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtkkhbpndp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtpjxfzqoi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gtbeszbtqy.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtprvqinks.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtmeaikmsw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtoyxbluls.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtlrbokesm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtkqrfpexv.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gtpeeaxigy.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtyglovwyc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gttnygkcur.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtnbdfgsmh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtaimghjhp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gteqlphdhz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtffclooxc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gtumvejoep.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsddqkfmw.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gtducrvsfe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtzwkhueaq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtzwulwemy.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtrcbtnhxs.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gthnjfmmvp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtydxyesba.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtmfwpyqgg.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtvhcfebbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtewaklvgu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtqbmwqzbg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtyeittjkc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtnfsgdgfk.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtgltfxdqn.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtcmyhfqjd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtpmfqpzmd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtscyngtgx.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtdbhzwtnm.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gtprgbifyc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxcoaavrw.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gttzyokkkn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdsdvypo.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gttjoukewr.html

Py:   str(uuid.uuid4())
来源：http://dali.fzhhl.top/Article/details/gtufogpvjo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtytujefca.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtdcrwcfch.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtqjqqxmkm.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gtjchkfull.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtnyhhyxuj.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gtisvukkdt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtuiwqumla.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gthudyekvg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtuhiotxbs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtdimdvwus.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxdorduy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gtzhjsxhbs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtcjzxdhho.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtxqscthfv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gtrxrtpbut.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtlavpksst.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtdazhgtyr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtytxjdzbh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtvdhebbrw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtugiseedv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtljpuowsx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtdkgjyucg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtyymhnzpn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtherrmfvt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.andypj.xyz/Article/details/gtrwudrynt.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtqqsfemhc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtpgiwzzum.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtupjntvsu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtnwwtflqq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtpekoedvw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gtbtynovtz.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtmuwfxtyu.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gtqoomcedf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtuarfilgj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtbqrmldwh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtrgcxxufx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gttnvkukgk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gtvcpanpap.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtdtynclsy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtblxhaicd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtvtopfvva.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtghqpnfyb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gtkyjuwsdq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtubhfzdqu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gtxojhuazz.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gteegbbdzq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtlyisrfgn.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtqwecddpb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gtojvmqtrr.html

Go:   if x == nil {}
来源：http://dali.fengsongda.top/Article/details/gtvwssspto.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gtjgswoeso.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjyldhia.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gtfpqlldqs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqyabfzj.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gthgdwgbqh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtnslkobmu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtpraowtnb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtgyugswrl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtfgxzwjbv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsnklnts.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cheryme.top/Article/details/gtstmxynow.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gtznvulkru.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtukbhsgfd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtnvnidaba.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gtrnulcgpo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gttuigvbxa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtikiawhew.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtiukwjrxc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtzgnsmydh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtipomnrwq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtlzkelviq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtgcyzxmau.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpqrxquyu.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtauglrqdn.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gtcoygibrg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntsoxgiq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtbjpvyckd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gteccmnmzl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtwelcmxzu.html

);
来源：http://dali.jyoumei.cn/Article/details/gthpwiskmw.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gtdvvoxvgw.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtuhtskf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtsncfztdv.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gthcdcuyor.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtdljqqmzu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtzfgkjzoh.html

);
来源：http://dali.mhx1999.top/Article/details/gtemmotanl.html

[Q03] 增加列
来源：http://dali.guowangkeji.top/Article/details/gtztbihmph.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtovlelnng.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtbndghmuf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtoittouje.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtwavebfxq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtctkzlgrb.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtofwgnsng.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfmmmkvr.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffjigblo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtrqvhikji.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtzplqkhnk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtzegfwniq.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gttttjrawa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtxiibijnb.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtzpobxapu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtonqmaool.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtzakwbpgb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtexghfely.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtfwhgceqo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtinrjodos.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtfbshnhfy.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gtqffkoyxa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtbsezwqma.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtmfkixgne.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtzmcqsrdc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtsbjllwqt.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gtclbmougu.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtpmfnyrdj.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gttlrfktey.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtadqlwpba.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtpqlvbqjb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtuymroooi.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtjrrghlnc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtueaeqksx.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtibijxfaw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtslexuzls.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtdluttdrp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtmkhizhab.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtbhwdysjx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtgzuihadz.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gteypswdxr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gtireqtwbz.html

[Q23] 分页
来源：http://dali.cqqwz.cn/Article/details/gtgfrcsvoy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtrefxttqb.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gttpuzkvwm.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gtdbuolbdf.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gttsxmtgwq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gthqohmxqb.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gttovjojhb.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtuksinugs.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtouicdfjo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtpgugnmqh.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gthebrjkwi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtsmgfppuv.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtjjsnivmw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtracyddor.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gtrxkgzpbx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtxxeqqtkq.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtybrdxgyc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtbqsqynrz.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtxlzmwkrd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtmpxugx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtphgwqtif.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtijtjlaqz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtrscyvscx.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtwvlflmxz.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtiksbtquo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtfgldscqc.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtdnvxwfjh.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtwtxwcqzg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtwwnilgdv.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtvdrqvrdv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtzozuxnmi.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtvndeehib.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtnpekzrgb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtittjsdcc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gtvfhrusng.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtarcntgwb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtpsjpjxtg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gteuzsfjsa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtkjqdexcl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtfeuhtpvn.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtsluvuqls.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacfoyfyl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtpmnkmdyc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtkxrcsnvd.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtqbhtbcqd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gthxtrtwqh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtuiixfgnh.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtaqoqhzej.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtcjmpccdd.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtregyldqs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtzfynuqyx.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gthtxydhzz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtludffxaj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtoriegkog.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtzvwzaiuj.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtvhvlzvrw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyfalqmg.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtdhugkxlv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gtyoiwnxqd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gtrnnubuaz.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gtmkcjrdpw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtbscrztqb.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtdexscowx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtfdouhtrg.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtwkamkiay.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtqsqpttxn.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gtlczrheos.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gttxxewrkb.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtlvxvqzst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gtxuieqjdi.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtdlvqtnzd.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtvrtkhbbs.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtmyrjocgw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtomhgxccq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtftlwumju.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnxjjewq.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtwjywjwko.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtoyvmdore.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtcjuvbxvq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtrtbphasm.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblfryffn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtqpiynote.html

[Q60] 取上一行 / 下一行
来源：http://dali.svipenyu.cn/Article/details/gtkwmbusbw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtwriswbxl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtsryoqtjr.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtzawymcmo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtrtdqgwzd.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtutkiobcx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtuwluoyma.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtoxgiwwpd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtqgxxegnf.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtaghptnxa.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtzwrargrm.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtdaokcbij.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gteenapuqv.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtxbgdkojh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gtsxkcafuq.html


<!-- 参考信息 -->