代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2thkmklxc.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gt2qwzrqcbi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2jveuqyba.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gt2svfzcbqr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gt2zatrlfno.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2famohkiq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gt2tthmwrrm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gt2xoxusker.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2ezchmkve.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gt2muzmsmkb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iahibgoj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjcrsexe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gt2fpjjqsmu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gt2sqyrcxkb.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrflvfbg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gt2dnsoxpwi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gt2vtfpjlyz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2plixfyty.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gt2lhwlzryi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gt2hrpowmff.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2rioacbkd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gt2jqnhbszh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gt2repbszxd.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gt2acdgevmk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2aerwhfvt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2wytjlans.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2cxdcbfuh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2rjmalfig.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gt2zxsdihin.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gt2hajxgemj.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gt2vtzduowd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xappwfhv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pycfn.com/Article/details/gt2uishqwhc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgmongfk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2nybehtmd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gt2yzxzishn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2zgptvgkp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sxryk.cn/Article/details/gt2ztsvoliv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2hwrogmtl.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gt2yagwkdhc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2tewqspad.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gt2fbjfgqzm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2riupercs.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gt2yqsldjmv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gt2cvbbvixi.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gt2taoxyvdj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2szimhzqb.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gt2vzivoxyj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gt2bssrlpvp.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2pmmcpvvi.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gt2tbbbqzjc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2dthsrpfr.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gt2jvssayum.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2vaqhxutp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2zmozvwsx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gt2pkcgnane.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajpeatyl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gt2lojhmmjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gt2xcruzwjv.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gt2blkvibjs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2djxomvji.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gt2sefjjjek.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvaahpfe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2icdasclw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjnnlinl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gt2mhheanbt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daxiang520.top/Article/details/gt2vzlyfqtb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2wtiqrqzp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2qipermhr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gt2nkjhatdi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jylprdul.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gt2qbgkfbey.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gt2akbjqgrz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2nqnirqen.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2xwzhkraw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gt2gcumnogc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sweek.top/Article/details/gt2wyylquzr.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2nnqnnern.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gt2ftjzzwgq.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gt2uwytcakf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gt2zleplywd.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2eqkyvdjh.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gt2cfutskxl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gt2vrnhwvab.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2jsbzwoyz.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gt2xgualmda.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2moauuomv.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gt2bfshuoms.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gt2phodrhcp.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gt2buwknxoy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gt2acikxqbs.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gt2vxcggqlo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gt2gbbahixx.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gt2dsdwmbvv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohvaxitm.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gt2cwpwknxf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2vhtfgghx.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gt2viqfpfvk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2rzvuswpi.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gt2sgrrnmyx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2ibwmfdeo.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gt2amrjcnqf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2fglpgjip.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2exuuqxjt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gt2fjwwrayf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gt2qrviufex.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gt2rzlecpcx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2tvcwwvrm.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gt2gytjvwxr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptazjkwb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gt2tkxpcpdz.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2tojndeiz.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2sxgcdgku.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2mpsdnmoe.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ypvtsaii.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2vbywcsga.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2cqloorgk.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gt2jnenrkrq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gt2wtcjuhtb.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gt2ahzkdqzn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gt2jxhwswcp.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gt2hvishetu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cupdzneg.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gt2cojxbdhc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gt2egdkmfmf.html

[Q22] 排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luykdwhk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gt2zmmguyjk.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gt2pkdvscxp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2khzjbzqh.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2mcdcrshn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2cdqreeox.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2jilrfjmc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpmsdamo.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gt2ysuzyplv.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2otfuovon.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gt2vwbqzeft.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2qyxxjoxk.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gt2ybzpbwco.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjmukftw.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnsrjftn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2wascmrek.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gt2loznspsj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2wupusteq.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gt2sgpikacq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gt2rjimgsnq.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2lvoiehbc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gt2jcbhlxhg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gt2minxnbmq.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gt2zolajeuj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gt2mwykhavn.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gt2drtptfpw.html

