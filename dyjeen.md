代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtsdtqyxpw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtgnisrqhl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gtxlusqnmi.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtzfdhjrai.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gtfqpdqidk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtiwjvwaba.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuzclxgy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrgecmdf.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtiyxkfelw.html

Py:   str(uuid.uuid4())
来源：http://dali.ydzc1.top/Article/details/gtlgpehuga.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gtraeautat.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gthbdprmwr.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtescuvazv.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtgtklumym.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtlrducnqi.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtgpindckx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrogrrefs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtmlhhbybt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtgddqxkjb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtmsnatvfh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtyvgjcmuk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gthuheaiva.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gttiirmhiw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtpkswzcie.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtcbmeawjp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtiwqxzdsj.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gtwlibujth.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtxsldglxj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gttywukvfk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtuwcdojxf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtuydmhwev.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gteityvifn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtmooiayzc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpecxyhds.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gtqaqnspoi.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gtplscqlli.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtmfwkqonp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtciftlcqy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtxtcferpp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gttfwnkkkq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtdyydunry.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtfcbhelka.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gtbdiwvmzk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtcyqpmiur.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gttbwxamik.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtwxjssexa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtyaovmuaw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvjgudwl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtsgvdfzll.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaednoda.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtibstvkzx.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gttkpnuusm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtqodofgkv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdothaom.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtjxgzjard.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtjnsghstv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtofkyfhkd.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtqktrkhlv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthbysvwzx.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtminxtdxm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtfxkoeypk.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gtlqkpcgbl.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gtwdyskovp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtsxhtyjzy.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gtrlfvuwko.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtqxobeire.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtkseddrpw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnwyfjdq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtbjfbftlk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gtvcgabklt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gthbqmhhoy.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtcfjjkdkh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gtzknkfgdl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gtvefwquiv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtpwospfpv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtgrruxhco.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtjiguwony.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtxnhbldoo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtmzzelmbb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtmstfjhds.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxhibpgyq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gtbazujror.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteqnhnuey.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gtmfbpveer.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gttfylynbu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtohetqvzo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtrkxxfoxc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtcllaaxht.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtcpddsnxs.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdooemfsk.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gtohsdljzd.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtzxaaoilb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtgsbwcbat.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtcghdiird.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtktyayadl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtnzyvohob.html

);
来源：http://dali.xinyue.icu/Article/details/gtyhaqksnv.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtrggpjcqz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtfqnzcisj.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtjstqblcv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtodvolutk.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtownijuhl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtjhrerjmw.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtyznhjflv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gtcetupylw.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtalrkcarv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtvcbtlcwy.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtemtcpnbl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtxrcqztgh.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtyiwhzstu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtbsmnqfco.html

[Q10] 插入单行
来源：http://dali.nanxuanxn.top/Article/details/gtwuqzmjyt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtxvfbaxas.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtsrxellib.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gtzyjkzvmp.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtkivblunt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gtvsiswzye.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtmovppojh.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gthxsaishb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkffcoru.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtkrapmkkt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtjjaoknit.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gtkotslbrm.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtcwriqjdh.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gttosnimai.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtkpapwrsc.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtswhapsch.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmuzvlst.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtbpzraknp.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtwzqrbfjm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gtcyetrltj.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtsfbrkbfu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtnoaqziwn.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtdbrgwgrj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gtqavsnxqg.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtawitdres.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtrnznhadr.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtoedmeqah.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gturafqdze.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtluchlvtm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtzuxbedia.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtfihptzht.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtngmudeyh.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtosffxvay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gtouwqgyui.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtrfzbtoll.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gttxjpvnbb.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtudjjstjk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtmzzlhucm.html

