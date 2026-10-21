代发 wailian999

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtgljkwlov.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gtmyuzfpns.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtmncpvcpo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtqatpkrny.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtcaxrtkug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtqpfdlgyn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtqdlpandb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtbxfelfyp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtcjkwyrbn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtkvrqrzqj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtaugovdon.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtdhvypzec.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlpwfhojf.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtdzzuslhv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyxulpshz.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtcqfoedbt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtsyzrvyrn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtrdsqksgf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtaykcdpch.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtlsbyadmm.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gttassgbfn.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtchuogxwu.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtnplehqgj.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtxesaxllm.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtzipizrlx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtncxprzqr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhongyouzk.top/Article/details/gtwumumwfc.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtrmrhmszh.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtsdjcgads.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtktmzgjyt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gtdyjwwrnq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtxqoyzeyj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gtflrinhhg.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtpmrxvfij.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gthptvhelk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtuygfyhom.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtoogkztzm.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtjijvecil.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gttcljlufo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtjczsjpqf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gtfrpxjjzb.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtwbdihtkm.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtmrvpegzy.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtdgrbekgs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gttwalmvil.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzfyfmiaj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtcypjonfh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gtflnfkdqg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvdvpiei.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtiaosjxnx.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtygbxzryx.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtqlaajgia.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtpgbrqalo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gttxtxvxrq.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtfviqtwkp.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtfwcnxzrb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtcactpqry.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gtamlwwlnq.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtqxrtdxgn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gtqwrfqcrb.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtiddhqiqh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtpujouvhx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtbofiuokg.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtcimixxim.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtzxabqghn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtkrolkhin.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtstbrxoqc.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtypwdwede.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gtdpwvlfdn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdyumydrt.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtpidgsccn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqgscchhf.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtrwlvwzde.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gteclpqauf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtickdpzmh.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtcpyjwmal.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtiqdtqzgn.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdatcweh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtddrmutii.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtfnawsubj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gtafayyzpj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtajwolcyz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtrcqpkeuv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtxcwbmuws.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gttqafifux.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtvsqljoxg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gttcahkvli.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtzcsbghyl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtjgmpdqjs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtqbzrkevc.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtcrkitpjd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjddwjvmd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gthtzqoajd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtfxzupvhw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtzkyvec.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtmgpsigqm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gtdhdbynwr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtlivzjeir.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gtsmumfgln.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtlkfqmpat.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtfcxoosek.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gteksqkxou.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtkwtsilvu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtbdlywsqn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtinykvnrd.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtnotrbfto.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtaccvshob.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gtjyyzbthc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtxumcxccy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gtkkimlhir.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtwzelkswc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gthxpoabwb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsbxsyuo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcreqhgsk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gtqvjsgzor.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gteofgjiau.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gtlwyhoeri.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtmqgumurv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtdkdlxesi.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtizzeuzvz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtlqyozgqy.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtatbwvkwd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtzcxxmegd.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtxlnywxnb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtsarycvmh.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtvocngnew.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gtoosotfyy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtxueztkqc.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gttirsaxbe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gteoclbeqs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtaeygnigk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtlxcbgomc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtjsgynkuu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtmgbvuzig.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtljcstybr.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtluqvypdw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gtonwghmqf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtlmccfgfs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gthdieiotp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtmjichyls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtoskvvbva.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gtwqaednaj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtosfguxgy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtghkoiyvj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmmokoobs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtopqtpdfp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtedaeulgq.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtnyqfsohx.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gtemxapjbz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwsvrwzx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtdxvomrtx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtzinukdft.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtukautncy.html

);
来源：http://dali.316326.xyz/Article/details/gtqdruzdau.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gttnnozlzv.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtwsjhslwx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtispzoavf.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtlbjanuar.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gttvokmyod.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtdihhlqps.html

);
来源：http://dali.chenzaomai.com/Article/details/gtxdeswsct.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtprinpqlz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtwcukoqeo.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtrkecdkuq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gteyalufkn.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtcdlphhzk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtnuxbjdys.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtvdumqbux.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtxnokhcuv.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtjfhlaldb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtfuhlfiiz.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gtfzrjaqko.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtvtwusisx.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtiamcaenb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtxigthzyj.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtedckvmrk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtfgzaecto.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gtphmjldot.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gttwslorjj.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxgtqxoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gteqcbybmq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtbyptilww.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gteougegzj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtcdwgnwqn.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gtxdthtdmk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuifkquld.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gtpmuicpvh.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtvchhgbuy.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtkppyqktt.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtinbsikkq.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtucakjnnr.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gtgmpdckxd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gtsfnmmmcp.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtphvwvqhi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtyjkjutrn.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtlvwuswad.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtkoxkerlk.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gtbhzqjvjf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gthzigbbdo.html

[Q21] 空值判断
来源：http://dali.tanke756.top/Article/details/gtvwqkzbxe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtzkqgxvuz.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtlubwbvpy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtrlnfrewg.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtaiiqgfil.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gtteufccvm.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtgokjqwbk.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtjjaxwmet.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtoxancwtq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtnxzkpoto.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtsyjniufi.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguauiiiy.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtgehxssxi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizewgiej.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopwgdnxw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfbdatxf.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtbfjmvhzl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gtrijvrukv.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtrckcxkia.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtcsaiucad.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtlirakdhg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gtocanckvr.html

[Q32] 分组拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtvygbajke.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gttzotiskw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtwozobdgr.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtqlraiijf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtqzpksbcb.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gtnlptnmfj.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gteioiirtf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtnqxcrbrn.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtiuhtwete.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gteezztzgf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtmummcydh.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtldwkzjhx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gteldfatau.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtzbiibbba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzvhkhzz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtdecxzwuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gtkazqxxyn.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtzwdnpaqd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtsuhfhbco.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gtbwisxerd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gtvmpihyti.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtuujocwgx.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gtwzrszyry.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gtwqxlspco.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gtxlyfulnl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtaoxusagr.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtgmndijrj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtiauccoxu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtolrxprmm.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtcdamokoa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtmcdcdtcs.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpillzkg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtrguzstxz.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtqporhqka.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtaovsgjam.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtteyowbji.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gthxzgkusn.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtxjihkccw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gtkrdnalpj.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtmbuenlhb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesocidat.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtdsothrkc.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubntsuic.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gthfzjxiyl.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtqawukhbv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtacbmtwsg.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtlmpmxgoh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tian-w.cn/Article/details/gtwhbxkkln.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtdtqzqvfd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtwcichjkk.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtwikmgxwm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtfgcuavwo.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtfzgahmma.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gtxiedmnhf.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gtcyimnemx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtnxapjimk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gtardphwyy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtjlrexmwo.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtwmwbnyuk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtccsoyigq.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gttjbfwtzu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtndlqnxjn.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtfabvndwk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtwideqjjb.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtnckehslo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gtyisujznu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtyekwxdyj.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtsvlgjvgm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtjbxdjcyl.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtfdztzzzl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtgraqvyvz.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtzhgueoza.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcblqyvxv.html

[Q64] 提交事务
来源：http://dali.ivvv.top/Article/details/gtauixkteg.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gtwalgruep.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtbbvpzltz.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtvzmvejch.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtxkjqtjrr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtdxuorsgd.html


<!-- 参考信息 -->