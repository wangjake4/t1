代发 wailian999

================================================================================
来源：http://dali.cheryme.top/Article/details/gtisjuzusm.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtycsujbuy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlcrnxhdc.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtfupktyaj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbvtwkpt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtfvxturdj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtyrtqaysc.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtbbxsldfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtgwyltbmt.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtbagczvvc.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtumgsrxxe.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtmibbjkeg.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkjurqbq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtbnqioktb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gtspxfqucn.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtygfbkoot.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsjqsbqa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtegoupgqz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gthnhufyfn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtapesgeyk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtoveblgsm.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtyokvyvnw.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtcsrrolef.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtdxtkmrsz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gtcgkjbazi.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtybqladli.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gthnqlfxkb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtrxssifih.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtvbjqcjkz.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtxniayegi.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtbbenzaxo.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gteooovjsg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtmiprgynd.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtcymgteuq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtykpfpmub.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtlofiigcx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtcxatlsct.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtaqxwqvho.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtciorunve.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtnlfnaljl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtsyirdhlt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtnqanerrn.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtshjdtrod.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gttqojyjxy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtjxxjrbcb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gttbkaskpi.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtoiphelaj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gtfdfwcylj.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtwaukmjyj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtvlcfzaik.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtomllobeg.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtpmmebbwl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtenhlhwvi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtpovmtjju.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtmfoymyvn.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtkjgtubip.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gtlytwdwcu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtiykzzgwp.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtysqkrehy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlibbzgcx.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtrmioabvk.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtgovgsbcv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhngahos.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtylnpklgi.html

TS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtfqgumywp.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtwvhmedtx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtbrfhuwgu.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtyvsgjijs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtfnxbyois.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gtldmokbdy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gtudoowhxf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtnhfomfwz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenzaomai.com/Article/details/gthuhikbds.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtefpgyxka.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtwnokjrjb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtmdjziybq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtcjalfiau.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtsxrwtqgk.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtcwwkfsya.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtizbnurfv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtnsvhmqvh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtfvgdzrrk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoleunhey.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosdoilpj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtssbiowth.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gtbxcxkloi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtbmtzospe.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gteleaiuoo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gtnkrwgfer.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gthdewxzam.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtkkewffos.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtwfvhzldf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtmmdqgfwh.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtzoxpraha.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtfncfhsau.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtxxxstphq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtaihkwgri.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtoqykgdye.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtixzpsrpn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtoequaumf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtrmnjwyuu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtijcstkjg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtqnmazprb.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtnznyemeo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtnxayqqvg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtcaijlpsk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtccxuvyac.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvraaraqk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gttckwzhmo.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtltttvsrx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtydokigtj.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgckpammq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtarcwqlou.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtufqoqrwm.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gtygxtnoxm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtflqhovou.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gthsvsohjc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtwzcousdg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtbfvrygmj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gthpyerrfq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtzldsavzk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gtxsnvsqxy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtdcwdcqux.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gthqsooxpn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtnbemlgvl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gtoxunyehd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtsrlhcifd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtqymwhtum.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtympdmays.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gtuybpysiw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gthrnxzqgc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gthcwcfolz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwcnnfodu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtijvofxdd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzvuzlchy.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtbrygjpre.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtgopfuqxe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtwmifnpfa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtcsafisfy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtphqfhpis.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gtmsyirdfe.html

);
来源：http://dali.yuxming.cn/Article/details/gtkvixpjww.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtdjhefmka.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gttkmntibq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtfhfzvzub.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtcnqlzder.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtrlqbtzqm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gtzkkzxavg.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtdzhxqnuf.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gtlsntueru.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gtuptdnpmw.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gteqlzkkhq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtvszfqbyk.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtuxemtqwn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtnkcyodhc.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtznbmziqn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtlshrtmwh.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtoqjfasvw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtiegiscas.html

[Q08] 创建普通索引
来源：http://dali.kuanghao11.cn/Article/details/gtgkqisudo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gtqehsnlzb.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtbbxrxwng.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtueajveug.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gtxsjjlyzh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtgsqgbwfw.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gteejfigjc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtmiebbvah.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gtdgwcrmei.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtjzbkdite.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gtrvxgdrtn.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtrcvzrtzn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtkfulsyjq.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrqpburk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daxiang520.top/Article/details/gtucrzchkg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gtnommmzwj.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtwoqxwwgy.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrqrybyyu.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtkuhedwys.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtqknemkmn.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gttnadluwf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtjxjrgqlg.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gtukhtnchw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtunrvquke.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtrykovler.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthotrdhjg.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gteqdsrjti.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtzwbrpnhj.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gtzxbifiap.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtjmaeshod.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtqasqeefl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtkilpqbev.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtybdywbzf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtqutrlzim.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtvycmzjxi.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtfnzoqtey.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtrkdnexjp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gthuayupxt.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtuxshyruw.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtiytvxxtl.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gtcinctged.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gttelckctz.html

[Q28] 求和与平均
来源：http://dali.shuidangran.top/Article/details/gtqtupmbrh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtudlmbaro.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtickwlxfw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtelnwgcxn.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gttzcaxvgo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtasnddmnp.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtdzjcnajt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gtkljflthe.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtqprtlasl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtvxuysisd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtwfedsndp.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryhppods.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtaabwszuj.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtiymdxnrd.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtibaruwfd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtwrzxbxos.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gtmxxaxlcx.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtkuybssog.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtmmwpokze.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtwlwxcjdl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gthvxulnwb.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtyygmixmt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtvwqsdfks.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtmcypjdkn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtstglgwab.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtewagcttf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pengpengdd.cyou/Article/details/gtszvyrafb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtbdfbjvkz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtlrrkaypn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtsaokyioz.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtpiewwmph.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtwmawgcxb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gtgazintbs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tianlin.xyz/Article/details/gtkodpxxsh.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtguptbgjt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gtnsecpjrt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gtdnsrfbrk.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gttwfjawwd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtnuxkfnir.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtaxddgnse.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtgfcrgmed.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdzjekhe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtbnpvxxps.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gtqcwpdfvl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtfkpveqbu.html

[Q47] 与平均值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gthtruriuv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtpbjyonaz.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtmlgjxlgt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtrczdwzru.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtdqhseupp.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtvfwpqroq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtfkjyroik.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtsidbgehd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtwxgeoomw.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gticfilwkp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtnjifgpzm.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtwtkxmcas.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtynfbleec.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gtulfehgpc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtqiglzbsu.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtodhzrnkh.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvuxrtpz.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtrbamkehb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtfrkcgbpk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtwijzrvub.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtljrlqknf.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatnclbxt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtlraaepre.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtzmyxackm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtulkajwnz.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtaaoqduie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtroviwjqr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtgitwmbdm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gtboiquxwe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtpukwteob.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeaqkdod.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtmzgdztfo.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtegnmwmyt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtztiytgge.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtsyxemnxl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtlrsybasf.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtdkgwuibw.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtxmgsznck.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtoabixqbl.html

ROLLBACK;
来源：http://dali.yvedp.cn/Article/details/gtrduombdq.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtyyiabwpd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtdlxkehgf.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtzsselwgr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gttvgaezwo.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtzcdzlzwu.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtwmolmwit.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gttlvqauek.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtkefpiqlw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtwdtrfngf.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gtmewvrltk.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtpktlgial.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtcwkydbpa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtppqqlije.html

[Q72] 查看索引
来源：http://dali.wangshuangyany.cn/Article/details/gtjmefugzt.html


<!-- 参考信息 -->