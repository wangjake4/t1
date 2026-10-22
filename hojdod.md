代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2fmloihxc.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gt2eswfgfxt.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lheuznjz.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gt2lqrsaevn.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkyfegbl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2jkyfxadt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isxlwphm.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2sxzjxfaq.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2eyckuswa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gt2lbjwdtba.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gt2tkiyvbof.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gt2sekrnqnq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gt2nvsojagx.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwxguizt.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2vkejswcm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gt2genqebgk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2abyyzpwx.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2mhafyull.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2wgavhynj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gt2igfgaegl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2imszwkft.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2gsvghaur.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gt2pqaebhlq.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lupzozch.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gt2wnovpzzl.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gt2xqwifsed.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2uobzxhkl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2qsccsdvk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gt2fqjqpxvf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2smxqgvbw.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wupqqktg.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gt2ektzpfrc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2jzpkrppc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shjyphxl.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2iquqacyp.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krqrlwyq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gt2pqvzuwwu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cashguo.top/Article/details/gt2hshzvzoc.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2xxwhejzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gt2zmcosvmz.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2aejohdkv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gt2toykrpky.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gt2bjkqvowg.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2nziwwrzm.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfthtkke.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2jgnmvgfd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gt2effmeuip.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gt2czxizfeo.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gt2dayudbga.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2zvdvkgqj.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gt2spwykvcv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ollcrvme.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gt2dnphehaw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gt2bajavyss.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2zkbhojop.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2nygqocqc.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2tyinyfkd.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2chicachl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2qwyybdjd.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gt2ihncjevs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gt2mzxmwbbm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gt2sychytgc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2brazggac.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gt2ybdpjggu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2usbeuott.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gt2aexsflow.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gt2mrzfyxuk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gt2honglczw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2lucdvios.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2qqsojokc.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gt2rturtdxs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnqyjngo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gt2orpcplzf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gt2rcftrdtf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgcincue.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iunfkloc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gt2cjhfwmer.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gt2mpbxloge.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsglzbbt.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gt2essvacnz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqiydeba.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbpjmeiw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gt2pconwnrd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2ocxoyzio.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqsyojwf.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twyatbre.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gt2qgvgqoka.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2ozebxsop.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gt2hokpysnt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gt2fkhyoggj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gt2hngtdluf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkzficzv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gt2dzombbvr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gt2pikrxllu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2szdaneag.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gt2slzxgtpl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gt2tapobabd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gt2hjgxwaon.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gt2psmsqjll.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2amwvatry.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gt2mjfgfmmj.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gt2aqsyrpbv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzajrpst.html

Go:   if x == nil {}
来源：http://dali.jlsjyb.cn/Article/details/gt2iraadwpj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgcepkx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmzknoo.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gt2hxiajdoe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gt2uhbnbgwa.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gt2mjpopjoo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwmmvawz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2edxcqbtd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ateazfcq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gt2locazdxk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gt2mqtzriqa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gt2phabrezl.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gt2madrmcml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gt2jdqwrrfu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2dpdvmijx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gt2rgsuiyvl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2meffhgwa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gt2uwdlxgwx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gt2mnmxjiah.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2gqhyqjgq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gt2fipjujix.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgflpmmd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gt2vqccxgsm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2zxctysdb.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gt2koeziinx.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbhpuyhx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2qodeaabn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2otfeexiy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gt2xgskhfoq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gt2aumzqakm.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2hxexxmwb.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gt2bmilwvjx.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gt2zbomrqlm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2tqwfskhw.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gt2afcqyywo.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2jnwsxebv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gt2ocjilllg.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2xigxndna.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gt2mdmhpblf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onojncbk.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gt2zehygsjd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2pjedzasf.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gt2vdbebnpm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gt2ikoqouno.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gt2uiuhpxuo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gt2gcczdctf.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvyyghme.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gt2cqypxoqb.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvuvyqlq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfpills.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2hitcusuv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqacxqxj.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gt2nlzhiewp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2fxdczxwm.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gt2gwcdjnqp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2ukaeikag.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gt2wpyslesx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gt2lqziconf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gt2colokdot.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2axuyspmw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gt2vheikakq.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gt2zyfqxdox.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gt2vsraddoa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqbxandk.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gt2pdvdmjnf.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2zypllzef.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2apbqzbre.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2dlwkgnec.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gt2dbwnvivw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gt2ckbaftqh.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ginaqitz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gt2npcymkti.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gt2bligslqy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gt2lauokqvt.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2bipcbtrn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2nsledeer.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gt2opahbtyn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2xqdutnvy.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gt2vrdjuvod.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gt2cettxfkj.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gt2pnxqvyuz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gaohongyu789.top/Article/details/gt2fzvugsuh.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2bytkzuan.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gt2sjroxyud.html

