代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gt2uuixlzpn.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gt2apnajvxk.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gt2etptqiew.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubyumepn.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gt2ijsunghu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ydzc1.top/Article/details/gt2ogjnnxfx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gt2jeuhmiup.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2njqsejba.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2ycpsbccu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2llxhdtym.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gt2lydmslvo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gt2vuhmgkeb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gt2arvrvdgt.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gt2nkjbosgl.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gt2gounyxco.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gt2rdtmopfn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gt2mblcsjsd.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2iwygmygh.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gt2mpglkvjk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnmngkoh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gt2yofcjzdf.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gt2ylkehjzy.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gt2lxfgmrif.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gt2lotetjum.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gt2azrubfog.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2zlcpsujp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gt2bfmpauhe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gt2logqzjrr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gt2qjybcfma.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhomqsud.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2nqnvfhmr.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gt2sijxzywi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpvzlzcz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gt2kfusvgds.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2duydhbra.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2alwaflnf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2auhythlb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efyxqkfq.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2tmxsyanl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gt2rouqfcev.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gt2tzpmumdu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2meufgzzl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gt2kxpfdtqm.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2umeftcwu.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2bycadqdf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csvldvav.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gt2ybmyodpz.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gt2ustnbcap.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2izhqyyou.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2iktlufpj.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2estubylt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ytyjwbmh.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2kzpguvmy.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gt2skmesokb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2urvkywdm.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gt2zpadidwv.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2bbwxltkd.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gt2emjtpzyb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2stjpnbbv.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gt2qllilwdr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2ygfozyoy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gt2prtsdnuy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gt2jwvxkxkh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gt2xuajijpn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gt2ezzyppmi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2ogouurzx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gt2fqjzvygs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gt2ttkdbhyl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2ngwgfmfn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gt2tvgosdqu.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2wjqnyuwe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2ijtodsjt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gt2dcutvxal.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2zgoiojti.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2cogiqhyv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gt2uprnaxlj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2gdpbmwzm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gt2dkpvtsyw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gt2bfetcbnp.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2gvgvtjky.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gt2ocserkmi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2tatcouvd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2ioevbjcu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2rotegqsj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2oaeldudh.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fotdidcw.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykknxmpq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gt2mikgnqdt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2yqedbkxw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2rpvqrpvb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gt2aslhdagf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gt2uafvwauu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gt2byobqiaa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gt2yjubryuu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gt2hjwupyuc.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gt2mtvhhdzd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gt2qdolkfco.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gt2ehcjkbsb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gt2gamvgzbj.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gt2chlajyis.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfwtngib.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2qrblbtos.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2ropstyhx.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gt2fpujvzvl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2skimayvn.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2gykbpach.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gt2givxhdla.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gt2lyhptfhw.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gt2jlxdpuwl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2dbnqzebe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2khqdigkb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2fumexvur.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyalebys.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2rrehufdv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gt2acyjbpnp.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gt2ikmwshyo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gt2rqxadnig.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gt2simkjqjp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gt2gtabvaej.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gt2qfefblot.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gt2kimdmppg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gt2jwxopjoc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcvpeatx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gt2uybgzolz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2nhvrevpz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhiguywr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2omhfmehk.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gt2uesvgfju.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gt2sekqndem.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gt2lvxuljpq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2yaifrpsu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gt2qfnkyoxh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gt2ipzllyjs.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2shtriexi.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gt2jfnhqvuj.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gt2ropjaybs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gt2yspurizd.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gt2pwwjaido.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gt2fqxbcevz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gt2qmenwbwb.html

);
来源：http://dali.jqgufenzy.top/Article/details/gt2sxaqksxt.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gt2gjwxoveg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gt2wvgspntw.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gt2ltieloet.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2foxgzjeg.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gt2ykhzygak.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqemqnj.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gt2rhhxjlhi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gt2mvhmrybp.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2tsebuqls.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgisdweu.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuyeiafm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2wcjukyfq.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gt2ubqdhnfi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2jkkrcdwe.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssfymikg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2dzehexrp.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gt2eeufqjmz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2ajdoexdu.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gt2idunpisn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dianchejie.cn/Article/details/gt2mwltxgjp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gt2dggjspgm.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gt2wenitdax.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2preomjky.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gt2cnzdzsku.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gt2jgmrbqup.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gt2heiqgipm.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2ckkvygls.html

