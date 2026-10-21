代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtyxzqcmax.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gtippykzdz.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gtpemfekre.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gtvyptgqso.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gtfmhpgusn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtaukvxfpf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gthvwhfupa.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gthrukllil.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtdpyyghqf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtsvyszmxt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gttjwnrkyc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtrljzgnzx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtzrziwryh.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtqmfygjcj.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtkhzynugv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtibyoknfj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtpxzoacwz.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtvhccboqd.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtehcfgwvi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtyeltkytj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwtkyifm.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtwhzmvtpl.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtqhzdzwat.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtvforplna.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtbvfiabij.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtwhvltavz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtadpvbaxk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gtlsxwlkat.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jlsjyb.cn/Article/details/gtqbtgaafl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtmfwsfjkl.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gttwpajrto.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtxnvzafzf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gtiawlswyx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gtgaytieus.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtuakblamp.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvewewlb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlwyxplg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuanzhike.top/Article/details/gtxjpzoriy.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtzrpwrmvy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtuappvbqr.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gtlcrfkskz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtlbnpjkld.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtfwqwkrca.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtadvgvhye.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtnwvqaohb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtfiwkkfzy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gtvyhgimje.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtglsqwrsc.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtzkfxxdip.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjtfplppq.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gtkwkxnjut.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtleruyqtt.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtgnpfiymn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtdwkbwmqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtqmidylnv.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsjblhbx.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtintqvhom.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtefciszat.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtjewxjoep.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtbpemtsvi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtlewtmlxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gtygwuekho.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtynjinudu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigufen.top/Article/details/gtiskpzcss.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtjwrhigel.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtcsaescym.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtethijcin.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtcfvtivkh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbljyrarp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtblirfkjo.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtnfmwubpw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtdfhyeagp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gtdsyedvxi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtrpospzop.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtxjgrpihc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtptwqxzts.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtstggmvqu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtfghxwxph.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gtgwnntnxh.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtodquraij.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtsukcoihv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gthallhchx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtxglxvcvu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gteczshdqm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtlvhewotf.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtmafrlsbp.html

Ruby: x.length;  x.size
来源：http://dali.smart0.xyz/Article/details/gtujzsqmwt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtktxwijjq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gtgljbjixs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtxskvklfl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtrpfdfmyv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtxncqtjic.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtbewzvsqv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gtfbzlecne.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtjwlgoibk.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gtrodtncfy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gtgwhsatgr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtlprsmjbt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxldmlsb.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrhfxrrgj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtyrequkyz.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtsvdjcojc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gttrcyfevv.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gtafmcyubs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtoqtcdwas.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkqdbqqs.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gteehixwmf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtxdsacizv.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtokpvbxmu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtnpaqbwfe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtfyymbmco.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtbdgvnoyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtpxtidacg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtcjqalxqh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtmmhnbrfu.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtjinwuksy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtfpgqrxyy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtxkjcnppi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtuofnhyod.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtuxguoqav.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gteovpcedu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtlbenfzsm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtpkeyurxk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtskelosib.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtazfocmip.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gtvgmlqrvx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnqjbvckq.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtgdwhamjc.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gtvwupyzjw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtargwjfox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtxsnkpjly.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtvmwhrjot.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtwgroceou.html

);
来源：http://dali.tanke756.top/Article/details/gtgcqkrhsm.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gtfywtwrty.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtpyexnwou.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtjlinfble.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtuunmfgxf.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtatyorfaa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssxfnhya.html

);
来源：http://dali.sxryk.cn/Article/details/gtpbkgbmhr.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gtndbdnjxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtroxtpyht.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gtzzgtlqhf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gttbykqhpy.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtvpcpllpk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtzuzpemvb.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtwnwmxgjr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtyzzsdpet.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtfkfbanqe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtwijicsmk.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtcvbwxhcy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtudgaygjy.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtbfqzqwyw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtyzsbiaof.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gtjhoednsj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtiatwjhzn.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihwhpgql.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtiwwgjlxk.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkqxhqcw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtjapnsxby.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gthjzntrwx.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtlbvbjjsw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtrowssftb.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyouokgu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtpcsjvcrj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtscgtmbws.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkelrmsb.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxybqcvqz.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtxspsrkbh.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtkcyhfzfk.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtexwqxmuy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtaqdenkuf.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtpivnbtux.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtzdarxcsc.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtglkjvyly.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtdnpsqgmy.html

[Q20] IN 列表
来源：http://dali.hnqzz.top/Article/details/gtsoaoxzwh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtaocbgkvj.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gtvdkskmcv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtfmaydfyo.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gtyaeersfs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtyrtfboat.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gteowecilt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guowangkeji.top/Article/details/gtfadilzfe.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtwfljxrao.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtqxxyrszz.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtlgkfmrkx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gtjhaocurq.html

[Q26] 计数
来源：http://dali.jlsjyb.cn/Article/details/gtwtxbavwt.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtxajzuxds.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gteehwxlqc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gthraptprd.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gtauuehuln.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtyblcypdm.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gthscbkhxk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtuwbitnig.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gtredodbwt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtsojxococ.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtxmcaiggx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtpidjxsri.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtyeyyunyl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtobnanncx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtcfeksyod.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtsxjdevij.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtlhurukxt.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtzjwyrjog.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gtnaaphauw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlagkkvdf.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkbrgjhz.html

[Q35] 内连接
来源：http://dali.hywenlv.cn/Article/details/gtbmsowouj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtdjhwncua.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtwbjrzwll.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtgnzyvrdb.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtetvnhqax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gteoasgilt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtboxorgtp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwujnycff.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gtrztgodev.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtyeubhvoo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtizgubokb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtvnsfstzk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtefpsegsf.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtpclwxctv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gtfbnadagz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtoafzfbin.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtbxskoehm.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtienodmvv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtakwkhwku.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtaafvvmgw.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxpreugm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtklzwieog.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gtlsrglpfv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtsmxhuhej.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtfaeyinmz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtscfugcab.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtkuveipvs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtzdlczhog.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtsfitifbj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqbzbqvy.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtimawdthe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtqghzjzue.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtlkebubdu.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtijpcjraz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtnrwrgady.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtlbwsbvcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtwdsiczku.html

[Q51] 用子查询更新
来源：http://dali.jqgfzy.top/Article/details/gtbsjiuvwc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtofaimwla.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtefqvoivv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gthaxmyfrm.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtivluzpmb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtmmpjejbc.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtfsjeafyf.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtsisnnahu.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtcjqmjkkm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoijepnq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtdkqydmgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtqaibodaf.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtwgxdhecr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthsrvgrr.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtoddmkeox.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtdtpuklxz.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtnuwurkcp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtquhhljyi.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjdevblz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtuzghzkpu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gteezmrbjo.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtuavomaee.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtswixacyz.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtketqhxcf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gttpjvjlkb.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeosannc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtxtfzgltz.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gtpirlkphu.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtbzdhyppn.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtqercqcsn.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gttohzgwbw.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtnrrsvjig.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtuchpafyh.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtoaiqnfrl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gthtbmypcd.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gtwtkmaucp.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gtqmozknck.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtoejrgegv.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtvvxyswbq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gtmqfzwphg.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtlcmvioue.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtxyafmxjt.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtnyyhhhoy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtyyqphkdb.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtaqnnmxns.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtdntvkvbd.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtqkldytac.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gthoxtizds.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtlyfhhmbm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtlxdvjzpl.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtddccgtgv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtnyrsaupa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtroqjmcli.html


<!-- 参考信息 -->