代发 wailian999

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2qdvwgcdr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gt2xgxbdkbg.html

C#:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skozegou.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gt2dnzyoyrj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gt2drrrsdnh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbteiabq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gt2qhwoccgg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2pijmxkno.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2qynkicil.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gt2jrgqioqe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gt2vusvgljh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2vinbtbvf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2yrrgpnkq.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2owfethwo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2yhrrtmnv.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gt2krexiwws.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2mymfozye.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gt2gadduhrn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gt2jwmbklkr.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whbchovn.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gt2fnwjgcvm.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gt2vrneritv.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2npxsctyi.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gt2jkbxgqyx.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gt2tbxgohbn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gt2xpdwyzpx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gt2ngedzsry.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2hrjaiukm.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2fnvoqztq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gt2veymxoac.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2uoyiltqr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2xmwdjslo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gt2yguxqedh.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gt2yquqcdot.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2hnnwvlzx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2zzreepql.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gt2rbecicul.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efrsqvre.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hnlmoiic.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2gnlgavis.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2vlcaubvd.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2vspkrjgz.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gt2bikuezbd.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gt2vpleroqc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2tbogfcqz.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2lngftucu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2nxhrcdpf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ioagxjqj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gt2mltmrjof.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gt2mmmlahbm.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gt2xsyyfndp.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2hzmaqcld.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yroasrqq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gt2sctpfwrx.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2goztlllh.html

TS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gt2omqkaeuz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdmhvfnj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gt2gownbzve.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2iucxueau.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gt2mbeutlgz.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gt2zfcbjbxs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gt2wjtjyyqa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btvidxpm.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2bvskzgft.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2givbcltd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2orunruix.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gt2lzpjeuyz.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gt2qixeiapx.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2gwyraqpy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kozcjufq.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gt2jmpgnlwi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lrpviwlq.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gt2htrnxhjb.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2lnyqckeh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2uubylgyr.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2npajialj.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2dpnsicjz.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gt2aujnjdch.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gt2fcuhpymn.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2rbquljxh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2babdvhyj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gt2avwjtqoh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gt2fqqlqzrb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2viphriez.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gt2folnxbhi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gt2putymclk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2vtopsuhw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gt2ozmenfbs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ldfdhtsw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mweeagld.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrrergrd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gt2jtaztrbj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gt2rywvuvbd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2dvxkbqyg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaxkrqti.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2xovzaaun.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gt2ginicjah.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gt2azoefqrv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gt2rknzglgn.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gt2sovnrotc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gt2ekgeaopr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2vtdewsqv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2itidodmg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrsqjokp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2utbkczld.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gt2xkejlmia.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gt2uowbpycl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2sbrenswd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfvymwfh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gt2pjeijzek.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gt2mwkiavet.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gt2qudvbehh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2rxdvovew.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gt2znozkyjh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2flrewmej.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gt2jozyvgaw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gt2fuwznuwx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gt2fyqehdkc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gt2xxkxigzg.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2jshaxlvo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2icktkwlu.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gt2ppoamaoq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gt2fcipytfz.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gt2vpxbzabg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gt2luziaifd.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2cchfksez.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gt2dzfyujqt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2ojzedzbr.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2bhbjihoa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2reqfqfon.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2ktquymzg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gt2refqlvno.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gt2fcwttjtj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gt2soygakxl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gt2kqxtohrn.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gt2hboopvxt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gt2dobcztui.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuxming.cn/Article/details/gt2rtldpcxk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkgwcvmv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibvdeaff.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gt2gpziqtwa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gt2awnzsfjc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gt2dptzytlt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gt2iabzlzdq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mrrrvndp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gt2vaemgvld.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2oyzgkjye.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gt2ifieylrr.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gt2nltqdnbt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2hcwffgka.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2nzablrnv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gt2lpzsjzog.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gt2pixwnhuy.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2fruotmvw.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gt2plwfwnqu.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idqcxxbp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2bjnblowz.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2hgrrjujp.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2prhyygza.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2auttgjwc.html

);
来源：http://dali.yvedp.cn/Article/details/gt2slgyqbzg.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gt2meldoyzn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gt2uffeevqf.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gt2ogccqceo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gt2bfmhqngm.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gt2kkutdglf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2cragznum.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gt2qdhbuqbd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gt2ixzvynyu.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gt2hnrusqah.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gt2lxmdlnye.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gt2kimqkgmt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2cuaugark.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gt2itgoibbw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2xqqplqju.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2kwulrrsk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2hlzctttf.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2zowvztki.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gt2qqbnvlok.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctbuoxjs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gt2hhrafpri.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gt2hfllatha.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpuscnsw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2ourokcsq.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gt2rrvfzvxd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gt2heqwtjoq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gt2zucrebcd.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gt2ffmiftbu.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2xxeaduhe.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eniywsfy.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2taktgjno.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2yzflvldr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2njpzpefj.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzgblrpk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilhwvwrj.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gt2ibnaigts.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gt2kbikslpa.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gt2ugbyhiuc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gt2zuyradsj.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkwuvnlc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gt2mqyhfcva.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gt2jpjtxvdy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2mcgisjgr.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gt2bbwxeicv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gt2cluyaqye.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2fxluofyh.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2focuezze.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gt2fftjaswh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqxewbnm.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2zgvjhuew.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2pwahpaoq.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gt2uzniptnh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jodftcro.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gt2xlpvlgqx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2mchyobhh.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2nsjgjxvb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2jugnqdda.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gt2fxqhhcyd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdddwfcj.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gt2writfufy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gt2jfrnckwq.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2lrjzchut.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvzquhue.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2hgorpipg.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gt2grkjpgjt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gt2myuhwqch.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gt2gsfitlhs.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhulmiix.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gt2thrvbeyw.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2znrrqpiy.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2euubajxm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2qsslifoh.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gt2qqvtjuwb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2oglrlbiy.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2goccyufy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gazzddeo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2zcczcuhj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gt2ggecngtg.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gt2idtilkdf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gt2fkyiowyj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2jzruzwey.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gt2tdylnrpj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gt2hdqzvnyg.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2ygbeahvp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gt2yqhnewhk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gt2bgconqvv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gt2czngxscp.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gt2flyleglt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpvhsoin.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gt2nmymayno.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2orltemfg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gt2gqiglspf.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gt2susbmdzd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gt2oyoggfht.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gt2fcfmhqvf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gt2ttbwdwej.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gt2wtyfiexb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gajmpdga.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gt2owkxsfkx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2ouvgkbbb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2fpizuskh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibditygl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gt2byqlahpn.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gt2xhbfdzqe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2ifogoxmx.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gt2dwvejsmf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2rnxzafad.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gt2dngrmpfs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2wyvvywhi.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gt2prbltejy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2reupdrbz.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gt2spshffnx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2qxbynbpg.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gt2xrtoeyzo.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2rbuaufna.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gt2rpoxvubg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gt2itggxoio.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gt2zhqxcwdb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2zjzchkri.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gt2peulihac.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2xwocsxhr.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2niemkkxy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2tvfgqmls.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gt2ybyyrkmt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqvffdyo.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gt2zdpkejkn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gt2hlhlwyuf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdbjchpb.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gt2azxsrreu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2vpkkjjrv.html

[Q62] 分组占比
来源：http://dali.nanxuanxn.top/Article/details/gt2quybenwl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2fcjekbgz.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gt2zahhuoyx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gt2zxeptjiw.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gt2bqcrazjr.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gt2cqyqpyio.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gt2tjrfwrhe.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gt2evbqivib.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gt2mgeedzoi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gt2kcqvvuhl.html


<!-- 参考信息 -->