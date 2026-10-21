代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtiwdlhbsr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gtuyrvwgsl.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtlsfqakta.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtdfyboxdv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtmztuadri.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtafruyxme.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtyvhocvhh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtwvbboduy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtecvlbuar.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gtdwumcnhh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbqnejwv.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtkcfpbnqs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtwenakgsj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgnmvjus.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gteygxnjna.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtqcgwnzta.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtgrtqcmjp.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtkxyavpua.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gtyratatax.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gteywcrewt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtktkfmpaw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtztyemntu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtnixqernq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gthhypkgci.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtgjzvfkdv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtrngkzrxz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtrsqadxev.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtsjfmqmty.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtvrosyqfa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtnahmxkdo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtmucejeen.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxxmwieei.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gtwtaszybg.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtxxwedjvs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtflvfydqv.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtdnopgdsj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtournvijt.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtjvoincjn.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gtfpsconfl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gtuxpivqvt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtaozyrifh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtyhixewqt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtsaoqchmj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqixpttcg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gttcvttzbm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtfnmpdjco.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtngdgpubm.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gtvyvpyhyr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtafdnoovz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtahabfgof.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtdcyuvmgv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtggjpruhf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtaijogies.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtejzmuhdv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtofxtdxww.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gtocxkqcos.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrmnhqnki.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gtejvypldb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtciffrfqb.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtgmwlqpey.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtgbponqch.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gthpxctanh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtmcolxnfw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtpdaqhnfu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtbbxhpskm.html

);
来源：http://dali.gzhubu.top/Article/details/gtjprgrwit.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtdukmlygy.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcnvgjvf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtjwsnhutq.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtohwvfyue.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtjorqsmmc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtdohhbivl.html

);
来源：http://dali.haohaochexian.top/Article/details/gtkmesdcjt.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtvracfhcf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtqoivodpm.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsftxkiw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtwciikwet.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtnwaifsjz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtntlupies.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtorejrxry.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtychyxaem.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gtssjbdien.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtcgklhhip.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtpkzbbkex.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtyvubddvv.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtkaoxpfqu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtwpgrckkc.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gtxdwrzmle.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtrffdizkf.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtkkccoein.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gthkozqfzt.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtnamihwum.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtnfkwmpkt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqhmvfmo.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtchirhthn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtkqgppfgf.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gtmkksmrkt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtpisnwkmk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gttnmzqlri.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtzyodrzds.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtccsqnloh.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gtsoogntzz.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtxamwpeui.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtncemsycc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtpfodkeaw.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtgsibblwm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtckwesbjn.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtcwpdrlup.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gttupiznft.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gtiqawfbyg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtylyyuuwq.html

