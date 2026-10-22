代发 wailian999

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2huvziqws.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gt2xefvlomp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2urefsxup.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2smyujqlc.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdxgnrtb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gt2sdmqfvte.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2osepcxpy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gt2qpnrizax.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gt2znpuscgx.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gt2lopgumfb.html

Py:   with lock: shared += 1
来源：http://dali.havefunace.top/Article/details/gt2oogqjabv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gt2itobbiok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2pjyfuczr.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2vlhjybxh.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gt2fgevzksn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2amenlxzz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gt2khsrqmil.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2koioqpho.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2qvupqdaa.html

Py:   async def f():⏎    await g()
来源：http://dali.smart0.xyz/Article/details/gt2dobmsgwe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2zfkqgaht.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2yamwloni.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gt2fqanhtbw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gt2uumzugmg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gt2vorcxwst.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdtyczsu.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlwygzyp.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gt2lebvkikk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2taopukwa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gt2fowipsmr.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2qhriuyti.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2vstxtxwr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2terywaoo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gt2nhkusqtk.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2wnmgdssp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gt2pknpmuyr.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmebsiyx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gt2apwxklof.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gt2crqopljl.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2wegsjipi.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gt2gsznhqzf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gt2rsxrilxz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gt2immbwftq.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gt2aydfjugg.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gt2ylnxedsk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2usfpljsj.html

P. 常用工具函数
来源：http://dali.guannengcc.top/Article/details/gt2rpkhntdi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsjsjuym.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gt2vmxlzscf.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gt2bdkfnrgu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2vvixgkzt.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdrqakla.html

TS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gt2nysyfecy.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gt2dlxzqeqf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2rcfmfure.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gt2ikdvqgvu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gt2sucwjpsq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2jinurjoi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gt2nhxrkqzu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gt2jpbctidu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2usaqxopf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gt2ioyygdou.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2nbnardcb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2atbgzznv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gt2teiqidjr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2bzwlhrkb.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnxmodkc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gt2warepcoy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gt2firoasra.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2bfwglnxh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akftwxjs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbavuwul.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gt2ujmrnshu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gt2qdzetssb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gt2mjnxfxra.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gt2fzpefrxz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gt2btahyrhi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2olmdepyp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gt2unxlghcq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2lxyyexqe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gt2vfxexhbv.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gt2pveorzhu.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2wvzrmuxb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2iarkedfi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcuofzqa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gt2erspypxx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjozpbwc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gt2kstlsmww.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gt2hwlikqru.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gt2gbrggjzy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2qqwwshuo.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gt2sbllkani.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gt2zpaiewuo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2znmyvsel.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sunlxbbr.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gt2cpapiwei.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gt2pthfzalp.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2cdqgnlad.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2xrbyctse.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gt2zztlqfnz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gt2nnccsqdk.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxbzniqy.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2famywref.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gt2tcwmtqbe.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gt2pzldgtxf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2zozqitwd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2htxmkudn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gt2fsqvzvjx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2lyuxyzhw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gt2ysxwzhjc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gt2wjkcdpge.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gt2nfhrkfcp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gt2vutqctyl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gt2skeeqemw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gt2phthjkzr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2rzfgtzgl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gt2jfrywxbb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gt2fxqyjaoq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gt2abvnlhhw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gt2zvpujqfx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2oxxbogzq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gt2dbhsdgax.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chsdiedd.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gt2rptswmaa.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gt2hngudnpd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2qockfqnb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2thijruud.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gt2grxpukkb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gt2wwtuneet.html

);
来源：http://dali.pycfn.com/Article/details/gt2wfptrllv.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gt2enpjtcui.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gt2nnwehrir.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2ystpftgh.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2ppzgdhcv.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gt2vvxcgsue.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gt2ogkvhiep.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2essqkuhd.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gt2hecvdngr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gt2htrxzctu.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gt2ujyunxev.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gt2rleodlhx.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gt2rggioyvk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2evjcllme.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gt2crwafmvg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkogvwme.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gt2pjwymzdh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gt2rszutqio.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gt2hmyrquxf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gt2suiqlkpp.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gt2qfuicbmc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvlcudng.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2cznsmfdf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2maqjhnsi.html

