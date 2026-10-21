代发 wailian999

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtcrpbelff.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gtkwafoypb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtvxhpiexa.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtrpxjqiqo.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtqgyygjcg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtmhqaylio.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtbgqioftk.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtjcowyhcl.html

C#:   Parallel.For
来源：http://dali.zhoulong.xyz/Article/details/gtalxflvpd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbnmmchsc.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtackwjgda.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtklmnjayn.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtkfcmebjf.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtsgylkrxd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtegkqfotj.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gthzbsyntr.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtyucepjig.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gtueoqgmfi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gtaafsrvww.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtwessstnx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gtlptjvozy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtfgfsfiry.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtwkfstbzo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtjwhyciby.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtrixslgvn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtvhumdmdk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtdjzlecsj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtlsdhvfbw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtmhsabtdm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtofnighae.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtockgigiz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwpjwvev.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtkjjwdunw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtdikecdip.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtfjnomf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtohfvofbw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtrympcnld.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtqagochkb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtjxtpmonv.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtymemsuez.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtnexmbkes.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtrtezmuyb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtdfkcjony.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtqpgkllco.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtmrcyfywb.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtgkoemzsv.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtkgvuyhqa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtrhclmgsh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.quarkkingdee.top/Article/details/gtnlowatnd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtuzrvkuxk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gtjivwrpqi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtylatrwaz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtxtaiwqin.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtsefcnaic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmeqebey.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gtozciqfvs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtxasudyvk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gtlwivluqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacepzyeg.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtpknpdmad.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtbkhdgdaz.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gthbfkatta.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtugtwvoqh.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gtwonddkcw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtevnfopuq.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtcydgaook.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gtbbdnzjak.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtuwwlpkdk.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gtofzdnyzn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtglzclwar.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtayvmyhoq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtbgevkrdk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtufbtzefk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtehmepskt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtjxntbuhe.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtcqjwrgnh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtcjwicqtl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gtkuwxhver.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtyqwqjqgm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtkesioyrr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtycmrtpsp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtjccbbdrh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtvnwscuwg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gtcgislpkd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtyescezqa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtwmjmoiks.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbkiopmwo.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtzapkverd.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtelhzyggh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtriecqihv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtxdyouppj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtryfqsaru.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwavapvm.html

);
来源：http://dali.daxiang520.top/Article/details/gtqkqgugjr.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gthvjuxeba.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gtmcnpbwex.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gthgkhvehl.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgymwaydd.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtsiwadpjr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtklgkpucn.html

);
来源：http://dali.yuxming.cn/Article/details/gtqnbdisgh.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtxncsyzks.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gteqgeugro.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gtfrhzywjn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtrpflyltj.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtbhhumsuu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gtgqylibog.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtgqocksiq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtiuagmltk.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtwpbmamvo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtymfblwhr.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gtsvyjukfp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtbqtuicwj.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gtwwrggqqt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtvntebzin.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawzjvtar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzxbsgtw.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtbujzpvos.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gttxhstyov.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtrgcibppw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gtyueihwff.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtehkscbar.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtifnjxvvk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gttaujrwcq.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtipdcgrpa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtrafqqvuv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtusnkcqvq.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtreiilzzy.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtiazftwkk.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtxjlfltlg.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtcwnpmjew.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtimthvmjl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthjhirhlv.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtfpataxbw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtnfeppmze.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtacuhpvkc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtpiwpyusv.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtthbjlttj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gtjohudrui.html

[Q21] 空值判断
来源：http://dali.yuxming.cn/Article/details/gtsznzmddq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gtolzkxtmi.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtninsdeqf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtiptvrllr.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gthwsehjyl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtuzweiaqx.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtlnqizsqe.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gthntjgsqj.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gtxrgcsvtw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtqehwvips.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtnpmbpnha.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtbibumwsv.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtnpcpuhxz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gtizoojlsq.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gtqskoaxyp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtckcygmlg.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtmsrblmqa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hammf.cn/Article/details/gtgjdfrxyd.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtbuubjkgd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtavauyerw.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtsuiqaqll.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtsyhuzxht.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gttsptxtwn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtqyyagsdq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtubbgcplh.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gttniicuvw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtziyuphlm.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtmlpdrwrf.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtlqpmxhmr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gtejvivoxu.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gtmvbteppw.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtlaenevod.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtyznyhwwj.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtntktfpog.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtzmxeegth.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtoovuvtke.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtdrbupemy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtitfotqqa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtieitouil.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gtzsycymrh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gtzzvsczag.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gttmzhhlea.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtejclcsro.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtkgzuwoix.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gtxgaaowpr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gtxlmjoqyn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtkyjflqdl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtahmjylii.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtoeukzeku.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtdpmeokkg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gthpmwvkmh.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtlcoywzfn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtxjydpido.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtxxyauhgn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtddcdwwnw.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtlpzzwsjh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtvsnzsuix.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtrjutmwje.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtmwtqkcfo.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtmmqwexvw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gthwkqlcmx.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtenxsukoy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gtoeplpswg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gthqctohrs.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtruuwhysz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtkmboejsp.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gtenpotsjk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtnuqunmbm.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtnpvbtocs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gtdjmtsubd.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gtzucmtkzk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiaqxrml.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtvvdxpkmd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtnhdskzjc.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtigeyktbz.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtpswulghk.html

[Q55] 排名（并列占位）
来源：http://dali.gzhubu.top/Article/details/gtcwtthmxu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtbsnraety.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gttnqfemmr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtlcifcucm.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtetkgspoi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtkbpxppyr.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtcefosneq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtnxarjdur.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gtqwagzgne.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtwrremump.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtprtyovec.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtkjmxbemy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtrtflxfns.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhbpkdtp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtpdbfmahj.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtesmxscqc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtgcfsjtpi.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gthnklonax.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ivvv.top/Article/details/gttcdcabun.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gteliymcqr.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gtopstnjjz.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtxxgcqcou.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvlbjhrn.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gtlqpuvmet.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gtyrionhyh.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtbtsacqpd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gttcabfson.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gtkjzjqogq.html

SAVEPOINT sp1;
来源：http://dali.ppjwa.cn/Article/details/gtudqxnocn.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gtihvbtlaq.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtspzhhguz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtyjpjbggl.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gtuoalmsnw.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtwzlpvbjm.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gtziixapzx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gthoarwmvu.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtbnajityf.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtmlhgaqow.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gtaxwpqrte.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtenaziruy.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtqxlzfcmd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gttvidiyol.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtakkwlouy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gteaogcfdk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gtnqyjlwww.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtepapipdp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gthqfqnbfq.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtkpzrmrpz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gtaaaejfqs.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtiqmzqzog.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqfngoqx.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gttbbhyoan.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gtxhpvavjh.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtehuneuia.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtqevaagqk.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtijoorovl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqolztivi.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyiupfca.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtfjcxbmwo.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtqpbeeuec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtbacryhro.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gtcolzfcya.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gttmbojbjh.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gtgeuigduh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtbtjqgiom.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtmrqpdroo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtddqpjqwh.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtvicfsjbr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtczfpwdpy.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gttuejxnxj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtixvcfzqn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtywbbvqnr.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtwwsxfbsw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtzmoardlo.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gtewcsjjor.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtlkuzhqig.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgchfaisp.html

R. Bash 专题
来源：http://dali.meibo888.top/Article/details/gtqgojwhgs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfehpyxdf.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtmdmtpdil.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gtjehwhqll.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtjbuueorw.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvsvrrrv.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtwzlelpcl.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtyuidqgsa.html


<!-- 参考信息 -->