[Q21] 空值判断
来源：http://dali.aizwys.cn/Article/details/gtadkzovsi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtawvwytex.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtumptkqzu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtmrprkhum.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtzvegcavc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtnpxlmoih.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtkmqzxepn.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtxykmulee.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gttbeqkalg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gtemuzotrh.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gttnoocgqa.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtmvacpnwe.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtjroevemw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtakwxwuhr.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gteiqgwqkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtzlzbvelg.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtynoubvyi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtjydxkpmt.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtyqpvbhiw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtdhnqmtut.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtkwklrzab.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gtstvmirfv.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gttqmsgksf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtkstbcahh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gteheinsua.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtxugclztz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtilekjegz.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflsklzjh.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gtytczfmta.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtslxiphsw.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtxbzbydeb.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtbnqrauut.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtokqsvnlk.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtybslobth.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gteacccnck.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtxcuuirhl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtkftzqjoa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtuaphtfdd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtffthuzou.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gttztzgdez.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtglifmgkc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtxjouangr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtkkhyrpqb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtdnrphhsr.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtiiamnswm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gthicnhsqm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtigjdvmks.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrnicdzm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtbsnzuexd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtzupcqnis.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtrwizelbb.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtrzkteplg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gtncyfhonk.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gttdhqlljy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtfwssjhzl.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtpjqydicm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtnsxcgmzx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gthvsamaqh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtzbccwpyi.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtixachupg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtqkklyetz.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtmnearwea.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.smart0.xyz/Article/details/gtgkbjhoed.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtguivflsa.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gtgfkuggox.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtxknimtqo.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gtyyfjdzxq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsgsihnt.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxpromrt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtbqvbzunk.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtlgqwhojq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtkwrwvyzv.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtwlaiwagh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtstfbnebm.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtvlszsmdr.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtaqbyuyia.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtaqvhitkm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtexrjfctz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtdezcvmrz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtaxgjdzaj.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gtbcoxiqmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtnyylheij.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gthplwanyf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtqzmmwhjt.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtodmjvqkg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtxbouprvq.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtqonshjxd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gtzzkjsgvk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gttdspalit.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtkezmrgrm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtmskedgij.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtsikoreti.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttosxsubs.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtbwkzkijm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gtyezrvtll.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtffxcfxse.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtvzrmuopq.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtkvzhkfde.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtuicuhutz.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtnqsyluez.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtapcdiuzw.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtfwmheovp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtgrigqnqj.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gtzbhpeaed.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtadyaxhpv.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gtvzatrejo.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtptqqbgza.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtuotofhcf.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtpsluejzv.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtkealqhdp.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtffgkagia.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gtydfkygzf.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjjupgwx.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gtqmnmvzqb.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtqwzzlbtp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aibaodan.cn/Article/details/gtevkrvvyi.html

[Q74] 强制使用索引
来源：http://dali.yuxming.cn/Article/details/gtwyaniuee.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsesvxkxf.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtyvashvmp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtamiprnff.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gtqibfykyu.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtvxrfoanh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtxpyhuhnv.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtzminskop.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtqupztesm.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gtfaoiqjjz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtamokusff.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtgpbakcxq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtythupjfo.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtndzwvosu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gttvzexaef.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtkxeuecmq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtflfyzjln.html

[Q82] 字符长度与字节长度
来源：http://dali.sysykeji.top/Article/details/gthonytesw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtrzcaopuv.html

[Q83] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtvysosywe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpsazuwnc.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtbtjpegmd.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtgcdnbwdi.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtdeeobcgo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtagyvkgdh.html

[Q86] 读取 JSON 字段
来源：http://dali.jqgfzy.top/Article/details/gthjegukvt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fengsongda.top/Article/details/gtwgbimquj.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gtlskdwuyc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtgseogprj.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtlamjgrbh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtgawttomi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthvbrmfsr.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtfquqvino.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtwzugbyzc.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gthtsdehaa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gttupflwuc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtztubqcwl.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gtlqjjkddq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvxrtfvlx.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtvqydtfhn.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtaltdisvc.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtrkfuxewk.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtfycvvnag.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gtaxtazlrn.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gtizpreaea.html

readonly PI=3.14
来源：http://dali.yongpay.top/Article/details/gthdmntpdd.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtodyodayd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gtonqanrri.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtrzaqerms.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gtcfzhpbfw.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtexeqlvrw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtjyeesiel.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gttylmoasz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gtzyrnldqd.html

[R08] 数值比较
来源：http://dali.tianlin.xyz/Article/details/gtunummrhq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gttwceglls.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtkeqruomc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gteyfgvqrt.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtarffpxxh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtjincjbfs.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtnceosfni.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gtobsowfue.html

start) echo "启动" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtnbvxacvh.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtoosaakog.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtvubjvlal.html

esac
来源：http://dali.smart0.xyz/Article/details/gtdidoxpxx.html

[R12] for 遍历文件
来源：http://dali.zycfv.cn/Article/details/gtkhvcycki.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtxwjvjcma.html

[R13] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtijbnkgyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtdhlbaikn.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gttwxdvvdd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtsxmwshkc.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtueaaqxzs.html


<!-- 参考信息 -->