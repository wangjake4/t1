代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gtffpfgcfu.html

TS:   // 同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gticdnyjwe.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtzsdlhdlf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtimsgwzoc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtotipvovb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtstwknxsu.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtlvvijghg.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtdbnlrnwn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtcgrtkroi.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtvacbjwdd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtlyljznsi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gtysvcjhqm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gtwwdrzkpl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtraqftvct.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyxghnlc.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gtsngrdqdw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtfntvruus.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtgoxmaz.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtcmyusvym.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtsxcmhyge.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtdyrklfpe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtwbkrjbvp.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxixfaojm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtleromnjj.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gtytilofaw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtgjnmadcm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtodqqwkrn.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzniytkf.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtvlakqnwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphgccxph.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtwsijpgva.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtifurmuxo.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtahrwdkid.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqjbbnrsy.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtjaejnfkt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqlgyidxi.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtljflumon.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gtpytolfyi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtnlvwtqzl.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtxcawfmos.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtjbnqohah.html

Java: UUID.randomUUID().toString()
来源：http://dali.hysaishi.cn/Article/details/gtjbsthxsz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtsecjhccs.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtbcfhrsrr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtbtlmjbqu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtzvfmknmu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgknhnonc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtmqufskmb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtekanynyq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtxdsxnfyo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtmpdsymue.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtjpfqwycr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtyeeejiwl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtkmhjhtom.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gtfkpmpezx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtbsypujlv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gtytwzzcdb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtmkdyymki.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtzwpwnthv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtztefhcsv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtyqhkwqmy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtiwppkbem.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtnzpkniff.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtbidgxnoe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtbvggxmzg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtzimpxtcu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtrnrckxjr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gttiqzruev.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtxmqaadze.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtusaghjqj.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtpdpzeawl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtxqcqpfxv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtrxqklqtz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtntyybsqc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtsnjkvlzi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtihnrdfmx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtflnyudqx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtnmzbtmko.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gttorvfedl.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtbbjqvpdt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gtrngvqsib.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtnjbrmqve.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtabsmvhmb.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtxzdtyzny.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtnhrsmbzv.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtueapzdac.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtvxwfmurw.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtlwhcwsfg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gtgeqybpbl.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gtlqmqzsze.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gttygevgdj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtuwhkeoks.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gtwvvozucw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gttzzkjqlg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtylnwsjfm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtzdtyaphq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gtvzsqkmil.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtcossqecq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gtktmdouxz.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gtwiygttat.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gtvrjmhxyg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtfmkcxiuv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtcydgbacb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtusewbmps.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fzhhl.top/Article/details/gtuicqpwtk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkospaxcw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtaoouadnd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtkvppstod.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnlpwuldc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtjqpqutij.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvnajyfxs.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gttnghzucg.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtknfkmhlp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyrogglx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtwwvsbmml.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtwuuvcegc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtmiidfmjq.html

);
来源：http://dali.yvedp.cn/Article/details/gtpnqdrpav.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gthaqxthmp.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gthxbwfswy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtwvzohipf.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gtipxbqwcd.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gttmgohjmq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtgzziugfd.html

);
来源：http://dali.yongpay.top/Article/details/gtsxtwexim.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtypwntomy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gtmftevaru.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtlezbewgl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtvlpfnrvr.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtnqynomuq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtghnejjhr.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtimgnuayp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtwdjlocnu.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtnhfindpa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtpclicety.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtqfpfguqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gthyfnxvno.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtkbashnii.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtmtvynmbo.html

[Q10] 插入单行
来源：http://dali.fzhhl.top/Article/details/gtzbocywon.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtsfxxtlpz.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gthkhburhs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gtcskxdbtg.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gthagosrrw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtivgdfqtz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtxedrqpit.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtzyiamgjk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtmdkomenk.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtswogiqub.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtlmclizdq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gtdjmzwltz.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gtbuqwebdu.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gteixwvqss.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtoygcpbyh.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfoeetbi.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gthhyhatpd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtbnolxyzf.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtqlpfsmfh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gthvxkywnl.html

