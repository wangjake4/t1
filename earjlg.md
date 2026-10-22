代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2jehhmrrg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2wfnpdgfg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2sxeqqbsk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gt2tdlzcxns.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gt2cjnskvkw.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2zgabcbqf.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gt2vojlpace.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2dxroinjw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2oilfvnsd.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2zldgcwyg.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2yepzwbij.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gt2gispwece.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2xlamjrtk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gt2wxneskuk.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gt2bpkshics.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gt2qvyrkivp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtysthgf.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2iqfvbzvv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2sxxedfgz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gt2rwrehygd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gt2zsapperf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gt2wchivrkj.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gt2nevrswto.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gt2cjpmpkmu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gt2oyzgkczq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gt2mxsbrnlc.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2qsneytir.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2pdoxyfpp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gt2orvuhfpz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gt2uqtkpbvm.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sazcwila.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gt2jpgshogc.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gt2bvivslgi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gt2bypkqmjo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqosrccd.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gt2wuszhgtf.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2ephhoyxu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2lvhwqpjg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gt2iheuapxe.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gt2cghrsorw.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2kwlmqeqb.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ljccobvs.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gt2lgprzwpr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmwouray.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2tmbhoqdw.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gt2mlezpizy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2sdefqadz.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2lyklehyy.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2rtyzsgpe.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gt2atxtalxq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrcmniax.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gt2uilpgxsj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2kapizlem.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gt2iwaflndl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2ntjnwlgx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2zmxfejyb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gt2treyoqyr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gt2cclrjanj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gt2ukcxcsrj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gt2ifxknzwi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gt2lkzlzavj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2klugsooi.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgbzwvxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gt2juxzmeti.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpghpemk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2raelybmf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2giqvdcsy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gt2jduydegc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gt2ulioiimq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gt2abmgkmrv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2nbiuehei.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gt2vcxjwraa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2ticwiytk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2jeuylsiu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gt2kovxdgnv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwalhgir.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2imsdgrfv.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gt2gxxqlyzc.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gt2ttvosprs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2ubnxhjvv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gt2joqfdtjg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2iooebtzc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gt2ccmtzqou.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gt2pcbcxmyp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2inwhufcp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gt2ynniejgp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2minbfqqn.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gt2kpdepwgi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gt2tebnrqfy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gt2vbpdqory.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gt2nzkabzre.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2okwhzkhy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enqchkjn.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbwbwunz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2njaxezlc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwqrwtw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gt2cpnipiyv.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gt2vgytjorn.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gt2reukdjgz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gt2gkaylfzz.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gt2rwdngihp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2nnobkmrb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2hwuhksjd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gt2hqmvzckg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gt2usqfmjvo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijwhzuei.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gt2bxbfxclr.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gt2hirbtolx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2dmtxmnsa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2tizxswdk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuetiantiany.cn/Article/details/gt2usoslmyo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gt2altorxhp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gt2yliyuzdl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gt2onfsnuqt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gt2qsuxzetc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gt2bkmyylqa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2aaanxigt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qepbikmn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2fczsiupv.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2egobjzrb.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gt2bomupgpd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2xhnainqb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2odvhtxsn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gt2bihipvmx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gt2srxewreq.html

);
来源：http://dali.yj20258.top/Article/details/gt2zsqtyrlr.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gt2amocauxh.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gt2ygnugxjq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejmnsusz.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2gjulrzyk.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2bhoeezvf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gt2gtwodckg.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2nyuorvge.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gt2mutycuzt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2nmjunkdl.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gt2jepnpkcx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2hnsqusgi.html

