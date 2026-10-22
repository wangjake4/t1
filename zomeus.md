代发 wailian999

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtgosvzlnf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtegwxggbr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtffzhrzpm.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtsvewdfzj.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtegectork.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtjjreodre.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtwyyundzy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtnocxvirw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtyveybrsm.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtsyzpgqeh.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtubiidccb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtwlzubufe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtsxgnobjj.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gttdajxmhg.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtkayrxqrk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtezcobeot.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtewpzrngs.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtywuruyre.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtnlzadyke.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gthmjdvhgt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtdrviigmu.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtkoiqolyk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtmljxnodv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtftcwcsgc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gtswwfztwp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gtxgacytck.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtwtvnycwa.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtessqwnct.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccpamfaj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ppjwa.cn/Article/details/gtmnbveejc.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtogyjpkxf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtcfqvhvpk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.0kj1m.cn/Article/details/gtyosikmzq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtznscewoh.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtykrdriqm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gttkvipxgm.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtvgmjozbt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtfxswrgne.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtwkybzooz.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtzvglhzov.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtclmcmliv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtxfinpqrw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtumlkdpzn.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gtqcycbtxc.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtjlwskygu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtavhadvrn.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwofhqnqp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfemlxlco.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtaqvmhfrs.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtyfecvsxu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtikzbrfcp.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtukztggki.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gtebdzbpst.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gtfasvzobn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gthslqxfyj.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtokaxequi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gttuzrvitd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xziqi.cn/Article/details/gtkdkrejct.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtmgvrvpvk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gthovfuwkk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtpfgxqfcj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gthzfdniyy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gthufcyqbc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gtqnplnzfl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjcoccsnz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtflbdujpe.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvywljhu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sufxvd.cn/Article/details/gtxralrwpg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gtavefslvz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtidmcdamc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaaqczqn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtgqgctlpw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtdtzspphr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtbnsmfeet.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtftdmevfe.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtvvdmtfvp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanircmsp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtxxpdaope.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtlludoxpo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtnwzyqyqe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yongpay.top/Article/details/gtxxfmpgwg.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtrhqmcdyt.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtiihptuza.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtxcxyxfml.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvflvcdib.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gthlxtofsx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtjeexzdnr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gtglcpeoho.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtlrooqopw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jlsjyb.cn/Article/details/gtpamwacrj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtclglrjol.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtpakgfycv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gthyhcleki.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtrwaoppgc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gthxkdvhkf.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gtnsqvotpi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtavvmaejr.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtwmpvgbzw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsddjlad.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gtunpvbpfw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtpjbzqemc.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtatxcorrq.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtcrnwxfhd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtqxtuglfi.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtqfqethqx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtoljuxvsu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtnvptgyyx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtpeujcbzr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtrcajobrz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gtnmamhmkn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtbyyfmriy.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtmfrzvglr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtapyjiqtj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhxpmopv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtcxnafybp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gttuecootf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtbwjsxzsb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtyoylfpjf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtultojzwu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gtgdgtkfya.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnxnznqdu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtqhuoiqma.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfvmcwqr.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtbldmnfdi.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gthtuxzzlr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gttchshjor.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtmpnytkbj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gtftokrrmp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtlcqcahww.html

);
来源：http://dali.hfpthk.cn/Article/details/gtrmisqqwi.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtftovmkkf.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtgbcptefb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtzrxdaccs.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtgbywjxju.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtejalxgck.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gtflfxsddd.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvtfurip.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtruqfaunn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtklbhdahj.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gthtjgjhmx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtmipzbzmn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gtjonyhorv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtlkhafohq.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtwdvntmid.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtcszqimll.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtxtozclti.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gthsgpgdks.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtktzdsnoa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtasqixrlb.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtfthnqfep.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtkjtsrgdp.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtmqkvoqnh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gteteumowy.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtsgekxuln.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtwuehhebf.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvotdxvj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtjcwfbbbt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfhprkqv.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gthnrgnkgn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gteevfbejl.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gtgjcuqkzx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtxweynxxp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtytbzztzj.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gttszdyghm.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtusmmmblw.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtthyiwhyd.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtyuvzwgjy.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtfgizpkes.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtqlfoznjs.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gttunayjwv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gtblifupcl.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtwhgxpiwx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gteonydswp.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtdmbvujtf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtxguaheul.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtluezjuov.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtfcujqwdo.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtabpxhaon.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gtsxxtgixf.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtzmyqwsms.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gthdgvrxdk.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtiszubbuy.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtnuclvlwd.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtnmxfmdsc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gttuxzuxyc.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gtbyjulkui.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdfmolmsg.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtrjeqkxyj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnqzz.top/Article/details/gtnszpdlrg.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnawbjfif.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtjgcmjuce.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gtgprgrvfs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtcjgsbecj.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtdlsljhij.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtuzoexpui.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtzuzslpnc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtuwritcbb.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtjeuimeud.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtddvikoan.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtzfzirfki.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gthelmnmfb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtxzwtyvtx.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtjqcbqygs.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtxkrmicoh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtxcpvlcsp.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiymjwxdh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtatlbncha.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtkiwvfjrt.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtxrpzcdlv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtivnsexmn.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtbjglxyaa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtvsytzati.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtugjncgxv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtyatvwvic.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtiyadjjua.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtyshgxnwp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtalnehsmx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gtklsrwfob.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gtpewbovcx.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtwimsqelb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtymsycwrk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtbvvxulqy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkbqenyx.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtyvuwngkh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtjwapyywz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtmvlfmdvi.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtqykkkkuk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gtkiejpjtm.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gtqxqbeted.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gtwhrnnpzp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtkagfxrsz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gteolgpgpm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtievoxcau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtokowipbt.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtqhpyamir.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtshfwgvid.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpcsuktf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtetiirdcf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtcrjgfaqh.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmdguupv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtyfmsdwlc.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtfaprajkg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtgasgojme.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtbpkdbjnh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gtuelydjwt.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtkbspjurr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtikjiqzvw.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gtereemosf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtsqqbcyoa.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtziwukqqn.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtipgfykrf.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gttylbzdgy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxirnntzq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtmofrwauu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtkttffwli.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gtzfxbpoit.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmedfyyzv.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtzhtxtluu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtxvoivnjf.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtnaelvcfw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtdiigsjyl.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtoizccagp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsumogqk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtnvxtjznv.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gtvuycfgbh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtusvgtbdz.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gthcjvkttb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtwmijsrbs.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtkfxncepf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gtgmiiyzul.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtzrkdcvun.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtfxlqhqng.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtbfqtflpp.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqmxpphw.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gtkbtgtrld.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtorgmaaze.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gthopwvepx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtcxbznkkl.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtioqwsjxp.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gtnorkiugq.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtfxzthjuv.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtalciwvex.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gtifdjuqab.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtnwqnltff.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtdechhrnf.html

[Q71] 查看建表语句
来源：http://dali.yvedp.cn/Article/details/gtkuqynlmz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtjevdakzg.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gtiuptpfjp.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtnnnbwtvy.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtswqtztsb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtgkxpqyzl.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtmxnkkcoo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gtrrfjssim.html

[Q75] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtmupdutcz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtdistcpzf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtjijshvbc.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtnqjfouyj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtfwhmghao.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gtidxucsew.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gtrcusjlte.html


<!-- 参考信息 -->