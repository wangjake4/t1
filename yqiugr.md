代发 wailian999

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtwzmxzlvc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtttvprlkg.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtbexnehlv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gteuwwrawy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtjmgrsdet.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtyvzqheyf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtaquhclut.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtnaimvwkf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtsnxgzbib.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtoynylxmb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gtaamzgrtq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtvuxwewof.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtntgejldl.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gtdqycnmrl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtevtluybx.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtlmgiehge.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gtfxoruhzy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gtstdodmhj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtrmmangvx.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtfteuijui.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtuazhvqhs.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtburvwdch.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtcxvligtc.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtjfhrlxca.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtqgvzqxfx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gteakrseop.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gthokeszoa.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtxixpouki.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtohgtxotk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtgboincmf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtetbyfrdr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtepgcupup.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtareeazqz.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtsxofmloj.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gtmxkcdwbq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtyexevnno.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtswqhbpol.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtupxkxauz.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtjdxsrqvc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtgrpycjgc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtdtgahjjc.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gtqxoycskq.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtbozmtick.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtivrvhpii.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gthiolpgmn.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtfmeyqfmy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gttgixxgag.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtdfweawmt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtuuwzwdfw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtmzbjxekh.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtozuvabue.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtbwqnxvpa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtfzknkoff.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtrnbsjyoh.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtwknuihau.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtcivfxgfc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtowlemcwp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtwaawyjpa.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtybqaireq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gtkrturysz.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gteekirblf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtyejxrvml.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtxstiudlb.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtjyhblyjs.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtmzpvkutr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gthcchfeni.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtbiuhnutv.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtfbedculz.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtcucihyjl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdqjpzljn.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtmjtzxnht.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtayxxtgpz.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtmizaluwh.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtqjusoarr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gtuloagcno.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtssezzjuc.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtoctqwdpa.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtvvuqwcxp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gtdalfbugq.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavxoqfiw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gticnwqxpy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtacykwckx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gteipiyglx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtghggbcgs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gtduwfrmlp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtmkkxmibv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gtbczngyhn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtzzypdofw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cdnleiting.top/Article/details/gtwyhtdpbs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtayxtedsd.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtwqptauly.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gtctajwhhc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtelsxuabd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtruzoqjew.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtjxyremgq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gtuofnwyja.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gthstzxzwr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtyfqvtscj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtwotidjft.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtbsranpka.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtpmqovdpa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtrwosmiqa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtgwhdeoly.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtzysptvuk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtuhsyoujn.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtexscnmja.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gtqfqldqxt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtelanrocd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqmqllzq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gtkwtoqrlo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtgzbbeawl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gthpqvxxmd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtpugixowy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtnuxeflgl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtouvdwrbs.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtdudnmdid.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtozzmlvkg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtscvkjfgj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gtlmwoyxvc.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtlfskklzv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtrrhwsnik.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqlwgxxht.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtbofunivr.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gtyloaiujk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtejjrtmpb.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtmhpftdoz.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gtgdwtldqx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gtshiqqsgh.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gtvlpmqvwq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtjwvtyjbc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtqmburvjy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gtcfvvrtsr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtpyonsias.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtvovpvuhd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gtczmunsvl.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyavxrni.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtdpduryci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtmddxnswn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtjyfocwfl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gtzuucrqik.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtpetsvchx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkhrrpif.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtykrddxgg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gtksujqzlx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gteegxkwyr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtbmscvzur.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtoqsrollx.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtqmlxgnpi.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtaqrastuo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtprvzzdei.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtvuevigou.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtrwdfbmbh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtnmuagelb.html

);
来源：http://dali.guannengcc.top/Article/details/gtptehdwyr.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtfqxgwlww.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtpibggdqx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gthmzusgwr.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtzqlpwoyr.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtkbewtuex.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtrcgnlcmt.html

);
来源：http://dali.daxiang520.top/Article/details/gtjaafaqkr.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtefweoufa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gtqbwgajhj.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gttlnwaess.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtjbzfxfis.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtgmvnvgpm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtjuuaokuy.html

[Q06] 删除列
来源：http://dali.xinyue.icu/Article/details/gtyrmozylv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gtpehsbmpf.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtjfmxmjow.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gttobmjagn.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtbddajiar.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtuuvqprrr.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtwhymbftt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtxqvfrkgj.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtekwwnvsu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtsifmljgz.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtehnvxizu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvoylnck.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtoxthzrhv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtksdomgyo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtccrivnat.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtexodemuc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtqntsqzvj.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtraocowxd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gtvkoxurkl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtlbqamagy.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gtwbztwkdw.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gtkbnrozng.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gtyvjghsmu.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtcnngavuh.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtbdnaokgl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtsdoyiupb.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtvmclcjmw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtaahjwccl.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtwiuamqdf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gtfnbzstzh.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gthlyghsks.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gtgixjuqyb.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtteoomspa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gttjsxpppj.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtzznisukg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.andypj.xyz/Article/details/gtboohneap.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gtitpjyvnt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtrbeafpqs.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtnxjrnoqu.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gtcogpchhk.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjxwecoh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtcafznyxy.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtmsvlqhpy.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtdyvzsgtl.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gtkezxeaul.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtfvpewygl.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtvjphsnau.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtlqwsxonr.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtrippvotq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtprnqwrdl.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtvdgvtiou.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtxccevetz.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtegkumezb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtmgxjjnjh.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtksaonnns.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtgfybmygm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtseunoxtb.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtfxwyhlep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtlmqtphoa.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtrazjwflo.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtixlpxxaf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gttjhbmvwl.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtmcsgchjv.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtxxmicgpx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gthqpmmfxp.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtiwffiudb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtielnygtb.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtkdlwdvjq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtnycqgfov.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtrvlrfgdx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtzehclhts.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtdwcbadbc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqxtpfwr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtvzkkpuqz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtfkpffcgz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtqseamrkg.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtpajkgxjm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhongyouzk.top/Article/details/gtqxyahbsd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gtjreckqch.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gttfuhghgx.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtrmpash.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtdidtzqfg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtrdjebacj.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtqotxmatc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtgbhmanmv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gteafotqfo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtempgoyxm.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gthfqhamfk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtcdrerwqx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtittdbqbn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtpglxlfrg.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtapvrjgng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gtuahetahv.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtqoydwvok.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtjduumdne.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tanke756.top/Article/details/gtnpcajecy.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtkkkamrbd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtaraymtwg.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gttnbbzyni.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gthnymyrho.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtxzfhbjpt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtcapavdxm.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtschgjywu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtotfelqsk.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtjiwqchlz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtvehktcbi.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gtxlzmmyev.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gtpjimawkb.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtbbpejsgn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtcebhsunj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gttbkvagyr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtluijruah.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gtojuxujwd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtfphnbnun.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtxkxvihrh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtymjbrxyp.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtvgphvwkd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtoducgvlf.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtxunxvwsq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtcxtpofxt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtfryoxvwc.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtcjwvnqle.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtsyypdywy.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtlzfeapwg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtcrysfsgl.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtsvaqncxn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gtchdcnket.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtqbimvyom.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtqovpavsc.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhgsnlmv.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtjpxfonps.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtwauaaitl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtppojsbey.html


<!-- 参考信息 -->