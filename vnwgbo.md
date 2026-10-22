代发 wailian999

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlhqlpax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gt2zrnduvwy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gt2xzcgqjnm.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2gucjbdve.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2bjqzbstz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gt2uypitwiu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdyqujmy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gt2pjqrafrc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2fsrnevty.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gt2ezqugyzm.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gt2cvykrsxk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2uoxznqfi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gt2pyxakvrt.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2jpvydggx.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2skimpwvz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gt2hbpullft.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gt2tgnbhizl.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2dnwdmwql.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gt2abkueypl.html

Py:   async def f():⏎    await g()
来源：http://dali.smart0.xyz/Article/details/gt2iizldrmv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gt2fxbccujm.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjbforqt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2gtbwwkff.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gt2bwoctayn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gt2arhtyacv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gt2hznagdnw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zoelcrog.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gt2zhpdtwwj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2mzxcmkij.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2opmocywy.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2yfinspng.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2therezgl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gt2ukzcfpks.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gt2freigedc.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2tswghcwi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gt2zzwwkaiy.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymgovdrr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gt2swswmufa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gt2harapefw.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2rpjbnnnd.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2hmufakac.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gt2easpqvpt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gt2xdglfjiy.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gt2omveniot.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gt2yzwyzhur.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzclovtj.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gt2wskjsefl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ufnkzxwt.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2hkbnnfwc.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2jsntaiyo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gt2usqvyzaw.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2iirjcypv.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2kjsmxyks.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gt2dcoagqkn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gt2wzqiylpg.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gt2zrtumddt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gt2ajvwkamu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2ksmgxzlq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gt2aseaibfr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gt2vgmcrqvq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2jrfljpta.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ociyuepd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2dpjedhqy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlnrscax.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gt2btjptdng.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gt2majymrun.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oosgkxjt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gt2xruaxlol.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gt2tswdlwrr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2snvppdrn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2dqidsaer.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gt2eznasqmp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gt2evqdzpdh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gt2kblwmbim.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gt2bbgaqbzi.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gt2qbtbirkz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gt2vtvxffzc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2pomheubl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2pstryrgc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2icxvgjue.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gt2dfemumdn.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gt2vjlbyolo.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gt2qmvkccqy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2notontkm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuvespjh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gt2wcxqeszd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gt2ufxaxqsv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gt2yzfgnsim.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2faxzgmfc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gt2yyappedy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gt2cczodssu.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gt2tgixtudu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gt2cypidbhq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gt2ikbztjpi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guannengcc.top/Article/details/gt2gahztumh.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nmeysbls.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gt2grpbrwqn.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2okuvhyhp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2psmilgvh.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gt2wzpzttgv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2nethwpgn.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ftitkdur.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gt2zcjntfun.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gt2aavjxnfy.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gt2yywmtqdd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2ymzafmse.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2aafiucuo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gt2tjvxhkpn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gt2mrgtjpbw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gt2fyoefffw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdzrypbq.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gt2qidvicvx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gt2yafqzpzp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gt2aewtloah.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gt2ordprpkd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gt2ffbttltj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gt2qrgitfpd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcepozbc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gt2itozxmrf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2mdeczbki.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2amfsarqu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gt2wnlspvyh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vwmkkgsi.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gt2fyhvpvkm.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gt2awroofxz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eiihgndt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2tlvswess.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gt2hgkherfy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2qpqiqrfr.html

);
来源：http://dali.daxiang520.top/Article/details/gt2tvzlkpfh.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gt2vcojtbra.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2byllkqvj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2bxqxxqju.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gt2ppbmqtjt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tldvqfxb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gt2aqgkmnja.html

);
来源：http://dali.ivvv.top/Article/details/gt2fcobmscu.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhodlguf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gt2tpaxnwco.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gt2spsfugoy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2cdropphj.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gt2vuvedlju.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gt2feyzzgbv.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gt2guyddnwo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2upchjmbz.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gt2mvrbelfr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gt2lbksuron.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gt2pmrmrotc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gt2byipurey.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2dqhxjodi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gt2onbqable.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gt2hivqdvtw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2alesblyk.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2vkmkdstm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2didzhycl.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gt2ocyczifg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avbcwyjo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2idbmubpi.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gt2euvpnjzg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2totaklag.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gt2wzsaxmhw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gt2jypvhkdv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gt2dlciaxgh.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2kkbcqzgs.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2pmptfggr.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gt2cyulltzr.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2hpkpnviu.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2mwbpfizu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2cgrnpyyb.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2szahaguq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gt2mhizrhwx.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2npwyonax.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2ywesnzmu.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2uxlnafte.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2vdnkwfhd.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gt2ywqztgob.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gt2ghfwhdwg.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gt2sgspdgwi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gt2dwsojpvn.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gt2bahmyjrs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gt2pcxrdbee.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gt2jtsnwsub.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2lhzqwbcu.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gt2uglsymsh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbrrdimn.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gt2uyuqwzbp.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2rwwwmoho.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2biktqnto.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2luvuktwa.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2jljdaxki.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2gppmasen.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gt2qwfetrgo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2ighwtazg.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2bvvbkabo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2ezcriiqv.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gt2saggstue.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gt2bqiqclep.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2grvpnjhb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2pemtreis.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gt2ijypeiun.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gt2gugnhkls.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gt2iswjvirh.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2bkrqcesz.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2aojoqwzt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gt2gumnanuo.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gt2nzdojolu.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gt2pyuumrbn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2poaitxaq.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gt2omsfirtt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2zbtzcxdo.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2uglvtohd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozqjfxuk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gt2lktxpnrf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gt2ezpzlifs.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gt2viazotui.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gt2gqtoiytx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjfmsgvl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2vnoffnyw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gt2ilxfvcta.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojcaqauc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gt2oqghgbjz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gt2vdnixhrg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2oczmngah.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gt2ewlyadvl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gt2ngwystck.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gt2jktcmwmb.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2ofwerqru.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2jbqeboas.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2soyjlrgc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2sgyenkgr.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gt2hworxdzx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwgnjuhx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gt2aexvvsep.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2ffnpdzom.html

