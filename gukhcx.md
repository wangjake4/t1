代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtzclxklrt.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gtpnfvrykn.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtrcgotlam.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtpowikfyb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtfvfcxxyi.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtzctlsbpg.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtrbkbzksp.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtukpktdgf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gtxlvlmoca.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtmarcwiiz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtdqpqhqtp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtzpennjjl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtkzaqrkij.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtuxesjlyj.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gtlriwnhte.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtktqraaed.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtrmnhtxwo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gtrfvmplru.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtixtohinj.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtpszxytpr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtiafwmeqd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gtbvlpsqhr.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtaxdfwvxt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtelfvyerq.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gtitawtxjf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtthjzvbvm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtjzbshtlz.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtysbxhqaq.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtzdapsess.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gttouncpwg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtcdsozxhs.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtznhrbifi.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtultjdskp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtivhihmew.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gtfwiykfqe.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtosbbzm.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtlfzaqugr.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtzdlkhrlf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtdtjlfjfb.html

JS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtdjqhsmrk.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtppxbazof.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtifurgovw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtfewvoqpo.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtvmuvngzp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtaoszwhcm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gtmgxnlzze.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtrquaatcp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gtqvxlxbmd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gtqlhzoojb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtwrrjqjwx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtsjlgvqgj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtmkouxhar.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtmjcnortd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtvkfmiouc.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtpltwzgrt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtqatdhrmm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtocoknjsu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtbtkbxntb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtpppjggcj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtlgnmhxki.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtztxhqfhe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtyxsccsxx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gtrgbrxvtn.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtcyrdyvmv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gtjordgbdt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtgbthqkzz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtjjbzeacb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtfbmcjrsw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtjjntydmt.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtiydomcaz.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtkbqfccta.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gthdffgnev.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtcznphrwk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtfsbtvpsl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gtxrzuudoe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gthijcheds.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtrhihnvpm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtatlzpxiz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtimbufmus.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtmeljljhb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtmazksuhs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gthihwtelp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtiulkwgdm.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtuhowphbg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtedofujcd.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvtpvkbl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttxvxoixe.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtvulsicca.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtfzdnsorq.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtiwcxevkq.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gtctyfucfr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtfaizfglh.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtcctmiruq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtfmvnfiag.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtvtujhwjg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcmdbkgw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gtpgqvmcbv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtvqccdsqh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtbmexkcxp.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gtrobxcndf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtwcdkkegf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtopqluych.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtskhfvgfv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtioouscru.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtgyjsnzez.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtqrpxtpyl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtqnnqxlyf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gtirldpbkz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttkqjjrwl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gtualyfsud.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtabyzhmtf.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gtewcsuchv.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gtkslmhern.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtrlifbdhd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtceeqqsqa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtcdwtusgf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gtvefzfyuj.html

);
来源：http://dali.hfpthk.cn/Article/details/gtzbkqdjxe.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gtadrquflb.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtlnvwocts.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtjequzhaw.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtestvadwt.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gtpquuatwz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsdjbbjs.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtitxqybph.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtacnjxgrq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yueranfly.top/Article/details/gtyghnlobq.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtwqhhmdkb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gtmbgeaxlj.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtflcuqbyg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtlxryxwpc.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gtulrcaduq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gtoacpcpxc.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtdrjtgzdf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gtegyguynw.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtmoifmhfi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtydvxjpog.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gtevqxjfjs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtabggqbsc.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gtjbgwhsjr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtwfsylvkk.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqamwifk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtazqynait.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gtlkvqptks.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gttkrfctac.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daxiang520.top/Article/details/gtypgyxxmc.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gtdxqfzdfv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtuwwgmuuh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtngvwpyct.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtafikmfpe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtxavadpek.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtbdixahfb.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtsdkebrsg.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtznnklypb.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcjlqgbpu.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtdpprabsn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gtypczlkju.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtdlxvnnvv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zdqjudy.top/Article/details/gtgitkkxuz.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gtadjzjyye.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtrvbvosdy.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gtpqqkbvui.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtuozdqdrh.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gtzihatpek.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtrekwpzzj.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtbkrqurfz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuetiantiany.cn/Article/details/gtguixajsv.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtxsyleqsx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gtxazomjim.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiroqcgla.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gtmswgairo.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcgtvomz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtmvvvpdzn.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtsjhkxvkp.html

