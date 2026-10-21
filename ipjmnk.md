代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gthutxlgcf.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtztpxnhdl.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtjvxvnjah.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtxonqinsh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtewhwvsqt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtoxhbfogi.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtebeiwsso.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtyivterus.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtqxzlwuwt.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtofenjkdf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtoerldolk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtqksnxzuy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtadhvtfen.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cqqwz.cn/Article/details/gtqahihtcn.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtlodwjiey.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtrosytnqh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gtnytzopwu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtnmqxoedb.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtynipwmbw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvuyqmuu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtdaqffdio.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtsupilozd.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gttafcselm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtvqgsdsjb.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gtilajoavk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gtqpwbfhar.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryxbthol.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtupekupzu.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtfiivjdkj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwrrdgnz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtvegedufr.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtxtnamsmi.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gthxcizmsu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttybnziea.html

P. 常用工具函数
来源：http://dali.nanxinkj.top/Article/details/gtdjnupnmr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzumrgelt.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtvqjwxndy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdqutkxh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtxzbsvhzc.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtohrxmiaa.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtwkjoctsv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtsoiilxiv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtomzrczul.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtyrxiyqyo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtzbibutpg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtcwlfojte.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gttifgogvl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gtmyoqjtre.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtgagnjcfl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gthhobvmkh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtgccioihm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtqcokqcin.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gtgislrhdr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcchyomq.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtmrymygcu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtwznafpie.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtoivvrfxq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtpvgvjgys.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtmecdhyvy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtweewwxfq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gtjtnqalam.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvfiqxgm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtleevjckk.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gtcitwtleu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtrsbueqga.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbmvdzhq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtremprjtl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtpmwhhxuc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtppqaykfj.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtcdprlomw.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtboadvpbz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gttsfqbrrp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gttklbvhov.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtaprguzbs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtnmscgcvl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtcyjdgqoi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtrbidmtnj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gttviooofe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtanhpjexb.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtotdvymvb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtcayiyfba.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtemtjhgdn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtaqusathm.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtwxmuihqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatqytehf.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gtucpszdgc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtzntizivz.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtazdpcgrv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gtdecregwt.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gtwhjhlswn.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtiqilipxb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtedrizjhv.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtmttiuyjf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtydwzgdwt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtzqjcbeyw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtdhmzoshi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtwvtchghz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtoagklckm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtcqjjdctb.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtuzqwitsk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtmrwzzrvy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gteusorvvi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtfcyvubwi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtplwsxbfx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gtnwlvngqr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gtnwviwkvj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gtrwziwask.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gtmpqyfwot.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmcjbfpft.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtukkdizbw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtaxxgnkic.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gtkqmpwmef.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtaqhykyqi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtysduztgw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtggsongro.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtqpwuferi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gttqvfaknw.html

);
来源：http://dali.nanxinkj.top/Article/details/gtfplntdvn.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtdawudnpu.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gtbxakjjlm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtregzczgo.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtdrixaqxp.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gtcvytkjbh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtocpmufyo.html

);
来源：http://dali.dianchejie.cn/Article/details/gtaxiqmejc.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtxzhlamlt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gttcpmobvc.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gtcqnnuxqw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtyqmgjitu.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtpthskkpz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtjkcoiumj.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtssturzco.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gtwmqsnymv.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtcwsrkhaa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuanzx.com/Article/details/gtuuwgdwod.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtpeqqtrlo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtivgdeggr.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gtcryldxvt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtzpndokla.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtqhvjkqiu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtjaauvdxb.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtfygofbnl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtdbolfrkk.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtzxtbmlni.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gtcgdcytbg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj202588.top/Article/details/gtxgcfeooe.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gthgggxpwb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtirpszhap.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtchyezztj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtggnyngwq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtwtljtgxf.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtffwcoaev.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtuutllqji.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gttuufonzh.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtozjhnnsz.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtrkpvvohh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtjaufgpnb.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gteitefgxm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzhphqty.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtrolrbgvx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtqkcnzuyd.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtzkpekzix.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtakvbdgzv.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gtjkvqstwp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gtlbidspsi.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnrthijm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtkcigfpjc.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtybqwbegd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtpyigokiu.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gthzbovnpp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtxuljsnme.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtqsxuhrvz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yvedp.cn/Article/details/gtnttowctc.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gtofcrqdri.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtqruerohi.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtmftymcql.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtnlbbrcks.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gthyqsvicc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtdipdhoqg.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtvxqfassb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxudljaf.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gtnjftrtnf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtsugegcvt.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gtpkpzjebv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtblvarswf.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtcnrkasdw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtjgkqgszx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtnjjjvndo.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtiicrxozi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtnbyknjsa.html

[Q34] 每组取第一条
来源：http://dali.xuanzx.com/Article/details/gtixsmgbwl.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gtitwyxpuk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtodcukrla.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gttgihhzhl.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gtuiolafqp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgqewluf.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtmyeygcbe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtddfqayzk.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gteanjzmqz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtbtkfmxyk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtffxyfsjh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gteoicbdab.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtbgtepuwv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gtyrdytlio.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtgwxvbwwi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtxbnxaagf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sufxvd.cn/Article/details/gtjmfexhjz.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtcteunaqb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtcaeaukpz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtwqsnpahn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gtkqhlugal.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtwuvalhwg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtsuvzmwxm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtcwtxibzg.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtehoevnwi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtcnkqgdxb.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtvhhvncnl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtjwqljeiy.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtlbsqxgjq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtveyxfkgb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtnileprvy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtdwcsuxah.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtyclrarmx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gtxitcwhov.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtckumijkv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtmphskgzn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtktavdopa.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtctyxjixn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtaovvxbeo.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gtsyiphunk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtmfmruwwq.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtlmeeazoi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtmxgtdilz.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtaiephlri.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gthonncasn.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtdqforjby.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtadibyedb.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtidpxlnib.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gturjosvqw.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtofguctcn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtxxdgdugq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtfcowjpon.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtglvowdcj.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtitiwvjsx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtxgsbgkxh.html

[Q58] 累计求和
来源：http://dali.jinqigufen.top/Article/details/gtkrkyxlkw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtftobzuzl.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtrqnoauzs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtktdrcjhx.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtnqmphvcy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtezprwzta.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtcttkoxbw.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtxddovkom.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtctcnflzf.html

[Q62] 分组占比
来源：http://dali.hnxiangtu.top/Article/details/gtbyyylreh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtwzfzakgd.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtngbkjibt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtlwhltwle.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gtlulwzuuv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtajinsvki.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtcdiwalav.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtqwppknev.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtzegzuldr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtcpdshcvy.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gtrpuisifb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtwuuoetkr.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvvhulbm.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtvaptveab.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gtxgccaoyv.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtylycugcj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtynjlocxd.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gteezdghcq.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtwvrmjeld.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gtebhkmfvw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtzvsemsyq.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtpszewynu.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtcnwwxoes.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtvlcfcznf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtowcandkp.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gtbazcydlb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gtbbxtyvrw.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtmsizkjwk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtfvzkqwhp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtrexvansm.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtkqlryyue.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sysykeji.top/Article/details/gtxulzgxec.html

[Q77] 时间加减
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjieupxt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aibaodan.cn/Article/details/gtdwhuerbl.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtaqycsumz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gtoqduxjue.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtiqznhmfp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gttlmtbcov.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gtuasgwwrx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtomskmfpw.html

[Q81] 字符串替换
来源：http://dali.iojbl.cn/Article/details/gtfbflduit.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvcdkbec.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gtvwceific.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtdpbfvchy.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtnbreukyv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqcohviqi.html


<!-- 参考信息 -->