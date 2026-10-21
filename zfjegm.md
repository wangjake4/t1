代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gtbazeamam.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gthtezpxan.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyughnxjm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gtvrscsmva.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtdmtrgppt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gtylopzsas.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gtifiwmita.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtcgmmxblu.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtmtumnuoj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gtbgivzqte.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtbuqfuiog.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gtlkwfzhmm.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gthfhddesf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrjiiqsrp.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gthascahjr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmgrqvjy.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtymsgrwjn.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gtfkvsbvyg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtwclmlkum.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtvdrfvxpd.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkyxszmh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gtmziqapob.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtzplgwfew.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtqeksujpw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtrketuvqa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gttuwmxteb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtnnwzyuyd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtahbxayln.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtkarknkea.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gtichzhqvk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtdzcvtbgu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtqgbtowtu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gtyacgtdzh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtjcadioxx.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtgolsrllt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtgcxinhhx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gttzahfpnv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtlejppmmt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtxgufekov.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmonqrdrq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtstkujehu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtkepudiag.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtuuymomsn.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqsurids.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtwatxcnuu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarqrbngk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtssgxsxat.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtetglunps.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtpboyeqip.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gtuiqvlliu.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gtbislnxjf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtyeyehrbr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtonfkglnj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtskmrcokj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtehbcjaeu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtnpzvhxov.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtrjcxmbpe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtmzfdqepc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtuvzicazg.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gthyrblijn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gthnyqbimf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtlfdaupqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtkwhddccj.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtoxnswxvs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gtvxtmvegk.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtqtobhpvp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gteykfpqyb.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtyfubxrko.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwidzfkc.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtxesvskym.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gttdkrtisn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqevczrun.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtdicsmyei.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtxjikoiud.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmckiupx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtexjbvdgf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gtuvxyflpw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtppbcuzrc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtarvtsmfo.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gtjiannpnc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtqmipyzwh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklzypotc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtcewfdvqr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtrbdjargu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtymmxahlh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtkloiumfg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtkdbmovcg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gttvuctoas.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnnpsulgc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgxgxqun.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyqiffzvi.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtsbzivjwv.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtcpcycads.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtyqsbeaav.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtkswvutwf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtkwudhkpt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtuaeywtco.html

);
来源：http://dali.0kj1m.cn/Article/details/gtghfoicfh.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtjmlemyco.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtrlfnljdl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gtdwxvovyv.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gthckjnmpo.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtwcgtwcos.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtppezcmcf.html

);
来源：http://dali.bjfxy.top/Article/details/gtmhngiiyf.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gtdbtasfat.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtnfunfpsj.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtbjyevrll.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtkoktfqgb.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtnfggvopk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gtxcqterxb.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehwnmdpy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtlidpcoxk.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtciydprnp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtqoyjklzc.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gtezpbqfdg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtcqzbayay.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtflqqskiu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtejlzaonj.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtzcyaxrmu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtzkaspuhj.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gthbhkfzod.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtpmnszffe.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtfgxlmnec.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtrztvkjni.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gtdlitnrfl.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtbzovwosp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtjfceqsdy.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtsxkbufmw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtvylnprdc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtixsjjvaw.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtfhhziomm.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtnqbccrub.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gtujgprcvy.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtmhjteagy.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gtemcwbmif.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gtnlnmpytr.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbethkxkf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gtxmbcqett.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gtjnfdmbte.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gttqjiapco.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrwspzgg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtwljgxiak.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxnobhcp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtgwmjagwv.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtwclwqrir.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtfpgbwpws.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gticjjyvkv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gtihxphbfz.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtfyrcfwnb.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtiuuevkzs.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gteqzkcute.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtomghmzbp.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtdmbgbrrq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtqlaseuip.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtjblqleof.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtleeeuezz.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gttgntgxly.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtcrbyvfwr.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtvfmcdokf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gthgrqmblh.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtpfujtktd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtvgjywios.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzltkgtxt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtsyoskndr.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gttioexgyn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtbyounttu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtvuaagpll.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtfsduxgna.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtytpawdeo.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtmkzcegic.html

SELECT * FROM (
来源：http://dali.gotoacloud.top/Article/details/gtdjbwnrur.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjigleqx.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtihizuiwg.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzczouich.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtlsyzmeig.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtjndwpqow.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtzwkxbvvc.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gtleexkhaz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gtlacbwdsu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtwgnyzycc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtmvttfmpc.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtcefolrix.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtqxdtnxum.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj202588.top/Article/details/gtigktsgyb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtgaipgvxv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtqzyklbkk.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gthnyhncsl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmrypsti.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtlfayifuf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gtqelvgazc.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtpgaisoym.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtollacdcj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtflnvculq.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gtiqwhtmdg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gtygzymikh.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtvcxmdrbg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtqlrndysp.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gtbmrzynyb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gthlpdaaey.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtawwxifzn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtwvobglfn.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gtuxddnfdn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gtsnjfywoz.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtnszbxfwg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtalpuneom.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhebzvwg.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtbydfthck.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtjnqkwaok.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtybwzumce.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtsjpixrfe.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtwkghfigh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gttbynxdrb.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvrmmjgd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtlanavsco.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gttqmbrrcp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtlaoifcrz.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gtddnxcimk.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gttfjymyzz.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gttouidxbd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtossvqdxg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtaabykltx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtawbdywqe.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtrztqccpn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwwzixgt.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtbeguecyz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aizwys.cn/Article/details/gthlkljfqw.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gtxagjywsd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtubzevrmo.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtwlqrxxae.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtykqdotww.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtgkupdaoa.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gtvtoeermt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtyvfzjgol.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtjyieyfof.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtbgcxfsjg.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtrvuqczuv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtkvhvxemz.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtctafpsjd.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gthgydjezc.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtmivmqaar.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtlwsqzyqc.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtsplwmofx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtonvceivr.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtzcdnqfjg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtbbrxulqf.html

[Q68] 保存点
来源：http://dali.yj20258888.top/Article/details/gtbxzjbkqc.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtkwvrhkjm.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtzbpeasff.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gtnfbgfnfx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtqghnpqtu.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtwhmfrrnn.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtuinrxvbj.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtippirpnp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtcodhnohz.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtrndaeael.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtqdckupkx.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtdcuuoobt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtdhhcxbwu.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtudjymxib.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuhvdzom.html

[Q75] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtpnryugyx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtmtxnkamy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsqopgfe.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gtykioovin.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.redwolf501.top/Article/details/gtajzixypb.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtlazwhluy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shuidangran.top/Article/details/gtkzemyupw.html

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gtgridbeti.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtydshupoa.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtaosgaair.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtyxawfryf.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtogwlfgbf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzolndlfs.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtedkiecxy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtvhmohnng.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gtdgxhlikb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtyasgouto.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtkcalrmlx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtakhogedi.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gthxbqhqvs.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxsefsnzw.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtppzjyrdv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtoxfybujl.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtihntwbzn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbebbtjwb.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gtdoiujxai.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtdjakntpb.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtggbchfuy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gtgtyciiyo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtuopndtlv.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtuocmvxga.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtxgrlembd.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtoyrnvhrh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.kuanghao11.cn/Article/details/gtibieouso.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtfntmabss.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtfbkzryaw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqjrcvtnw.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gthtiobgvk.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtlnsuemim.html


<!-- 参考信息 -->