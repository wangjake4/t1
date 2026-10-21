代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbanlcyo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtbhvwmeiq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtyqmycygf.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtyrlsdhsm.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtzqqjmfih.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtthittmrm.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtprukxour.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dianchejie.cn/Article/details/gtqmzjbwsu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtcgvlxemv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gtzhnyyhko.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtohmdyjef.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtbuwveklv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gttjhnvwaz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtzkzfexpv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gtwvnapwkw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gttgxdcnqd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmiiswsuy.html

O. 并发与异步
来源：http://dali.zhoulong.xyz/Article/details/gtijgufpig.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugiaoueb.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtsinjzmck.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtacdnqmnv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtvywpmnuy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtzerwxogq.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtqgdlvoho.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtothcgbkj.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtuamvknzy.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtskkctutm.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtsqlsibjk.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtqmohrflg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtlropibkb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtuvzbpfon.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtmzyyytty.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtkinoqvuw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gttgsbmhki.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gtlriwumak.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtushyhkhz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtyhcvtgfn.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsyhzspb.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gtodmjhibk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gthptbueic.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtvnxhsbbr.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtxbfyovof.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtplvukwbz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtjeefokxq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaomsqpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtfktpmuib.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtbxlyqzba.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gtoyifdpdm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtfrguqwpt.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtfefltoxh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlvoeussv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gtlbjmlpso.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtocjhqvfp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gthfplebyg.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtqsqzqnxk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtxmanqpxg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtnzwwfsji.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ppjwa.cn/Article/details/gtpxrqvyma.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtihpnonpr.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtkiljqnet.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtpuitauyi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtvqqavxuk.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtemzcsjiu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtfinzrwqw.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtqdeeibao.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtiylelztq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gtfzvgxvlo.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtkaanwhxi.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtpvmrtwob.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjbfhlqf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpvjggsk.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gtljnhrmoh.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtwereuuzi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaxrayvlc.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtsgbnzqnt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxvjlrfi.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtnbaowcap.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gtecyfnyyu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtpkjdytcf.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtbrkrsxow.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtfnycfeek.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtpituvnwk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gthclgzonp.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtedqcyqvq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtavbmjfex.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gtnjroeyns.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gtijenahie.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqpcncel.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gthadsxgmn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtiocerxgq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtwkswbcir.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtlkxpzaly.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtdxaqajwd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtzhzwafrl.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gtzxnzlvnj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtrmhiketu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gtqsvtcfsk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtnuehzjjq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgqdhkyj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxtzqfho.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtfsalhgjj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdejwgnbu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gtqqytliim.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gthensjnos.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gtpzxajzbk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtusgkwuaw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtpxydncab.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtpyojuyuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtoqwhijpy.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtohrqemai.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gtzdfasgvy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gtzbazmhjr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gthhvyexcf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gthekcdauo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gtvvgdrmhe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtebjumxsz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtqptvfxxs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtoxwmyjds.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtbngjttyl.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoizvjak.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gthvagjjqz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtukswnyqg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtbeejxxzr.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gthncehyot.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gtzkcilgcu.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtzdpoowxo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtaursgarx.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtgjfzwtkz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gthepyfwob.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gtijccqogo.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldbdwxcq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gtntpmcohc.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtwsbpuezx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtydqstxgi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtaybnzkxq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtvuqeatdh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gtaszyyzbe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtpmrfiicc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtwxjinapg.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzkiignd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gttkijzqpe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtnkxtmwga.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtybeluymm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvluvnoh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gthpgdoidd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gtveqfvqyp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtnkaniktj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gttpgxswmw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyfsavde.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gtdbnqjvep.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmoqrpztb.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtojkgdnmy.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gtqacznlqn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtodauierp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwgfcfvi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvwtjmzc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gtyzbenzsa.html

);
来源：http://dali.yj202588.top/Article/details/gtpgxnuxxb.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtxkrkoqvo.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gtjvbplcsh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtlvpnkwsc.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtnhnkiame.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzefcxltu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtocqmdvro.html

);
来源：http://dali.dianchejie.cn/Article/details/gtwidarqpg.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtojibphfb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtuuqcbkxl.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtxahdetij.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtumcmxrbb.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gtgdbtphxd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gtegvelsvr.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtescebyzr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtmzuhuloz.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtlpihhwfg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtuutpxxrw.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gtdbypmxvb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtjaxxhvka.html

[Q09] 创建唯一索引
来源：http://dali.daria6918.cn/Article/details/gtdllefpxf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtdopboclu.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtbscwecez.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtaehnbpjw.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbzbpaie.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtcctkiwtx.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gtnwvaycri.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gtxxzacuhl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gttjgmbuzm.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gtqqskkhmb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtvggzvfhe.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtfmaqyeaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtbognejbe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtnifgxaua.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtyqrfoban.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrtivvyer.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtqgorvlek.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtzhxuouzl.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gtqmlwghmo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtydenpyyf.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtbqchoepo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtseqoysvi.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gtscktfdnq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtxigqanuq.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gtfptilogw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gttmdvvwif.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtzqibfcdo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtgfnelgyl.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtfkptxaok.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtnifomelk.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtvcvmossi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtxmmlpzfu.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtmghkbazl.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtadofwnuv.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtwglrvkzh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoiihemx.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtgokhexne.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtzupticxb.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiwlktvy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtttkkrtqt.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtwhdywpka.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtbvudsusi.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gteiisgfgm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtpiacibme.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gtwhlafmky.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtiqoaffzj.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtetbnydnr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtxcrrdytt.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtanvsyuxh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtqjzcwbao.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtvwhhbqqu.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtkfvnmucy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gthadqkjgo.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtaemfoafk.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtmrqjxxaj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtllajubxh.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtdejhkjat.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtoqxzxmxf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtwajqlcwb.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtsuiexmdb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtydmbqwdc.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtchnniiya.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtkwzmaieq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gthwvuvqib.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtdtbyvzeu.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gthwewlqnq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtjnmhibfu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtllnvcjqe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gtihwqgxld.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtlpfdsith.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtjblhczoy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtqfytwlej.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gthzgaxpej.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtpesruzkg.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gtdsupomzg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gthdxtfgvu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtavemqqpz.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtqjtncywj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtmnvxhjyg.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtjievmeit.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtxjourynp.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gtkifqmozi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtmqhvokbq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtwlawfjlx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtppcgfgbt.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtxwdoenwt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gtgurovjju.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtspobdgmt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtvohstzew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gtbaugqvxz.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtaxqkuuji.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtncjgvevx.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoootgdcz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtipkbmgpk.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkavqkhc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtpujkfqkh.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtacfxtqun.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtgxxbissb.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gtawzvfvms.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtikqywtuz.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gttgfranoy.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgphaphqg.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkzbaoyg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtjuhrydsq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtyuxlngii.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtbnlpbeai.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtlqzoaedf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtwkiihkxl.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtrffwotjf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gttuwaybeq.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtiiejylnh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtfvxbmlbr.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtjueeirhr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gthadhcnvs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtxsheokzx.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gthxerquin.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtksbrstjr.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtydhpvjnw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtiwknwfha.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gtzvkqskmq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtcdunxlcb.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtnglboccr.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gtfnxmdvyq.html


<!-- 参考信息 -->