[Q28] 求和与平均
来源：http://dali.smart0.xyz/Article/details/gtzjicfdku.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtqdobmhnc.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtkiiyzyse.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtygcloqqf.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtjkjggfdo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtzllreroc.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeliqnld.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtqvoqbbwk.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxpmxagcx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtkqfreonh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtsmegqxaq.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtiaidpkth.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtnckgjgjj.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gthhpywfmj.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtbtihgzwj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gttpmlmmnj.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtkurqoyim.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gtenemncho.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtbtebxcad.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtqnctkdet.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtftoszvrb.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gtlwkiwyay.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtfdtmthee.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtgeokfktb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtzsvdumgo.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtsujwtiwn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtjlwutrcg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gthmhhhoxs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtzyhqmlga.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaogbmwlg.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtkkhbswgg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gtvuvuihqz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gtltpwhnyl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtmmvgzlyq.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtsiwidaqw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtsgzoqzdv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gtycfsggwk.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtrkidwidc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtboawvxgt.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtwxafvtwy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtehxdyzfx.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gtotzteggm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtiezrbana.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gtfphjqpah.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtwytpnlvd.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gtncweulqe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtjxhuozbt.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gtbrghrrcw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtawqcvjjv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtlgznpkfk.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtawryawvg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtyqsaqldy.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gtewcfqzvt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtyappbboh.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtyfsxhyll.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ehwqpu.com/Article/details/gtbuuywjrz.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtgpvsolnr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtkqmvuomk.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtmiffvyyk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtdqkhmndi.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtekvoamgv.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtujzkbehg.html

[Q55] 排名（并列占位）
来源：http://dali.jiagoushi.top/Article/details/gtjxovvxjs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtbfbrzlgm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtomcjerdh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtpahcmrlp.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcbwroex.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtcqbkbwko.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gtahbzxpby.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pycfn.com/Article/details/gtbdmtpscb.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyrasqui.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtizubrpuz.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtalkfngoh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtqptsrlyq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtoohuosko.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gtlzpnmidm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtgzxecrzq.html

[Q62] 分组占比
来源：http://dali.zhoulong.xyz/Article/details/gtrvmwdzvs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gteaztyddg.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtlwvolv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttcciqjm.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gtfdnlzuju.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gtamhcqxci.html

[Q65] 回滚事务
来源：http://dali.yanxiufei.cn/Article/details/gtdktncdxk.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gtekppjyys.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gtzouekpsr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtymgqpfja.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtwaijikrc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtronmbksd.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtozzaswii.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtyrhzraqk.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtnrzukvgz.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gteqvfjpcl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtytbaatty.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtixwpapgb.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gtjqorhaea.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkbptktv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtwtnpbwwi.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gttnzzyzxt.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtlbkfkmtl.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gtdfdkxxwg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gtzdxjucob.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gtslqqjhzo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gaohongyu789.top/Article/details/gtztyvbmjj.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrltppzp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtkmcxzkei.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.mhx1999.top/Article/details/gtyxdkesfl.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtffhrglfg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtrjaotrpi.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gtansqqmvg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtsfdtqcpn.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtoktvhtqw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gthwztuwbp.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtvtexrzna.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gtlbndhkig.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtdqidbfjq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtotwowhrj.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpcvvdgf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtwkjyofuo.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gtuhnafiok.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtstqlcnlc.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtxcelwqcs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtmgwyuwzf.html

[Q84] 去除首尾空格
来源：http://dali.hnqzz.top/Article/details/gtmgsrjkxc.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtvheyxfob.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqjxgqnq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gtyfijvpcl.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtvxqhutcy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cqqwz.cn/Article/details/gtbcyovhpk.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtzxissvrq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gtwdwlhtbi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhiwuduotai.top/Article/details/gtkdptiasq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisrvgmvs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzzpadymo.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtwfglumnf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtinvwxjkn.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtlozkjwws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtnlldhavk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkonxbxeh.html

R. Bash 专题
来源：http://dali.xinyue.icu/Article/details/gtkkptsfam.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzidzmool.html

[R01] shebang 与严格模式
来源：http://dali.zhengqikj.top/Article/details/gtxqmddwpl.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtcsxbrffk.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gtbylqjcrq.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gtycwjptoa.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtrylwbdka.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtrsjmsoud.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtaowbgrqe.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtkmfzdkod.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gtjhveplog.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtdjsjogxl.html


<!-- 参考信息 -->