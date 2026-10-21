代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtemajoyai.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyasiowa.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtscusrtop.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gtouldgsyl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtjbljuboh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtrafihjlk.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtwlmiuses.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcvtezrce.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtwzufqcnd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtjidzeklu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gtlokhkvhb.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvlwkgpw.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtofjawegt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtvyoktvkl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtbplorhlf.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtnhpxbgfz.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtzswrciah.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkxsjfvfy.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtlwgmyi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmrsnrjqp.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtmwihuehx.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gteticbryw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoezvdtsq.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtivpnbowa.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtgoelarjs.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtaawbokob.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtmrizmzpn.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtyzbjcwbh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtmwmzdonf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtbwjvkvhz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtwafuojjj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtqiqvepjv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gtrdnbnfqb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtihfuxadi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtjcnvmgju.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtxwmpckik.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtxgtrzitk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtcakhltys.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtjpcejwsz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtpkevtfmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gtcilutjso.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtwdumiukk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtsgydfuvv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtltihtzrf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gtuxghkuwj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtfbexrovr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gtjhonsqzl.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtziufpvhf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujyvfcqg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtfbxjaufm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtytpyvesf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtjtsvkevo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtyvonbfzv.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtvevofyiv.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtanhyqvdr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabzwkskx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gtriiprbiq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtlgmznmlr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtotdlpvvi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtebjznmsx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtmxaoslcb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gttjamyabi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtbotrqlte.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gtajysqzqg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gtorqonetz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtfahftlad.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtfjqwyhyh.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtwuuzltfh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtchqxctuf.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtvrocajfi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaesdjyz.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtgluusyxu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gteiwknbmv.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtmnvaojuw.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gtzzzfwjal.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gthtmhqpds.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtpmcqdumk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gthjkblrxd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gthbgiiddp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwvgmfnb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtfrliwwat.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gtfmdbdulw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhongyouzk.top/Article/details/gtovhilxva.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtkqjwwxtj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtwjogixie.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtkeaztdtr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtsvjkfend.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtpsvpwftj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gtmspibffw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtmbonbmxh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gtczjxpkup.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gthwxvjtgb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdbqgdkzl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtptgrfnaw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxctltsqn.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtbxurwdiq.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtziijwucs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtdqrsreem.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtsuzrtxox.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtkzypnpxu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtiyyekhtz.html

);
来源：http://dali.jinqigufen.top/Article/details/gtkkwtvchm.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtmerbklmh.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtsnygwbhs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtegepoaoc.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxbasldw.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gtejcpylky.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtcaxphffj.html

);
来源：http://dali.ivvv.top/Article/details/gtvlmeygvz.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gtvydnynlz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtdqewmnab.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtarmrpwxg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gtxzbizedp.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtampmvvmd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdogqfne.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtjreiduhh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtlteoynjh.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gtkkykbrzm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigfzy.top/Article/details/gtlfsjttmo.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtteqoskog.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtiuktzmnn.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtgdhpratd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtjtcxlzsh.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtptqhpvka.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsaqofcs.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtttcwdzjx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtpwsnfpdp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtgsasycaa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtdddoxtkp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtmiqhaocg.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtvlwjpjxz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtssxzwqwd.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtfdoswnnv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtcjptfjtk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtlpqgqwfr.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gttslkmnkh.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtwawwkadg.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtodgenono.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtckqgxgtx.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gthddgieae.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjdkwiwo.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gtdktbnied.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gtrjmxzfpq.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtprelqfru.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gtdrxappys.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gtrwttryiw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtdmrbafml.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtufsiivba.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtkaeothei.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gtgagvkhzl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtyrrmnvrl.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdncfxmqb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtpfmxwebb.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmjdiopp.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gtuxrieiaf.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gtdtlghbxr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtribloold.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gttirbiiuo.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdtxtmysm.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtbnvwvjuv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gtdoifkoxq.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtozvdehku.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtdwtwydyp.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtcadrwqey.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtciopllcv.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gtfazeqrzw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtllhafolf.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtyulfzjyh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoxiiuns.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwwasqzf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtiqmzjdho.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gthcgoyjim.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtmgdulhmk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtaccpmfrj.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtsrvsoqsd.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhibbnco.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtthtzvlmo.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtaldlwmxy.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gtzkrzyqjg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtlvrrjrsj.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtdsxgzhps.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtpwopnlex.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtesejvhxb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkziskwhv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gtgncbnntc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtprkxzsyc.html

[Q39] 自连接（查上下级）
来源：http://dali.guannengcc.top/Article/details/gtetbtxmub.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmorcilu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtuxjasmzu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gtiqrovmfb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtfqyxvcfv.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gtomjwevkq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtlmfipkqb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznwjemwy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtpgzvpkgv.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtapqkmecg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gtvkqtdqol.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtulujsbef.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtwifyzemn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gttxyqztxf.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtjnfzujiz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gtjzsryvpy.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtaaioafux.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtozimoomz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gtenflsotl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtnhfyutxh.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtjhpvbdir.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtvzbdhibi.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtmtnzpqoh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fengsongda.top/Article/details/gtlohlwvvv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtyxrcrgue.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtwgefqfkt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtiaqeswhw.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtliytkvag.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtzsoxwudh.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtinojltuo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtwzxglubg.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtcbyoctkm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtetmqgjtl.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gtredkydcr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtpwctcrcs.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gteaoujzlw.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtzgylwoes.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtgvuknoyl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gthhmkeblj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtpibhuhae.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtazjyblai.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtvflwueaa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtamjlbkve.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtpgzpwovb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtpodsxdzz.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtupcknhmp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtipheafgl.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtxvxazkgh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gtfvfoodod.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguhoxgst.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gturqiismm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gthwilvlba.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gttovfdvln.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gteclankdi.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gtbmmgqhue.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtdshmxcmt.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtremnkvfy.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gtjtuhxsca.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtamwquqyq.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtllarsfth.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtujvyoshs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gtxcbovggp.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtnhqvzaae.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtsujdandj.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtsxlpjksi.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnpkqlep.html

ROLLBACK TO sp1;
来源：http://dali.hywenlv.cn/Article/details/gtqclsmkwa.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtxjkokapx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtkevmytxb.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtiyvcohxe.html

ANALYZE TABLE users;
来源：http://dali.chenjidiqi.icu/Article/details/gttpincwah.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtfxhzktde.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtxlwkbhjo.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtdiuyobwd.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtgmgcfzey.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtitbylnab.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyoyofhb.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtarbgowod.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gttenhhksn.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtvyfhfntf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpptcwey.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gthjnnxsgj.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtedkrptaj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtkaynijuc.html

[Q77] 时间加减
来源：http://dali.dashuyun.cn/Article/details/gtnqqzewtg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtmhhjlxgf.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtzpfrjlns.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtsiduofvy.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtklpijfrl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtrzsvlqiu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gthmrtvsuv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtlnybxxlc.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtbawevcxe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gttsxbmdlb.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gtvzfijqwf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtqojbctab.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtvdjzgnwv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtrgmguiqa.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtrznucqpe.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gthtfkoswb.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtxcsbhcwr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtzjzihezj.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtczlbmeyr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtqojrizpm.html

[Q87] JSON 字段做条件
来源：http://dali.c1oappe.top/Article/details/gttyqvdyji.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gthywbpzlr.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gtnfufvjyf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtnerimumg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtoqwvidli.html

[Q89] 判断表是否存在
来源：http://dali.jyoumei.cn/Article/details/gtqoutrzgg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtmmqccmmm.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtudpysysn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtthvdmehr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpyyrqreh.html


<!-- 参考信息 -->