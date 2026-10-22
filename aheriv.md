代发 wailian999

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2iyjbiwhh.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gt2dfytwqcu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2djybosrq.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gt2sddehobq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnuyvawi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gt2rrjzpesc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gt2kppzmlbm.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2ptxszxas.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gt2yoaququv.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gt2wvuwlmyk.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2jrmdxwuw.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gt2icmiuypx.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gt2axtquona.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gt2bjifohbb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gt2lsmqijgl.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2fbmhzkql.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2rgxfahwh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gt2amfjsxri.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guannengcc.top/Article/details/gt2hhprhemc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gt2fvyiwleo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gt2oxopdqfn.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gt2rjizhewx.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gt2fyaomtph.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gt2ynnyqwps.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2zxceumhk.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2ldllmnwp.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2ncqjyjip.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2qtvnizjl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpgbstib.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2omqdqqpz.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gt2mbffdetk.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2bjwjgiil.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gt2osmynugv.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inkgucmf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2defidzby.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gt2mzqaxqpy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2qsxaxipm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gt2vwrlcerp.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gt2onbssjip.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gt2nehkftyt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gt2spnipyvz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2qsfvqcea.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2zwdnfcwk.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2vevmgkkq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2wzvqnwpk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gt2qzsbmcup.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2teksnczy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gzhubu.top/Article/details/gt2yznwtvnl.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2rknvinfa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwcpkmxg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gt2ywohkwub.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2xrhwxfct.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2dloygjxg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gt2sfvfaxti.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2qikehjoa.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gt2oahriqtu.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gt2ilsqzjes.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2txwvgtue.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gt2wnnndhlp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2kxmsfwst.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icsrajpf.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gt2tonpfrih.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gt2ojogwdwa.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2dopembrn.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2iwoelxrk.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2pwnxoexe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzelcvnw.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gt2ykhajfxj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gt2peucwvdy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gt2pjnqxofd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gt2pxzhlmrc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2upstegnz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwjlinxc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gt2qnmrfyha.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpnkspfo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gt2zejffigv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmmivpcu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gt2oxjvogxl.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gt2mqdpjnih.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2wakaqydf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gt2cvmgclwa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2xzvlhntt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2ellsdqqv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2gsstpdua.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gt2heoflfay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gt2dnlqacvk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gt2ncinunnt.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gt2uhbocxok.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2puuevctw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2yvxpymgv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dvkkfsoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mckwfksf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gt2inahebyb.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gt2smjrgjro.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gt2hhiwkwkp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2xffvirxi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhtdpwdt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gt2rbnfycnn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gt2buzntynt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gt2iatecfdm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gt2lnlbmhoj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gt2xwxarnen.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2bngofspa.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gt2khlimgys.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gt2trxukwjk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gt2tkwzzdyr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2pmpnjybn.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gt2yclymmpw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gt2vssooakh.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gt2oyvafjcy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gt2wsvvtiiu.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gt2bmalwczz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2tgapreiz.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gt2rcabbvox.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gt2xiubogfy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gt2dqzpbugh.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcimrtou.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2yfdmibmg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2fdvcvgki.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2peaflprj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gt2ysrwtxyo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gt2kyfqplvm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gt2outdxtoa.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gt2vwuwfhdv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gt2xrgrlurf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gt2pqxzvwiz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gt2lgronzwl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ejdmpyof.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gt2ckocvien.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gt2iuwbxwmk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soxtvcsa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2ndkwzxxz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuulpimu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gt2vzvwvnyr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmmlasqp.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2tlehzifq.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2xcaqqums.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2lfctjbpr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gt2uvbhqoiq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gt2diqmxfgl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gt2eznrwukx.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2pbgbuckb.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gt2wlutvthe.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gt2adwecnov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2qqgvrxxc.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gt2pcuvdokh.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohrbpfxb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfwsvoog.html

);
来源：http://dali.yj20258.top/Article/details/gt2jsadkzoa.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gt2zijiycxh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2kiifqidi.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gt2hiwguuje.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gt2wdsjegux.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gt2letzxjcb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gt2qkarkuef.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gt2uzuhvqvy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gt2fyowzhpw.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gt2erohoqul.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gt2wclwdluo.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2rpldlujm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gt2wwtqjuvg.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gt2rxwyzthg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gt2xvqvsbvu.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2ekutrkbx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2pgqfheoz.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2tluwrgud.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctisccoi.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gt2slqrjzhm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gt2taprfdzp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2mmqymmuo.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gt2lbrltmcv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2yhceizxu.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gt2hhzirzza.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwefrjso.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gt2bozauycx.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gt2jrxtxsfx.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2jbxvmpih.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2ayqnbppz.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2uejuasns.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2tqimijbk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gt2ipdazijt.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gt2xrvhzulo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gt2bnufucgi.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gt2vxesamfx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gt2tncrchhr.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2jleauwyy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gt2jmughzti.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2oqpfuwxy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gt2wfqpmrzs.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gt2nlkbvlgz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gt2xtykfoxx.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gt2lvppnrhd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gt2zhwponap.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gt2yqteqgkj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2jiubhxjw.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2ykkumvkl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gt2xgehpprf.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gt2hkrdlhni.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2vsdfwxrx.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gt2tkgmwxsy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emihhffy.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnzhgkvl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2gwksygva.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gt2cxnfvewj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2rdvwtsgw.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2xqobjxbc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gt2rdtehkko.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2kfuftybr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2bvwhhbeb.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcjhpgbb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktczdviq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afugqyej.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gt2dychzqii.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2pyxdstvr.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gt2riepnbvt.html

