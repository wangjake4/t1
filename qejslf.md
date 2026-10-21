代发 wailian999

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtssmjqxaz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtiuwjysnx.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtnxailnbt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtsvymzfit.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtxtrxmgxe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gthjjbljsj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtkmatgtgy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtphevmzxz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtfkaehcbz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtedvbmhqn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtlcxfuwdg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtjwwldxif.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkuogknqu.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gtuaggntws.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfntelcef.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtpaevlxvu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtlwadewxy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gtbaqpnaps.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtfrhovokj.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtgcinyztf.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtgoreuese.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gtqkarnoiw.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gtfvubmloa.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gtywovzmyt.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtkuhtyvtb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtsjglgtop.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzgsfvdm.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtwqczfpjr.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtpssgvbxy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtyqngdaxu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gttjpzhqdn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtesrpwwql.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtkgenfzuj.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtgmwbecbe.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtaxazgqkh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtfuhpntwx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtlvbjnfke.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtpidwyybq.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtwvsjkupo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtiwdhyirz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gthqocxsal.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtshbbsmdc.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gtxhcqgpmn.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtumwjltyh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gtiiyvmjkx.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsbieqael.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtpbnakfrd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtorhumdew.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqogkhsay.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtmmicargm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtvsaizcdf.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtygvdqslw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtolusgsef.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gteggfynpf.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtlmxqcnll.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtxqggnmlq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgqtpahg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtlinjvxdr.html

Ruby: threads.map(&:join)
来源：http://dali.hnqzz.top/Article/details/gtihcohsnr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gtebdwojhn.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtowdpgzli.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreboqxxx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtfpfcdrpz.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtrhykpezb.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtxdaprahb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtdirztpgd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtcuatpcth.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gtqomiysjq.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtnwveqsba.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjwpeomvq.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gttvmpjoav.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfgprnwvc.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gthkxswctm.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gtfgthbbxq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtzhmjnqjm.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtewwulkcn.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtxtjivslo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gtazndotef.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtqqgofwsn.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtcmjvklrt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtyxhtxypj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gttukctyqu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtrywabzsq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtswwnikda.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtvrzmtzjy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtvelfmqmo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gtbmrpohvk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtawyhciha.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtttlmqizi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtivmeubip.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gtlzryygeo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtwdcmsvzw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtvbhwjrkh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtpkwrmexo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtpsbfgnfh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gtusvydpvw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtfyhkqfsi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtbrzxirkc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtudpdprfh.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtjwrkaajy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzdusyst.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtmnldzzfa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtowrqflok.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gthkeaovdb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxictnvqx.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gtgzvmycxa.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gteofcruay.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtqooxyeth.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtbpwaupzj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtlcstpbzb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gttleiznrm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjdtvhvp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtztzonjsv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtonialirr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtysibmdky.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtnkcimift.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtufbsvygy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtbpsdprdk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtsxykinla.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtvmpibrjk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtbxqhxijv.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtverhudqc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtejmewfwy.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gtoiaquzrc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtwsgdedrg.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtpjmpfxyr.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gthrxakrmt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtqvxqmcdt.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtqomtgywt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtwwtltuem.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtdagxmqsa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gthqdhxcgo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtvhviadtq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrkmgrol.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gttejzgfzi.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtltfslnaw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gtlrbmzqtl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtkrqxzfri.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gteealgzyq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtfebtjpcy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtxhegxask.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gtoufzsxru.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pycfn.com/Article/details/gtpvoskoxt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtvscktaou.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlnswsheg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gtqnsldmrq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtithzemgc.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvagrcak.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtegiwdnun.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtvhttoqct.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtrjlbuzla.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtuasrglew.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtirpxdgqn.html

);
来源：http://dali.shuidangran.top/Article/details/gtgcurzvok.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gtsbwufakv.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtznsiwfqp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtumpecrkw.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtbbrgoesj.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtyfcemywo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtqmkeezpd.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtnlxawmnu.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtqyzkwpwj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gtdpcpyhfr.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtzfwkayfw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xinyue.icu/Article/details/gtjiqexdqd.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtdikuybop.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gtwzzjdtbj.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthugtxoiv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gtvligwrju.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhrcremr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtwcdujhpo.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtsinavbye.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtdaemzpwl.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gtjvusrhqg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtovdezirj.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gteckjexlh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtgvbmzmki.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtuubcmmsc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtrpuawvbf.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtqwxkkudj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtndwqpahn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtkxnbsvzd.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtdmwugdvb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gthpmxuuru.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgxtckzn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtxsducrut.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtuxlagrzm.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gtqpetrzln.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwvlsknis.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtwojzzhgc.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtkiqiiayi.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtpexyqehx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gtzbwvkrng.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtorllukxp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtrdvlwwid.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gthoghmsfb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gthufxnnvd.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtnggxupvi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtankvliys.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gthxfcccrk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtmhyjystr.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtryozzhhn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tianlin.xyz/Article/details/gtuqxqwger.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtuvbpgipu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtdhjoglab.html

[Q24] 去重
来源：http://dali.ppjwa.cn/Article/details/gtuflahajc.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtuemdkwir.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtpnlpmmcf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtstsaluje.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtesdkuyem.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtdplrdiqw.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtzpxumibw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtpmrpajwk.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtimxvteaz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtyaqfjikm.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtlkimrtev.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtygrstevf.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gtivzrwjlb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtrovurncd.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtbixahbba.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtrdlrjgue.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtzbmgpxob.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtetynxqta.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtiogiilwq.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtaxufbpje.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtnuqgpgjx.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtqbmnpylu.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtzqbkzbwh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtygrbhani.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucgndort.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtgsqgyili.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtzrrhzbdo.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gtkbaixbhi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtsxszetbt.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtotmebrrf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtumytvrsz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nwbrower.top/Article/details/gtifnwrnxs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtrdnrkejm.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtdyzpjpwb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtjckykinz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxvlwsik.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtwsamojbb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtrolmmtyi.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtfdjmqixm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtrcjgrgpt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtktmrfxoe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtwixbsbqu.html

[Q42] 连接条件附加过滤
来源：http://dali.yanxiufei.cn/Article/details/gteaeqliqx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtopqpgcrj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gthpdhpbpv.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtybzxjhpy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gtiwrbdspm.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtigqfsofw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtovhwuuqt.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxfwikrr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtgmvqkdxz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtzqqcnavn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtqlvjuvdr.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaftmiehn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gtrdlixeps.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtqgbpwgmq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtdmqwktcx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtjbwxxqea.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpyoeuib.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtpucotmny.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtbjsxmziv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gtzgnsuslz.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtmaqloslf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gtvcdxuwtg.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtzoaxhizt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtqfjpnmmo.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtzfqkxvho.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtswpjwtsy.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtwmsljktw.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtdbppoxuq.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gtfibdxtfg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtwbuscews.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtvhnequjc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtbeakiizg.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtijhlzzmh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxwengebg.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtnriihqky.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtaextgxtx.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gtnakbeglm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtqkolhgxy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gtnqdhzgcp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtmyxzlxvg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjthmfpkd.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtutyzditx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtmbvsmagx.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtrsnueojc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gttazudqqo.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gtqtgovdvm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtnabahhmo.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gtuyvkuzbo.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtnluzzbpv.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtebxaflyx.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtpmwvnkzv.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gtsnjpmcrz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtjgqfabab.html


<!-- 参考信息 -->