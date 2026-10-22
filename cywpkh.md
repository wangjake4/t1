代发 wailian999

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtlpcckatd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gteidyhtqp.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gteeiquozu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtyoofflqc.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtnfhlyase.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtpufexyoq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtdbunpyar.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtvfncydha.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtlitmgfuu.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtggojlekl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtouegkfcg.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtjecytmwx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtvgvwtvbf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtiwzhocug.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtgixhdqdp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtdclexfdi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtyjdfcynz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtzuwvvkoe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gtpgxiiznu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtlgyyvqas.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtsqdvxbww.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtzindfayr.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtzsnwoual.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gtteyqkxrw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtdvtohtfw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtgpclyooo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtoxqaiuyi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gtbdexvvnp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gtlfhnlzeq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gttcmmkzms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gtbhqsozxr.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtrwmtyvxp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtwcscqaar.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtnosbttwv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtmsbexwqu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtmaevjjox.html

Java: list.size();  map.size();  s.length()
来源：http://dali.havefunace.top/Article/details/gtizggbsdn.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofmxggbm.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtfifgwozt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtkxgynjtb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtubkdjeeb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtnaftxrtd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gthnvnsyok.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtcujyuksu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtglodzzdq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtlxffyulr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtaisjralw.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtaagmzhvq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtcfyhdmqy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtvzufszbi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gtgwbhadhn.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtkbwokoth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtgfoyrian.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtgllzooka.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtpujkdcpi.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gtecroczwa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrqqkblh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtpeuvgufw.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtppboxytm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgvsoasb.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gtijvtzfcd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtzaffbani.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtqpflkpcb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnenuhisj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtjoxalwrl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtyfbxajtg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtblsmqihi.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtjhdobrvh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtqvcjltvi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtwibdaqao.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gtsywpnmqg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtjckfhbie.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtztgmqhts.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gthxzlkryt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtyyrbfrxc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtqxwhvrdi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqytefprg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtfzwmelqb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwxwzsqov.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtuywscasa.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gttwiphtnp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtmfxnuihb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtxgvrmbts.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gtsmcgkwuj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtmmujxppt.html

);
来源：http://dali.dianchejie.cn/Article/details/gtqbfkgskf.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtjlcjhoav.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhehwjjm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtvtgthcya.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtgnncrmgy.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gtzdwehqbd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gthgzxonmz.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtgpfxkfvj.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gtpbomseqh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gthkitblco.html

[Q04] 修改列类型
来源：http://dali.hysaishi.cn/Article/details/gtuxvjiqpo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtbtemtsgr.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gthhytivnl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtsfsprmxd.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtapdzbjfm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gtfmwngpqm.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtmkenvzzr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtngmnkler.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtjcsjkdbi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gttzfbmyco.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gtmwrbxwhb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtsgwnwzjw.html

[Q10] 插入单行
来源：http://dali.hnxiangtu.top/Article/details/gtokbkrkcj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxdixuja.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtekdyyvcq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtupbswhci.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtcrfwluju.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtbslpvfhw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdxtfpxk.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtwmnhfteg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtypqoqqhv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtywbmcskw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gtooltzmin.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtyyxwpevl.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gtweeoagiy.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtghvnlten.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gtgfuvosvg.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gtkzqcwpgk.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtobihfuua.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangdashe.top/Article/details/gtfofwveft.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gthmkidhoz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gtmdwngstv.html

[Q19] 范围查询
来源：http://dali.quarkkingdee.top/Article/details/gtnvkappyb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtabpbxuje.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gtdjnaqaec.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtyqhfnnjk.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtpqtvrtrd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtblwdtwcy.html

