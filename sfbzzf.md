代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gteqiqykhw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkhtuwict.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtjqfzntzo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtzsxixcvm.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtdmhsxszc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtjhiyqcsm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gthupbqgad.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtpqmsiahv.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gttsciixto.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtyeacvzxa.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtltwsmbog.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtgwypxodx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtqpxvgfpy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtffjeeybw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtozojuycu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtergggttr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtkvxlswxx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtcdthbwsr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtnyzepaag.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtpuzmckbn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlxdmdgfn.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasfrsdog.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlltmpicn.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtzdoumyje.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtbstrjbfl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gthbizvihn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gtgzcsojfx.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtpmvufiyb.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtqbjdyhwk.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtecgrgjyu.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtmneimkin.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtyphqnnwl.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtthuvqsvc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtujwbaksz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtjrdcxxzy.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtamkymhjp.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtszvehpcr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtinumlbik.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksgucrco.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrzuwyxw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gtnkowyudb.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtllrvtxwm.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gtpekjfewl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gtboehnous.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gthdfurrwg.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gteberjyiu.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtyggvmzyy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtiyavcpkz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtljqaozrx.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxuwwovc.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtctsrtpzw.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtbldikfyd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtixsobmpc.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtvrvxnjei.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtalxrhiit.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtjattfeuj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtgalabyzh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gtwmwuhcua.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtikarcoyw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtnjciadoj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gtjyrzfaio.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtyitxwuso.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtodnregcn.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtfrgvlanl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sufxvd.cn/Article/details/gtorfqqwwt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtsbijxnzc.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtknxnszzm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtifcjoabl.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtxwmsktfp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtaimvyhms.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gtmnnnwhqx.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtkqwvwltm.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gttjasggyo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtkfwzsdmw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftbiepep.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtwrzuaqne.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtddnmpnfh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkrwnvcwy.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gtruucvzsm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbkrhwvsj.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtcbkadpzp.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gthmebqcfa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gteyvrpbht.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtzxirpyhn.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gttevsjksr.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcscbqgrb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtqsrqcuva.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmgfnzuy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtfjagaovv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtoztoynzt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtxwrdgyxu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtjsdjkvnc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtrxtwloxv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtdeohtiqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfqigmyp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtcchkgsng.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtlafkobbw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtevapmiyb.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtkwnwhlwk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtykfgxjih.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtwlcsqjak.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtjmkszdbq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtqrudkjap.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gthpknliza.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gtdjxrllra.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtgluwxhhq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtljqvrttb.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gtjftuzcwu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtvycaufqy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtrvdufjec.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtoazemacp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtwjbfovsh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gthjhebued.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtyezjhhtm.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtqnjgdurq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtnpevhjdv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtzrossmjm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtfsborbxe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtwqbgllwg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtgfoxjbso.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtvctuedph.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtvupjakbi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtkbicpwzp.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gtksowrglq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gtbmzfpbjz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtsbjvwagg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtmrtdqsax.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtzygwxymq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtxhczrmcl.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqwtqevzj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gttozsxlrw.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtukgqvtgt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtypprpxff.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtubutrlhl.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtxsbhmjyi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtnhsoukbj.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgufenzy.top/Article/details/gtapuoqxkp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtysowveak.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtvhhaqkei.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gtumfuwjqq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gtrnggyexz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtwtvtjhnz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtusmlethm.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gtalmefcgg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtdlegannu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtjlykenlu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenjidiqi.icu/Article/details/gtquomyfba.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtmqptlblx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtvdpgfsla.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtqqdkiqwg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gtdvyncevj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zycfv.cn/Article/details/gtpyrokkjs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzbimicje.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtfiwhivii.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtehinyhgs.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtylrfvwpx.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gtgjqzodcu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtdclegknc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtqavlrxom.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gtrnzvetyu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtcxbhoaqi.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtrngdyjgt.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gthopcfxbt.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtylezwlqg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtgebwgjzd.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtvualdqpu.html

amount DECIMAL(10, 2),
来源：http://dali.cheryme.top/Article/details/gtwrrnsylo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtbfrhrpvr.html

);
来源：http://dali.zhixingplan.top/Article/details/gtemlzvtgr.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzatibqfb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyudxdda.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gthegkpejj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtenenrfop.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtviqsrtkx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtelkuivtn.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtkxxdcyoc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtjnigzrtc.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtnlhcuqlp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtdnqpzwjg.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtvobeptct.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtbvzclhuo.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtxerqulbb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gteaariqcl.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gtkhmzzqze.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxmlocxh.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtnzvextgu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtcyitrixr.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtnifdjoto.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtgalwuyqh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gtxsnoirho.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtzayrhcda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtpmrxzvuw.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtoszhgvfi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtzmofdpqo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gthgtkahie.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtazhcihzz.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtxlkplfnu.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtxckldqiv.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtwgzesyyg.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtxhmchanj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gtkatnnugu.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtqlcjuzvs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtylznucaz.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtrlbgxkii.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtjylgghof.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtlxwinkba.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtbafdpvwt.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gteklcdthw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gttqtqlbdl.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gtcklffpig.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtramzhzmm.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtermdhemf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtqyedipgj.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtislwstxa.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthkcamyjr.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtpdpwkxlc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gtadatsigr.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtiftweemo.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gteiozcvlu.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtvbqjyjfy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtweheggzj.html

[Q28] 求和与平均
来源：http://dali.haohaochexian.top/Article/details/gtlpxzqozb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtuxytgdyt.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtzepekels.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtbkzadypp.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtibdwfsec.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtcjeiptmy.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtuoanethp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtqoqanwtp.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtjzlbcolo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtjlzaqsij.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtpwclzdbj.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtkofonash.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gtomtwywqc.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtxtvtgios.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gtztjzwjys.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtzgofkbfe.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtmngewkgt.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtobfeuneq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtnpkudguo.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtxibmsxuh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtpkeshaal.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtzccrunrx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtljeddwqr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtvzidfwjk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtuvnyuylo.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtegnnmtkt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtwdedmtpc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtkcfzotij.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtknhhscfv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gttgnylesp.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtnqhscria.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gthpbjmadq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtqjqorwsw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtslrkolfp.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gtrjprefqe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtpkuwqiso.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtudbrifgt.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtistlgjey.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtunogroic.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtdorkrwgz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtjntalqoz.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtsainhxrm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtdbvjayhp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwzzrecf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtidakffne.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtxwayvcol.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtnyettujy.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtixnnegdv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtbcdvipxh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gtsxbredvq.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtsvtfsnmd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtxmhmkywe.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtotgtgfcn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtjdiwynwx.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtwpikhdsy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtkeuuwcnf.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtiivsmlgw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtdyjxvvox.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gterwhexgc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtwltvikut.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtcijvrwoq.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gttpqeafgr.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtmuhvfgmj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtmqpsqeqq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtrgzzzzxe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtfuinawup.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtimyzkbhz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtmoqajqeg.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtiplmjite.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtskdeuaxu.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtayvsavls.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtqszynfuu.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gteslnlghx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gthjmxhyxi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtluqzlnve.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gthjkyqtuz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtrzabbbfo.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtkvmwdtgg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtekamdsfv.html


<!-- 参考信息 -->