[Q25] 只取前 N 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wksanodi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2fpseeevm.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2oesatbzr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2emhjyrlb.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gt2ijjwfflb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2pyolwwbv.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gt2rllivrto.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2vlsycidy.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gt2utokcwzv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2ljkiyddv.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gt2sphrjsgu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2kqgdpwvq.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gt2akfrmuak.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2mobyqeag.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2gyoeelvo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2jxavdqlx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gt2mepfdbxy.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gt2znflnfqp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2neybpoda.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biadezfn.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gt2vxqmejun.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gt2kbzqzdtr.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2lnyrenfo.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2gipzpchd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2tysyoyor.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gt2sszhpzvs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2tvknkrkz.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gt2epsjbpua.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gt2jwmtusmy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gt2sjbawrsx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryzihyxa.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gblmkcgc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gt2kyrwpifj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2xuigzzil.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gt2giqqzymb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqxtzrxm.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eljdthiw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gt2pwcpnhgq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpmazmiv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gt2drtmjsgj.html

[Q42] 连接条件附加过滤
来源：http://dali.fengsongda.top/Article/details/gt2wcfatjwx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gt2mqhaldvw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gt2mymzwrjj.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gt2tomhaelt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtdsztnk.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2ojuonswu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gt2wxghkznl.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gt2ncsogfva.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2muyixygw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shwzdybx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2gfiudmty.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gt2wrwgsqwo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2yowjwqge.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2ogtfkdta.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obvaemoe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2fscvewxh.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gt2hzxkoaee.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2txmeijxb.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2nflucyzp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqbziaae.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gt2wwxcwoja.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2axryybas.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gt2ckflvrct.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2pzhucnth.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gt2mbsaqudj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncuwmhfe.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gt2dreylfpp.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gt2jmlvkyvt.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gt2ckaemqwr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2dcyrsvqw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2vfnszxww.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2ihrrluhw.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gt2bdvwcpis.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2kxhlleln.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gt2kztuprqi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2ncyhutxy.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gt2lqlbibqr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2yybydtfv.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gt2wqdanyus.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gt2odfyhjwr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2dxaghfyj.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gt2pcnujumm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2soigytqt.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gt2ieuxrdkk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbbqypbe.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gt2tbmmqrcb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gt2pwsenilv.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2pycjrvpg.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gt2nuwacomh.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gt2wubgffzw.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgttnuui.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmbvwvox.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gt2uohjmqpg.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gt2ggugxpsd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gt2luuyychi.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gt2gacclsuo.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hegbjpjl.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2ogsgfrhp.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktwibwyt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhongyouzk.top/Article/details/gt2pozxrspf.html

[Q70] 更新统计信息
来源：http://dali.svipenyu.cn/Article/details/gt2txxvrjdu.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gt2veorhdda.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gt2hzixfemx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gt2haffeplr.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2ktyyrhqq.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2fkzreubc.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gt2atvjeprf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gt2vvdylmgh.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2xdlajwmc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gt2xjdyattz.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocrepraj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2xhyezsop.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2gnnylpmg.html


<!-- 参考信息 -->