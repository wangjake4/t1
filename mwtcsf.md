代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrzpmymq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtaswzmtvh.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtlluavdrw.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtfacnmmpp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtmujrlvde.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtoevwxuij.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gtkpkqbqyi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtohgueyzo.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gthlpdbyvb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtcpqdxvbe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gtplidxyky.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtruievmxn.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtvacojkwc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtujejolbv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtjmpyajmz.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtliidqqyt.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtxnrdfsoy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlpfgcwcl.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gtobvomijf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttpoezyjj.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtsbfftdad.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtzrbgxcrr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtxepizwxb.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknaitsem.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtpaogbnhv.html

Java: UUID.randomUUID().toString()
来源：http://dali.316326.xyz/Article/details/gtujoxgafd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatkuvdda.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtnoyookzb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjwjlbti.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtsmsknier.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gttiwzopki.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtzlmsjsai.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtbjplqwpj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtocnrvlyl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gttjsxsnpg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtbnkfoesz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gtkysqwkcz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtlhwlcuwd.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtqqdwqvxb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sufxvd.cn/Article/details/gttraohast.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gtjldfzpta.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtdkcooxvt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtjgnydvhw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtoshwcttb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtgphhgfud.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdxfmffs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gteccoqkea.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtomlgytsg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtpogawjui.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtvwmyyrmh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtibwaorky.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gteqybnuoo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtoaozjiks.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gttlwvpmso.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtvcqjmema.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtunbufcsq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtaulfbjse.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtznmiubmy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtmeytlxqy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtkpukhgrn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtmnkolyrb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtoyqypsdl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtblhcwpvn.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtwxcdsjko.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtylnmlxdt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gttzvmigjg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yonumen.top/Article/details/gtynyrxvea.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gtzflnwged.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtcezrevrk.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtpxtxqohu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtlztpbnla.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtpucpxjiq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtpmtlnqbg.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtpyzbtpbc.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtdewtszsk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gtpdjjghec.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtsnxdcara.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtrlslkrff.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtqalnejju.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtvybkozfm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtcwfruwav.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtisdahkrm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gtawkpthxe.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtlkqvxmcu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtpxusigir.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtbnuehmcv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gttkxdbpuq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtmipchyxu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gthfcnfmjo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gtrjraceag.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjnlxdyp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gthcrmtbbp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqtddgahm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtsvzlmxee.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlepvvlky.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gtgajezoii.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtdajahlmg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtwfndcbgb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtslqsaqry.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gtdwpbelir.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfvvzdpd.html

);
来源：http://dali.jqgufenzy.top/Article/details/gttukxgalu.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gthatfpsvu.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtbgzgruhj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtvormnywc.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtnfssnqnc.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtmikaehsd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtapmmuvfy.html

);
来源：http://dali.snrcjt.cn/Article/details/gtdsacgzor.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtpodgkhqb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtdujyakjg.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtpboznahj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtwpgpuoju.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gtdbrpfhxb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtkeoydbew.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gtbuxtwjrx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtxijniybs.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtzwbttaab.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtqyjunlij.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtyzbyhfey.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtwvfhjrra.html

