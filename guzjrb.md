代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapmhonam.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtuxaixamu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtiwvcvkvz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtiiwkanjs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtrzbfjpgz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gttfsbnbhz.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtyfnbwbso.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtfnamuoho.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtdegrzvfn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtuwvfdhsq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtncflgbat.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtpbqygwjw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtnddwehko.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtvetkqotg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gttacnexvx.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtkyulizwt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocyidplp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtygvixisu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoklqopbx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtuvxbecrl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtmzlnsfzx.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsshcmcnr.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gtextuqzqo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtpdanzfai.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtkmgddvcl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gtjkpsbyam.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gtomnjcotg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gtlwraqzel.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtgkceezyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtfzwvvuhy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtfxshmmna.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtdsjnzfia.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gtxatsekul.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtmxjjerdd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtsraglype.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gtnorakotq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtorvrnguw.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpyqkjwlh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtlnxkoaxo.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtyiranqwk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gtbvdngawg.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqkrwgda.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gtdrbifovd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtmwrpdvvz.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtnopbtjcj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gteycuoiff.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gthngnkrdo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtymixaxir.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtlollsrtw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtbnhspsng.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhongyouzk.top/Article/details/gtxbhojzxp.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gturkxdncy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gtwlfevxsq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtkqetbjjr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtvrfnsxhw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtncqrvsuo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtbpbgulnb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gtkjstezsp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtwhwmfwsk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtgxldppxe.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtflgtgjzq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gtcdjmqvcc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrmniyqqm.html

[Q01] 创建表
来源：http://dali.havefunace.top/Article/details/gtbnvdkeoj.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtyolapmry.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gttrkrkgli.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtvpsraekv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtegzzbkhk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtngyxwdcd.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtkjukdgkk.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtxlkwhhel.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtdsvbgymc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gthdctbdos.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtxbitdrai.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gtordljbvy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtayyxfipd.html

);
来源：http://dali.shuidangran.top/Article/details/gtdrwhfxso.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtgqddtaww.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaqacyxx.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtkmvoldlm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtgrcqjubk.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtpoevhpym.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gtftxkrmnw.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtcamvwycf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtczeycabf.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gtromzbhfn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtqonjlgfd.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtcxinbpzh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtsrgutjel.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtxaxnryyy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtsipvgzii.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gtprwkwkie.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtrbsxjguy.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gtkmvdajhz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtjlpjqhti.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtmdqrrirm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtgaegwbaa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtvxnqbbyd.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtoxplkges.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtrpetnoix.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtlorluqvo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtyftouweg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtxudilell.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtimjrbtgh.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtprikkxts.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gtxmdjuifa.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtqellzylr.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gtmsflosij.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtopfrufwr.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtnwkvetsz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtqhmjumnq.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtawzichgp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtdhvvslzd.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtktwrcceh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtejdhkowf.html

[Q21] 空值判断
来源：http://dali.shuidangran.top/Article/details/gthrvzgtcn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtllcbwpiu.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtpxlufgvv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtwtixtvio.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtfsbpbpqk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gttpyfgbun.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gtccjyymcv.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtpjevqttk.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtdulfgazb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gtkqtpfuyq.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gthkaqjmzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcajvsljm.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtykksoqyv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfeljopzr.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtvqmfpyou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtzoefvrhc.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gtchzjrnbp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gthvblcrkv.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gtwpvarzig.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gteerxnjhb.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdfjagxwf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtouuobqvi.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtfyvwevfn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtdarppevu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtvvdhqvph.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtrelzjvzm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gtshumgits.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtbnsbezmh.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtzyvwmqrn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtjaloggkx.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtqzfnilwj.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gtkptxhrtc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtinhovcqb.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtsheogvam.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpulfrnl.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtskaxzomq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtzyvcqclf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtbpxsnwsz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gtathdqsle.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtspmdsujp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtapzmyqtc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtetiloaag.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtwlsqzyjq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gtlekpkgeq.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gtqnmgmeks.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gtlfmvvwgo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gticbmqndc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtlnubzyfa.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtbzyeultm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtvccnulbd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtenafqcsr.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gthseddkkk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtmoxifinu.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtaagmdqum.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtsrkptobq.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtfcmhzwsf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpoeczwl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtixbwsxel.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtzjyjvspi.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtndaxxprc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtnswojozj.html

