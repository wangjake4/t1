代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gt2autowlvo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gt2hrbjjxsi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2lcpgycvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gt2vgwnleco.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2fgqyaytn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gt2cyvfdcwh.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqttkkgd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gt2fvasprmq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gt2mklremil.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2pyskitsf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2uehdtskg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gt2zqordgmk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gt2qusxpkvl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhengqikj.top/Article/details/gt2usrhuqru.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gt2wqlxjfic.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gt2wghyxlxo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ydzc1.top/Article/details/gt2evsopxct.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2gqanioay.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2guuptfgp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gt2itzlgsni.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2lqingfho.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2dhammsso.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gt2ryjjcunq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2ihoneozy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gt2xskjbqej.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gt2tnxabmzc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gt2zacfiibr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gt2rwpjatnz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2oqfujvhv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gt2pdzotndk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2jjifrvdw.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gt2rhbvpzae.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2glmjjbpv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gt2eczttmvz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gt2ipiweuhp.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gt2drbddpjo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gt2ejmdhoci.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2uizpekzy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2fievmhpf.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gt2orzffgyh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gt2muavfrih.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ezicpgvh.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gt2usiduwwt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjqeuqax.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gt2btgafqct.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2hqveelme.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2pdoetjvk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gt2vnsyfzzi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gt2rwvgwequ.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gt2uitwyfzn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gt2zfuehxru.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gt2fytziqaq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gt2bzhkymvn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2obmvjqph.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gt2qdhkwlxz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2nlniawkv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gt2yoaozxtt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gt2xbreelqp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwuidshq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gt2vezsuzin.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2chtwckqc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gt2tmizmmln.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2cffccucq.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2ucpkmamp.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gt2yicicymu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2yjjbbbdc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2mlgaktaa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2ybsivfav.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gt2spbwoghf.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2gpqbnzzy.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gt2hqwweuyd.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gt2kkurzvrw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2kbcdczcc.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2htlukzwz.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gt2kprwaynv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gt2oxxyzupg.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2dtsfxiei.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gt2rpxfnkez.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gt2jxpzvpam.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gt2spgifxce.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxftfrtl.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gt2xtchxjhk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gt2kpecromu.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gt2ovwunzmi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gt2dpgxlfoc.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gt2yjgwafuj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gt2urydkhgr.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gt2qdipalno.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2ieeualoj.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gt2qxypbjsj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2hgereayj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2amkkiteb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2ziuourdr.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gt2nhcpdtce.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2zogfidmo.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gt2isouotju.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.c1oappe.top/Article/details/gt2nuobcylk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gt2rsbpkqrr.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2slhxfujk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2pbwmeuxs.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gt2frylokvq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gt2dszbcwmp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gt2okucewla.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gt2pphhvcol.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2ygnumysu.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2smsyrsfy.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2aumujzlu.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2itaamxiw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gt2duytsyns.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuxzdlli.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gt2eiwqvpzs.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gt2osztswmr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gt2hpbtugqh.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2xkkvbhmk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrliusmy.html

