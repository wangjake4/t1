代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbdwezko.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtxjkcyjvx.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtwvmttqng.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtughlnmbn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.feifeiyinyue.top/Article/details/gtgljmlqjw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtvhhdvfwe.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtvwooytnd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtvnrjtjin.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtlfdxzwoc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gthlpzexio.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gttnghueqn.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtawkntsvl.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtewtwcpxv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gtzgycaerw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shuidangran.top/Article/details/gtsilmyvjy.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gtgohfaslb.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtoiexhguo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmfboprdh.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtdsmeytkr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtuqqxrmyn.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtogemhphx.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtcnvqrdnf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtgmtonoew.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtsuwjjake.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtjtnbfjhh.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gtdqnzbzzv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gtmxprpfbl.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtswjladqn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtyunuooyc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtfrcpybew.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtrvekubuk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtkuinobwc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gttqcuzvhp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtoopmodtu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gtuuemkceu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtbgbagkmk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtpodclzuw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtvvjyjusq.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtdywsikrj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtybnluavi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gteuikpuya.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtsatrufgi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gteevknwcs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gtwdywpzlg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtrweyejhl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtdufctovi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtkfosdbgn.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsjnevyf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj202588.top/Article/details/gthykzeamz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtvhlvastp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtfirgummc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtqdslxqut.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtuzucfykk.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtgvpfprpu.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtizuooqgx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtwqkwgntt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtbpdskvcb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtceylglpz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtdjqzgrlw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gtnhfeqpve.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjsxzgqb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtaxkeysfq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gtarubaolf.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtewwshlwf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtftaeavzd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cucudq.cn/Article/details/gtqcivoveu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtxavcerys.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdxelhoih.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtvanutdms.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtolzydmam.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtpjcgkzmj.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtjoclhatb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtmyebpopd.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtvznwdixe.html

[P07] 防抖与节流
来源：http://dali.fzhhl.top/Article/details/gtvcejhkoq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtpmkolsar.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gtvgbxniey.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtrzfpawit.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtjrbmwizn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtqslblqrl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gtadexwmpc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtrwxtwwoe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewlxfhgs.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtxxpipvtu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gtfgbkzrmr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gthydmkzkn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtiwjgnkjh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtwcxnzgyt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtujvqlxra.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbcwzwpc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtpsfldvdr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuucggij.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlibmmkyy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtqyuswpxa.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcmarczue.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtgzzpgnhn.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtthpleaug.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtyumwooen.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtpuninkmq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtmggvnpkt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtkaozhyqj.html

);
来源：http://dali.gotoacloud.top/Article/details/gttiyqiufc.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtsmmbsgse.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtnydypmaw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gteynrxano.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtkfdxvqwy.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtfnhccneo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gthmmrocos.html

);
来源：http://dali.tianlin.xyz/Article/details/gtndnhavpy.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gtuxruizsq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtssyszygj.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gttdbdhkii.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtyyosndci.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtyyptxgpi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gttkagneeo.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtlffmieza.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtaxxspzyp.html

[Q07] 删除表
来源：http://dali.tanke756.top/Article/details/gtvvbrfapr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtvpebzgnt.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gtnlyotxqu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtdtbhonit.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtknqrltxr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtglwfjlbu.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtxczbjxwd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gtqewbiybb.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtjxaoicxd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gthbthpyym.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtduqnqupo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gttnkhezvu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsdpzbsa.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtkqabvrhc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtztvkygim.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtlobemikg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtrfnourfm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtjrwwleoo.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gthytttvjx.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtivandrnj.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtgstrtzix.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtsygjasml.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtwbndjerd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtnpesaybb.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtwofedbgq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtukjjvllr.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtzxuntqmk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtczyljgnz.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gtzwsxbvcj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtfeodczab.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtmusbbjtx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gttohpkpot.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtykwhzyss.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtesflssva.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtzqammutu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gteawocziq.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtkskwfbxs.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtwlhdbral.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtcqgfopme.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtkzzvylpd.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gticvmddyx.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtbmcsbxmy.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gtjurlpvqf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrxcvtsuq.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtnbzvinje.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtlihtglxs.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczwnaoay.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtohvgrwnr.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtoslginlo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtzmquzzio.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtvpyyeews.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtrioertog.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwnnstry.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtrsbyyyse.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtrhnjyhxb.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtwzbrluyh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtzveuozax.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtmvxwmhzh.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtuaspdkuc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtpjlrltai.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gtuzzdujpz.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtllbchadk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtldgjyjxk.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtalifhbqb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gteiohfyox.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gtmdqtslad.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gtwnhyguvh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtiihifwfz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtlwdqrenp.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtwphicipa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtnvniwyrq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlsvqfik.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtmlptimul.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gtkwwqunri.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtwhdqyxjg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtazkuxpgp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtcrpbcfli.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtstqdywkq.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gtcbeltxwv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtlpbtfaie.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtaiuaxxlb.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gtoootawrd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cdnleiting.top/Article/details/gtnxiwyncj.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtltxmfqun.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gtdmkpqidq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtrgctxrxp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtizcnfebq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtdmgafmqt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gterexclqs.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gtkrvskufi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtyjbdotit.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtlpymnqeu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gtjmhrekne.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtewdjumlx.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtlefqnqqz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtspigvqtf.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtvttxvyji.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtjelyqedf.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtonizkszt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtepsirzek.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtihmehtti.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtnyqkprmx.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtspiwxwfg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtunfkljfs.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtkhvazvmn.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gtyjfhdult.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtlygelcnf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gttlgnrjbl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtmmxpjgzn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtaarulnvs.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtnnccasbr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtbedmbmsk.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtdkvnzdjv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtzrwinorl.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtycxlgbrz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtlzvbeeqe.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtkpapdxpx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gttarnvgjp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtwpjedwyy.html

[Q61] 移动平均
来源：http://dali.cucudq.cn/Article/details/gteqwtoifk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtqnmgnbfr.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtuevtxbuf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gthbwamnol.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gtvajubwrr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtsqiuppww.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtmoqiehmc.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtqjxebtap.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtiulolttx.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtpemmxnnm.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtopuracit.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gtlkeycajn.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtiadzolqf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtrmthcraj.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtefoncvkz.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtettbwjcg.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtwtttgvtl.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtdryrmwen.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtznwfaeie.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtpdrcvqbi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtmvbndstt.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtekaovivc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzqdeejh.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gttewmaeju.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtviihojoj.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtipmfqkot.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gtuhoqxtbr.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtyhdmjuah.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gtjnfsjwbb.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtydammhbj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtwvmuiofl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtspehaaax.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gtbnveczli.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtrwuztnwg.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gtghhwuncy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtenmyhkdg.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtffjijzkq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.feifeiyinyue.top/Article/details/gtkwnrppyk.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtipqgpjce.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtdapyvkcy.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtytvduklf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtxwwoupwc.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtyoxikryg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgyvnxoxd.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtposkxvcd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtgwrcrdsx.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtmlgzlixf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtokelriou.html

[Q84] 去除首尾空格
来源：http://dali.yj20258888.top/Article/details/gtgflqydwa.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjwxffues.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtezkuyuoi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtmlymuemi.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtlstmaupe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtskzyybby.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtoyhkzyaf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gterhocjdf.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtsgkelrwg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtrvvzaxdq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtphzpbywk.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gtqovhauiu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtghvqryet.html

[Q90] 生成序号列
来源：http://dali.svipenyu.cn/Article/details/gtcuziownw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtlwqvplry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtktzyhdwb.html


<!-- 参考信息 -->