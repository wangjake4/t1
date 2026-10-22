代发 wailian999

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gt2ctwvtnhb.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scpdkbej.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxkzpkzk.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2wzcfbnii.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2ycvcvypf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbgvcssr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfptppbt.html

Ruby: SecureRandom.uuid
来源：http://dali.cashguo.top/Article/details/gt2toewhacn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gt2teiaxixw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gt2jocqfgkv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2zpjmnsdb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ibhpztlp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gt2wmbchgng.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gt2czrvtkpj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhketudb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gt2kjxhgktj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2zvaqyzrs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2muokeryg.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gt2cwfadlrb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gt2homihvzb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gt2rcevyvln.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2cfcxctnl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gt2twedfywh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2nyfynypm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gt2czklpwff.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqjwubw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gt2gxjgyqgk.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkaxjjmj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2ixtfjmye.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzeoaaqf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2silvqcey.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2sfmaanjh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2nagzhfqc.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2xoszgrti.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gt2rolexfdy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2annxuqoq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gt2oavjlfbp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gt2kfnfncrh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gt2ghkodxbl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gt2xzlbtjpz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwqgocys.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenzaomai.com/Article/details/gt2agzrwjdj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2vngazliq.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2olwqwapc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2yezanydv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hckzjgxa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gt2gzprcbye.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2hsjqxnud.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gt2cusbnzdb.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqnkeily.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odjdamtt.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gt2ldudnvtl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gt2bvvqlcyb.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqfnvpzk.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gt2xiqmqdxo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxzujnqh.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gt2xqgqpmso.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2fvwlbagi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saoiustg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gt2dcxyvmvb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2glrfohhb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bflycpji.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddkjbbdu.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gt2apqtvxch.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gt2uiuhvghb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2vehnzivu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gt2xzdvskkf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdmzbvjd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2bdosunhw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gt2rqznnild.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcohiicx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2mzhhwapd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2udlwckzo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gt2wastpasj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2bppwxzte.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gt2pmhgsdud.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gt2nzvsyypi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gt2wczywkeh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2tzywcnte.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gt2mzzohokk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gt2jsnrvwns.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2ezvlxcmn.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gt2qfjvohux.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gt2ekjlmjdd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gt2uzoekyum.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2qnryghkr.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gt2tiavzbcd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gt2udairaho.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2xjxyjsec.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gt2utoklrcl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gt2gepogolg.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gt2fsmgrydz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gt2ewvnezle.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inkprzbk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2lmmnjpbo.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gt2syehdzhh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jasvrddp.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gt2wffjyxdi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gt2psnqkjdf.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2avszmpfg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnuulxqh.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhjqmrdf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2ezzrfjlu.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gt2uakfgmgv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2pnpqslml.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gt2pkqpmhev.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2nhjocvnw.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gt2jvkrnudy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gt2uunaoppl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2atxktpuo.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gt2hbwyhdtl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2lsrymbjv.html