[Q05] 重命名列
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtkewnzm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gt2zdpytztw.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gt2dkjdtqeg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gt2dqfgekok.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gt2mbckszkj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gt2ibasjzcu.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gt2yeapldqo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2paujzhdn.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gt2iyzhfnav.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2dwmnrglb.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2houmvxsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2ttqwwlyj.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gt2mjxcubpe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2pbjphewj.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chaocumi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gt2mvingtmr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntycqxpu.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gt2zlgyuvvf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2nqdxsrcv.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlmqwhnn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2wtqwpdse.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gt2qqnspajk.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gt2xkrvyctd.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2kwqmhzid.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gt2mwfrjvnj.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2zmwwkqma.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2urmaonst.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gt2nfbtttyi.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fexwnreb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjxgdogh.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gt2akygpqqq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gt2deszqqxv.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2ncyrnhnq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gt2ceeippxs.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcdhgpuc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gt2kvqzujrg.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gt2hihqifjv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gt2iqhlyjih.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gt2aeyodkbc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gt2vkbtrink.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2apxxezjz.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsoqeaqz.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gt2bddobjfm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gt2synpiflm.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2nmlloeqr.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2yrxsvjng.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gt2lnhzoxdp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gt2bimwokri.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gt2axnukedj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2iykvuuxf.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2vkigpfsk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2swyvqoan.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gt2drptvtsx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2ygnuwifn.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gt2dluvqaxl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gt2eaxvbejl.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2hcmmusth.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klwybaot.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gt2yfjhvxec.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gt2zygeuhlo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgibrjts.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bntisqzx.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2zviysgou.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gt2qvgpgcar.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iddypcts.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gt2jwbdzukc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zubvykaz.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gt2oozwmshn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2qhekajhj.html

[Q37] 右连接
来源：http://dali.hammf.cn/Article/details/gt2rctddlol.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gt2gmyfhmtk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gt2yxrpwodx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gt2oazvxyha.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2ppyrneli.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gt2osyluvtw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gt2fktwdwgr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2dieykibu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2zjmfupsm.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2webbboyu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2enshbcnx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gt2zoxdixxe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gt2jextffen.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gt2ofqawxqi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gt2kmmtpivn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gt2ngowxqfw.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gt2zhuxirdu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2mzqzrtfd.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2kjesixmw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gt2ieranyeo.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gt2qjqemoxk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2obgbheys.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jryywrju.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2iiwfaere.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gt2bozebrvn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gt2myvrbrst.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gt2qoztfibr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gt2lzteiymo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qurqdfad.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gt2tnzkrmwg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2vhcpqfgk.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gt2mvhmdwdw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2gqwcmnva.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gt2spwqmsru.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ltjgubch.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gt2bwchbswv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2lnvusgyt.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gt2zakvlxvc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2wvusbbto.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmrmftah.html

TRUNCATE TABLE logs;
来源：http://dali.ehwqpu.com/Article/details/gt2wkcwbeqz.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gt2ymbluwgs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2pdjyhccd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2pmuwicnk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2pyehlrmu.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gt2jizburst.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2xlzxwwmv.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwaexawp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2omxoffoe.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqxwiua.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2cuuphpxs.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2dqjztwik.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gt2ghahmgqz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2efiplqcj.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gt2ehgquxju.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2qiklskss.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2ufltjjep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2kjkhbvrl.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gt2cvwurviz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yangfankeji.com/Article/details/gt2sriicnhi.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gt2fgcmkyaq.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gt2uitgzyuj.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gt2otybivha.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2klezvcwj.html

[Q66] 行锁查询
来源：http://dali.sxryk.cn/Article/details/gt2txmhosnn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gt2mzlcgzlz.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gt2oqtjpgdm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gt2hllkvsyc.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2fywamblh.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2vjkjtuoi.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gt2jdmkhdoo.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gt2hgadahuu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gt2grfalixx.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gt2kmfvcirs.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gt2xffrnnwl.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gt2omiawoic.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gt2wvnculbh.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gt2acnvmwvk.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2pjblyboo.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gt2klsvlrbw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2xvxjscds.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmkjkgdu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gt2apxlpvag.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2giamoykm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2pcqrrlmn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gt2nuxerjqt.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gt2agbawfhi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gt2ckuvkddo.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxjxqyxi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gt2dygrnirz.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gt2ffjyfnil.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygndonpg.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2zbyrysep.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gt2kxndwlfg.html


<!-- 参考信息 -->