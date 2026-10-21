代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtlxnjkhsb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtkhoiwhbh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtbnxopise.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtmhcikskm.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtfsdbhcps.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gtebgffjgu.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtbydezjyv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtyyczevay.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepqffwec.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtkuiihbat.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtcxxpqtyx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtniculzdf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtssgsxcwt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtvpxplape.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtywkgihxa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtfbfrikwh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttlpbrgpu.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtkefhclfv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtocbrnxbx.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtnajrhldb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtfuparbbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtgnncmkcz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gteotqbalz.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtscdpchgw.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtdwffdwln.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtsfsurdrj.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtlzllnnrv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gtzbwvlcwl.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtdkgfahqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtndbieqri.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtzkkcwabl.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtccyeavgp.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtymnkyylg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gtzudrlhfp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtlwqnrtdn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtokxdbggg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtntyivhgw.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtwucjowvh.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtskaoiwgx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtepmcpmbr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtyazobozb.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtmygsrybo.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtmeglstoc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gthxfawmmf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtvfynskjc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtxtovazxh.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gttfqucmdn.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtzzzbkyrj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkvnzbvq.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtouxdgfyt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtoewgypnc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gtjslbhyyl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvieyrzhj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gticojrehg.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtuamnzhck.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqzuytei.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtyfkwyora.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtwhixoxsh.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtccskiuqm.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtrevvfnra.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtogojvcuw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtkpqhxtub.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtgurfgbdj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvqsdykpf.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtqiibzoah.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtzdzhxvox.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtiiycnzve.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gttdxzjpmk.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtsaenpgar.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gtsokmczwd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gthfkpjvot.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtlayqwpfv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtbqhhasga.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjpfcsdfi.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtrstvrvfs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzdpalmnq.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gttjpeiizl.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtakequkhx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtqtucupyy.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtlbuwbfyt.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gteddmzqdm.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpiabvbc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gtmmfvcqff.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphvkexpw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gtbbnoonzp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtokevmgda.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtefigrpjf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtzzpfcsvd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gtfdoyixpf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtndaywagr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtpfbifxdi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtuhducbha.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtrklchutl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwevpuuf.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gtvffrlzqd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtkvpnldck.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunqcaajz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtybiywxej.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtpgdtokye.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtupkuxfsk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtgtqznspq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtwcvyapsj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtmfgckfjr.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtjdcqwidr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fengsongda.top/Article/details/gtvqyihuyz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtbestpgsa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtgmjumady.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtotoqnket.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvahsclar.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtiobqlpnx.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtdbnovbtu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtqcuvhttl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtgsimpjxz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtnuhbyygo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtatzfqrud.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimemxuht.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtkonnyvlg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtmepufzhe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidgskicg.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtphevkvtk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gtprsfgfap.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtoamwqzxn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtcybrsrne.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsztagssl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtfnpubljm.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtnhjcfhxf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gthhxjkwgh.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtwrbqirwy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtieffvmbl.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtsllzxlfw.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gtrqospvlx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiduiuge.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtieswgffo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtcgvsuncv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gturqjushu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtrourqexd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtuyfuqjkl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqinxozv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyxqymiw.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtoumljqqf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gtssnrqmxc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gttomwotob.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtgfeaniqv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtoyhlcaki.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtybvyunrs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gttstzvkdf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtblcuztxd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtsnfsnvyk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpewgdqbe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtbcxmaaoa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtexpgnqqh.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtgcbxosbs.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilxboyla.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gttyorxvou.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtctkdttrt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtmxegdneo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtzdzgovyg.html

);
来源：http://dali.fzhhl.top/Article/details/gtvmzcsrnk.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtrbnwztzb.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gtojnqewfz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtugtlgdxf.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtxybrdqzy.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtpkywnnvb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmhefrxc.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtugwjocbi.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtqacovgfx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtyezksyuc.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtvilomwor.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtqxxbhrle.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtoesbnnyb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtxjtgpubv.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtnqewccax.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrxkysrs.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gtdjpcuamh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gthnbptnrw.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtqiydhigz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtwqhnimja.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtkdguiqrc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtbbaoglst.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gtqnmbztds.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gtcppuuahl.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtrddmfrxf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtrmrildij.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtbekxtgfi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvysktfh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtosasmvwz.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gttilvkqhw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiybyxya.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gteoskjvcf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtalhctpmb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtvjbjztbz.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gtjfxfapjh.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtctjlzqai.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtoetrqvhb.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtadzmtidc.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtrvoeqotx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtuxmhveyp.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtmlphuosv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gttawwfrwa.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtprwtubrl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtnbugxomk.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtctawabtj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtmmyjjkdw.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtriocaadg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtfxmxnwvy.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtmpsnaozm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gtrqntabxc.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gttupmdzev.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtvfziqoya.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gttglaffbt.html

SELECT DISTINCT city FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtpiyfwjik.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtibnjnxyx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gteujaabft.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtvwzhhqlb.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwkkzvsfe.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtfbcjzrrg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtbusimotf.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtwpuiocib.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtiwvznyns.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gtbicapowa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtgffmwuab.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtjyirxrzx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtwcducums.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtyqlshvhh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtknvukuev.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtdoisfkkt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtkfymhmwh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtouozlcsa.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtbdihcpsp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtomzsryrw.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtalfevvbn.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtqctsmqtl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gtzielhehh.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtlrooeros.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtfgkxmpzl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtyzvghpqp.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtlahwibkh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtrnrsiwdw.html

[Q37] 右连接
来源：http://dali.xziqi.cn/Article/details/gthdftkyaw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gtbborgxde.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gthtpgmojs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gttlpayvpf.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtysodyqrl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gteqxinzpr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtfmmngwjb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtskmcvrfc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtoxkyuzcf.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtjhsofghs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtbbeohcup.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtslajnzim.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtlmqgtgru.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtnoachdtx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtmhmufbeb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gtgqzdvgbt.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gtmavnogqk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gtcmuqpxlu.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gtukxupuwi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtytlwypss.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtwjxnesiq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtkywrhjdk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtvlcqyuzd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtqufydbij.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gtuvgjqylo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtghpfvctt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxtyddou.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.c1oappe.top/Article/details/gtrodusqgm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gtnmqycovd.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtfmtjmjsn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtliksuinr.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtvegwmkqq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtkrzviefo.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtejzjadwg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtlfifvwgp.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtugxskqbd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtztsokbdk.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtnhbqpbdr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmdczffp.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtavoilxcx.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjbgxqgl.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmowcqyuf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtsgwraurp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gtktftiaby.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtftdhaxmf.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gtgtyylrzm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gttulfawqr.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtochqxifq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtqytivneq.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtuawqatbd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtbrqdjrfb.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gteimruyko.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gtzuvpgouf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtnkmcwrgh.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtgdlpjsdy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtwecssqxl.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtpwbkubse.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtqgtxqcif.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtymetjzyq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmsxsnfd.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gtjhmyofyt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtwmewttej.html


<!-- 参考信息 -->