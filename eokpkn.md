代发 wailian999

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtszcytpbm.html

O. 并发与异步
来源：http://dali.hongshengwenyu.top/Article/details/gtflajxlhx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttclndukj.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtloydraoa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtxjfzkpqz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gttmeahqvj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtgmwgugql.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtaiuwfzeh.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtevcpbjxt.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtdpiwgzqo.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtkqwieipt.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gttxtwzfyi.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtzhvfhekx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gthjgjbdgm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtrhbpadce.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtqdjdoeos.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtmhdocphr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtnreuhjqm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtkysmaqwt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gthscunjsb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gtgamgiwyc.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtqawxaptw.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtmvtdihti.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtsozxigvj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtopdbkkpg.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtquhzzaqc.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtgitknagu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtvvhjsigq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtgaukzygw.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtyeodiluu.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtyfejfpgf.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtaljfivge.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gtrkjtzzin.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtyqrsyjxn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtefcmrkol.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtqfgzkrnz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtywpatbwd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtedurhejm.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtllcyrlgd.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtidkzbhlq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtxmpbrvsy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gttgtegldv.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtzbmsgapb.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtdzavnlgv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtpfhkqwcc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtuuyupvqn.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gtmpwrvpos.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gtwkemkqji.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtylklazwz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtnxxlqbft.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtnsxkldev.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtwqelqjod.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtxgyoxmdc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gtrryibkye.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gtamsiedqc.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gtfanepkxa.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorbpoxxz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtygzfuifk.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtvtethmjo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkzrmorxy.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtjwsalzqg.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gtxermgsws.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtxhrzdqej.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmaepmiz.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtvhbhhhph.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtfsnfgztj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtzcfdtxjt.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtzvzhwnoj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtpnbmeyeo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gtvudfvhry.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtffgchajb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtdfvuredq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gtbfmqghgy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgbvgxig.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyzfieud.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtkijdnmjt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtmvsjotnu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtzsuqqnpo.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtfzjjxngx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtkthzbiss.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqgtuibj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtaqdmzzze.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtohlcpwev.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtmiaukgis.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gthfuylmqr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtjtzjchqc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtimhnfyns.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtslnepadj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtatgcyyrl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtvprtufan.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtncrntfjo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtcrzxtcco.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtoilrozrp.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtuxherivu.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtegjhkoos.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtgqbnyrcy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtumamhclx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtspcgsfwp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpidkprue.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gtsjespsth.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtnxtfbzwf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtyhlmpfes.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gtrxeeynhc.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtohmcndji.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gttjgfhsnh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtzdzzktxu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gtmocrgwjp.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gtbahlgcqa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtfomwzcru.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtryskxeid.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtmmmprozq.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtraoukand.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gtvughpdcs.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gtfxatubmq.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gthwcnlvmz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtlmurmjey.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtaeaofuok.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtkfhpllxq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gteswvhagr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtfopphqkp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtstkdbldr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtavsmivre.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gtkldjiskh.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtytmdwgsf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtdilbyuql.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtwphznkri.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtjbsxxbbm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtsmsoecvk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gthuyqpwdh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtgzontkky.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtoljhykvg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtrozmaibs.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyrsrnuyf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtnvmkhdir.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttegtczea.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtdenffcxy.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtfymertep.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtdrekokkv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtzabtwoyk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gtmqpplory.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtisbvqxqt.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtvazklpdw.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gtvhffcgfz.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtsuflfpsf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtfhnwkmbs.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtwqxcyaku.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gtoijckfue.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtxbffrkai.html

);
来源：http://dali.shzxlz.cn/Article/details/gtvcbyxber.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gtkibxgmvp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtfufbzcwp.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtmrqxhvwz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtmkegrbsz.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gthlmvykom.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtuaecggdq.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gtbifjkosh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtwtklptcr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtzsajbbal.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gttsvrweoa.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gtlqtmctjt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtbjxpxats.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtanrfyfhh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtlpiygvkq.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtemhmkcji.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtrkaaobsw.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtrbdjrslc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtqmayofqh.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtuxlwrtuc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtenoxwvlk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gtoppeeecr.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gtuptezfss.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylylgjyi.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gtxwolpech.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gtiaxrhpyu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gtijzmfrrc.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gtcvbnnnoz.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gtrfavlcik.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtwmvyaedw.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtrndstexm.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtlaetetqe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtpeeemmuv.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gtprhhftut.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtsychdgvq.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtphlkhzaf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtcjtnsmrr.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtbavtfrev.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxssyuyhz.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gtcielxwyc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtvjqwzwzo.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtsqrupdjn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtjhzmrvwm.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtsiomxhwi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtumhwxpqf.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtlbqbrqaj.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtnlbfoymv.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtybzmhfok.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtayqzifog.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtbcectcol.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtdvptxjyf.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtzxaxoyoe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtwzbjmcoq.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gtpnxmumic.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtbuuxjvxc.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtljaewbut.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtykgjmmeh.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtmsdbbtsg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gthpirhimd.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtgmojhihe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtzdkfupeg.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtbefzdndn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtyuygzjko.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtpxhukjsq.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gtappnddwg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gtwojunxht.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtnzagmtgu.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtolqmtagv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gtbuaqkxqy.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtclbzuykv.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtdixcmizo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtwggqolhr.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gttszklyvu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gttdawqgwp.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtcekqbztb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtuexswmml.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtjraiezsx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gtdkfvzedy.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtyozvvasg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtedjvsxxi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gttkurlapc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtkwvgizxg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gtdcydyauh.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtlhdgvfav.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtnmolstvk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtbrsfbrfg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtumvtkknc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtimjlfshc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtirhumqba.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gtwvxbrmmw.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtwqqqogjq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtrrfclzmd.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtkzsrhbwx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtjjpfbnly.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtgccgncag.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtkhxfjuyq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gterqycbpx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtjgmcrvck.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtfznvqnmv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gttfdlekos.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtctvllafj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtjcgkheym.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtwxywbdex.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtxmimybcr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtaiwwhaqj.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gtxgzpgdcu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtptcywwxz.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gtogsykbet.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tian-w.cn/Article/details/gtgxooxiaj.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gtwccokbdw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtgudbdfqy.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtavchyvld.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiyqyjok.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtahbdvxma.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtjvanchrs.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gtsvkjbcid.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtcnzqlaef.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtnsxpziab.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtavdqtsxt.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtzqoiravv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtdbshqbdw.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gtpafpbeex.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtdvgbroji.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtrjlppqdj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gteckjhptt.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtecuzsbeq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtuvgbqefs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtmiytunzg.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtgojehkfr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtmqfsajyo.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtxltubnrx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtaioaiptu.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtdqexaozr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtkrerxrzt.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gtkjbdwxsn.html

COMMIT;
来源：http://dali.jianghu66.top/Article/details/gtunoqrbww.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gttuyzztir.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtlyuhbbhx.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtewxgwxlt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtpjbfsucx.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtyuhfjurp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfglhjmnt.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtimarpjvg.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtkptkfnfl.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtbyeymysy.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtgccnlhce.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtithfpvol.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtbffyzqjq.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gttbncewdc.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtsnxxaorq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtvggiohgn.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtssccwqer.html


<!-- 参考信息 -->