代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2acjeqsrf.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gt2ctrodmxw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gt2encinwgi.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gt2brskkwmq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gt2qcyqxkoz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2pwazopfv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gt2zedcxiik.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gt2fzdqwxcw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gt2fxwkysnm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gt2jcwwgwti.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2gjsavheu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gt2mxbgxort.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2jprmycst.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gt2khsukadc.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2sstlepgs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gt2egqypsfq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gt2cvlcvwcu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2jcatxszp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gt2fqwtqakq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gt2ybvkazwc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gt2supmbduc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gt2wscqfjlf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gt2wldlhoyw.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2himvjksg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2nckhfuph.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2otixecux.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gt2byqazrmk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gt2eqyodiky.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eysrkgbq.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gt2xnqbcqta.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gt2gowggrrb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2fegolcmq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gt2nzdgidsm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnpkmhhb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gt2jvdxzluv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gt2mqgoiupn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gt2izrdzfwu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxwxeeko.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyavfuq.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gt2hamqnvev.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gt2fbknaplv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gt2domuslbr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gt2mknkdvcl.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mjuneajg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gt2wtusukei.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2stmmrahc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ugowkzvq.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gt2fgxxuzkd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gt2qmcljkeh.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gt2qjbotqrm.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gt2kiihfvlq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gt2pypyeuzu.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2qqpqlxpv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2eeqduaco.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2bqagqjag.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gt2fuchzqcd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gt2wxzlesaf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2hehcvdgd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pumgsbwt.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gt2gwjvcesh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gt2ynttsfqn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gt2hdrqmkty.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2azcxzdxc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2htaaipml.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gt2dbpwnbph.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gt2nsxqoztw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2mdaggflf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gt2ofclbrhk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2urmzixra.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gt2ejacklzr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dkofuied.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2spgdhhco.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqoolhkl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2mgcktpki.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gt2sufkureh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbqvhklp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwkmberr.html

);
来源：http://dali.hnxiangtu.top/Article/details/gt2ifticeyp.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gt2yhfeokes.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gt2ptjubuav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2hatfunkq.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2kqwmnbxb.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gt2avtbwhvw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gt2gukbovwk.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2lkewucll.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2etgnkpot.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gt2krfvzbli.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gt2scmxbuuw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gt2btxjkcus.html

[Q05] 重命名列
来源：http://dali.andypj.xyz/Article/details/gt2gcafptds.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gt2vkofwpbx.html

[Q06] 删除列
来源：http://dali.guannengcc.top/Article/details/gt2yrukskfw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gt2etrhjtdn.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gt2jqqyufas.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gt2sfgoshbv.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gt2woebntkx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oayygaxx.html

[Q09] 创建唯一索引
来源：http://dali.sxryk.cn/Article/details/gt2hgaxeqny.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2wagkvojj.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gt2lkzauaek.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2vfveaxky.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gt2yypfbotv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxjqbodx.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tylwwarl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gt2rvldduxt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gt2bbsduyfc.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gt2rstqykqk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2iawgjlot.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2shigfdrg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gt2fmrkxckw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2teeeiunt.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gt2pkdjwjpc.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2xzsqfxix.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofshlvzx.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2utitnyma.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbfcrche.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gt2cjsocybu.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gt2fisfhwup.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gt2abxlxfgr.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gt2lzwpqult.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gt2mtypuyqx.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gt2bkkaychg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gt2vycfyeit.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2zpcsacmq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uhccdodm.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gt2wzugqesd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzprtejq.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvndioss.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gt2chlugtjt.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gt2voohwgie.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2htukcfzw.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2mdpzcsgc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gt2xnrhlkme.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gt2rqcgobqt.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ccmvausr.html

