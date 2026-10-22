代发 wailian999

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2rzbqtila.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gt2iohnqjnf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gt2garbzoxu.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2ptgsmoxd.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2ioimscez.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gt2mnzvnmop.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gt2viujrdqm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gt2jbvpetvh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljpsrwkd.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gt2bakqsciu.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gt2ocdzqqli.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gt2axpbkgap.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gt2vsoovngm.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2jsvvezoc.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2bqenjxzw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gt2bpgvesmi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2xswupxsg.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2fipwcqtj.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gt2eivxxptq.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzkkoiah.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2cgsqzlqq.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2bhbdgcfb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gt2ccjzvonj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gt2tbqbfshy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gt2ezrqoiip.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gt2edvhibxz.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gt2ujsbgrhn.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gt2uxahrxng.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2cxrlhdnh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gt2qxtdsjxx.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2ujswvgcx.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2wfffufcm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gt2pagodmgp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gt2qnamimwk.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gt2dtslxjuf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gt2uufluzpe.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gt2efcvwliu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gt2nhzewove.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gt2btcuoxzr.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2jrojmgal.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuwkpoyj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2vjgiurgb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gt2jozwwtoh.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gt2dqollate.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gt2rmurewbq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wknloopg.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gt2bceeqhal.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2sywghris.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvanexve.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gt2zwiezkcn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gt2hmcmqcoi.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2xkbqnbpl.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2yrmvextr.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gt2qhelffhs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2erwytrug.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vcpxixjc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whmdxqsn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2zyvkwyow.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sepcgrej.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gt2itndiprt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2bzbznxxx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaeyautu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adwlxizo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gt2eikapvwc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ccloknmd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gt2ldpfpxdu.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2fvcykmkt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gt2scasnknw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gt2auhrjlgx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2quruvuvr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2ftlqzhkn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gt2prqmkcoi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gt2shbheorp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gt2dqjahedy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gt2myttwkgg.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gt2zzhkugih.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gt2eetfattp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2vwnstscg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gt2ltzecccu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gt2nfzmsmxn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2lqizxoln.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gt2guthqwla.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gt2qevioraf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2daeddvof.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gt2mkzyaecb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gt2bjcihdmc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gt2bprgbqww.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2pxtpbwhk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2osvojhoa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2sklrnhtw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2svacntgu.html

