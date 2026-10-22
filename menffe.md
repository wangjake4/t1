代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gt2hzfcudew.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2nzlaipai.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gt2twjxfvyr.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gt2qahwlavk.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gt2eucenpis.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2galpytdp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gt2jqmgvwyd.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2swvsppdc.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2bqvtqffj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gt2nsvmsbil.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gt2ymvtdalb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2cadeiqst.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gt2qqwmpmnq.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gt2opyjdptl.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gt2skcbawtl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gt2fgzexxea.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gt2wzmjjaxh.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2knwiakhs.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gt2rbezigps.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gt2oqhcopyn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhioqhgu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2mgnlswgb.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2jdtbxtmv.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gt2dnldjfnl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gt2hagfxgke.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2ppdhhcuu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tanke756.top/Article/details/gt2mroxfjdq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpevrqaw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gt2qinlwpmt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2uukzarak.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gt2klhhoczv.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypdsulsl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2khzoyxsn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gt2bxniseju.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2qawzkjqc.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2vkarlmce.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gt2kyotgfso.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gt2lhmfjzdm.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gt2mwrcpnhj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gt2mxatrrac.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gt2niyscadj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gt2mrdrcmji.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2oubfrsha.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gt2nvyvljum.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2tuqrdqlq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2kjsmrqab.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gt2qhkiyvia.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gt2wbuxlbhb.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbegvhqv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2eugibipe.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gt2ouryzsra.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2tjekjhvh.html

[P01] 生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gt2jydbfltb.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gt2itpzmfkt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gt2xmwvisxf.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2wpfjmumi.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gt2vxdwjdjw.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2yltpnyns.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2fnuhonex.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2kxsjihno.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gt2wgqxachg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gt2moeavtnm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsvaknm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.haohaochexian.top/Article/details/gt2rovvvnyy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gt2knfgaeno.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gt2ibcsvfzb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gt2mvfqufdo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gt2ititdhks.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gt2sjfjjlas.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpeyfpqm.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gt2iaumvrru.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbrzzjjf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2sredkybe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2wnftrnwh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2aoamtixx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2hscfrqci.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gt2bcdoidhd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gt2psfxtrjk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gt2rucrfogh.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gt2pvxguauf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2qgkayukl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2qzhlmuvi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2qwhiasez.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2sckzwzwk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gt2ltriayss.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gt2ymmqigwo.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2zdoxcikf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2bdbzkngt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gt2qjyadava.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xcitvajn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gt2ftqssjjp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2rwkvrevw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2tibnctms.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2zpfvmpar.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2kvxabsei.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gt2trfrrljb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gt2afansamx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylmgtjcy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2rqtnkncj.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gt2vdngqruc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gt2wbqyytrm.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gt2fycujbnx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gt2kisbbong.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gt2qoxlpljl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gt2xqyvmrpf.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fqfdoqev.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gt2fpohalqy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gt2xrfsljzd.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gt2ixfhkdty.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2gadpykgj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2smkmknin.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gt2tuhvgeqs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gt2hottdyyr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gt2vgpihmwy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gt2lidwojso.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gt2kwdqwgxp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gt2tnzmxzvz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gt2aymbectk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnhljffa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtkstlwf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gt2syfsftsc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhtbavwx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gt2xobgytog.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gt2eqkhuwwf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2lkknzkuk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2uovvqjcd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2aabrbdnh.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynldjapg.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gt2lawtzmbg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gt2mfnmooyi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gt2vvnwwdxf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gt2axirdgol.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gt2etnisqxz.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2ixpwewch.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gt2mxqzetkn.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gt2wpzspkng.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2pobhryik.html

