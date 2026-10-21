代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gttpyiytep.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtajptospt.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtilvumibw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gtvteetjzp.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtxtibugyz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtjrkumomo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtarzoeaoc.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtvzplmgub.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gthltygsnv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtqduqxtsi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtuukcdbkn.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtdhwrxqym.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtnjndvbmy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjlwpjfjf.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gtexmpkjrv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlnxgaqnv.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtitjdnkms.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gthuculdok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtkpcholfz.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtrskgicqp.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtitkvkqet.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtwejjuqfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtfrjglmbr.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtobnrkfhk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtewfzmhsq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtjgkarkih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtepqaqhov.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtepzdvszv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gtxrvmzvil.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtcqniplib.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gtjsufedie.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtmpaahwxw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtopdjkcfr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gtjjrbvdbh.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gtwukqiyjg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtazunmmxg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtbehcrdty.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtmmxowrdh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtzclbkvmm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gtmghbkrqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gtrjzxmgzp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtudilgulm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtjnodmkmj.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtnyaavzhf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gttytojlmn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtsjqrnfss.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdogpyfvf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtbznutmhb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtrdzyjjcs.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gtlrtjuzqb.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtqzvjndzg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtquampzgu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkqqpfef.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtmwvtqgbo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gtdwgobxry.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtxjdvfgkj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtdymjrlsh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtvstntkor.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gtdsmetdxt.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtqvmnzwyo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtqlbvaoxk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daxiang520.top/Article/details/gtaxmmnwqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtehbxiqwq.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxhudfmqz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtvjfhecuo.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gtcxxfgdud.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgrwcmmvc.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtxadzkofw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gttbzduszb.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtplrogksg.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gtgzltchdg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtwmqqaaqc.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtrcmixdom.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtpiqfqdgo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtnszfdzcz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtjjllvksz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtpycppfvr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtcmdyxens.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlcqkytd.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gtauryiyrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtxkvniaac.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtvfhhshcg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtizzdtxpl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbxgipps.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtuzlnfvrr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtxpdacdrz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtzxrdcfsd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtkbeyuwun.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrpxpibgy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gtfeurmwsr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtggdrmngu.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gtrydpoarr.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gteeztkelb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtyjneoaec.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtnyyeodkr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtycqsqvgv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtyrdepfcz.html

);
来源：http://dali.hfpthk.cn/Article/details/gtdqkycrsg.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtjpkxowmu.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtbehurddp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtlqnlzyrl.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtafrggact.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiowqsgq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtavznnpzo.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtmzlqkqjj.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtnehszxxg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtyzyjedqt.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtdldzhqzd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtrbllrwdw.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtzjzrrsyo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtiuphixiv.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtlbuywemc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtxbggwzpk.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtazdzvufe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtcgykhmrg.html

[Q08] 创建普通索引
来源：http://dali.zdqjudy.top/Article/details/gtwoqfocdn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtdtdffoxu.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtqnyyzxfd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtquhlfcpf.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtwfpvmwxb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gtygwjmdxx.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtmorakmgn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtregnlqvr.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gtqzhtklpm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtjkhbhbqg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtzvjadlcm.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gttcarfrhf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.smart0.xyz/Article/details/gtnroamygv.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gttbektbfj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtjwdjrlsu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtcdluegqg.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gttbhcryfr.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtuszirmvp.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoxtvcbm.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtlbpsxwhz.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gtnohyktky.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gtgbfuhswf.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtiqbhlphy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtunomrwwr.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtivqojbgt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj202588.top/Article/details/gtjzordyfa.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gttnfokmkr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gtntugylbc.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtqhalqemv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtistodend.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtkxbiuvas.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtamwhhkzt.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gttdshgxzz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtelxoxdky.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gtzexzngcd.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjrdjxqbg.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtpntffkqa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtocaapyxi.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtmyycsyhl.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtxpahemaf.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtlnwkuuup.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtsqefrewi.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtpxebyprs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtjorxkcrb.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtsohonzrd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtrneatzak.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gtwzhjnxes.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtzagepkov.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gtslfzvzcp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtocggkbtp.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtnqkniryp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyyvftxp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtzfxtusdj.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gtsbmntohl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gtcxbrnuif.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gtfklksogl.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtozdbjisy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtmmpfjdaw.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtsyrbynjm.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gttqjwvobw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtksrgllnk.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtqzkgymwo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtbfuifkvb.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtsffzzeev.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzztadow.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gtjvrxnmbx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtozbkxozf.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gtgovvvivo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtohryjtxo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtmrncarqn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtytqisylu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtobgsssbl.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gtizilftaj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtcnkmhhjg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtakvqlhtq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtxbonfvcp.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtpufymrba.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtqtvgnuhc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtaqjlaepr.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtgtzbcxvn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gtpolmtlzw.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtnsnvwzes.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtwecmeony.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gthnllrphd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtqjjdciky.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gtmxvkeptm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtkbhbzulp.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtlsscjrpl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gttwcsnbgi.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gttolozlxc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtlnlnwqhm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtemonqtib.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtqjplyaxl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gteedswger.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gtdrcxpsfa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtilmdikgu.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtrpgdecmm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gtblvkuzrr.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmfvyorg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gtskoynfgt.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtgmxejqoc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtzjnzyoei.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gtsnxnipnt.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gtzohvtlwf.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtrypvrsef.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gtwmolgkeb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtpfnfahcm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtjgtjitui.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gtvejxspdm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtpchchdnf.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gticmoqvgd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtznvppwqx.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gtaojtnjxs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtgjbpkxhh.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gtpjlimkxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtqwllegzj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtypcfjsyc.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtkodkdjmz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtuqgejwhs.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtasikuuti.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtzfkfeins.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtzxrehtvm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gtvqdfuxiz.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtqwvlycdb.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtexksumqj.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtogbmsyva.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtzznnxebo.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gtdmmphoat.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gtqlrnwuqh.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtvuhpadwq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtxnskiwfv.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gtpowovqha.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtiwjhwdmi.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtosrbmmfs.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimxrdvdo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtnrdakewd.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtrkohxreh.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gtculvtgrv.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtjzcodnbg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtfmsazpef.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtoezraisg.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gtpldwzgdv.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtpxgbepbl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtcrwazikp.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaercoxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtnkvdbmzk.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtkvbvhcim.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtuxaqlrsd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gtxlvvqnor.html

[Q76] 按天统计
来源：http://dali.redwolf501.top/Article/details/gttbryeobx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtvbpvinyy.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtusgpmlyw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtlykjztut.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gtttwnrnse.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtzgaflnsl.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtdrjvmied.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtsptbrhyb.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtbofqnyjr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtbujdhtyj.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gtcamxgczw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthhuyehvo.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtkdmjqzbg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmnygumvq.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtipcminuq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtapcthoti.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtcojrozwy.html

SELECT TRIM(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtqbsghjao.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtgvitnqbj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gtzvtkcydf.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtzcpacamx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtaiemadzd.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtcqdiuvos.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gthbbufpxx.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtjixqlqxg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtxcynjwgr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdismzpz.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtdnfjkfrd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gtkuafdhfe.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtmpassavt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtxpcecznp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtppskdtba.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gtqctrzatj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnffkjrzt.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtaxycsqqa.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtvjegqfyz.html


<!-- 参考信息 -->