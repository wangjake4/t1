代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtxlgidpbh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtwglmphkf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtzzdolqcn.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtpmewkedd.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtqdqnthhp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gthkntcfbv.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtbhsoatsh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtbfargrfk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gtcotcbmps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtbiharxtt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtdoofonoo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtkipqwvfe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtlpkyurkp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtlsqbvivi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtsdatldrm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtgxocteuy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtujppzmmx.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gtawckkpia.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtxozoemsj.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gtjcgbbgea.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gthzplodxd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtrpwveycy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtqywjyzmu.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtvwuxklns.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gtuijwpuvu.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtkvomhvlj.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gticwgrfaq.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gtbtxxalqy.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtyyckbndu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtxuxcwwnw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtjwniigyo.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtvhkmdpco.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtjrhmhqiv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtplzkjywf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtkoounidg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gtysmdteas.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtghcbxfqe.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtrygxjyky.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gtppsufrkv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtobmyakkq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtloaytjee.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtwbaecmyv.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtwlokkvhl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtbjzumvdr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.redwolf501.top/Article/details/gtdpxlapli.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtyfuvnttk.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gtojfinxhl.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtivckneuf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtlzhctouf.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtpisyaxqp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtklyvcihv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gtqyyvikqz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtidtgzzxy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtwbjbasjh.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gtxirdondv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtlfywzhxl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gtekqtgpit.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtkmkplutw.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtbqmpxnll.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtkvrxsyqn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtxwvbadyh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtoirhgchq.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtsgoqsmam.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtubdmbwge.html

[O06] 使用进程池
来源：http://dali.jianghu66.top/Article/details/gtggcmncaz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gtshlzkaki.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvzbiotx.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtgxqisozu.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtpibdoplm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gteplliemm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gttbhvpibl.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gthxdcismw.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gtcgmzhtsh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtldzwhuxb.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtqnrvbquc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtaswdwsoi.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtowngexov.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtzkkzjsvt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtvoqfhcvn.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtoyqwzobf.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtsmhcmqeb.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtlduocyev.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtzwdovhqc.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gttzecrlhy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtoxdzvuta.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtwjmagvqw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtzyitwvlf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gthqnwgrdz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtemzrlayo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutgxocwh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtikucvwev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtjcythwle.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtsxqjfhrx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtalondcei.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gtssuircgy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtyuyyfpnq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gtejzlhkja.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtubmnuqmi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtyphkavao.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtuoqeiozq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtwigaxviu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtvvpdlzps.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gtdsebbwif.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtkvjnjxmb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtjhybdtdm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtexzsiyaa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtaykheyiw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtrkadtttp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgiumsyk.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gttissofgm.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtdbpovwxg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtxwadxgls.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtpnaoicbl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gtdpfvkzdj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gtvnmxvtmv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gtrdqvpvbj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtrwylekjt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gtffwjewlg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtpqllvkvt.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtsdmfzqbg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gtbogmtgid.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gtvyqqfpdy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtfsyojurv.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtaakkyggg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtysnjkvba.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtdcaubwmv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtiuznyzzz.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnonooiiq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtndkfjyuq.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gtppgnicrh.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtlmmdmdvf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtjcmwxfxx.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gtzcqcjgjh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtutprtjhp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtsaynxbao.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtuczexzil.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtamvuepyt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gtxrfnkuqu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gtqogtvjif.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gtltvuijfk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gtlenunsrc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gthvjoeioz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtjgqyxuqd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtxxpgntgl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtqvokpkdu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gtmdtzxyxf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtsfnzxedq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtqvtsgzfx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlzazdfpo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gtiagnvrby.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqvessscr.html

[Q01] 创建表
来源：http://dali.zhengqikj.top/Article/details/gthcvquctr.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtobsegxoi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtmkhwqmpw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtdcgxumsz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gtupcezhfm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtkmsbdrfp.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gttyyhmuoe.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtfxlwprzi.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtgykbzndg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtpvztpegg.html

user_id INT NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gttfyrufdf.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtonqokati.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpiweqmt.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtaqatosjp.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtjyinqitl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtgmyjpiwk.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtmvgfovty.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtufxomzng.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gtfyjkvwos.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtlofcoech.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtirhqquaw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtuokovjoe.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gtuflvflmz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtpzxtesfo.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtpuxoeuno.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtqgvjcpde.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtmjirwlef.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtzyooupqf.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtzmcyfpfo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtnehdbgvw.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtroajzpks.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtfngxgwhs.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtkvzqgbsd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtvpicxcyq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtnvejmlyy.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtdgjlymmm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtnbpksnpl.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtuczojbhp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtfmvvidyc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtmvdjtfcp.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gtgxobgegr.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtzfdhyrim.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtesjlfjyn.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtvbjvwajt.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtsopbhgyh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtbsfpuesy.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtxwxsrqxn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtrqffobmf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gtuioblfis.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtwehuxpgf.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtkbbihmth.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtvicbyzqc.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtqbnwbncd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtzmjkozfp.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtppvjedji.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtdujfxpbm.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gtrmhgwlwi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gttszfobru.html

[Q24] 去重
来源：http://dali.snrcjt.cn/Article/details/gtpvqbhbet.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtfcoeuzui.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtdphhrfco.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gtuhvtpyry.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtzfvzyrfx.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtjicpoocu.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtyihwmswq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtrgvlkrcs.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gttsztblmz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gteeaitmdc.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtmmghigge.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzhqkoudz.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtyaffleea.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtqlysqsdo.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtubymzoib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtpgphspgv.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtqrsmnpky.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtmausevsw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gttshavwum.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtpdqjvdgq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtazprizcv.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtfrdbpjjf.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gthihlbeon.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtqazukabn.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gtwvchebvh.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtptjefsmz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtihwxuyxn.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gttdavnghr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtrmfazyfg.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzhkspyj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gtynccwsds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtibuaqysd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtekgoiccz.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtzbfbkihi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtvxfgpjpl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtnngloidn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtoaglymin.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtpbagtore.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtjlvgffgz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gtmtrmoihx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtnnjotufw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtetdfcopf.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtwzxfkzpz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtomcgyozx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiekdcxv.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gteellvxhf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gthyfquvrk.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gtttozetbu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtxjazwzaq.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtzzkcumzu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtockkjdzh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtywytjrck.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtepdrhikx.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gtlrshaykc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtmzpshgwi.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtcpepejoa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtoshgqiux.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtbrgxhdmg.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtndioexsz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtbvbnqnfx.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gttobgtizk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gtoeaezhwk.html

[Q51] 用子查询更新
来源：http://dali.sysykeji.top/Article/details/gtpxrhgqll.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gtjpapfjpw.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtjkijhrqf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gthrriujvl.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gthhozyfvj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtbtdzjcpy.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtlsyposud.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtvxplhhja.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtqxhmbnkj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gtmvxrzshe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtxcqmbjoc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtbqtaojfi.html

[Q57] 行号
来源：http://dali.hysaishi.cn/Article/details/gtykugsucs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdwahunyj.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtnaogwliw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtroypymln.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtlinmxrze.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtvsosddfv.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtthjntoni.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtdkwhespn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gttnuixguw.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gthmlehkms.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtlenejtxi.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtcduckuls.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtxtblcmpk.html

[Q63] 开启事务
来源：http://dali.zhiwuduotai.top/Article/details/gtzsfwczsj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtmeibzava.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gtrjhyqufw.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtpxaxodrs.html


<!-- 参考信息 -->