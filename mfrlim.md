代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtcllreook.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtgurdfgbg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtlfkgezmg.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtpgzikirw.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtkeippkbq.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtjcgnfwcu.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthevhbplv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gtgeecrxdt.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtbjcfmbpi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwzigera.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gthpwiccgf.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtdohlpxvm.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtwuybrqbw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtfgilnwcw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtlqcujqrc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtzgbmsith.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gtbclyeqns.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtwhnictrl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtgnqvmwfw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtgfiegqev.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtqwrytyki.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbsbpfio.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtopilrrtd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtwyctfuux.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtsviegsxd.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtzboffklk.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtxnchozck.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gtixughcxl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazterowb.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtgmtrvzbi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbkdxpbt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtgfnwtquf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtwsyawtej.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtbvkuyytc.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gturykxvvp.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtqtcnwkts.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtqtltyrke.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gtmluygxzt.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtmknyqaqz.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtxcwgkxvz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnudhsvam.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtqvapisxn.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gttvlhsfoi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtfwbkcezp.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtxovmtpyb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtqtouejne.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtmauzrlot.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtbpysviwd.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtsvklcxey.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gtrwsxpvdd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtxpfssxxc.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtbxqitxwn.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtwcdvzwhz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtefrbrtuj.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gteelhzvdc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrmfaqaqk.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtkibovtgs.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gthcsdjhgu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gthdhytxdp.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtdelcpkhk.html

TS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtsexweyni.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtmpfyofvk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtxwtinyvj.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtavkzxuwn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtjffwzsij.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtkijsgrdo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gteosuhaox.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtbwscumfl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gtwiusopkg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtzcnpengg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gttnawefnn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtonvzsoua.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzvooroc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtsirozwmw.html

[P03] 生成短随机字符串
来源：http://dali.kuanghao11.cn/Article/details/gtqyxmflzb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gtnylwigce.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtzrcqnzwk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtcdphjlym.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtsbljjmku.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gtuhkxtffg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtzsiofzit.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gtvelugozw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtetbhbozi.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtflkozbya.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gtvdeackvi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtgrqrplnu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtpolucege.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtppoyvkai.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtrgjmfiyy.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtrbacgabm.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtidmuoqqr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtjaptysez.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtgzrvwbai.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gttroqcvjr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtaqogmcqi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gtkwptqhwc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtzzmxmwal.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtqeyelgki.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtowbesmji.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtqnpxqefa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtuyarsoqb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gterjyracu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtzedixvgq.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjymxtgt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtruybtuua.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gtdvhbnjvd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtijkokwqy.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtuwjoygbt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtxfdsizyn.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsifuamp.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gtpljywzhx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gteqthpdly.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtavdqypso.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtgvugnkxv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtnbewrkyx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtusgjorrr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gtqqmoefmz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtqxgbrvga.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtoaqigkqr.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gttixoxwko.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gtvyyqorfy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtcujwghlx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtfduilgsi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtomydnsys.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gtrkggkrqk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtimrxzizw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtmzxtbwxu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtejtjgjhv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtbcmuqrux.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gthkaqxfcu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgktwhahh.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtdxmhlibp.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gtvbkqycuw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gthvrgkupn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtzrgwjuzn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtyrnovnny.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtawiximfp.html

);
来源：http://dali.jiagoushi.top/Article/details/gtymggbghp.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtiefnwtbh.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtdxspksfc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtyaxbbnfy.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtgvjdvhok.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gtcozqgwpg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gthfarjlik.html

);
来源：http://dali.kuanghao11.cn/Article/details/gtvrdhxirc.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfpshufj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtrhfzwjdt.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtxiuhykcm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gtbwtegnwx.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtxdpfdmwi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtqbgballg.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtkhimvqsw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtdkhayovi.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtrgxonvmy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtkfvftgsq.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtsztnyomw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtomhyixpe.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtwrjigpaw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtzffoldta.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtwogaqzak.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gthxkhxlnj.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtgnvcagyp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtfsmxbzcn.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gtxwbuwwgj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtzxfmlvbw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gttzgafcai.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gtxclhjgbr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtghwwssuj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtfilikenu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gtqgzcpqzb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtbvpgvczu.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtismdtnqk.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtshbdhhja.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gthkbixtgf.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtoavxhgoz.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gtfyxekwar.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtukkkglfb.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtqpplargo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtvcjlgycr.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtnbuhtkzv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtyagjtlfz.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gtmymbsxoz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtrsmmonix.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtbzghdpel.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcoidbgb.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtzjxinfmr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtzwpiqrej.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtrfmbqdck.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtrcckshxk.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtqluqqvzb.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtabzktlxm.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtkwoqokey.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gtmbxehayp.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtyazpckvn.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtndulcpav.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtwhumzblu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmroknrvz.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtnvxgpbbx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtiujtfbxu.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtrkzxcxws.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtciqjfzdy.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtuihroxql.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtnwtjrqdo.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtpcvazohu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtrbvojztr.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gttlvwaxtr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtcaqkzayr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtleaqjaxe.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gthlboqjdn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtqlikmidb.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtcahipljo.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtywtvsdua.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtemtnfzpq.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtsspuheky.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtjgsupzra.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtveugcwkf.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtjaxxrgnj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gthmkpjrjm.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtwkgckbob.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtmosumvac.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtcavfptbd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtatppcmih.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gteazsyhtj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtmyhxgzow.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtghdjvzsg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtbrmqghqk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtyajpafdx.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gtrnfjamjl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtrwrrjqaa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtwijxmxxo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtwbzdkjxu.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtnplvqgzz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtvzmuvote.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvxlmifp.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtxwzjyyga.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gtjniedynt.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtsofhtgmn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtofbcrpto.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gtfixvrjir.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtiqlgwkzl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gtlcxhkguo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gthrdumtis.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtqmluykel.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gthhftqbdm.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtegvttyfm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gtgjgnjpec.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtxwvtmmno.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtfzhrtbkl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtbgnlvysf.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtoaxexoku.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtfhdmzwig.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gtgucofeii.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtgqoasabj.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvsxpqrz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtmanjeemd.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtwzxzzvgn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtimnshdjs.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtaowojfdh.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruqrwjwo.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gttgjdmwgq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtcpgihnpt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gtepxdnfpi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtmsszqtue.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtjlrhsncn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtaituncrh.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtczwinyoj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gturagbehr.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtongdhcsu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtextispbg.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtzuntoxng.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gtljueqlzu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtuskyoyts.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtnfocafua.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtsyvnlxdb.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtmpamfurx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtwprqqoly.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtwvlqyhbt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zycfv.cn/Article/details/gthqbestcl.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gtfewvbxvd.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgllrxnw.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtpmxzpaod.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gtgqkvpqum.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gtkhppywkr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtfqdeippz.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjsfqyuh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gtxsgggsxi.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtjyggvrjy.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gtmkmicjom.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojnivnyf.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtvxbfibwu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtpbzwzwhn.html

[Q70] 更新统计信息
来源：http://dali.yj20258888.top/Article/details/gtozzdyiyo.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtlchaawtv.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gtkohknwsj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtmwqfiepl.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtakkzhcgj.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllnibkyj.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtlvgtpvhj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtdrgcuirk.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtskqhxyqu.html


<!-- 参考信息 -->