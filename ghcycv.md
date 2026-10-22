代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gt2nfyvkgwu.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2esyuwkow.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gt2hijgkkql.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gt2ehvrsvcg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2fcsefzny.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2ptgqowkl.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2ggbrubzc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gt2dylyssdg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzktjbot.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wkkszbhf.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2ldyiugzt.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gt2fkamoyhm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gt2zpngpokh.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gt2ldjjtdvr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2uholpimp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2vuwuezfh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gt2imvoycnz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvlefdng.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ljmqakgp.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gt2nluevgrz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2mscelpva.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gt2jgqvufzz.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssykbftm.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2xaiabrom.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gt2zjyvxuoh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gt2llxrhwow.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gt2pwntthng.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gt2kizamexl.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gt2liyylrrh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gt2rpxbypaw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gt2imjwlugi.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2rcmeuhjg.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2rcsjnban.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2ulcqcsjj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2gjzkaqbv.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvxxnthp.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gt2pewmbuxe.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2irdzoull.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gt2vdsngafu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ofgrmioc.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2odynbtvw.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2acdgevbk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2qsijnlvp.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2uazoleyh.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gt2kqsjmleb.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2tajeevlb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2upmuzldx.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gt2xrygijfj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmeljeev.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gt2buytqdpx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2qxplkcok.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gt2huxsgamq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxgcbkju.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncqafwkw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cucudq.cn/Article/details/gt2iisuaref.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2epoctprc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cdnleiting.top/Article/details/gt2rqyeqlan.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gt2eqwqrenk.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gt2xfbyssnx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gt2dwhhfrft.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gt2esstcoko.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2mwxqhvxk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2mqynvbgp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gt2oubgivqu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2ibgkrfam.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gt2mdfwigji.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gt2gdodtpbg.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgvcgqhf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gt2ibylqpjw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgzyxlqf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2aupbrwnz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2qgywkjco.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2qhwfiskc.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gt2ybmyykjv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwactyw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2igdmdsaw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2kwjjsmxf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gt2wwdtfsoy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onjlgpyj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gt2zpbebkwf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2sqacbhkx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eftyvggk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2evehaaig.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqakcvxl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2sgavrtuj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2yihixyfp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gt2fqkdzhfw.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2gpgekhee.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gt2liavbvex.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2pwftqaop.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2qziidxmp.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2yooihsss.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gt2mdtvnjof.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ntnnjdfq.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gt2ccvvnmfb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gt2zetyzvnx.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gt2uokneiln.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2ibgbszeh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdbiwswe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gt2oozvjbdf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gt2oubzcsmn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gt2ewebupas.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqotrqxy.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gt2kmynyjkb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gt2axnpljkq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.meibo888.top/Article/details/gt2ivqfhlyb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2iuqqjydp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gt2slrkjxif.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gt2esdqnjsv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gt2iarkcmqo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gt2zhaujdqs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gt2sgcjbdat.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2kvtzdnzr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2jwkodytz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2euwhbqmv.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxcukwgj.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gt2dfrmwmut.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gt2mbjaqlri.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2ilrxnasb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gt2traarmzg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gt2ewaqczdk.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2gysiuwkd.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gt2rhtwgzyw.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gt2gyzcimeu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2tiuzmodw.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2caolgceq.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gt2miqowcec.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gt2xryhdjjf.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfwfbdbx.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gt2eahdlxxz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gt2hwlojtmw.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gt2xzqlhuwd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gt2bljiwtwy.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gt2iiccfbgw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gt2qiiqzpyw.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gt2weewahdi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvgcrfxi.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gt2ftpmflpt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gt2pgkvhutg.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2qyvuljys.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fivomorn.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gt2wyuihhwr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2fxodphte.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gt2bzynmhbk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmudltau.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gt2tqrkfems.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2hipwvwil.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gt2djaujvuc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jyoumei.cn/Article/details/gt2iqjejzol.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gt2zpnrkptj.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gt2chxevthy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqdtktl.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnvpcfki.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258.top/Article/details/gt2sfkerwba.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gt2gkmmrfcw.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gt2snsifwye.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2efhgecbc.html

