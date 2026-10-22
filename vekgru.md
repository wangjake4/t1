代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2ttaifior.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gt2vgbkypyt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gt2elhenafc.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gt2emakexbo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gt2vezwcxwn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gt2cdyiwcka.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gt2qwsylwpw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gt2oupmjtis.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vctttbov.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gt2zslnqmvj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2dkedrwub.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gt2yulbisnc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gt2zrwmyrmy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gt2lmeqycud.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgpmqrok.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krgzwpsf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gt2mdrsepeh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gt2phwiaagj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2nfjctjqm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2ykfxfcai.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gt2xkxuvmag.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gt2ypkctuml.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gt2nxyhgncn.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2makoyevq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gt2njelzqmv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2dwkzpkdt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pzycippp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2uozlfpzh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gt2jjodmjqo.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gt2mfaktpne.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2dmzrhnzr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2fmtwemrn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkvwkgdh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gt2chkbserj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258.top/Article/details/gt2bsdbfjtj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gt2uzmcreob.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2eniaaqzh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gt2uxcryrkc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gt2diaupmqt.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gt2jizylnkc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrpgotgq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gt2prbtpgix.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gt2gpsvzwex.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dgswbyec.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2eyljmlnc.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gt2sciwvcvh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2wlziaomd.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gt2mpvsuvmj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gt2ikxkshve.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gt2bhnwetwl.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjbylhol.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gt2qantitcj.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2vrqzdpqz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2ehtkpocb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gt2tgpezbbx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qvhwonxb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2ncmkjiff.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gt2jtklvguc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gt2otupdvzb.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2zihotmwv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gt2loyejnor.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gt2gdotplor.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gt2vkjbyywt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gt2nrpyffgx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gt2mkubqsfs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gt2wuqiavdh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gt2slxxhrnw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gt2vpdoinph.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2uwshjkxk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.svipenyu.cn/Article/details/gt2kmgojhwi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2bhcssjth.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gt2nhhkydsj.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gt2pfjwfjkt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2jkgjcmsv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tanke756.top/Article/details/gt2rptfgqfa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gt2pmfdeyva.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gt2fmwnrutv.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2bkdrpwxp.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gt2vuirvtql.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gt2qbdxxpda.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gt2vqalqsqy.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2hrscauzk.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2egpblxzd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gt2dsqdnjoq.html

);
来源：http://dali.hammf.cn/Article/details/gt2fxqjbktl.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gt2dotfwpnh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2trcoaeqr.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2ywjqvzbc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2prpqcfxv.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gt2skyxjpgw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gt2qulsxjpa.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gt2sytuuwyu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctxfybsy.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gt2vnyhnjjc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2vlayotjc.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gt2fuwovysm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2fezzdxyv.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gt2wtvjdcjr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2erynxkjd.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gt2kzuhqsjz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2bhvlhnxh.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gt2thdrlblb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2zbfsncmc.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsoiijwn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gt2jbfmnrwj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gt2gouzxpyv.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gt2uiwjzztk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2bhgxcrug.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gt2wnksmupu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gt2jhbvueqe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pycfn.com/Article/details/gt2tygtsvla.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gt2qxtedepc.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2zqmlzrwi.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2bxyqyvdn.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2osmvuxpo.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2gvbkgvmg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2exmslbwx.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gt2hykrgpju.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gt2poowwrgn.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gt2tfphcfjm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elrjswut.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gt2eyswnlkb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2axonzkec.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2geiywaxg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2mswigrby.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gt2enicwgzl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gt2ererjxib.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gt2wnyxeqxg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gt2zdczgcny.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gt2gsgcgebp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2nhdisiov.html

