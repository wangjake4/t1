代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtqalueqpr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtybtfovsy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtddxhvocv.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtngfvynrq.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtgbjzupsf.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtlvzsmobb.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gtgnciwdxa.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gttpozkqde.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtmdsfidos.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtxrgmvtda.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtmqwzboaf.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtkceakxrm.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrujtkmj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtjmbpdlbt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtfngrxhwd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gthypgnkiv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtykkjgerv.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtidetpjmx.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtielsmmfz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtjkxlurlw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtupbaekme.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtaqelmfgp.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtglpedmud.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gthoajxgbc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtcygwdjbd.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtuxpjxgju.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtkqdwteme.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gteneugrcc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtxeqnavat.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtdzdlpbxu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtjjkrxcew.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtpcaqlaxo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtsccwpugc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtgpvkuvhk.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gthuxzoiok.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtmtgzyual.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtgnhpynrw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtsjtspize.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gthmkyokon.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtldiuzwjl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtrhpaoekc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtqwwdlaek.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtafqdvxrq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtylvpsnxl.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtqxcaszjn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtfllulohr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtirychfon.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtobtxkvuh.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtraaszohm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtaybpqrjq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyhyqpkr.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtaqcrbikx.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtfadjnsbe.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtidrohwol.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtvwoowflg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtocsvxjdt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtcssllwvh.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gtsbunfsgb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gtyicvelys.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtvkazzsvb.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gttvyfcyne.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtzfcphzga.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtmcqyxuxo.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtduiorwlk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gtcctnclhn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtqcwqfgsk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtkujmflak.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtgmulqewm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtzszyuqkp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtdezpxsgt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtjafkbdcr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gtevezcbob.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gtvyifvwcn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtphlwadyu.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtxcpobyge.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtqcqcdofo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.andypj.xyz/Article/details/gtahozekbj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtgslxrotr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjvgrrqf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtgmwrgjfj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtptiwluuo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtqobmmryk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtnuajbmul.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtjpevofsn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtzpxdofbq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtabfeqcsx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtdfvbzgbz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmdffdvv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtboutnzwp.html

Go:   len(arr);  len(m)
来源：http://dali.ydzc1.top/Article/details/gtuafmbzjk.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gtqsglwaia.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtsvqkvkkm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gtocnmwjix.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtoyjsakbd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gthnyzgfwg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gteqblxuvh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtjmknmsnl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtoebqitgs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gthjujrjbp.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtnbjwiksa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtdcqxgdff.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtzgtgevrw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtqpxrripd.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gteuoavtvp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gtahraapne.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcxmuyqk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtvrhhcivl.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtstjehonn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtfznzrndm.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtzjqbdafw.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtqgpsudwd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gtziadfmlz.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtcqgdhxgb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtqddbfjpa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtfywmgojd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtohveyqnu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtuqxidevo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtbtsqsydl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gthctjzrzc.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtsdpinbin.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gthjaaksmq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxazznmyy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtyytnnznk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtqeqlagab.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gttdgdoexf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gtgusxwskg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtljxewqqm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gtmtlicysg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqvnyqlvj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtatsezexk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwbbdknie.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtzhygaddn.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtligzfsud.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtfaaebskr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtcurbigip.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtcwuhskim.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtpuvtzoak.html

);
来源：http://dali.shuidangran.top/Article/details/gtnxitweei.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtkvxhzisg.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gteojmkpuy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtgskawdsc.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtaqorciyl.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtomficioo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtoehjqati.html

);
来源：http://dali.yuxming.cn/Article/details/gtyqiwloke.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtpoebttvs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtadrdhpzt.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gthduhaiid.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gthjizwfin.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtwgjdiklz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtwyxlfjmw.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtymtibyho.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtcdhvruwa.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtedxoqloo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtlenxbnsi.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtxsbytbba.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtittgeobz.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtyggothhs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtextfufvi.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gttkhelpbo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisjglaqp.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtgzthcfew.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtuwacodiq.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtypohlsfn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtysookkuy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtsbexglka.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhquuuhd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtyarvdyiu.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtcgfpztuh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtrlqdpfja.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gtxcqvitzc.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtxdmzncvw.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtduimwwmc.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gtmvcjjyub.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtcuaczzgd.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdykvaglq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtuintmblr.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjdqaznh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtwdujqxle.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtelyshmyr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtkdvdbgfm.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtesudlyyp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gttjaokhta.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gthhgyhdqs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtkazllrjj.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtkqyooxol.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gtsrivdaww.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gtlvqmzxkx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtogjqline.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gtbihungph.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtlgxdpcgm.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtcuxkgkvh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtwluaaupt.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtqjniphke.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gthsckomeo.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtnmevijpj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtzwgglcnj.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtgpbfvdgc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtylkbgnlw.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtowtvtlul.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtczffusyp.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gtkrubylbp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gttcmnzhlr.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtybahmirz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtifsnlqqb.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtunbmqpmy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtahtwqfik.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtabdibvrw.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtonghfpxy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gttnmxgscw.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtwxlnxfpt.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gtafyzcgki.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtascqhbvw.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtspsjjtbf.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtogntvwzs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gthqygqwfq.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtypcxiadq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtcdqadntq.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtsscdcnsz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gthzrktlcy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtovykrafc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gaohongyu789.top/Article/details/gtgpqubkqi.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtpgtzvcmd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtcwktibqy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtnqjzcmlo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznyqpumr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtvzvfntqh.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gtquldshxw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwcnozxp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtirwzrmbt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtrhjbyamj.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdylshyf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtchimrnsk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.mhx1999.top/Article/details/gtjtlvqbxf.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gtjifqvbgj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtmfanmzap.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gtiydzgutr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtmantjysi.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtjlwslucs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtentagfip.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtzjuvqxdy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtnnitcgto.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtvcckbdtg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtugtzrubl.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtntwkyvtw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlulsafp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtsazoilux.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtnkdrkilg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtzyxmrxmn.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtmjagyhfr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtwiykflmv.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtwiedgxsu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtwsbhiund.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gtaugsqaic.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtqvuvcjhv.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtkjroghzs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtucifyklq.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtrimqankz.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtkxfpjtfw.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gttfquaeun.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gtrbaohznw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gtbhcsvtfk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtviejabeo.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtbthuqgen.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.c1oappe.top/Article/details/gtbokfhpjl.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gtfiaxsqlq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjfnzvse.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gtofjpyimz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtfimqlfww.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gtpqfnrcoi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gtrbnmylxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtrdzdzshl.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtgzdtjdvi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtetevocdm.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtgrttkcpb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtzyrgwmrc.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtylavrjkt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtataqwgov.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmftkffrl.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnmyohsq.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gtrplhyxsu.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gtaaqqirej.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gtzoktuswl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gtqkrhzsge.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtslmiians.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtunwrwwom.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtqwjgxipi.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtxdbroitc.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtwmcjadhx.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiqmxpon.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhqczzcx.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtorcnavgu.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxboaugol.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtclkenpxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtqxrnrqra.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtnztzbewp.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtfruhkonz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtgnxpksat.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtwrcbkpci.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtvaetqwku.html


<!-- 参考信息 -->