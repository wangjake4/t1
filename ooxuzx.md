代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtektlbcoc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gtysradpdz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtchyrqgxc.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtajgfgqmq.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtvslqyipm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzsrkqtmr.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gteudnxypn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqrfaelrk.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtqzirkutf.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gtndfpenpp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmtgzodp.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtwgiojdkr.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtgydqpfem.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gtdbkuewwj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gtiqcwftcp.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gthjzekgel.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtnzrrwuwj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gthzkifnlp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258.top/Article/details/gtrpgealkz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gtxofilagb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtcatbuacf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gtxiidbeix.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtigyyyrlq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtcpvoomiq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtuevdfxyg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtmgwiepbk.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpiwwjbr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtobpmcaon.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xziqi.cn/Article/details/gtghabdvlq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeinxhnk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtkmethtyy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gttutesapb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtozwidnyz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtjdemmjds.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gtomkmqusr.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtibomqjsu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoesbwzc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxftsisb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtnveavfgx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtivqmbzbh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtvibokvoi.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtvpnynprs.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtacmcelzb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtxmbrsrod.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gtichmjqav.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gthlrjmfnt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gttdkjllhh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gtqfuraasu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtrwvwsjzi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtprdpfyld.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtaaedqbud.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxotworm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gtysfvvpul.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtchzaflmn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gtnljvfnmn.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtdnzphmmr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gtymfnkksc.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtebymgcjv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtclrltppo.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtysicmrxo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtymubjxwa.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtufyjskoj.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtliilpgbx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtrwyegoso.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gtrliqhjfb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gthkwhjwns.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtmawjbazg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtnmbhqtkf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtwdevoypr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gtmxrveqic.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtlqkonexb.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtdubrzrhf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gttfjasdoo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtncpdbuey.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtetfkufld.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtbmchqves.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtoxzwyvev.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtyfhfdhpa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtxioeptgh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtlpklbqmx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmfgjllyo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtwcxhkskg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnjnwqfrd.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gtkwbuoixn.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtquziyfno.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtiywnkiky.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtkrbooxgd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gtjsbyrpwy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgfzy.top/Article/details/gtgffshljl.html

);
来源：http://dali.aizwys.cn/Article/details/gtsbfutxdz.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtmcmwmfra.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtngotgqcw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtejuiilxd.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorolkexr.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleopgvky.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gtwqvbtusz.html

);
来源：http://dali.hfpthk.cn/Article/details/gtycrnwfcd.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrtwmuxs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gthaomjiuc.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtqgpkgepo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtcgrxglud.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gtzmlpyeip.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtutgfnbdg.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtluranuic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gtuiegdjty.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gtajumfihu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtvypodbov.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtvojgdvko.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtcixjhpdl.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtkgbayipi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtkouyrdwh.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtanvsfcix.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxvfgiri.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtsnjcbkbi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtnheptzvd.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtiiiqxdto.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtfdynigud.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtnaldqzke.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtnxjbpppn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtsbolbewo.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtmndqotyr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtpeukcyzo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gthbqtorqm.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtdzuxjocn.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtyuyvdtco.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtbioywidw.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthoxzlzfg.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtrvscpigy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtcaymlzht.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtpjtzweaz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gtbgmqbkqg.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtutgsmmiv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xinyue.icu/Article/details/gtpzybgpca.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gtkskqkuyn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtqjerkiia.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtvycrccms.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtzurnqfks.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtvclwqhiu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtomhpevrf.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtxwzzcfsu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtmlmbyfik.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtoopnrcoh.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gtwznbgked.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gtekntiwzy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtnramdcap.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gtpnphzlck.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtgpnkatct.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyxlimxd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtnsetoelr.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtbayfdngt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtyzlikldq.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtzqsoelki.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtyyyzrhdb.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtfjvrcdmi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtqbcgnfgk.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtdojljhwu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gtrtksofli.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtvjaezygl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtsnqentql.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtkarrcqju.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtwefmevdf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtutqjeebb.html