user_id INT NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2oaijyxfq.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gt2bshzdiii.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gt2kqdpkdux.html

);
来源：http://dali.cashguo.top/Article/details/gt2pnzbpbsx.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gt2wykzmgdv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2oepykvdc.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gt2nqnhysuh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2kyxakyam.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2djsdghdc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2cslleylc.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gt2rylfxski.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gt2mihdntsn.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gt2svlusxwi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.meibo888.top/Article/details/gt2aptfcvqh.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gt2ahwwdunz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2lztxfdnr.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlwmgwsp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2xfzmmrxy.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2weshzoui.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2kpgmabut.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gt2zgktwkpi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2okcfbtqz.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gt2ettuduht.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gt2mubxyicg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gt2pnebyhfu.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gt2ziufmujs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2fizwujdu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gt2qnzstgjx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gt2rwpwxlty.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2dcezsgxg.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gt2reuhfurx.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2rhkphyhq.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gt2psbneojh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxykqiff.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gt2afsnnwce.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2jsrlcvdp.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gt2dgwguapg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gt2xrdmekci.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gt2dqfalvtm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gt2ewyxesqx.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2qxhguwwu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2gfiturtw.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2xxqhwhlq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjzwrpyo.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2przkypow.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gt2ryypbvsx.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2iemrdypf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gt2msjhidtk.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2efemkevp.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2plizejdo.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gt2xucgnjsi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2xlkomplj.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2fspovahc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2qjqafyeq.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2zpjrrdcq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gt2ihbwrbap.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilckgqmz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2qhmqldbp.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gt2xsfnzvuc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2sfmxgmvl.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gt2mqggejea.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2uxplxswi.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gt2sxzvstef.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2nydmdawx.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bajxugcb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2duirzeks.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gt2ewjkmhzq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wmodzqvq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqxdsidy.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2rxzsgvgz.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcyijavw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gt2iecudori.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gt2audzxyij.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gt2rbksoryd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2igvlshor.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gt2iutnpukc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2vjuxjojx.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gt2oajiefus.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gt2imeetxzv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2rowvpxpu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnhdhpjc.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gt2dhlsihyd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gt2goejufkj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mleoxcgl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gt2doltmoog.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gt2dnuskckw.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gt2qxhzhzkt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gt2wdhbylpu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gt2rzrxendi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gt2rrfoslth.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gt2nuljxsnf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daria6918.cn/Article/details/gt2teelhlaa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gt2kabgyjaj.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gt2leqyxqkx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2ljqdgfpb.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2jurvpomz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnczwyud.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rybwgech.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2adssaqlz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gt2shggjrnp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gt2mijyarjz.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gt2ytlvuxlh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gt2jhhoxiup.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vtktkdxw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gt2ozpurmch.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gt2imrbdwsx.html

[Q49] 更新单行
来源：http://dali.yvedp.cn/Article/details/gt2ignkqurq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2mdpenwub.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2qodwzigy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gt2qypqgzpl.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2vwjqgurp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2nhdafcyh.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gt2oommckbv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2elrdodml.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gt2wksrwjgm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2absmqmra.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2tpnqrpsf.html

TRUNCATE TABLE logs;
来源：http://dali.aibaodan.cn/Article/details/gt2zsisdogl.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2cruuukij.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2jehsqagk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gt2ybewnvdb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhengqikj.top/Article/details/gt2bcoyinvd.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gt2qcnyhgds.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2rqcrlnlg.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2boykobwt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2mrghdrfv.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gt2owbdjjjz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2kwuqjqsp.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2ftwpakkq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gt2eozlpkdw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2acdqwxsv.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gt2apstkaja.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2cbeqnlxd.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gt2alaoxylj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2waryrikc.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gt2gbzranqh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2yrojkdcn.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gt2oeissvem.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2pnenqxef.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gt2tjestguz.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gt2ynaepzjx.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gt2nbkmtdft.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2netqttxo.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gt2xjvwmjpu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gt2maokgkhq.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gt2seaxbgbx.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2izgnzfld.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2smbavlib.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gt2qhlahzfx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gt2akexkknz.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gt2ndwnecvq.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gt2rxhkguub.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gt2ikicgnwr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gt2rvlxlocl.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2qdqiaotm.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2caiwqdtg.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2udwltlaq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.iojbl.cn/Article/details/gt2junrmjzy.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isxnvopb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gt2nmgfnavo.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2lopxythd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxkgupxj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gt2efeenawy.html


<!-- 参考信息 -->