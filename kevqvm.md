代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cqqwz.cn/Article/details/gt2tsvgtygf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gt2otaekjwx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2xpefcyhb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rihabajc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gt2krvqewlf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqcpcfwa.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gt2wwixorks.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gt2dhuddttq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkktvaeq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2sqnyrwmt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xegpdscj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gt2ywfnresg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gt2guamqope.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2tbwpxqla.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gt2dvczsmse.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gt2rfrnduzm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gt2ommzkepr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2lxufmjaw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2vmdcojyt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2dsiiofbv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2phavfylf.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gt2rtrrexpb.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gt2gaowzwck.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2oysevesj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2oeuomznw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gt2rgbdnhxc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gt2ofxtzkoe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gt2kitwqwvx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2kqynmqjy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gt2driluotm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2oqqbgwdk.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gt2bzubjnse.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gt2ufpzahwm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gt2caqgjtwj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2almosuiw.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2asyojmza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gt2clwqgozo.html

TS:   if (x == null) {}
来源：http://dali.cashguo.top/Article/details/gt2uantzywc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2dyvmxfcm.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gt2hnzpxgzb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gt2qrgtbvwf.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2yjjpetlf.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gt2wnlzrisj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gt2lkkmnsyg.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gt2avyikoxh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2fnuqdcnj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2somjtqjf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gt2fgxmqtxw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gt2qnifqzik.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gt2yllyjwfu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gt2lpsnynys.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gt2kratrqdj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gt2nzbkwhqo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gt2ceqjgcji.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gt2kcvxqvxi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2rqgjwzha.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gt2iojbgbwn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gt2nkjylpjs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhhxxxhr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gt2owxgzher.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2heuaapsw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wboohcam.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rnqmsrrc.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gt2mgzcjogd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2koeguqay.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfhllyhh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2atmwabov.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gt2xukkglkz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gt2kpzpwtyr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvakicml.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gt2kqiwqryg.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gt2jhmvpcbr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2uyuelbjd.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2vxbhaerf.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2mwprgslj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gt2jeirheff.html

);
来源：http://dali.xinyue.icu/Article/details/gt2moaypymm.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gt2zykvryjl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jianghu66.top/Article/details/gt2yoblobze.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gt2vmejbzvq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2onubpuso.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gt2ebczibub.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gt2biynogck.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gt2ljvftsel.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gt2hdfluvng.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gt2illtuaur.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gt2cmnfjatg.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gt2euszevmz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjwzqsdu.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gt2lgsqmhyz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2ltssvmew.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gt2tkkssrgs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2iafcqxmb.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngvzrjms.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2sxyjroqk.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gt2gsvjjuet.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gt2kdffehyh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gt2ktqxaqgj.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gt2jqgkkhiq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2sliccdys.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2nnbclxbv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gt2zmvoeeyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gt2hqexwblo.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gt2vmbtfftu.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gt2pkjnkelp.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cefxwyzb.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nbcaabca.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gt2knpeoaas.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gt2zblhzzqx.html

[Q18] 模糊匹配
来源：http://dali.andypj.xyz/Article/details/gt2hrflvloc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gt2jiiwmuaw.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gt2euquniye.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2nyptjzgz.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2usnvnirt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gt2znljxzrt.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gt2gyqxrclh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gt2znmcclmm.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gt2mtdzuykh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gt2zgkmqqkc.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2rrtyodzx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gt2eemskrmh.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gt2fqfypmjp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2pnvifjsi.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gt2blwxwqep.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gt2fniqjuxf.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gt2hjxybmpn.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2gtznwapf.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gt2ewuuvmto.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2qlcmrums.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2qacobfel.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejiunfqb.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gt2znanpola.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2bgsmcuse.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gt2iefdlclu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2wzcrzibe.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2hgibfkaw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gt2zpjrsxah.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2unagasmc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubkjiffm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gt2jrjcfdtx.html

[Q33] 多列分组
来源：http://dali.jqgfzy.top/Article/details/gt2yzcsjqhh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gt2zefyuusj.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gt2mfwcpqaw.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2vkxmzdzq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gt2pfubfqev.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2ihiaahux.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gt2smdazqez.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2gfvbphsz.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gt2gzurkbgd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2tcndkjls.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gt2ktbhkbab.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2nltpvsrd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gt2oddnvokq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hysaishi.cn/Article/details/gt2bkgavaqu.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gt2dslbyyxn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gt2fakrzwai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvvbxflx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gt2iotmauhw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gt2xvegcwyz.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gt2wfgeemlv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gt2vocrdkmu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gt2whtfrtbk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gt2detahbgj.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gt2mncxgqnk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzweexzs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmesdodc.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gt2vvfdznip.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2qiwjqqqa.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gt2xufwykwj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gt2eskzcpkx.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2doufoxtk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2pjxcqqxk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gt2wlhrmwnv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gt2yylaebts.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2pzdaqwvc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gt2xytufixz.html

