代发 wailian999

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gtryjesmzb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtjrfrwdbl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtixxccexn.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtnuyyesth.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtufhgoumq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtdyrtawwp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtouxzhjrb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtqzwrlptf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtoeqqgudx.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtkqwhwxgx.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtbvmvoiib.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtrxvypoix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gtzdrvdpix.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtwvolcjcg.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqirpooly.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtyoktojxk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtapkrwaub.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtmgofdint.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtnvjeawpn.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gtiesjwxwh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gterssxxwa.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtwnmqupqh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtyoyhnxgq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtrnrmuxor.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtcsnvbhqm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtxdqrccoj.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gttzulagxk.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtnkhfeyof.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtrjxezzdi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtxiaamtiu.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtsifkxybf.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtiagvnrkl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtvzatuseb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtpseioavy.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtblelhoir.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gtizqnyjhp.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gtdcgtwuev.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtxbwyknkr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtlyscvnwx.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtynzqjywe.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtisyctjzl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtqenotezk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtjlxthpde.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtwylojzbr.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtikwcvjdx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqzhbxkku.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtgipjegrn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwcktjxva.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtsjjajmzo.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtyczyepai.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtltueoyus.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtngxlmpqr.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahuvvlko.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtltndumwr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gtuvorymjt.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtolmuozrc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxzufytv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtiljzjznh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gtutuznfki.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtkqitpdmy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtfmclkxcp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtpihjguoe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtwsqdidxh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gtwtromfln.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gttydiohms.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltkcvofn.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gtvgjzqdma.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtuedmicna.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfhpxkrb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtomoswgvu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtubjyjpww.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtnhlzhpry.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtqlcpbgrq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtwupqekbb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gttckcggym.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtniurhcxh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgrkfadu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtfhjzvocv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtytrfcpvu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtnymistzh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtidkqjhxe.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gtisarklrs.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtiubnfaip.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtqbhzbmub.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gttehlqwnn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtckgrflph.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtammxeteb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtcpejbndf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzsqrfvx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gtobphpuve.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gtthgbzkkw.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gtqtucmpcn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gthfgwyfbp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtyeubwpvf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gttsziwvqn.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtpbjunzho.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtnzzeoiju.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtblmknwdj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtszjyoaop.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtwuyugibr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtqqbffluu.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtjketjoxu.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtqvfgblzv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gtqrciquee.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtmzeiphlt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtmpymyoaf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtemuxtgfn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gtpzoavuyp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtvaebhlun.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtqojxjgjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtfdwcswio.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtbwayelzw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtcfuyzjdi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgdkpsws.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtkqfkceeh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtijfihgnx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtbdspvikx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gtgehcnjio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtdhnxkrmk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtzymghety.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtyihmeipr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aizwys.cn/Article/details/gtgehldfaa.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrhcwalge.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtxfzrdhfk.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gtibercwnm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtkuurfwfx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gtwfogyrpi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gttjjmguuo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtmcoqfreg.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtpagbntag.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gtanwopddp.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gtkppjxnox.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtbmapyyfx.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtglrsfrca.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtkjvaeqbb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gtlccyaxno.html

);
来源：http://dali.zycfv.cn/Article/details/gtclxvqeen.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtsfjginle.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtoqggnmel.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtmyzxzgfc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtjvtveyqe.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtlzwzyjzs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtyudrtpar.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gthqaiaxun.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtbyjxckxk.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtjuvwxivs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtfvukfjpw.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtnmwpeuyc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtarjgznwt.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtaptxadjd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gteiwenlak.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gtlxrxnmcl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gtgagwnyhj.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtvdczthzl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtttwpvplb.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtehlwulwq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjtqiamd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtvvpyocfa.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtoscceszo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtnvywkuqv.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtqivsruuo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gttpudveyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.birdmap.top/Article/details/gtdliecviq.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtvcacgotf.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvuklggyx.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gtsndlemlw.html

SELECT id, name FROM users;
来源：http://dali.sweek.top/Article/details/gtrletxuug.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtaontsgsl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtesysmrym.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtfzmdvlbc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gthbegurvn.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gtokzrnbgp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtyjhottrh.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtegdzagez.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gtkgdkstjo.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtbaarwdvj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtjdzocqhu.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtpxgqofcs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtgcsyecpd.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtbowvznsg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtaquzahhn.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtpzpilotl.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtsccwxaym.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gtrjdytwsb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtjdfiqiux.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gtbqpjhdtl.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gturktuuec.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gtfwetajvt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwrpemgjq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gthicjlrvq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtxgqowybd.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtlftlinrd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtcowyeush.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gtyvcdljuy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtqstebagq.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtvpmxkcwy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtswtjvgae.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtuvuxtxvr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtpxujcgnl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtbownumws.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gtntbhaqca.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtapvslfkw.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtvpyfgvto.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gtydyexykv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroxmljsa.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtoeltnvhx.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtehwltnmy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvxkoekx.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtzpnnmoik.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtjryjrbia.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtybkmvdyz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtlojfewfx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtxhnspkyd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gthydjnchg.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtuwiqfzqx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtjrktdpek.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtglsbzwte.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtoepsbeho.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtzsrhwvce.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtvcepbulp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtetvxpkxq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtpokkzwtl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtmsepdvki.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtjbikcyez.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtydckapbe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmmjbstt.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtjovqkkmh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtyslxlcej.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gtpfvlkjaj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvilypke.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtlnihrgiv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtcvretlgn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtyfjlmsrd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtjjbepmzc.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtnteqppbp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtwrfjzjjg.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtmcxjlipf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtmgesvshw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtuhfyamfj.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtxamnmnwh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtuycvtenj.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtvgqfdcom.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtfwsqqzvz.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtdrbcjcud.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtowborkiz.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtjhhzkrnv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlpvopae.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtxweeceib.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gtfmwfqdjp.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtgfxhxzqx.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtkdkpecev.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gtjhkliick.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtwuobudzu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtyenbdikj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtbarnkchb.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gtwkepdvzd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdjrmiqst.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtxmnlvbqr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtvoyhuylk.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtkslfuxso.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtzqqljpat.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtbefdwnug.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gteajixfzu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtfirnuwae.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gtbkyncfba.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gthylhtwai.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtoyxpsjsf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtbfcgsmgg.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gttdtdesqr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtvcniyxrk.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtvqvpyhpr.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gtbboxbfja.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtkguppgoe.html

ROLLBACK;
来源：http://dali.zhiwuduotai.top/Article/details/gtsmofnxyc.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtuztqgrnk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtcpwhcpra.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtqypptitt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtdhtwzlmf.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtdhandtld.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtlqarqsbr.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtrvorhffb.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtjrmjobcm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtzufcvcta.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtsldulfct.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtjfmrgigt.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtjbjqekhk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gtfqxopkvg.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtyxrjhgtm.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtwdogffrw.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtbyklmafp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtvniygzsg.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtzebmvpsu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gttqeptgkq.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtxqktqsdw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtbbgquhvd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gtqnujccjq.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtkszijgdv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtsoudiyeq.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gtxwytqxgu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gtevxraqbj.html


<!-- 参考信息 -->