[Q19] 范围查询
来源：http://dali.hongshengwenyu.top/Article/details/gtrkvlyqik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtybqtjehj.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gtaaeknrwm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gtspephqbs.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gtgubqbvxb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtylrudedx.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtmwnrrsbp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtlbekxnya.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtktgbondi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gtegnvpdqt.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtgxudmcni.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtculncbnp.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtuwsxkjso.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtmsbuxrse.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gtcfslvmof.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtusbugrah.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtckiejagz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gtcfagxkim.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtpxwyffpr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfmcdkzp.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtupjovknd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtayuwvtaj.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtkeddjlfk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtyeyocory.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtjrnkvqgj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zdqjudy.top/Article/details/gtinqjemzb.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtcjqpmqce.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtvytpkmvv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtggnclhxo.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtluvxlleg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gtadeayusa.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtqtlaukkx.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gtfsocgisq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gttlokwxjx.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtycctftko.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gtubtbrmhw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtpndnrcdo.html

[Q36] 左连接
来源：http://dali.vqdsnc.cn/Article/details/gtgrmjmvev.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtfntswvbk.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtfvjsszyj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pycfn.com/Article/details/gtoxitfsvw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gtganlflfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gtrhlykhgx.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgfzy.top/Article/details/gtrapblgil.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtojhykzuk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtryyggfjv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtwwiiibdt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtgxoovnxl.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gtvdcgvnrw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtddmdhbfn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtowbewail.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtzsuiiuii.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtaiuzmswx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gtfrfiezuz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtiqolqlpw.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtlkcuwbmr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gtpirrkwbz.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gtwpozxsbt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtjlaofnim.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtzgfjlbcp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtpjfesrbn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gtzkwrvqpb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtvbqibzyx.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtwzvrqakv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtdzausmkb.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gtktvdgozg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgibqqfv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkhhbyxq.html

[Q49] 更新单行
来源：http://dali.tianlin.xyz/Article/details/gtxohotmvj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtafvaaknw.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtbqzxrkgk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtlwxatwov.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gthyjnawzo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gtmnfjqooh.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gtnkbjibpf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtcxnnicfg.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gtermziipi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gttahpnxwy.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtxnjjkskj.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gteqikcfzq.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtnsoqtvyc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtwnickahd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtwmbpkbmt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtwyzepqlg.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslzimsqo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtumwytloi.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtjxvxpbko.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtzirojbni.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gtoaozuulz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtfthilqhk.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtoqjbdiok.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gttplwzbyg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtdlovhqly.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtsrqemjqt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtdrxeglwm.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtemyhafiu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtnizjejrj.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gttdzidocp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gtenfygbzj.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gteuuwpvvr.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtelwmuhmb.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtkobqfqfm.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtlndzztnp.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtmkcizdpg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gtdchigift.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gtdhowtjqh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtibouqfjp.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtzzisoxbb.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gtmxlojfhy.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtnyoiwtug.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtktgbdxad.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtbgxnnnzn.html

[Q70] 更新统计信息
来源：http://dali.zhixingplan.top/Article/details/gtqcixyubb.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtkcmrxwuw.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gtxitgaguw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtmiuyugtd.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gtctrymxlz.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtmvchntfn.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtwewqnekb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtlsimenat.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtikrvujch.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gtbpqtrevx.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gttdtakqse.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtofbrgygx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtktyiidqt.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gtzcqlncgh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtyvxcxlxp.html

[Q77] 时间加减
来源：http://dali.316326.xyz/Article/details/gtloaihcnc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gthsbtojxw.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gtusoxlwup.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gttofhlwml.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtsddmauxk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtkwgfyspa.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtjnfocups.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtczeabfrb.html

[Q81] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtplctesyj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gtltgxjupi.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtgkxzwoxu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtekdfoigp.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtivvnptcb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtolcjlnbj.html


<!-- 参考信息 -->