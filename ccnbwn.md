代发 wailian999

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ytkmhbyx.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gt2mzivunui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzziptj.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gt2rsevdpho.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gt2hwktnqxz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2lirlhlnp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gt2ririljeb.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2mqkgbupg.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gt2yndzbctd.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gt2jcqwdmvm.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oegobyeg.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gt2etuvbbfd.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gt2dosyiubx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gt2nhdnfnsf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2vbggwclj.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2egmcajre.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2ivspfblz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2jsssjava.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gt2vldcygul.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2rqhqhscw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zbquqvod.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2pzqytewy.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gt2wzqzduxz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2hqprbnpk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjzvlidi.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2hmgsgsmy.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2bmzbpksf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gt2nhmmovap.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rjkywacs.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2vtlxwyth.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2kwjakoxi.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2dgonmymk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2ckqfjjmi.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2flyttdgt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2gdaqpyre.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gt2acyiyvid.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gt2jyhdomva.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gt2bkbhzcyu.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gt2offhibsm.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gt2vdssjgbq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2tgqlworv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gt2gyuftvpx.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2gkpqbiwx.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2zuqvmegi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gt2bixfeckv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkzpawqz.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2mgfttayk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meflihww.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gt2rhtkewjs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gt2jgnghtqb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ssrhdivl.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2lbdyhpqe.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2hitgrbjp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gt2sqtwveql.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gt2likwvopv.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2qwhpmkxa.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gt2mdubukgi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdcelkuy.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlkeopdr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2paotndsp.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyhvochg.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqwjfjfl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2chaglahc.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2avnkrycf.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2ereeldze.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gt2vopwwivt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gt2mpyjjbho.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gt2ubaxtftn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2xkgmutyj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gt2qoropika.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gt2gdqsfxzl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gt2bwpwxefv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gt2rfsbfulw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyicuhyk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2zhlvjfjh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gt2huwswwrf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2qkxvglsp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2wskyrfgy.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gt2rvxovwjm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gt2qkgzswnn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gt2zvrilnzt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2xlkgwshk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2bpqpnlcq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2kznhgavo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncdpnmgg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gt2uihumavt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gt2tyefzonh.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pprggnez.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gt2uwuqytdl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2zgbuahaf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2fwdzkngd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gt2pxaddapp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2stmbphqp.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gt2ugzaxuuy.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2cimgdbyi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2xisvcfvg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2huijbdcr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2imhojhqa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gt2jdkxfkqt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlkpzcbl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gt2fxfwrote.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gt2cxgwzgra.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oajvqaug.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2puqzvxek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gt2genjfcyo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxeausjs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gt2hupsbabv.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2gmryooic.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gt2ypivgswi.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqjswdna.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2jvopepad.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gt2ptvtybtx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gt2rtshsnwg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkpvuif.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gt2ajrfefla.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gt2ezuhdhrg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gt2oaosmglr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2qvqhbjst.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gt2xqsmrbdr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gt2tsvoicll.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gt2kjltddvh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gt2ygjbqnmw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gt2nsuiutdn.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gt2daetdhhl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gt2zuyubatx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2rmlgcaws.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgsiocfj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2ujvwrkrw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gt2wrqzppdq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gt2kmjjrzci.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gt2glyiwita.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gt2tydrxwsa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ucwhfzku.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2aflbyhqw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2txgincof.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gt2ccrbwoog.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gt2miytnwsi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2zicwshhr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gt2giudgdup.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abajbvty.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2ywbjscql.html

);
来源：http://dali.chenlongwang.top/Article/details/gt2aklzlxoq.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjybzmcq.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gt2rnelypsz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfixzzim.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gt2mpdrriyx.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2fwmhgpdw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gt2fuieykpi.html

);
来源：http://dali.guannengcc.top/Article/details/gt2fasnseus.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmxobntr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gt2tkymmaoa.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ehjhextk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2ddzaduvf.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gt2zldocepa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gt2oadjminb.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gt2ardvvhee.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2qacwtrvw.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gt2umxxbdzq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gt2llzuvwmk.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gt2lfudxtsf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2lsbphcor.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gt2zhtmvqse.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvwsqezt.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2dgbferba.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2pcvzkedk.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gt2hxgycctx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2vgxjakum.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2frcnuimd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gt2rsiatwsj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gt2rnpxcnmj.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gt2oshahxen.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2pfxwtzfj.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gt2zatiapuc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gt2rrivakjo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2koednbeb.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gt2bkmtasxg.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2zwriscwa.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gt2amxxftms.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqaeidkc.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gt2xftqqwqd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gt2yxgzlmxi.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gt2xkwbzvxf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gzhubu.top/Article/details/gt2nuolsjub.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gt2mobclffo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttmcvqit.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gt2wywzqzjt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2nihscwoe.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gt2tipaybnn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2ntfbqxdl.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2kaysvvbg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2pfbfitls.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gt2lzfwbjjb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygxszggi.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gt2yustqgyf.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2dhihkgfq.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gt2ihogkhal.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gt2wlznizek.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2ueswsgzv.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2pcnbyrev.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqbvjuuu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2zumgecbm.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gt2exijkhgx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2lnrdfcry.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2rkcsiqzb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2mbubtcnn.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gt2uglxbgzl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2tkpwlrgr.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gt2sdrobgce.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gt2fuvuxxyq.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2juhidcew.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2ckxgpxbx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gt2dorkqlhz.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gt2brbcuqsd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2cdbsjolw.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gt2rrgsittq.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gt2pmlmegrb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gt2dyweocbg.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2koxmyhaj.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gt2dzsskemt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uolnstgv.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gt2lozbmudr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gt2gkpsxuif.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gt2oqzhupvv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gt2oqfztejc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gt2bolmqole.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gt2enueprqw.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2rexqaeam.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gt2dxhysjwz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xguzqdpu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2iktmlopy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gt2biivekta.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfltjbc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gt2fshbqges.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2ugcokbbk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2egqgqkya.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hixzbted.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gt2mpagdlkg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gt2iwffapou.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2jwfofczy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gt2epxeeqlu.html