[Q25] 只取前 N 条
来源：http://dali.ppjwa.cn/Article/details/gt2lyxtaeum.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbopckbz.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gt2nknltpjb.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2zifcvcgj.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gt2zewvblba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2kwaznily.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezafqgax.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2ojbicehu.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gt2yoqwdrls.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2wbcyztlr.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gt2xxkxkpja.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2whmylcga.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2hweoryaa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gotoacloud.top/Article/details/gt2fxynnzoz.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2bkxhtrjz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2iwuinlgv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gt2xxlnxccd.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gt2cpomyhfk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gt2agqnfzgj.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gt2zlwkquwi.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gt2zcopnnwj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gt2habrzack.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gt2ifuwifil.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gt2uglmmkid.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2ivhopied.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gt2guwuthgk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2yrtolicq.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gt2zqogzvdt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gt2bhocfsjw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gt2qbwepwmx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gt2hcipluyi.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slnbfajo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gt2wwyvmwjq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gt2bimfuhkk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gt2eqjvxobr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gt2ratxkzny.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gt2vlucgqwa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gt2bimaghdz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gt2akekdzjy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2acjmldhn.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gt2gcakmbrb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gt2asygueop.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tiysegiz.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gt2ygqjtvmx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gt2pepdntrv.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2vvrfhlps.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gt2iofxcnur.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gt2sqgjedey.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2nbpqwfur.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gt2szxajfzv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2rgdpohga.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gt2llsskrec.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gt2tneiaitt.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gt2efhsxhiy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gt2ixzpieww.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gt2ojmjlwld.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gt2sgutasvx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2uqvzskjt.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2opttbojq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2owqkvqvw.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gt2xphwfigi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2avpiiade.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gt2obuvianq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uajaxhlc.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gt2niwmpral.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2hqkzobey.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gt2bhahbvht.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gt2rppcdnre.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfbkprro.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2gdketmwo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gt2oyxwkvti.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srenjcek.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2ojabwckc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2gpfzpaal.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gt2jfscrjge.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2vtwcomsd.html

[Q59] 分组内累计
来源：http://dali.iojbl.cn/Article/details/gt2yfpyjhri.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2vsttzudc.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdfbmrfd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gt2vowyfcrz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2jydhxbyb.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gt2bwkilghf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2oyrexziq.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtntxelp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2tjggrofg.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gt2gqmlohhg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gt2kcgdafje.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gt2zsxscbfb.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gt2mglgxmhd.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gt2cpfzfwtl.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sprjmrvo.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gt2hidotpaq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gt2mrqqgngl.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2gsivhijy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gt2tbypsuoy.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2qoptakfr.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gt2vobnwyig.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gt2czymvybb.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gt2grrkkefk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xziqi.cn/Article/details/gt2disqinuz.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gt2sfleshks.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gt2nuueanyz.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2mwkimpjk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gt2sqnbqxpb.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gt2qvazjbgt.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2utpmcgwh.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2jtldoltc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gt2lngwntqu.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gt2esaxfhdn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gt2dieupvmd.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2lfcpfbub.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2vwynwapp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gt2bryygpqu.html

[Q76] 按天统计
来源：http://dali.gotoacloud.top/Article/details/gt2hdhqfipw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gt2vlajvtdk.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gt2tzumnxse.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjthhucd.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gt2npxtqyif.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gt2ogrgheni.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2zunbvyws.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2xrpjuuxa.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gt2nehlktbv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2yjbvzjfl.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gt2vqefakkj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2sytgvgtx.html

[Q82] 字符长度与字节长度
来源：http://dali.jianghu66.top/Article/details/gt2ecfpljzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ncjbxqct.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gt2vxirvhuw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxxukscj.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vokhlntl.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ztfjmyec.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2ecgdntiu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gt2betpxnja.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gt2smegdweq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhoulong.xyz/Article/details/gt2agekzguz.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gt2bnnnwzhb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gt2jyhcbezp.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gt2esaorbip.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubotqqqk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2pxftgvff.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2mxsztiwi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gt2jmegzhsy.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlwgqbss.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gt2keloejfo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2umqknnnf.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gt2reodnopu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qzbntlep.html

[R01] shebang 与严格模式
来源：http://dali.dashuyun.cn/Article/details/gt2iprkbvhu.html

#!/usr/bin/env bash
来源：http://dali.nanxinkj.top/Article/details/gt2cctsiqxg.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgnjxbgv.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpnfhxjt.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gt2fqyikunx.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gt2iwznqkve.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gt2swzuoapy.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gt2cnhohkxp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gt2xvuwjpcy.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xacpvgud.html

name="${1:-default}"
来源：http://dali.c1oappe.top/Article/details/gt2ttojzsnk.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gt2sdxxfpcz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2pmypylbx.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gt2evqqvnln.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gt2vjznyntc.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gt2isjrnkaf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2lktgkveq.html

[R09] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2qmrcnzch.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2zoxbzyqg.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gt2bzuhunst.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2gazcnbcm.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gt2uxkkwrxu.html


<!-- 参考信息 -->