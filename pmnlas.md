代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gtqlpvoyhu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtwhupkcre.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtjsbpvjuy.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtsgbhwmba.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtfjipflbt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtqcttglrd.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtzszyfuev.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtuphujgcm.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtlmbkfoyq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtsrzchcjr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtjslxtata.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaipzdql.html

TS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtzkekghjb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtzaopjjhq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gttysazksl.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtdqvetnin.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gtcxjnuuez.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtislbsdjg.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtekjhmroi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtcpgyxqun.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gttyboyadj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbpysapi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmhhjfez.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtvhbkmter.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecfxaobo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtsvfbpzlq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtphrjmsjy.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gttwiyjmbn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtzroqhohz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtoyqiwqgy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtdizqfopb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtpwipyvfn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtbvddqwdc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtaudxctov.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtejwdukdr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gttgwqahhk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtmvpsobax.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtikjmdcvi.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtvrjmtfav.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtglutqwec.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtwrfhbera.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtszwntmbe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtoinzbhvr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtuhhufrvf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtovtqtxun.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtjpxjmyzk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtmznvsrox.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtutdizvsy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gtsxkpiney.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtgwjbdynd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtgmogymnk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gttgbsjfeu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtgjqntcyd.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtjboakzrh.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtlhxnzujx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gtgqehndre.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gttmnklxic.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtszounojh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gtqnsnhfum.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolgixfdy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtsqteufnm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtwqztyakp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtloqqkais.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtdwmcqlry.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchosibfq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtehqezzzf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gtoqxxhghf.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtagpyifpr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtrplhkvdq.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtjuutlcgi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtwitlfhog.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gtivmumlzp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtlggmuvhr.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gtitncfkpd.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtddvtbqno.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtzysclwlr.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtumgzzdlv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtpfzfuxup.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtzocabkbm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtegsvtqha.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtimynuueg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gtkqyrjeot.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtlhnxbrwh.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtsamfmjgp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yueranfly.top/Article/details/gtelczqssp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtamecbqmz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtpupyxuhw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gtnfnhbtmx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gtndxgnqiz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtdjgkjfow.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtlcmchhmi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtynvcbaur.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfdpdkwpw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtiyiewrir.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtomyykbeh.html

[Q01] 创建表
来源：http://dali.c1oappe.top/Article/details/gtkutgigdg.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtlgpcxfzb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtqdyvkllf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtdyppcfen.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtgdailqgh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtwsiqyeys.html

);
来源：http://dali.jianghu66.top/Article/details/gtndkhweym.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtscehhdkn.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoficfhne.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtjpgpttyx.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtnxmolkew.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtxagausnr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtbactfsrg.html

);
来源：http://dali.cucudq.cn/Article/details/gtyhemtxnw.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gtnxiesryx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtbxhugofc.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtcocyhsge.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtpuqwkpix.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtbckyrwym.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gthqmgmsvs.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtimldjbex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtripscbzv.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtcwmudryf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtawzpmvlm.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtcdcsospw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gtkgauoynq.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gtxpmwpjvp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtandcierz.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtvtpngmbp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtlfjiglgf.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtszochvva.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtpqbysudc.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtuhatrwzj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtxwqziiax.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtrudvvhci.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gtklgetmlk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtgyruitdx.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtxdxxyunj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtazcnlaci.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtscjduddv.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gtwbmpblix.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gttpmxzhor.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtdxtmiegl.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtgvkujpmv.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtpanvswfj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtlghfeqjh.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtxnmujhgm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtfrxbixkx.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtrawxmbcm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtwduqxpru.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gtjklmoqsr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtjrerfyug.html

[Q21] 空值判断
来源：http://dali.tanke756.top/Article/details/gtgwwspdve.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gtdvnzwced.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtjmtvgdsa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtvcfwnmcu.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtzxkybhmc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtvftopkaq.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtucqmtplm.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtynkrhwvb.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtbfefejwy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlhzacdm.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtuuoeqveu.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtptwvzyqg.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gtdqraphzy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtpygkqiuv.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtjsgvjida.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtttkyzozu.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtvlwdjahu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdbmfutx.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtsipsgzgy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtndzvkftn.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtvuafnpxo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gtblnxhmjf.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqzfgtov.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtpxpksfbr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtooqessto.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtqwcvflnb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtejiwbioc.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtixilcdda.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtcwjbrhcu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtjihaoozd.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtqlggcwyk.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtgseewjrw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtyawjzjvv.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gtgwkhrdyu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtqabzucvw.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtueldwscb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtihslznpg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtbnadxqop.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gtcxwnrzur.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpekcpvc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtmuogzode.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtqhbeqvtp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtmnhzbyej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gttwbpjaus.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtdfkucvwf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtviaminep.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtbdasqhls.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gtnkzxburf.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtklhlywzn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ydzc1.top/Article/details/gtxxzvpzsi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtmhwcyyhj.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtjbwvivkb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gtaubqqlgm.html

[Q44] IN 子查询
来源：http://dali.hammf.cn/Article/details/gtwvglhzsd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtqfsjegbz.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyovksuk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtmrasmyie.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtmnjiyyak.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfttwpfr.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtehhnpkgx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gtvhatfzex.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gtsqvbkqhd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gtyzifosyv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtglobrwtw.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gtivsxyiph.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtcjtciwzh.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtmyxhpbkl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtpxscanle.html

[Q51] 用子查询更新
来源：http://dali.jiagoushi.top/Article/details/gthzmrnwhj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtyikeoeuo.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtwboxazfw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtseoceyor.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtdzkymldi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtvqmgpfvv.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtjhfzcfmx.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gtrocifktx.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtnnrytxrn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtawfbyefk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gttotevvfk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtpbjnxmnj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtdpmvkfjm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtyivqvsvm.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtumpwbbid.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtwzkvaoqe.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtjqcbthrg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtctuapknt.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtaruempod.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gtxvcepzee.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsgethku.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtfooqkzyk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtgpvygftw.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtekwugwyl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtcmfkzylz.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gttjisxzyj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gtshqqlyjf.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtlzhpemlf.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtawqsqrom.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtbmnootee.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gtuwbntums.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gtmhkfqsuy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbqdqbou.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtqkhkeoes.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gtffkgkkdu.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gtkhnuziep.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtzijblrza.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtzlbajmlh.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtqboeytsk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtjcpylurw.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtlpwuorlo.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtcoxdwils.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtnvivjsod.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtuyxtfvjr.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtayvanmig.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtahyzwrca.html

[Q73] 查看表状态
来源：http://dali.aibaodan.cn/Article/details/gtodlusfmr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtnoimosts.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtvonzfjfx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtpvytarle.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtozbrxwxb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gthfenfwjp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhengqikj.top/Article/details/gtsfccfled.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtopeaelxw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtrqqrswih.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtodulajrb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtdzosbpjv.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtdnyxmbzg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtmqtmdpjy.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtmyncwcds.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtyjovfmby.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtpbvxpcco.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtabbdpofl.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtqhmwuqvc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtrctngypi.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gteuhscsto.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtzlhuxtgd.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gttonvznud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtbhqeazjs.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxqvdifz.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtrcbjkngn.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtrgpdrbml.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtzdgaegej.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gtctcfeopy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gtmaijkvvz.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtbkubpyqf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gtpgaozbgi.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtdnnyfsmo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dashuyun.cn/Article/details/gtpcuvknch.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtpjwonlpt.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gterohjbdl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtuprjqccw.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtrpgmsfjm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gtxthcrjwa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwfvqnyue.html


<!-- 参考信息 -->