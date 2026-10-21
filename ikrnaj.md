代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtsjfaicjf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtifaarnkv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtjgwdagxl.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gttdfnjdor.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gtorzqazps.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtshmsufxw.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtuxuhvirf.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtwdpzuxpg.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gtjieztseo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtawwmqgco.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtxvangttb.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtjsftkywl.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtvstfqebv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtnrufrvos.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtsrvnwvfq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtduqqetzl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtvmozmkxm.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtgoqimscw.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtwfdibqzs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtwbgpztxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gtinterrwf.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtxnkqcydj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtqzmtgxln.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtjujdksth.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtthkaaaxr.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtlklurjyz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtakxmdjca.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtgkaniqzn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtwyqhgcoj.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtkmyydcxk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtqjglwqvh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gttlijskco.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtmjmlznxf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoewryjut.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtdvvjlfbx.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtziqrhlxy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtekzjenoo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtcsgvjrsp.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtmaetstfo.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gteivkbbzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gthbwxrzlh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtqnubpbim.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtytuaiyla.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gtopmgmnsn.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtzdnqbguq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtgyuxcrmb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtgrdhwpte.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtihkcvgvw.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtfsixdwkf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtgvqbskza.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtvltwjkjf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtlhfdkzbz.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gtkydmbauk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpmdgbojv.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtvoowtnow.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtibdqaydr.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtuiyolhnt.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtuelbrcrx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtbpciooaq.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtfwbkhtno.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtbhizhprt.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtkqhydpwe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtzdiqrgsn.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gthxkdyuzc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtpbupqafy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtcqjkwjms.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtqlkemyjr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gtpqorohub.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtsexacuxp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtjmidepxb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gttacbhden.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtqvrhlkvw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrpanyqj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtjlmceank.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelcgfxeb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtwcbtsjee.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtrckjzidr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtgkoysleg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtsfxlrvym.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gtigckouhf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtpqwzvxfa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtlhvptjln.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgfrdcwe.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gthwlqlgvc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtyrpditud.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtytwntanp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtxqnniuxg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtszrdsedv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtntvnthxr.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gtdyyrlwjk.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gtwryvlnjk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtriejmotp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtsbpegyou.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtkoholywu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcovhngui.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshdcmbhc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtbkcspkgf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtuxcwwheq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gtbxeyssde.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtxmgugyzi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnqosqrl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtzczcznda.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtkktofebn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfszykoci.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtlqzqenjx.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtspndrwqi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtskbtuzuj.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gtxwchlfox.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtajnseekp.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gthnaewyvi.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlusridec.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtomznyrdp.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gttlwxqdtl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqdstrub.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtdspnidcp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gttbgmyiei.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtkainzafb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gtutpbzemy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtrldrqzsi.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtqcsuykpp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtxqowufgb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gthtlcatvi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gtoxggtjcv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtqghrtxcv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtikhfszct.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtggomjwvj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtjpfdxcei.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtijpseuye.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkitmyiki.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtqiwzntyc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzyrrxmlt.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtadnqykjg.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtwuqfzirm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtlkpkehwi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtzlwlevob.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gthtjhunie.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtksagowyd.html

);
来源：http://dali.yj20258888.top/Article/details/gtykaerfkj.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtogogetnr.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtsxdlxayx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtfywrzqvn.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtdcjsfhwl.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gtcverbkzb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtcrnvyuya.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtaanpyusp.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gtnfpndlxq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtrasorxse.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gtgqfdrdbj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtncfqdguw.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gteyohobep.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtgqlrxiva.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtxyminjex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gtnuewqkab.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtwrpszgfp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtxkgwrzpb.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gtfoyxjqbf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtwryjbcop.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtmhxadlyz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtkgkasiex.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtjmujnogm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtkzkikzdx.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtmjvvyjrc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtnfjsamnl.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtsakcnevw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtqnvazldf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtjxadysix.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gtigheefen.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtfenozclp.html

[Q14] 存在则更新（upsert）
来源：http://dali.hongshengwenyu.top/Article/details/gtogizpmwz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtdsqsgbie.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gthboozzhq.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gtdzwlmkty.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtobsnwqml.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gtixruirsb.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtmirqykiy.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gticbibltg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtmqyfvnpj.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtdnjuykta.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtwsoumlgu.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gthpkehvvj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtmmyffxar.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtgiqppwxi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtvivscdtc.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtcthsvpdu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtftrjkvrq.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtepyhiglg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtttlzglxg.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtyyvgcvxs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtoufdnpvv.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtbhtcphbv.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtxavskwpb.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gthvdizhdf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndlgqatz.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtpeesyjbj.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtpymzavow.html

[Q27] 条件计数
来源：http://dali.shuidangran.top/Article/details/gtbndmubod.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gtziwhkcsf.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gtnuicbcvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtsophivqv.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtlpgydxrp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtdsbyaorr.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbstiohpw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtdbomqsvd.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gtkdwxxpfd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtllnaudrv.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtmcqzmswl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtktdnearl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtdazrluut.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtqrdzxwww.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gtkxrwvrwe.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtyttjeoxb.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtenpkmmvx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtyotniauk.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gthsymunfm.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtjdeeofwf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtlmmipgzt.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtlswkpkav.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gttwlkxdji.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtuoiuqxwr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtypilzcyv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gttruzfywd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gteugspunk.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtvjrnvsxx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiztgonb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhrslwnx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtntfdfuho.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtptiiqffe.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtjgvaaebb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gtxtrjwcmu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtgnvxaqix.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gttwlawohl.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtvshgeqgn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gteknqarts.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gtjsmxjqvd.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gttlibmgbz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtvkxdoyoe.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtunonjrbx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtcprgrast.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gtqpbujgdi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtwquvfmnu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gthnnswjni.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtvstgykpi.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtvenabpuw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtampvykkl.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtfvqweynh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gtbrbzwexf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gtwwkpqokf.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtskchijmh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtmiuxijff.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtknulbqls.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtbezpmeeg.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gtcelfjaib.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gteplsqjib.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtbyqwwlph.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtonafzazt.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtzbltfghq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtwyehrqtv.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtlnxhqztx.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtzbkmkxvt.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtgvignfgu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtrxrhisht.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkywlcwk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtyghyrdqp.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gttrkooqjv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtyayzyvbo.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtkdyzfvcl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gttlywomri.html

[Q59] 分组内累计
来源：http://dali.hfpthk.cn/Article/details/gtusmcpjvy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtgxfpxnmr.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtpbjrysyx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gtrzeldxgq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtiirpfijr.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtqmfityrg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtdofacrbv.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtfbmbkhoj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtvgbzdtsg.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gtteszajyc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gteypzcyjk.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtbmhokkmj.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtxxfiiqvj.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gtzkkiggwt.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtwueynhqd.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gttekmzehf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gtjyzoqpqi.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtlgwmqbar.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtvwirevqo.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtxmftcusn.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtkxhleoju.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gtnwownlih.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gtgskvxwzg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtbajhhtcv.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtwawgzlfq.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtytfxawpo.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtvgevkqjj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cdnleiting.top/Article/details/gtdcpshgjc.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gtmbfsadwh.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtntryzepx.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gthknnypsd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtfuklrkdy.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gtwwcijpom.html


<!-- 参考信息 -->