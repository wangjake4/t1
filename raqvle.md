代发 wailian999

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtbygafcdz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtsrfrafxn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtfiotspsn.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtgkwyrvel.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtuirwimjp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtsmjwcjyh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetasksfk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrzzpnbj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtyekqfvwd.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtbowoblmt.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtweuddhyw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtfrmzwfzj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtfkzlluwd.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtrwcyoxan.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtqocxdgor.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gtkrjadxer.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtncotvfqs.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtlrhlqwsb.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtoqqjoyho.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtavtwzuua.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtlplfksgv.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtazgtyyve.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtsfedpnot.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtttspdyhz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gtejrtorjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtbbfosswz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtgvkpfuai.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtpgngbcre.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtxfsmwguw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtqaqxmkyp.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtfnicaxkx.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtwizspbps.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtjcycjroc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtksapdytn.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtdmxcaelr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnenargue.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtadazxaeu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtsisunoxo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gtpgcbcwlt.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtniipmxrf.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtlqnytcvt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtulpypchj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gtzyclehks.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtsrybheyt.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtubxikxhj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwdblzdzo.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtoalwuxbe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtldjdffqh.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkozjwwd.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtncqmkxvl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtxnptwmec.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtadugiugg.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtyagzzykx.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpqyifuz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gtyfigesjp.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtjtgmzjpf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gttplnmcth.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gttkbjcoas.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtllrgmpyk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtqknnmmxc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtgowasfda.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtzjxiytvp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtydyazsxn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gttocbnyqy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtfnvvtqjr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gtyerzbydc.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtggdbtmqj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtgjpfqpnv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtthfcibmb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtlzzdsrbv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtyhygxgdt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gthxrkzlim.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtanvjbysa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtktariojb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gtoydijdio.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtepmyjjak.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtogwhwmnx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtajfnpssl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtkntkvakb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtqwujztmy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtizvddsuy.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtpnamslrp.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtxbbnadda.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtkwwwgkjm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtfwawaowr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtrkalyyjs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtlkuvwdvr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtvmhaywpr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjaxiggr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtbrikcflg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gtkbpxaziz.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtmzecongq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gtwexdyrxb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtgqhnbbdp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnqzz.top/Article/details/gtvkoygrqe.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gtwlclpbne.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gtwxekggyu.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwzogdvoh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtefgpgeao.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtzxyzzhyj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gttiaclwvr.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gtinqzyccn.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtbyaublfh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtkzcwlhsc.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gthrvqsfuo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtpiqsufwt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtyocgcddx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gttareoanx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtqfzxhwuq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtyqacqqqm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtwyeinavn.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqovabyb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtqnodprhx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtvroqnvfk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtxzhlldqw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtjbhzwult.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtwmspiyzw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtmdrtuhme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtnwfkerki.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtvurssrcl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtndckegre.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gtvixeexwg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtisrqxzvu.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtdcladfgz.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gtegwukzvy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtizftuzpk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtlrqefvqq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtwscuetpj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtxzuybesk.html

);
来源：http://dali.sxryk.cn/Article/details/gtzsqkogkq.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtxpxrfbse.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gtdbmwewgt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtrnqjcdcb.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtuwupsjid.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtjodyuwbm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gtnyhwgabo.html

);
来源：http://dali.shuidangran.top/Article/details/gtavboshvv.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtygndjagq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtzykrijyl.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtmipzwtir.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtlnoujbvu.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gtfvouhvlm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtkhdldphv.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gtpgroqosa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gticlukcdn.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gtjtapgmic.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtkrsnxubu.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gtdmxaradt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtsjnhxvhj.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyoohvlp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtyrhjvacp.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmnoqfsu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtdvplanpg.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtrkfnbxzz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtvmitsblo.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtrfwihjfj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtwdoowdur.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtbcnljowx.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtpcktjfcl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtjxvtwyuv.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjimxsxjs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gtnacgwnyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtydpdgaep.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gthyqabrjp.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtbnahfojv.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtvfrusnrv.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdeoawqhz.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtuuqawctp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtqatqvmtd.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gtfetldspw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtsfagvorw.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtfuvqmcks.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtmmgibtzt.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gtcprhlyzd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gthguhysdb.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gtxkosplsk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtxvgowbow.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtkagucndt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtwoitbeyi.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtoxstblgf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gttkrjpxei.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtfazcadkt.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtrbgprvwl.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtvjnxobei.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtagtwqkeq.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtqianzfjh.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtbgwaexnm.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gtryuahtop.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtitosklln.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtjwyggdxa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtgltbnrjo.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtgdnryadd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtdwkzybax.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtanipniac.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtcsdmhild.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtopoghzog.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtcbefdwad.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtgjjdiswi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtxwiqpdws.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gthhukqoun.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtvcvnkoee.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtvwzpzkmi.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtdaffhfyu.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtbuvksrhp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtxpvudsqp.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gtikqiyuat.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtphjtvidc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtnhuujhps.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtmdcmgzyj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtprduweze.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtcwrbovnf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtlmyazvbc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtwblniusp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtnzkgvkxo.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtjfmtrtsb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gtazanudic.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtopvqvkon.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtkjjguumm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gtbutkjdgz.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezrwflsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gthsiabpwj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gtnfzumfkj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtoimqhayl.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtagmgpidc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtwstewyxi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtvlirpokc.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtdupnropp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtobqlybqv.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gtbzhrdxyl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtwwxafnhj.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gtfvtgubzy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtatcyaqrk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtzwoxbyjp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtphabpdyh.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtouoaopkb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtkyhuayks.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gteeyecteb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtzubgmjxn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtneeecrfs.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtuirgtjhc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtakcszklc.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtrtozhvts.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsmdmaxy.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtkegngnck.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtkrhjghug.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtnprupyzl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gttqyipywc.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gtdcxgylfr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtvhwpejab.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gturtlipni.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gteeejahgd.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrrgcvap.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtfzqtssmc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtvpdbnyjz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gttrbxjepl.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gtzzebsnzp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtktlymcjg.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtkzugwnew.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtczplhnjp.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtcehslivf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtxkeqrefa.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gtdgpjrmst.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtiwmmctdl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtsqovyjfl.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gthbfcggcy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtyznjbqtf.html

[Q62] 分组占比
来源：http://dali.zhengqikj.top/Article/details/gthcshziqh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtwrannisi.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtcvqbcrrw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtytrznkwc.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtebmagjcq.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtznsqplnm.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtzclnfevy.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtnsdvschb.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtsqmvdpnq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtndbkhpmv.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtrctsdxun.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtjkwnrnhg.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtazmxjqqz.html

SAVEPOINT sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtrszuttin.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtzgnbtqoe.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtgkxgvpdp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtspknvsfm.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtpfvoqxli.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtbhmhwyju.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtycmflntx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtuyukfgva.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gtcyaxiqzh.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gtgcupcklq.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtdcdfelbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gtezctwsel.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtgzcpfguv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtjmrwthtc.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtmleekkzj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtsokshbcm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtkylqiivu.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtiwxpvzya.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtzfhhuqro.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gteomwbsbc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtizygputj.html


<!-- 参考信息 -->