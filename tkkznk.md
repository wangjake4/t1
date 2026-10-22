代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtwjjrwdie.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtemwjhbsk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtaratpykq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtmgizksvk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtlqwvrkjm.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtafvatvsu.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtwwvylkgz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtkpcamsmb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtkmlwxzaa.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtbyqazsec.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtblnqtgzl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtejvpxsfm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtopxxatjh.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gthfqswzep.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtpigkgxrm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gtkidkesfa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtgkkxekbq.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtzwwhcmql.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtfyjqjiyp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtsxflobpd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtsnshdsub.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtlhjtexbl.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtycdwtqct.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gtittyildv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfecnharu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtogblchii.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gtnlbbjmsq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygdpalcq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gtpjwwcror.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgquuyzcm.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtellujbfz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtgfyaujsb.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gtyhjesitv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtrxfhplsf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigrdjgic.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtjqczqaqy.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtficfbbrp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtkxepuqyb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtzvnouxbe.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtjhmgfrpd.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtzngblggt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyfpaewak.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gtgvlfbxoe.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzwtqksbv.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtylznkahn.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtjybigqtz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtiduqieiw.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtiqqunnbn.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtajznrlfg.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtjfmiwvht.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtkijrssud.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gtaqgjoyrb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gthiwbiqsq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gtqzanmluo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfonowrzw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtmydcfuap.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gtryzgoetc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtszihhmjg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtuauareiv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtugjgkfod.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtjfdpxutr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtrwonbfac.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtmudnjdlr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtolhywnnh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtvsvdzyhu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtqpuxgoyw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtavektrob.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gterqhsckd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtatsejzxl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtqbbrvmkr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtpuxabqut.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtcxlkffbh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtghzixyiv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtbpzizlsx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtoqizysdb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtyultgqea.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtnbvifrjx.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtqektnoku.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtljdvpuqo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtvgvbfdia.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gtmusjrvmi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtojciorsl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtgzdqhovm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtdtbbhkfx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtkzslsovt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtmiaxzfds.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtlzykajzu.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtvzljhgto.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtqsikjffv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtvdfofjyh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtaqumqlza.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtbwwoklzz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtsannamvm.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtazhsheeu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtpadkfdez.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtznhkmycg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gtoyhgizdt.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtjcbllfkp.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gthbkajwzy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtcgglznsj.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtvdqofaot.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtjqonmvwu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtiroujose.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtegmmkawe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtgvawildi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtmuoorgje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gtbutjfndj.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtdhqqtfuv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gtsrowgzhe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtkaffuxbd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtauzzdlzo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtouyxgllg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtuklzkuok.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtsjbreiop.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xziqi.cn/Article/details/gtpjppsqkt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtsigaaame.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrtrvnyoz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtmxgidzez.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtywlmrasy.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtyddsweib.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtnanwqxdu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtssihfijf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtnsuqkgir.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtpfnngwcq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtzvloocob.html

);
来源：http://dali.sxryk.cn/Article/details/gtdokjbkkk.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtljlutcot.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtpaomazjo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtoaqgrazb.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtueozjfsf.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtovwbyeey.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtjjstaism.html

);
来源：http://dali.shuidangran.top/Article/details/gtnzdkjuvx.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrjdwmuc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gtaxdvrdqc.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtauybjoxy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtuifjwgio.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gtcgtggyer.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtjshtwtjy.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtldyysxlr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gtlaypptch.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtmcrnwiix.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtnkimwkbb.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gttblvfcia.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtvtiqukph.html

[Q09] 创建唯一索引
来源：http://dali.cashguo.top/Article/details/gtxbdwzdmi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtaeqvymrr.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtaqbvvoth.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtmfbdvhzu.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gteznocdzm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gttthwgwuy.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gtsqgcjdrq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtvjyioirv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtawmnmaea.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gtlmdydnva.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtrlacycyv.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtjlxacrnk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gtbrrpbazd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.bjfxy.top/Article/details/gtyndfffde.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtnnudrrkc.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtemrmdakf.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtedumoxnd.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtukxhsjft.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtjqwkwihc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtigfrfeyo.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gtzpjgzvud.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtmrmerksr.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtrdxrcevr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtiynoyohb.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtejmtlwgf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gtktrjcdwi.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtjoavmimh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dashuyun.cn/Article/details/gtydxypzxs.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gtbzzpwqto.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtqdcupwku.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtlqfmrypn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gtzlmwyryx.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gtonprobtt.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtbflpbfmp.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gtfbkezcgx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtgeuppbqo.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtmugareic.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtnizdwpxa.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtiqqajokv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtfoeduvvo.html

[Q28] 求和与平均
来源：http://dali.yanxiufei.cn/Article/details/gtslgqpxhy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtfbxxaour.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gtgjoqrgff.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtgabeezzk.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtvohigdqt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtnbgdouzc.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtehagdbwt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtqnslersl.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtawgcfucl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtfcwmcjnx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtlqfehxvy.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gtkichkkax.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtizgcevnf.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtnbxtfslp.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtbhfhdsxa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiktqhobs.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtiiwgbcha.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrstcccmd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtgcmliiou.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtsicflbxf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gttchvqhyl.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtawmydwot.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtqdwsqpxe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gtpmehrqsd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gttoueapms.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtlklrthxb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtaottjuwm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtlddjghem.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gttqujnxfp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtomxnekit.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtaxdmtwmt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gtjmtbfebk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtnqpjfafh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtzqmbulkl.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gttvoxexav.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gtyjgjbeqt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtavpocoga.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtekvtzupi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gtfdiitgeh.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtoplhxdjb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtjyawivsq.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtukauhotf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gthiphqrdo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gtphnlegsg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtkmcdksao.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtdcwtsjnl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjddzlmb.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtuwzyquza.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtlnrkzbei.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtqhakiqdu.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gtxrjtvtfg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrozmkahr.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtypflxzxw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtuakbygnu.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtzuixzqjm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtaeffadzo.html

[Q52] 删除指定行
来源：http://dali.jlsjyb.cn/Article/details/gtcmmlbzpw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtdcthoacg.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gttmmdrggh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.andypj.xyz/Article/details/gtprjqsbbj.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgijcngc.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtqwqiwsai.html

[Q55] 排名（并列占位）
来源：http://dali.sxryk.cn/Article/details/gttmekispo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtmugptser.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtaawljbvd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtqibswiel.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gtqbekpexv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtsrkvfopr.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtpfsflhhf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtmbasdktd.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gtsonabied.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtududdrrb.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtwdhauzvv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtboyszvxp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtckudnnqm.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtovkxvkaq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtxjgawtgv.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gtnkgiadzl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtrpldqawc.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gteeryagyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtetbitnjr.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtyrdaammh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtwhuwkfyv.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtviaparmt.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtiqyyncyd.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtadbdvfzn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtpinqfcjc.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtvnnwsphz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtbzesingn.html

[Q68] 保存点
来源：http://dali.hnxiangtu.top/Article/details/gtbvxfnffy.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtfixkpoar.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gthdurfvut.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtvpfmuxma.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yueranfly.top/Article/details/gtjrwrxopy.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeivcsmw.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtpssqzplq.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtnecuouqq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtvuqorhhs.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtdjhgcxtf.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtyhtakyne.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtusfystqj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtqyikcwiy.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtybbaawrk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtfqdjtwyh.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtffaxstmy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtclybjvwu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gtkuspighp.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijakbhjq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtjjyicmvx.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtrmsgilrh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gtndhqzcfp.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gtqnniwflc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtsnnjpvhg.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtrcmralmk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtxeqbjape.html


<!-- 参考信息 -->