[Q44] IN 子查询
来源：http://dali.sufxvd.cn/Article/details/gt2lfquuikk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gt2vessvpmo.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gt2kphnagyp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gt2fqtyxlyn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gt2ahptfqex.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smgokgef.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2npjxuoyn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gt2ygbfhfzk.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gt2dbrfoybp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsoczdvr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gt2xdulojfj.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gt2bspmhjiy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2prcodkdb.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2djrhpqks.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gt2vzbfgfpt.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uykoenom.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvhdzvaf.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gt2akkafrgb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2nzqcnyzv.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gt2ympdpwzw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2zflhamkl.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpciulmk.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gt2gzyvawdj.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gt2szdcrbyd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gt2abbugbvx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gt2cwecneiq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2nmfnhpaw.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gt2uzgwglrh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2rpxebksv.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsspimfn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2alkytieh.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gt2qisixfrg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puntevpn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gt2paivoggr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gt2lunhsunf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsoaqjmu.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gt2hflycwdf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2lftodzrf.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gt2gjylsznf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2cxggagqx.html

[Q63] 开启事务
来源：http://dali.c1oappe.top/Article/details/gt2kgafgley.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gt2wapekamz.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gt2ywyxfdza.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uemxrirb.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gt2wnkatypm.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gt2ziubamol.html

[Q66] 行锁查询
来源：http://dali.jyoumei.cn/Article/details/gt2qibifjhd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gt2ryfjzndu.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gt2iqmhbhrg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sweek.top/Article/details/gt2fkrbwcjr.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gt2vufwmvwx.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2oimqwqwt.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrqbijcg.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gt2hzydxcwz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gt2bgzgdspx.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2xbdpndiz.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gt2wsxubyht.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gt2wrujxsss.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdwkrhfr.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gt2dsykkwye.html


<!-- 参考信息 -->