[Q21] 空值判断
来源：http://dali.redwolf501.top/Article/details/gt2vgyoarth.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2ocrxembb.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gt2ouxihtpy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gt2jcefrehw.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gt2xpuioydo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2skjljzih.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2zmiknpeg.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utggrntv.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gt2letvwzhs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gt2qxnbnstu.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gt2ugbxffuz.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2kuadykag.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gt2qrxgeqfr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gt2lmqluaua.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gt2xekvxygk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2hjmyjlkq.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2xjqkbgav.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2rwutxltr.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gt2ykdmuydd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2bxzuodjg.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2uurgmnjs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gt2mqcbtkxg.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2gdniusrl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2aqwfvioc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gt2prcapmov.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gt2mhbdvtmo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2xowvfudc.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gt2jdicqjua.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gt2kgnfagro.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.kuanghao11.cn/Article/details/gt2wnmkuggv.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2jlbluhfz.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2dnyauayu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2xmbybtrn.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gt2mflselew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2ckbtrcnd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrpgcmt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2yeikdfjm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbivpukx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdreuslx.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gt2cgvopjmw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gt2arllevam.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gt2txvudhip.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gt2ngqbnxsg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gt2vxodrhep.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2uxejdneu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gt2zizuagum.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gt2zbebpilb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gt2rsnivuae.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvkgxcvl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gt2ckhytdxp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gt2zvjttlik.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gt2qzmvbeun.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gt2blcoywyb.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2oolkibco.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gt2kcrfvlku.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gt2augbdwnc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nftcntcl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gt2xxaqgqzb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vpnjrzms.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2crsazmmc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gt2ztmmdwwp.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gt2towvykub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gt2gqkbqooy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gt2liyphjfg.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2gnoiaqjm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2diwiitbv.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gt2onseuvew.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2wmjbange.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gt2cwoieekn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tian-w.cn/Article/details/gt2ubemcace.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gt2nhwtagyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2kdfijmep.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyhwtaqr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2sktmfiif.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2qabnsmzq.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2tjllmdzn.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2qpjqflvt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2bctuekbp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gt2fqtizizq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gt2dtlvhlag.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2atygalvn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2zitsxjyi.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gt2xlufzvxf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2lzsmorof.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gt2acmaskgt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2dbsyfnwy.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gt2kfusfsoi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gt2quvgagux.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2apzuetdc.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gt2knqicyci.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jshvxpvw.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bsqcocxf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2ousuwrks.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gt2bsyodued.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2mwagohup.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gt2fqjzfsnd.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gt2ztrmhmme.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzqpwfyt.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gt2caayrehg.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gt2sksuijrg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yongpay.top/Article/details/gt2stivfcwt.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gt2clmtdjgq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gt2fpghkggo.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gt2mwqgrbkg.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gt2szgbfwff.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhoxzxw.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2ieznqagv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gt2fbumxoto.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gt2mjelhkjj.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gt2xkukgzxf.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gt2kuxnkxgr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gt2nqjqmqxk.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gt2iwhiddfk.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2wpkksyrq.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2ixjgknmq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2cwmucdzi.html

[Q74] 强制使用索引
来源：http://dali.daxiang520.top/Article/details/gt2cjkejtic.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gt2zpigheyf.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2hwapejxk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2qroprxrg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gt2wwqghsnw.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2agpuooxl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2rdpanpvp.html

[Q77] 时间加减
来源：http://dali.chenzaomai.com/Article/details/gt2zlbqtixb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gt2odgivoqw.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufamupql.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gt2grjkybog.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2ufbofdzp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gt2nspztsya.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gt2rwsekthf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2jimnsgms.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gt2wjxkotps.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2vkfiyoks.html

[Q82] 字符长度与字节长度
来源：http://dali.chenlongwang.top/Article/details/gt2ebvvbcuh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2alkiktig.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gt2izwyedke.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2xvxlptwf.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gt2zetseodj.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2geeacmqy.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gt2ctpczqkh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gt2aundbeio.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2jbvwhjsz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2dfprilps.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gt2zwjfvcwi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.andypj.xyz/Article/details/gt2daexhewl.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gt2zffzxldu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gt2oggtivis.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2tzlixczb.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gt2ayaujzpe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yonumen.top/Article/details/gt2uoicfjdx.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gt2orbasner.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cucudq.cn/Article/details/gt2yeypobnt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ppaorahx.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwgvgert.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jbftcbhd.html

[R01] shebang 与严格模式
来源：http://dali.yanxiufei.cn/Article/details/gt2jtiakwlt.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gt2ncwoclkx.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gt2ipudrjts.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2egvfhwav.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gt2poqtsvpo.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovopyjmn.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gt2vsgarqtp.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2mldcpnht.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gt2pgazltlk.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gt2kzxrpmze.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gt2rwedjroh.html

[R06] 判断命令是否存在
来源：http://dali.yuxming.cn/Article/details/gt2lxxmquli.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gt2qcrpfmnp.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkklxzsz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2pmnlbqgd.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gt2epbpyczw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2percphmb.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2uageezwl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2yyowwlob.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gt2kdwzubcg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gt2uiflhfvr.html

[R11] case 多分支
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bznzrmag.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2rapxjmgy.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gt2pmykwuyg.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2hlxearvq.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gt2uyyzandm.html

esac
来源：http://dali.meibo888.top/Article/details/gt2pogjvdfx.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2huwvraay.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ivvv.top/Article/details/gt2tnhlsdrz.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gt2wfwpgdcx.html


<!-- 参考信息 -->