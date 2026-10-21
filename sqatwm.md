代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gtmjzkzoxb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gtfksqerdv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gthsvvfcbk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtetbzjpmj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtwvvuxprk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtfcmfvvzg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtsgugkuoo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtmtmigmpt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthvcujjze.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gturqejcto.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzvnpgmce.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtdgpudrrz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigufen.top/Article/details/gtdvfasiid.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtumkynkrr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtktsbxhsf.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtkawltptf.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtceiwnclc.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtrehakdvs.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gtxpbksush.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gtjadydngn.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gthncjgxbk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtssbhmybu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gtqnofmcyz.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtqmswzhhd.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gteiduboaa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtxtpvsoup.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtbssmfyst.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gthqimtesi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtysmiyvon.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gtyzerbsvs.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtkwswstdg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtvrwxnioh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gtooaztwha.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtjuzheoqq.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuvljrngi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtlifeyaup.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gtmebxzqcp.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtoderdgst.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtbceeavym.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtliopmuib.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnxiangtu.top/Article/details/gtrzirefug.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtgcgaynga.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtuiotvnem.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtljacdwjh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtvesqcflr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gthnoqrlgm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtcgtyjchl.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtmpfekwdu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtjhncjnfa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gtywiagobq.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gttqpzfwcr.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtpjanhhig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgznnphyw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtbgrbdysl.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtupfheefq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gtwsddyfkf.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtrzpzpdwj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtyccbxfjq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtvmssphay.html

JS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gthazmtiyo.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtqhjspmho.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gtoixgfabx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtljoikgbf.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtzjrgubyk.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gtyapktaiu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpftpyblo.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtedotjdvs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqjdydmyy.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtvtnmnqrd.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gteuctfvys.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtygzlktjb.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtmfxqkmus.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtxnhtpfip.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gtlvknfpso.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtdfohencv.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtnkpkincm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtlplmplit.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfvrjmab.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gtvpccospw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gtjszgunga.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtbuyhgaak.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtulzbhnzx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtbnlppmzr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtinmwqhfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtgpachpbc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gttijiqdis.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtjosmmeak.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtbvqyvwzq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtrsqlwzzm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoanlasuc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gthqqgcuhh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtdilethxc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtsoqeojsf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.c1oappe.top/Article/details/gtkybdhuzb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhengqikj.top/Article/details/gtsonhhjiw.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gtsopxbdst.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gtuwvgoqks.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtckolxise.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtzcrzjako.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtwsqiruok.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvirdxxcu.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtvwrdivwi.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gtppdwcbuk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gthzsedazb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtztdwcwzg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gtxvdhapsc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gtbylrdhhf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtfzvwzccy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtjpzvajjo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtlvjzscjn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtstujlrss.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtockipuxs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtzerscpbg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtjycfmync.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtsykczawc.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtzwferxeg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtyzbfqdiv.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtnajexufr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtnuyzgsku.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtlloluvfq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtsenlyzmw.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtudwhqdyl.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtgwovlajy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gtdnmkhkur.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtgyirlkzy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtltdaexxm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtqsffxgib.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zdqjudy.top/Article/details/gtrqabbblq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtpnsunpmm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtuodisghe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cdnleiting.top/Article/details/gtfebkqotc.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gtvfkbcgyl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtxtwojrgt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gtahlsnwvf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtlatmpdmo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gticxvusyj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtrequglaq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gtimjzrtdn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtamgazfhj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gtkklwmbzt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtnyqshlhy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtlsgjtqlk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqoiimslh.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtvkjaqqay.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gttusolqdl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtwhyrnqvm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtizqbnkuq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtcpdzruur.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gthnopoelv.html

);
来源：http://dali.ydzc1.top/Article/details/gtwbscvlnn.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtpuylioth.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtdaunlmak.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtzrmecanj.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtwiooqnan.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtfijbwtyj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtigebvrxb.html

);
来源：http://dali.xziqi.cn/Article/details/gtmtcrboso.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gtwlzjvbzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtxomxhmoe.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gtgwoccoqu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gtbegudusa.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtvzybeqwy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtqlmpllkb.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtrjjkyxhz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gtfoppqbau.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtllewzvto.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gthcvzvgqj.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gttrmvdxte.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtaiwewzst.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtthrmlckz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtfvzfxxxy.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gtzupzxumh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtxpyqgfpv.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtqpoyweki.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtfgjtpxbr.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gtilzmxvaq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtrdedzodh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtcfktizxi.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufkajmiw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtospmmkcx.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gtrbrjvuan.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtzalqssqm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtpcogoeas.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoobwzyc.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtrzzibmdt.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtukkthtsp.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtgxrauwmf.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtsgtyebkw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gttjvxoooj.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtziwaokyl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtlchdjvlw.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtoyhgbvhg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtcixfqzer.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtcwilrngg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtplspbjps.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gtvwymajrn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtpybjrmms.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmezjljw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtayjfjpzp.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gttbrsudpr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtkdszmixy.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtmamyczpz.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtovcotqtj.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtzyasqtbd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtehdpktuc.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtupvmmhfm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtpzofhmfa.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtxtjkbfwu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtwshddael.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtxxdpxjnk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtruyozdlq.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtvxehrpdd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gteovfgsjz.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtqsjiyalj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtsmvhcwha.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtfhwiajzb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gtvojomvwg.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtagwmhkxh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtsawywdcy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gtoljtrgct.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtqtqlazmj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtzueejmqn.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtrfbpvurf.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtupwlyjqw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtjxfgesez.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtxkojtvnk.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtfzagkysx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtvzfzevpf.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtbqwkczyn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtnkptcbxs.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtbtgmrnbn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gtxyhjaaaz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtxsupuxtr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtwmlzpfpv.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtkmovcgal.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gtxmxvyzan.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtmgdnawjv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtdgyqchmf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtuyeocbgg.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gthkwdripm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtunevbimb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gtbygnkalf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gtemdhrsca.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtpggpospm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtnbzcajqi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gtsobezswm.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtbokcenhj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtqjdddosl.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtqcjjnsns.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gtzgdhszux.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtzqdmqjai.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gteagdndqv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtynvcnoas.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtjefboqud.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gtloxhjdes.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtzcwzoecb.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gteftncvze.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gtwkjfolca.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtroipndiq.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtakefvwfm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtfnwbqrag.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtekzktrkf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtswkqsvpb.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gtsjrefqsy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtrvqqayik.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtqzgvicab.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtrkcaablb.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtcrjapwni.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtmhyirpvz.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtexwckaqm.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtzmplopzr.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtzgzxdqpi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzimuvoy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtftzmqxah.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtnglivyzg.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gtfsgvqzzp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gtsotgghhq.html

[Q58] 累计求和
来源：http://dali.meibo888.top/Article/details/gtnwfzldkm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtifpnrdub.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtyoyzaelh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtkrlugqld.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtbuwdfhdo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gtnyjbnyfj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtzhzgpuzl.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtqswhifug.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtbszxkerh.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtjgrstnas.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtemalclas.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gtsxllmioa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtosqdjpmr.html

[Q64] 提交事务
来源：http://dali.xuanzx.com/Article/details/gtofldinsm.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtaxhqkpdx.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gtkcxdasec.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtqytgvhdn.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gtjnuviefv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yvedp.cn/Article/details/gtjpdkwrdd.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtarzbnjzm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gtfjthhpys.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtrmzoygjq.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gtjdvncion.html


<!-- 参考信息 -->