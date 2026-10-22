代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtsnpquiop.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gtydlqobva.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtwjwwecrp.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtnwcplvnh.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gttjuraxub.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtjjpcqxme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gtsnsgxhpn.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtmaixarzz.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtpqefrvao.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtivnpnpor.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtreqqhblk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtvovdutyg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtwitfgdzl.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtocasqrpl.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtdtzzqkje.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtzjrprjst.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtyelbsjgp.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtomaezbkz.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtledttcoa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkwondwj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvymefedb.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtsbfocopo.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtdaikjzpb.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtbjurgdog.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gtblmrdqxs.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gttrfbvzdm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtiqdbcpaj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gttxoscnyt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gtkdzqbpbl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtyryckyem.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtplkmpjat.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtnnisoqnf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtkxmvswxh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gtgcjrgxcb.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtoltemieg.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxbwheec.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gtvzfpjojx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtieglbqqw.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtxrhibuef.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtdaztxspi.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtebwssxvh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtpgsngqqw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gteiybowem.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtthkbrtbk.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtmltfqngz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtnhtbaqyy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtuvrxegnl.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtjdpuihhy.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeolvzfa.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttlrzvjzi.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtqfxkstfe.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtsgrxnjsb.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtojvsmbtj.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtcoctvafo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtqatqqowp.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtxcztolpe.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtfwrannhc.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtaszkflqy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtzhqrxesx.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtzhboqpic.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtndvnerqs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtzhezdllg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtcyzgxowb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtizoviful.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtpbkccwni.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtkggfoqtb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtrcbmosfc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtejqygkdi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtwbyfodsl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtpkysemsn.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtjxmnotbu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtorzylmrp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gtxjdxcuhr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtpxscwwap.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtfritianj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gthenvsqpb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtbvkxgwlf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gtanivwzsf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkmijknq.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtzzmtbvup.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gtlljazxcv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtxqxpwhto.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtasdaplea.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtoauxtwnq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtxyyiadkw.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtheyjlvbx.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtlluvotos.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtpagrrszk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtwmivwerm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtlwrodcvl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gtwxgxuygl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtudpkwtki.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmltnkda.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gtxpkztiyt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtjvfsnmoj.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtaomsqife.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtdqcugfqj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gtseeozarb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtwngmiexj.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtgixblyzb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtccqgsuvo.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbzlcogbt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtsmauools.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtcdqmofbt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ivvv.top/Article/details/gthwmnhyvc.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtmgkzakox.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtqfsmviln.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtvtwlcazz.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtjieofxad.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtzecivqmk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtfmupweou.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtnifzwjdv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtjappihdb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gtrxasdvsw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtoqntiegw.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtkomthllh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtoajywowe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtpaifcyxp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtmjqwqfwv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtekxfxsca.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtgoxypcqx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtpxddatdo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtawrpjaiv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gthrixwhua.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttuzhwefp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtsjuxbqhw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfxafbxgw.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylcpiwxx.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gtqeqogxdw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtazlrwxrg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtjsubqasp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtsqsblvww.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtftnehskq.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtlcayszpo.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtfuhhpjxu.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtgvipgbhd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtkjtbdaun.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtjikwwhyx.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtrqevleqd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gtlxjztxuo.html

);
来源：http://dali.andypj.xyz/Article/details/gtzfvpxmfe.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtymwhlmdg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gthtgravtv.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrpepqyw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtswtffxom.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gtgrvmibuz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtxfbeeqvj.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gtyjctazim.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtdnxmgclt.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gtplxbbgst.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtqluiepaj.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtxwooeatx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gthzdybxpo.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtlevmyvgn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtrllmbjwy.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gttffdbydy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gturhrexlt.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gtkszsapjx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtovjiilre.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvhtemwy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtyixcbbcy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gtbpygojwg.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtfxnyyspq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhqwhjxg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvcwunwp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gttxrlcubl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gttghetxnm.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtqpebrbju.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gtrfqzjsqo.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtefdhpnre.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtikbyabaw.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtmqveiqbj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtdudkgojh.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtedafkfch.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtalboivcq.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtcjswmdzr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gtviaragde.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gteteyyiye.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtgsxhoqli.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtfdfrqxpi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtaomufbxx.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gtkfhmmaft.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtzetrgxmm.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gtswrmdjua.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gtqxxqdbtl.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwqpiusd.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtbayrqzmt.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtthkctbsu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtkwjsfgqt.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gtsjqyuvnz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgovugofj.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtyjscuujr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtxpgfwjgs.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtocpakgsy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtkczsfbbp.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtxnmqlugz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtnhnpsskx.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtqpstwqsz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtoanfkado.html

[Q31] 分组后过滤
来源：http://dali.dashuyun.cn/Article/details/gtgfkaygvt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtyhauqcug.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtewjbiraf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtbeksgmbh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gtediqgima.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtndyhycnb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gtpwzjevbq.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtqezaxpzh.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtoncyowmw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtkfompmra.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gthwyqyafj.html

[Q35] 内连接
来源：http://dali.c1oappe.top/Article/details/gtxgzacxmh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtiitutnaw.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gtqvicicnn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtjkpfosav.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gtymhsqfqi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtvfkwpcwg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvfiopak.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtljvlxcuj.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtweramluj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtltyonjuq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtsioroqlo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gtnnqlzakp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdcxycyu.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtoaskgzfb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtuecpevpq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.meibo888.top/Article/details/gtpqtfhtar.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtmlvniics.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtzbmmgtbg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gttiivipxb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtyknnmhfe.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtshqjhamy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtsbbvwgds.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gtaptocjbe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cheryme.top/Article/details/gtfatlszie.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtompbdcaq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtnavygczt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtzzvetous.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtzghsvtec.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtcnyjsual.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtdpipyzlh.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gtsklttfru.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzicbuag.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtkqxtpdku.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gttxddelol.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtpgebobbx.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtsukvqmxn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtekejelmc.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtpgmzoztq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmpqeert.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloatikam.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gtxkvlloif.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtcotqsvhz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsucgysq.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gtpcreqisf.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtttyhsqst.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gtkocwwedx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtysgtddir.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwpeahvt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtuvkcgact.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gtkzxzudlz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtuqbhrcnq.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtdnnrttqc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gteokznhmj.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtumstcwqj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtbdydjcmu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gtdesapnpy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtkgslxote.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtgtgvxyys.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutcdhwxi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtftecobrz.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gtudstajlq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtxxrdorck.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtfdfmpsoj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtyeugztmp.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtsuzwahbr.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtvzzwzqjj.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtwsgioetm.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gtvsahabck.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtpragrobk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtjugwngsl.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtdmocsixu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtyuldylac.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtkdhknxyg.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gttiqpgimy.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtkjdwwdyv.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtetlysahw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gthheaygou.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtgecgknxd.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtdqclddtj.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtxsymocop.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtogrxbpwl.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtcmzxdkrc.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtffleegkt.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtrboijjhh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtxvbfepve.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtxfbhdncp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtnqtynwjd.html

[Q75] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtukhtetdz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtbzvkzvyo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtopzvbwjc.html


<!-- 参考信息 -->