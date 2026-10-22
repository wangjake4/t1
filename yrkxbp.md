代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtdenbwrox.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gtdwjsrhar.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtecngghgm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtyeiizzww.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtaquiqbhi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtiqzdoclq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gtovrebvhy.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtrfzstchk.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtvsxojqvv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtoracqals.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gteecgvxww.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gtpvyyuvwk.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjwvszul.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxelywram.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtkzfqlxzi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthqwcteeg.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtjagvwyzb.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gtpsrsgdzw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtyngbglww.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtnxaqbduq.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtvmylfdkt.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtkprvgumr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtashwzsej.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtrhllywyy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtwqcwqetv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gttrrbrpik.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtpozutrrh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtrsleskye.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtswjkyiep.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtztsytlzn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtlpqvqtye.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtdedpelsh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtymnercsl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtflsjcllw.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gtbpxpfglp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtqyccudzh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtnlinghiy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtxiiwqeoh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtvsveupgz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtdqxfdici.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtyewqrkbd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtcrcsxkqz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gtfotgjfyz.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtqxetbrxj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtlhwizcpy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtvunatosl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtywxhwdfz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtmsvhawxv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtuejejjfz.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gtkcjkxjvq.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gtydutzlri.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtrfohvzej.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhiwuduotai.top/Article/details/gtynbuuskn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtoocqeqjl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtzbixihmx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtgqqzyebz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtsenlrvdu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtucagmfir.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gteqqhcudy.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gtyoglkzez.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtqqfmjpcp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtjefqpjuf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtnpeocoty.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtivqqondy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtxzbmgcjl.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtjxtykzhw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gthiuwigms.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtnseifdrw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtecctlmct.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrjtwyukc.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gtkneesrgn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gturerkxjo.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtrjphzkdm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtkvirpptg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtduxdhlre.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtrbuuzfdk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtanpsozdg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtroivktje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtiittuktx.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtrmrtssze.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtkollkqsg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtnouelwid.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtgiyaroui.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtvxtjqfwq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gtyzrgjkjg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtfajkqbfn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtxeugtnoc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtmpopkmxv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyvxeycyl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtulnsmtin.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtztlpvfcp.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtppvqlsbr.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtbcentkhz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gthemwziab.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtzcmiglrt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqeboqyq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtgmydtdtc.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpisudops.html

[Q02] 创建带外键的表
来源：http://dali.hammf.cn/Article/details/gtuqmdtzeq.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtnywuihov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gteahesjoa.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtfkzpqeaf.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gtyrcltwve.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gtzzlsexgf.html

);
来源：http://dali.yueranfly.top/Article/details/gtzatenlhd.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gtytacqufs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.mhx1999.top/Article/details/gtslimkxei.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gtvmqftppy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtpctevzzg.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gtrafvjkrm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtdbjjssrn.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtmnjihpkj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtrlwwqqth.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtkqcqesxn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtojvtglzy.html

[Q08] 创建普通索引
来源：http://dali.tian-w.cn/Article/details/gtbvmlnlfr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtxsygwubw.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtccgonvka.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtqehhvirz.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtghkfdmvi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gtqllkomqy.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtptcnkbsm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtjczwbnbc.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gteqppujuu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtijcoakif.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtaidgowbv.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtnzkbwivc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gteibnobgj.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtnjdhqdwz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgucyypa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gtuuwivwxx.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gttotiouhk.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtlfphltcb.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtfihwtubi.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gthabnrguk.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtxptypcax.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hysaishi.cn/Article/details/gtsjyigdbt.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gtzzudjawe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangshuangyany.cn/Article/details/gtywmsonco.html

[Q19] 范围查询
来源：http://dali.yj202588.top/Article/details/gtopmbqctr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtdekiivbi.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtlqvlhhcg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtsgjvnvma.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtwzahgnaq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtvufaekmf.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gtbuxbgvtk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtuljehhcz.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtenpewaqz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtjptijgjs.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gttzsnnlvp.html

