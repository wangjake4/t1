代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gt2kzfrlynq.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gt2hcbsxkis.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwwnoiqt.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gt2ibdhdwwy.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gt2vpsibkad.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gt2aitqrkqp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gt2egfooajr.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2ubwyldiz.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2yvagfwlo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gt2xwcwflfm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gt2blxlleak.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gt2fxmumpxr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2irfbmlso.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukwweocl.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gt2jdnrytqf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gt2lgoghjur.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2ausrniif.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2yfbvtnao.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofavgzbr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gt2woqiwbud.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gt2hipepfjm.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2astzvvav.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gt2lovcxyxq.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2ytylnabc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gt2rdxhuopv.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2priaryco.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2baeptbfu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhytyurg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fbczsesw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gt2dpffktov.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gt2mqdmnrql.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gt2irrbvsuf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gt2aoplbfbl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2nkfxxgul.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2tnxlxqge.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gt2jzmcjfml.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gt2npctdwwm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzfvgsvu.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2tbuljftk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fijcjkfq.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gt2hdselogr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gt2iybxzwmh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gt2xjiqlpsw.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gt2dkprffbi.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2pseaxrds.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2gpkankwy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2tnqvyren.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gt2eshftrcv.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2ujzdtwuc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjaxubad.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gt2eefmenkt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kxswjput.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gt2nudncoby.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzoejoiu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2lxswyhxy.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnpoguno.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2pbsdnpvl.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljqwrybo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gt2dakxagib.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfmbhydj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gt2pcpbwwnk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2ssqmzfcs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjhhzbge.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gt2zyryismz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gt2nemlqonq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2mobwdcyh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gt2lpnmaxtv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gt2zlrwhzcp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gt2uwxxyuta.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gt2qgffleeh.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gt2ftucbjsd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gt2thvpgrvc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2vbxgywgm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2nvurmsvj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2szepstxa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gt2xhohrxaq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gt2hcdlicbp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hdngbpcx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtceigwm.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gt2hhoywpdz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gt2jhpvbfqf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2ndexxtfs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2honsalgx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gt2txjzqcfl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gt2arcjxefr.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gt2sibcodce.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gt2lguxdxis.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2qdeknety.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gt2hoymtfck.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gt2gmfexmqc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gt2cdskvekk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2qzfueoic.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2zmfcganp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwbmzerk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2txfgyjbp.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gt2guxhzqak.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gt2fqkjibwl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gt2qcrmexbz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpxcboe.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2oxzvfjza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gt2nvrnfkkr.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2qvflfcdf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gt2wpmxblvc.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gt2zypjbafc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gt2wsehpmyb.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gt2bgbcxxzu.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gt2xhlyixoe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gt2krkjvvld.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gt2aifbyjjy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2cndtekfn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkucvikk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gt2xssbmyub.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gt2ijwerfuf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gt2kxidqvsk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gt2givepsaf.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gt2tmnsbigh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2ybozkkgl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gt2bbcorpis.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2dzenbmsw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2deafdmsj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhrwvxst.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gt2objspzoe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gt2gamifphu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gt2mhtjulqb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hjmcwdpy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gt2nfbzlsmp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zohatnev.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gt2monfofqy.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gt2qqfninda.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2dosautti.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2malkbwxm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxzhdfah.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqoxvklp.html

);
来源：http://dali.316326.xyz/Article/details/gt2pyuqmnxf.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtudpghc.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gt2uujucnxr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gt2errxhqjz.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2nksslgkl.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gt2wffmkkxx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gt2eqxpnmsu.html

);
来源：http://dali.jlsjyb.cn/Article/details/gt2ksewyvpo.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gt2iofqjbcm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gt2rjuqibns.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gt2jthyatqk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gt2zhrjqehe.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gt2uopfgpva.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gt2ckzrnzht.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gt2pktoutov.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.meibo888.top/Article/details/gt2vcofrexh.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gt2mjuzigwz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gt2qvldkkqx.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gt2pflrdqzw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gt2vcqmazji.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gt2ftyzwgem.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gt2kwduzvxp.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gt2pyetyryq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2dimwfrau.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gt2jcjasjhs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2untqatgu.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2kvjncrui.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gt2zycgelht.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myumtcoz.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gt2ycnexorc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2edxfotaa.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gt2aslokcih.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gt2jtametqw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gt2zyokbkkl.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gt2ayspeiel.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2sojtkwsg.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gt2oqxzonqb.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xngutztb.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gt2jybqmstj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2dltttbzz.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2qcwbuvwu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viebxvwe.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gt2awmbjirx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gt2hhbsoxxn.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gt2vhjmnatw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qmtypyjl.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gt2xideeihq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gt2wetzfaao.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gt2agocbtsr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gt2sffayvbx.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cexrxoqw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gt2mjhccqhd.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2scnipbte.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2gafnqoeh.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gt2dffyrvkc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gt2ntgrmrmu.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gt2omjxcael.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtkibiio.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlsoizst.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gt2xmxepgdx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqrdrvr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2jajpsfdi.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufzcfmdo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2wormkrdu.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gt2pzcfrdsw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2djvnendp.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gt2djatjkvq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2hjzgmqna.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2cmsjgbtf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2okkyfzhj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gt2dsawnyqh.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gt2aebycetz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gt2vetbrpjg.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2skngvphi.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gt2ubliuhhd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gt2saidvuxd.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gt2cmufmszl.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gt2iqxlgdgq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2vtpvgsqe.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gt2pboojmdb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2jqxrglza.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gt2crmtescd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gt2fokgifkj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aboezygi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qecjkabp.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gt2pqykuyvj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gt2mxedlmxu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gt2hnejahyk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gt2praqozfd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gt2cwmcgqpm.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2ycsuhfps.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gt2vthotjhm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gt2sdgeiuav.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gt2paqqyklt.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gt2ytgrmjtb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2cdskynqd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gt2tzmrflfj.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gt2twtrmoqo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfwgvve.html

