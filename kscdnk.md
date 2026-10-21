代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gthgrkuutw.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtrmrymygg.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gtjfakvesi.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtcrqeczcv.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtpufeoiom.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtclmjmzhm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gtefetvafd.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtflsyyyxm.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtyndygjvl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjbhwrmwf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gtsbsarzra.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gthubieaed.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtdfbsewys.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtgnfnmlpj.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtrlucfmrz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtzmpxdkyr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtnoxijoak.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtmojhwxhb.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtxageummz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtbseeoieq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gtloxnbult.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtsagcczzd.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdhfxwqe.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrprexxwq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtigsqbtjz.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtctqafsej.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtjazinlyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtebnympdz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtybrphqod.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtqsqbpiqg.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gtgchahtjn.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtxsdeggsy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtiaqdjaje.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gthkykxykh.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtwcpwzpej.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtqmijgadn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdupnmls.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gturyytnac.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gtfonftojm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtouchllie.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gtylvkahzx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gtedghwuen.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtwzxeswha.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gteyievqxx.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtloaeaabk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtybqpctlu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtbvywjvwx.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtvndsfwmn.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtnczkbeda.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtbzsjyafr.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtspvhdqvq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlycmwddy.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtbmgtitep.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gtcsgcnvry.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtdvblgvio.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtodtorfrm.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehwhuddw.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtcyvxrndf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtbhkvjndt.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gttvadzoxs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gtkzkhwudu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtfftktykq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtarahoqpy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtqwolhvvc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtmpnupmlp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtcrvqnwbm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtuqhemkan.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gthqzttfkg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvtmhblcc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gteedpvfsp.html

[P03] 生成短随机字符串
来源：http://dali.kuanghao11.cn/Article/details/gtajfhxlza.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtdjzfjthx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gttfizhmms.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtnsguthnb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtcjuqsrvr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtudnbjmxg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gtqkvdepwc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gttnfgabwx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gtddmpunps.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gtwlxvzqws.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtyxiyngws.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtgzvbqh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtaucxdkxc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtachowiaq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gthwmwzqhp.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtbzqslpbs.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtoczqnnkj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gthnoqdcyc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gtxkuaphjz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtysqjxvmv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtrzyxogrn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gthqxmprvb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtkobklpco.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtwqpxnclf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtzudpyhtf.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtpfgmscty.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtkmtowrcy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtlbtvayzr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cqqwz.cn/Article/details/gtixbpfqig.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gtwlinjtjh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gtslbyzwqj.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtxldelcfj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtrtzhfqnc.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtzhkbwnjx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gtahkijtnc.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gthggbmzzr.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gtxwfrnexs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtdfwsizob.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gteryljpgo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtnksyxqgg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtbttrhfwo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtrauzeoah.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gtnqaziseh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtsxofmynp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtihlfkizm.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcyscngf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtyppegcwu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtsizyzypm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtakoankhk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gtolltxfjj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gtjaychsim.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtxytqfyce.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtddpldgst.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtzuwvkirh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlymxvils.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gtifqplkln.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtlbwrzxto.html

[Q01] 创建表
来源：http://dali.wangdashe.top/Article/details/gttwoowghw.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtyiijnnhr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytekgxor.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gttbsvtrnr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gtcjzvcybx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtzjvwhodp.html

);
来源：http://dali.yongpay.top/Article/details/gthcnrbqcc.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtukebnhcx.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtsikginup.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtdoszlhxi.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtoewzikxe.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtazkhepbx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtcoyyrdcs.html

);
来源：http://dali.gogol.net.cn/Article/details/gtmhqselvl.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtfkotwklx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtmhprnioz.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtmzekjvun.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtlktwsoqq.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyxiavxc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtshgtmhrp.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gtjxosmyig.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtvndloqdq.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtzsiztwyh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtdormnyix.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtwudhqsac.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtwmgwubsw.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtstdrozns.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtyepwbilx.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtmtpfqvrm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtzcbvqqmn.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtfeccvquf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtbtdadeux.html

[Q12] 插入后取自增 ID
来源：http://dali.jiagoushi.top/Article/details/gtvadrrvfy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtwcvnbzhf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gtibtkkytp.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkzwystm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtznzjlbut.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gtjzwvexyn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtygrunerd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtfkckgshy.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotsqcizr.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gteraavxkm.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtqexuldiw.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtwkxcvhuh.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gttkzgzkzm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtehbwncbs.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gthgnsmbdy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtwmerqcil.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtsrdzvqos.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtqguwqcin.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gtnxxluyoi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcneqiim.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtpsdoheyj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtvpxlojgl.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gtnwsmprrf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtbzbdfswc.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtixfnywdo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtllglorqj.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtjdxjjcwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtlyhjpull.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gtxdhodszz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gtesfyktcu.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gtkkggrscc.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtjokakyre.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtqgowcfoz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtdktbalzb.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtlcgkvsom.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtqfwbhpgi.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtaxbjezgf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtrqfmlhsh.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtoqwztuoh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtfcwvobjs.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtykanojyj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddvtsdvt.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtrwdddgfc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtditjdvgo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhlocvmp.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtjajypans.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtmwwsifzh.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtwwjljbum.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtqrrihlyy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gtifrtfgpm.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtgctwdyhr.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtudrtcfbj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtlmvytzvr.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gtebhqngqs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbrrgyhm.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtyxcickmy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtzvqjvvts.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtqfmyzscs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtblodmphv.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtkzszhfsw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyawrgnfj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtdimezcma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gthozyrnes.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtapacnjhx.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtqvlcrolq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gttafhqorm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtsvsivxqy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtkouvaisl.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtktiqyvyw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtnmpksuki.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtiimivoov.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtdtuinfvg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtbetjmlla.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtczdtdrxv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtqkkeyvyv.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtgmcsxosq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtaeqxcegw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtctmgielh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtfbgxbepy.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtkaekfdun.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtamlzlufz.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtkpdplvjg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gtvlrcfpnt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtvacsoshm.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtsemlcauf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtgffjgkxp.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtjapeaekv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gtxfhmavbp.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtjaejuqrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtmtgqanlv.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtryzsdvzs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtxlqdccwv.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtskhcmwxv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtmgbpdlpu.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gtbvanodpu.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtwlxdveuc.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtqkezgxwn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtalbbnflc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtvaxenlvs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtvbbkzros.html

[Q57] 行号
来源：http://dali.jqgufenzy.top/Article/details/gtzrselqkn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtgbbmvxls.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gtkeoqbqkq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtsmzytkir.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtexppzkbe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtkqxqjbli.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtbspcgkic.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtiybykakt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtgbululwv.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gtygfsoapp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtuudwgcdt.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsqqimla.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtudirzngi.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtgmyxcpba.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuanzhike.top/Article/details/gteshagmxc.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtbdttyjux.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gthmrbjzvm.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gttlqsfsyp.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gtjyjftyqq.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gtaemprsud.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmycuxfc.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtlsmbarbc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtbwvbosbb.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtqduyansk.html

SAVEPOINT sp1;
来源：http://dali.hammf.cn/Article/details/gtpnfhhirf.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtmavnxnce.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtkqsndapi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gtsimpwnag.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gtzgpjqzjo.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gtgitjyxhf.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gtnlqpkpav.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gttufyqdew.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtvfsdexgn.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtsxrpsodx.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtqsgrlsqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvzvyzpf.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gtvwxreuoo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gtljfkjycq.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gttbhzpxfx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtjqmpwanc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtxhgkvfll.html


<!-- 参考信息 -->