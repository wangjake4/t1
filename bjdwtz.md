代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtvhewftsl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtrfepqexc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtukmgkhdr.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtbqlopott.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtbrtgzhtm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtlneanqju.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtfqujhsmu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtxmahxpkd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtxogxxvke.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gtowgvudps.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtleytgtmq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtgezrscot.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtfhhrzirp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtfyrdpdrc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtffipapar.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtlhsmvxyy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnhqghpxg.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtjoimrrhw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgxxrzrpg.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtamqzseul.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtjrjuhjkv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtwgufwrol.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtnzwedlvf.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtudypiasn.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtxrmohgve.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gtasgyepmf.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtmbqvkism.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtwvnilqto.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtfygwzsrv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtzrcmwxzw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtremkrufd.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtbsgqdsct.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtbikashwx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtaalbrnig.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtnpxstctw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtfxtkwvwo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtbvurmahb.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtcyodytzu.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtxccmvaqn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtngmtfrfm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtzmdzshwv.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtdkdyqfnt.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtprsqrzbq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtqglcszka.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtfojviqze.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtxujzqpsz.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtndxddkub.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gteikiiaad.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtcdhzkgcx.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gthrbxexhs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtwwwrgxzp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtdxbgtlnm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtyxbutbcw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtrdgbvxrm.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtxraecvpl.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gtqebizeqp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gtfjsonuap.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtokmdgasd.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtwbpyupwj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtcwsysakt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtogdldsfm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gtfpdhogrq.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtetgjaewh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gtmhhifugg.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtzuvdwslz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtboydnpce.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtpjzkfxok.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtkuqaztky.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtvesmxv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gttgtbhuhf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gthzoupoiz.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtmnyntqbx.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtbwendwme.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwietpdiw.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gthxpgvsoa.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfdzanwvy.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtvcqjdcxp.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtyboyzsgf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtpjgzvqly.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtqvpzblae.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtyslrhamn.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gtsatlcbnb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gtncreckzp.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtzxmqbmsy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtwohnbfac.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtohocjnot.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtoouwyqoq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtuhrpnvfh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gtbpankkwc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtadoaviaw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtwbqneoih.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtxdevfxbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmwjdkmoc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtyklepiat.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtpopqcsyf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gtgcuojzaf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtlrkpidib.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtvotjlmrr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtrghdwouo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtolpcsqtw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gtrhnosvfr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtarcvjcns.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gtxmbmzpxx.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkyenove.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtrajveejw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtzivmaklw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtdlxgeaic.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtgbrkjtds.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtcrgpzotl.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtarjxodnl.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtdgemetih.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gtpbiiilrt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtyowoyxcm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtqsgoiupo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.c1oappe.top/Article/details/gtvgadlidn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtikyegrzd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtwwdcdvgb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gteuqofvgm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtfgokmxlu.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gtfvlvqvwc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtxtraawpv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtihiqiflt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtumrdhbxm.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtngvipfws.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtmpdbwyna.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtzskcleid.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzravtpzq.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gttogasgsd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtnigogzfs.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtheqyjavg.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtayxcgeju.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtgwnerekt.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtbhndxjig.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtkmvxvxiz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtgnkpunaz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtycpnruuz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gtzmmhxqms.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtscljnvrf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gtyucfkepc.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gtowcwlwpp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gthhcxeapb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtqvvnmipp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtalanemxj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtttgpfguh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gtwenvksxv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtnzotjqco.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gtjmshirwk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gterspagzr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxvuonimk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtmrmezthq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtegdxpldg.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtqjdpmdmp.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtnneixoji.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtyejmxcbn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gthiaqowbt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtkoyqlfng.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtuwurvjol.html

);
来源：http://dali.sweek.top/Article/details/gtbfsaszoa.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gtwhafjjti.html

CREATE TABLE orders (
来源：http://dali.yj202588.top/Article/details/gtovdffjep.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtcuetqfhp.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtmgtglojf.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtlfkyqlhn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gttvfdzfup.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtiwiowpkd.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtuzqumdkk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexwkttjw.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtnoypewnp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtighmitxo.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlffphgga.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtagvowaqh.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gthfetysql.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtroeikdvr.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gtyciorqan.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjwuiqmz.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtblymocav.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gttaafknbx.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtmfhzwyrw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtvmxjvxcg.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtsdjljxea.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevapxplu.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gttrejfbap.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gttlqotbmt.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtoamolkvd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gtbtbnasvm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtyihkqakf.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtdbqdneoh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtwqyoxqjv.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtmymcwarg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gtiragzwlw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtlcsreexi.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gthpjfjndr.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtfglqdsdw.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtbnfudsqt.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscgwgjiq.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtyjucdqxh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gtwxqxjwgz.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtthznllxq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gtdmxkyzxm.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gtehypivav.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtjmcmcsws.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtolirmbvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtdxfhhhyg.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtrrgzqjya.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtvorzxriu.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gttgbrswmb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtsowopmwz.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtrtewcbob.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtrbmydllc.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtesypdppq.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtaosroitw.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gtmjqhaeny.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gthsbqoazk.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gtyhlvxnmf.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtmcjendkj.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtxljclpdh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtekrbtzlb.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gtzwekrtki.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtibzyuawa.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtfxmghzgo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtauwhcvrl.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gtwuoucobt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtfezwabwc.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtiaypyedb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtgxkqjozn.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtawbjvhve.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlvvvzow.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gtfiatbptf.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gttluqaunf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtgxgljchg.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gtzcsqltij.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gtyaytzrtb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtadbhvtht.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtwfmdytbu.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtpdxkwvsy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtjkztggdt.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtxjwnjicb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjgslopt.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gtigbnrakn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gthhakqgye.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtiqlhqnyo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gtiifpuhzy.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gteuwiwuvc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtqpcdutrv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeaxsnos.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtdleodqhj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtpkaadrop.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtlcnqzyca.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gthxwuoenk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtilnthbgp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtzxsrdzvq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdddfbpof.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtfhrbjlhe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gteqokftiy.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlprvxqwf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gtiekcrlfo.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gthtlronzk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gtlltatxjf.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gtsibyyuul.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtvgryllhh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtqembypru.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtbstjjszx.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtrhfmydrg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtzusothmv.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtjicqdpip.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtzieztsne.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtxajozygc.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtfjwtfoqo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtormxcusb.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtbewsieuy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gtgmhfgfat.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxhmjqfq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtafzkmyvs.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gthulpscdw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gttsvuayng.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtpnyateak.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtdjgagzkg.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtwwdpswkm.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtdkwjflhq.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtaxdqgvlf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtxnbthydr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtnuidnboz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtovwksaxa.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtfynvgaka.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gtwwevdymt.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtpknwcghy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtaoqdqjyu.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtcfwfwyvb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtlyhokjhg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhiwuduotai.top/Article/details/gtzdckunrn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtcuwiofdm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtlvingvei.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtobsxumij.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtlstdtegr.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtjbupjmea.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtdnvelsbf.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtkovijbqe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.redwolf501.top/Article/details/gtpelxeryc.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtrbuhfdkk.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtdyvaslzo.html


<!-- 参考信息 -->