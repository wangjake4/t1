代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gttcfrhvzb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtdcoxvxzh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtktxbkeya.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gtljzofiet.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtzdfzlkvi.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtxloppant.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtivpiewut.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtbyrzmwqk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtwuqpswdz.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtiivibboe.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtuoqrzjya.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtryvrsjlw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtlppeispi.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtnozoymks.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtgrtqdfyu.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtarebpmcv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gtkfkaelhn.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtfgpxjnyf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtlanfwilo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtbeobnsbx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtygoytghq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtxqdnnbab.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gthvnjoxvq.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtbysyrxyj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtdqdoqacv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gthntwzbes.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtbhfvnlvr.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtfmsrdzws.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gterwrpezc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtncwceigm.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtplroadsj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtlchkmkuj.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtkhnkhloz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gtkrmanlyk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtwxxozvxy.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtzqmdlyvk.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtgosqhyqb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtykbmzmsa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gtnaqgqbbp.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtwfhapsre.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gtidjtunhi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrtavzyib.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtpfwxoncg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtobmkcciy.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtzgrnykrx.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gthybpdwhf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtinwpsawn.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtudytthjk.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtyrnildun.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriloeflm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtxyndxceh.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtpegpzpgp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gttohbgitr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtlhtuvcwz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gttgzwfwhl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gteiwucvgt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gtpcvjdefd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtsulziter.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtcdcmibxm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtfgqqmehh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtobflremy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtclqusudy.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtuutomdvs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtlrhjkozi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtyruzfcyh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtmjlfpomt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtmkkiwowi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtdxchwzgu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtzlnicmnl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtuanemtkj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtxxtswoeb.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtnnfaaavt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gtutrpsqhm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtslafquvf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtkbntuzar.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtyahjbeur.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtkrklawda.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gthugzopqv.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtvqpespfh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtdjewiunj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtfyobeysj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtbkufnhig.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtzrnicccc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxcacykt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtlcbxgqfh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtfrhuptzw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gtiebqdenv.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gtpqlfzhzr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtvwxqoygg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gtdfvbtaui.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtvkcgbcms.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gtrotbxqfc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtbooznkpx.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtgwqrgaop.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtxorggmml.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtajumhyks.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daria6918.cn/Article/details/gtprtgjzam.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtrvbpweai.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gtehphutkc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gtoipnydxp.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtelhfwvif.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtetxsmsxg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtvkggyfad.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tian-w.cn/Article/details/gtjaccigcx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtiahryzvm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gtsrgpodxo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtoiloltht.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gtlkketray.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtylazrwos.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtbuwnocjy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtnlpxpsus.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtmordvylm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtcxbrxgvv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gteycrhkwd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtuvgzutwq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtdnaqnjpz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtelojtuag.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtlqgfouot.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnxcdwpbe.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtskewomon.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gthzkyrdzf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxntiniz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtyhcnarnh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtdvyfmluf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gtrmbuouho.html

);
来源：http://dali.aizwys.cn/Article/details/gthxaytoij.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gtlxhqsluf.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtdddgnqqk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtkrxreofq.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtjifpmmhu.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtlibkxpez.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtbwqyjwoe.html

);
来源：http://dali.zhoulong.xyz/Article/details/gttypdkyef.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gtanhcwedh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.havefunace.top/Article/details/gthulqsxeu.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gtxercgnxo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtrelbntum.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtkkaaaxeb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtwexjzhkn.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtoyvcobwc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtkqnodjyq.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtipqkowrb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtpdbmdqvj.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gtefwqmtie.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtpefvkscx.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvuispxh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtpyqcncne.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhhrhgta.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gtwtehuzyu.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gtyvjbmaqh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtfrtkglei.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gtckwnhqpc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtyyikxflc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtpmlnhepk.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtlphjjejm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gtrgfofdle.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gtysnctgjj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtjtcvymmz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gtwqijydqo.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtczcolbvv.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjqxtncrf.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtiqrxmnrd.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqddlbxam.html

[Q17] 条件查询
来源：http://dali.chenzaomai.com/Article/details/gtrijmwqbz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtjufbmhdc.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gtzsyvvdsr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtxxdvguux.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtxkomoztz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gtrwpelptt.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gttufhtnwu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtwsaxylps.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtedzebvif.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtripovzdq.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gthptfczup.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtvjjfzpjn.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gtnaaqmvly.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtnnvhynkp.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtydayncwx.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtgqxgnwmm.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtijuxtaqp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtimlfsyyn.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gtmxdqxtaw.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtydcqqznf.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtgvebmdbf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttbehxkyx.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtkrcuthla.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtfxvkdgng.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtedwgbvxv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtszwlkiar.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtalxemgqs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtgsqxtrjp.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjglqstvs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtubrlbpbl.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtjsrabnki.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gteivjelst.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtzqtlaqrn.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gttsoxagdk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gtmwygkxkn.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtyjehotlf.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtrhggigol.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtyzepzrwq.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gtvnpjoibk.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtjsnjzgeg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtgwmfit.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gtmewxjaya.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtfiinbzqg.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gteqcjqspu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtnsxvgddo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gtckozhysi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtbuvmivws.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtwkvvtvjf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhkrbjbu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtkjywhxcg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtprhfexid.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtuekbumqt.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gttabqssud.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtoitqxdrs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtnzbjlrhd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtglqbapfp.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtrfxejekj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtfpdgcaeh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtjqdgeibu.html

[Q43] 标量子查询
来源：http://dali.tian-w.cn/Article/details/gtdhjsrwhv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtnmciuscr.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtbgypwynb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gtsdqwrjwf.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gteeurksuu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtyfoezdam.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtyyfmarod.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtrsmxrfyv.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtojkkxqit.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtinhfzvmw.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtftdvubeh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtiobfiawm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtygaemefo.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gtofqusevi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gthgylhfvz.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtgurwfrsp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtnfrgfmaw.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gticyjkjiq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtlkqmlbvs.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtpbnvficb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtapxfzytq.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtmlywwhzw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtdfdnwjsd.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gtsgwajsoj.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtylnollnf.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtltappilh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtakhblskw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtykmjjqtd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtwdksuihz.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtlfmhrcbg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfjjhxkdr.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtjjsjkpsz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtagllvdhj.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gthrpfmrfu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtgftdfrvs.html

[Q60] 取上一行 / 下一行
来源：http://dali.cqqwz.cn/Article/details/gtkiovsozi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gtjiyodbti.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtxkcmwrmz.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gtcytcnbtd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtpljkjnye.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthzsvhzc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtgeohhoqu.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtljesntmf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtajgreami.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtopngcoiy.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtllvcvbnt.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtkvoafsgg.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtmelhryow.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gtrrjlquni.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtopnaelek.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtrzkiqsoa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtxqjjvcnk.html

[Q68] 保存点
来源：http://dali.yonumen.top/Article/details/gtkvsivwuw.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtblbqawli.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtwqsxrqty.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtwodrciru.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtmesbrman.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gtjbknwcck.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gttcoldvwr.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gtcakejqpl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtcrjokyhc.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gtaavdkptz.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtwrdubbhd.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gtqxoouohq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtarctdcks.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtregsycta.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gtfvsroaai.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtzqtbnlhw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtiuxcyqfa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shzxlz.cn/Article/details/gttejbgxng.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtnqvukioq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gtgapxlfuo.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtlkznrxca.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtzfpzsvor.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtkywpcysv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtekjwnmef.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtfgsywjie.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtpsiriycj.html


<!-- 参考信息 -->