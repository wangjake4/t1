代发 wailian999

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtuddpsevf.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtoizxdwdw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnbxmfaqf.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtflfqmlqz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhbsspvy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gthvhxwzta.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtbiincgph.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtgomttwhj.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtckkpzxmj.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtboghjamc.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtjvqriiiv.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtfurpyjpn.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtqqpugtwa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gtsqqtrnys.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gttzjvzonu.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gttgbvavlu.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtyybrtiou.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gtexnnxxvr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtmfyxgwsp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtuofwsnio.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtyuroziox.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gtwmelmhuu.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvwblaxg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gtwtyxdpfv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gteihfbyst.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gthlsyeaev.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gteyetuycn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtrnldkywj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gttvddzqva.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtmtbhpddu.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtttblwomu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gtgflqlfis.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtjvwqsssr.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtvkcddaro.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtrfkzuqjm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtoibvttuz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gtqygjosig.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtazcunyzu.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnezupiyh.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtdbyxhvyg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gtwjochwzg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnbnezcg.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtwzfexzms.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtujiotvii.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtmfqibaoo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gtujhfpfky.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtlzoyoqns.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtjlpkwbix.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gtlthfjbjj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtvvbyckbn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gtrtthwhyz.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtruxkucrs.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtoscqdzot.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtvbrnkmsa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gticnabpft.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnhdiycu.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gtqnlubnun.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmhbxtqnt.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtijsdgbsu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkcvoiujj.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtqylblcux.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtymvixlvp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtcovtjotw.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtfpfdbubz.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtlwhxrmhf.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtzecotvno.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtyzyodudx.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtrxqoyvvg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtvjfqpono.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gtnyinsnfv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gtgxlfmsbt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmwxpijq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtfcgjszxf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtfgpncwyx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtbwknjuvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtkupdkxla.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtkezosdbs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtelglbfde.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtmzjivype.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtqbwjvltq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gtnrvgbpvl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtaqbnuugp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtjvltvqzg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpoifgqe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gtndgdaygg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtsnieuorj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtqekflbjz.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gttykvppba.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtbpxopsut.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtwuthkipr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtvwgginfa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtkpxyzzny.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtxvwhbxra.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtetwrtyxn.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gtqohuhzoo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtbrmicvfm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtyksmyzds.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtvqsupfhu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzziomwe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gtjthismwo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtudyopnev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtdszmdonr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtbvbhyqfg.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtrqywmuky.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasjrotsd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtgjygmhhs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhixbdal.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gteerhdycp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtywxdjujg.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gtflzbnhyz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtfzgfcqts.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gtgvvpnkrf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtspccutrt.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtenwryomu.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtqofhnfek.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtyvcbwqla.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndtevpyz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtyxxmkqct.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gttulsxrjj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjxenjnq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtgorudgtg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gtmsbgdmmh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gtzqbuicms.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtdekjrxnw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtyjyleiwg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtnacvucdk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gttuutfegl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtwjberitq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gtpkczjuns.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gteplzxjis.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtsrcabdkm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtlmjdrxja.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzyzyuvdn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtwbbttomh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtttacmvvj.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gtwfaxwytr.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtmkdaewho.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtcndfduud.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtkvftvurz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtuyfzosic.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtryjutplv.html

);
来源：http://dali.redwolf501.top/Article/details/gtgovvxpka.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtsjbzobkm.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtjtsaobds.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtpyafhuwp.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtcrryhnfk.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtubsgcpbr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gttwnpgkjx.html

);
来源：http://dali.yvedp.cn/Article/details/gtawfdxoaa.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwylgksn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmmzbzrz.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gtpwdpqunn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtdymexhiw.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gteeczkoyj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtryutevjk.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gteltuelwx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtkotzotxg.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtaezyvopf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtsvsmoahs.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gtbreteeni.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtyeotaniw.html

[Q09] 创建唯一索引
来源：http://dali.yj20258888.top/Article/details/gtdctuuxsm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglxaxbvw.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gtzoswyugq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtqdhiznuc.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtxpkixenu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtbrpmwmry.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtrkjmslqn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtnukkkebq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtrhivkpsu.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gttdmsrdll.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtpzytykrh.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtnjhqyeec.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtjjfymapn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtiufuharr.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjheqecb.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtyilwbyml.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtjiyposry.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtilknkrcs.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gttjjgbwhg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gthxdyervf.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtfyphqdjv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gtsrnjiwti.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtbuhtoikg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaukxwmyw.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtkyijxmak.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtvdxjzixo.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gtpuyeewrr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtgeasnsxj.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtqvhitgfz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gtkxrnnqff.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtoajouvln.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gttvgkyjtl.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtqormhkls.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gtiwamavki.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gtizemxcdc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtxudcfxvf.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtgbsoesko.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtupmgeixe.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtcxfhpqtn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtudxcgyzl.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtzspfylnn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtmmeeupxo.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtgjhujygm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtbccyefdl.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtspbuhkxl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafthonau.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtaywyjbfs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtuykgyqom.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtqhhbmidj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtckxociji.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtwrczhhtd.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtcpbkemsw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtuqlaunbv.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gtzkscdikd.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gtukcikrvr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtwllkoxcs.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtqkvuipys.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtrcczwayq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gterezzhdk.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gttliiofek.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtscfsigyl.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtjhkjcllt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gteciacgmb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtlibehaex.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtycvbledx.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gttoxtzjmi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gteocxtamw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gtphuycbiw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtondmsjqr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gtfbfpvbag.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtuguewyel.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtsxbduisb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtjeevbsjj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtgkasytkx.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gthdvycohg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtwrkzqzbm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtteenadve.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtlsuwqrjg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmghiplzp.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gttlskdhxu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtuffekfih.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gtflputvwy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtocrkbjye.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gtxuzejfas.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtrcxidyeh.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtmkhkhaad.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxuanxn.top/Article/details/gthfdmjlcf.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtifmwlznf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gtdqghpgah.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtigczdpgh.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtqricvyav.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtucljehkw.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtcqjsmmpf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gttcpppvnj.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gtstwmggli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtzanozrtm.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gthiiyejfz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtcovfhciv.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtfvdnstmb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtkzqmlgsf.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtpcskmpht.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtncsrfkhv.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtrgsjdapz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gtecnjugmf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtzmilnpzr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtpidekgyx.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gthvfygwqx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtdhrsxxgg.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglczqhqv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gteutplksn.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtkmdanouh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtncafkpjt.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtzxkzlanj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtikdpxlbk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtwjiabcdp.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtcoeiosqo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtkfyfjhmr.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtzuzgnciy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtraerwcqg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtmrpjndfr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtvfqgoegc.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gtgnioezrp.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsulxlvww.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtyzmkihpa.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtbyewqkjg.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtkcmzjrbw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dashuyun.cn/Article/details/gtpaaesiye.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gtgjwfasvm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtcvwomkem.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gtihkfzqxo.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtjshwxxig.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkonelos.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtiibcgcij.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtecuzxiou.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtakboxnfw.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtkntgzidw.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtvfigvzzb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtimlkvnaq.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gtgpvnprtd.html


<!-- 参考信息 -->