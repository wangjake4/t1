代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtwaekvtri.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtcjnhonlr.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoysbtgmt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpuajwjb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gtlmsycvrv.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gttayjyqef.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gthodtbaub.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gteffajwyj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gteppnhfxz.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtzgyjniwz.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtdooempfj.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtattukkle.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gthmntrulb.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtrzzvzwid.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjrbgvvan.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtdbatksat.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtledthtqz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtmndchzeq.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtpdrjfxty.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtapvobdes.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gteswjkdrm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gthkmgucst.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtptyrorms.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtztdvcoqv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtnyoiprxw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gtcbfcyarc.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtkwflscgy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtcqmdkrod.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtvzkweojf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtsttgoabr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtdekxduuq.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtpbspkvkc.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtzelhlctk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouhginiv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtxzygslvd.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtkcxmhkjo.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtszffjppb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyngyppqp.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtqdnkduju.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtefowiupi.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtfproxsfs.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtglfriwms.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtjguglxzg.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtimwaiwwv.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtfrwpkhdn.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gtxlhsowwh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtiutwqthn.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtvdzqohqg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtcgiadyrh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gtizihijij.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtlfirxowd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtuarrqsje.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtocyxsset.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gttovcyjhe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gtwdvjbkxr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhengqikj.top/Article/details/gtbzuiwrqi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtrfgiwocp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtfmweifnn.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtbxovrerf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtmrldpsax.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtcdixwjte.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtbqkaoynq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtdywjviik.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtcmxeiula.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxctipdmz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtfqhxktiv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtbghigdio.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtvvmzgrxy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtykhkntep.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gttivcztzu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtllrgjybo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtvddtflns.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtulsnkgnx.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtjuksbcdg.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtkbeclbsl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtxqrygufm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtcwegxryg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtofgptcgk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtyqmvqact.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmswzauna.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtzptcgyww.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtzmmoxhiu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtdyzyfxnn.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtxmxlgmht.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtnkauawvj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gtsiofxztw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtqgqwvlmp.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcoetuaip.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtnoycsboj.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjuyuvak.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtvqvaiqcx.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtreennzdd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpsyfsgj.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtxjzyiwpr.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gttxkxbiha.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtkqefqyym.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gtrljcveob.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtbbhixwmm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtshwwordg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtuecwbeig.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtbrtijizo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtftxraafh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtvjrufuqa.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gtqkhyyhxv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtmgepwtcm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtisteamcg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gtczfaejma.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtjdqztxde.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtszqgfgmy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtyisbtsah.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtoweudwxr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gtfxardbmh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxqxjikzf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gtmsyrgqlp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsudftkxs.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtqkplvwye.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtznmowjae.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtjuitdvic.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtdckxlfdd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtikfeuehq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gtehakoiav.html

);
来源：http://dali.ppjwa.cn/Article/details/gtfobpuguj.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtiaxnpoer.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtxdxccdwr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtdgstjqpy.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtweurqlrd.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtgqxjvszm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtkgqtlyne.html

);
来源：http://dali.redwolf501.top/Article/details/gtaldmtxyt.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtpotmljrp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gtkapnmmzg.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gtonkzlzzt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtpdvnjvpj.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gtugdjrkks.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gtyicpzpry.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtroshhqlk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtsdoaeuge.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gtvefiikmg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtiwwnpjlx.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gtkfbvoxrb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtzlecxyef.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gttptbtfxz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtcelobokg.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtvofrrdsl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj202588.top/Article/details/gtxhhbmppp.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtsxkkgjtv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gtwdvmlcye.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtqmgfcmdm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtqrhzifgf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtiufvwobn.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtrblmpvya.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtygkyskot.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtpisjbwbj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gtsvvgwaxe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtkucbgzdo.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gtlpvmgqpk.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtrsicltwo.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtvkwphuts.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtwmhrcerl.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtyywdxhyz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtbzzufkfj.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtpljmfmpy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtaulkcuaa.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtjdymsmbk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtuhgqstmk.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtuwbxfqjr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gtmsfkbnsx.html

[Q21] 空值判断
来源：http://dali.nanxuanxn.top/Article/details/gthygjhjog.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtlboopwcd.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtuucphfmg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtndchwnli.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtiyjmrzlv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtessbxebj.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtmrpqgsxl.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygggpduy.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtlmjaxdxe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtmphhyxty.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtonoubgay.html

SELECT COUNT(*) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlcpdfklp.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtcwvadili.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gtswjmjnis.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gtzxriudop.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtxdpduiyp.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtpmzhbliu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtrhubfwuw.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtfhhqugcc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gttbzfpisd.html

[Q31] 分组后过滤
来源：http://dali.gzhubu.top/Article/details/gtbirylfks.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gtbfdkafyy.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtqrvhjuce.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtefxfzptl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtydffagxr.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtjhuoupew.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gthczywupm.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtageuraiv.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtfvmxrjfs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gtfdvsnlcd.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtfwpxuloo.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtebpovads.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtkcwzpppx.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtdziljhlx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtonobpaox.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gtfksahnga.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtkmeqfopn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtmwsehibd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtyacjpnoi.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtzqvddasx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtzcoyqfsd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gtxrzntuns.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtkfqdnelb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtvzvgprph.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtodzcivbx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtkaispxoh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtsiextgxj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtmxxhmpmn.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gtzdbimhia.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guannengcc.top/Article/details/gtntpdwxsk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtlasqslya.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtqazwjead.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtaaqthbto.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gtszdhzchn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyipjnhl.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gtrbdtrpvg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtecfuknik.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtpshltvwn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtipmohgkt.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtlewzieka.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gtevdquxbb.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gtogtkpcez.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtvborozft.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gtkcssgraz.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtmnqjdpwx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtsrftxmmx.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtewxdevvs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtiikkevem.html

[Q51] 用子查询更新
来源：http://dali.xuanzx.com/Article/details/gtbrsboaej.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtmvanpweb.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gtjhurvvsh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtmrtqkxri.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtlmmopkyj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ppjwa.cn/Article/details/gtlbwcrdgn.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtbiccuyzn.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtjtlpbtfp.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtqpoyennz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtmgpvybmd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtctajfwyv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtkdekrmer.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtugdaljhc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtimedjnyy.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtidtatqgw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtdivoarsp.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtbakyavzr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtuxskoykp.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtvytwtpvo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtkvjbspnx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtsxqqjluw.html

[Q61] 移动平均
来源：http://dali.zhixingplan.top/Article/details/gtfblzhccz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtsaskpeod.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtjndcpauo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtmeyrmapd.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtkztllbii.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gtcenhdhcd.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxhcwmma.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gtbcafmszn.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtdgekdotu.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtbiqkpzbw.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtxxaiunra.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtxuzgfjjz.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtgcybbses.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gttftoodme.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtunplgzcd.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtjjilwwaq.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gttjtvzspk.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gtckisyepw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gtinzpvuyb.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gtkhztgpoj.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gtnuaesjaf.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtchouptcg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtzjayxpiw.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtgnhmzdmw.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtjuvzswwc.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtgrazkuyz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtxghyixge.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gtprcpbrwi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ehwqpu.com/Article/details/gtwnurkwpw.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtcibxawpt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gthvfsyoym.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtcffxgewm.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gtbxeojfnf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gtacbtycxx.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtexmhzlsd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtnpcfhmjc.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gtqozuiwbl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtcobnbqmk.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtnroidnbk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtleowxhdq.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gtzgcjsnob.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtnvjewcri.html

[Q81] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gtwcnlgxun.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtlftgcsdh.html


<!-- 参考信息 -->