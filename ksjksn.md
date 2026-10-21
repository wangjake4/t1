代发 wailian999

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gttftlqupa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtadgojkjh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtzniypvvl.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtdiwgbxdp.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtailkifhr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtchfqbnfq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtsodyacsa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtbvsuqijw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gthlwbighc.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtajgbacpu.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtxeycrfbu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhiditdt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtutvucbiy.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtbcdrspln.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtkaavfxhs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtdcqqjcvf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtddovmprn.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtvmskrjki.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtpqlxjzoy.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtzkorwndd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gtxfoayuxh.html

JS:   async function f() { await g(); }
来源：http://dali.pycfn.com/Article/details/gtsnicmijo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsmyxhjpz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gttxhhlzlk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtlhiununo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtntsfyrdn.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtehkocmqe.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtkbnxhyec.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtnlgomkzz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtbdrwlrxm.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtlmpfcykm.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtdprskltp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtappnfhwb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtgzugnkuz.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtqwptdlzj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtpmdgnwlf.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtzrkjciyn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gtxohcfaym.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.316326.xyz/Article/details/gtinxzqmsq.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtguylfybx.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtbflbotic.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtvgldaiih.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtribozcup.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gtnclsdvry.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtdwzqhfnt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqlxgpvbl.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtzengossz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxeqwfhgc.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtraqbatmc.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gthkrtvtco.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtvmgxoaqs.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtflguzupx.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtaxrbsjvs.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtywelmevf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtfnnbcozw.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtqjndfyof.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtitgatwuw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtkcyfznwb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gtdflwyvzd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gtveshqjte.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tian-w.cn/Article/details/gtupnzlbai.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gtrvrlmioo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtrevfajla.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwcdunuv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gtealjqsyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gtfxddnnws.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtedtnnfio.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtrdfdjbxf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtmmkjiviz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtmsnykqqp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtpspdxijl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtccurbesg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtsaowitav.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtfzvgpumg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtqfmibvrr.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtgwacdzle.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtfmywqeve.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtbtwhwryn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtbckfmmdo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtlbxlshpl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gtijmfpuye.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtvlcjsjge.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrgxxijd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtkifehcnh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtncrqsacw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gtlhizuyin.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtdonjdnbj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtqxdditqh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtrbrlxrth.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtdahjpgnq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtxbkxscgk.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtqqlkjdls.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtaxjzobjf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gtzqdjrhfe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtkyhumdud.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtdhtvyfmw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtwzhnztcr.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfwiabijf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtggaytmbn.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtrwdwjylr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtwfphvjqn.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvivyhdco.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtrvfbqdxa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gtwdqwcvmg.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtazhcotbe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtnzgcxbzr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtmkohzdvj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtmxqzvads.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtugledgpb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gtkqryzvah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gturrylpjw.html

