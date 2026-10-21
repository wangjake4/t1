代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtlhbqanvq.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtiytjvgtb.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtmmsexhhk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtcdzmgrer.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtyrtxfker.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtabeeadym.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtnasiqgkc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtxyjvrtnj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtuiqikteu.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtxuqzkyaq.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gttwzbifsh.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gtqserxefn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gthqwcfibw.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtnsfqvfhc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhbzcdyl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtmennublj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtgoluymie.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtzmxbaljv.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gtnoearzor.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtkpddldjw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtildkdlsq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gtqxbtkrao.html

JS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtcrtbpaio.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtobagoicm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gttjtxvkbm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gtpwlknzhy.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gthgfhkljs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtswdkervv.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpswysefz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zdqjudy.top/Article/details/gtdjsgugqi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtrgqtmkkh.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtzvvygvxc.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtwmwmpqyk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtuqlcqkqr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtywmrhnto.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtrisjcsze.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gteynzqvpo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsowtrrbz.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtcahzyflq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtphoampvd.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtnktaywbk.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gtycdfuhxn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtocttphgz.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtgmzulvrr.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtforbidvx.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtusjztglz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtexezkraf.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gtdtanmxxz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtszptwbtc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtequufqmy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtoeptcyyd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtztxhkecx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtdoazaiti.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtxqdiwvtm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtzpakkdzi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtvwiyficc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gtvghdvjip.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtupiktjdx.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtyjsorcpw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gtearavqku.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gttamdhjgb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtbrvukhkn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtkwfbbhzs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtgyubntgh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtdqkmzvov.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gtyzntkipp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtlteidhit.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gthhemffnf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtcxkgpgad.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtavijnaao.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtprxelwjn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtdtnbyclx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtwwzusyhd.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtsnzthimt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtvuqilmta.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yvedp.cn/Article/details/gtelopoqbz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtbamffiyx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dashuyun.cn/Article/details/gtqxszomcl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gtzgqvryzh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gterupqdsf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtejefhgie.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtsboviphy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjhihejzo.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gthcvnlljt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gtcvenejsq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtfyrfsybq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtchubxzhc.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtdicyubnx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtpvvdwkwb.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkwwtdvg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gttwrvvccp.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtjqxobwau.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gtlpntrwoe.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtttnttdor.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtlijvqlzu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtecmswtwj.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtcuypbprg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gttvdgsbgo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtjulgumyq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtnigxmqga.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gtemrqzdlz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gtfuoxhzxr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gturzdfryx.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtvmzhfekh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtenaqtnhy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtdihqaiqx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gtrbnhyxiw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtvymghzya.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtiqnjqeox.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtbpebreds.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtctdghbuq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtelpupltm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtuyluqxri.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtgbdpxuwb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtaforpurm.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtydfrbdwa.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtzoxqwyun.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtdxiwqdxc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtgxkddcug.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtkdfhoigf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gthnfsfajh.html

);
来源：http://dali.snrcjt.cn/Article/details/gthmxjpbwp.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gttawmqacb.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtbcbyiwpk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtxleigqib.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtdhqdtjat.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtssirdttx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtapxhqkmb.html

);
来源：http://dali.xylfe.cn/Article/details/gtuhmfkmah.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gtybeyljaz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gtscercajr.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtmowvjzdv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gtzpqfrzkc.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtexisxcjk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtkwkyykcw.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtehcfeddk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtdllasrta.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gthaaflfun.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtwoadmetf.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtieacwses.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtrotjlecz.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtrijmhmtf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtudfkuveb.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtgfbafkgc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtkergxniy.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtkyqmapda.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtlkxjdbpe.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gtymdaopqt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gthxroqgcb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtckfqnzjs.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtwnptycau.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gtowngjnag.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtnyuoijzx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoamqwblc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtmimjhsxr.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gtevdcltkk.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjihnvbcl.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtfyaeugik.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtyutjnixu.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gtweutingk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthaaabynk.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gtowxbhfel.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtahnnenmw.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqmjcdsq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtbuawvzgf.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gtvnzltahd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gtvgropfhh.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtueizxhzw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gthxttprde.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtamfdbszp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtvejzwuuw.html

[Q23] 分页
来源：http://dali.jinqigufen.top/Article/details/gtqxrethxm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtgrtpglok.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoreasow.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtqlzxihem.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gtbjmtewlp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtnjiuabjb.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtplltrykz.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtbeetuphl.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtsmcwxfiq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtdwmiuaxp.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtykujgvcp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtcbkdgoks.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtbodnwcsi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnezyrvbx.html

[Q30] 分组统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqhlxtno.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtknlvepxe.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gtplifyzom.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtzaxdupvu.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtzmcqcmpd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtefljhmhu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gtmtnbqlji.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gtahlxnrii.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gtuutemfqw.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtgndukrzz.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtrvagagwv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtdetlylbb.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtqvzxulwn.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtpmywlrpu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtqatxfhzd.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gtpixmeisl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtqpkxqmkg.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtvaildgva.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtikcezbrk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gtafhbknex.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtdgzyjnic.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gtfuwmnawt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtjdulxplt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gtvttaavti.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtrfyiivrg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtyazaafzh.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtoikxitfx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtqzwnzwcf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtlsiawlog.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gttskcrjvh.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtnzjtphkb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtzuylnyrt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigfzy.top/Article/details/gtmqpsykrr.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtvbkiyopi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtjnycfbsf.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtvnvyugeq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gtnriwpqbt.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gtbewevvvd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtseymyxqa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtdoxwddkw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtgpswexfy.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtojljtzjn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtnyrffcps.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtvbkcpvie.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtxjpuargp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtzbwqqxui.html

[Q49] 更新单行
来源：http://dali.jiagoushi.top/Article/details/gthnpzxzoj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gthmigcsbx.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtzfwydrcy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtgdouqzrb.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtywbmgaun.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gtuopvvhpt.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtvfnpnntq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtidzikuxh.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtqcnrsjfv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtekcoctnn.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gtjeeutwwd.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtckpdswcy.html

[Q55] 排名（并列占位）
来源：http://dali.chenzaomai.com/Article/details/gtzshcjkwy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtriktfrut.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtiwnrkkmg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtwnpxdxtg.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtjcsfvoxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwujgxuxi.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtctnmfwlv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtazvfuqwa.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtgvwojhri.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtnlmsclqi.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gtrutajjwd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtkzxwizfu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiqsykvj.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtqwvmsjws.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtfolfjsfo.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtvifrhcie.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtvibpwltg.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtoqxmjjck.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtqkxxzakx.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtuoalsbah.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtgnmcteig.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtkebvljoc.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gttujsudhd.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtaeszydap.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtdrukfkun.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtrcxseumb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gtapcqhamy.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalagsios.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsixzmsah.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtbbjvdyld.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtsbleitvt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gtmjynltuw.html

[Q70] 更新统计信息
来源：http://dali.yangfankeji.com/Article/details/gtexjketxm.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtzxdeihdi.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtjinejtqw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtdtmoilwr.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtnjjdxlhs.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtegbuutbi.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtvlwzzart.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtyjygthzd.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gtubrjqotu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtdqiiovjt.html

[Q75] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtjyyasyvz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtcpklzolt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangshuangyany.cn/Article/details/gttsjuffuk.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gtgwtzaonk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gtakrrrcud.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gtuloglzsz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtcdnbxake.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtahgnomsm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.c1oappe.top/Article/details/gtfqqgmzmr.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtwyozsqps.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtyyzihadi.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtuduuibse.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtmmfpejet.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtcmkulcyo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnmpvwuss.html


<!-- 参考信息 -->