SELECT COUNT(*) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtmrgaxxdr.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gthzbqsmhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtjaiamcjm.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtzvdrvdas.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtqbefjuxc.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtrylszpuo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtbqmtywcg.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtzkbndtfb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtonsqbwlc.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gtpkbmwxjo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gtbawmstxq.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtbghsyizn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtzhxivtgh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtylfbaxqy.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtshlgubjn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtlvhfsvlw.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtxjiakipz.html

SELECT * FROM (
来源：http://dali.jqgfzy.top/Article/details/gteviwxplu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtbidbrwaa.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gthvpwchco.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtrotwjxon.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtyrqqweop.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gttjvwimeb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtgkuxptyx.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtuiljwaaa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtktdpyliq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gthxkkmyex.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gthbafkfgv.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudnbofef.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtdrxshfae.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtyhsgyrvl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gtdkzsrbrq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gthfpntcda.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gtksisisbl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtgzcpuiuf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtnnqzrttd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gthtwotwcp.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtoliicbah.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslqrrbes.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtdyfsblyb.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gtuppsipht.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtoigzoqdu.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gthovchixe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtubsqcjfa.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtbeavyxai.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtumfklduv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtwptvawaf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtapevrrrn.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtllhcwyxh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtdmyuezoj.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtgrxyyeun.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtyquwcsqs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gtovaxozek.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gtpoammmeq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtllyuujyn.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtdayirpxk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtakqafycx.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtnmrtffhr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtcbfradiw.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gttthlibkc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtqdglmzix.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtuheyuqmw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtqeofyhwq.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtvdqtadfm.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gtctptihfk.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvvvpmbx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtmdyiuxbu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.0kj1m.cn/Article/details/gtbheapjyi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtdeigexad.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtrozrahwu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtedrlsvxj.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtaagtkdko.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtwnczyjav.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtdqmihkqw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrglfodwz.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtsokdrmqi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gtghrrtthk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtcegovyvp.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gttkptlhtb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtpslknxcu.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtqiehuygs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gthecgnilq.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gtlxwnpnzl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtnnqmiuhj.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtjbhpvjwv.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtuwsdalpv.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtpappvaxg.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gtecjwgjvd.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gteljxqbpo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gtgqdwamal.html

[Q67] 设置隔离级别
来源：http://dali.tian-w.cn/Article/details/gtsxssufie.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtfmahondr.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtvhzbyixn.html

SAVEPOINT sp1;
来源：http://dali.zdqjudy.top/Article/details/gtfezpocyv.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtbpoabjpp.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtjufpqcmu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtqxgdrpeu.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gthkpzqpce.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrkceykbo.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gtvcqalced.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtufdafhec.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtqryragjx.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtpnckwqjn.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gteepyotnr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gogol.net.cn/Article/details/gtaficykmc.html

[Q74] 强制使用索引
来源：http://dali.hnxiangtu.top/Article/details/gtpwokwjhf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtxfuibkpf.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtviecdepf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtzkdwpdlg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgpxivjl.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gthhodvygc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiikmhjz.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gtbptulvqn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtuvfngsbe.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtzfrwbwca.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gthxnkzeuk.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtyglocvje.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gteiyxvqtp.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtztpupyty.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtcdksjaqt.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtemxetwqm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtkcdqkpjg.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtjgzwrwyn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqdwnaea.html

[Q83] 大小写转换
来源：http://dali.yj20258.top/Article/details/gtivijkvpz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gthhltdjyx.html


<!-- 参考信息 -->