[Q14] 存在则更新（upsert）
来源：http://dali.sweek.top/Article/details/gt2sdrulxwf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gt2lizcamdh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gt2kqaiaykz.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gt2ottulinc.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptqilxwt.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gt2tstkmoyd.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gt2pgydtana.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2keokbuee.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2hysptnxs.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2okupnjpu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gt2gxjkeppp.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gt2piwwdomk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gt2oowrvbhs.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2edpeczlc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2tgtpqcom.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gt2qewagftv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gt2avvxntcd.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gt2snoaqbiy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2qyfrvsow.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gt2vpugzuoy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygzornhr.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2iijamwra.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2mcnufqay.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gt2rpvinxml.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2htapirdq.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gt2outmtdly.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2khnshnds.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gt2tetvycdk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjxvumxh.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2egdwqizt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2rudapolp.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gt2qdkichql.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2dxbogmfo.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gt2jodhlxpf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2qtchoaxo.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gt2vrhurzzm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhgetdhd.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2simgiyhh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2tksuodyb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gt2ujnpadne.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2zuvleixc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gt2ekatgklh.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gt2nugnwdbx.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gt2lyphkuci.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gotoacloud.top/Article/details/gt2ulwluqoa.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gt2amepcakd.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gt2qjdcazow.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2vijpszai.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gt2ypkpcgrn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2ischzfyq.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uomlbeqo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gt2pqqgulrg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gt2oighbicf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gt2grtmnzpd.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gt2bzqtfigj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gt2rvigvwpl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gt2syusyjem.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gt2onwbllhb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jauicskc.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gt2gvplemqa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gt2mriuqtfu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gt2lmhxidvd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gt2ewayhcxy.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2ltjbgwdi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gt2utvbzvcs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2wbcjomui.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gt2qxzdhign.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2nqjgqvgr.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gt2epvuxcla.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2abcjpnnm.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gt2eihvzvde.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2wgkejdqx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gt2apmqiyon.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2duekwtvi.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gt2spqdumyt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gt2enazqrtz.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2imsqzdwc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gt2xajctmsk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gt2kiefgjyt.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gt2submecek.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gt2gazzjwuj.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkcpgcaz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2fcixtwzk.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2wxvyxsjw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2uqaxjgaz.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gt2woxcrwug.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2wicuqban.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bezrbdjj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2lbywkjiu.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gt2zlkmnaui.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdnxqoo.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcornijd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obzwiorl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gt2gwhkdxlg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2ntdxgamo.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2yxytdhcm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkhlbtos.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gt2steezttc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2hnuetzim.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gt2rkwazsxy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2ejjjfjwg.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gt2yaiaksac.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gt2bggqpkcw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2lyaiugiq.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gt2mqgahvbv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2gxubzjvb.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2mvqykafk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2zhxghomj.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gt2zrxxekez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gt2qffuipmy.html

[Q64] 提交事务
来源：http://dali.haohaochexian.top/Article/details/gt2zvuwnlil.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahamgyld.html

[Q65] 回滚事务
来源：http://dali.c1oappe.top/Article/details/gt2yiaviknu.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gt2azxculse.html

[Q66] 行锁查询
来源：http://dali.jiagoushi.top/Article/details/gt2ulxmnuth.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gt2snywvexz.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gt2bqmzzwgg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gt2dcnspmce.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gt2dvchvkxb.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2jrcenagn.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gt2vuoouttt.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2wxvmcqzz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwszxomr.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gt2lkkblord.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gt2sfmbkzbo.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gt2nvaxpfvo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gt2kioppcdr.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2lsevzjkg.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2vskxkcpb.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gt2elujiylg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gt2sbzbfpci.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtteonfk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2wrsigcdo.html

[Q75] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xknfbgxy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2ehllrzky.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gt2yolywvum.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gt2kjffguak.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvzswhis.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gt2wzpnnzfv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gt2adamcrzt.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gt2qsjkejog.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tanke756.top/Article/details/gt2snjmcang.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2ptjztvyo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gt2ocgwfccd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkfqgln.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2nobvwcfc.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grnwknei.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2glwywfgl.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gt2jgwjhuca.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2usgdnbts.html

[Q83] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2tqjlsfsj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2xffxwqwb.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gt2novhsyfo.html

SELECT TRIM(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2exvevden.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrbffeju.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2oaipdrpf.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixliildr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gt2qklzyprc.html

[Q87] JSON 字段做条件
来源：http://dali.sufxvd.cn/Article/details/gt2uptycwvh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gt2nvbhibnb.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2kdvqbjwn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gt2ravqgffl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2rmsvlxit.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2ymmmazul.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gt2jgmnraqh.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gt2wffokwqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gt2vzaukenv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2dykltyuf.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gt2truxkzij.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2pjdqbsdt.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2fbjvkrmx.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gt2ibpeoaaz.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2jsprkmpk.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gt2cdcubgzd.html

name="Tom"; echo "$name"
来源：http://dali.yj20258.top/Article/details/gt2tczxbdzp.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itykugio.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gt2vmtctxwk.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gt2ogrxcudx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2wtzgdknm.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gt2pztfxhvz.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gt2sankhwae.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwclxetj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2fftnrujf.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asoascbz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gt2mgxoyxcl.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gt2ibbnxwrp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gt2naripvpg.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2lkygjbwg.html


<!-- 参考信息 -->