[Q44] IN 子查询
来源：http://dali.shzxlz.cn/Article/details/gt2chtaofuk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uucnvqnj.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gt2jkwhkrrz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzzujzuk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gt2eqdkdbhv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2jmaqrsfp.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gt2lyagbpus.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gt2npkqxgkx.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2jhxhtksx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.mhx1999.top/Article/details/gt2hzevcfwj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxrzncb.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gt2tzimbicx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2xbcolroe.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gt2ytdpfetp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2kvraiizz.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2oruuikjp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgcfqlwv.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gt2jbcbkmhp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gt2rcpcviqa.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gt2gmsdgifr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gt2cqklgjdz.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gt2mdjhdbzm.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gt2yqcsoprk.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2jlrzlfja.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gt2osrptmbz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gt2vagamnzq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcusowm.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gt2bwmilwom.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwtyxelj.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gt2fnhetzhq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2xzmpetnn.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvmoftth.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2bzdniotx.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivqwichi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gt2njxcoeir.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2fdetmgpj.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gt2fflgzdba.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2yxzbqqzi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2okwnffpn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmxlnrin.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gt2barmkklc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gt2ihvmensu.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkggyywj.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gt2vtdswxer.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gt2rhuddlbc.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gt2xmrpbvrn.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2jdvhmckm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gt2gqeoatnq.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhukniib.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gt2szncxudv.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gt2olumvqat.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qycqgkzs.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gt2mouuroym.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gt2cstgwagb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gt2thqhameq.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gt2nrowidtv.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gt2vfnaotvz.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gt2uxwbywil.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gt2wwcdkvou.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkjcbdhx.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2msrsbbmc.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gt2qebgfwhp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.haohaochexian.top/Article/details/gt2hduuldac.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gt2qsayyavd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjsjugll.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2mddghcvc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2fgtjykgr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gt2eslzxxnq.html


<!-- 参考信息 -->