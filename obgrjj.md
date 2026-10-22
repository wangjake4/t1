代发 wailian999

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2bzaflaqg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gt2vmlwvkhx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gt2ceuemiwe.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2etiwgqka.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2scyhbifx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gt2pynmvwqm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2klthmtzf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kerbkbeh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gt2tvotmctl.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gt2cbxhwdiu.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gt2bgevrzfv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2zkclmhge.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gt2cywaknna.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2rxuneror.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmdxvshn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2wglyejkf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gt2lluqbfex.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2hklwjflk.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gt2wgrfmmms.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gt2krpgzyxc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2lxqfenzx.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gt2qxrtoxhz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2lqwtpoiy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gt2waixpznc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2owmufeyu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zkiqdnia.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gt2guyolprc.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gt2jsnuwcjw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gt2tctrqpwy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gt2hhnrvwdd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2cvdmaafn.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2evvteexu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2onuzxxpj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2hgaubhvc.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqygvbki.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gt2iierzwxn.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gt2agvfxcce.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2yqydkpea.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gt2gqaihozx.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2mpmohucs.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2dqqeunns.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2akziwndt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gt2jhpcykry.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gt2wsvxjtjx.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gt2wbuhjzsw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvvwxbbk.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gt2unwqhvik.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2skikazqd.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdkqpczq.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gt2kcbqygfs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzusdihy.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2qaowyvsf.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2wyocnksv.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gt2iywobebp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gt2zjrjdfjc.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2wdflbwns.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2ynlengey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gt2vcdildwc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gt2qqmxpqnu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2hegdwhja.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gt2gopvrmbr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gt2sgxulqma.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2dtettmsy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gt2uvwoemfe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gt2twiiihcg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gt2mdkmmkgj.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjakfdwu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gt2fdxpfvoz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gt2ppdduknt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2vcvokdqc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2ghaxdhnh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2xvkarsqo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gt2oxsdwfna.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gt2uovzfcjd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gt2gljxoodw.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gt2xftjpbuj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gt2bgbpsdoi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2vqdvfqkx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2tesckawn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2bjdcinrg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2csznzahb.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gt2czzkonyd.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gt2jaugapdo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2rzhxbyyu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gt2biqflogh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gt2rcvmdlke.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gt2ytoeumhx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2uinrskms.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2cqixzgdr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gt2mpnhkgux.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybfwsnal.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gt2ogjkfvvc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gt2ddrnpqii.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzvufzil.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gt2exkrnzta.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gt2treruvbc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gt2hywzufsa.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gt2wvmgdooh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2feycices.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gt2iftxwhqi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjzwfsiz.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gt2jvvqzthh.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gt2hjyuoghh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gt2ohqhtdmu.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gt2zqjvmram.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2vcltumsc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2sgchoxrg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2nliykppd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gt2nkbfsvej.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gt2mjptrsik.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2azzwefyh.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gt2kktxregf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gt2yrjqokwh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gt2ovhukhzk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gt2ydxwtmrl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2quqtfdet.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gt2rlcmpoxs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gt2uhglryzf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gt2cnnbwvkr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzyyxecs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2bwqkboih.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gt2npgshagl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2okqgkmae.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gt2biduoeob.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gt2zrcpijdj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2ictpsxhp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2ofxeopqo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gt2awcxdadt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gt2tmabmdet.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2hklknyin.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gt2orotttwt.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gt2rflcfqkn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2rnixzhqk.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2nspeghhr.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gt2tkblucww.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsuxwkjo.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2nbevqzcp.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gt2smvxdpln.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2byyjsvfi.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gt2rgecvyab.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvllyntp.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2ixkviffb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gt2jxcbywkb.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2urmgenxc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gt2qxqzyoeh.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gt2ktrisxsp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gt2emompote.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gt2zanhwefg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2oluzcmhc.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gt2diffiunb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdoahic.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gt2cyosqvrw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2wwnpxlzp.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gt2ajwhummi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gt2qhnwyktr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kffpsisu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gt2mknffxeo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gt2hkmfkwlq.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gt2wokorbev.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaijrnor.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gt2lvbzsnlx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gt2vorusvss.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gt2fgkxvcei.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gt2whoozywq.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2tjftzshd.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gt2bmdrbcqb.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ebgzpukp.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwoakevi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gt2tsnkfvxd.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gt2ycuxydrj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuzuccmc.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gt2lmnxtsld.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gt2rfwpmupc.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2vfldazcv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2awfvztca.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gt2ecounghp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gt2jzjlvddp.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gt2catshtba.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gt2zimvcpml.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gt2xyfpxmkq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gt2kxiumwac.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2yfuubytx.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2uhqafwvz.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gt2iwlyerpj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gt2gpeowovw.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gt2zntydfuo.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2tsdrudxe.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gt2ckzhqkpc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2ayviaolz.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gt2yuxwodxa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqvhdcoc.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2ngwnbfbp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2tkfwsnbz.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrjxrwoo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2xddfvnvn.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2plmuqhbd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.snrcjt.cn/Article/details/gt2krukrlzn.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2zpexifbj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2bisbxysn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gt2urguoagw.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtmydarv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gt2txggphzv.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gt2zpgdmjyy.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gt2ckrnjzzt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gt2fvhiyuxq.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gt2sqawqjwl.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2rbmigcih.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gt2lsjsjelu.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gt2ewfuowad.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2tarfpruj.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahwucbmp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gt2wcaqkist.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gt2cmrmzasg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gt2uyazhsiq.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gt2hlqdnwzq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gt2tqrjjbcp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gt2aseelpio.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gt2rdzpedzn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gt2pkryyctv.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gt2ycnfctjv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2hihvuxyd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gt2ixrhgbkg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykmflbwc.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gt2bsdmxljq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrqqebal.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2mmidbpgr.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcdlmywf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gt2djkrakuf.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfhmhikk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gt2wxjdewcr.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gt2zwjkapic.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2yjvqtzuq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gt2clmphahw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gt2cqxutijm.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gt2dfjylhco.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gt2toefeqfs.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gt2lvfqbijs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gt2ffkxhxkg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gt2amnzrneu.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmidvexx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2wzufhken.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqptvopr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnijpnzj.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gt2vvrsemco.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2ynkjaiyx.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gt2hutyqkba.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2tedexepw.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gt2oonicgnq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2avocqddi.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gt2zsoevgza.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2gaintppy.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2emvgflhb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2jrkmzkek.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2fmpjzzqo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2avelrqll.html

