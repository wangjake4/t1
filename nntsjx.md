代发 wailian999

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtaxbxxjjg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtghpwlqno.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtatasjyoh.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtsnmyfzoc.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtesfbekfo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzmnoezo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtjkzmerzz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtolflyhhj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtruziymbi.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gtvncnkdzf.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtofesmjwe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtipptwetc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gtxrdomjxp.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gttxoqvyqi.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtlixdqsnd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtehjlojum.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtfllnmfbp.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtldikjilh.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtffrgihjt.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gteljenhwh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tianlin.xyz/Article/details/gtktuomqjg.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtzsliqafu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtyptuptqe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtsgigqmjn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtwpiufgdz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtlmukhdnr.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gttztktwvl.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gttahfccva.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtxricjeos.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtuwhfvkps.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgqjztnb.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzsjqjqz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtkidgxmco.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtdjdaatvn.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gtfznbvbcf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtymmrrkok.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtayihdvnj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtvwzcvtog.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtwjkpnurx.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtvlgvnhtw.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtxwlducwf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtqheoehlx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtiblydbxn.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtliifbojw.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gtkgrlqbzz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqnzlnlfp.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gtlbjpijll.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjbejwoqz.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtryguvikg.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gtmfxfaeje.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtqusbcrtx.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtpdqomoit.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtnnvrrtuk.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gtbshrgtaw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gtxlfribyg.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gtfrffbuvz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtdrigvqgu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtukwlgnwf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gtmofwgjse.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gtkjllptlq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtslshthbk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtgnylyitx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtdcsyivjk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtgpdysojo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtietetbpz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtjsriiswn.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtqihjupgz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtsseskehv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gtuesasgmm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtipttzhyp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtlyxgoqkg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtsdwwzlye.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtsvfxytuj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtcnkjhkkv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtsedlgniw.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gtzzruanbj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gttscnvhgj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtoinclqpy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtckhqxoai.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtzvsavgkj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtysdpqzox.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtnysrtlfy.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtukviqogk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtxamzaqii.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmymrqac.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtvvwstjia.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtgjyohkxs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gtsqnxrcir.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtjqutohyj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqvqlreo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtmqgdzuxt.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtydtcsglv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gteilvkvph.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabbmungo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtylgtedbp.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtdvspkxng.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gttyxrjrwk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxgahopei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtwtabvfkh.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtjmfhzxft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtfwvsijqh.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtivdfxuno.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtoexmndow.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtehmiiuqi.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjayezsu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gthphiojne.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtgtckgayv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtppnplroc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gteotwonlw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtzolfuyms.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtmgsynihp.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtavpcdvbb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gtliojoyjm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtcdsuqoqy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtbzzdqgca.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtpaucemmc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gtuujoexen.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiomaiux.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtrinzobmg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtnrvermkf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqouxiyke.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtpclbexyl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gttreypcwf.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtxlzsppdp.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtdpyegmpo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtdcvjofks.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtqbvdarel.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gtnrmckzwh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gthggncoui.html

);
来源：http://dali.sufxvd.cn/Article/details/gtqymxuzbo.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtfsvaejof.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtxzgylrzf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gttlonztaq.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtlupkogbw.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtdyxekgzp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtiudrodxg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gthdvctyap.html

[Q03] 增加列
来源：http://dali.redwolf501.top/Article/details/gtgfgccsxv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtyolukehr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gtqfatnpkh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtjkzdcokb.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtugcujhtu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtnrsqkgqx.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gtxulncaas.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtkyinvgep.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhwhynxh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtbzxtwqus.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtbxcnmctr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtzhnlwjkk.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gtduaowvyd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtmaaxpinj.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtbazlffhk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtgpnoxtyp.html

[Q11] 一次插入多行
来源：http://dali.xinyue.icu/Article/details/gtimqbbpas.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtgasactri.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gttoxtoigc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtmussjubv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtpnoqimuo.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gttyyiownv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtkbvdujmv.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtkgwpjwmd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtygoyymmj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtqjtltdtp.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gtjemkcibs.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtxymtcdzn.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtetilhhew.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtasdusbsa.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gtruiehenc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtczitrryr.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtmzqqbesy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtwgxfndrh.html

[Q19] 范围查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhzqgihk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtpvnfotek.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtorjqjvbv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtrwmjtgmz.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtrgliixpn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtsdrhpkrf.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtxsfcwyvr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtecbebytx.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gtqnjbcsnk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtzhstqhsd.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtpelursso.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtahecdvjc.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtvwwqclto.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtbqoilcdu.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtuinvtasv.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtlhugjqms.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gthrccutwb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtzklffzrc.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtrjsmbnbu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtswjqjqdg.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtpfetljud.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtubebrwpv.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtwnnauuqa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtzxxwccjt.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtqcowargq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvygwvcrj.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtduexdnjx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtdmbitukk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtghvdiykg.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gtaxdnvpcm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtdiutsuvu.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtlhpbpaoy.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gtpmlfvcso.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtrhmlpnir.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gtuowmiuvq.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtvzcwfpsr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtqanfdg.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtkmhgtujm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtwrzztyml.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtcjsflwkn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gthvfiavlq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakmuosgt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtjoisfsnq.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gthirgdiui.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtmvahyfwm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwftmgjq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtwcudvekl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yangfankeji.com/Article/details/gtzgnpbggl.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtloibvrxv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtnzkeysex.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtbwjnkttu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gtuuefwmlc.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtrdvwxqvf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtpczfcazf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtifpggiwi.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtowzjwofy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtflqmynqy.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtvicwckta.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphahytcp.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtnvqfhsmo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtykqvpkho.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvylecte.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoudrcvoh.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtatdpcamb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzjopevi.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gtmmkxktdt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtsowawhxc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtndqymsli.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtxtikjvfe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtrehpowmc.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtvvwcaxnq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtlblovnja.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtlbbpzyuf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtmebmynar.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtfrqkaimi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtucimickz.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gtexlukbdx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtlwhrmhhy.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtitejrecq.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtilkuxpwz.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtqulpkwjd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtgiqmjzfu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtbicrermb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtidcqcuzg.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmcqafzb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvoqrrrwj.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtqrhnhpdr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtwuaxltfm.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtxmfocnuw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtgfgrmbxs.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtecagynmg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtpxcmxgip.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gticqtnyum.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtcdbbzhau.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtcdukymnu.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gtcsrtrjet.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtpuoagess.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtinffnezw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtqaophnbw.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gtylquriac.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gtjpgopvic.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtadnxfeid.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtxdheucwa.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtzrborujf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gttdglqbin.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoouodwge.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtmofyncew.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gtdqknxjoc.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gtazyvdbsv.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtapcefhkx.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtrpffsthz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtojolyllk.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gtodbdlvyt.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtnsonvkiw.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gthuswphik.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtiiddoqsw.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtumlzymuc.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gtvyztjagw.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtsvyiqdtw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtinxbhgjh.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtrbszkyem.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtfkxidqxn.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtqpwqhd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtiqsrnubb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gtcpqekgol.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtfkzdbqgj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtkuubqfbs.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gtejjiixls.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gtppymbsvh.html


<!-- 参考信息 -->