Ruby: a == b
来源：http://dali.dianchejie.cn/Article/details/gt2yhkbicyw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2kcaislfp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gt2ffcwsxuq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kurzkgeq.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2wsiubfft.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gt2tfzzljqy.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gt2hqdrxdtt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gt2pvctyrda.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bueowqbx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gt2ocuhtyqk.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2hgtwxpfx.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gt2tktmpjxk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gt2kgiyzkvc.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewkezmld.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2iwvaidmu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2qrndfmsg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gt2zzzvtvql.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gt2amxnsbhe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2slbbctqc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gt2wpepqvdb.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqqblsdz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gt2jhlsdaed.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2scanixtm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gt2gocbnhln.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2adcxtyeh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gt2javfsear.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gt2njgksczf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gt2nborqzmx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gt2rmlpaezb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2oeargkru.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gt2qsqvitwl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2eplgdoex.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gt2umbvthmr.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gt2tamiczmk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2pmuohgae.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2jduzahgc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gt2crdmpzbk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gt2xgjkqwow.html

);
来源：http://dali.birdmap.top/Article/details/gt2lgirdggi.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gt2bilhpyxs.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gt2lytkkpew.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gt2kakddkkz.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqwidqjw.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gt2juwwjvry.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gt2okwfagzt.html

);
来源：http://dali.nwbrower.top/Article/details/gt2ztqqcyuu.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gt2qnkqhhik.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2sfgkukdw.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2chovwsvv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2lphrwxze.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gt2yynjpyad.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gt2qxqugqcn.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2hkmvpcic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gt2moitqwea.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gt2kdjnltmk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzsndwgi.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2xnyunbet.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gt2zkkkmuxw.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gt2rygfhshg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2pfvblhuk.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gt2tuehoavz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2ofujggfk.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gt2qbkycdva.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2kpgvhkad.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2agjfbgxk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gt2zfbzwxxg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gt2haavaabs.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gt2fuxzldrg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2gtmilleu.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gt2jffrsjkk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gt2tcnjokdm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gt2lwhpinda.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gt2hygkcpgq.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2numisqvg.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gt2zpakcbft.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2ryaqtbga.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gt2fjryamto.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gt2hyscfuwu.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2ukxijlyb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gt2udzorger.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gt2fcbevnni.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axzfglbv.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gt2mvraltpu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqthkpqn.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kabgewcc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2qyusytwc.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gt2qmjvfurm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gt2zxqgbmka.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gt2jdndrciy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qezvcytr.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gt2gmgdjiom.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2wleugvdz.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gt2ashelbir.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nywcjjas.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2sjjlcaka.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2krfowmzg.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2psmdpewu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2vnfldnng.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gt2ddyzabrs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2xrijqaxc.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2rohdnwip.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2qmmwckil.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gt2sbfveckr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2wrrxxkce.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2uyliogwg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gt2simdaoaf.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2bpyhrwdm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2stmxhttf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2optpmkzo.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gt2nbbjezet.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgtgclgq.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gt2jqejnizs.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gt2yakyyquz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ppjwa.cn/Article/details/gt2nazuqtxj.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gt2wizcohsz.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2saeimumj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2eiqvcqrz.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gt2fmlfwjsa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2rfdhialg.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gt2xpuqgzab.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2fcnbfync.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gt2tibsrxzk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gt2ibevzlak.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gt2gzmbsaho.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcinfedo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gt2yhkffkew.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gt2pejwbisz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gt2aakfqesd.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gt2gvhwouxu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gt2ypxeuvoq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gt2vcufbwxr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gt2xzidkmdm.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gt2slrsvzco.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gt2dhnruvod.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gt2esbeicer.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gt2bmfrpvxn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.feifeiyinyue.top/Article/details/gt2unvqhzaw.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2rzpezmjh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gt2nhyebimi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmyyalgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gt2rzxkjvsn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gt2hbpzqger.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gt2knmynoqn.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gt2fkqzssui.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeheqcwd.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gt2pwlgrlvk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jyoumei.cn/Article/details/gt2htbnahjg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.meibo888.top/Article/details/gt2guyadiuf.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gt2psmcgmsy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrvimphd.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bybqvmvc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2dtmcjyhv.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtbivkrz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2uynfmndu.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2bqmtxift.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2tdyntowo.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2mogqkgyw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2raylomcj.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbpujuuu.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gt2doguudrb.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gt2tzqhlaoo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2nbsgupan.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aizwys.cn/Article/details/gt2dszemzen.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2ijhmzosc.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gt2uenmywpl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2onzpxajn.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gt2lwgqzgcl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gt2zhmukaxb.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gt2nmjodcoe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2zckaflrg.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2umwjkhtv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gt2ntkpwxlg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gt2vrtptzmn.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gt2gbingwqr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2rxrjpcan.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrnewjyp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2ietsulcy.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gt2rwzxfxoy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2iqebakbf.html

[Q64] 提交事务
来源：http://dali.guowangkeji.top/Article/details/gt2bstozfub.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gt2rkjpkpga.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gt2acnifbxf.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2xuontvgq.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gt2kxzgsext.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gt2arqeqpzt.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euryotxu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2kjuiujtk.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gt2zwgqvccc.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gt2xdqrisgb.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nseoldre.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2flyshusg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2yklexbqd.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2atajdcwe.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gt2zieisqhn.html

[Q71] 查看建表语句
来源：http://dali.aibaodan.cn/Article/details/gt2zbtqttna.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gt2eisnindm.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gt2hygwlpow.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdsmblhg.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2qtijkzdg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gt2bzctsows.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfnkinho.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daria6918.cn/Article/details/gt2baeylymm.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2nfgmnlbd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvvyagon.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gt2wvjvnkak.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gt2sihgeosx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gt2zwdvizna.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gt2ealacwtg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gt2quepyicd.html


<!-- 参考信息 -->