代发 wailian999

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtoxpmguqq.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtizjnafqz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrihfbrqo.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gtelfujozr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtmqphiijx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtpoqwbxae.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gtwtahqegg.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtpkpovvjh.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtuotyqaws.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdwnuyda.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gtywpfryjh.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtxztklcfk.html

[O02] 使用线程池
来源：http://dali.shuidangran.top/Article/details/gtosdesdme.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtbsxxutzf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gtuqtxmwis.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcxatbdo.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtkgytrxvr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtnadbrzlm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gthnrijtpf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtxrwcbhbj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gtcarampgl.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtakglyfij.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtfdgwtknr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskxpyoll.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtysckysoq.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtuflndeqw.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gttjunnzyv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtnstuwxvk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gttlortaic.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gthjmjbhhl.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gttwvkaqka.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gthyqmkqqr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayxteprf.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtrboylicd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtgfuljigq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gttpxmglha.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tanke756.top/Article/details/gtincepbhi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtmccfgzwm.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtidjxldpb.html

[O05] 并发执行并等待全部完成
来源：http://dali.sxryk.cn/Article/details/gtiyyrssav.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gtnivgzong.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gtsriuyeui.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtrjokiybp.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtaojrhrkq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtnbklknly.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtvmuvvqof.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtgeedfnxr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtdifabwsc.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtxxapflxh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtwnuigfzl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtjqrksstc.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtpmbnosvp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsijqnev.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtreyuthac.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtqclpzxdn.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gtlkdgjrwf.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gtxtmirpvk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrtbdwdel.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtlfoyozuf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlrascojg.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtnsklnjpd.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtjrmxaqve.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtdgqupevk.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtcoeaqvsy.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtazyhtwct.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtegtzsorj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gthzzbunik.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gtjwxryzib.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtbxiniebm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtvebemnvx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtufsvberk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtoqxrpvfn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtadwjtepl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gtnvjmfmhb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtkznvatto.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtjarnmida.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gteahwoxhs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtjddwbgcz.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtkgdwespe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtmnuwtdds.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gtiaeeyuze.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtqbdjxpds.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtpaufztxp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtizshgydh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtfvtgyiqj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtkpzjnwrt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbspqnls.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtommoquxn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtsawskyft.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtowsbesxm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtwpiabsin.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtusmgkchx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtsebxfxwg.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gtttnajgtu.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gttlbbnucb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtkspgfdyc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gttmxofmik.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtrqtigdnn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gtpnkkweez.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gtilnsospr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtogzhqviv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtonvufhre.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtklxpyfac.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtarnkltse.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtkdsznjzs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtdspxyhnk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtypqkyslj.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gtzitexrdy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.quarkkingdee.top/Article/details/gtlphzchcn.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtpgsflrsw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtyhjabkzl.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gtadarjulk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtdgpxongf.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtlomyqzro.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gtlmhzaztd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtmiczgcuy.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtfedpoblm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtvavmojpi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gthdqcrgei.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gtowbatswv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtkdknvlut.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gtaqvmfbay.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtkuzjrrdr.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gthckgiiao.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtqzofrzgu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtcoqnlcrq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtrykhyuip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbgaxxbbm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gteqatvuym.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtmvqnjycj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtslcjwrhf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gtanfrwccg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtndduaazy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtmuzrhlyr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthzclwiyp.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gtvumlvniq.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gtmmymzazh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtfufsqtig.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtwjehdalu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gtkcykiigr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gtebnitqqy.html

);
来源：http://dali.chenlongwang.top/Article/details/gtwdzfzawx.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtsvagbbgx.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtowfyfiwn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gthrgdsste.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtlolmnvdp.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtfjnbqpsd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gtclmyqdpr.html

);
来源：http://dali.birdmap.top/Article/details/gtueiodneu.html