[Q22] 排序
来源：http://dali.yanxiufei.cn/Article/details/gtignelmin.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtztkqhghf.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtgegoghxp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhixingplan.top/Article/details/gtzyacqizu.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtimpmvder.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtjipdnulc.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtciykiqxk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtvzjvykmp.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtumccyfdd.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtfgpinuns.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtawaluubl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtdwdkfegh.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gtzlnuyfbq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtpmutrfyl.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtsiohkrxy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtrykwquib.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtphnvwrzy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gthspndwwb.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtwraakxbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtforqhgxw.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtfguivkgx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtykltgvgg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtbghwmdxx.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gtghuxkcbq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtqkdjctxl.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gtuaxtqfhj.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtzymqkfxv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtekkxkqgr.html

) t WHERE rn = 1;
来源：http://dali.mhx1999.top/Article/details/gtiovewnwu.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtpcncrubf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gttghuidnt.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtstupgdib.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtzoevykcb.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gthpneplqx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtbcxmngyb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangtech.top/Article/details/gtivowmpzd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalhbbfbi.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gtomfbounx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gtixoqcaew.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtdiwyqfgr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtlksqhrdo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtcfptmiim.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtyuegbotd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtrxsrjaju.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gthdgpknux.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtjcbjucqy.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtxwxilugm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gtkkigyiqz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gteseshvzw.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtwofwdhbz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtbtqkqkxw.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtgltlbqsm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtodyybtqr.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gtzbggptvr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtcfwpwyiu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtpqgfsgky.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtaoeahszj.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtvcombjwv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gtidcyorcm.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtdwohwuvw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtyhpfxaub.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtsqvdvgdl.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gtlammlzjl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gthyruuorr.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcxbsshg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gticwnqjsc.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtxymsqewd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.birdmap.top/Article/details/gtflagyiev.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gtirsonjtx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtldprxpgn.html

[Q53] 按条件删除
来源：http://dali.hnqzz.top/Article/details/gtvxdgvlyu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gtwapqemsd.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtcmdjmysp.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtrvgklbdd.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gtqiwqvwjp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtohjkujaj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtjslczeqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtaliowjkc.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtvofmivch.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtnqbszobl.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtjqurkivj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtfbbesqqt.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtvkdibhnx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtmdseenos.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtsxfzcfhb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtyogkdvhy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtzapggnfv.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtsoowbltb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtcqlvtrae.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gtqbjofdws.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtuugzcdqk.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtvfpcjlae.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtnnqrvkqi.html

[Q64] 提交事务
来源：http://dali.guowangkeji.top/Article/details/gtgemsozak.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtaiimdghc.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtzbokxkax.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtlfdgblzv.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtrzttlmtr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtyevhuldm.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtqfbgzrih.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtkhydhbxs.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gtxcghhruj.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtsiqqvpeh.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtlsflykiq.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gtxoopoaeq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtelvwsaxo.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtpxieulkd.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtvitogpkg.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtadeuafts.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtprtiiplh.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gtuezohllg.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gtlvergomg.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtatiqmvai.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtjmwmtsoc.html

[Q74] 强制使用索引
来源：http://dali.pycfn.com/Article/details/gteltrawsl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtddwzeeez.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtxktadwwc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtixzzvvoy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtfmlcbhtc.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtljuntqia.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtzruxkjvk.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtxodjotww.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtvnjyqygt.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtfqroqoqs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gtucqskqod.html

[Q79] 字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtovnxnswb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtaplheddc.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtizozomrw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hammf.cn/Article/details/gtfmuiagld.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtptuzzfei.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtnmipblfn.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtefgsdetv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gttexfltuo.html

[Q83] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtwimkddwh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtxwiqkwow.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtfquhjjss.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtdjtyymfo.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtgozsetaz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gttdbebqca.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtlhblgqbu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.smart0.xyz/Article/details/gtvmihrbrd.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gthijxqehl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtsjkzymat.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gttsxvtgvz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtpovpkquw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtdpigbash.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtbyljksla.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtcluomiox.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gtjxonlrwg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtlcbsysqs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrnhnsinq.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gtbrhbmlus.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxhnenvbd.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtzcxniudu.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtcixxaujo.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtaebobbvb.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtzmyxllok.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gtnwnhtshg.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtodxctoch.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtgqeqfevp.html

[R04] 位置参数
来源：http://dali.shangyingyoupin.top/Article/details/gtexnxizcx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gtzspezkjw.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmivviwz.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtgqblcccz.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gtqbdksucp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtyepwmdmg.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtowlyflsd.html


<!-- 参考信息 -->