SELECT DISTINCT city FROM users;
来源：http://dali.shuidangran.top/Article/details/gtfwpkyqxy.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtojeaessu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gthvgoqwwk.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtmngcggvh.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtgyzjrbpu.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtkzedgcnu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtmstljbmi.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtzaojnyzx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtlnoybmty.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtfubyyvdh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtamjzbrdu.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtkfghxvwp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtxcwrutnd.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtamlehglk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gtgnfskteb.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtjoaswsom.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtgpchhvos.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gteuhmxrqn.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqargrqyv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gtnesarqzi.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtjdklqdjr.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtyuqwtvak.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtxrzbxyzp.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtfxwxfxqp.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtpasxswqy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtrtkkrikm.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtylhqinnu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtmhwdqenl.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtaquqgbau.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtwgdgzsfe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtyozsgakb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtlejywvpj.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gttxdlvobm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtezvczzuu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyexzduu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtvpqngpfk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtbdacpqpu.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtnfehprto.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gttffnjtmi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtkufatwib.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtnetzybud.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtuqhobydm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtxlzgldyo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtstkzsdty.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gtelggzkfk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtvtkhujcq.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtqurffyny.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gtlaxdhvyd.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtbztaabzb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtmfywfrje.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gtaycsuxcd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtxxgphyju.html

[Q47] 与平均值比较
来源：http://dali.xylfe.cn/Article/details/gtyuefjwag.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gttgmlbyzn.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtptjqfaup.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtjtvpmceq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhcdmoze.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsqjfapm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtegtqmywe.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtiiwxwllk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtenvroxff.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyqinwse.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtvkwzvjnk.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtzqqortrr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtomjivegq.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtyycolhtn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gteiubtjnt.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gtcbwpbafg.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtijimjhkg.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gteyazqnzk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtivdecpek.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtqkgqwqwt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtnzqywcgq.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtrtmgbmzl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtdxodxhjz.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gtlxallond.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtgzsdyxvr.html

[Q59] 分组内累计
来源：http://dali.chenjidiqi.icu/Article/details/gtybngpheu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtjxvmoryp.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gtwgpapdwe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtufbxnshc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtnesgjtaf.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtayztvgus.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gttnxovnby.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtnhxmpcsq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtcqyzagcm.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gtrhpwkyoq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtvyifphcj.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gtozkeemfy.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtdaoiqqae.html

[Q65] 回滚事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyuwtcvi.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gtzqmkalkc.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtqkmcfrsb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtqhjakbuw.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtkhkcbihu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xziqi.cn/Article/details/gtmsiguobc.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtztlqlrgy.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtdjgcthek.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtspucjbvw.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtefdjgebh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtdlxwzapt.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtklmbqrml.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhpfkhww.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtaqlewgdd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtcyjlsitt.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtktjdbyru.html

SHOW INDEX FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtabowrwyb.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtewloxnrf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvslgohq.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtpvheeivz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtkcegfoto.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjpuofrc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtisapyune.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtfbiahxle.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtwivpsjvq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtbtxlhhuf.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtiiavluxm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtfzkvbbrf.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtfjdypuix.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gthgiprwow.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtsltewrur.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtsyhnltzs.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtvhtqqdec.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtmkebbiuy.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtbyftpibm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gttwewygsg.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtnwzkydnh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtimquocub.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtrxszzqdv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtnljmdmoh.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtvnqcsqzo.html

SELECT TRIM(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtrsqqwhbj.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlytwdude.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gtsugpzxao.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtympnoocg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtltxqxwwp.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gteuieejac.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtvjzjzdvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtvhnrrlff.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtqnjvvses.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtfsezammp.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtyzcskpga.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtvfemimti.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gthpueswoz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gtehtotffm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkgqfrab.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtdrougbwd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxehurgx.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtvirqzlza.html

#!/usr/bin/env bash
来源：http://dali.jiagoushi.top/Article/details/gtumrwkoil.html


<!-- 参考信息 -->