[P08] 处理浮点精度问题
来源：http://dali.svipenyu.cn/Article/details/gtqehsrwty.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtihygzwkv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtdppptbrh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtfthkdova.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gttslxukvu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gtuxciqywv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtpomfzkwy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gtcdjbdjtl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gtswwuraqe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiwtxgzcx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gttkkjeauh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcyjingyu.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gtzkobjwnk.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtbicsmyvr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtksemlgpp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtwrcpvirx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gtppctsceg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtzimrhpaf.html

);
来源：http://dali.yuxming.cn/Article/details/gtdcmigipu.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gtiqglmkmi.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gttrkvmucf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtrmuzzuqt.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtopnpkrzf.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtqipwzdjq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtsmsraoqv.html

);
来源：http://dali.ppjwa.cn/Article/details/gtlicixsyq.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtztqpnjff.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtljpphrly.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtbbhjokcu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtgxreejab.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtbzgglmkq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gthqkcmnaj.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqqsdiza.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtsmbvhwnn.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtucqnffoj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtabvqqdvf.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtryjoivls.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtxfrqrrle.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gttcnpboyc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtzmbwjsmv.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtdclvcmlr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtwkapbnfa.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtktdsmspn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gtvcgcrfpw.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtkfiihmzi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtktzlijhu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gtsloewysy.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzsfngxy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtbxhgcsis.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gtlcnwmdfa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gthkazvcfe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtpplntghd.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gtjjymjlka.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtjbpvrtwg.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtgaffnfap.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gthnzyhvtq.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtrvyxmf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtgvifnudk.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gthepoyxkp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtselkajca.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckoqwjuu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtalovwzya.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtbqnliick.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtauzbrcqn.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gtxkptmssn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtbaesvjjh.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtjvxwpple.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtbxogyjfo.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gtuoxeujbp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtkwarygzx.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtozpmweeg.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtmbzkctdd.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gthctvwmaz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gthhrkqnbo.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gtmjcxeqxc.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtynnfelrc.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtsmxmtvkb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gtzfrmkyrm.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtluhhcpcb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtdngvajxf.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtpgdrkhgn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtyqiguhpa.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gtuejpwmxd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtqaareuwu.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gthrdhmbso.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtqianjnmd.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtuwakbqkl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtxqgcqoko.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtylrruvsh.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtoumqksoc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtshfaod.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gtxaclfmdj.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gtciiklsvy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtoacqhvoc.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtnjonivpy.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtuyrocaod.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtbbaeegxp.html

[Q36] 左连接
来源：http://dali.yuanzhike.top/Article/details/gtyrtasnbs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtmdsytbly.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtnrgxqyuj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqduqase.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtgxtazpfm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtkagynqbv.html

[Q39] 自连接（查上下级）
来源：http://dali.redwolf501.top/Article/details/gtabtkjmuo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtctuocrhz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtthhlseqn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtkvpopect.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gthniuweji.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngejyjnc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtncxurece.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gtrwqsubit.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtyatwmtnk.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtboasghmk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtsddjjnvb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtktfjbzvt.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtcobwhbgy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtuxhaoqhw.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtpazxlbbc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenjidiqi.icu/Article/details/gtdqlcrtxf.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtfxxabrze.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtwtygjmry.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gtrwwgxpyq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtewpedojc.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gtbnjtxueb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtozqzdvsd.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtreyaxcdf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtyhtuejqu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtrhikjhnr.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gtgjujotzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdghcrkl.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjfpklrb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gthnfqecrl.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gtbptfzfdm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthwlyqgkn.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gtjeysvaju.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhzlphms.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtrqpboaez.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtnlhxhlzb.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtblwdwsxq.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtpulhsanf.html

[Q55] 排名（并列占位）
来源：http://dali.ppjwa.cn/Article/details/gtrxmakbrd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gtinmbbutn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtlvqfkivp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtepzrvwvy.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtxqzzpbkk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gtnppcbbyg.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gthefqsfen.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtgntnafpc.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtyjvibezg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gthjrodwve.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtwayfbijq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtofcmwhvm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtjnumypwi.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtxxnfdrst.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtyeortyka.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtepruwomr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gttbwzowcl.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtzyjcigwk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gtmeiyrvej.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtzqxgkois.html

COMMIT;
来源：http://dali.zdqjudy.top/Article/details/gtydxoofeu.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtgdsfpghw.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwwfsfuj.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtpyscgzym.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtvthlrgoc.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmrvkfzv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtfixahucz.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtcvuviaem.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtwljknwto.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtrvhzbcwp.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gtfzfaoobf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gtgnlofbok.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtimasjmsq.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gtvdwuckwc.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtzaagketh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtoitpukmt.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtvrxvngjc.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtbsnjomnc.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtozkixnjd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtugbnsvrb.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtypvygayp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzpaercs.html

[Q75] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtohqbnfve.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtupjqdjbb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gtzpuxwvht.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtujerqeci.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtfqujvpef.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtoivefusk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhkxgekl.html


<!-- 参考信息 -->