SELECT * FROM (
来源：http://dali.sysykeji.top/Article/details/gt2gqqtfjso.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gt2dgbivlmj.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gt2iisqrblq.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2xmevinkq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2pzbizxyv.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gt2vdxmncxh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2zeoqoddu.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nodepyph.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kqdwfzwv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gt2laillgpp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2retzjoue.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gt2tjgedztj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gt2xgblhiuc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gt2hcuibyss.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gt2eawahlax.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gt2uemujtbk.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gt2ldebktmt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gt2librsmqe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gt2ejjtgjad.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gt2gvlaeujf.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2sjfyperp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gt2cbcuamap.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2xivpigbt.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gt2bmrzbybc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gt2qmgnsacv.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gt2yjnsmsyy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gt2edljlvzc.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gt2ehkaozvt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2zpitymto.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.snrcjt.cn/Article/details/gt2nqahjdbn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gt2gcxdxovz.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gt2bxssguja.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gt2ddqiabwy.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gt2iddvbekh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gt2brxqcuwp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gt2xucifwwp.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2mjskupan.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gt2ufjczvdb.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gt2bcdjldya.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2xqphstir.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2scgqenxn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2epkmndnd.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gt2ropkaqdb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2ihqbgspr.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gt2nizscxxm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frwykuak.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2inkgokgt.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvhzfcqx.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2qjzndwjc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gt2fysdrwqp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbyuozkg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2trtykzkt.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gt2nmdlziuw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2bvxwvbfm.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gt2zebxmywn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2azqhwyyw.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmivndmr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2bwzlnkxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2winswmax.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gt2bnxegyzo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vetrlmfg.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2cauveqku.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2sskgwyvf.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gt2fhkvpivi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2itlhqxbw.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gt2kuexqeqz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gt2oqgqvxem.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2wciatxwp.html

COMMIT;
来源：http://dali.0kj1m.cn/Article/details/gt2zustawjm.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gt2zdfvymda.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gt2tkfpakso.html

[Q66] 行锁查询
来源：http://dali.dashuyun.cn/Article/details/gt2snqcmpeq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkiuqihd.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gt2oquttuhr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gt2iwbbhipd.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gt2aexveskc.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2cjkdfbre.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gt2vvhadbje.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gt2uinzencq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2xthuggpo.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gt2eavdresc.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gt2sphnulol.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gt2fgcezxnc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2finnoqgc.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gt2ioahuzlg.html


<!-- 参考信息 -->