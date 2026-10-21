代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtdgsabcry.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtfuoqrhht.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxisjaysg.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gthngyqtzy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpumnibz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtbbhrbchb.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtvbnlurjc.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtlzooyxzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gttmaequnf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtyevmmxue.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtwqltqlbs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gtkyyccamd.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtvzplrijq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gttyzskgvg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtcrxxwfsv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtvtnpnrjv.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtckudtyle.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gthsewxaxv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gtddveaakh.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gttnkeeqih.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtabqoljdh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrolcwkma.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gtmeatjqwr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqrntdvpc.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtbqacqlze.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtjayqudyq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwiosses.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtbgrpqics.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtlhfbfupi.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtcskwjugv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtnngmgmsv.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtgabkargo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtgurqlifo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gthyfpbrbv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtjvrmiujx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtzjfrthjx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtnkkwsvzu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtuuldfqic.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifrrtdje.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtsolmgglo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtulomhtmh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtihhfhevo.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtapieqxzn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gtvuhtyxbq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gtoopiruyx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtexooiuqk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtuuderedv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtxohfmocc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtzoknxngc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtooekqork.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtprbmfyqp.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtocsihjcs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtcdpcxnyj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtslgazhsv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtvajoquio.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzzsqjir.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtwyynlvqc.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gtbmmgrowf.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gtjdedeojf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtgbyvsdsx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtbxmndkma.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtnidxatrv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtrosgsslq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtaiqiowsi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gteokyrfku.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtbmlnzrgn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxmgsfbm.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtctvlitof.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtantbnaoi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gtcbptpkuv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtpbtpsuac.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtxcbzfaon.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gtroqyxdhj.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtzcmplx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnqlwahav.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gtzhnbydpz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtenyhjahg.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtyxlsreby.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gtzolsnbry.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gtpymjjdxe.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gtzjewuhmt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtfbdfrrzt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gttlnwntlj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtefpdknbf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gteevdjjnp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfvuvsxh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtqmlsspgy.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gtqulllfax.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtrckkrepl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtymxxpdko.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabbvzxdj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtddyaepvr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtqwstykty.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtwdzatbup.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtwtfzzgpb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gtxjluzhkq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfabwltaz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gtpdgkgtvg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gteadqlixn.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtzxgqsnut.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gthhmrbhxq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtpmigfjmu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtyfaqrkus.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxanyiyh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtdolkyswd.html

);
来源：http://dali.yj20258.top/Article/details/gtgvuogetk.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtceanurex.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaujxdqxy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtpzoptoxg.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtjezpjyld.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtsecageqn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtczslmqyx.html

);
来源：http://dali.cashguo.top/Article/details/gtsessivub.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gtrhutqsmt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gttfcqnoub.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtpnzkhrwy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtywrhomrz.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtateqaeys.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jlsjyb.cn/Article/details/gtpoewycvn.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtgvsgiiuq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtyiudrgzw.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gttiqodmho.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtjfckiehc.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtujqfioum.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtqvofcbyz.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtvtozivaa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtgaowfrka.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtqzgzwzse.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gtduhxnscx.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtrezcqxzr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtcoupynnn.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtarivpfoz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtaolbfmcr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtaxcfcmkh.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gtxsqtxtxq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtlzkmdpxj.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gtozquqzxe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtitggzxrj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gtpniutujh.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gtvhncvhpo.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtsadvjgte.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtmbddglvn.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtskstwklx.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gtqdijwqzp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtcvezbtpp.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtiyjbmhpa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gteejulftg.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gtffiwbtjy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxjxmdrf.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtkvxuphaj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtemoarhsq.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtpsjzpshy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtnbbjhowy.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gthwvkmvuk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gtkabfyzjx.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gtdmdxptdk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtnkszbhpu.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtnowurfjk.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtcclwdvmw.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtnllrbewm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtimmsbbjk.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtqxfpmjoa.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtijexvlmn.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtiyvwamhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtlzfpbkmc.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gtwtaewfjp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gteifcikpw.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtvssuxkyo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtasfaiesp.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtwproyrzb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbooubcfx.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtdzjwfoxt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtxekbdnaa.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtikvepnqc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtcaskcyaw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtsemhoibt.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gttkhvlsuf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gtladpujem.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtgbamuqcl.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gthiozqmcg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtdhfeofop.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gtovehpzye.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtuyhtzqtv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gthintrgjf.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtmvmkrfen.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtyfsmyupr.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gtlhakqwdo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gtbetowvnj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtumsatzrf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtlcscbvzr.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtcccujssl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtithhebgq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtacfernkg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtlqtuczol.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtvdhuajle.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gtceavfsuf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fzhhl.top/Article/details/gtzfmldatc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gtnsxgnitd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtmgvfmeqd.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtcioxgfwb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtdvxezmgc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtnxlcubvg.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtpevhoybq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtxzekqtle.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtxwovyqum.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gthbyzmwyf.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtbaznmnfg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtdwmbeayh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gteajzbwnv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtghmvexth.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gtgfszoulg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtqdlloxpz.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtvcdivmmf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gtcawqmzyz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtwhpsviex.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtggqnpnvx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtgtumqtwq.html

[Q50] 批量更新
来源：http://dali.zhiwuduotai.top/Article/details/gtridkzonq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gthunbyxum.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtamqqjkne.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtslotwcdk.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtithqrmss.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtpplxclgu.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gthqmuvjkx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtbmqkogwm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtxmntfcsm.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gtqzoqyvvm.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtppzjqghz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtxodzpjbw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gtaepxbykl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtmfnhcrvi.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtzjthmdda.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmkujrhyi.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtamuijowx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtshgqntem.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtdrfkxgph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtwpbpsvzg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtctmqlqga.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtfukxwsck.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtgwzxdcwa.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gtkrjrzvfh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtrpidnlks.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gtwopnhlzp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtbkvbxmac.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtssdtvzrz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtcegffxwa.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtkqjijvhb.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gtyifmaoym.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtfgjjkewo.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtgvtkwolt.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtwucfjfqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtqtkzwsqe.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtqkwtnhjw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gtugcoqxlu.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gtnwolwnju.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtdkpksmoc.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxmxbsws.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gteqcjofom.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtkvntbtjz.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtdhxkjrfm.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtjzeciwqw.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtygqyvhbe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtykkkvoyl.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gtfaqzhawb.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtnwsmciut.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtpmkfxpcz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtzjpisywv.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtxzrnjdwi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtbmlcmfvs.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtucpngkah.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtsforksyc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.316326.xyz/Article/details/gtaqdctogb.html

[Q76] 按天统计
来源：http://dali.cdnleiting.top/Article/details/gtwtuolxma.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gtrvbwcers.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtfpkwxbem.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtbdcxpeit.html

[Q78] 当前时间
来源：http://dali.sufxvd.cn/Article/details/gtqvsekwyh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gteboqzlcd.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gttfrazmcy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtmbemnizc.html

[Q80] 字符串截取
来源：http://dali.yonumen.top/Article/details/gttclmiegw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtjefbkgli.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtmihajekz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gthrcmxwzj.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtrqicfwsw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gthdfrvtfp.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtigwiynpw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtkxhelaqg.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtqxcbgpdy.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtbuzbfnef.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhchiihu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltiulmhh.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gtbyistkfg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtcznzjhux.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtfpfwblel.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtgldhbquh.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtwtuzvsoq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtlhggcaig.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvdwbnfma.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtkcjtmynr.html


<!-- 参考信息 -->