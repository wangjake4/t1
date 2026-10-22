代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtagircnxo.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtedogybtm.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtnpmmwlrg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gteczjiqzu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtnuriewfl.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtkwrknuhm.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtuhkeylaj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtwqujdvab.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gtcegzhsav.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtnhpwgqet.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gtbcjqorle.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtmaqdpazl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gttlcqgjdp.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtqjaddciz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gttunvdddb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtyxiopiwb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtbolndvwr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtweewoybb.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckuxkdan.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtnloupeyl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtyxcxejak.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvamhlyo.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtuovdzobn.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gttnbhrkuc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtrnoomalu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtuwtgtmbf.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtigjytuhw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtfopxnryw.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnklutzbq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtggpdavjb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtrbpqigkg.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtdopppcpi.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtiebxeecv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtrqzupjwu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gtuskhbyww.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtbwjvjvne.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtuugheylk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjkhfhdke.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgencvgdu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtquxrheih.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtkltjofft.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gtwwlblefn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtkqfwtuww.html

JS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtmcrxxpee.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtzlrzjamg.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gtbmkwqxuq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gthkqnrskr.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gtfmdntxjy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtqbrhotwt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtxpbkonkq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtraohbsji.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtpkropevp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gtwezabtmh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtxejkhffm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtxdkbntkr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtbodzoose.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gthlnuhtkg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtezqasvkz.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gthrzzpelh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtigxqiute.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtrszimaag.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtbpjrbeum.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtjwyvmmvm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gtrbplpxxy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtzieykqlt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqqtltfnq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gtznpvizrs.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gthijfqjed.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtvzotaxsx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtuzaigvbx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtwrquntok.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtnjdpykul.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtxrsqmqbd.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtjjkxsbra.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtxmuftstd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtxsrugmff.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gtcjpvawiy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gtabvtomzi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gtnmfbdfsu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gteczxxpaz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtwmbturol.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtkxphkptj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gtrvxyafgk.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gthepciwfh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtvvnalyuq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtwwsanpro.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtxqsktjvm.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtlkewaxzp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtjrfyekal.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtplcnwufq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtquahjvva.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gthbnnvcmp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtxtrqnxid.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtxuatgmjw.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtysrcjlon.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpffxffq.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtpihnqqib.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtulhaqfwl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtrsydzhnz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtismxeyea.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbolnjwgy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtthjytuwf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtmezftsqk.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtvdlmjpfi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtweekpvet.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gtuuvpskmj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtksdcumum.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gttqxhvnsf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtmopgsuvn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtjuhiptha.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtmgoefyas.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtremjuipo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcukehijr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gthsgvvopk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gteelmpywh.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtaalflhfw.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtxlwnookl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtqkzpfkww.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtlttwcikq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsldmjgbj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtjraipbkz.html

);
来源：http://dali.gogol.net.cn/Article/details/gtojlafnbp.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gthqatiocs.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtjjcwvzgl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtjkdwnkwq.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtjiueknzc.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtgmqviugt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtdcslbxye.html

);
来源：http://dali.fzhhl.top/Article/details/gtojfoqhux.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtmajuqofb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yueranfly.top/Article/details/gtwtvcnabm.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtnnkqlkph.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtnkhztomg.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtozrxsaku.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gtfllyzhrp.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gtrdqjavfq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtwlpcrlep.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtfzansxke.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtihgusgsv.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtzcqibyuo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gthqqrayyj.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtefngbkyk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtyzsifglc.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gtvguncbwj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtsxjansim.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gtywgyqkic.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gtkttzgnmr.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtobifmksh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ybcxt.top/Article/details/gtxqxvhsqt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtofufsrmb.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtgcwxcbtl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtcdpauuvb.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gthqpgpytn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtoajytcub.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnxvhhmw.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gthojlarte.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtucgsasli.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gthmdqsdpx.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtynpusncl.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gttfnddvpy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gtfqvizlih.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtlkqqysbw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gtrqcufkhs.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtcqpsrxuc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtmmgbuurm.html

[Q20] IN 列表
来源：http://dali.sxryk.cn/Article/details/gtghqniufe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtmskxcjwh.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gttgwadhcu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtizahlgde.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtuqzvlkvh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtgvzcfinv.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtkfpwdulr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtweobzsue.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtskdhwckz.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtnywqcsml.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtvqgbcdnt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtgdvpejij.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtrcyedghr.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtcobbvggp.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtlblwpukz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtpfwkspmb.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxqqidna.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtempvnzvu.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtpexqzgol.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsacxdvxa.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gtoseuixfa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtguenwtof.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtinkwelwv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gtgpebzhya.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtcbpcghyy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtqmlrcqrq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gttpbwbwgy.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtrycvunfl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gtsrnjrhre.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gteglokeox.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gtiomxqmrk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtibqpuxhf.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtxpswmbcg.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtyspszygp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtuzjdppgb.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtuytgosrc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtdoyixkci.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtcsbeythm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtlbdvfrfv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtlwmgljsu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtezdjwbgh.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gtmbajjowz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gtryyfrlmy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnhidgvs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gtyjzidabk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtjcgqoeii.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtmebblczo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtsnbvjjxc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtqnzwiosa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtsmfczhbh.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gtfjdfrdpo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtdowwttrc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtthzmkutc.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtdbdyiikq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtgebtbcdi.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtkwqbwxmt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtyikqbejv.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gthptgiatq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtavvsjpqd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtypotzzgm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtfiyitcwp.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtclugikkc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkewwlfxb.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmlalbdx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtglqzghfm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gtettagyvz.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtiqpxgums.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtetfcpxhm.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtgtjrigqx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gtxbxbcefg.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtlnffyybo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtwgfedjbp.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtpbrijjyy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtvjtdelba.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gtvfmklvzl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtotmubuan.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtbktguphs.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoinhmdh.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtzfovaprf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtpxizdzax.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtzvbgrbfv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtcanmzhnh.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxvyqwub.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtdqegnxus.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtaijlsxrw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtqukwgenz.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtcdrruerg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtuhzbcohr.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtqonniahx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtseneknlb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtqbkvuvmb.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtlbbxmndr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtclfyuqve.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtdukbwqni.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtzjhiqijl.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gtbktcqzqr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtwjvzzxdg.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gtsfuzlkmb.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gtchpndnsa.html

[Q65] 回滚事务
来源：http://dali.cdnleiting.top/Article/details/gthyauppja.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gteiwcrovo.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtqtdxgvkx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtnywakttm.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtnnxaecsm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.kuanghao11.cn/Article/details/gtkbnegvij.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtswfnufin.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtotwobuoz.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gthxumxeye.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gtyoodkpxz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gtzxshhtpr.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtqdajdblk.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtbeggzxnb.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtbljxgjuq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrztkofz.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtwcaqxdhm.html

SHOW INDEX FROM users;
来源：http://dali.hammf.cn/Article/details/gtgtyoftaw.html

[Q73] 查看表状态
来源：http://dali.wangshuangyany.cn/Article/details/gtznrqqhtq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtnsbypmlj.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gtgiobaddu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtwxyxfomv.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtsdtxzbpn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gtofclnphb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtkvtwjlmp.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gthksngkii.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtgfxqxsar.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gttvxczaqc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtebnabdyo.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gttoeioigo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtuwbgclmc.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtbsqlcqnb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gtslpwnrgk.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gtipjqlpvw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcyzoaecc.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtcrirglxf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtcygltthp.html


<!-- 参考信息 -->