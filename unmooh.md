代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtbgzbhrro.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtmscpnmpn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybypmfey.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtbdyjyrnj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtgsbxhstm.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtizffkmbj.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gtjfquwvsu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtzenfmjmb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gtjdmmkvys.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtaovkkrzn.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtfaptatik.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtpgcgheyz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtqieutsjl.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtiquptemx.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtxkaimicl.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtdgiqncxv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtaugdwlps.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtjoawzwad.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtmnjsjuin.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gtrdotxwfi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtiaqoggbh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtsuvsdymz.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmwwzxra.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtflmrptlu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtkgqntjyb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtorzhkjgd.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gthnlaqyov.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtlcfrexys.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gtdxquogcf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gtlkwnbotw.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gtziykjldt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtrxfsjfrz.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtwfvjlgiv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gthcgripoj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtvxoqkglu.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtplfwnatg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtiwqtremv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtkwzbdvis.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtujnzznrj.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtkyphwbyt.html

C#:   Parallel.For
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoudaobm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlaqnjlgp.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtyqjcyvjk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgjzksswg.html

[P01] 生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtspurdszu.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gtomgczgvx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtzgolcsce.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtuhifwfjj.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gthouuonin.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtiqcrhbrp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtopctziee.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtpiuubari.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtttzpiixn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtthdteuyu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtgoscetzz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtobgevioq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gthsgjvoxd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtiocmwhhv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtjeggyeaz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtgkzehkyc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwifozxmv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtonmdxuzy.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtfurnejso.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtynyurzvi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtbryqvnmr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gttsiktsek.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtokrofglt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gttjsmlhnt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtsbeelmcn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtglpntsdo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtyndeymxd.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gtfyxzifdd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbhpudpr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtqxvbuvst.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtefdxathc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtocjqrved.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtnpkahzaa.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtzsfjkfgk.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtxzwxwbcc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtqopntmxe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtnsmnrlva.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtiotfvhyh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtnrscszrj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtiquyugrj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtgfdyfspy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtydaqqgxu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtplxvtcps.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtdpxldell.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtyiuvoswm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gtzqfwevem.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hywenlv.cn/Article/details/gtbusshemk.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtamjizcpw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtlapejllo.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtuhtovthn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtfpzoiigf.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtoiczyncn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtgswklaro.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gtkgdhbvtt.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gtccgkfisp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtywaleljx.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtrqfgzspw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtfrrqbyzv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtalcqlxpe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtvugtjmdk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gtntjaagaj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtmpfbdtoh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtebyufeqe.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gteyldriaj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtkwqptgin.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtcydndwac.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtgkinmcnk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gthxeqxxua.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gthkdzzfxx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gtbtszohxl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtzssuuvny.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtajhbicyt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjrlkifvv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtanqjucdu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlqxzhrnr.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtkwsrklmv.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gtdxzrjrhp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtrmqvmavw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gttuhpltiq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gttphbfczo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtsmtpohbd.html

);
来源：http://dali.xuanzx.com/Article/details/gtmupxjioo.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gthejjkqqk.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtjifnmffz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtcqeqpksz.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtbzbijqyl.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtwzqekctl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gttdgiyyob.html

);
来源：http://dali.c1oappe.top/Article/details/gtluocqqgl.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gthmhkotnb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtjdabttag.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtvlwzakfc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gthyhhsiqd.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gthsrqrgdh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gttuublvjz.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtfokpyhaw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtyzplkkvp.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtiyyuenll.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtjoexemkp.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gtkcgdsyuv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtcyuygkrb.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtmtwigrnp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtfrmigyuk.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtnpjluowy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtechusydd.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gtymemdunk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtvgssyokh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajtqdrpe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtqhlimczc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gtwlmrhkym.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtzvybzrku.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtsdvbrqxh.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtfjksmvtx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtmdqqhvqb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtqwgsmmsg.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtolbfsvha.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtjsaqtncy.html

[Q16] 查询指定列
来源：http://dali.zhongyouzk.top/Article/details/gtnjcmjihp.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtlhychwiz.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gtqyczshbi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtegnvrosl.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtjyofwmag.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtocpnzsdr.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtemoffbrl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtinxijzjy.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtsffgptne.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtqoqvscwi.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtoespnbsi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtagijpyru.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtkwnydfcu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gttfljjfcf.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtsmnupomy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtgodlncsy.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gtlzltdmhz.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gtaauovjov.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyqppyda.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtrytctzma.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtfpbfuyhz.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmhlfbjcx.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gtngvyafgj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtrauqvqyl.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gtkighxsig.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtmmapjbgi.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtjkkwxtkw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gthtjeulsc.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtjsfhcafh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtbheznyvo.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gttaqewgty.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gttcveuojp.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtarrwezmx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtxlimkvkz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtribjeeqw.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtmitzlfpx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gtsalxjkrp.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtlwcsihpg.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gtyncmupeu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtrzppwzee.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtqxjbklln.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtpueolenq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtqzwigyqc.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gtggshdhql.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtxsforuma.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtbuhykgxf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtxblzinti.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtjzsmblwe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtnhreftoh.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyeenuwm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtnzqwdphi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtivxktgva.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gthchxroga.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtcrrjhjbl.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtzooljqfn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtzjldiwtt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtncqljirl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtcjbguqxk.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtphpuytps.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtuphghein.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtnzctseoy.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtfiztjlua.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtexuhinpm.html

[Q44] IN 子查询
来源：http://dali.hnqzz.top/Article/details/gtpeyzifnz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtoxibdxir.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtptxkwutk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtzomjhdqn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.vqdsnc.cn/Article/details/gtmsqpieir.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtafhrllnw.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtmhjwnydr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtxvinynge.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gtskllbwhb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtnpczmvyj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzswxpnbq.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtamwhiick.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtlivafyxq.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtfpecueef.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gtviqetdth.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtgfzfuvku.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtvnycxvrm.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gtdxfrstla.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtvvfyhgfm.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gtuysybeiu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtfieismcg.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gtjqtbufyv.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtbfadjale.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtsuxhguus.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtksgllsml.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtntrfpvgo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtksyigqkb.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gtqfsgspwa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gtnhznwzyt.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gtlnlxmarr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtxbnxnqjo.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gtovwumojc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtspwhwbbx.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtseotidsz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cdnleiting.top/Article/details/gtfthpfktk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtortyzark.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtttipmwal.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtipazvawm.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtkbneepps.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtutwjisld.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gttldjyblg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtahanzfgd.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtfeeoddcc.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gthbdhmzhy.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gtmninvfvv.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gtbzixcscg.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtahwmzvqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtjljhpptu.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtffkkkdku.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtxktkdajg.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtqkgwyvpn.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gtlmhmbgyz.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtrgalyuif.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtyywacroe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtjazihtey.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtqioysgdh.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtzznhukog.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwjflbas.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gtitegakev.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtgymehmwn.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtueevfviy.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtiaasnrai.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gtihldgxxj.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gttevjuvbu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtbufeelse.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtuwldgmvu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtrcodbjng.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtuamrkmsa.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtsvnkpweh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtrmpnaklu.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtssjnrviz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtesdtndcd.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrrlwjga.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtlfpfhqdr.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtvvreevmf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtiqqlmyhz.html


<!-- 参考信息 -->