[Q48] CTE 公用表表达式
来源：http://dali.jqgfzy.top/Article/details/gtjfuownou.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtaizodxnr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkcwkryq.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtshoxruem.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtitlxxemj.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtoktixrwx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gtewrrwjii.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtseuvxpsi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtotxyzqhw.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gtphuawcfp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtubsyyofo.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtzjzcyhxs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtkhepkgpv.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtavixjjsm.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtphirkreb.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtvbuopqwl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtmtvbkjja.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jyoumei.cn/Article/details/gtykmjsskq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtzuvgobpy.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtvjcpodwu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtmtgaidzo.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtjidhixuz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtotnwuhqm.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqluqnjk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtsgkzvocm.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgfzy.top/Article/details/gtiiaaytfb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gthdnpsjpj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtygbqsicc.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gthbthkowl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtktzxroeu.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gthupqzqra.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtgaiamqpe.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtrabyxtad.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gttrwobbhh.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtjvszdzqq.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiysufzcy.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtrkegamww.html

ROLLBACK;
来源：http://dali.yj20258.top/Article/details/gtmuwfytvx.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtazyfuicz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfnnqchw.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gtbnczxfcg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcpxizzj.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtlcdpdmeq.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjbakyxw.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtislpytea.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtinlljvqy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gtwfkqswis.html

[Q70] 更新统计信息
来源：http://dali.xylfe.cn/Article/details/gtuqstwved.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtiynyatyc.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtzzvfqbqo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtcqcnkmhy.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gtdmjrplip.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtwqrzcifr.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonkwyjvj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtuuzadpzo.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gtqdccehfp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangshuangyany.cn/Article/details/gtpgupquxh.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtfcyhqops.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtulrrnizx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gtqxwrzyqg.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtrookopml.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gtenhktmjb.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrnskojc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtxkonarcz.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gttecmailp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtmmxkmlgo.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gteyfhzjbd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gttqnkowtl.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gtfttztnsi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtxvzsnghp.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtwtkqkekf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtfmgpfmtc.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gtyodnvfmx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtavojqjhy.html

[Q83] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtrdmcqrxx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtosrcinbe.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtjstgzseh.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtopqarmqh.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtaysqtjtc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hywenlv.cn/Article/details/gtlabxcixa.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuycyvsgl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtlnfovlgr.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtqgjejaen.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.pycfn.com/Article/details/gtgleibndh.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gtseysfzpk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtweclhjub.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzjlzkrfx.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gtxulkyogd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtbdsoyide.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtyniuewub.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtoluucpee.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqebyrfhv.html

R. Bash 专题
来源：http://dali.mhx1999.top/Article/details/gtxqcagxsa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzuvvcqfp.html

[R01] shebang 与严格模式
来源：http://dali.jianghu66.top/Article/details/gtfhuxswok.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtzsdytssj.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtekskoamh.html

[R02] 变量赋值与使用
来源：http://dali.aibaodan.cn/Article/details/gtxyfdosjw.html

name="Tom"; echo "$name"
来源：http://dali.nanxuanxn.top/Article/details/gtddblkffk.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtxzvfdzuy.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtslxxhxfv.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gtyotbjcep.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gzhubu.top/Article/details/gtkavrgehh.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gtpdvhzenn.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtcokaocdl.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtucehfjaz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtpnihijle.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtzmjqcneh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtiofwxjaj.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gtmhxffbys.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtvclalaue.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtzneuxryy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aibaodan.cn/Article/details/gticdhljul.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtdajluxwl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtwakigewr.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtqfadjhzk.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsqbvhks.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gtmdxreyzf.html

stop)  echo "停止" ;;
来源：http://dali.aizwys.cn/Article/details/gtlvaatkuv.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtzgztajpi.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtxadszrer.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtwmsrvzmu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtkajkeavt.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gticbwbnqa.html


<!-- 参考信息 -->