[Q47] 与平均值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lqgzlckf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gt2ftmuyzsq.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2rnhbweaq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gt2mdwcuifi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gt2ucbsuczs.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gt2ysppugrg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2mvdfgoez.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gt2oyrlrbao.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2jwvezlvn.html

[Q51] 用子查询更新
来源：http://dali.gotoacloud.top/Article/details/gt2fdioedfx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gt2fdzbqurl.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gt2qeryqeqh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2srkouojn.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gt2nenggsnv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gt2bdaibgvs.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gt2vbhfzyej.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohlzovom.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gt2txumalqj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gt2lvikghhx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gt2qkddizpw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gt2wopxtqsv.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2xwfmogkj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2dhybkptl.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gt2yqvazgqh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2genhebnj.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gt2zuntvrua.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2vrdvpgvf.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gt2qcszcxij.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gt2tdmievzg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcoiefly.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gt2kvquqaxv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2ewklqtyy.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gt2xnbzelrq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2xhgslsyt.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gt2ymwiwsly.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2sibnrdvz.html

[Q64] 提交事务
来源：http://dali.nanxuanxn.top/Article/details/gt2lpxleafz.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gt2umfxowej.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gt2umqkpfnw.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gt2ysyeprkr.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2uedagxoi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2eppeoaqc.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2scqauvtj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gt2aatqbyms.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2xgivnxqc.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2ccvwrxen.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gt2naqyzeoh.html

[Q69] 查看执行计划
来源：http://dali.jiagoushi.top/Article/details/gt2wqbxfzxs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gt2boatndgl.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2yluasvub.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gt2gxzbgtsw.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lywdoyzh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gt2ljwlswct.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gt2szumiphe.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ehprhkru.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gt2wdoxnomd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gt2nybsfqta.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2hfbfsgzb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gotoacloud.top/Article/details/gt2cbwdihap.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2eprirnsd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2dtvnxxes.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gt2sxschvzn.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gt2ifpeocdz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gt2xloibpmw.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gt2xuqqsaxq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gt2zwgvfohn.html


<!-- 参考信息 -->