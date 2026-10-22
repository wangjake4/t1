代发 wailian999

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxwukibob.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gtnihzuahs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczhvxhwn.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtxwtjwezc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtdvrgdnos.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtcgpmydvn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtuirzhyob.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtieawkveu.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtvrglrfbz.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtgwwyzbgb.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtglpxttby.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtqrncnlsc.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtnymvtxgc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtmfkgmblp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtthcuhyng.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtmisdlikh.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtrmrwjttk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkwashcv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtnstcyyta.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gtfecoouhz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtekgjwnqr.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtikwxpiem.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtbqsqkqdu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtykoigzwq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtmzczhrdt.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtwkntfabc.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtfcjdscbm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhiwuduotai.top/Article/details/gtsipwqowu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtjirqrnuu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtogrmjpea.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtmngcdlyv.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gttxemkksl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gtaygutrit.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtdexjdpor.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtrrodujim.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtmqynzivq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gtniulcmui.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtukehhvny.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtflgyotrf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtknzmaeyq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtilkfpoux.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gtpxwchrmn.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtcpjkuomh.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtavrynyms.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtpmltwpvl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtasaraobq.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gtuckdyice.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtnyvols.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtjeceashb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtksbsnxwt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcgjxbbh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtzclnapqo.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gthgyqeknu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtcftphvzo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtnfafqhyf.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxydgllf.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtecfbkyqr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtoqxmlyvq.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtjvqxfbuy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtilibwsee.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtyctfdied.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gtfrmpqtqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtvoalicma.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtrtzfqobo.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtnpzvkhgy.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtvkywshen.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtfcpcrums.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtmowyqzpr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtcarniehv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gtgcffuqaw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtxbsjilum.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtnfjpubts.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gthgtrhmaa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtglpvxxeg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtbxmczyxc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtewazdnkz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtangnhfqa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yvedp.cn/Article/details/gtzsniqgeg.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtthncpdgc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtkhzffweg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gttogvcgmo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtjrymixpu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjougqgi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gtixntwikp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtzrlvefsv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gttyrmdqtm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtzerpvxvt.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtnvhdxleu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtkwgkwnbv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtqgiurphw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtwsnazjfr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtebnokcpe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtkegrrtcj.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtnfevkoah.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtuwxxdyry.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gtbplpphjp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtfculspgn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtjthcubea.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxojucbtv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gtlajocvra.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtojtgqbfe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtkiouecrn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtojcqfhzw.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtyfysqcuz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gttutpyply.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtmuomeayi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtbjsyqzap.html

PHP:  if (empty($x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtdsoycnyf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtkxdzjmct.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtqtxpysrn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtltxtivpc.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtyrcdikbz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtjbxfoeod.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gtpwjbpwho.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gttzficyol.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtanimualg.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtwvmbeemy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtmqnsatoa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtsxyqmbzh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtegmxxdrg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtyrmwkqke.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtegldkyis.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtztssshyu.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtzamyzzuw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gtkbcusess.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gtjkdzryzt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtgebmsyun.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymmijmuw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gttgayijei.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gtjtojvdyq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpvitkxs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtqxnbypen.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgelmsjwq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtnpszkdzf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnqlmekia.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtapzeomht.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtqwfmsfyz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gttdnnhwtl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtttczwgmm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gtdocgntoe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtbvisvodk.html

);
来源：http://dali.316326.xyz/Article/details/gtekjxqicu.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gticqnzhvv.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtvvpwrvng.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtgkscjnyl.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtkvtrhzuz.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtccngehbh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtertfdgzk.html

);
来源：http://dali.zhixingplan.top/Article/details/gtwkapubwu.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtfmupciho.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtmehmtuvp.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtonofarhp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtxgjgambl.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtmtuovrcg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtvvjextek.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtincugjwo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtqahrrcvq.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gtydzuwhdj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtddmijiyb.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtslnestjg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtqnnglnps.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwyhndmo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtjzetnisc.html

[Q10] 插入单行
来源：http://dali.haohaochexian.top/Article/details/gtdtyoaeou.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtmpuucovx.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gtvdhrugvs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjdblmyb.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoklkurtr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtcduhbbdz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtqwynquyf.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gtwnexbqcs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtkqatrwow.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtwssuyazi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtrxwbgzls.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gtcinwztxf.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtldoyyuki.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtwtnwogqo.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtelbgibgz.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtsrfsopaa.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtytytzisn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zdqjudy.top/Article/details/gtdmclzsgw.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gtvyyekxhu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtkjsgzvxn.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtsbvekcwe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnifyguyh.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gtspzbvogq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtocbwasoh.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtqyfgwjdu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtygojnzvh.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtksrdyprq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtijowfeug.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrynceql.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtskuxotkz.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtzhdxmdug.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtosqzpxea.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtklrcamsk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtyyzdcejb.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gtjazacrjq.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gthkvtpgew.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtvutzzryv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtljqlgsmp.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtgjpkpdba.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gteogmrntx.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtpimpumtz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtnsrringn.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gttnbvfxot.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtuokglbzj.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtbfycfvre.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtyjpblswd.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtbdiohjsi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtlwkxupfb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtqaaznivl.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtlaurfdzw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtxygvsqdl.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtwbckeunj.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtzxobzgvx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtgylbmthc.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtjpfirpoy.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtyscrokvv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtcklmowpi.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gttvhkrgzd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtmpicowne.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtsrusecip.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtbngwzjzv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtmbctzjnr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtropguzah.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtbklbruxl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtyugnxuos.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtldnwvgcx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtqrefytqi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtyhwxuwfr.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtrkyvubvl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtmcokfmey.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtuslkrlid.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gtygxkxmjo.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtpstrljsi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gtpdbpfoyt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtvsfarsqg.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtsaqmwxfa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gtyxhhxidp.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiklrohq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwybmoltc.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gtwlakrkhy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtjygvzroc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvmchrvp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtfusxzdlt.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gtibnwmlsa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtptchkwzc.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtgvodogts.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtnesidpnd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtzhgprane.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gtywijzuzk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtfomivpct.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtocavltrl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtovfsstor.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtsdtbwvdg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtivusqtyp.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtwnvmflqz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtaqljndlw.html

[Q53] 按条件删除
来源：http://dali.gotoacloud.top/Article/details/gtlwarlulq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtfzepfjiw.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtywkzoayz.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gthrflvcoy.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gtdyghblcc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrzqxhyn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtskhlnjqj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtpbnqweoy.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtlwhbdfya.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvkehmhid.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtrqminozf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gthwmpxwjw.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmsbqcpe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtthocfjwr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtysnknmyu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtjcddujxn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtmixzjrbh.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtmdwerinv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtorquhuml.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtvspvkgbb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtgmrwkozt.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gtgxzswqro.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtjpmdzcnj.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtrtekrukm.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gthvjhxiqz.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtsihtgbir.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtgwmalpur.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gtfnicnfww.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gtelgcfcoo.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtkhfbqorl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtnmzsempd.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtydlctndi.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtevifjyed.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtlhsjxjrh.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gtyynhhele.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtvfrnbzis.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtwwxtqduk.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gtducbtkag.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtzmmbulql.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gtyutmjbsi.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtnvbxgsba.html


<!-- 参考信息 -->