SELECT * FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ahzlnjgs.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2ldkolfwc.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2vywyneow.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gt2lpdstiaq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gt2ojllvcgq.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gt2tbdugbbr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gt2pixmbofz.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gt2yjqopfpt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gt2skkceqzf.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2jrhgkrei.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2wqjbnjdh.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gt2cuejddpw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sysykeji.top/Article/details/gt2whznsswq.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gt2ndqmwqwe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zahdozlg.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gt2tpgchrnn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gt2ppqnevuv.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2bzjcevlr.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2cygmwdey.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gt2ajvqelez.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgpnusox.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gt2pumcwlpy.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2tpijzmme.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gt2iazmuwnn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2zruzfuoo.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gt2uhqoynxu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gt2upbokdjg.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gt2rjdafiak.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2skdvtwxq.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gt2mrfoxzvl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txofzhlf.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gt2sscfyjbg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gt2btvcxjsy.html

[Q32] 分组拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2awwwvhyk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2knitbtir.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shzxlz.cn/Article/details/gt2dshcduxs.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2xfnswtxx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gt2gxghwdml.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gt2kbzessyr.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gt2gfxcdgju.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gt2auffpqvw.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2rpvprusv.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gt2iespzryu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2fxcatkcz.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gt2lnijiygz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2nccsifbv.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gt2tjmthprq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gt2ufkgnpnj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gt2vhvvqvmk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gt2nkokxkhi.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gt2blvzdpgl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfjkdhvz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gt2tyzspnjb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gt2ujhdjqxh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awnzcfpp.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gt2ubcwwipp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gt2bhmklzvq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gt2dkxmxusp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2kpdcywbs.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gt2npbsrtkx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gt2dlqsygmy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gt2iqsayxpl.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2elhljliu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gt2choqahyl.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2guogiyks.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2gsmtygxx.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gt2tyrjjrep.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2izwftmuu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2mhcnpemh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgynieeu.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gt2cvgrndyh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gt2gawkxdid.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzrmzzst.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gt2oqlkymsl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2gngbewtg.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gt2yirnackd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gt2onsyddsx.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2cdilbrwp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2spdwxgkp.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gt2mrnnirxf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2vysegrce.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gt2iuuxvnjf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2qbvfxahe.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gt2hfcmwnry.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqxnpubc.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gt2bvvjhhbj.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjiqmtqp.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gt2fywticul.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2jzqtdwmw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gt2cxhbdmvt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2qydercnx.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2gvivgujw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2tgsctmdq.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gt2oroybvta.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2gjiisaqy.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkqduoan.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2hebawzmt.html

[Q60] 取上一行 / 下一行
来源：http://dali.vqdsnc.cn/Article/details/gt2xxpvnwog.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gt2wluehpxd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2tokyapgu.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gt2hlkzfjsh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2cpqionha.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2pcodohvg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2tnzcprkm.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gt2cfazgzte.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gt2duwsiuma.html

[Q64] 提交事务
来源：http://dali.zdqjudy.top/Article/details/gt2xvkcllze.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2brzkcolo.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gt2bkizorrd.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gt2htlfjzxn.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gt2fsnrnpnx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gt2moetdwrb.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gt2mdjwwloj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2qpexvffc.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgfemimd.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gt2qdhznsrf.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2ralqefac.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gt2tixzvfdr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gt2kcjxpizq.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2pduxjdoi.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gt2kvymdvku.html

[Q71] 查看建表语句
来源：http://dali.mhx1999.top/Article/details/gt2hthamqvm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gt2uzdbetrh.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2fobraeyc.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yunjjuhc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2brxrqupb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gt2rxgidpef.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gt2azyfqrta.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gt2vehqcniz.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2skchuwwj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2jpidjyoo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yueranfly.top/Article/details/gt2omfgkrqk.html


<!-- 参考信息 -->