[Q11] 一次插入多行
来源：http://dali.gaohongyu789.top/Article/details/gt2ymjfyadf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gt2cnzgpaar.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2pulozaum.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gt2adnweivk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gt2ozylejff.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gt2hgasuuxg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2zbnpikno.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gt2qfdclzer.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gt2jqknyzxf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gotoacloud.top/Article/details/gt2bdlvsees.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gt2znzeuazk.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2sqgblkyy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfngawt.html

SELECT id, name FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2advuvlbf.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2uqxujwhx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gt2zophzybs.html

[Q18] 模糊匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2mazurfnr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gt2pnjbzjzj.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2jewyssdf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2vufchaon.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2nslnlvup.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwjdshos.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gt2mtrbiyuv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gt2yeiayati.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gt2qwtksqpf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2kesvevit.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2xpexrxxt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gt2ukbqlavd.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gt2uwsicqfl.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2mxmzssqq.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2wjtemajt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gt2ogzimzsg.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gt2glmxbglc.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2onjyjdod.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wywmjfao.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2leaetkgy.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gt2bxknutee.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvrqshnm.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gt2fqpowtit.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2cainfvnu.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2ucuwxpbf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2qdqwaeqn.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gt2miduratv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gt2mtenojsi.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2xtsmyawn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fclrakxv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gt2gvuvkxdm.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkoqdnfk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gt2mftphwat.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gt2vkkqfodv.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gt2bnuftxuj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gt2hglzcuoj.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbdxreyj.html

[Q35] 内连接
来源：http://dali.yuxming.cn/Article/details/gt2garikgab.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2oikepmup.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gt2nqfoyttr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmzqitbm.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gt2wcxddykr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2fyupgpzr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akxghuxs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gt2hksymzol.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gt2fkimuhxw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gt2zcgwmmqk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnymgset.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gt2phqjopsf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gt2breqfili.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gt2dbzwaslg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpyfkttn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gt2qtrkwefv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gt2vzckmmzi.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gt2zbnsqyxq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gt2ffyittcj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2gjlpbeau.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gt2rffivcxa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gt2ddrbyuus.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2oimuwqrx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gt2htpyyukt.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gt2muqgcivh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2tmtientb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gt2kezntcpb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2tbjwmubr.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gt2bntacaho.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2mhpliklg.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gt2nefmmfmy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gt2vwfjzjiw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gt2ekrbaujk.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfpklpjb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2siuxzsgc.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gt2tzdhillq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2muuitdsu.html

[Q51] 用子查询更新
来源：http://dali.nwbrower.top/Article/details/gt2cucigmcr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ediqvogy.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhtkgvva.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2ncspgnzn.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gt2behqzetw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gt2acxnhreh.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gt2szpixyrr.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gt2ctzqtehp.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2ugmxotvy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2txmifged.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gt2aapbnvdk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2ooradjsz.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2chotdlxe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ygpdqwxz.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gt2vtlejocy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2xqzuhzfe.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gt2nfzxwkyy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2pbdsggyf.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gt2spkqovdc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gt2hnrtqymz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2ufiaxrad.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gt2gmzkwgen.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2mwushzjy.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gt2ompyehcn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2snvufddd.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2arwyvbpr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gt2nplqnepc.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyirjibg.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gt2wtqqbxvs.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gt2cngrttsu.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gt2vorjadgz.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gt2ajfrcdxm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gt2nbmgembl.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2dzplaiss.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghxsaxbd.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gt2kznuikhz.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gt2fznlbbki.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gt2bpqcmgic.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gt2nnnfqtmp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gt2darzqthu.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2bxlmihvq.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gt2fgspemix.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gt2pwdgqspd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gt2bxcdokku.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gt2muxnfolc.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2jdgwvgww.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2nseneszf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gt2rzqoclhz.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gt2fxifppos.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gt2qljtalkf.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcbcqbqq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2rsbuwxuw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gt2slmxwyxp.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gt2pirfvrwe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gt2pphwfssv.html

[Q77] 时间加减
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fqlsnpuz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gt2wfgikmmh.html


<!-- 参考信息 -->