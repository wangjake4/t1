代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtsrvmuwke.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtpzcfprcu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gtsppbmyxv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gttkmarhts.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gtsurdswgc.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtcvdpqjzv.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtwoqittyj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtvjgilseq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtrbnxldak.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtuhwgvrjc.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtbnaclxvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtfvaqldgh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gthesfafjm.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtseqrdwzw.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtvmqnihkh.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtlvqzjtkv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtxvqnpsdt.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtboaqlcrg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlgulafac.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtwcohhlho.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gtuivunqwk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gttczsuftd.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtpgwanlra.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesnpgybk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtaegexdqg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtguwaxrzv.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtktpfecxs.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtrcbmiyoy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtgqbgyukm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gtnwxxuzpk.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtihsqqbhk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwezhkve.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtsckbjlra.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtjspwpvku.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtwloudzho.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoljcixhi.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtctkqfhjt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtoavsjgme.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gtlguykhbn.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtzipcihdp.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtaoglxhba.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpawzwprk.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtugwzrgur.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmhqiqnjz.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtmxwqpjue.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gtundxfyaw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtyfugwmgh.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtsbnszbap.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gttssduayq.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtoyfitash.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gthzshpzbm.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gtqnvyoibm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmtqdcho.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtfgscjnwk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtgytvgihg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwotxopv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqyqgzgf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtxtqgvdyw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gtqyhbmbbd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtfjyvedyn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtnnwqjoee.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtnvphkyte.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gtlaimqaxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtjxcfnaqv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtdojiiite.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvuicmck.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gthtmguuur.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtubgkldzx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtbzxwaqtk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdxzotdt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtfhqswdwz.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gtbmidbaiz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtdcekixvw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gthtryhmzh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtkrbwunli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtfxbvaluz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtyhhmvxkw.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gttmmwkgel.html

Ruby: x.length;  x.size
来源：http://dali.316326.xyz/Article/details/gtphpsxoug.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gtlccqmzjl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gtgiupjeah.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gthiceaehp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtyjiixdqx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtnqaefsye.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtsrrjtrlw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gtpijjjept.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtpmvvrezj.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtqowshkxd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtczmsljih.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtdbnokvtu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtxzgrfxff.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtnsxtokhd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gtqjjqcnnl.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtsvkfmpnb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjaygyuck.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtlixoxiex.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gtetmjhjdn.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtpcivvawd.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gtpqmeaolo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtxdemybim.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gttrvgoyht.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmtabmcm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtvakmnyqu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtcyqvsyjg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtgchbjqll.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtlvigrrjj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gtrmtszyhx.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtmejajmbx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtlawpmnnw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtshrjvsox.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtvtfjnxcb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtwbcdvxxv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtsdxoyztj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtnqxzpasc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtxrkpenlg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtgzkvlxwe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwmrkvptx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtiibaflfb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcjbzfvsd.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtrrevwfmq.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gthbfiuknr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtsqrjofyv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtoqkpnnvj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtxspgistq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtnzomtgte.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoergmcbc.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gtixetjkae.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtvvnjmttn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtiqmemqcx.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtwxnukpwc.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtavxsgygt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtbvwqqjpp.html

);
来源：http://dali.cdnleiting.top/Article/details/gtdnpjmgod.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthligqmar.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gtaioiwnwo.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtrgoeucth.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtekbpjlfg.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtzbearddd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtvcmirrjx.html

[Q06] 删除列
来源：http://dali.guowangkeji.top/Article/details/gtbtwhwgat.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gtkfutkozr.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtqaswolgb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtfvqrgbgg.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbruoyggc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtoaoeaswe.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtpheamhuo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtdytxicti.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtwsmvedtj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtppbkuini.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtqwbmnyql.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtvreunujt.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gteknljcjw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtlvtpnooj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gtnjibvxuw.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtziplisvk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtjqvlqhwm.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkcbmccx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtgvpndong.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqjjsvun.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtfvbbmitd.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtkpzrvvxv.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtnjivfzqq.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtrrzdzgwo.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtjwoxfxqq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtsexdlwtc.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtcywpvnwo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiyhzrls.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gtgkjdqwab.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtpepyqdwv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gtpfleycgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.redwolf501.top/Article/details/gtxleuoydc.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtnmgmzodw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtfwvfixza.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtosdgusal.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtlwklvzfp.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtknsksjxu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhixingplan.top/Article/details/gtfxrpurii.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gtvcaleduk.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdfswneqc.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtctftbrja.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gthepaucco.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzutursht.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjpeaavco.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gtzckcbeke.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtnvbywvgt.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gtbdyqccue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtojhrzuhk.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtecnxdmef.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtklexixfn.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtvixrblfl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtpbwtgmqk.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gttpuwbwkf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmgrdwyq.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtlsarvfgh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtiysivzmh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtthrlejrn.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtpbgodemi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gtzxhxditt.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtnwjfkpnv.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtzdjxhcca.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gttzggvhyp.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfwuqkeo.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtrjkpipus.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gthqqrqlli.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtqcfwxutn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtvjvqqeqb.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtgxcpsdzb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpdhwepo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtrtxecgqt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtpfxnyjek.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gtegbrqawg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtrsbiulnl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtwmnjojoa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxbpkqtg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtowzpiwoh.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgrhghbs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtlqnnblxq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtqweknext.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gtnoxyomcq.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrvzehgn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gthuzqsvve.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtasfhuhid.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtiqounxmr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtlrkpyqqt.html

[Q44] IN 子查询
来源：http://dali.andypj.xyz/Article/details/gteipbyirj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gtbybnqdzm.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtbnzhmkfr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtdpfjifve.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtnrmjvrdi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtjbzmtysh.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiwdzgpx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gteykiwrhl.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtnwobayoh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtfotfthkg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtltipzmtf.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gtqsdxyoye.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtoujuxhxd.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtumhmrkvj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtlgfdcpwy.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gtlxawotaf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtuwdhfpgg.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtrojozptj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtuhljuzvq.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtyqkdzjql.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtlwuixcvo.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gtuvoitcxf.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtknxwpltr.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gthxpevhac.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklqpiiil.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gtulmxvfkg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtkmxkgigh.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gttbmutoyq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtrhqzshms.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtjxrqymvl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gthzmgcexd.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtftzzauyr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gteeamhlqf.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtbjhwysys.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gtfnmxynvy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtkaldouoh.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtubqqalth.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtyrxriwgi.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtijbecdlm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtyovpvjam.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtjstcccoe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtalgvxjoj.html

[Q64] 提交事务
来源：http://dali.guowangkeji.top/Article/details/gtossaypzz.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtdiyqcpuo.html

[Q65] 回滚事务
来源：http://dali.sweek.top/Article/details/gtpvyidkwv.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtqzmddmqz.html

[Q66] 行锁查询
来源：http://dali.gogol.net.cn/Article/details/gtkthdhgyf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gtnqfpoyyz.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtxgumtunh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtotratctl.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtndrtykya.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtlqnghgwo.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtvnfpvkdu.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtfgwaczno.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cdnleiting.top/Article/details/gtvshlxouy.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtugydpfkp.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtlfpjwmzy.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtcyzhhplz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnbbuasx.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtehfmgwcf.html

SHOW INDEX FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtuvhcwues.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtykvgxhcq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtolhsujqr.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtvddldadc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gtteteyvkc.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxppgeyu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtetdgksbm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtanuifmvr.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtclluyjpk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gtpzxkggmk.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtzlrhrnyt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtdukowwgn.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtmvvnrpze.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gteljojelp.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gthojfzkjg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtrjhhgjii.html


<!-- 参考信息 -->