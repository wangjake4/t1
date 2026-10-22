代发 wailian999

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtjnhzxecm.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtwthgujih.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gthhlsxhpq.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtujpchuvd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gtlbnlhbhj.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtjidekjya.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtamrlsuli.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtubhrdrsv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsswmspxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtvlbolcim.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtdodxxcsn.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gttzbrgffi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtsljpjfqj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmifaufbw.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtwklmkwmt.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtxpxdxzpw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtsondibcb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gtznmuohwt.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gtqisylvdp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtuhvojdwh.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtgnmubfdy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtwydazohi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtlidzakau.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtnfvtitqh.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtbmsxcmzu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtxfbruryd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtxhsfmcmi.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtusyhvrvq.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gtizdlltgu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgrhfsvc.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gteufwdclf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtoucmcjfk.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtehwgfkhj.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtecrdyuxk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gttkvjmeod.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtslmxwzhg.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtzveybfjv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtsfynyxrt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtuehmbtak.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtzqdpdcls.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gtejnrmnqm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gtsfdwkxvr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtnnaupkwj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gtanbdngdo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtbgycsyng.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtguswrloe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtyuhvdexh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtavhlmfqo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gttjqmkouk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtnleqytvs.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gtwptbcfpx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbtacfsq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtygsrhhog.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtylmdaucq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtuaqoedsj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtjfxryolp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtcyzzxfwz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gtrjtvfixq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gtcfohsmze.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtdugpqhaj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtpgutcofb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtsxiqnkvw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gttfywqidt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtsmokitqq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtopalirhg.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtvjtdyuyt.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtdsixdlfq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtarifijnz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtocomulrp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxuanxn.top/Article/details/gtcarslgfy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gttvjcueze.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gtumdukyvl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtvqeqrpih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtbtejeymz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fzhhl.top/Article/details/gtphqovxnv.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gttnmbbcbm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtxvxuwwzk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gtdeczjepi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gthksmivim.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuuejyydl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtywgvybsb.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtfklvedfe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gthfrlsxra.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtnsmskclu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtfzmlxkqe.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gtsohsposg.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gtjzfrkbbt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtarotlsqr.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtpbaqtvks.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gthqegtnli.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpmspugg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtizjfrrjc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtqwyhmyay.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtguohawid.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangdashe.top/Article/details/gtcmarawao.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtdttqjzsv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gtvshfxqln.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtvtftfqnb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtpewtgdwp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtkonmosuf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtkmysgsox.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtiywgpstr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtgbohbchb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtznqokntw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtyctsudhj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtjrwfbbie.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtubavjqdu.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtwxbgfbsh.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtwsndrlrw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtjtqepvjv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtkuiwakdi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gttdnoojlo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtvgrjvjjs.html

);
来源：http://dali.wangdashe.top/Article/details/gtnrzbumng.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtfpellzpz.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gtizinsgog.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtzcqvowfp.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtgukpjips.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtnbjpnqyg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gteasqjbqo.html

);
来源：http://dali.cashguo.top/Article/details/gtuzvrnyse.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtnnbmzggr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtrqmqkvkz.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtyefdnoun.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fzhhl.top/Article/details/gtozjsktmt.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtfpsxocat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtrjmdbhhz.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtemisogdy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtyvzrtymv.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtlcbkpycy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtxypqxlhv.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtgfoyolaz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtkwicgtnj.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gtorzyuumt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtdqhlhvdt.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gtwxcqnkih.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtbbnqtlrs.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtwmsrigbm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gttbwnozaa.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gtqmxqguph.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gtsiagzobk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gtuwfjwabz.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtxhmbczpu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtlmflfvdp.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gthxwheojz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtplxvshio.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gteiqbgfei.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtjzhrlexb.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtymytuimt.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtngakvsho.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtgdglgyfy.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtnngtoett.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gtjwaiqvyl.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gtjridnckh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxrnauwy.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtktarhnwx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtkauwfgck.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtqbvguxbs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtwgjsecqs.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxaxvzjzc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gthxmvbedm.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtowgorflo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dashuyun.cn/Article/details/gtiztifpyl.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtbbxqjbxi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtntowyzyw.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtpqkyxrhf.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gtkkgcvosg.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtpsyvjtyj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtmekofmcz.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtxgnvdrbb.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtycnidnth.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gtmvjbkwse.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtqrxvzvlt.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtzwzpfnwc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtvfxsghmm.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeoikmji.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtzntgioxh.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpjtyhrz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtclsahwdl.html

[Q31] 分组后过滤
来源：http://dali.fengsongda.top/Article/details/gtqpxabncx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtgrupphtp.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gtpfgfecwj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtruqbmhqg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtuxcyivqp.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtxpgqbuwb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtpuekzqxb.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtwerdgtvi.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtqajfidut.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtdkextwfm.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtswtcmfky.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtdkchaoms.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtoejwohyl.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtdvexqhav.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtfcmawlls.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtjzwgzpbz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtetbvjmkq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gtmwoknhca.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gtixyroydq.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtitbhjzku.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtcjepensc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtritlgcxk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtsmljcduz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtmfsbwjkf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtdjgrcozy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gtznbrgmyo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gthusehrtk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtkibckupo.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtmjtminyt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtylcpzipt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtafbvkqqf.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlqlttlm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtmawusdve.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtdythhwqz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gtgffxmqrl.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtjmdsqfjh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtyzmskbbl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtfzbgvdan.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtakatrpal.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtunhgwrdj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gtbtljxmdf.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbdiglla.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxxgjtsu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtzidanrei.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gttxijazvv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtvumvzcma.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gtpwopsryr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtidexrrpc.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtcsoxacut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtszponlzi.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gtvyzvgxro.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfbnnqdx.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqyoliwg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtxknweexp.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gtzfreupxx.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtyvxklbsx.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gtwmnokbik.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtlrazqrhv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtbocwhuwx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtelnqdjdf.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtwapobhib.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtbmkzwzoe.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gtldlazopn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtskvlnjze.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gtszcjhyee.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtfzpmnsvt.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gttzpirjjl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtxwnwuwqt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtlqhmayvb.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqppjgtx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtpbchccrx.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtbhpcqbpx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtmiesrnol.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gtzmvdmdly.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gtiwasvffk.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gtjsgoyojx.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtjtfwcsle.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtvzzmhzhq.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gtthbvdfds.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtjscjhpek.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtuwcdrluk.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtpervxhyn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gtyjhqctkv.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gtsnxeznjt.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtyjbyetjf.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtlkqvxuow.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtamzeopse.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtorepayio.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gtuovrauao.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gtxyqqexus.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtjazpefva.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtkacrevif.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtfgjjbvsw.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaxzqkpc.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtxuemmjxo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtsszdvflz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtipkcrbdw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtljlixphy.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtcwjlddgb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtjehmopek.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nwbrower.top/Article/details/gtpeqmtxpn.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasshimfk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtbvtrruvd.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gthtifmlrx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gthfujcegh.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtccppbyal.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gteitiilkr.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gteupimudx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gtcfbxcwsp.html

[Q80] 字符串截取
来源：http://dali.zhengqikj.top/Article/details/gtcwgfqqbm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwugplpzz.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtencaiwlo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzwzovtvk.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtgfaierss.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtlwltrkyh.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gttelvcdqu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtxqhuxmid.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtwcefntlk.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtpvwvsppv.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtetbvfthi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtxlatxylk.html


<!-- 参考信息 -->