[Q57] 行号
来源：http://dali.snrcjt.cn/Article/details/gt2uoimbcbb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2auoyysmj.html

[Q58] 累计求和
来源：http://dali.316326.xyz/Article/details/gt2fgybteuc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2vatdfwxs.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gt2pjrxawid.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2tjppxavs.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gt2fnpotnvf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gt2jnaungch.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxdfmkso.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gt2ibmmvkqf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2rxikeank.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gt2plazmslz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wokiizrd.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gt2baiggmsd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gt2erqoctxv.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gt2uzedhjzn.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gt2kuhesogt.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gt2agnhbrue.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gt2tmwchrsy.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gt2suyrkppi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gt2hnnpwotq.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gt2uqicdyhu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjufxhdm.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gt2hxhgghnr.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gt2wqlmfkqx.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2ctztdvhf.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gt2zlrrosfa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2qssykmcl.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gt2bzdctocy.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2zpvtqcdb.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gt2cwbtrmhx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gt2xpwyitbo.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2zkbxmbbf.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2uschkdmq.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gt2szweadgc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gt2qvkklckp.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2jdhrodaq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2abitvcay.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2oehvidrb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2ajbuqaiv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gt2lresxhim.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2ivqukece.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gt2cynxvamw.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gt2xeoqxohv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gt2eszjzfsg.html


<!-- 参考信息 -->