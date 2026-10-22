代发 wailian999

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2giuhsctf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gt2ihplagdl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gt2hrxnmevu.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2gvzalzyq.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2pmngnooq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gt2xldwxawq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gt2xbureixu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gt2ccruulge.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gt2kuquruxv.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2vezwgvss.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gt2fiqrqycj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2vanjytig.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2qurkibaf.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2cdoeunnm.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwlcxidb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gt2dmzuzzjs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gt2svudwsui.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2qthesdlg.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2sjwbvnjh.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gt2izxouqfz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gt2surbhmdr.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2pwzqvcvo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bcbuvwny.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gt2fwokvzkv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2xbtrzoei.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2hrqemdeg.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gt2uzaqqzie.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gt2kclgooep.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2brujjdsj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2rmxgtwxl.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2fhwwbhyl.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2wdsmgixh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2przwbiwd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gt2gfyxxewm.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gt2xoqmueol.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gt2rktvcjgc.html

[O06] 使用进程池
来源：http://dali.dashuyun.cn/Article/details/gt2vmlrcnzj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hfpthk.cn/Article/details/gt2vtwqvgti.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gt2hfwsbxub.html

JS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfarzkzx.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpuhepfv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2kwuopjnb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gt2kcgilqbv.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwtdojfu.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltxnvwgu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2jshyvbtz.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcksuuaw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ausjemus.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2vsorkjse.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knpjjaid.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gt2miskjorv.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2nhceteqw.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2zzsjdziu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gt2mclysvjm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gt2ygdoraeg.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gt2zlpvdzur.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2czofdmkt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xziqi.cn/Article/details/gt2yhexqmht.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gt2ripnlhiu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gt2fmjhfxpy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gt2jdmqheli.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gt2bthdqvmf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gt2odjroquf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpbbewoi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2akotvusg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gt2nrnjcjlu.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gt2jonewjse.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gt2qsymheaq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gt2augawzgr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2lnzvoues.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gt2zsvljzuy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dyfqqnwx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gt2kejaygol.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2orkxjczc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gt2bljntywv.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gt2dpptanzl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gt2bovnoygn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2uqugqyxf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gt2mbufgfwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2opddeqja.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2lihobtds.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gt2jfgkbgdu.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gt2djvycqzk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cklplvqz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gt2pqstdxqj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2gjvsqntj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gt2rvzkwlbc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gt2bywuqwir.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gt2pexlgzhi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2zpvxxvqg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2navpeycq.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gt2ikinqkot.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gt2kflmhhzz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gt2irrkwcyp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gt2euqwucco.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gt2hqqxytwh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2gyzedodo.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gt2yzsrzonj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2vbbygrel.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2prydztfi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdmizvt.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2izvahvzb.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gt2hcjqgxrl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gt2nqozjkdm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvpdpzim.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2mdbqpmrg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2eiuhdkbn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gt2asrtinvl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2yukuzsgk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gt2yytowfjz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2thkllwux.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2suowmtml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gt2epywxikc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gt2nibvbzvr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gt2gzhqnrmg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2lknkbtsj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2jmoafive.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gt2tcgwaogn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2usddtujs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gt2ktszrvrz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2gnutwthi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2kqeqvmgg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xxqrkipx.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gt2kaafbrqh.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2upfjrjrk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2sxfcwqye.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2wadmqumh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gt2kbvllehe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2wmsrralw.html

);
来源：http://dali.hnxiangtu.top/Article/details/gt2aycaiwgp.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gt2eugexjyg.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gt2ewuzdbkz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2kuqcggdc.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buohctub.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gt2wftaqmto.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gt2hvvbatig.html

);
来源：http://dali.sysykeji.top/Article/details/gt2wjioiikm.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gt2eujbxrfu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2ntlafsbj.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gt2unehvjjw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2qdteilyj.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gt2pghkxgzv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ooifjtmj.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gt2uvhjrvlk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gt2ojuydofg.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gt2dvpeefwe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gt2naiocovy.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gt2vtrwhgmd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2jxmhvhfj.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gt2fylnsoyj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gt2vbbyvavo.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gt2ehnrhjaj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2hfqbqbfd.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gt2daycqoqv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2ttluvvyw.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2nukdvjdj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gt2idqvpkaf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gt2ypbscnza.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2vivrcstl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gt2eiyrgdta.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gt2cwjwrfmq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gt2skttkrms.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gt2rmvjcczf.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gt2colgsipy.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gt2srcfrpql.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gt2xokrezxi.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2rgdpfggc.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gt2hqbkdxap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpmwbatg.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2zgyqqich.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gt2assmcmvv.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gt2mlbufdxk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gt2vxuionzx.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gt2sixbyqfw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gt2bkodwrib.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gt2qnbbazsk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gt2nadvekpm.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gt2epdtnbvj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gt2ebqkaalr.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gt2okcnbrne.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gt2kmkogtph.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gt2lpiugrgn.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2jnpywbms.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gt2khbrfoun.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gt2xtvahrhx.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gt2tqqilofj.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2dmncrbio.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gt2dukdlpyn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gt2xouqmqft.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gt2ircmfrhi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2aqfwhxkg.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gt2fahjmpck.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2dedegptx.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gt2xqayijnl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2onnhnqqt.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2otchfmyd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gt2lizhlrgt.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqwmvdib.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2gklqjtji.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gt2ocigcwee.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2sicoqprq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gt2hiuxxphp.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shbeiykb.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gt2phrzuhdz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gt2vvexbzii.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlrxasbm.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gt2tlqbgxkb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gt2iihunqem.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2dxflrbua.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2wibzspct.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gt2uofjhnyd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gt2fpnrqkkf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2tyivpuix.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2nwlmrfuq.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gt2ykyivbjo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sxryk.cn/Article/details/gt2gahtaemq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gt2mluaxkkc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gt2gwtzcdgf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gt2uxertagn.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbesvght.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svdmoexw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gt2qimiscfb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2iwffhhcq.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gt2txgldzff.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izpvgvkr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gt2sutuuudf.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gt2zosunoed.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gt2fteudmsd.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gt2lrbcgjyw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lthadgxj.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gt2mlsgjjjm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcygxgcv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmbtbmlf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2umpgdscm.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2vealclzn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izswghyh.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edlxgupb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdncbonq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2qettgurq.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gt2bbgseipf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2gpdawmxd.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2ydapluyt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gt2jheoukla.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gt2yapftpdb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gt2piyufrdv.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gt2yocbxsps.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2yiyoqhul.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gt2ayohtygl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gt2jqcifqld.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gt2seclwtxj.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gt2marifulw.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gt2asglzeqp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2vyqfukap.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnjbhhgc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2xrdqjgfv.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gt2laeivqix.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2eogcdgbd.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2iglxknnv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2wknnwztx.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gt2hgyjanbq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2jlllpabw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gt2squdpyxh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tianlin.xyz/Article/details/gt2cuktnacb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpmslxhp.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gt2hkhhrnri.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muqhaxps.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2oygmnemv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2wkpfudjc.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gt2yybkxffm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gt2ilydxvrp.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gt2amvikrbo.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gt2jhhepvfq.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gt2injvkpgt.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gt2fbvpciti.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gt2ylyklzms.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gt2sucszpbf.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gt2qjvhdfec.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2huyvygcg.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gt2obagxjwv.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2biyjfysr.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2ukqohxtg.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gt2fhayfmfl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2grismdvu.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gt2ffrstwcn.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gt2ysudtkkm.html

[Q71] 查看建表语句
来源：http://dali.yj20258888.top/Article/details/gt2wthtwvgp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gt2ohudvouf.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gt2rhhfvhso.html

SHOW INDEX FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2wblcvyfh.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gt2ooavruvj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gt2qydvqxhd.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gt2idiuiebw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2ggtjabbg.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2bjlgnvtd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2xbwbpcwt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2jwafblxf.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gt2zaqlflmt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gt2ncctcsim.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gt2gdsgjgyr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gt2yyuwgnid.html


<!-- 参考信息 -->