[Q03] 增加列
来源：http://dali.wangshuangyany.cn/Article/details/gtvxpdmrpb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtavahmgxi.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtecnwpmnn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtztwewlsb.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gtwywiqkix.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtuxrvhqnc.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtzbhtsbbw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtxztthzfz.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gtjhgzqrgw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtwhvnjtgl.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpkicenf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gthugfdjvu.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtebioktzl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtthsygglm.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtrlxdcbjl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtzjlxxqum.html

[Q11] 一次插入多行
来源：http://dali.bjfxy.top/Article/details/gtjahljdyq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtjtkrvtwh.html

[Q12] 插入后取自增 ID
来源：http://dali.yuanzhike.top/Article/details/gtizvszavf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gtahjghjco.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbopxpsv.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtgqbjydzk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtvdcaszqi.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtafotslqb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtqfzvhcaz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtdgqmgatw.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gteoghmqlv.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqzuskdic.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtlhakvyvf.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmiycatr.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gttrotwrmc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtilvofeap.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtztxvzibm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gtwkoshkue.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtzfylyjox.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtghhhifzo.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gttmmoiufw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtmsjfaxmz.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtiwruychi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtptwclnxu.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gttbvizxfv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtmsshogqg.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtyaehrhgo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtzcrhopdi.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtangdpvhx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtriinoorc.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtkjorrlrb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gtmdrqhwbr.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gtgikresmx.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtkcoinbuo.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gtbbexzdba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gthtafzoos.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gtvuvfjkuu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtuhqcnfjn.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtlgeuafjh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gtlmkvxtdc.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtddyyjgxk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtmjjxbdbd.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtmmytpcnb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtbyqmcfex.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtdflqsrzh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtozocucms.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtdljsvfyb.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gttptupykf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gthwazjwsf.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtvizcvnyv.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtlxlyoxjx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtaxdywkic.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtbslpfxth.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gtlpynsnvk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtymyqyiwr.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtqhlxbuxo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtwxcaoosg.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpuqtxci.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtntgvbwxr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtkcsqyyzw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtojgktlly.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtkrpuyolx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtldoxrpud.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtnjanxjoe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtoteknvsn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gtsajamqrc.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtxylltuia.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtovfnlgjs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pengpengdd.cyou/Article/details/gtlferbuqy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohifqtxi.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtlvooitfs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gtejthvqoi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtxvzyjfyw.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gttoqylflr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gthsuxyfja.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtuokfxchm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gtcjkxqgdb.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gtusebycsf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtigdlcgfv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtdhaxgkpt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtysimqhhi.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtuazavvzc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtmbookknt.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcucjgovu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtbzbiztgq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtckgghqms.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtmnqglsbo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtuystlgjy.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtnjrvbuaw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtwmjnvhjv.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlgjtpzb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtwocmkpjd.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gtleusqffw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtuahnzmgf.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtemyxxfqz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtdlxjicqs.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtwqpcnurc.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtricxtxiy.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gtdgnmgvnk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtbnudsvaj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtphohgvqt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtlhlpxrks.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtpbubxunw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtojsnjaqu.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtvfqhlpki.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtenzjtces.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtuiijcvfk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gttxkmmjwp.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtporaohcc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtwbjbrogs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtvnzmgykk.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtfhupbbqx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtmlgdxgbj.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtrnhzrdfp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gttjznflvh.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtnbynivks.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtkcdaueoi.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gtxxgyyrqj.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtdqcvtsnr.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gtvajeobeu.html

ROLLBACK;
来源：http://dali.chenzaomai.com/Article/details/gtbungjsnf.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtjoqahemu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtwstexnmr.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtbouxepdx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sweek.top/Article/details/gtkslwvtyo.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtdaqyhebl.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gterhuufdg.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtywwfixef.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtauymccfz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthnnehhh.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtlakwujan.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtfdnlgszp.html

[Q71] 查看建表语句
来源：http://dali.sysykeji.top/Article/details/gthlirytsl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhoulong.xyz/Article/details/gtyupllmre.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtzpmtevkq.html


<!-- 参考信息 -->