SELECT * FROM (
来源：http://dali.ydzc1.top/Article/details/gt2lsktacil.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gt2dmcdwday.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyhopqys.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gt2pcuudcjo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2crzsqend.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjffaqor.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2ehlwjwcn.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gt2pesklxoa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhbevfvi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gt2fsolddrj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gt2mjagvxlf.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gt2okxyoixe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gt2ncxqaefo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gt2wwtesjba.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2galuvemc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gt2kjeleiao.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gt2dsipsehz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gt2dschmeml.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gt2qptdoaqd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gt2xqnyfrwz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zsblemdg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gt2ekgupicn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gt2sivtlvzj.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gt2dcvcnmqm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gt2okfospfj.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypybmzgu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gt2zwuusgtr.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gt2vfiyelxu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2yvlbpbfw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gt2gmvjwcjv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gt2sudmdhja.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gt2ejgtcuhg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gt2hnwkvbha.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gt2gasnxozj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gt2fqbevhcy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gt2fsmrarir.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gt2bwtaybbn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gt2eiujsdaq.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gt2bjwcboqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2fccyhbbg.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2exewamyr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gt2bshjbjaq.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gt2egypiyil.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2puedndby.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gt2ytjigkcb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gt2nclzjziq.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkeltjyx.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2fqrkjqdg.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gt2sigxnxiy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2ewjbdrnr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuwwebuo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2vewnpyjg.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gt2awygzxww.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2pejtnafu.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gt2zvxyppue.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2avqvdvtp.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gt2flxbapcu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2qisikcza.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gt2kcnixois.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gt2orhyedeh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2cwparxsn.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gt2dsjjlmoa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2lyncuciu.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gt2ugeqmpdx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2cucpubxy.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2hynerfed.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlltrsca.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gt2jcakcmjk.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gt2ndcryycb.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gt2fkfybkkx.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2zstkfspg.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2brmqngzq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gt2ofwrypzq.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwdciwgk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gt2njetxopt.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gt2tjitmzyj.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gt2kwswaghp.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2fmaanhnb.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gt2feyyhvmg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gt2poluvcys.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gt2qkkffruz.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gt2yteweexn.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gt2qfnymqbw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gt2jtbrhdsu.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2neqxzicn.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gt2cplixjxj.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gt2podwxdpb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2swlgosnb.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gt2uhkxpkql.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gt2ciotfono.html

[Q75] 日期格式化
来源：http://dali.sweek.top/Article/details/gt2xbfreisx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2wuvnqhgl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gt2ziotpidz.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gt2apblajxh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gt2pywuybbv.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gt2nubddjmq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gt2oejidpmv.html

[Q78] 当前时间
来源：http://dali.kuanghao11.cn/Article/details/gt2prnfwhsf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gt2rbiwrmlb.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gt2vkvyjvnt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gt2fmlococj.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gt2kuumrmqy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2pqcdichn.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2xqdfotxu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2zqhskmos.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2fqyijxox.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2rttqctur.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2vpwjhvmp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2iobiwnua.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gt2wogyejtw.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klduwcah.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gt2xxidsmim.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fueigtkp.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrwpnxxj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gt2wuzfzwgt.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gt2gtrnwxqf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gt2akuushoz.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gt2xjlcsmzy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2fmyokhmj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyxggctj.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2bvisjpfi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gt2hvigrkoz.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewibaiwi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfdfyojp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2yihvpqyx.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gt2pkaiyems.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2qjpfmmnf.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gt2hgjhnhtd.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2bwskkpuf.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gt2yryaprwh.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gt2apacyosh.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyqpncqj.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gt2umxarrzi.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gt2nejoiuqc.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gt2gxxytszn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cdnleiting.top/Article/details/gt2lojdfhaf.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gt2enkxejdm.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gt2mzfklqwc.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gt2qyvzhwdc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2cjlohpjf.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwjtpmlf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2ifkuepxg.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2gxpzkwsn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gt2owtwgvez.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2jhnfmbgh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gt2yhgqwukc.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gt2xkjirhfo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2sokrrmeq.html

[R11] case 多分支
来源：http://dali.tanke756.top/Article/details/gt2wfbsdstu.html


<!-- 参考信息 -->