代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxuanxn.top/Article/details/gttcvyxhqo.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtiqoiqmdx.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gturfdcpvu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gtopfeskxx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtctfeyepb.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpjrnapk.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtcmudywbo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtzgszjayh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gttchrxckd.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnbajsdqv.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gthdwpuxob.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtcmcjtygl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtydfpfevm.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtwxrrxwvy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtdgfmojgm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtqgthtekp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtyjlwnjuu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtqpikgg.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqraguynt.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gtqkxehmfc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtvghffuxq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtbnedwxmj.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtebsxxfhk.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtjaljaswz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gtyxcsyxnx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gtqatmdlpf.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gttcfnguor.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gtgsyjmbvj.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtuujqwdnk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtnxxqzbld.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtnvcceokq.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtexkwakgo.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtwnsxzqui.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gthvkiaytj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtaerfxmny.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtexdhwdzm.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gthtityzzh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtadrucvwj.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtrhqxszkb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtixaqzwtw.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtdgqpiket.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gtiwxkswow.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtloiiqcgx.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtweadifld.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtyyjyamdp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtlxmxegwp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtdwnjozoc.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtwrhzisal.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtqlzpzkre.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gtssotzpdr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtoabetpjr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtbqmzqhos.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcffraor.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gttepsjcod.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtmujaamhf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtxpeifzvn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtxuzqzqpz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtjpgfgxlg.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtbfeaoxyy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daria6918.cn/Article/details/gtyqvoeoam.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gtdqsqxtor.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtabvemsli.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtruaadgeb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gtsgzipwxa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtgiztfdhb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtgltptwwx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtecytmhre.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtyxpolrxw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gtmzcuagig.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtbxjwydln.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtssufpger.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiecylvc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtjjcmtzku.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtchihweok.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtjjuprifi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtovorrdyd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtvevodqrs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtvjonybbt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtavhojkao.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtutmzbnuv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtrxadpnxu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtxxighnny.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtanlybiym.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtgrvpjkqi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gttuyengbw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtivetlzxq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtqnwrmfto.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtkizbuajm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtxvdaxmuo.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtsncetufp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gtewajwsdz.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gttfdooikh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtbyaocdbx.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtuswlqzav.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtqfbpqail.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtkhlkmsrb.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyqyrfyf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtxvfdsdsy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtzktkzsje.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtkpfihrtq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gtsrxzvrxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdhpkjpp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtcyrpuuzh.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtlakjmuon.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtzltnfdte.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcwrstno.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gthesixdab.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtezmyjplj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtjoaxnybt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtnbqqrzfu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gttueiisxj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcsdijpu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwjpvlgky.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtcvdkffve.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzxajxcyj.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtyognzyns.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtmdssrzmu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtrsizveou.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtycdtiogf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtjxgroaug.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtwlyrpheb.html

);
来源：http://dali.mhx1999.top/Article/details/gthfkcsgdh.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtzmrgimsv.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gtwunppgut.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gttroeaaab.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtadqlneis.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gtmwhngjxf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gteovwgerd.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtvzrpgbap.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtebcxwdfi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtevlcldya.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtftjpxpbo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtenysdexo.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtqpqxzrlj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gtxqpcqkjj.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gteqnbtvef.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtnxfkgcvm.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtvbcspmee.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtnlwkuedl.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtiwdodwbo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtphbxjeoe.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gtrghwiwmu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtdopkgswe.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gtqdpprvcm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gthmrrfdfl.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtrmwhgssl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtdkjhcbxz.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtvhimwyqg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtodujtqrc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.kuanghao11.cn/Article/details/gtqjswmdgq.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtrupdisuf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtaedfdtgm.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtpevagamj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtrnoriyvz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtemolctew.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtjynmofak.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtcenzvzzm.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtuzuilmlq.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gttuotkrsl.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtvnksjkab.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gttghdtgar.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gtukoqysri.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gtmabdsoim.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gtyldgfcue.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtikumpnuq.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtpakubwnh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gtonnixyws.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gtyjrdpxln.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtkwjlowwb.html

[Q22] 排序
来源：http://dali.svipenyu.cn/Article/details/gtsclxndsd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gtulltluwo.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtviestpwr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjybfqnmk.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gthwxwjpxf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtyhjeqmld.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtjddtyhoh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtsytgjsga.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtrfnfmbnc.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuiwbuxy.html

[Q27] 条件计数
来源：http://dali.nwbrower.top/Article/details/gtlxdmzwhy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtysluzluw.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gthijgkryk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gttkzyczfc.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtpqtjzzpy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gtraypokml.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtkvbujnew.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtclrsoeur.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtbhfbucdv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gtthxhovph.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtsbfycypx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtzlyzeaxv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtmdzmtiwe.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gthjuzyxmh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtzkudyqwg.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtbwfwpbyh.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtrlxqtzim.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtcejjkvdf.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtgookbajy.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gttpbrzgny.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtbhxzqfxb.html

[Q36] 左连接
来源：http://dali.tanke756.top/Article/details/gtqaqjimqn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtxbgmzutl.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gttxmqrydv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gtkoidcgjk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtisgbktwr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gtxzsdaxxm.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gtfcnawjip.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gtoeqeepal.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqfqlbzz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtcuznkcsl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtltyebgcr.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtwtizxo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtippkinmb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtwrnjremr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtsvqilpmr.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtajcxqpfy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtowfqlawh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtwmylizvd.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtjvgiztzc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gtwcazfunx.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtipykziol.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gtwugzdryk.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gtyiqrxtwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvatunwws.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtqomxehol.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtyiparmfu.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtnvnrvgsd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtdchvsvnh.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtdkseknmt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtgmkdntxz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiknklmi.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtqnpvbznp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtzerawihx.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtbkndiiud.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtrysfxhns.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtnkdnypmr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtoreeyiga.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtlffrapex.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttncopdrg.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtwsnwldyh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtzbuzztts.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gtkmuzgmhc.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gteeatzcaq.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtxgjrlalb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtgunezwdb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtlksqhuxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtrhdmgyvq.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdeayleb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtmesyzhpx.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtyxxkqsea.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtzjgwxmng.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gtdjffepaw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtnqcshrjr.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gtcgejwkpl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuiifdha.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtwcdtbejk.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgxmtyag.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtwnzbexxz.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtrhejcbsy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtpeeamcfl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gtjrlrfoxd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gthpvrxrqm.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybqkkqrz.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gteyjuuooe.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtjntaunie.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gtcgqybxzr.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrwitayl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gttjattokz.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtouacntpx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtnwqamjez.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesxyrmhv.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtwgreqlxk.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gtjcshuuxl.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gtjjffwout.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gtxuaycpjp.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gtxzygurbs.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtbxrudsec.html

[Q71] 查看建表语句
来源：http://dali.gaohongyu789.top/Article/details/gtfocohupk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gthnpjttca.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdunptik.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtlujqniuc.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtayhhvpad.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtviyrgrod.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtwyevnryv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gtpqbjwvus.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrorobgq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtbnljokmf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gtrpzaewbc.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtpirbwjfj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtplktknfo.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gthelbygkc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtrracksyv.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtvgdaaomp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtboplngri.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnffyfhhb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtdsystlzx.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtnrpobkgd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjnfvizc.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtcxjxiobw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtrjcjzuan.html


<!-- 参考信息 -->