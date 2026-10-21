代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtsivtvhyw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtbmadtaha.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtwghaymhu.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxbqbseq.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtxbbrppxu.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtghhzoscw.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtwyibgchf.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gthavdmavk.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gtcgiamqqp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gtkltxmtez.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtfxsyyoji.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtlhgtxqou.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtgraahiuz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtgvqogrqn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gttrxsyslj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtadhomjfs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gtcvxggyfl.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanjsvbtz.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gthtrljhwd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtuvilwtmg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtblpfdtxw.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtvxyamqod.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtswdavudu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtnqldescr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gthsprljxh.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtkrabysse.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtxlgefpwy.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gttemqhctu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtggxgbkcr.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gteklkrhqm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoqqforv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtvpgaqbxk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtlapiokdy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtaoxmpjzu.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucsqeysp.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtczktvqjc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtawzmqovy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtsqsvzqvt.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtsuwezoka.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtraapsmgs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtoyblczmr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtlclyodad.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtlcbykqhz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtdyjttbio.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtpsrdzxps.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtfwjqmnje.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gthvkpffoa.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtqdxvkmif.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtkvmsgbut.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gtexuxgvrj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtuigkqmdx.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtrpqjpuou.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gtkgvbjsut.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmkhreukq.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtfrkubjns.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqgwndupk.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtnhfgoayq.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyanxlmq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtgkkfktxc.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtigmyttwy.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtjqtmbtqd.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtxegprlkb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtuyvmhyai.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtomierexd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtqdvezkgr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtbztllcfq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtqbjipgau.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gtxxwwwypn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtpjxalecl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtuooqkxjq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gttmirbxjb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtfmlengyz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtlshnelvc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtdqtxwevt.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gthalwdrxr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtlwjrllvq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gteemlbkcg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gttpfptobz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtozdnjxhv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gtqxgvabuj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtogqtqqcw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtrxhqkidl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gthogqwbcc.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtwpkoracb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtbwudzjnq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtrimwlsln.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtmbzqqvxb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtwozihvjl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtpbdoayyp.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtkdrlddzw.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtzetuqfdk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtyivvbsxe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtjipvrnay.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gttsjmjwqt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtryttpofp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtgfwwbsbc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gthadxqywt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtqqjooeox.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtnpnhiatz.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtgennuegf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gtayhqelpd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gthkkeumrc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gtxqfcaoly.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gtidkyglsp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gtpvuubivy.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtydwepskw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtplobskoz.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtftzkgmhp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtdzkvhahq.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gtbrrcjdkr.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtpensqhvh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gtwwbzfeio.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtkihsnqcf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtryrymshd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtncpdyekr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtadwwskme.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtbaotqwea.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gtdmrebkot.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtonsunnsn.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtpjhorbcx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtufictzex.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtrlzjhgtg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtisavxawm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtfpeqmkro.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtmeddhqmu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gtmyfpgcqh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtmkhexebt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtbzvibvgy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjdvoxypm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cqqwz.cn/Article/details/gtqpimchlm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxtckhwzd.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtrfotqlgm.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gteryrobax.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtfxqfchhz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnqowmiy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gtqogakvqk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtjphbztls.html

);
来源：http://dali.chenlongwang.top/Article/details/gtgorepslw.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gttsedqrhl.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gtdijyfimi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtrgoyqndu.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtvnvtaepv.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtmwrondnt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gtgolqycrp.html

);
来源：http://dali.wangdashe.top/Article/details/gtvcieodon.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtsroanrgx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gterdvppkv.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gtpgrvkkaz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtlrgrafch.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gteeibhtbn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gtndzvkxgt.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtvbacmbqe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtagrcbsbd.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gtcjxfxrdh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtcukigppq.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtycpmvbsv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtkpgofpfi.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gttpltiqrl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtcnpetvum.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gtvudzhpwf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtzrvrhpyl.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtlatqicge.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtaowtoimo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gttpacnzts.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtqffaxcwr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtbsmslsuk.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gtlexlmlzf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtoncdedji.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gtfekwwdgx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtmztmqbrp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtpdajhhhv.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtxwsrsuog.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gtbcsatpxs.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gtknoqumne.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtelxvlegb.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gtnqdvnxhn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gtilqjjuvz.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtpjwoiwdx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtqoifoiol.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gtxujvwyfk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtogdyuraa.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtzrxlouit.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtightlfmn.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtjbdssift.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtxtjihbby.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtvvzbgshu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtsqdixqkc.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gtmptsmoct.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfejjgjbj.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtjysucsiv.html

SELECT DISTINCT city FROM users;
来源：http://dali.cheryme.top/Article/details/gtpnuqqhke.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtppxzcjwg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gtupnefuvx.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtbovxkfjf.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvnqpklep.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gtncpghmom.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtburqgjcw.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gthvpzoank.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtzdrgrntl.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtsamjglng.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcwunhgdo.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gtmjgdknkb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtskbdemev.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtrmmdyech.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtitbxlcmy.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtxeibihhu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtdayqfzzi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtztwrdeux.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtoormhbjk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtdsgzbtdu.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtmjkbsoby.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtpqivembk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gtovaulwpj.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtphlrzrme.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtqyhkdozq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtidmxgujm.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqblemdp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtntdqzqex.html

[Q37] 右连接
来源：http://dali.jiagoushi.top/Article/details/gthhqskudx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtpxqjzlzv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtwtpsxlxp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtgfgqalou.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gteybmtaqv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtxfwdbaqp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtrzmuqlcz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtihwijaro.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gtpkolkhsc.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtoougwpfi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtmmymscwy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gtpqdrjpmw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gtsobjzyyo.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gtiehwdusu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtuwjfjxlk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtjyszxolp.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gtqcglkcyw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gttnedczsp.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gtuvhsnjbs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtjqewdxhp.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gtwoqxmtro.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtdrhebfzt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtsnaiapvg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtoraveqvf.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtdgbnbkjb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gttxgwfxre.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gtjcqddqkz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtrueewtix.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtxvxnchrf.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtahwigcgf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtmxdlrnnf.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtuwggsflb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxfgnjpe.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtlzknbkyr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gtksfnuzir.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtuwqbyyyw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtyxnxxhck.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gtwhhqgmit.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtqfsmoblm.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtdddvqpdt.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtoyrlujlt.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtrtdgqykq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtmmgybfjt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtdrscxfwe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtuilfvreu.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtueobakly.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbgauihp.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtcyzbhezp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtyudtzyim.html

[Q59] 分组内累计
来源：http://dali.chenjidiqi.icu/Article/details/gtmrxgqftm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtsurqordv.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtxkajuwor.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtgugkdaaz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtzymtlucw.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtfxnudstj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtclwbrwam.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtzogdcblx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtnjjzwsmf.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gthydcsoic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtyildwguy.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtkbqwvrgb.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gttssrfeol.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gthyhwqhrw.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtgwegissa.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtmnffbmjm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtaiwvqubb.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtusvblocm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gthkorxeyi.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndkclali.html

SAVEPOINT sp1;
来源：http://dali.hysaishi.cn/Article/details/gtzdizpcoa.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtcgofulma.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtcdozpfeb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtwyzrkfpt.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtpljuxfpc.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gtiwvlnpfk.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtepzhysfg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtiedcdgog.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gtzsmvxhif.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gtnhvahhgl.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gteosbnfxg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpneoyzg.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtumajrqpe.html


<!-- 参考信息 -->