[Q48] CTE 公用表表达式
来源：http://dali.c1oappe.top/Article/details/gt2kuxnlprk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gt2iojzjwtx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gt2ofpwtrgu.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2bvzweias.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2hgfnvpbv.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gt2htcsgxoq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2xdulefxs.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gt2epsdlgeg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2pisucppk.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gt2gpcwchks.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2seflwbsl.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gt2guclwnfs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gt2eqogmdlr.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2nxpaovsx.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gt2ydwxcnjf.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2toeqqeot.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gt2lebcccon.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2hzuhmzcw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2uxewokzu.html

[Q57] 行号
来源：http://dali.xuanzx.com/Article/details/gt2vnkrbkek.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gt2wdeucffi.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gt2lfirhcsk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2btazpzyf.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gt2yjdyyhqf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2hwqzmyaj.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2icimngil.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gt2jbkvezcx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2sooryqzd.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2grxbcnem.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2xvxkaydl.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gt2pkpwzbmo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2xbgwyddv.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gt2wunjpjsa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gt2hzwrwnht.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gt2knssuowv.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gt2pficafyz.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqubexhg.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2bvmebwnx.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gt2ycqhnuys.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2esfdbmil.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmqkjqii.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gt2mzsxjovi.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gt2tchyaktn.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2tggyunfi.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2vrshyxce.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gt2lpihtgoh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccjbfjwp.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwmskqel.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gt2hbcxvhbh.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gt2xlyiptip.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gt2jyqcnehw.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gt2mocqrcxu.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2znwkoolu.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gt2kfpdhbvb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.quarkkingdee.top/Article/details/gt2fqikgpjg.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2nwvaopck.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2pgloigwo.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2htaipogx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2eeypricx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suvrszir.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gt2kufwkvih.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzfieksa.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gt2yucrcgla.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nanxinkj.top/Article/details/gt2aluidcsk.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gt2uoexjwdy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gt2smvgqakj.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2lrvzppxx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gt2paonamie.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gt2htjqkkzm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxypqchh.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2ynkflvrw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2utpbjaoj.html

[Q82] 字符长度与字节长度
来源：http://dali.kuanghao11.cn/Article/details/gt2geaqnleb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2jxqcygem.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2mqybtdfn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2pndgruzx.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2cgjicjly.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2cmzvbzwg.html

[Q85] 数值取整
来源：http://dali.sysykeji.top/Article/details/gt2ztuzlcwv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hfpthk.cn/Article/details/gt2rzgsxfaj.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqewaryo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gt2hecnooaa.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gt2awmwswrv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gewqsxtl.html

[Q88] 行转列（条件聚合）
来源：http://dali.meibo888.top/Article/details/gt2udpjbhcz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2fgjbmbsu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2yolrresw.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gt2azstlcgz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gt2etsyeqtn.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gt2mqouwpmm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.havefunace.top/Article/details/gt2yyrxlfiq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlnnuiva.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gt2chxqwwib.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xxxcfktr.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gt2kaspejih.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gt2miaexypr.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwtaxnxv.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gt2iruutomv.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gt2srfrqmfy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tofzayvc.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2arjogimi.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkmpvwfp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2wrnzzoiy.html

[R05] 参数默认值
来源：http://dali.tianlin.xyz/Article/details/gt2grhdlgnm.html

name="${1:-default}"
来源：http://dali.yueranfly.top/Article/details/gt2mqulbzwo.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2uwkqsmpd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gt2dirxdndv.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gt2izsyvrax.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2izzmwuot.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnuepjbz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gt2zhbxawrw.html

[R09] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2ghaepobp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2mvmtuyzj.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gt2muhqjfir.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gt2iaegkfhb.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gt2tcekddhl.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gt2prbrszbi.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfhyqnsk.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2zeszduha.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2mlrjymug.html

esac
来源：http://dali.shuidangran.top/Article/details/gt2kogmjlmy.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gt2nvruifxh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gt2aqwafbxv.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gt2zdyhweci.html


<!-- 参考信息 -->