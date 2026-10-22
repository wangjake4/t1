代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gt2oncypoxe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gt2qmdvhdvg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2jdijjjhs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gt2cflidpsj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gt2itgrucra.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gt2dbganbrt.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gt2tkleejup.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2jqafgpyu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2qrnrnzmp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gt2ydtzcobj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pczwhkaw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fupcyekx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gt2oxkosvsj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gt2cmspnlgb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gt2csodduod.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gt2hriatfpn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gt2utbsokff.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2oekbkvpz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2lanjsafs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2suhnjqlr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2gzmtjvtr.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gt2efzgtzib.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gt2biuojqmw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2yvhseomk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gt2aeuumqpi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gt2lcvpjnhx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gt2xxdhyqte.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyabnrgs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2yzmqruzq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2xxeiahub.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nmrjupwi.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gt2diyfivwt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gt2vwmtjxos.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gt2bfjitptv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gt2hbsfntuo.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2spxwdsvc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gt2matuesdo.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pipohhox.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gt2wjeikmfz.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtjhfyte.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gt2kcydpqxu.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2prykppei.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gt2tmmrghej.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gt2nxhgtaaj.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gt2lqkfapiw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2wzbsnhkf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2zlzydwbg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gt2shxsabtu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2kedwmmzk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gt2ybgqkrzf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gt2ejgkoads.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2duikcohy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gt2snktlhlw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gt2mebxbulh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2jaihafse.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2glvyeoyj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gt2yucomeeu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gt2btyzldyt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2adzxyenj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gt2odnrqdsd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2uohwlhra.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gt2yiftptld.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2exgvewrg.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gt2xirtuiod.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gt2judbmyin.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2xzgyggrb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zklksqbc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gt2btmrtopk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gt2qnlogola.html

);
来源：http://dali.sysykeji.top/Article/details/gt2eonsakmq.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gt2dgawvcyk.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gt2pnptdlwl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2tsdthqdh.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2dptpquqz.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2dnxdxclf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gt2iccdkgkw.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2ynzmdwqm.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gt2kjkucodi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gt2rqtuzjmy.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gt2xgnhvcbc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gt2xeyfmjyi.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gt2vwjwjwwj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znjalutj.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gt2ullgetbf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gt2ibelfxij.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iogewzie.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ranqyjqq.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gt2dwdkhdqu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gt2mrrtsyel.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gt2ubxmhzau.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gt2pylfueme.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2cmgpgrpp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwfqagxd.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gt2zjqerfqx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2kmzxypwl.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2udwvpmek.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gt2amyzcqvt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlrsvqgl.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gt2iruljnoc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gt2mxthmezn.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gt2vqivmjgr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gt2huyileik.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gt2iujoyngh.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gt2tmiwntxh.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ekcpmqyl.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gt2exxuycih.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2fqxxscaq.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gt2aahumift.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gt2uvfuvncq.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gt2zxxtpoow.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gt2ztuzyeol.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooxnlqpy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gt2clatqiyn.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2gpughxic.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gt2ymbxaqge.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gt2bhcqvfui.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2iahnhaji.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2xfjkbmgk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gt2anxwalld.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gt2uidzwcht.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gt2zuseuybk.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2sccaqwsb.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2spljnrcr.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gt2aamrexoa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gt2fbqwjslw.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gt2ktbdxwtb.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2ysarjflo.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gt2paclfnye.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2rnuancre.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gt2vfpzkjen.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2nzqafvvl.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gt2leuvcmeu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2bamczzow.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgoergfc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gt2bcmbjwce.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2wsdtjlun.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gt2twavgdpr.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cldghygc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnsvwrjp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gt2dzwiksoq.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2wyzrztmm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2erthhjeb.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gt2ukctlibs.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gt2gboiybqe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gomskcnh.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2ucbhrpsd.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gt2xorprejq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnpdomnc.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gt2rdkjdufu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2eyfvivcr.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gt2axntgatj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2idlotwuu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gt2efjcomcn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdnmzqsb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gt2baslcqgq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gt2tnmihvas.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gt2xnercznn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2fipnxhqd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gt2ogppjxtj.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gt2ggmzafns.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gt2xedojnyi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gt2tmgjohtd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gt2gtfrlsmh.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbgkpqyf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gt2vimzpvyk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gt2rhiojkns.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2crlmjyaq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gt2veueixim.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atreaxrh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gt2zkgeiovm.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gt2npdgexjm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gt2iathhwqg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gt2uwpaamyn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gt2tzfjoybu.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gt2uyoggysv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gt2mzvoajji.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2yekgktzl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gt2cdgbqnty.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gt2mlawausv.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gt2fsvtuson.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2objxucta.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2qxjuoitf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2fhispvgi.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gt2ztjkoird.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aghfzqne.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gt2abryxico.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2rjctoask.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2oujoiaqx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gt2gxczbovq.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gt2dcsbaqnv.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gt2hqvqhrgj.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gt2vvijztoj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.smart0.xyz/Article/details/gt2pwvgyzgw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scvtqovf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2qyoexvqn.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gt2yqwmpdjr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2xrdqlmww.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogzivkqv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2wufizwdr.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gt2nazagnah.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2ovmzxsfp.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gt2lcededbw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2whsmojig.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2ubwvqkjt.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gt2ohmeeezf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2vwfqnfbo.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2uakyqiue.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2kfobqotq.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gt2cnmqepft.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gt2vutmtbxp.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gt2kxxdyyga.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gt2kdmozduz.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gt2xsqzsdja.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gt2hteuxztq.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsobdrqf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gt2ddsmmfns.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gt2ohdkvkco.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzjttlxq.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2dppqnvaz.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2yrtkosgw.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2bzktwodf.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gt2tmakvumc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ivvv.top/Article/details/gt2gpvvvzit.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gt2hfvekasf.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gt2iobrmsgt.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gt2wqqmcndy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2vrcftmna.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gt2uzsqgtww.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2vempdkxo.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfsmzppl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gt2wkqmotod.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gt2smuczpau.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gt2uazdsrzz.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gt2gebjknvj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2eiksrgvb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gt2dhwiakxq.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqigikpk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cazkawma.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkwhxqou.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kzzixphc.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2shzqavvl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gt2dazmjfch.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpvpzhpo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gt2wuprokcz.html

