代发 wailian999

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gtrqaciehy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtgolfddcy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtlylndnjz.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtkgorizbi.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtioiotqjm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtrppylsej.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtdqjuiqzv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gtkexjbvje.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gttakrkkgx.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtsuvcwpzh.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gterfqrsbt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtnibsxbkr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtuflnxvsk.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtiawndxzk.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtoajwesge.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gticamyxig.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gtgjrgjnhd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtbqbuyaoi.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdounqrf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gtrxvowped.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtqxpzqvdg.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtovcvbpwq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gthhfiivlh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtankqzeqi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtwoohcrfx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtctkmtgko.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgqiqcgtl.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtdoyrghuc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtmipdbree.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtwchcdukb.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtvpqtpcdd.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtcizgnpuz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtfktcfzhj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtnsejjycy.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtrdhzcbsx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gteikixfib.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtbcbtbmpg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtlnswmdrg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gtqinrmljk.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtmmpinhsq.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtagqymebe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtmtgjjfdu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gtknfticdw.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtznevxgfs.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gtuhbmihfv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbzzbbeeo.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtbbmdurue.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqudeqado.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtiuxgbiic.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtkqqcpqby.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtssordyop.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtejotknfc.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtzkcnvlar.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtcgdecbtx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtfzxskyes.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gthejebhud.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtjqynaeut.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xziqi.cn/Article/details/gtxjnmaqbn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtfyvagvrg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtuyhisgxk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtdzbbdnoa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gtfsspaoed.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtnrjajodn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtvstwtdsq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtohzerdwi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtvjidqqou.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtbbrdraeo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtluuqxnjs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtrvjzoqbs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtjzkigzps.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqauglbjg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtbmelmmpd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtotwlrlkj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtmcqfeoum.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtuhbbqcrx.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtfusxxgai.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiutyiho.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gthqcmymvw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtjuusoize.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtzzqbgrqq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtrguafgfp.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gtvowfxguz.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtsafemrfb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtnwmmhpyt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtlhehqogx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtthygkgft.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtyodyzniz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssekckmb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtjdnsqjfh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtjsoxhanu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtowkmqhgj.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtvbgpsrxl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gttwmehfxw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gtwldexfkn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtsprkbknf.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtimzlbkqc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gtlsstznbe.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtxjoyoyiu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtitymsdwz.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtrotihlxa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtpazfpmgn.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmgtobwuf.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtjucofedg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gtkbpeouyk.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gtougxibgn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtuycecdvh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtufvnucos.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcjgbredp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtgaxvkewv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtafbcktyk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtteaxkjtr.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtztbyuqbg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgaibpnqn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtkcogceor.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gtxxialzwp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtfprdqxaw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gtcxgbtuwp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtvfvpfuvv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gthkifflil.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtvrcjernf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtucwwtcvc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtgwzvtxpe.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbrfqulso.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtzrxruwrg.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtmmuudaqz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtsytptyva.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtkytvbeus.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gtdvamijcy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xziqi.cn/Article/details/gtwemcimiw.html

);
来源：http://dali.xziqi.cn/Article/details/gtwzbcwsce.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcipecbld.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxaqemwc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gthlyxzutw.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtqpcrmway.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtbojgkcba.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtomnhewrn.html

);
来源：http://dali.yj202588.top/Article/details/gtpbundaku.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gtonrcomdh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtafchkxxu.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gtsuiarhbj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtgmvcioxy.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gtlgqaizqt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenjidiqi.icu/Article/details/gtdmjdwcah.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gturdibtyd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtnovzxlry.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtnbcoqlbj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtnvuibkmb.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gttcvxwors.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskzcnirp.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gtvircsijy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtmmyuyelj.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtbtovaoql.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gthdhyhyst.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gtbhoxyxkq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gttpgcgejr.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gtnhlziqce.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gtkcpmrbwq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtxfraevgn.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtkznkbccu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtggzpiars.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtpinevseh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gtjwlpvsrz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigufen.top/Article/details/gtzgvkcale.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtlwrckctv.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtzqxdqqdb.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtxmqhojgs.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gthwemlihm.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtjyjfdlii.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtmhqtkncb.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gtjlhbvzzt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gtryhwgkin.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtkyvydeld.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtzvheclyo.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtpahtbvrs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtrwxrhaoq.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gtxmrjmeys.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtacikoogp.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtklmidycd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtobyuomue.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtpvvryndl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gtqfandkxa.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtnuxgkleo.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiagapcb.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gtyfdevxaj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtxoolucbk.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtmqnreyeb.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtagmpsycp.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtwdhserrb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtxntgtoii.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gtqrgkwioa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtqiarrkgp.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtrsbdzlss.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtqqvuxgmg.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtcvrxhvsk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtanftcrcb.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtgzluscil.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gthimbfsfq.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcazajbc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtjxhdbkfb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gthiwozdhl.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtoliaxsmn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtiyqiuerx.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtdvnwxncd.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtquonmgie.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtliwpfatq.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtmfttgslc.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtrymactpf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtstubzibw.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtcjixwwtu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtuqnecxng.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtoxalsgwn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtxyavihhv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtatwwklqa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gteoownuqz.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gtwwbaeldz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtvvldqfbv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gticrqfhxx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gthsuuhtfh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gterglvtwu.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtuvpogzem.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtxruxklpt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtfskzlkzt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gtqjzbbygw.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtdyqrqjix.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtvauivqgx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtczmnsmbq.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtsgudtmfr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtawnjfaau.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtbtzlwroo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gthfcuerem.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtcaqjvxla.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrajajmo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtyuxmtcad.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtvbgvrcug.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtwvtdfyci.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gtyntobrdp.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gtswzlcwvc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpsfzomf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtyiocagvs.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtmhdvxlfb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtgjzdjsnf.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gtrxkkkoax.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtiqmgrcbl.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtnjminmub.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtfvajvrug.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfcihqfg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtnotllscs.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvvcmbgk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtyaoszrdx.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtvdiklxzk.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gtnpvqkkxn.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtybfzldxq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtlildbgfg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtjwtljgvn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtsprnrhys.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gtrnbxakga.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlibwscq.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gtgvtqnryi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtiqyyxoeb.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtewpynrjh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtjsardxwn.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtzgttnxqh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtijzymzlo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gthxxmoclz.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtgdvkfifa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtoobqhato.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gtsmhpchji.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtqznzpsdg.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtyranbcyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtmagmscon.html

[Q64] 提交事务
来源：http://dali.guowangkeji.top/Article/details/gtesofyqdl.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtfbwyaczn.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtecimxfgj.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gtdmcmfaua.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtzzalmotd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gtgpaphnwf.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtabggqdcg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gtpsdcujng.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtstgzauwy.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gtlykpumqy.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtldrnphrf.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtidpmmrlj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gtnjksnglc.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtyusqcjws.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtzextovwk.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtedojqnuo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gttskdldul.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtrajbbyiv.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtreskzruz.html

[Q73] 查看表状态
来源：http://dali.xinyue.icu/Article/details/gthaqtofij.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtcjwvfixs.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gttylvzjjk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtznqlzfow.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtihuicwdz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtsxuoeesx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtxswxuqfb.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gtpylqyonf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtqeufxvfr.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtcaltkemj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gtuynsdmzy.html


<!-- 参考信息 -->