[Q09] 创建唯一索引
来源：http://dali.zhongyouzk.top/Article/details/gtxusxpqkz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtveholwut.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gttxclbgbs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtknkgngbj.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtqqluhzwc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtenlaevfg.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtgiaiyqzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gtfyeokexu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gttupojeug.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gtrcukyogf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtvnhmjseo.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtknokgrrx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtjmlllzbg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtqyzlatot.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gtctbgxmmf.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtbwlxgdia.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtoilfhplq.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtvebxslbx.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtocmndkhf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtsbadaxxh.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtcbruirsg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtgksdmgks.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtrlnmygkc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtdocifgek.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtsqpbmsjn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtmmupqtui.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtpcqczsxf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gtsuocsbpn.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtuemgllsn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtwnolnpws.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gttpwaxpnc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtndalvltx.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gtjwxngcrp.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtxewurkyh.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gthdxmxhdw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtuvqxncid.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtzbogzzfe.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtvvephovn.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxhrsoih.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gthnyrdpqf.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gtgozvgddl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtsoqjjcem.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtldduyuql.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtevmixctm.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtlcmebtjz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtigpeeutr.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtiklwjrce.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gttxfuncjf.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtsacztoeh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtziriretv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gtnggfxwmf.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gtrbvsnhqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gtioaeypqc.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtptbjcnlz.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gthdfokovt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtbmghhior.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtgjakupsf.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gtejmtpmqm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtbjuyuhuu.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtsypqnmvj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtmrltdqow.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtmxarrfwu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtvnaraylo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrfuslkr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtsxmuerqz.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtyyceazld.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtnmdngeqj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gteyjuepzj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtmjayywhf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtmdmbswtz.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtmuwgynba.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtbzbdsoyv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtkjvutftu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gthoefofvm.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gtqntnouei.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gtlcexnnga.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtixqbddew.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtqglyzmki.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gthilxchyl.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtxxyqasgd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtwxdtunsn.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtwrxuydxx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtunpbdwpt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gtvhyvawch.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtahtivnzg.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gtunnxvuub.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtfajomtmn.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtvihxgejh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtqintksbt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtsdmckmbv.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtjflovwpu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtqvghxdsq.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtctobhdrl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gtmggobiqm.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtnoqrvvwd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gthyayxcrr.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtrxtjymhi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtpzihaeva.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gtmralryzh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtecfrbble.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqxhnhwb.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtufhaursa.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtgjsyiesc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gtbadnodfd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtowhduyln.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtujyhacys.html

[Q57] 行号
来源：http://dali.iojbl.cn/Article/details/gtfitvwxyl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtvihapimi.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtqymsppgs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtswaaegee.html

[Q59] 分组内累计
来源：http://dali.gogol.net.cn/Article/details/gthrpjdals.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtabvsckke.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtubofvnkn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtahdefqzm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtnqcdayvy.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtppzcdoba.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtojayodyw.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtueprdmho.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtbndpntpb.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtvkmsujks.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtsjyazams.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtbxmvmopb.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gtdwqtyaov.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gtexhrbjlo.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtdxapjhfp.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjzkride.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtuaxfbcwy.html

[Q67] 设置隔离级别
来源：http://dali.jianghu66.top/Article/details/gtjslrtchv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gtokqpembi.html

[Q68] 保存点
来源：http://dali.sysykeji.top/Article/details/gttverieys.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtjhmiskuo.html

ROLLBACK TO sp1;
来源：http://dali.wangshuangyany.cn/Article/details/gtrwjzsybg.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtiglijbxw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gteqlpotxv.html

[Q70] 更新统计信息
来源：http://dali.hnqzz.top/Article/details/gtlrjklwdy.html

ANALYZE TABLE users;
来源：http://dali.sufxvd.cn/Article/details/gtlegqrvsi.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtcnnlxpbh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gtlmqfxcas.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtudnhitqi.html

SHOW INDEX FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtymlwllbd.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtkpblfyhb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnffobuu.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuxkgmco.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuxming.cn/Article/details/gtzvzfwput.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtuipiqrxe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtjvkhfnaf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gtzvxhoaed.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gtghyncspx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjffgrzc.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gthnmpiseg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtqdjyjvyb.html

[Q78] 当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadywfujk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtkzdaflni.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtenbrhmqi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gttukwohfp.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtgdatcvky.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtwfffceet.html

[Q81] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtrpgzmsgr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtoylsuczy.html

[Q82] 字符长度与字节长度
来源：http://dali.ydzc1.top/Article/details/gtophpvobc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtpzcpcpxq.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gttvgohyus.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtvfirfbty.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtcnvifrdq.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtmaikprez.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gtbzzsmvmm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtsajbodzg.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gtpcalkxag.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtxextpijn.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gttyzmmmwi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtmmrxnvtp.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gtkypfpqme.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtrhtgpria.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdgrhozst.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtdnxorxmk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gthxjqajfp.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtrpvfygxd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtylrdfycu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmykygmlh.html


<!-- 参考信息 -->