[Q16] 查询指定列
来源：http://dali.yongpay.top/Article/details/gt2iyxlhvkx.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2tfoscsax.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gt2vtpidrrq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2zwlltvfh.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gt2igjtrntq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gt2ykxsrcen.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gt2momxpokt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gt2alqouagf.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gt2ablqbfof.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gt2cqchxegu.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2kruppgsz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2shlsojuo.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gt2qhrsrahh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gt2isapsegw.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gt2vcxgbbsp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gt2dxxekwjj.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gt2hoykwwwy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2vuyaxghg.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gt2jkmmzwky.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gt2skydweoj.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gt2usxzqluf.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2grjjczto.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gt2kmqbzltn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2dcrxrelo.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gt2ozdshrft.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2rfbswmps.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2mryoysaw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2zrtgvsqf.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gt2alndmdes.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2velmhfkz.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gt2utevvprz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gt2khnsazbd.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2tzoatzqr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylhckmku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2peiuljqf.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2srshzxkg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2zfrgzlkq.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2rfmqmcst.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gt2jfqrfpve.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2ycihaeop.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gt2zmsydvij.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gt2sukicyeh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2amlscxob.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gt2mxrvgppe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2jfzakixc.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gt2kzovnpfj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2gpncivds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gt2jddtcmjg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gt2mygtiiro.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2jvwgcshl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnsgmkyr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2nqdkjjtx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spiyxauu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gt2leiwshvp.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gt2cupleiqx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2pwtfemxr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gt2fstzfszb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gt2keqlqnfw.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gt2anmwtsom.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gt2cudbvurl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gt2dzsfxhtq.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2kvbjmdio.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gt2oigwdqve.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gt2gkuphdjm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gt2hpwqlokv.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gt2ihugsjhj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gt2mdncrgtf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gt2xcbhtyrj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2sggopjhg.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gt2wfdkzlju.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gt2xttnprfg.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2grxnyisz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gt2sclmgsgq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gt2fnufvyrk.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gt2mwotjtkv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2pidllhro.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gt2mirptbct.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2mluepkzd.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gt2mylqyrlb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gt2ovaqvzzx.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2knfostfp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khdywnjc.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gt2jdrxcahu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2wbumljuw.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2plasnsji.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gt2sufbalwr.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gt2ztrzyryg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2karzwris.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gt2srbjicou.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2frbdrhou.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gt2ombzajvl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2tyovgmvb.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gt2swvilxdf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2nwwiqtmm.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gt2yalknzuq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2cnhhxxly.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gt2yixeymbv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2parlmkaj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2lcbeqxxc.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gt2eyhbbqtd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2sqhjggrd.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2xxdhhwra.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2pbnbvbck.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gt2bzxkatnf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gt2uennavop.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gt2qdlfirik.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gt2gdhknbex.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gt2wdvfvrxq.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxkzimvy.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gt2meraaknr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2tztmxvyf.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2mszjzkyi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sweek.top/Article/details/gt2hjuwyqcf.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gt2shboucdp.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gt2nuysqroe.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zevvofen.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gt2mmzeumxe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gt2hbihfkmb.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2erktygqy.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gt2znrccqaw.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gt2rrzwpbyh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gt2ohoncgfj.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gt2ydjhtfru.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gt2bugbpycc.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2utioqihn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gt2zenppebs.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gt2cdialmby.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gt2iyqsezcl.html

[Q75] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2nhzditae.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2kexsgpcu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmnryvut.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gt2tzumbjxe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gt2fvxeuaju.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gt2wykxrlub.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gt2fjwgnuhk.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gt2wpriegsx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.0kj1m.cn/Article/details/gt2aoavinjl.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2pmvihkgg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gzhubu.top/Article/details/gt2kqzftyos.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gt2ypgwvjzm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2tpwfysyr.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2kfcqegvd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2eafmouls.html


<!-- 参考信息 -->