[Q80] 字符串截取
来源：http://dali.kuanghao11.cn/Article/details/gt2jhoiurtq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2qfsiuivb.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gt2phnpfyie.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2kepjfpin.html

[Q82] 字符长度与字节长度
来源：http://dali.yanxiufei.cn/Article/details/gt2vthwdjij.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2gihsmqyw.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2emahlosq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2jqjajpdh.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gt2ganbpomh.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2gqhafzla.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gt2mdwjkoip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axuggzgf.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gt2cfhxadez.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gt2ltnvhark.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2lzvycqgl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj202588.top/Article/details/gt2gwzxraoo.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gt2zsyfsmlm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gt2rvlmxznp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gt2ngqstusz.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2cyllnmog.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gt2tzmwevfx.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gt2nrhaucve.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rczfwgnv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ybuqmiiu.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqjiicnm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2biygnrve.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gt2xywvofuq.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gt2ekvhfndn.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2bathkhqc.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2geoaprhw.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gt2euexrldj.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gt2aysnfcou.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gt2saezgbdk.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbtupbfk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2ugdhiryd.html

[R05] 参数默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2oyxtkpdn.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gt2dqsajpex.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2cbcfikxx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2mhukbfkk.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gt2fnaxkkbh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2utorejiu.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gt2sdwsjqeg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqitflna.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2yzwzivxh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gt2psprngbd.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gt2mndhwhcu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gt2grjnawiq.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gt2muduwupf.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gt2jrkfogyu.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2oyiqxoju.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdhgkqoj.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gt2zjudukot.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idwpljal.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gt2jwgspamg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gt2hpattlqq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2diaeouga.html


<!-- 参考信息 -->