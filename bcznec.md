代发 wailian999

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtygaykskf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtdteiqfmw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtrjgcgqox.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtsnphlrqq.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gteavxrvbq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwqarvxm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtkecysglr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtskqnyjyi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gthqeqrwkb.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtkelpyjfp.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtkczqwjmd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gtowknxrog.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtdlqvhwgt.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpdkkqkl.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtidwvlrqi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gtjehggsnt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtejeytsob.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtlymccxza.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtonibhtgk.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtadhwnaij.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtnzesjdsj.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdackkesi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtinkcjurt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtortoxsrn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkzpjtcq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtusnivwpc.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwacbeolb.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtwgbnfxkg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtlhfkulyu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtcllmgpff.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtlewlbmhh.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtknmoowxp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtabbubnme.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtctywlhal.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gtpzfioinf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gtidrbxqkn.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtrguyazxt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gttjfoxpwk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtcoyrufzs.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtgtffmkfw.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtzwcituik.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gteukjtllo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtbvwufqbh.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtieptfrbu.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtrbehozhv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtkwpsgriq.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtyeilzlji.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtezjdhdfv.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtjcpjsxkn.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtnjubirdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtgodocbhi.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtcutxwwjp.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtxwseqpti.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtcsahwkmy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtzdrbwrvg.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gtywqmitbh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtvyhozjwf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtbplleadg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gtgosfquxu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtkppjalgf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtdxzlftsa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtiarbjgnl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtnpqsdmua.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gtrcwcgono.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gtlkoawwvc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtrqzlblzh.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtktvxijbc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtbqfjomif.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtlpwodzhm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtbsoivwdp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtfaelvdvp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gtsblfiuig.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtgmnddxrj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtbdvyugmn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtdtkjsips.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gtohmzjqjj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtxemwaske.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gttanmuwcs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtavuqqciv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtuopvdtrz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtnyxqoogk.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gtrlccxjqy.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtjaqzsqjw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gthodbbuni.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtlxrxirku.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtcjlndvtv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtvsdsaoyy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtpgfmbwby.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtlrdlrqhg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtbbfwcszo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtisrpiczc.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtzlqubpei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtxcbwpwgm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtsphazmbb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtukouakrr.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtbsmzecrs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gthixjxzhe.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtyrhdhfgl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtjyojazge.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtlekkqkgx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtwxosdkbl.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gtelovclwy.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gttmpyycub.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtenqlgqrm.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtgaccljkc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtpegnorml.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtmhkjwdzv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtnxgoaprm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtowhmmxbp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gthoyoidot.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtwarbnjye.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtvjkhehor.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gttsxwdipv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtabjmnklg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtgsqfvogy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtnjhyshct.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gtihhneohv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtihalkjlw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtuzmtzyhr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtfjuhbhye.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjqwqwhof.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtqbjtbwsp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyywjbeds.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gturhwhgpo.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gtqoumcrsc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtuscahpzr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtrnowxheu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gtxbmqahgu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtxqgggwbw.html

);
来源：http://dali.xinyue.icu/Article/details/gtspxtbdcr.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtoqmhcmye.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtruexxqmc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtbnrsayjk.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvvomvxp.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtzhkvwlyb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gttsfvnkfm.html

);
来源：http://dali.fzhhl.top/Article/details/gtiosqugjf.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtlljcylns.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtssjvlnsz.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsdsbchn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gttqwvhdrd.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtzawxkryy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtgkkxozaz.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtpbcofafw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gtrytfacat.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtxhbwbhle.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtlzbfcsnc.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtasydtzoh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmojlnkpp.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtgpwhtmrb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtkkyuucrt.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gtrwetvfsp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gtrjlvvpsl.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtzdiglurm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtlckbaqob.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gtrjxkjiku.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtvtbidxyr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtunpbctco.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtxbkkogog.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gthybfywgn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gtzvtizqve.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtocbyfvjm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gtfrtbrywv.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtkgcxjvnu.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtrelqvhqg.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gtjstomniw.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcofpkotl.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtklnfecvs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtuuuwfxbj.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtbgfsovbc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gtpkgczrrm.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gtilrnezvi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtokzeotex.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gtphwftmwo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gtslwleevm.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtcglwbyru.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtejchafyz.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtquofefbn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtsoqxxvfr.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gtfugetbph.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtzfxhralq.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtmoxhzcjj.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtetkchiia.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtolfpiwzr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtarqmavnf.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtesdtjoma.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtrdhatr.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gtavqeejwi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtnewbqhdq.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtcbpjlirm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtyhdibpch.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtunrxcrlq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfwhdmkx.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gtsnuejdlg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvprqbezr.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtmhvozocu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gttauopfyu.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtycouagov.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtsqkqhrnf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtgevxsles.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtzvbqyakj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtrfpvwiot.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtvwileqgt.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gtnasjxxtn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtlwhkkcqs.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtvomrlbse.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtqyuewixh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtoazwuzos.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtmxdyvivk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtlddcapvi.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtzqjwplxc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtihnxevfr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtrshcdojh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtjpykghyr.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gttbzjiimh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtrgosapfh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtjjdwtexb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtwofujyew.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gtpsgqdzaa.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtafxbnmsq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtesmozqod.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtgrwijnlx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtlinuemiy.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtvfnezfvs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gtgacvxotk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtbyvrchcs.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gtsljwshct.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtvzdmdoox.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gtdxjlsaqx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gtiepcwyem.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtdspfvtpf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtdcugfjlg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbjkpdjk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtjmxygxbl.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtecpebnug.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtpwenrswb.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtzhtgfmdq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gttwjfynwe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtogmzzajq.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtzklubsts.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtttumdzvp.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtkdefvaih.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtmyxwgzdk.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtavxmonig.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gtsmooobfs.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtxwgqnsmd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gteajnthcr.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gthliuebcm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtfyskgamx.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtlkiofibq.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtxhmjnnna.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtwsujgwyq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtovaeoxcn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtyltvwmww.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtdunmjehd.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtlxyblpuz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gthqcctzku.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtqwgqmywe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtfiuvlgms.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbflkesmj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtdaakgxff.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtogzttbjq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gthysbtobs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtwwdwkncs.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtbucvempc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtkxetydjf.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtwysrxjvz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gttirxnkag.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtovjhcfxg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtflyhgegj.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtrujrilgh.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gtqfhlwsak.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtzgnbslgr.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gtiurhhfba.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtkhrcsbzb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtdieerggc.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtekbefwov.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtedenzotu.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtqueyedgj.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gterrdxdzn.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gtqfaixzle.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gtbdcloemc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtpgusepjr.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gtunebyvag.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtfwkxeccg.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtmnwocjqy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtlbzjzwqv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gtbpskdidh.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtqeoggmdh.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gtjuzgbndg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtvagqvakr.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtjahyakir.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtfhpfiogx.html

[Q75] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtilzlwaai.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtwvrompan.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtxzlakyxs.html

[Q76] 按天统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhgbxsle.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtipsuvthb.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtqcxjypcw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtincfwhdl.html


<!-- 参考信息 -->