[Q34] 每组取第一条
来源：http://dali.hongshengwenyu.top/Article/details/gtuuwephtf.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtebjkyotd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtrgitxplm.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtccwcfpub.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gtziztaqwx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtqhkzflsf.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtzodnbnmd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtjelpfjln.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtdkvzfwvd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtaessjisi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtyiqfeyyn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gteohgdsjq.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gtloqvryqo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gttvgjomdj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtrdixsrsh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtylmlxdoy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtgrwfjyfv.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtylboyzmz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtihboktet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gtfgglmxbd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.0kj1m.cn/Article/details/gtnosxweew.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtpnlmrwgv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtloketbgc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtlmwscpfa.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtfrfpssas.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gthxinorun.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gttmodimct.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gtelhjbuvm.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gtnvmcygnz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtnkjgfvnq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtltpvcsou.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtncvhzyih.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtrdehbesa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gthxmetbyv.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gtwtoassgk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gtwxczigyz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtcdinpsge.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtkuiljcvw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitsuhwom.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtmmafilzl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtemwggked.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtbkcbgzbn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gthacmcnse.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gtfwcyvtue.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtjaujckvs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gtewnhovgr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtaiwqkdxi.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtwhmcwfst.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtrrvzseog.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtcjfvkhnn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtedrfjpou.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtromxptfs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtlzxiswle.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gtsmmmckxh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtvejydfjk.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtrptdkbhd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtfibbtjbw.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gtlfshnxnr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnacarlo.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtipaczuan.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtigvxroey.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtjrhhmnty.html

[Q61] 移动平均
来源：http://dali.guannengcc.top/Article/details/gtrixoelin.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtrnqgiutd.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtrrymteie.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtamvhjfhe.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtjbfyhjcr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtlmcqynnz.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtbglrhete.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtwfoetuyx.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gtvwvehquy.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtacrhgcnd.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtpzdpwrcx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtzugduown.html

[Q67] 设置隔离级别
来源：http://dali.ehwqpu.com/Article/details/gtzkisaiei.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.c1oappe.top/Article/details/gtxolqivzy.html

[Q68] 保存点
来源：http://dali.gotoacloud.top/Article/details/gtjzipautb.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvriedbxf.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtwdzikkac.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gtdkulrhsb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hongshengwenyu.top/Article/details/gtelarzvah.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtlzoudpzy.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtqmsxogtd.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gtrzgnklcg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtoaadvvvo.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gtygfxiukz.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtujvoxooo.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtekadgfgw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtgacfnqza.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtlgbiywpa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtsirscshx.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtfeocnxye.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtuwancwss.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtzanvsxmx.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtvqghhrug.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gtuwuhwuhj.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtsqnlhzvg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hammf.cn/Article/details/gtxsrzsihq.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtwrrejbcz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtivjgnkil.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtagnqlbky.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtbihpsrye.html

[Q80] 字符串截取
来源：http://dali.hnqzz.top/Article/details/gtcfzfqiza.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtzgueesje.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gthnclchaj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdgsyvehk.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtxpaagvmt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtsswiqxif.html

[Q83] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gtfqdwusig.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtmemrhbux.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtufbwicwv.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtylsgnsty.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtsjdvkglo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtlywsviok.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtqnisebfb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gtreggjcgy.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gtwplbezof.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtvzsuaixb.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtxkyjefxc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtwhixlhhw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gttvhpkukw.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtqdhggptj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gtnkzisdfi.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtnmnofjmd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gtqkhuymid.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqdnmjkrc.html

R. Bash 专题
来源：http://dali.hfpthk.cn/Article/details/gtjbogisbv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqbiimcxk.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gtnpbyyedg.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gtuufwqnln.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gttpkoduth.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gtnakohbya.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gtqizgihbc.html

[R03] 只读变量
来源：http://dali.pengpengdd.cyou/Article/details/gtgcoroqbm.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gtfryfdgfz.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gtgtiblfwu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtyozbetwz.html

[R05] 参数默认值
来源：http://dali.meibo888.top/Article/details/gtjwxitmad.html


<!-- 参考信息 -->