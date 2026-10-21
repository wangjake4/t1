代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtwzjcxoiq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgivxdnt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtibqdwilm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtcytlzxja.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcbxzhrbm.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnmrekip.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtzrivuing.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gthlltdujp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtuqheppcv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtzerbusfu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtpzzlvhso.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtaewxdpll.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gtjjtylscb.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gtvnlzngdn.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtmwrsaows.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtmmqznfae.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtugsiewpd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtdqgxmfbr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtfoiuclfj.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtcunbfwob.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gttyhhadqc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gtutycogod.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtjzniggnr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtvsotjntf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtqejvhflt.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtdhvteyea.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtllvgoyud.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtmyegouqr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtnrjssycz.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gthevlqswi.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtjtoclwcs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gtvatnqhji.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtxbgbjcpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtvidfugzs.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtwfbyxtiv.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtyfdwbril.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gtvrzxerkv.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtaffvhwqs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtlazziwot.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gtttutszjw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gttybbcjaq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtmfwpcodp.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypscqczg.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtibjstfbw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtvfbmhoev.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gtdwhjlntc.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajbgdsaj.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtufhxtwou.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtpgdgunaf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtlofpkdkw.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpzdrums.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhbicihc.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtumaegtgi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gtuezuogfb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtorpwjwlb.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtoldmuply.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefrivsjb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtaqmqsvyt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtcwnuooha.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtvkraszgr.html

C#:   Parallel.For
来源：http://dali.yuanzhike.top/Article/details/gtggpdqnta.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxmrtrvpl.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gtanpwowtw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbsajqtme.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtbhczzsvv.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gthhdfmmjx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gtdtnxqmoe.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtjtujqmxg.html

TS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtmvvthysl.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtvpgnsruf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtmevioyga.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtlaoscsqv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtgvqnzupp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfunnmmn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfawqhqsy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtppfhllwf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtmmkylary.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gtfhafbsyg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtugubnyiz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtkvbwzimx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gtntfzkbop.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gtmpwwkkit.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtatmrwaha.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtcfzdkbkm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gtnmivywlv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtukoinpeo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtggkxzrwb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gtfiejxawq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtoyiljtwj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtqcarosfa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtluivlgxw.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtsgmfjjkc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtvopgqlvn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtfuduntrm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtodwhnfxt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtfmdcpqxg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtpnpkukig.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gtxypwssnx.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtnxdweigg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtgszdbdyp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtwyegnnks.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtxyhgfpvk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtwewqssbi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtkrafphui.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtwemrquol.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtlseyxohe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtsyvjgoyb.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gtxreawymp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtequaxngh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtxgivdpeu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtlmixbzum.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtgpbpkphb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtmkegsdws.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gttjdnaafz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtrauzfyom.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gttjqaafzv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gtnibluxyc.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtsbifkhzh.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gttdubhshw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtzrkqmsyd.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtdzzlargg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtkdnqcovv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtfgbmkcsl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtodhrluka.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtjjqxdqrp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gtxqjgpfob.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtadtqguos.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtyofhlzll.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gtrwexncxw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtnbndiiwo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtkbbmuadm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtbuhivkxh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gtpxznwshg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtytycnxza.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gtjpvfuozd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtzlnjcrvj.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfmnnupr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtdreafvek.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqimkllcn.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtbptehnrs.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtpsclcgbo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtvyffueht.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtwenuyukl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtesvfnslz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtyagxegrt.html

);
来源：http://dali.zdqjudy.top/Article/details/gtdgtbhsjr.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtbjsxkdcp.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gtwsxgezbo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtlsuxajdu.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gteeauveck.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtsedadsiq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfewnbnx.html

);
来源：http://dali.dashuyun.cn/Article/details/gtoootevdg.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gtkrowedyi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtydnkkznz.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtiiyhetdt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtgtbaloxk.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gtwnxqqygq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtiodozixx.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtfjfoofze.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtlgybujfh.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtmxozfrpx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtholafavv.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtqvxdusmg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkdidgnp.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gtyqrkfafy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtevtebnyw.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gttnxflscq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtodtfidnt.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtegvvjoki.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtiussupxq.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gtxhqgwoff.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtplmnwlgt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gtmircwpin.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtdicfflza.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gthcfitotb.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gtuivlgtkv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtkzlojjtn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtzcnzphws.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtxyiqmypa.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqkcfjebg.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gteqoxymmy.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gttsqpsxjb.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtcjudwfhj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtmmgwafpp.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gttonqcjaw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtnvuxipqz.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gtvlawzjzu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ppjwa.cn/Article/details/gtrppcckca.html

[Q20] IN 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptovunsq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtxpkfgdxh.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtxwlfnoxj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtqzyeghjz.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtrnmkaztr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtsmrvxomy.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmfpazau.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtzktfwoeh.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtkfmuaybg.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtvhwfmbsk.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gttnhwmuzh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtggrrsbqw.html

[Q26] 计数
来源：http://dali.daria6918.cn/Article/details/gtnklshwel.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtsznyhwea.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtadreuhjg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcourkzkx.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtrnidgbhb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gttsqexbkx.html

[Q29] 最大最小值
来源：http://dali.wangdashe.top/Article/details/gtcummyixq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdevrwbns.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gtenilofnz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gthiglbusw.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtlggynjwr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtdibrgwcx.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtdurnzesa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtcpyqjgct.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gticyeqnja.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtmcijnivr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtqhbxxtwr.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydnyrqul.html

SELECT * FROM (
来源：http://dali.jqgufenzy.top/Article/details/gtvpvewiqt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtwnoivwhu.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gtkfrtjzsl.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gthbxhugro.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtvqslqsbu.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtnpgxhlgy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtjapapzvm.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gttqlpvlwt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmfwelrw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gthvshjacv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtwcptdcrc.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtsnodgrra.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtfyobeugy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gtpjdeyoai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gtdtbzvjbs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtqgqcxtse.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtaoblwbdq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtejmsgwyg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtfrfingls.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtneucfpss.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtvoppyqmz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtyvvegjyu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtapvraktd.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtlunvnxla.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtpurohisl.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtovmneqlv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gtxnptsuku.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gtbgmkcswr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtoydrfskm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtaklkjscs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtjkemztkx.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtseqqtoog.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtygsmovyw.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtcswysjif.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtdinjirgg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtotbpivai.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtsiaicuan.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtzpthfcbe.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtprbqivmn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtoforqjof.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtplhnrjtu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gthjayponj.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtnaysercy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtclnjvwdq.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtilbbvjgj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtirgqmasi.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtyzfrooid.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gticcmeync.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gtbcimxost.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtrdjnhcwp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gtbofiquev.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtaoxheukl.html

[Q57] 行号
来源：http://dali.nanxinkj.top/Article/details/gtyldkvhkr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkdebtjnu.html

[Q58] 累计求和
来源：http://dali.cucudq.cn/Article/details/gtqfgtydoa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtlncdgdkw.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gtpxfdcsqr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gttxxshrdf.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gtmkvsuugz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtafehlgji.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtaaqfqkyp.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtzjsqxmwx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gteimhnijv.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtegkjqspg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtnryvogxz.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtmoekutns.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtrshpvjce.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtrmubqtwr.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtxisnrqvi.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtkmnmbqxw.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtnutgcsml.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gtyufkjddb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtzcunkkxr.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gtnsnqiiww.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gttdtfkwyl.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtjjklnhfx.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gteklpwcqs.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtfzdqnzqa.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gtvmzyouph.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtnntmysbm.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gtykjgalvq.html


<!-- 参考信息 -->