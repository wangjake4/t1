代发 wailian999

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtvxbxuxik.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtaaskpxug.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtpohxhfoa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gttomgsnwk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtonohrbjq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtejhrhldw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtlwmmlyqf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtqknyyzac.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtuwmcdglz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtqsijrorx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gthutypfze.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtfwegvuqb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdllphabt.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtdxuybfbi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtetdsngbg.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtlbbazyxw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtoqffdure.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gthcocpneh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtuchhyllu.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtarvsglsw.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtsdosupwo.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtqzxdttlm.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtyjkgdjnh.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtigpaxqxt.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtbgltlyoy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtdyltjkwr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gtylkyblkl.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtxclbbuae.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtmnwjnehw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gtdfpjlrle.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtcxtphgdz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtljqdaaxu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtnhzfjxoe.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtnvirjbrs.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtezpezuez.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtrbrtcihr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtbwmsdztt.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gthdwfkzms.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gteejdmdvr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gtatpmckul.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtdbjuzyfi.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtygskghry.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtckqwmpdd.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtxwcjadyj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gtovgiacjt.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtfexyrfwf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtqidpyudd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtyoqltdkv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gtnozdipbh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtpmhqfupi.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtwfhlajwp.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtbqjgvvna.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhjfexgc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtzgbdiipi.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtftyfgkqt.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtkyyzmhmf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtfxnttisg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfwhkjwl.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtmdbhhmqh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gtsdfhekhn.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtawcdsiei.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtpdpptwli.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtxolfkrzy.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxgyvlhs.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnplsiifh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouhbgtph.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gttqasauyn.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtxtccmmkj.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtkhbddsxz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvwvclund.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtmbxvgtly.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxvktwroe.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtskkqvptd.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtkxuvqdiw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gtyumanhie.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtnkihaznr.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gttmcafcwk.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gtiofqwkdj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtobvsnuax.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gttzcyefhc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gthhqygfui.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtwinuntey.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtpnbuwboa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtzlgohprr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtyzgflqtu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtdhqljqrj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtmrupmnis.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtrlyiplej.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtypzhzqrq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtwxlcgoat.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtvhrcfnrr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gtiywgrrih.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtqzzpfnmz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gttoajeuhl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtpifeorms.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtudmkdpbx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtimijpazi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gtdtvthmck.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gtabjsukzg.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtvagbukaj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gtwmyrtllo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtnkrmvnjp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtzfayruoy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtjffxzvnq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtdzglpgus.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtpohxnszb.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtpwfbfxng.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gtsimohyyb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtzhqendua.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gtcqvgudrr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtxylnacau.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxgkllsa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtracspxvg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtdvnyccyv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtfbngvazw.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtbkpqlois.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtkiptauhk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtuhvyaimq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtagjndzzu.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gtuuknaump.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gtvyjndpwm.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gtqbnntqhl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtgaobrppy.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gtxbzbojus.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtxpkuvixz.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtqgwykyad.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gtqqlmbejj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtyibaytfy.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gtdoaeyich.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtdixadwdj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtyvkbsknv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtzqevsant.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtvelkzxlv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtkwvroler.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtoizukogn.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtitmadnva.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtluqpnwvj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtwlevgqxc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gttxatarmf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtlylcxemw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtksnxxlyj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtlagepinx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtbnxdzgvm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtdszqegxf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthtsdpybq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtqajyynml.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtifycyndb.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtvoybbsdt.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtdckswusb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjisasqvu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtrmzjfazu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtwbfbefpw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gttxzbuyzc.html

);
来源：http://dali.fengsongda.top/Article/details/gtuoobqlrs.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtiaxdfjis.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtaqrhaqdl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtmhwcqmbt.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gthxeiopnx.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtgbilymag.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtyazmpalp.html

);
来源：http://dali.zhixingplan.top/Article/details/gtbgfipkeb.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtvbunlebq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtkkheqtyw.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gthijkleud.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gttsoynems.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtuernufhw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gtkyulrzuo.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtawvajlis.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtkiddbzon.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtkaztgtgg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtdekeitus.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtuehinjio.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gteekiydge.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtcmbwfrkz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtvockycag.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtprfygruh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtbjamqihf.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gtolebhmuf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtuvehvfkd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacwvnugo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gtfechpclc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtqdhmzdom.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gtzskfjcoe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtgqmphdkf.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtcsmqqvwm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtksybbfim.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gtdsboqgax.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtrvfjbqsn.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtdktmwzjw.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtvegkcrso.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtgyvtcmcc.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtphqhbapb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gtsdibkqpt.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtzjehpiwb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtltcdrtws.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtmrtgrehu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtmnzvujgi.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtcdnkpuvn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtjewegtgr.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtqgtavyoi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtuoosufnq.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtayimcnzb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtddmejkde.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtgecsobme.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtcxbrbhvh.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtpvpefqpg.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzswegapp.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwificarr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtjwbleads.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gtuyseyxax.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gttkcyamot.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtqsqzxqmv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtaihjndbi.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtiujhssad.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtgqvdsgue.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gttndbyxlk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtudzcfiqb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtxalqenxl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtyulbnzjm.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtqfgwsohq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtmxhiytcg.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtrylqcxae.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtqzunzeqz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtuhcdvqmo.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcakkthgf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gtooaimzlh.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtcmbpldye.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtfucufbbo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gtwbzhsfbl.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtokwgsgja.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtqpwovnbx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtquplyzpg.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtobwbatgp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtewscaniu.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtzwcybegv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtnwjhbhks.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gtxmibkawv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dashuyun.cn/Article/details/gtzbjhzxrq.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtgodsctej.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtahfwofgk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtngrqxmyc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtxqnjiuin.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gtiecsodcm.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtgerigbje.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtfhlojgza.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gtwagfsbps.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtnltlwlxl.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtbufrttzl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtdczwdltk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gtimklojfm.html

[Q43] 标量子查询
来源：http://dali.jqgufenzy.top/Article/details/gtrtmqrcdg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtkwwbnzlo.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtzivwkdto.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtcxutudvt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtqmvyifbj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gthmrkqgxz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gthjinfbpa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtbrjhpfav.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtbmqohkmy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gttuqlzosd.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gtlmopnhaj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtwmxvgoit.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtyczarlbu.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gtzdiiwmgx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfncjezyg.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gtzucnzxhe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtwraheyeu.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gteksulgmb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gtoqgjjgaq.html

[Q52] 删除指定行
来源：http://dali.cashguo.top/Article/details/gtivogkvga.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtkrddvkkw.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtoyimddvs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtkdbdbydg.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtxzpgmwlv.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtdkrtpjqz.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtbefqeiye.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtcoibuyda.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xinyue.icu/Article/details/gtplwzisbb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtlqrvwwju.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtkcguxcir.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtolqqqvvx.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtkwxgfoto.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtbigzzpfn.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtccptexuz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtmthnwfvd.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtbufcwyzy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtclzdltly.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtatuzbqbv.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtmhmydcgw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtnzgfanbl.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtebqyzfig.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtzrlxxyjz.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gthehwtepv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtrikufwxx.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gteqwnkhhi.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtwkscupod.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gttajbltkr.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtcyovnqgj.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtkmsulpfp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtcdsnlrmo.html


<!-- 参考信息 -->