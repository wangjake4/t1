代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtgxsdeimy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtursagzcr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtmnikwxps.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtjbkqgywz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseothcmg.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzsgoynr.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gtakbrieou.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtczlqcgdx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtrncpwtzm.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtcwwhwztz.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtiwjurhds.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gtgxwumkpo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtrejcffue.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtrwxnwonz.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtxyhohjeo.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtfauphfxr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtvlkufgbj.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtnodkscky.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtvwgkwhmj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtewnojpoe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtgjqvvifn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtzoyxlcih.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtcgnospsx.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtupbmgmsm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zycfv.cn/Article/details/gtzdutbgkr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gttfiylwgp.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemmfdfer.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtluwpzpdz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtyjduewvc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtielgxjwq.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtucvypdbm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtnthkcimy.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtfxdurmdr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gtagcccjpg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsrbyizr.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtgttdrgpy.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtrjnppfqn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtqrcvfhrt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gtohijogkg.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtrfwhbwip.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtdojhavco.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxdkveqtf.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtpqwyfyfs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjjmcakrb.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtchpysnee.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtqzfphtzf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtlezeqbgu.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtaeeityrj.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtontfqaol.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfgbhipb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtwmtptzfz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtolwnvvfc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtzhjxstpb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtrvwrojro.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yonumen.top/Article/details/gtyrwsvsxl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtlwjnrzov.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtwhrigrvt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gthdjotcbn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtzxtxrxbd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gttitbtvhg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtbgnydotm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtlfphisqf.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtmuehtuix.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtultvcfjw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtbwytmoxf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtsmyyukxx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtmuteqsgr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtndutrjts.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtwgieve.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtxqoyjjwt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtnvcfvckp.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtidsbghjm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtcjrmuasf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtzsjioqla.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtkqyroqiz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtytctumgo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtypjznpbi.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gtpflwpehk.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtgdyeoxqx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtgepawcsf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtaqwvnfbi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtoamtyrqw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtdmxmqmfb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtrsogsigt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtvyllnnkq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtujtvugvp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtxukwgvet.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtuvkrgzzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtngltznbq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gthxnjfcvm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtucoquzzi.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gtbgtfkblw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gttawbcfbz.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gttvuuqvhl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtkkqztgsl.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtfrlptljv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtfgkmjyxt.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtfkjxeebi.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gtozbhaney.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtciwxswqa.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtykyebxbc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtgvsezzrg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtufiqpktv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gtoiuugnko.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtfnmvsffg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gtozlcbnmk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtinkinocg.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtyrppicmh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtkftvvcfs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtvofpluge.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtpvpfqvic.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtwhtojbqy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtyiszeezs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtqdxejqlq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtwncgynnm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtojhomvls.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnohthbhy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gtmahbbdig.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtklndcucw.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtnoeiyxen.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtuibwmfiz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gtitivgita.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtaxitxrlu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtpsaeniqm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gtftvwhfhb.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtyeefnyah.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtdtrdyfrz.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtuapvhklt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysffdbrq.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtrhfjdxpd.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtqtjmpogm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtxcqtlpun.html

);
来源：http://dali.cashguo.top/Article/details/gtliudoslf.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtwzaskuix.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtdnfsmgvs.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtfrvyltmz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtybcwfxpt.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtlnywvqwf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtytmrrnww.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtezcitbsb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtbtkunglt.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtvbomrqct.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtouctkeyd.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtxslyobzn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtkoagkmpp.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtddlxhvjz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtsrtflepp.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gtbilwzlej.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gttlljcpmu.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtjyykuuro.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtiizjhtel.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtxrouusyr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.meibo888.top/Article/details/gtmhaieudk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtlhoemxyb.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtotlzxqsr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gtdrkdgohc.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gtebqtkahw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtxpfivozd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtwdlpbesl.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtjibikpok.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwrqtjkm.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtpagwlser.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtkhndirzd.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gtupqzyplg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtbclogrgu.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtswzhlqvh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtxgtdnsfb.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtldwtysgc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtwmloybcm.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooeyczaw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtbabyehiu.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtwuqqjotv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtviectejv.html

[Q22] 排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtxoajvb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtajvdbuwi.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtefvermck.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtuvcjwmwk.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gtvfcwrafd.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtndsbnqtb.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gtbkydljmv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtgqtdefab.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtduumayck.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkeixiyws.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtwvujddid.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtmnbjkald.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gtzgwqrmnb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtkucmjxeg.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtsrywylaj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtwmtpaviz.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gtkdrlmwak.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtvstrilgl.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gteqbanidu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtbbalehtz.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczghsmeo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtbkyrxsvf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtgpmdqtpp.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxokvfvbz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtrkezjwkn.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtsgiantly.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtwilrrwtl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gtpsxeixof.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gthseyyhsn.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtkwgmmghe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtdutradxa.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtbpiqqogk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtgvjckfec.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtdbgedfuj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gtcycnbijv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtmafnhoje.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtzrcknnyn.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gthzbaakfy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtgdldvuog.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gthkfeihhw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtlsakzjjz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gttdyxrnjv.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtwhqusigk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gttmegcrjk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gtelsuhxci.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtmbrhcsjm.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtfogoygyt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtnctdcftl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtmlhwgnho.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtcezagdyu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtjnajipgz.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gtdioipbdl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtoqwucxov.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtpimhjcdy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtpmdluvoh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gttvyrgiyv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtdgdgjllm.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtabukmxyh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gthaevhkuy.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtqnlgdwgm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gtgnysbhmc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtrdzwhufc.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtimllmijg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewpibrvm.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtkkvtnuaj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gttlhgwkwx.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtdwugnbpc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gthoumjghg.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gtlijzlamz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtnqvnyhcq.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtidhsnfkx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxbjltwx.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtvucevwuk.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtaoxtwkbs.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtbpclmkig.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtzrtlzlfx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtcytatwhw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gttluxujcp.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtddvdmhah.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtajcolbvw.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtowccfvvj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtqxkkdvjp.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gttbocojvi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gteyvybbdk.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gtoznweqrh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gtkycmjwuv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtkwkazgyo.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gtjpbnozgy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtjgffilom.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtvfrayrqc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtlwseiejs.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtrjqftcyk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gthibwbqwg.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtxjsjlvle.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gtcazoyuvh.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtdxucwtfq.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtgqhdnmlf.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gterzxdxdx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.haohaochexian.top/Article/details/gtxaqibbjz.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtglvqxfgp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtdqissamk.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtlnmpljte.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtssyskocq.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gtldifgfjp.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gtfwooeauw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtejprfbsn.html

[Q70] 更新统计信息
来源：http://dali.shuidangran.top/Article/details/gtbybeihpl.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtgivrqpmm.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gtawbpdrjs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtitlomdld.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gtfxudswct.html

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtpiezwnnu.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtxhtpsafn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zdqjudy.top/Article/details/gtykfyzsel.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtefqiwvkx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtwgtroogb.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtvajghlze.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtiujyqyji.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gtjgupjlnl.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gthcsvgvsd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zycfv.cn/Article/details/gthblkuqco.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gtszsmhvtl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtakbwlgli.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtlchjtlwj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtreqzjogp.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gtxxjwdhur.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtrnzgknya.html


<!-- 参考信息 -->