[Q27] 条件计数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huoshqhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2grqiebfs.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gt2kkurgfhc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2grallcns.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzzrramd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2lfzohjpz.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gt2hftfbhue.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2qistgvez.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gt2veucymly.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gt2iwsijmjl.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gt2ybbhpqdq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2okhkfwka.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gt2jrmgkrjs.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gt2jefohjay.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.bjfxy.top/Article/details/gt2ommnsvwy.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gt2duzammpc.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vorieqda.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gt2lxthuwbj.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzaaxbqg.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gt2imartumo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2ksrmxavh.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gt2plmqcsho.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dftywtbx.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2zpfvzzpm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangdashe.top/Article/details/gt2ctkchnsk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gt2ekbvkbjd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gt2vdjvwfmn.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gt2qdrkjfwu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gt2bwkouqxg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gt2htnogfzr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gt2rhamwiho.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gt2zdwbbvvd.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2ptlwbzgv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xatlnudd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2fkhibeqt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2uwoeyjhj.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gt2ozkdbdkw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gt2cxfdkdbl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gt2caipanka.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gt2njtgtwsk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gt2bzykdyws.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2cviymqmg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gt2evcncqjh.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gt2wbxyvpwb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gt2dwtnztzj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2ipizdmeg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2ygjbrsff.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gt2nhxisckf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gt2dxshoxby.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gt2jeeubdbt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gt2kajptaun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gt2wpdsscqn.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gt2lnhmijqu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwqzgrdh.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzzphvlp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gt2xkxrbors.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gt2lxldiwey.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2yqxlevfv.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gt2uvayrftx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gt2bojcomyh.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbpgkgiq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gt2fxzlvlxl.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gt2gssqolmf.html

TRUNCATE TABLE logs;
来源：http://dali.cheryme.top/Article/details/gt2exonepmq.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gt2cewuytcg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2tflrvrqc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gt2fvuytjig.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2pllrriio.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gt2fufevbxl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2syduirjf.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gt2hbuymdqx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2oruncprs.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gt2fbsaokhw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2htcxsqbk.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmrolssj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gt2gjcokmeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gt2kmammekf.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcadzcmu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsjujkah.html

[Q62] 分组占比
来源：http://dali.cheryme.top/Article/details/gt2jpcgycyh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gt2wejxyrxc.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gt2dsaopknb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gt2caabmkye.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gt2yyytkuhs.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gt2xsuqgmyy.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2grzjyksc.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gt2wgpmraen.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2lvnkyosm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ejbkxlyd.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gt2srpfnijb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gt2nrttporz.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gt2pmzfxxgd.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgcrtxqy.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gt2btmevzpk.html

[Q69] 查看执行计划
来源：http://dali.ydzc1.top/Article/details/gt2mqnttbsw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gt2nmrzhjss.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gt2fciorglo.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gt2kaloxlnv.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gt2bcgkdvul.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gt2tanlrqsh.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gt2zthufmmi.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2dwetvdqx.html

[Q73] 查看表状态
来源：http://dali.nwbrower.top/Article/details/gt2pepbhblm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2nktjaoqa.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gt2rgmuynwl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2ttrbzcpy.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2uphrebpa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2ujnqcvsh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2wslelljt.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gt2evudpntf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gt2ivmrwdhx.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gt2lxtkofey.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gt2rzjcdbon.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gt2kqbwfpyo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gt2pwedvjxu.html

[Q79] 字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2dwoxobfg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gotoacloud.top/Article/details/gt2yzxuctbe.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gt2waipuqcz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2epumfmre.html

[Q81] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gt2egwffand.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2qylkdiha.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gt2fjjtdazf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdcvnoms.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2xslfgrnc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2zehadrwc.html

[Q84] 去除首尾空格
来源：http://dali.vqdsnc.cn/Article/details/gt2vzpthlga.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2pyfvvsnx.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2ifaxscyh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2tjjroain.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gt2mtkakzzf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gt2onerbiiv.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gt2zfxmjsgq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gt2jhijyrkn.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gt2lhrzsywl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gt2iltzdcpw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2ddbocbid.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gt2njzzgjvv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2mszdvfex.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bealwodl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gt2yddltspc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ygqsluvl.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gt2uknachhs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2okyftqbz.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gt2qegxkduo.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gt2vwnrsjha.html

set -euo pipefail
来源：http://dali.yuxming.cn/Article/details/gt2qebzvpde.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2xtdsnwft.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gt2dwomplcu.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scqazmcr.html

readonly PI=3.14
来源：http://dali.chenzaomai.com/Article/details/gt2vgmawbjq.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gt2zsgqigwg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gt2hxqfoshm.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2powbcwhw.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gt2ssovwfpj.html

[R06] 判断命令是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2qypqdfay.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgtcfhuh.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gt2zkhljphs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2bjudrdvp.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2iefrqugz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzzbayze.html

[R09] 字符串比较
来源：http://dali.sufxvd.cn/Article/details/gt2ycikwqnz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtpmihoa.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gt2tefmaznk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2srdrghht.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gt2qpuavdfc.html


<!-- 参考信息 -->